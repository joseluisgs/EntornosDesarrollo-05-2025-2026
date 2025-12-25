### Cuestionario de Diagramas de Comportamiento UML

**1. ¿Qué aspecto del software modelan los diagramas de comportamiento?**
A) La estructura estática y los atributos de las clases.
B) El esqueleto y las relaciones permanentes del sistema.
C) El proceso vivo, la lógica y los cambios de estado.
D) La organización de los archivos en el servidor.

**2. En la analogía del coche, ¿qué representaría el diagrama de comportamiento?**
A) El plano del motor y las ruedas.
B) El manual de conducción y el flujo del combustible.
C) El inventario de piezas del vehículo.
D) El color y el modelo del coche.

**3. ¿Cuál es uno de los beneficios de modelar el comportamiento antes de programar?**
A) Aumentar la cantidad de líneas de código.
B) Evitar el "Código Espagueti" y detectar errores de flujo.
C) Sustituir completamente la fase de programación.
D) Diseñar la interfaz gráfica de usuario (UI).

**4. ¿Qué representa un "Mensaje" en UML?**
A) Un correo electrónico enviado al administrador.
B) Una llamada a un método entre dos objetos.
C) Una notificación push en el navegador.
D) Una entrada en la base de datos.

**5. ¿Qué herramienta se recomienda para generar diagramas profesionales mediante código simple?**
A) Photoshop.
B) Excel.
C) Mermaid.
D) Word.

**6. ¿Cuál es el propósito principal del Diagrama de Casos de Uso?**
A) Mostrar cómo se implementan los métodos en C#.
B) Visualizar qué hará el sistema desde el punto de vista del usuario.
C) Definir las tablas de la base de datos.
D) Modelar el ciclo de vida de un objeto.

**7. ¿Cómo se representa un Actor en la notación estándar UML?**
A) Un óvalo.
B) Un rectángulo.
C) Un "muñeco de palo" (Stick Man).
D) Una línea discontinua.

**8. ¿Qué tipo de nombre debe llevar siempre un Caso de Uso?**
A) Un sustantivo abstracto.
B) Un verbo en infinitivo.
C) El nombre de un actor.
D) Una dirección IP.

**9. ¿Qué define el "Límite del Sistema" en un diagrama de casos de uso?**
A) Qué funciones están dentro de la aplicación y qué actores son externos.
B) La cantidad de memoria RAM que usará el software.
C) El tiempo máximo de respuesta del servidor.
D) El número de usuarios que pueden conectarse.

**10. Según las fuentes, ¿cuál de los siguientes es un Actor válido?**
A) La base de datos propia del sistema.
B) El teclado o el ratón.
C) Un sistema externo como la API de PayPal.
D) El programador que mantiene el código.

**11. ¿Por qué se considera un error usar el nombre "Gestionar Productos" en un caso de uso?**
A) Porque es un nombre demasiado corto.
B) Porque no es un requisito funcional atómico y es poco específico.
C) Porque no contiene un verbo.
D) Porque los productos no se pueden gestionar.

**12. En una relación de tipo `<<include>>`, ¿cuál es la lógica principal?**
A) El caso de uso base es opcional.
B) El caso de uso base no puede existir sin llamar obligatoriamente al otro.
C) El actor decide si ejecuta la relación o no.
D) Se utiliza para modelar errores técnicos de hardware.

**13. ¿Hacia dónde apunta la flecha en una relación de `<<extend>>`?**
A) Del caso de uso base al caso de uso opcional.
B) Del actor al caso de uso.
C) Del caso de uso opcional al caso de uso base (hacia atrás).
D) Siempre hacia el límite del sistema.

**14. ¿Cuál de los siguientes ejemplos NO es un caso de uso válido según las fuentes?**
A) "Hacer un bucle FOR".
B) "Pagar Factura".
C) "Actualizar Perfil".
D) "Generar Reporte".

**15. ¿Qué significa que un Caso de Uso sea "agnóstico a la interfaz"?**
A) Que solo funciona en dispositivos móviles.
B) Que no debe mencionar elementos de UI como "botones" o "hacer clic".
C) Que debe incluir el diseño de los colores de la web.
D) Que requiere obligatoriamente una pantalla táctil.

**16. ¿Cómo deben redactarse las Precondiciones en una narrativa de caso de uso?**
A) En tiempo futuro.
B) Como una pregunta al usuario.
C) Siempre en pasado, indicando que ya han sucedido.
D) En lenguaje de programación C#.

