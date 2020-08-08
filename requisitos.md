## **NOMBRE DEL PROYECTO: ANALISIS, DISEÑO, DESARROLLO E IMPLEMENTACION EN UNA PLATAFORMA WEB PARA EL PUNTO DE VENTA Y CONTROL DE LA INFORMACION EN LA EMPRESA VARIEDADES MARY**

## **EMPRESA: VARIEDADES MARY (ALMACEN COMERCIAL)**

## **APRENDICES: DAVID CABRERA, JOSE DIAZGRANADOS, LEIDY QUIROGA, SEBASTIAN ESCANDON, EMMANUEL ALVAREZ, BRAYAN TORRES**

## **INTRODUCCION** 

El presente documento tiene como objetivo brindar una descripción detallada de los requerimientos para el sistema de gestión de requisitos de un punto de ventas y manejo de datos de la información que se le desarrollara a la empresa Variedades Mary, obtenidos en el análisis realizado por parte del equipo de aprendices en conjunto con el cliente.

## **PROPOSITO** 

El propósito de este documento es describir de manera formal el comportamiento del sistema para la implementación de una plataforma WEB que se pretende construir. que tendra capacidad para gestionar, realizar ventas y almacenar la informacion que se trabajara dentro la plataforma realizada para el almacen Variedades Mary. A continuación, Se detallan los requerimientos funcionales y no funcionales, las restricciones y atributos de calidad que deberá cumplir el sistema. El documento está dirigido a:

1. El cliente.
2. Todos los miembros del equipo de desarrollo aprendiz.
3. El Instructor.

## **ALCANCE**

El alcance de este proyecto será el de crear una plataforma web para el comercio Variedades Mary para que se les facilite en almacenamiento y recolección de información de sus artículos y al igual crearle un punto de ventas en línea y así poder solucionarle la perdida de información que se tiene al realizar las ventas. Gracias a la plataforma web habrá una mejor comunicación de cliente a vendedor. Este software tendrá las siguientes funciones y especificaciones:

1. Tendrá una base de datos con el inventario de los artículos.
2. Tendrá un punto de venta en línea.
3. Habrá un mejor contacto con el cliente.
4. Tendrá una interfaz amigable y fácil de usar.
5. La plataforma tendrá un módulo de registro de actividades y de registro de usuarios.

El proyecto tendrá la duración de año y medio y al terminar el proyecto solo se hará entrega del software ya funcionando al almacén Variedades Mary.

## **DEFINICION, ACRONIMOS, ABREVIATURAS**

1. ADSD-Analisis De Software de Documentacion .
2. BD-Base de datos. 
3. RIP-Registro de Informacion General.
4. CMS-siglas de Content Management System.
5. RPA-Automatización Robótica de Procesos.

## **DEFINICIONES**

**Optimizacion:**

Optimizar quiere decir buscar mejores resultados, más eficacia o mayor eficiencia en el desempeño de alguna tarea. De allí que términos sinónimos sean mejorar, optimar o perfeccionar. 

**Mercantilizar:**

La mercantilización es el proceso de transformación de bienes y servicios en mercancías comercializables con fines de lucro. Es decir que el valor de cambio de los objetos prevalece sobre su valor de uso.

**Regularizacion:**

Regularización es el proceso y la consecuencia de regularizar. Este verbo se refiere a normalizar, ordenar, reglamentar o sistematizar algo.

**Prototipo:**

Primer ejemplar que se fabrica de una figura, un invento u otra cosa, y que sirve de modelo para fabricar otras iguales, o molde original con el que se fabrica.

**Sector terciario:**

El sector servicios o sector terciario es el sector económico que engloba las actividades relacionadas con los servicios no productores o transformadores de bienes materiales. Generan servicios que se ofrecen para satisfacer las necesidades de cualquier población en el mundo.

**La boutique:**

La palabra boutique se refiere, por lo general, a una tienda exclusiva, de ropa o accesorios de moda. ... Así, hoy en día el término boutique también hace referencia a un establecimiento o negocio que comercializa o se especializa en productos o servicios muy selectos o exclusivos.

**Base de datos:**

Programa capaz de almacenar gran cantidad de datos, relacionados y estructurados, que pueden ser consultados rápidamente de acuerdo con las características selectivas que se deseen

**Content Management System:**

Un sistema de gestión de contenidos o CMS es un programa informático que permite crear un entorno de trabajo para la creación y administración de contenidos, principalmente en páginas web, por parte de los administradores, editores, usuarios y demas.

A lo largo de todo el documento, se utilizan los términos Requisito y Requerimiento en forma distinta.

## **DEFINICION**

En esta definición se planea exponer los datos recopilados por nosotros como grupo de aprendices S.E.N.A hemos recopilado desde el día sábado 9 de mayo del año 2020.

