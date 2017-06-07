Learning Laravel
===========

## Descripción:

<p align="justify">
	En este repositorio trataremos de documentar lo aprendido en el curso <b>Laravel 5.4 - Clon de Reddit</b> impartido por @gpopoteur.
</p>

## Especificaciones Técnicas:

En mi caso estoy usando:

* macOS Sierra 10.12.5
* ATOM 1.17.2
* Composer version 1.4.2
* Laravel Framework 5.4.25 (php artisan --version)

### Tópico 0 - Run

Podemos configurar XAMPP o MAMP para que funcionen como <i>servidor</i> en mi caso por practicada usaré lo siguiente:

* Abrimos terminal y nos movemos a la <i>PATH</i> del proyecto.
* Corremos:
```
php artisan serve
```
* El <i>prompt</i> se queda suspendido y nos muestra:
```
Laravel development server started: <http://127.0.0.1:8000>
```

Basta copiar la URL (en mi caso: <i>http://127.0.0.1:8000</i>), pegarla en el navegador y dejar esa terminal abierta para que se siga ejecutando nuestro servidor virtual.

### Tópico 1 - Rutas

<p align="justify">
	<b>Def:</b> Rutas son un conjunto de URLs conectadas a porciones de código, el cual se ejecuta al ser llamadas estas URLs.
</p>

Las **rutas** se encuentran en la carpeta:

* *routes*

en el archivo:

* *web.php*
* *api.php*

Son básicamente lo mismo, están separados como una buena práctica.<br>
Las rutas que sean parte de un API se registren en api.php <br>
Las rutas que respondan a diferentes secciones de la aplicación se ubiquen en web.php

## Fuente

* [Curso](https://www.youtube.com/watch?v=XrrbV5YO2PY)