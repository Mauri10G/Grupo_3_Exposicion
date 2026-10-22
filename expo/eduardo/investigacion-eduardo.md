# Investigación · Fundamentos del prototipado

Responsable: Eduardo Chicaiza  
Asignatura: Interacción Humano-Computador · APE 4, Fase 2

## Ideas clave para dominar el tema

### 1. ¿Qué es un prototipo?

Es una representación parcial de una solución que se utiliza para **explorar una idea, comunicarla y evaluarla** antes de invertir en su desarrollo completo. No tiene que incorporar todas las funcionalidades del producto. Su utilidad depende de la pregunta que queremos responder, no de cuánto se parece al sistema terminado.

**Aplicación al grupo:** interesa averiguar si una evaluadora puede introducir observaciones, generar borradores de historias de usuario, revisarlos, editarlos y exportarlos; también cómo responde la interfaz cuando falla la generación.

### 2. Wireframe, mockup y prototipo

| Recurso | Enfatiza | Ejemplo del proyecto |
|---|---|---|
| Wireframe | Estructura y jerarquía de elementos | Pantallas A y B diseñadas en la Fase 1 |
| Mockup | Apariencia: colores, tipografía y distribución visual | Representación visual con el estilo del Dashboard |
| Prototipo | Secuencia de uso, estados y respuestas | Flujo navegable del Asistente IA construido en HTML |

En nuestro ejemplo, los wireframes y el mockup son estáticos. La interactividad depende de cómo se construya cada recurso; no es una prohibición inherente al nombre.

### 3. Niveles y aspectos de fidelidad

- **Baja:** bocetos y cajas esquemáticas. Permite discutir si la información está bien organizada.
- **Media:** pantallas y contenido más definidos, con navegación básica. Ayuda a evaluar si se comprende el recorrido.
- **Alta:** apariencia y/o respuestas próximas a la experiencia prevista. Facilita revisar textos, mensajes, errores y decisiones detalladas.

Para **nuestro análisis** se distinguen tres aspectos de fidelidad: visual, contenido e interacción. No necesariamente tienen el mismo grado. El prototipo v1 reproduce la apariencia y los textos de la interfaz, mientras que la interacción está concentrada en un único flujo y la generación de IA es simulada.

**Precisión bibliográfica:** Houde y Hill (1997) proponen otro enfoque, centrado en el **rol**, la **apariencia y experiencia (look and feel)** y la **implementación** del producto. No debemos presentar los tres aspectos de nuestra lámina como una cita literal de ese modelo.

### 4. Prototipo horizontal y vertical

- **Horizontal:** presenta muchas secciones o funciones, pero con un detalle limitado en cada una. Permite explorar la extensión del sistema.
- **Vertical:** desarrolla con mayor profundidad una sola capacidad o un conjunto reducido de tareas.

**Elección del grupo:** prototipo vertical del Asistente IA. El resto de las opciones del Dashboard mantienen el contexto visual, pero no se consideran funcionalidades terminadas.

### 5. Desechable y evolutivo

- **Desechable:** se construye para resolver preguntas de diseño y la implementación se puede reemplazar al terminar la evaluación.
- **Evolutivo:** se mejora progresivamente y parte de su implementación se conserva para el producto.

**Aplicación:** la lógica que simula la IA es desechable. Los hallazgos de las pruebas, los textos de interfaz y las decisiones de diseño sí pueden reutilizarse. La exportación a Markdown es una descarga real; la opción PDF está simulada en la versión planteada por el grupo.

### 6. Errores que debemos evitar

- Construir un prototipo sin precisar qué queremos evaluar.
- Invertir demasiado tiempo en detalles estéticos antes de comprobar el flujo.
- Tratar un prototipo como si fuera un producto listo para producción.
- Dejar la primera prueba para el final, cuando cambiar decisiones puede ser más costoso.

La comparación de «minutos, horas y días» de la presentación es **ilustrativa**, no un resultado medido de este proyecto.

## Cómo se relaciona este bloque con la guía APE 4

El bloque explica por qué se utilizaron los wireframes de la Fase 1 para plantear un prototipo navegable, y justifica el nivel de fidelidad y el alcance elegidos. Se vincula principalmente con los pasos **1 (revisar wireframes)** y **2 (generar un prototipo con elementos de interacción)** de `docs/vinculacion-guia-ape4.md`. La conclusión individual contribuye al paso **4**.

## Referencias consultables y verificación bibliográfica

1. Houde, S. y Hill, C. (1997). *What do prototypes prototype?* En *Handbook of Human-Computer Interaction* (2.ª ed., pp. 367–381). https://doi.org/10.1016/B978-044481862-1.50082-0. **Datos editoriales y resumen verificados**; se usó su enfoque general sobre la finalidad del prototipo.
2. Nielsen, J. (1993). *Usability Engineering*. Academic Press. https://www.nngroup.com/books/usability-engineering/ . **Ficha bibliográfica verificada**; no se atribuyen citas textuales ni contenido de capítulos no consultados.
3. Granollers i Saltiveri, T., Cañas Delgado, J. J. y Lorés Vidal, J. *Diseño de sistemas interactivos centrados en el usuario*. Editorial UOC. https://www.editorialuoc.com/diseno-de-sistemas-interactivos-centrados-en-el-usuario . **Existe edición digital en PDF de 2012** (la obra tiene ediciones anteriores); especificar la edición que se utilice en el informe final.
4. Shneiderman, B. y Plaisant, C. (2006). *Diseño de interfaces de usuario: estrategias para una interacción persona-computadora efectiva* (4.ª ed.). Pearson. **Ficha de catálogo verificada**: https://www.biblioeco.unsa.edu.ar/webbibeco/index.php?id=15189&lvl=notice_display .

**Base del ejemplo aplicado:** diapositivas `jueves-bloque1-eduardo.pptx`, resumen `fase1-recap/README.md` y decisiones del grupo en `docs/decisiones.md`. Las descripciones de las funciones son el alcance previsto por el equipo; la verificación práctica corresponde a la demostración del prototipo.