Este proyecto está diseñado para el beneficio y aporte al sector economico en el area textil. La boutique es una de las mas importantes y uno de los grandes establecimientos en el sector donde se encuentra. el cual se caracteriza en la venta de artículos de moda y lujo como prendas de vestir y joyería. reconocido por su gran variedad y calidad de sus productos, ademas de su enorme fiabilidad a la hora de mercantilizar. queriendo lograr una extension en el area que desempeña llevando esto hasta el domicilio del cliente, a lo que ahora se le conoce como tienda virtual. 

Este proyecto está siendo elaborado con el fin de sistematizar y optimizar la cantidad de informacion que es suministrada a diario. Referente a ventas, compras, stock, observaciones y demas. 

la razón por la que hicimos enfasis en la parte de la obtencion de la informacion y su procesamiento, fue gracias al  estudio y analisis sobre esta. Que puso en descubierto la perdida de informacion, la falta de optimizacion, esfuerzo mental por parte de los empleados encargados y sobre todo la falta de regularizacion y su obtencion de informacion. 

La tienda se encuentra sin automatización para este medio teniendo que recurrir a catalogar la información artesanalmente, esto ha llevado a un gran retroceso para la empresa bajando su productividad. ya hemos sido autorizados por la propietaria del emprendimiento (Maria buelvas) para ayudar a la creación del prototipo del software web para el almacenamiento de información, el cual para habilitar y entregarlo totalmente restan 14 meses de aprendizaje.

## **APRECIACION GLOBAL**

Este documento esta conformado por secciones que son el proposito, el alcance, y la ultima seccion es donde estan las definiciones y los pormenores de los requisitos. en esta primera seccion se procura proporcionar una vision general de las funciones que cumplira o no el software. En la segunda seccion se da una descripcion general del sistema a construir, para conocer los datos requeridos y sus funciones generales, aunque no se entra en detalles de cada uno de esto factores. y por ultimo  tambien se conoceran las definiciones y los pormenores del software.

## **PERSPECTIVAS DEL SOFTWARE**

Este software sera de facil acceso, sera capaz de generar simplicidad del control y obtencion de la informacion la cual suministrada por los usuarios.

Logrando una multifuncionalidad y accesibilidad de acuerdo a las funciones del usuario. Se espera que el sistema funcione en un ambiente web, por lo que deberá ser capaz de funcionar en cualquier plataforma con un navegador web instalado, siempre y cuando disponga de conexión al servidor en que va a estar corriendo la aplicación, ya sea por Internet o alguna red privada. 

la información que se muestra va cambiando a medida que se va ingresando a cada uno de las opciones.
Esta interfaz cumple con los requisitos de interfaz amigable con el usuario y facil de usar.

Al ser una aplicacion web se espera que el consumo de recursos sea muy poco, por lo que se enfocaría basicamente en lo que gasta el navegador que es alrededor de 64 MB.

El sistema WEB, permitirá su utilización de forma descentralizada, además trabajará de manera independiente por lo tanto no interactuará con otros sistemas.

Lo que se espera de esta aplicacion es que sea mas usable y mas intuitiva para sus usuarios, ademas de que satisfaga completamente los requerimientos con el mejor uso de recursos posibles.

## **FUNCIONES DEL SOFTWARE**

El software debe cumplir con las siguientes funciones:

1. Registrar usuario.

2. Acesso a un panel de navegacion.

3. Ingreso de productos 

4. registro de asignacion de venta.

5. realizar venta

6. Generar el registro de compras y ventas.

7. Mejora en la ejecucion de la facturación.
 
8. Generar reportes.

9. Control de la informacion:
	-ajustar los procesos internos de ventas.
	-visualizar el recorrido.
	-seguimiento de contactos.
	-Consultar registros.

## **CARACTERISTICAS DE USUARIO**

El sistema cuenta con tres tipos de usuario final, los cuales cada uno de ellos puede representar un rol, que incide forma directa o indirecta con la tienda ya sea como: Empleado, Cuerpo administrativo, cliente.

Empleado(cuerpo administrativo): Este rol de usuario en primera instancia es quien mas interactua con el sistema y tambien el cual tiene mas accesibilidad y ser el usuario a disposicion de administrar la informacion de los usuarios y clientes de acuerdo a los requerimientos u opciones definidas referente a la informacion de las ventas.

Empleado(vendedor): Como el anterior este rol es igual de principal solo que con alguna limitaciones en la accesibilidad a la informacion suministrada en el sistema unicamente es direccionado a encargarse atraves de la interfaz vendedor de generar un registro de asignacion de venta, y unicamente trenda acceso a su informacion personal e sus datos a cerca de sus ventas asignadas.

El siguiente lo constituyen los clientes igual de importantes que los ya menciondos, quienes solo tendran acceso al modulo de venta donde puede hacer consulstas o revisar detalles referentes a los productos y a su informacion personal alojada en su perfil, y a la hora de la facturacion tambien a la informacion referente a su compra del producto que se encuentran en venta dentro dentro del modulo de clientes.


