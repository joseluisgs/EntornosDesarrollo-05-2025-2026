- [Parte 1: Diagramas de Casos de Uso (10 Ejercicios)](#parte-1-diagramas-de-casos-de-uso-10-ejercicios)
    - [Ejercicio 1: La Tienda Online "CyberShop" (Carrito de Compra)](#ejercicio-1-la-tienda-online-cybershop-carrito-de-compra)
    - [Ejercicio 2: Gestión de Fincas "La Urbana" (CRUD Completo)](#ejercicio-2-gestión-de-fincas-la-urbana-crud-completo)
    - [Ejercicio 3: El Cajero Automático Avanzado](#ejercicio-3-el-cajero-automático-avanzado)
    - [Ejercicio 4: Sistema de Puntos de Información Universitaria (PIU)](#ejercicio-4-sistema-de-puntos-de-información-universitaria-piu)
    - [Ejercicio 5: App de Comida "Pesadilla en la Cocina"](#ejercicio-5-app-de-comida-pesadilla-en-la-cocina)
    - [Ejercicio 6: Gestión de Biblioteca Municipal](#ejercicio-6-gestión-de-biblioteca-municipal)
    - [Ejercicio 7: Red Social "FaceSpace"](#ejercicio-7-red-social-facespace)
    - [Ejercicio 8: Gestión de Calificaciones Académicas](#ejercicio-8-gestión-de-calificaciones-académicas)
    - [Ejercicio 9: Máquina Expendedora Inteligente](#ejercicio-9-máquina-expendedora-inteligente)
    - [Ejercicio 10: Clínica Veterinaria (Citas y CRUD)](#ejercicio-10-clínica-veterinaria-citas-y-crud)
- [Parte 2: Descripciones de Casos de Uso (5 Ejercicios)](#parte-2-descripciones-de-casos-de-uso-5-ejercicios)
    - [Ejercicio 11: Descripción de "Realizar Compra" (Tienda Online)](#ejercicio-11-descripción-de-realizar-compra-tienda-online)
    - [Ejercicio 12: Descripción de "Alquilar Piso" (Gestión Fincas)](#ejercicio-12-descripción-de-alquilar-piso-gestión-fincas)
    - [Ejercicio 13: Descripción de "Retirar Efectivo" (Cajero Automático)](#ejercicio-13-descripción-de-retirar-efectivo-cajero-automático)
    - [Ejercicio 14: Descripción de "Instalación de PIU" (Universidad)](#ejercicio-14-descripción-de-instalación-de-piu-universidad)
    - [Ejercicio 15: Descripción de "Poner Notas" (Calificaciones)](#ejercicio-15-descripción-de-poner-notas-calificaciones)
- [Parte 3: Diagramas de Secuencia del Sistema (10 Ejercicios)](#parte-3-diagramas-de-secuencia-del-sistema-10-ejercicios)
    - [Ejercicio 16: Comprar una Lata de Refresco](#ejercicio-16-comprar-una-lata-de-refresco)
    - [Ejercicio 17: Partida de "Las Siete y Media"](#ejercicio-17-partida-de-las-siete-y-media)
    - [Ejercicio 18: Aldeano Mina Oro (Age of Empires)](#ejercicio-18-aldeano-mina-oro-age-of-empires)
    - [Ejercicio 19: Validar Tarjeta de Crédito (TPV)](#ejercicio-19-validar-tarjeta-de-crédito-tpv)
    - [Ejercicio 20: Alquiler de Película Online](#ejercicio-20-alquiler-de-película-online)
    - [Ejercicio 21: Login en Facebook](#ejercicio-21-login-en-facebook)
    - [Ejercicio 22: Chicote evalúa un plato](#ejercicio-22-chicote-evalúa-un-plato)
    - [Ejercicio 23: Emisión de Recibo Mensual](#ejercicio-23-emisión-de-recibo-mensual)
    - [Ejercicio 24: Actualización de Software del PIU](#ejercicio-24-actualización-de-software-del-piu)
    - [Ejercicio 25: Devolución de Libro con Multa](#ejercicio-25-devolución-de-libro-con-multa)
- [Parte 4: Diagramas de Estados (5 Ejercicios)](#parte-4-diagramas-de-estados-5-ejercicios)
    - [Ejercicio 26: Ciclo de Vida de una Multa de Tráfico](#ejercicio-26-ciclo-de-vida-de-una-multa-de-tráfico)
    - [Ejercicio 27: Ciclo de Vida de una Mesa de Restaurante](#ejercicio-27-ciclo-de-vida-de-una-mesa-de-restaurante)
    - [Ejercicio 28: Estados de un Pedido Online](#ejercicio-28-estados-de-un-pedido-online)
    - [Ejercicio 29: Reloj Digital (Modos)](#ejercicio-29-reloj-digital-modos)
    - [Ejercicio 30: Lavadora](#ejercicio-30-lavadora)
- [Parte 5: Ejemplos de CRUD (Para practicar)](#parte-5-ejemplos-de-crud-para-practicar)


---

# Parte 1: Diagramas de Casos de Uso (10 Ejercicios)

*Instrucciones:* Para cada ejercicio, identifica los **Actores**, los **Casos de Uso** y las relaciones **<<include>>** (obligatorio/siempre ocurre) y **<<extend>>** (opcional/excepción). Dibuja el diagrama correspondiente.

### Ejercicio 1: La Tienda Online "CyberShop" (Carrito de Compra)

Una empresa de e-commerce necesita modelar su proceso de ventas. Cualquier usuario web puede buscar productos en el catálogo. Sin embargo, para realizar una compra, el usuario debe ser un **Cliente Registrado**. El proceso de **"Realizar Compra"** es el núcleo del sistema.
Para realizar la compra, el sistema **siempre** debe **"Verificar Stock"** de los productos. Además, durante la compra, si el cliente tiene un cupón promocional, puede **"Aplicar Descuento"** (esto no pasa siempre).
El pago se realiza dentro del proceso de compra, pero puede fallar. Si el pago es con tarjeta de crédito, el sistema conecta con una pasarela externa.
Existe un **Administrador** que puede gestionar el catálogo (CRUD de productos) y bloquear usuarios fraudulentos.

### Ejercicio 2: Gestión de Fincas "La Urbana" (CRUD Completo)

Basado en el documento . Una empresa propietaria de inmuebles necesita un sistema.

* El **Propietario** gestiona los inmuebles. Un inmueble puede ser un Edificio, un Piso o un Local. El propietario debe poder dar de **Alta**, **Baja**, **Modificar** y **Consultar** (CRUD) tanto Edificios como Pisos y Locales.
* Nota: La gestión de un Edificio puede conllevar opcionalmente la gestión de sus pisos o locales asociados.
* Existe un **Inquilino** (persona con nómina o aval). El inquilino puede **"Alquilar Inmueble"**. Esta acción puede especializarse en "Alquilar Piso", "Alquilar Local" o "Alquilar Edificio".
* Para alquilar, **siempre** es necesario **"Identificarse"**. El inquilino también puede "Desalquilar" o "Consultar sus recibos", acciones que también requieren identificación obligatoria.

### Ejercicio 3: El Cajero Automático Avanzado

Un cliente bancario se acerca a un cajero. Su objetivo principal es **"Sacar Dinero"**.
Para sacar dinero, el sistema **siempre** debe **"Validar PIN"** y **"Comprobar Saldo"**.
Si el cliente introduce mal el PIN tres veces, el sistema ejecutará la acción **"Retener Tarjeta"** (esto es una extensión de la validación).
El cliente también puede **"Realizar Transferencia"** y **"Consultar Movimientos"**. Todas estas operaciones requieren, por seguridad, **"Validar PIN"**.
Un **Técnico de Mantenimiento** puede acceder al cajero para **"Reponer Billetes"** y **"Reiniciar Sistema"**, pero requiere una autenticación especial mediante llave física.

### Ejercicio 4: Sistema de Puntos de Información Universitaria (PIU)

Basado en el documento . La universidad instala kioscos informativos.

* **Usuario Final** (Alumno/Profesor/PAS): Puede **"Obtener Información"**. Para acceder a información privada (notas, nóminas), el sistema debe **"Identificar Usuario"** obligatoriamente.
* **Administrador**: Se encarga de la **"Instalación de PIUs"**. Esto puede implicar "Instalar Nuevo PIU" o "Instalar PIU Existente" (especialización). Esta acción siempre requiere registrar la ubicación.
* **Gestor**: Se encarga del **"Control de Funcionamiento"**. Si detecta un fallo, puede (opcionalmente) **"Realizar Acciones Correctivas"** (como reiniciar).
* **Operador**: Se encarga de la **"Gestión de Red"** y ver estadísticas.
* *Nota:* Todos los actores (Admin, Gestor, Operador, Usuario) deben autenticarse para entrar a sus menús, excepto para ver información pública.

### Ejercicio 5: App de Comida "Pesadilla en la Cocina"

Basado en el documento . Chicote diseña una app para controlar el caos.

* El **Camarero** utiliza la app para **"Gestionar Comanda"**. Esto incluye anotar platos y enviarlos a cocina.
* El **Cocinero** recibe la comanda y debe **"Confirmar Elaboración"**. Si faltan ingredientes (caso excepcional), debe **"Notificar Falta de Stock"** al sistema, lo cual cancela parcialmente la comanda.
* El **Cliente** (que descargó la app) puede **"Reservar Mesa"** y, tras comer, **"Evaluar Servicio"**.
* Chicote (**Supervisor**) puede ver todas las evaluaciones y **"Despedir Empleado"** si la media baja de 2 estrellas.
* Tanto "Reservar Mesa" como "Gestionar Comanda" incluyen obligatoriamente **"Verificar Disponibilidad"**.

### Ejercicio 6: Gestión de Biblioteca Municipal

Basado en.
Un **Socio** quiere llevarse libros. El caso de uso principal es **"Realizar Préstamo"**.
Para realizar un préstamo, el sistema debe **"Comprobar Sanciones"** (si tiene multas, no puede llevarse nada).
Si el libro no está disponible, el socio puede **"Realizar Reserva"**.
El **Bibliotecario** se encarga del CRUD de Libros (Alta, Baja, Modificación, Consulta) y del CRUD de Socios.
Además, el Bibliotecario registra la **"Devolución de Libro"**. Si el libro se devuelve tarde, el sistema extiende este caso de uso con **"Imponer Sanción"**.

### Ejercicio 7: Red Social "FaceSpace"

Basado en.
Un **Usuario Registrado** entra al sistema (Login). Puede **"Publicar Contenido"**.
Puede **"Comentar Publicación"** de otros.
Puede realizar un CRUD sobre su propio **Perfil** (Modificar foto, datos, etc.).
Si el sistema detecta palabras ofensivas en un comentario o publicación, extiende la acción con **"Bloquear Contenido Automáticamente"**.
Un usuario puede **"Denunciar Usuario"**.
Un **Moderador** recibe las denuncias y puede **"Banear Usuario"**.

### Ejercicio 8: Gestión de Calificaciones Académicas

Basado en .
El **Profesor** accede al sistema. Su tarea principal es **"Rellenar Acta"**.
Para rellenar el acta, puede ir alumno por alumno. El sistema le ofrece una herramienta de ayuda: **"Usar Calculadora"** (es opcional, un `<<extend>>` de rellenar acta) para sumar parciales.
El profesor puede **"Firmar Acta"**. Una vez firmada, no se puede tocar.
El **Alumno** solo puede **"Consultar Notas"**.
El **Administrador** gestiona el CRUD de Asignaturas y Grupos.
Al "Consultar Notas" o "Rellenar Acta", el sistema siempre registra un log de acceso (`<<include>>` **"Registrar Acceso"**).

### Ejercicio 9: Máquina Expendedora Inteligente

Basado en .
El **Cliente** se acerca a comprar. Selecciona un producto.
El caso de uso es **"Comprar Refresco"**.
Esto incluye siempre **"Validar Monedas"**.
Si el importe es superior, se ejecuta **"Devolver Cambio"**.
Si no hay stock, el sistema ejecuta **"Mostrar Error de Stock"** (extensión).
El **Reponedor** puede **"Reponer Stock"** y **"Recaudar Dinero"**. Ambas acciones requieren **"Abrir Máquina"** con llave electrónica.

### Ejercicio 10: Clínica Veterinaria (Citas y CRUD)

El sistema debe permitir a un **Recepcionista** gestionar a los pacientes (mascotas). Debe poder hacer CRUD de Mascotas y CRUD de Dueños.
El Recepcionista también puede **"Agendar Cita"**. Al agendar, debe **"Buscar Hueco Libre"** (include).
El **Veterinario** atiende la cita. Realiza el caso de uso **"Redactar Diagnóstico"**. Si es necesario operar, se extiende con **"Programar Cirugía"**.
Al finalizar la consulta, se genera el cobro. **"Cobrar Consulta"** puede hacerse en efectivo o con tarjeta. Si es con tarjeta, incluye **"Conectar con Banco"**.

---

# Parte 2: Descripciones de Casos de Uso (5 Ejercicios)

*Instrucciones:* Para los siguientes escenarios (basados en los diagramas anteriores), redacta el **Flujo de Eventos** (Escenario Principal y Flujos Alternativos/Excepciones).

### Ejercicio 11: Descripción de "Realizar Compra" (Tienda Online)

Detalla los pasos desde que el usuario pulsa "Comprar" en el carrito hasta que sale el mensaje de éxito.

* *Pistas:* Incluye la verificación de stock, el login si no estaba logueado, y el fallo en el pago con tarjeta.

### Ejercicio 12: Descripción de "Alquilar Piso" (Gestión Fincas)

Basado en .
Detalla cómo un inquilino alquila un piso.

* *Pistas:* El inquilino se identifica, selecciona el piso, el sistema valida que está libre, se registra el contrato. ¿Qué pasa si el aval bancario no es válido?

### Ejercicio 13: Descripción de "Retirar Efectivo" (Cajero Automático)

Detalla la interacción física y del sistema.

* *Pistas:* Introducir tarjeta, pedir PIN, validar PIN, pedir monto, validar saldo, entregar dinero, imprimir ticket. Excepción: PIN incorrecto 3 veces.

### Ejercicio 14: Descripción de "Instalación de PIU" (Universidad)

Basado en.
El Administrador decide poner un punto de información en una facultad.

* *Pistas:* Seleccionar facultad, verificar que no existe ya uno de ese tipo (regla de negocio), activar contenidos iniciales.

### Ejercicio 15: Descripción de "Poner Notas" (Calificaciones)

Basado en .
El profesor entra al acta digital.

* *Pistas:* Selecciona asignatura y grupo, el sistema muestra lista de alumnos, profesor introduce nota numérica. Uso opcional de la calculadora interna para hacer la media. Guardado de datos.

---

# Parte 3: Diagramas de Secuencia del Sistema (10 Ejercicios)

*Instrucciones:* Dibuja el diagrama de secuencia (líneas de vida, mensajes síncronos/asíncronos, retornos, loops y alts) para los siguientes escenarios. Céntrate en la interacción **Actor <-> Sistema**.

### Ejercicio 16: Comprar una Lata de Refresco

Escenario: Comprar una Coca-Cola que vale 1€. El usuario inserta dos monedas de 0.50€.

* *Actores:* Usuario, Máquina.
* 
*Mensajes:* Insertar moneda, mostrar saldo actual, seleccionar producto, dispensar producto, devolver cambio (si procede). .



### Ejercicio 17: Partida de "Las Siete y Media"

Basado en .
Escenario: El jugador pide carta hasta que decide plantarse.

* *Loop:* El jugador pide carta, el Sistema la saca del mazo, se la da, suma el valor, muestra total.
* *Alt:* Si se pasa, pierde. Si se planta, turno a la máquina.

### Ejercicio 18: Aldeano Mina Oro (Age of Empires)

Basado en .
Escenario: Simulación de 1 minuto de minería.

* *Actores:* Simulador (Reloj), Aldeano, Mina.
* *Loop:* Cada 'x' tiempo, el aldeano extrae recurso. La mina decrementa cantidad. El aldeano va al depósito.
* *Alt:* Si la mina llega a 0, se destruye o avisa "Mina agotada".

### Ejercicio 19: Validar Tarjeta de Crédito (TPV)

Escenario: Un cliente paga en una tienda.

* *Actores:* Cajero (Persona), Sistema TPV, Banco Externo.
* *Secuencia:* Cajero introduce monto -> TPV pide tarjeta -> Cliente pasa tarjeta -> TPV solicita PIN -> Cliente introduce PIN -> TPV envía datos al Banco -> Banco valida -> Banco responde OK -> TPV imprime ticket.

### Ejercicio 20: Alquiler de Película Online

Escenario: Usuario alquila una película en streaming.

* Usuario selecciona película -> Sistema verifica edad (si es +18) -> Sistema pide confirmación pago -> Usuario confirma -> Sistema habilita visualización por 48h.

### Ejercicio 21: Login en Facebook

Basado en.
Escenario: Usuario intenta entrar.

* Usuario introduce email/pass -> Sistema busca usuario -> Sistema comprueba hash contraseña.
* *Alt:* Si ok, redirige a Home. Si fail, muestra error y limpia campos.

### Ejercicio 22: Chicote evalúa un plato

Basado en.
Escenario: Chicote pide un plato y lo prueba.

* Chicote -> Camarero: Solicitar plato.
* Camarero -> Cocina: Marchar comanda.
* Cocina -> Camarero: Plato listo.
* Camarero -> Chicote: Servir.
* Chicote -> Sistema (Cuaderno): Anotar "Es una mierda".

### Ejercicio 23: Emisión de Recibo Mensual

Basado en.
Escenario: El sistema genera los recibos a fin de mes (Batch).

* *Actor:* Reloj/Sistema Automático (o Secretario).
* *Loop:* Para cada Inmueble alquilado -> Calcular conceptos (Luz, Agua, Renta) -> Generar Objeto Recibo -> Guardar en BD -> Enviar email a inquilino.

### Ejercicio 24: Actualización de Software del PIU

Basado en .
Escenario: El Gestor detecta un fallo y reinicia un PIU remotamente.

* Gestor solicita estado -> PIU responde "Error memoria" -> Gestor envía comando "Reiniciar" -> PIU confirma recepción -> PIU inicia secuencia boot -> PIU envía señal "Online".

### Ejercicio 25: Devolución de Libro con Multa

Escenario: Socio devuelve libro tarde.

* Socio entrega libro -> Bibliotecario escanea código -> Sistema calcula fecha devolución prevista -> Sistema detecta retraso (Alt) -> Sistema calcula multa -> Sistema marca socio como "Sancionado" -> Sistema confirma devolución.

---

# Parte 4: Diagramas de Estados (5 Ejercicios)

*Instrucciones:* Dibuja el diagrama de máquina de estados (estados, transiciones, eventos, condiciones de guarda) para los siguientes objetos.

### Ejercicio 26: Ciclo de Vida de una Multa de Tráfico

*Fuente:* .
Estados: **Impuesta**, **Comunicada**, **Notificada**, **Recurrida**, **Confirmada**, **Anulada**, **Cobrada**, **En Embargo**.

* Eventos clave: Enviar notificación, Acuse de recibo, Rechazo notificación, Paso de 30 días, Recurso recibido, Pago realizado.

### Ejercicio 27: Ciclo de Vida de una Mesa de Restaurante

*Fuente:* .
Estados: **Libre**, **Reservada**, **Ocupada**, **Pidiendo**, **En espera comida**, **Servidos**, **Esperando cuenta**, **Pagando**.

* Transición temporal: Si está Reservada y pasan 20 min sin aparecer -> pasa a Libre.

### Ejercicio 28: Estados de un Pedido Online

El objeto es el **Pedido**.
Nace en estado **Carrito (En proceso)**.
Al pagar pasa a **Pagado**.
El almacén lo prepara: **En Preparación**.
Sale de almacén: **Enviado**.
El mensajero intenta entrega:

* Si éxito -> **Entregado** (Estado Final).
* Si ausente -> **Incidencia**. (Puede volver a Enviado).
El usuario puede **Cancelar** si está en Pagado o Preparación, pasando a **Cancelado** (Final).

### Ejercicio 29: Reloj Digital (Modos)

*Fuente:* .
Estados principales (Modos): **Visualizar Hora**, **Modificar Hora**, **Modificar Minutos**.
Transiciones disparadas por el **Botón A**.
Acciones internas disparadas por el **Botón B** (incrementar dígito).

### Ejercicio 30: Lavadora

Objeto: **Lavadora**.
Estados: **Apagada**, **En Espera** (Encendida), **Llenando Agua**, **Lavando**, **Drenando**, **Centrifugando**, **Fin**.
Transiciones automáticas por temporizador entre las fases de lavado.
Botón de "Pausa" que lleva al estado **Pausado** desde cualquier estado activo, y "Reanudar" que devuelve al historial.

---

# Parte 5: Ejemplos de CRUD (Para practicar)

*Nota Teórica:* CRUD es el acrónimo de **Create, Read, Update, Delete**. En UML (Casos de Uso), suele representarse como un único caso de uso llamado "Gestionar [Entidad]" o desglosado en 4 si la lógica es muy distinta.

**Ejemplo Práctico 1: Gestión de Usuarios (Admin)**

* **Create (Alta):** El admin introduce nombre, email, password. El sistema valida que el email no exista.
* **Read (Consulta):** El admin busca por nombre. El sistema muestra una lista. Al hacer clic, ve el detalle.
* **Update (Modificación):** El admin cambia el email. El sistema vuelve a validar duplicados.
* **Delete (Baja):** El admin borra al usuario. El sistema pregunta "¿Está seguro?".

**Ejemplo Práctico 2: Gestión de Asignaturas (Ejercicio Calificaciones)**

* Define los atributos: Nombre, Código, Créditos, Curso.
* Intenta modelar en un diagrama de secuencia cómo sería el "Update":
* Actor -> Sistema: Solicitar formulario edición(id)
* Sistema -> Actor: Muestra datos actuales
* Actor -> Sistema: Envía nuevos datos
* Sistema -> BD: Update
* BD -> Sistema: OK
* Sistema -> Actor: Mensaje "Asignatura modificada".