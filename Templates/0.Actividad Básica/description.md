# Actividad de prueba: Nombre de la actividad

Enunciado de la actividad en formato [Markdown][Markdown]. 
Por ejemplo: "Armá un programa que te permita lograr que el Alien toque el botón.
Para eso, investigá las primitivas disponibles, y la forma en que podés lograr que el Alien haga lo que indica el programa."

## Tablero esperado

En los enunciados de una actividad se pueden armar pequeños tableros de muestra, con o sin vestimentas.

### Con vestimenta
<center>
  <gs-board attire-src="Alien">
    GBB/1.0
    size 4 1
    cell 3 0 Rojo 1 Verde 1
    head 3 0
  </gs-board>
</center>

### Sin vestimenta
<center>
  <gs-board attire-src="Alien">
    GBB/1.0
    size 4 1
    cell 3 0 Rojo 1 Verde 1
    head 3 0
  </gs-board>
</center>

## Cierre

Además, se pueden agregar otras explicaciones. Por ejemplo, en un proyecto hay varios archivos que configuran el proyecto, y que no admiten comentarios (al menos no que sean visibles). Entre ellos encontramos:
  * `contents.gbk`, que contiene el código inicial que ve el estudiante al entrar por GobstonesJr,
  * `cover.png`, que contiene la imagen (usualmente de 300x300) que se muestra en el selector de un curso (cuando hay curso activo),
  * `meta.yml`, que contiene datos de la configuración de las opciones del entorno,
  * `assets/boards/*.gbb`, que contiene los distintos tableros iniciales (en formato `.gbb`)
  * `assets/attires/*`, que contiene una carpeta con cada una de las vestimentas que se ofrecerán en la actividad.

  Existen más opciones que se mostrarán en una actividad completa.
  También puede consultarse el ["Manual Técnico para Usuarios"][ManualUsuarios].

[ManualUsuarios]: https://github.com/gobstones/gobstones-web/wiki/Manual-t%C3%A9cnico-para-usuarios
[Markdown]: https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