**17. ¿Qué es una Postcondición?**
A) Un error que ocurre al inicio del proceso.
B) La garantía de éxito y cómo queda el sistema tras la acción.
C) Una condición que el usuario debe elegir opcionalmente.
D) El nombre del programador que hizo el diseño.

**18. En el control de flujo de excepciones, ¿qué significa un "retorno al flujo principal"?**
A) Que el sistema se apaga.
B) Que el actor vuelve a un paso exacto del flujo tras corregir el error.
C) Que el caso de uso termina sin éxito.
D) Que se reinicia la base de datos.

**19. ¿Qué modela principalmente el Diagrama de Secuencia?**
A) La estructura de las carpetas del proyecto.
B) La lógica de ejecución y el orden temporal de los mensajes entre objetos.
C) Los estados físicos de un servidor.
D) La relación jerárquica entre empleados de una empresa.

**20. ¿Qué representa la "Línea de Vida" en un diagrama de secuencia?**
A) La duración de la batería del dispositivo.
B) Una línea vertical discontinua que representa la existencia de un objeto.
C) El tiempo que tarda un programador en escribir una función.
D) La conexión a internet del usuario.

**21. ¿Qué símbolo representa un mensaje de retorno en un diagrama de secuencia?**
A) Una flecha sólida.
B) Una línea discontinua con flecha.
C) Una X roja.
D) Un círculo sólido.

**22. ¿Cómo se representa la creación de un nuevo objeto en UML?**
A) Con una flecha que apunta a una X.
B) Con una flecha `<<new>>` que apunta directamente al rectángulo del objeto.
C) Con un bucle LOOP.
D) Con un fragmento ALT.

**23. ¿Para qué se utiliza el fragmento "ALT" en un diagrama de secuencia?**
A) Para repetir una acción muchas veces.
B) Para representar una decisión lógica tipo if-else.
C) Para borrar un objeto del sistema.
D) Para indicar que un mensaje es asíncrono.

**24. ¿Qué fragmento se utiliza para representar bucles o repeticiones?**
A) ALT.
B) OPT.
C) LOOP.
D) BREAK.

**25. En un diagrama de secuencia, ¿qué significa una "X" al final de una línea de vida?**
A) Que el objeto ha sido creado satisfactoriamente.
B) Que ha ocurrido un error fatal.
C) La destrucción o fin de la vida del objeto.
D) Que el objeto está esperando una respuesta.

**26. ¿Qué operación CRUD se asocia típicamente con el mensaje `GetById`?**
A) Crear un nuevo registro.
B) Buscar un objeto específico, manejando si existe o no.
C) Borrar todos los datos de la tabla.
) Actualizar la contraseña del administrador.

**27. ¿Qué describe el Diagrama de Estados?**
A) Los roles de los usuarios en el sistema.
B) Los estados por los que pasa un objeto y las transiciones entre ellos.
C) La velocidad de la red en milisegundos.
D) La cantidad de objetos creados en memoria.

**28. ¿Cómo se representa el "Estado Inicial" en un diagrama de estados?**
A) Un círculo con borde.
B) Un rectángulo redondeado.
C) Un círculo sólido.
D) Un rombo de decisión.

**29. ¿Qué provoca el paso de un estado a otro en un objeto?**
A) Una Postcondición.
B) Un Evento o transición.
C) Un Actor externo únicamente.
D) La destrucción de la base de datos.

**30. ¿Qué es una "Guarda" en una transición de estado?**
A) Un sistema de seguridad contra hackers.
B) Una condición lógica que debe cumplirse para que la transición ocurra.
C) El nombre del estado final.
D) Una copia de seguridad de los datos.

**31. ¿Cuál es un ejemplo de estado para un objeto "Pedido"?**
A) "Hacer clic".
B) "Pendiente de pago".
C) "Usuario".
D) "Base de Datos".

**32. ¿Qué es un "Estado Compuesto" o sub-estado?**
A) Un estado que contiene otros estados dentro de él.
B) Un estado que pertenece a dos clases diferentes.
C) Un estado que nunca termina.
D) Un estado que no tiene nombre.

**33. ¿Qué garantiza la "Trazabilidad" entre diagramas?**
A) Que el sistema sea más rápido.
B) Que el diseño de estructura, comportamiento y estados sea coherente entre sí.
C) Que no sea necesario escribir documentación narrativa.
D) Que el código se genere solo sin intervención humana.

