# SASS = Syntactically Awesome StyleSheet

__Autor__ : Alejandro Ruiz Prieto

***GitHub*** : 

-Es un estandar en la industria
-Compatible con muchos frameworks

## Ventajas

1. Mejor orden y estructura.
2. Tiene caracteristicas que no existen en CSS.
3. Podemos incorporar CSS sin problema.
4. Menos codigo (SASS) -> Anidacion.

## Desventajas
1. Nueva sintaxis por aprender.
2. Se debe de compilar (No es nativo en el navegador).
3. La anidacion puede dar problemas.
4. Capa caida.

## Sintaxis de Sass:

1. Variables(custom properties)-> :root {}

    ``$color : #e1e1e1;``

2. Anidacion en SASS:

>div
>    display:flex;
>    h1
>        margin-top:10rem;
>    p
>       margin-top:10rem;

3. Extensiones

- .sass:
- .scss: 

## SASS se compila -> .css (Node.js, webpack, gulp)

npm install -g node sass