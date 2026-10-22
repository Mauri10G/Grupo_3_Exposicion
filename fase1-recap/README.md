# Fase 1 · Resumen para conectar con la Fase 2

En la Fase 1 diseñamos en papel digital el **Asistente IA** del módulo de observaciones del Usability Test Dashboard 2.0.

Historia de usuario de partida: *Como evaluadora, quiero escribir las observaciones de una prueba y recibir borradores de historias de usuario con criterios de aceptación y severidad, para editarlos y exportarlos sin redactarlos a mano.*

## Requisitos

| ID | Requisito |
|---|---|
| R1 | Escribir las observaciones de la prueba en texto libre |
| R2 | Generar borradores de historias de usuario con criterios de aceptación y severidad |
| R3 | Revisar los borradores generados por la IA |
| R4 | Editar el contenido de cada borrador antes de exportarlo |
| R5 | Exportar los borradores a Markdown o PDF |
| R6 | Informar un error cuando la IA no responde correctamente |

## Piezas

| Pieza | Imagen |
|---|---|
| Sitemap, con 3.1 Asistente IA bajo 3.0 Observaciones | `sitemap.png` |
| User flow con rama de error | `userflow.png` |
| Wireframe A, Asistente IA en reposo | `wireframe_a.png` |
| Wireframe B, borradores generados | `wireframe_b.png` |

## Cómo pasa a la Fase 2

| Fase 1 | Fase 2 |
|---|---|
| Wireframe A, reposo | Pantalla `#/asistente` |
| Wireframe B, borradores | Pantalla `#/borradores` |
| Estados del botón Generar con IA | Siete estados en `estilos.css` |
| Rama de error del user flow | Mensaje de error con Reintentar |
| Seis transiciones de navegación | Rutas por hash en `app.js` |

Los informes de la Fase 1 y de la Fase 2 deben decir quinto nivel, paralelo B.
