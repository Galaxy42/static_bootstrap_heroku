Static_bootstrap_heroku
=======================

 A simple static site that uses Bootstrap :)
 
 Este proyecto usa:
========================
[Bootstrap](https://github.com/twbs/bootstrap)

[HTML5 Boilerplate](https://github.com/h5bp/html5boilerplate.com)

[Heroku](https://heroku.com/)

[Heroku Button for Developers](https://blog.heroku.com/archives/2014/8/7/heroku-button)

[Heroku-BuildPack_Static](https://github.com/pearkes/heroku-buildpack-static) by [@Pearkes](https://github.com/pearkes)

Crea tu propio proyecto a partir de él(Lo que estabas esperando, el famoso botón).
============================================================================
<!-- [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy) -->

Como usarlo
================================

Una vez que tengas tu app creada bájala para poder subir tus estáticos a Heroku:
```
heroku clone -a [Nombre de tu app]
````
Recuerda sustituir [Nombre de tu app] por el nombre de tu app.

Una vez que hagas los cambios(Por ejemplo, quitar este README.md porque Heroku no lo necesita):
```
git add .
```
```
git commit -m "Tu mensaje de commit"
```
```
git push heroku master
```

Espero que te sirva este recurso y pronto tendrá mas cosas :D
