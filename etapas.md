---
title: etapas
---

# Etapas para el proyecto

- Persona A: backend (líder técnico), documentación
- Persona B: Frontend 1 (UI/UX + pantallas)
- Persona C: Frontend 2 (lógica)

## Etapa 1: EN PROCESO

Planeación/Diseño

Días 1-10

| A | B | C |
|---|---|---|
| Arquitectura general + BD + lógica + documentación | Wireframes + navegación + UX | diagramas casos de uso/flujo + revisiones con B |

| Día | A | B | C |
|---|---|---|---|
| 1 | Revisar alcance proyecto | Investigar apps similares | Definir usuario objetivo |
| 2 | Definir arquitectura general | Bocetos de pantallas | Casos de uso |
| 3 | Diseño básico BD | Wireframe para Login | Diseño básico flujo de navegación entre pantallas/módulos |
| 4 | Ajustes diseño BD | Wireframe para Armario | Diagrama de flujo sistema entero |
| 5 | Documentar endpoints/URIs para proyecto | Wireframe para Formulario | Diagramas UML |
| 6 | Validar diseño final BD | Wireframe para Inicio | Revisión técnica general |
| 7 | Crear repo Github + estructura **backend** | Definir colores y tipografías/fonts | Organización de módulos/secciones **frontend** |
| 8 | Esqueleto backend | Ajustes UX | Revisión de Wireframes |
| 9 | Inicio de documentación | Prototipo visual en papel | Feedback |
| 10 | Revisión general | lo mismo | lo mismo |


## Etapa 2

Base de la app

Días 11-20

| A | B | C |
|---|---|---|
| Server/BD + seguridad + programación | Android Studio (Pantallas, UI) + ajustes diseño | lógica + configuración + integración |

| Día | A | B | C |
|---|---|---|---|
| 11 | Configurar servidor local | Crear proyecto Android | Configurar dependencias |
| 12 | Conectar BD | Pantalla Login | Lógica Login |
| 13 | Progra. registro de usuario | Pantalla Registro | Validaciones frontend |
| 14 | Progra. manejo se sesiones | UI recuperar contraseña | Lógica recuperar contraseña |
| 15 | Seguridad básica | Ajustes visuales | Integración Login-Backend |
| 16 | **Pruebas** backend | **Pruebas UI** | **Pruebas integración** |
| 17 | **Correcciones** backend | **Correcciones** UI | **Correcciones** integración |
| 18 | Optimizar código | Animaciones básicas | Estados de carga de las dependencias, BD, y app básica |
| 19 | **Testing** | lo mismo | lo mismo |
| 20 | **Versión estable** | lo mismo | lo mismo |

## Etapa 3

Armario

Días 21-35

| A | B | C |
|---|---|---|
| CRUD (BD) + programación | Android Studio + UI/UX | APIs/BD + lógica |

| Día | A | B | C |
|---|---|---|---|
| 21 | CRUD Armario | Pantalla Armario | Conexión Armario |
| 22 | **Crear*** Prenda | UI para Crear Prenda | Envío de datos |
| 23 | Estados de Prenda | Indicadores visuales | Cambio de estado |
| 24 | Categorías | UI filtros | Lógica filtros |
| 25 | Fotos de prenda | Vista previa de las fotos de prenda | Subir imagen |
| 26 | (**Ver**) Historial de uso | UI para Historial | Registro de uso |
| 27 | Contadores | Visualización | Actualización automática |
| 28 | Validaciones | Ajustes UX | Manejo de errores |
| 29 | **Pruebas Armario** | lo mismo | lo mismo |
| 30 | **Correcciones** | lo mismo | lo mismo |
| 31 | Optimización consultas | Detalle de prenda | Integrar Detalle de prenda |
| 32 | **Eliminar** prenda  | UI Confirmaciones | Lógica de eliminación |
| 33 | **Editar** prenda | UI para Editar prenda | Lógica guardar cambios |
| 34 | **Revisión completa** | lo mismo | lo mismo |
| 35 | Armario completado | lo mismo | lo mismo |

