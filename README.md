# Clase01

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.4.

## Conceptos de la práctica con mis propias palabras

* Define que es un COMPONENTE y al crearlo que elementos lo forman.
  - Es un componente de angular, practicamente es como una plantilla en dode va a ir nuestro HTML, es decir la interfaz que el usuario va a poder visualizar o la página     como tal.
  - Los elementos que lo conforman son los siguientes:
  
     Un archivo de lógica, la cual es la que pondremos en un archivo .ts (como por ejemplo app.component.ts), ese archivo debe incluir una clase y esta es la que va a        contener las propiedades que se van a usar en la vista (HTML) y los métodos que será las acciones que se ejecutarán en la vista. En este archivo de lógica también        se incluye una metadata, que es definida con un decorador,  que identifica a Angular como un componente.
   
     Un archivo para el CSS (podemos usar un preprocesador como SASS o LESS), donde incluiremos los estilos, lo que nos ayuda a hacer bonita nuestra aplicación.
    
 
* Define que es un MÓDULO y que función tiene el patrón de diseño decorator.
  - Los módulos de Angular representan un concepto central y juegan un papel fundamental en la estructuración de las aplicaciones Angular.

     Un Módulo Angular agrupa un conjunto de artefactos Angular, como son componentes, directivas, pipes y servicios que forman parte de ese mismo módulo. Dicho esto,        representa una agrupación lógica en lo que podríamos llamar área funcional de nuestra aplicación (ej. módulo de contactos, módulo de administración,…). Es más, un        Módulo Angular también define las dependencias con otros módulos, esto es, que otros módulos necesita importar y a su vez qué componentes, directivas o pipes            exporta.

   - Si vamos a un término muy técnico, un decorador es una implementación de un patrón de diseño de software que permite extender una función dentro de otra función,      sin modificar la original de la que se está extendiendo. En términos simples un decorador nos permite decorar una función a la cual deseamos especificarle unos       metadatos, en ellos se informa sobre la función y sus comportamientos. Las funciones decoradoras inician por una "@" y a continuación tienen un nombre.
   
* Menciona y describe los elementos importantes de un @NgModule.




## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