**34. ¿Qué dice la "Regla de la Existencia" (Clases -> Secuencia)?**
A) Que todos los actores deben ser humanos.
B) Que si un objeto envía un mensaje en Secuencia, debe ser un método público en Clases.
C) Que los objetos no necesitan estar definidos en el diagrama de clases.
D) Que solo se pueden usar tres clases por diagrama.

**35. Según la "Regla del Estado", ¿dónde debe verse reflejado un cambio de estado?**
A) En el color de la interfaz.
B) En un atributo (normalmente un enum) dentro de la clase correspondiente.
C) En el nombre del actor principal.
D) En la licencia del software.

**36. ¿Qué representa cada línea de vida en un diagrama de secuencia según la "Regla de la Participación"?**
A) Una línea de código en C#.
) Una instancia de una clase definida en el diagrama de clases.
C) Un requisito funcional del cliente.
D) Un minuto de ejecución del programa.

**37. Si en el diagrama de secuencia aparece el método `ValidarDescuento()`, pero no está en el diagrama de clases, ¿qué ocurre?**
A) No pasa nada, es normal.
B) Existe una incoherencia que debe corregirse añadiendo el método a la clase.
C) El programa funcionará pero más lento.
D) Hay que borrar el diagrama de secuencia.

**38. ¿Qué herramienta CASE permite generar código C# real a partir de diagramas?**
A) Mermaid.
B) Draw.io.
C) StarUML.
D) Notepad++.

**39. En UML, ¿qué indica un rectángulo sobre la línea de vida en un diagrama de secuencia?**
A) Que el objeto está destruido.
B) La activación o que el objeto está ejecutando código.
C) Un comentario del programador.
D) El nombre del servidor.

**40. ¿Cuál es la dirección de la flecha en una relación de `<<include>>`?**
A) Del caso de uso incluido al caso de uso base.
B) Del caso de uso base al caso de uso incluido.
C) Del actor al sistema externo.
D) No lleva flecha, es una línea sólida.

**41. ¿Qué campo de la narrativa de caso de uso define el identificador único (ej: CU-001)?**
A) Nombre.
B) ID.
C) Actores.
D) Descripción.

**42. ¿En qué lenguaje de programación se basan los ejemplos de implementación de los estados en las fuentes?**
A) Java.
B) Python.
C) C#.
D) JavaScript.

**43. ¿Cuál de los siguientes NO es un actor válido porque se considera que está "dentro" del sistema?**
A) Sensor de temperatura.
B) Cliente.
C) Base de datos propia.
D) Aplicación externa de mensajería.

**44. ¿Qué tipo de relación modelaría un "Pago por PayPal" respecto a un "Pago" general?**
A) Include.
B) Extend (como variante opcional).
C) Asociación simple.
D) Herencia de clases.

**45. ¿Qué sucede si una excepción es "insalvable" (showstopper) en la narrativa?**
A) Se ignora el error.
B) Se indica el fin del caso de uso sin alcanzar la postcondición.
C) El sistema se reinicia automáticamente.
D) Se crea un nuevo actor.

**46. ¿Cómo se llama el estándar de diagramado que divide los diagramas en estructurales y de comportamiento?**
A) ISO 9001.
B) UML (Unified Modeling Language).
C) XML.
D) Mermaid Syntax.

**47. ¿Qué representan las "Acciones" en las transiciones de un diagrama de estados?**
A) Lo que el usuario piensa.
B) Operaciones que se ejecutan durante el cambio de estado.
C) El nombre del archivo de configuración.
D) La velocidad del procesador.

**48. En la matriz de verificación, ¿qué debe coincidir con una "Guarda [condición]" del diseño?**
A) Un nombre de variable.
B) Una sentencia IF en el código C#.
C) El nombre de la clase.
D) La firma del autor.

**49. ¿Cuál es el propósito del diagrama de estados en un objeto "Pedido"?**
A) Ver cuántos pedidos hay en total.
B) Modelar el ciclo de vida desde que se crea hasta que se entrega o cancela.
C) Calcular el precio total de los artículos.
D) Listar los nombres de los clientes.

**50. ¿Bajo qué licencia está distribuido el contenido de las fuentes?**
A) Copyright restringido.
B) Creative Commons Reconocimiento-NoComercial-CompartirIgual.
C) Licencia MIT.
D) Dominio Público.

