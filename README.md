

nombre: Edwin Maureira Toledo
curso: frond end Corfo grupo 1
Modulo 6 - Ejercicio Practico 1

## Estructura del Proyecto

La aplicación está estructurada con los siguientes componentes principales:

-   `App.jsx`: Componente principal de la aplicación que configura el enrutamiento.


## Cómo Ejecutar la Aplicación

1.  Asegúrate de tener Node.js y npm (o yarn) instalados.
2.  Clona el repositorio. (git clone https://github.com/emaureira/modulo6_ejercicioPractico1.git) 
3.  Navega al directorio del proyecto en tu terminal. (modulo6_ejercicioPractico1)
4.  Instala las dependencias utilizando `npm install` o `yarn install`.
5.  Inicia el servidor de desarrollo con `npm run dev` o `yarn start`.
6.  Abre tu navegador y navega en localhost

## Se configure en vite config.js el Manifiesto
    Nombre de la aplicación: Mi PWA - HOSPITAL CFE
    Modo de Pantalla: standalone

##Configuracion Service Worker (sw.js)

Durante la instalacion se crea un cache de y en ella se guardan los archivos que estan en la constante: urlsToCache

durante la activacion se elimina la cache anterior

durante la captura de datos hacia una peticion de red, lo primero que devuelve es lo que esta en cache, si no esta va a buscarlo a la red, lo almacena en cache y luego devuelve la informacion

