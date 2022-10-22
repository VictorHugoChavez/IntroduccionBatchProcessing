# Introducción a Batch Processing

## ¿Que es el BATCH PROCESSING?
En terminos  simples, es un metodo para procesar consistenmente grandes cantidades de datos.
Cuando hay suficientes recursos informáticos disponibles, el método por lotes le permite procesar datos con poca o ninguna interacción del usuario.

## ¿Cuales son las características clave del Batch Processing?
* ***Eficacia*** : se programan procesos que no son tan urgentes 
* ***Sencillez*** : este no requiere un sistema complejo, no requiere mantenimiento
* ***Calidad de datos mejorada*** : Al tener pocesos automizados, tenemos interaccion con ususario, podemos mejorar la calidad de nuestro codigo en errores humanos, error del sistema, etc.


![Caracteristicas del Batch](./src/img/CaracteristicasBatch.png)

Se ve claro que el batch procesing realizara un extracion de datos de nuestra base de datos, despues va procesando la informacion y por ultimo lo va almacenar en otra base de datos.

![Proceso de Datos](./src/img/procesaDatos.png)

## ¿Cuándo se debe utilizar el Batch Processing?

Las cosas que no necesitan procesamiento en tiempo real y son candidatos ideales para el procesamiento por lotes podrían incluir:

- Procesamiento de nóminas y partes de horas.
- Facturas de partida para cualquier empresa u organizacion que acumule datos y produzca un resultado principal en un momento determinado
- Estados de cuenta
- Investigacion y presentación de informes
- Sistemas de factuiracion que pueden preferir factuar una vez a la semana o al mes
- Administracion de actualizaciones de base de datos
- Archivos que se convierten de un archivo a otro, por ejemplo, facturas de fin de mes que cambien de un formato a PDF

## Las alternativas al Batch Processing



![Stream](./src/img/REAL-TIME%20OPERATING%20SYSTEMS.png)

El stream processing trata de no tener una gran cantidad de volumenes a comparacion de Batch Processing, requiriendo hacerlo en pequeñas cantidades y en un corto tiempo.

![RealTime](./src/img/RealTime.gif)
El REAL-TIME OPERATING SYSTEMS que es mas conocido con sistema en tiempo real, significa que la aplicacion se realiza en cuestion ya sea de milisegundo o segundos, y como ejemplo para poder entender este concepto seria como la bolsa de valores donde se ve en ese momento como cambian los numeros.

---
Antes de querer entender que es Spring Batch se debe conocer que es Spring Boot? 
* Que es SPRING FRAMEWORK? Es una framework Open Source que facilita la creacion de aplicaciones de todo tipo de Java, Kotlin y Groovy. Tambien es conocido por que utiliza la inyeccion de independencias y de patrones de diseño y el test.

Si bien es cierto que Spring Frameworj es muy potente, la configuracion inicial y la preparacion de las aplicaciones para produccion son tareas bastante tediosas. Spring Boot simplifica el porceso al maximo gracias a sus dos principales mecanismos:

### Contenedor de aplicaciones integrado

- Spring Boot permite compilar nuestras aplicaciones Web como un archivo .jar que podemos ejecutar como una aplicacion Java normal.

- Este consigue integrado el servidor de aplicaciones en el propio .jar y levantandolo cuando arranquemos la aplicacion.

### Staters

- Spring Boot nos proporciona una serie de dependencias, llamadas staters, que podemos añadir a nuestro proyecto dependiendo de lo que necesite.
- Una vez añadimos un starter, este nos proporciona todas las dependencias que necesitamos, tanto de Spring como de terceros

---
