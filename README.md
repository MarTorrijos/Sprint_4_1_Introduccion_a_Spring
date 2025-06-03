## Objetivo

Familiarizarse con los siguientes conceptos:

- Protocol HTTP
- Primer contacto con Spring
- Gestores de dependencias (Gradle/Maven)


### Tecnologias usadas

- Java 21

- Maven

- Gradle

- IntelliJ


***

## Nivel 1

Dependiendo del paquete principal, crea otro subpaquete llamado controller, y dentro de él, añade la clase HelloWorldController.

Deberá tener dos métodos:
String saluda
String saluda2

Estos dos métodos recibirán un parámetro String llamado nom, y devolverán la frase:

“Hola, “ + nombre + “. Estás ejecutando un proyecto Maven”.

El primer método responderá a una petición GET, y deberá ser configurado para recibir el parámetro como un RequestParam. El parámetro "nombre" tendrá el valor por defecto “UNKNOWN”.

Deberá responder a:

`http://localhost:9000/HelloWorld`

`http://localhost:9000/HelloWorld?nom=minombre`
<br><br>

El segundo método responderá a una petición GET, y deberá ser configurado para recibir el parámetro como una PathVariable. El parámetro "nom" será opcional.

Deberá responder a:

`http://localhost:9000/HelloWorld2`
    
`http://localhost:9000/HelloWorld2/minombre`

<br>


***

## Nivel 2

Dependiendo del paquete principal, crea otro subpaquete llamado controller, y dentro de él, añade la clase HelloWorldController.

Deberá tener dos métodos:
String saluda
String saluda2

Estos dos métodos recibirán un parámetro String llamado "nom" y devolverán la frase:

“Hola, “ + nombre + “. Estás ejecutando un proyecto Gradle”.

El primer método responderá a una petición GET, y deberá ser configurado para recibir el parámetro como un RequestParam. El parámetro "nombre" tendrá el valor por defecte “UNKNOWN”.

Deberá responder a:

`http://localhost:9001/HelloWorld`

`http://localhost:9001/HelloWorld?nombre=minombre`
<br><br>


El segundo método responderá a una petición GET, y deberá ser configurado para recibir el parámetro como una PathVariable. El parámetro "nom" será opcional.

Deberá responder a:

`http://localhost:9001/HelloWorld2`

`http://localhost:9001/HelloWorld2/minombre`

<br>


***


## Cómo ejecutarlo
Clona el repositorio o descarga el archivo zip, luego ábrelo en tu entorno de desarrollo integrado (IDE) preferido.
