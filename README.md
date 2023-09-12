# Introducción al desarrollo de SPA's con React y Vue
#### Gandhy García - Aplicaciones Web Avanzadas - 2023/09/12

En este proyecto se documentan conceptos básicos, características, arquitectura y un ejemplo (Hola mundo) para React y Vue.

# React

## Características principales

* Librería de javascript para el desarrollo de aplicaciones móviles y web.
* Desarrollado por Facebook
* Basado en fragmentos de código llamados "componentes" para la creación de interfaces de usuario
* Compatible con JavaScript y Typescript
* JSX y TSX -> Extensión de JavaScript y TypeScript para la creación de elementos de React.

## Conceptos básicos

* DOM Virtual -> Árboles DOM virtuales. React puede actualizar partes específicas de éste árbol para no renderizar todo el DOM
* La interfaz de usuario se divide en componentes que pueden recibir datos de entrada ("props").
* Estados: Partes de los componentes que pueden cambiar a lo largo del tiempo. Una vez que un estado cambia, se renderiza el componente. La gestión de los estados de una aplicación React se puede realizar con librerías como Redux o Recoil.

## Arquitectura

React está basado principalmente en componentes. Las aplicaciones React siguen los principios de las SPAs, es decir, las vistas (UI) se generan del lado del cliente. La comunicación del backend solo se realizar para la interacción con los datos.

## Ejemplo Hello World

El ejemplo de implementación de React se puede visualizar en la carpeta /react-hello-world.

Para correr el proyecto de react, se recomienda ingresar a dicha carpeta, correr "npm run install" y "npm start".

# Vue

## Características principales

* Framework progresivo (open source) de javascript para la construcción de interfaces de usuario
* Creado por Evan You (ex trabajador de Google y desarrollador Angular)
* Permite crear SPA's con ayuda de otras librerías
* Basado en componentes que encapsulan código reutilizable
* Vinculación de datos bidireccional (data binding) para el manejo de los datos que se muestran en la UI.
* Usa "templates" para definir la estructura de los componentes (código similar a HTML)

## Conceptos básicos

* DOM Virtual
* Directivas Vue: Atributos especiales en el HTML que permiten añadir funcionalidad a las aplicaciones (Ej: v-model, v-if, v-show, v-for)
* Renderización declarativa: Los datos se procesan de forma declarativa al DOM.
* Si bien Vue no tiene "estados" como react, tiene un concepto similar llamado "data properties".
* Vuex: Librería para la gestión de estados y el flujo de las aplicaciones Vue

## Arquitectura

Arquitectura basada en componentes. La interfaz de usuario se divide en piezas independientes de código.

## Ejemplo Hello World

El ejemplo de implementación de React se puede visualizar en la carpeta /vue-hello-world.

Para correr el proyecto de react, se recomienda ingresar a dicha carpeta, correr "npm run install" y "npm run serve".

#### Enlaces de referencias

1. [Qué es React: definición, características y funcionamiento - Hostinger Tutoriales](https://www.hostinger.es/tutoriales/que-es-react#Gestion_de_Estado)
2. [¿Qué es React? - Oscar Blancarte (ReactiveProgramming.io)](https://reactiveprogramming.io/blog/es/react/que-es-react)
3. [¿Qué es Vue.JS y para qué sirve? - Dongee](https://www.dongee.com/tutoriales/que-es-vue-js-para-que-sirve/)
4. [Introducción Vue - Vuejs.org](https://es.vuejs.org/v2/guide/)
