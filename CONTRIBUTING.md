# Guía de colaboración

Puedes [crear una _pull request_](https://help.github.com/en/articles/creating-a-pull-request) con la documentación que incluimos a continuación o [crear un _issue_](https://github.com/comunidad-tecnologica/alicante/issues/new).

## Añadir una comunidad

Los datos de las comunidades están en `_data/communities.yaml`.

Para añadir una nueva comunidad siguiendo este formato:

```
- title: 
  web: 
  twitter-alias: 
  meetup-url:
```

No es necesario que incluyas todos los datos para cada comunidad: web, alias de Twitter o URL de Meetup. Tal vez sólo dispone de uno o dos de esos datos.

## Añadir un evento anual

El listado se encuentra en el fichero `index.md`.

## Añadir cualquier otro dato de interés

Adelante, las ideas son bienvenidas :wink:

## Probarlo en local

### Requisitos

- [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.4.0 o superior, puedes comprobar tu versión con `ruby -v`.
- [RubyGems](https://rubygems.org/pages/download), compruébalo con `gem -v`.
- [GCC](https://gcc.gnu.org/install/) y [Make](https://www.gnu.org/software/make/). Puedes comprobarlo con `gcc -v`, `g++ -v` y `make -v`.
- [Bundler](https://bundler.io/), comprueba si ya lo tienes instalado con `bundle -v`. En caso de que no sea así puedes instalarlo con `gem install bundler`.

### Instalación de las dependencias

```
$> bundle install
``` 

### Construcción en local

Podrás ver el resultado en http://localhost:4000 :

```
$> bundle exec jekyll serve
``` 
