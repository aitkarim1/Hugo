+++
title = '¿Qué es BACKEND y FRONTEND? (guía completa)'
date = 2023-10-18T01:13:47+02:00
draft = false
+++

En el desarrollo web actual existen 3 conceptos claves a tener en cuenta: Frontend, API y Backend. Decimos que son conceptos "actuales" debido a qué anteriormente todo se hacía con PHP, increíble ¿cierto? pero todo empezó así, la estructura de las webs y la comunicación con el servidor se hacía con PHP, no era necesario utilizar JavaScript lo cual hoy en día es casi impensable para el desarrollo de una Web.

## La web funciona con la arquitectura cliente servidor

![image](https://edteam-media.s3.amazonaws.com/blogs/original/a04ca961-f61d-4dc3-837c-55c06df42ce7.png)

Antes de explicarte qué es Frontend y Backend, debemos entender la arquitectura cliente servidor. El cliente y el servidor son dos computadoras (y no, no son las computadoras de tu cliente y la tuya 😆), el cliente (cualquier computadora que desee consultar la web) es quien pide la información y el servidor es quien se la suministra, siempre y cuando el cliente tenga los permisos.

El proceso cuando el cliente solicita información o recursos al servidor se le llama petición, en el desarrollo web tradicional cada petición recargaba toda la página y había una mayor carga en el servidor, pero con tecnologías como [Ajax](https://es.wikipedia.org/wiki/AJAX) y [Websockets](https://es.wikipedia.org/wiki/WebSocket) se pueden hacer peticiones de cosas muy especificas haciendo que la web sea mucho más fluida.

---

## Desarrollo web tradicional (90s - 2000)

Como ya te expliqué al principio **se hacía casi todo con PHP** y por eso no existía o no había una división entre programador Frontend (el que hace el desarrollo para el cliente) y Backend (el que hace el desarrollo para el servidor), en este entonces el monopolio lo tenia *Microsoft* con su navegador *Internet Explorer* y este navegador no respetaba ningún estándar y no había muchas opciones, por este motivo tal vez los más veteranos no entiendan muy bien estos términos "actuales"

---

## Desarrollo web moderno

![image](https://edteam-media.s3.amazonaws.com/blogs/original/c79bf9fc-7c15-400d-9a01-8d0f2061ad4d.png)

El desarrollo web moderno **surge alrededor del 2008** cuando empieza el auge de HTML5, es en este momento dónde empezamos a hablar de Frontend y Backend, debido a que la tecnología web crece enormemente gracias a las APIs que vinieron con HTML5, estas APIs hacen posible una comunicación entre Backend y Frontend, de esta manera cualquier Frontend se puede comunicar con cualquier Backend.

---

## Frontend

El frontend cómo ya dijimos es el cliente y es el que se encarga de toda la lógica de este cuando desea realizar alguna petición, podemos decir que este concepto surge en el 2008 debido a las herramientas que surgieron a partir de ese momento: HTML5, CSS3 (2008), JSON (2013 - 2015), AngularJS (2010), Ember, Backbone, Rest (2000) y Nodejs, estas tecnologías hicieron posible el Frontend.

El Frontend ha ido evolucionando con nuevas tecnológicas como lo son: ES6 (2015), React (2013), Vue (2014), Angular (2016), GraphQL (2015), las cuales por lo menos ya deben haber escuchado; en el panorama actual entra en el juego WebAssembly que es un nuevo tipo de código que se ejecuta en los navegadores web modernos y proporciona nuevas funciones y grandes ganancias en el rendimiento.

![image](https://edteam-media.s3.amazonaws.com/blogs/original/46ccfe56-bee0-4a2c-adaf-ecd3213a0de5.png)

### Características de WebAssemby

No está destinado a ser escrito a mano: Está diseñado para ser un objetivo de compilación efectivo para lenguajes de origen de bajo nivel como C, C ++, Rust, etc.
No es necesario saber crear código de WebAssembly: puedes importar librerías y programar con JavaScript.
Se ejecuta a una velocidad casi nativa en diferentes plataformas.
Lenguaje ensamblador de bajo nivel: Pero tiene un formato de texto legible por humanos
Funciona con otras tecnologías web: Mantiene la compatibilidad con versiones anteriores

---

## Backend

Llega el momento del Backend y cómo ya dijimos es quien esta del lado del servidor, este se encarga de la lógica de negocio, es decir, todas las funciones que requiere el cliente.

Un desarrollador Backend debe ser capas de crear una API para que el Frontend pueda consumirla y así poder realizar peticiones, en el desarrollo de esta API hay que conectarse a una base de datos y definir que le es permitido mostrar al frontend (un desarrollador backend no necesariamente debe saber bases de datos, puede hacerlo a través de una ORM).

### Backend como servicio

El Backend así como el Frontend ha evolucionado, y el último paso que ha dado no le puede agradar a los desarrolladores; hoy en día se puede contratar como un servicio, es decir un desarrollador Frontend ya puede hacer todo el trabajo con estos servicios, solo debe ingresar a la plataforma y realizar algunas configuraciones.

Algunos servicios que podemos encontrar son: Firebase, Serverless y Servicios de cloud computing; siendo frirebase el más conocido. Estos servicios ofrecen grandes ventajas como seguridad, facilidad de integración, funcionalidades preestablecidas, etc. Pero hay que tener en cuenta que es un servicio y cómo todo servicio hay que pagar, por estos motivos tal vez hayan muchas empresas que migren y otras no, entonces, desarrolladores de Backend no se preocupen, no se van a quedar sin trabajo.

---

## Conclusiones

El reto de un programador Frontend es que su código funcione en todos los navegadores y los retos de un programador backend son la seguridad y el rendimiento.

Aunque Frontend es todo lo que tiene que ver con el lado del cliente, no hay que confundir diseñador con programador, muchas veces creemos que los programadores Frontend deben saber diseñar, pero esto no es así, esa no es tarea del desarrollador, en esta tarea hay otras personas involucradas, como el diseñador y el maquetador (el que pasa el diseño a html y css).

El desarrollo Backend tradicionalmente ha sido monolítico, es decir un Backend gigantesco que siempre se va alimentando, pero en esta época entran en juego los micro servicios con los cuales se puede dividir la lógica de negocio en pequeños servicios (funcionalidades).