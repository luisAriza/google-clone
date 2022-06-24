# Google: Clone

En este proyecto se _maquetó_ el buscador de Google con **HTML** y **CSS** aplicando _breakpoints_ para hacerlo _responsive_ y poder verlo en mobile, tablet y desktop.
Se integró la herramienta de **Parcel** para automatizar y optimizar el codigo.

Clona el proyecto en tu computadora para poder hacer tus propios cambios.

## Runnning

Para iniciar el proyecto primero ejecuta:
```sh
npm install
```
Una vez instaladas las dependencias, inicia el proyecto:
```sh
npm start
```
Ahora ingresa en tu navegador http://localhost:2664/. Ya puedes hacer cambios al proyecto y verlos en tiempo real.

## Building

Si quieres enviar tu proyecto a distribución ejecuta:
```sh
npm run build
```
Se creará automaticamaente una carpeta llamada "dist" donde estará el codigo minificado (_para que pese menos_).

## Deploy

Para subir el codigo a **GitHub Pages** solo ejecuta:
```sh
npm run deploy
```
Con esto, se creará una rama en tu repositorio (_gh-pages_) donde solo vivirá el codigo dentro de la capreta "dist".
> Importante hacer build antes de desplegar, para tener el codigo optimizado.
