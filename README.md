# Backend Challenges boilerplate - package.json
[![Run on Repl.it](https://repl.it/badge/github/freeCodeCamp/boilerplate-npm)](https://repl.it/github/freeCodeCamp/boilerplate-npm)

# Gestión de paquetes con NPM

npm (Gestor de Paquetes de Nodos), es una herramienta de línea de comandos para instalar, crear y compartir paquetes de código JavaScript escritos para Node.js. Hay muchos paquetes de código abierto disponibles en npm, así que antes de iniciar un proyecto, tómate algo de tiempo para explorar los diferentes paquetes, para que no termines reinventando la rueda para cosas comunes como trabajar con fechas y obtener datos de una API.

En este curso, aprenderás los conceptos básicos del uso de npm, incluyendo cómo trabajar con el package.json y cómo administrar las dependencias instaladas.

## 1. Uso del package.json

Este archivo funciona de manera muy similar a la sección **head** de html, esta formado de un solo objeto **JSON** que guarda información del projecto en pares =="clave": "valor"==, este archivo tiene solo dos campos que son obligatorios, el 'name' y 'versión'.

Otro campo comun es el de 'author'.

## 2. Descripcion del package.json

El campo descripción es muy util para poder definir lo que es el paquete.

## 3. Agregar keywords

Las palabras clave tambien pueden ser utiles para saber que es el paquete, este esta conformado por por un arreglo [].

## 4. Agregar licencia

Las licencias libres mas utilizadas son las MIT y BSD.

## 5. Version

Describe la versión actual del proyecto.

## 6. Dependencias

Las dependecias son paquetes externos que agregan mas funcionalidad a los proyectos, ademas de que estos tambien funcionan para poder saber que necesita nuestro proyecto a la hora de instalarlo en otro lugar.

## 7. Versionado semantico

**MAJOR.MINOR.PATCH**

* MAJOR: Cambios grandes que son incompatibles con versiones anteriores.
* MINOR: Agregan nuevas funcionalidades que funcionan con versiones anmteriores.
* PATCH: Son parches de seguridad o correcciones de errores.

## 8. Caracter tilde '~'

Funciona para especificar la ultima version de parche de un paquete.

## 9. Caracter caret '^'

Funciona para especificar la ultima version minor de un paquete.

## 10. Eliminar paquete

Para eliminar un paquete del package.json solo es necesario borrar el par "clave": "valor".