## **RESTRICCIONES**

- Debe haber conexión a internet.
- Uso de sesiones para limitar el acceso a usuarios no autorizados.
- El horario de atención al cliente será de 6:00 am hasta las 10:00 pm.
- El vendedor solo podrá entrar al software estando el punto de trabajo.
- La sesión se cerrará luego de 5 minutos de inactividad.

## **ATENCION Y DEPENDENCIAS**

Para el completo funcionamiento de la plataforma tiene estas depedencias:

- Conexion a internet.
- Base de datos que servira para almacenar todas las ventas y registro de actividades.
- Un servidor con su respectivo hosting.

## **REQUERIMIENTOS FUNCIONALES**

A continuación, se detallan los requisitos funcionales que el sistema deberá implementar.

001. Módulo de Ventas
- En este módulo los usuarios podrán ingresar a la página a ver los productos e ir seleccionando los que necesitan

002. Módulo de Pago
- En este módulo los usuarios podrán realizar el pago del producto anteriormente pedido

003. Inicio de sesión
- Inicio de sesión para que solo puedan ingresar las personas registradas en el sistema.

004. Módulo de registro
- Opción de registro para los Los clientes podrán hacer sus peticiones quejas o reclamos referentes al almacénusuarios de la plataforma

005. Módulo de PQR (peticiones, quejas y reclamos)
- Los clientes podrán hacer sus peticiones quejas o reclamos referentes al almacén

006. Ingreso de productos
- Registrar el ingreso de los productos que llegan por parte del proveedor al almacén

007. Módulo de reporte
- Este módulo me permite realizar reportes de la diferente información que habrá en la plataforma web

008. Facturacion
- la plataforma debe generar una factura para ser entregada al cliente o bien podría ser electrónica y se le mandaría al correo del cliente.

## **REQUERIMIENTOS NO FUNCIONALES**


**Usabilidad**

El sistema deberá proveer una interfaz amigable al usuario, que sea fácil
de aprender y de usar. 

Se pretende que la navegación entre las distintas
funcionalidades del sistema sea realizada en forma sencilla y en pocos
pasos. 

La interfaz deberá ofrecer funcionalidades para realizar tareas
repetitivas en forma automática.

**Mantenibilidad**

El sistema cuenta con características parametrizables lo que permitirá futuros
mantenimientos. Es decir cada tres meses se va a realizar un mantenimiento
preventivo, encargado de hacerlo están los desarrolladores.

Se realizara el mantenimiento dos veces sin ningún recargo económico, pasados
estas dos revisiones tendrán costos adicionales.

**Fiabilidad**

Es uno de los factores que dará confianza al cliente, para lo cual el sistema está
controlando todo tipo de transacción y esta apto a responde todo tipo de
incidente. 

**Portabilidad**

Este requerimiento asegura que el sistema será totalmente portable en cuanto se refiere a sistemas operativos en MacOS, Linux Windows, también así mismo este pueda ser utilizado a través de diferentes navegadores como: Mozilla, Chrome, Microsoft Edge, Opera que pueda mantener esa portabilidad. 

**Seguridad**

La detección de vulnerabilidades y la seguridad informática es fundamental para mantener siempre segura e intacta la información privada de la empresa y de los usuarios asi como cualquier actividad inorganica dentro del sistema   , por ello, contar con este tipo de herramientas constituye.


**Modulo de ayuda**
Es necesaria como alternativa por si se requiere de alguna informacion en especifico inmediatamente el usuario podra acceder algun modulo de ayuda para asi mejorar la experiencia dentro del sistema.


## **Ejemplo:**

**Inicio de sesión automática en un sitio web:** 

Al automatizar el inicio de sesión y el proceso de navegación de un sitio web se pueden ahorrar muchas horas de procesamiento manual.

**Navegación automática en un sitio web**

**Scraping: extraer datos de una página web de forma automática**

**Utilización de GAM**

Se deberá utilizar Genexus Access Manager para toda la gestión de usuarios
y control de acceso; autenticación y autorización.


**Interfaz del sistema**

La interfaz del sistema debe estar implementada como una aplicación web,
a excepción de la extensión para Smart Devices. Se pretende además la
existencia de un portal de requisitos.


**Requerimientos de Interfaz externa**


-Interfaz de inicio de sesion(principal).

-interfaz de informacion de compra clientes.

-Interfaz de facturacion de ventas.

-Interfaz asignacion de ventas(vendedor).

-Interfaz de cuerpo administrativo de la informacion.

-Interfaz perfil de usuario.

-Interfaz de reportes de ventas.

-Interfaz de administracion de roles.

-Interfaz de compra de productos.

-Interfaz de ventas en espera.