## Etapa 4

Formulario

Días 36-55

| A | B | C |
|---|---|---|
| estructura + programación | Android Studio + UI/UX | APIs/BD + lógica |

| Día | A | B | C |
|---|---|---|---|
| 36 | Estructura Formulario | Pantalla Formulario | Conexión Formulario |
| 37 | Guardado de prenda | UI Guardado | Lógica guardar cambios **(ver día 33)** |
| 38 | Seleccionables (frases) | Selector de frases | Lógica de selección |
| 39 | Símbolos textiles | Selector de símbolos | Lógica de selección |
| 40 | Guardado temporal | UI Historial | Lógica Historial |
| 41 | Fecha de caducidad guardado temporal | Indicadores de tiempo | Eliminación automática |
| 42 | Validaciones | UI Ajustes | Manejo de errores |
| 43 | **Pruebas Formulario** | lo mismo | lo mismo |
| 44 | **Correcciones** | lo mismo | lo mismo |
| 45 | Formulario completado | lo mismo | lo mismo |

> Los días 46-55 se solapan por si aún no se completa el módulo.

## Etapa 5

Inicio + estadísticas + mascota

Días 46-65

| A | B | C |
|---|---|---|
| estructura + programación | Android Studio + UI/UX | APIs/BD + lógica + integración |

| Día | A | B | C |
|---|---|---|---|
| 46 | Datos para Inicio | UI Inicio | Integración |
| 47 | Recomendaciones | UI Tarjetas | Lógica de Recomendaciones |
| 48 | Estadísticas de uso | Gráficas | Conexión de datos |
| 49 | Datos de materiales | Visualización | Filtros |
| 50 | Lógica mascota | Diseño mascota | Estados de humor mascota |
| 51 | Reacciones mascota | Animaciones | Integración |
| 52 | **Pruebas** | lo mismo | lo mismo |
| 53 | **Correcciones** | lo mismo | lo mismo |
| 54-65 | Optimización- Inicio completado | lo mismo | lo mismo |

## Etapa 6

Lavadora

Días 66-85

| A | B | C |
|---|---|---|
| estructura + programación | Android Studio + UI/UX | APIs/BD + lógica + integración |

| Día | A | B | C |
|---|---|---|---|
| 66 | Estructura Lavadora | UI Lavadora | Integración |
| 67 | Selección de prendas | UI checklist para selección | Lógica selección |
| 68 | Peso y cargas/tandas | UI barra de progreso | Cálculo de tanda |
| 69 | Reglas de cuidado | Alertas | Validaciones |
| 70 | Historial de lavado | UI Historial | Registro |
| 71 | **Pruebas** | lo mismo | lo mismo |
| 72 | **Correcciones** | lo mismo | lo mismo |
| 73-85 | Optimización- Lavadora completada | lo mismo | lo mismo |

## Etapa 7

Clima

Días 86-95

| A | B | C |
|---|---|---|
| estructura + programación | Android Studio + UI/UX | APIs/BD + lógica + integración |

| Día | A | B | C |
|---|---|---|---|
| 86 | API Clima | UI Indicadores | Integración |
| 87 | Modelo de vida útil | Visualización | Desplegar predicción |
| 88 | Ajustes del modelo | Mensajes al usuario (notif.) | Validaciones |
| 89-95 | **Ajustes finales** | lo mismo | lo mismo |

## Etapa 8

Cierre

Días 96-100

| A | B | C |
|---|---|---|
| estructura + programación | Android Studio + UI/UX | APIs/BD + lógica + integración |

| Día | A | B | C |
|---|---|---|---|
| 96 | Optimización backend | Ajustes visuales | Búsqueda y arreglar bugs |

| Día | Todos |
|---|---|
| 97 | **Pruebas generales** |
| 98 | **Documentación final + actualización a finalizado** |
| 99 | **Presentación** |
| 100 | **Tirando Facha finalizado** |
