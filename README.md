# :dog: Pet adoption

## Objetivo

Vamos a crear un programa que cree perritos para una casa de adopción. Las características que tendrán serán las siguientes:

- Nombre
- Edad
- Sexo
- Raza
- Tamaño (pequeño - mediano - grande)
- ¿Está vacunado? 
- ¿Está desparasitado?
- ¿Está adoptado?
- Fecha de llegada al centro
- Fecha de adopción
- Nombre y apellido de quien lo adoptó

Las acciones de los perritos serán la vacunación, la desparasitación y la adopción.

También tu programa deberá poder crear personas, por el momento las características serán solo su nombre y apellido.

## Requisitos no funcionales

- Has de crear un modelo de base de datos normalizada.
- Un perrito puede ser adoptado solo por una persona, pero una persona puede adoptar varios perritos.
- Has de crear una arquitectura MVC (modelo - vista - controlador) de estilo monolítica, usando el patrón de diseño DAO (data access object)
- La vista será por terminal
- Has de usar una base de datos relacional en postgreSQL

## Requisitos funcionales

- DEBE crear un perrito
- DEBE mostrar la lista de todos los perritos 
- DEBE editar la información de un perrito
- DEBE eliminar un perrito
- DEBE crear un persona que adopta
- DEBE editar la información de la persona
- DEBE eliminar una persona
- DEBE mostrar el perrito con la persona que lo adoptó

## ¿Qué aprenderemos?

- Programación orientada a objetos
- Patrón arquitectónico MVC
- Patrón de diseño DAO
