# 02 - Especificación: Gestor de Entrada Central

## Responsabilidad y Ubicación
Este archivo debe ubicarse en el directorio del núcleo del proyecto.

## Requerimientos
Se requiere diseñar un módulo que envuelva la librería externa de captura de datos por consola de manera síncrona. 

El gestor debe exponer una acción genérica para realizar preguntas al usuario y capturar su respuesta en formato de texto. Este módulo es el único autorizado para interactuar con la entrada del teclado, centralizando así la obtención de información y evitando que los servicios de negocio se acoplen a librerías de consola.