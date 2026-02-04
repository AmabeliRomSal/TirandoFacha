---
title: descTF
---

# ~~Requerimientos~~ Descripción de Tirando Facha

## Registro mediante formulario

En las **opciones de ingreso: textual y formulario**

- El formulario se abrirá mediante un botón en la aplicación **especificar dónde**.
- Al seleccionar el botón, se moverá a otra pantalla (activity) donde se preguntará al usuario mediante un listado de opciones los siguientes parámetros: **categoría de prenda, textura, densidad, uso, antiguedad**.

---

### Categoría de prenda

Qué tipo de prenda es (blusa, camisa, pantalón...).

### Textura

Cómo es/se siente la estructura de la tela (peluche, suave, rugoso).

### Densidad

Qué tan gruesa/delgada es la tela de la prenda (en promedio).

### Uso

En este caso, **se utilizará la misma técnica de ingreso para tiempo**.

### Antiguedad

Cuántas semanas/meses/años tienes con esa prenda.

---

- > RQNF: Todos los campos se deben llenar con algunos de los filtros desplegados como opciones.

### Campo Antiguedad

- Habrá un botón/switch para especificar si la prenda es completamente nueva, haciendo que los campor a ingresar del tiempo se desactiven (en el código, tiempo=0).
- La estructura básica de la sección antiguedad es: un **switch** (prenda nueva o usada?), **inputs de texto** (para tiempo) (con sus descriptores, y formato en semana/meses/y años) (> RQNF: si se ingresa 0 en todos los campos, la prenda se cuenta como nueva), y un **botón de "Ingresar"**.

### Campo Uso

- > RQNF: La opción de uso solo se puede llenar si la prenda no se considera nueva.
- La estructura básica de la sección uso es: **inputs de texto** (para tiempo) (con sus descriptores, y formato en días/y semanas) (> RQNF: si se ingresa 0 en todos los campos, se solicitará (mediante un Toast) que ingrese números válidos, RQNF2: si no, se desactivará el **botón de "Ingresar"**).

> Ambos **Antiguedad** y **Uso** se desplegarán junto con las demás opciones, utilizando un **ExpandableLayout**.

### Campo Densidad

- Se compone solamente de un menú de opciones (dropdown menu), con descriptores sobre el grosor de la prenda (**ver si hay una lista predeterminada, sino escribirla**).

**Lo mismo aplica para los campos de Textura y Categoría de prenda**.

---

## Reglas de ingreso

### Diferencias entre **Ingreso textual** Vs **Formulario**

#### Textual

Éste es un nombre redundante. En realidad también se ingresan los símbolos.

Es una sección donde se ingresan las instrucciones de lavado mediante **seleccionables** (osea, frases cortas que se deben seleccionar).

- > RQNF: Los seleccionables que elija el usuario no deben contradecirse.

También se pueden seleccionar **símbolos** en vez de texto para cada una de las 5 secciones.
Primero se debe dar la opción de seleccionar **estándar 1 o 2**.

- > RQNF: Los símbolos que eliga el usuario no deben contradecirse.
- > RQNF: No se puede utilizar seleccionables y símbolos al mismo tiempo, >RQNF2: debe haber un **switch** que haga al usuario elegir entre seleccionables o símbolos.

Por último, la manera textual se utiliza tomando en cuenta que **la prenda tiene una etiqueta**.

#### Formulario

Éste se utiliza como un último recurso, donde el usuario aproxima seleccionando las opciones en ésta lo que haría la etiqueta.

