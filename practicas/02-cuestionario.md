
### Preguntas de Investigación y Desarrollo (I+D)

1.  **Optimización de la generación de código mediante herramientas CASE:** ¿Cómo facilita el uso de herramientas como **StarUML** la transición del diseño dinámico a la implementación real en **C#**, y qué ventajas ofrece la generación automática de esqueletos de clases frente al picado de código manual?.

2.  **Desacoplamiento de la Interfaz de Usuario (UI) en la lógica de negocio:** Analiza por qué la **abstracción del caso de uso** y su independencia de la interfaz son críticas para el desarrollo multiplataforma. ¿Cómo afecta el redactar narrativas sin mencionar elementos de UI (como "botones") a la escalabilidad del sistema?.

3.  **Refactorización de patrones "Anti-Gestionar" en sistemas complejos:** Investiga cómo la descomposición de un caso de uso genérico como **"Gestionar Productos"** en acciones atómicas (Eliminar, Actualizar, etc.) mejora la definición de **Requisitos Funcionales (RF)** y facilita la creación de métodos específicos en el diagrama de clases.

4.  **Gestión de estados complejos mediante el Patrón State vs. Enumerados:** Compara la implementación del ciclo de vida de un objeto (como un "Pedido") utilizando un simple **enum** frente al **Patrón de Diseño State** en C#. ¿En qué escenarios de I+D es preferible una estructura sobre la otra para mantener la coherencia del sistema?.

5.  **Impacto de las Reglas de Trazabilidad en la reducción de deuda técnica:** ¿De qué manera el cumplimiento estricto de la **"Regla de la Existencia"** (donde cada mensaje en secuencia debe ser un método en clases) previene la aparición de "Código Espagueti" y métodos huérfanos durante la fase de desarrollo?.

6.  **Modelado de interacciones con sistemas externos y APIs:** Tomando como base el ejemplo de **PayPal**, investiga los desafíos de diseñar flujos de secuencia donde un **Actor Externo** tiene el control de una parte del proceso. ¿Cómo deben gestionarse las excepciones técnicas cuando la API externa no responde según lo previsto en la narrativa?.

7.  **Automatización de la documentación técnica con Mermaid:** Evalúa la eficiencia de utilizar **Mermaid** como herramienta de "Diagram as Code". ¿Cómo mejora la mantenibilidad de la documentación de comportamiento el hecho de que los diagramas de secuencia y estados se almacenen en archivos de texto simple (Markdown)?.

8.  **Formalización de flujos de excepción y puntos de retorno:** En el diseño de sistemas críticos, ¿cómo influye la definición precisa de los **puntos de retorno al flujo principal** en las excepciones de un caso de uso para evitar estados inconsistentes en la base de datos?.

9.  **Validación de lógica de negocio mediante Guardas y Acciones:** Investiga cómo las **Guardas [condición]** en los diagramas de estados y de secuencia se traducen directamente en **sentencias IF** en C#. ¿Cómo asegura esta correspondencia que el software respete las reglas de negocio definidas en la fase de análisis?.

10. **Implementación de operaciones CRUD mediante Diagramas de Interacción:** Explora el flujo técnico de un repositorio (como `ProductoRepository`) al ejecutar una operación de **GetById o Update**. ¿Cómo ayuda el uso de fragmentos **ALT** y **mensajes de retorno** a visualizar la lógica de manejo de errores antes de la codificación?.

