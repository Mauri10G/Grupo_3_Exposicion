# Grupo 3 · Exposición IHC · APE 4 Fase 2

**Técnicas y herramientas de prototipado**
Asignatura Interacción Humano-Computador · Carrera de Software · UTA · Ciclo julio a diciembre 2026 · Quinto nivel, paralelo B
Docente: Ing. José Caiza, Mg.

Fechas de exposición: **jueves 22/10/2026** y **martes 27/10/2026**, en total 1 h 40 min repartida en dos sesiones de unos 50 minutos.

## Integrantes y bloque

| Integrante | Bloque | Carpeta |
|---|---|---|
| Chicaiza Chango Eduardo Josué | 1 · Fundamentos del prototipado | `expo/eduardo/` |
| López Yantalema Erick Alexander | 2 · Técnicas y herramientas | `expo/erick/` |
| Carvajal Jaya Juan José | 3 · Del wireframe al prototipo y prueba cognitiva | `expo/juan/` |
| Guevara López Oscar Mauricio | Apertura, cierre y Kahoot | `expo/mauricio/` y `kahoot/` |

## Qué es este repositorio

Es el material de nuestra exposición y la evidencia del APE 4. Partimos de la Fase 1, los wireframes del Asistente IA del proyecto **Usability Test Dashboard 2.0**, y los convertimos en un **prototipo navegable en HTML** que probamos con compañeros y corregimos.

Evidencias pedidas en la matriz de planificación:

1. Prototipo navegable: `prototipos/navegable/v1/`
2. Registro de prueba: `prueba-cognitiva/`
3. Versión corregida: `prototipos/navegable/v2/` (se agrega después de la prueba)
4. Conclusiones del APE 4: `expo/<nombre>/conclusion-<nombre>.md`

El detalle de cómo cada parte responde a la guía está en [`docs/vinculacion-guia-ape4.md`](docs/vinculacion-guia-ape4.md).

## Estructura

```
.
├── README.md
├── CONTRIBUCIONES.md
├── index.html                 redirige al prototipo
├── docs/                      guion, decisiones, vinculación con la guía, mapa de navegación
├── expo/
│   ├── mauricio/              apertura, cierre y guion de cierre
│   ├── eduardo/               bloque 1
│   ├── erick/                 bloque 2
│   ├── juan/                  bloque 3
│   └── conjunto/              diapositivas del jueves completas
├── kahoot/                    preguntas del jueves y del martes
├── prototipos/navegable/      prototipo HTML, versión 1
├── prueba-cognitiva/          plan, guion, hoja de observación y registro
├── fase1-recap/               resumen de la Fase 1 con sus imágenes
└── bitacoras/                 una bitácora por integrante
```

## Ver el prototipo

- En línea, si está activo GitHub Pages: `https://mauri10g.github.io/Grupo_3_Exposicion/prototipos/navegable/v1/`
- Sin internet: abrir `prototipos/navegable/v1/index.html` con doble clic. No necesita instalar nada.
- Modo observador para la prueba: tecla **F2**, o agregar `?observador=1` a la dirección.
- Forzar el error de la IA: agregar `?fallo=una` o `?fallo=siempre`.

Las respuestas de la IA del prototipo son simuladas. No se llama a ningún servicio externo.

## Cómo trabajamos en git

Cada integrante sube su propio paquete desde su cuenta, en su propia rama, y no se tocan archivos ajenos. Los pasos están en el `LEEME.txt` de cada zip. Resumen:

1. Aceptar la invitación al repositorio.
2. Clonar, crear la rama `aporte/<nombre>` y copiar el contenido del zip.
3. Commit, push y Pull Request hacia `main`.
4. Otra persona del grupo revisa y aprueba antes de unir.

Plantilla de Pull Request: `.github/PULL_REQUEST_TEMPLATE.md`.
