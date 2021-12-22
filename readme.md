# Encabezados



Podemos crear encabezados haciendo uso de #, así como en HTML tenemos encabezados con niveles del 1 al 6 y en **Mark Down** debemos escribir tantos # como nivel deseamos.



## Párrafos



Se crean al escribir texto, para saltos de línea damos un **salto de línea** y para otro párrafo son dos.



## Listas



Se crean con el símbolo ***** para listas no ordenadas y para listas ordenadas usamos los números seguidos en de un punto:



- Elemento 1
- Elemento 2
  - Sub-elemento 1
    - Sub-elemento 1
- Elemento 3



1. Elemento 1
   1. Sub-elemento1
      1. Sub-elemento1
2. Elemento 2
3. Elemento 3





## Imágenes 



Se crean usando el signo de exclamación seguido del texto alternativo entre corchetes y luego la ruta de la imagen entre paréntesis:



![Logo](https://picsum.photos/200/)



## Enlaces



Colocamos el texto entre corchetes y entre paréntesis el enlace:



[Enlace a EDteam](https://ed.team)



## Referencia a enlaces e imágenes



Si tenemos varios enlaces que llevan al mismo sitio, podemos escribir el texto entre corchetes y luego, preferiblemente al final del documento, escribimos los corchetes con el texto antes escrito seguido de dos puntos:



> Cita que contiene varios enlaces a [EDteam], porque en la página de [EDteam] pude aprender **Mark Down**.



[EDteam]: https://ed.team



Con las imágenes podemos escribir entre corchetes un nombre que queramos asignar a la imagen en lugar de la ruta, luego para hacer la referencia es igual como lo hicimos con los enlaces:



![Imagen de Lorem Picsum][lorem_picsum]



[lorem_picsum]: https://picsum.photos/150/



## Código



Podemos escribir código `en línea` haciendo uso del símbolo **`**, y para bloques de código el texto de se debe encerrar entre tres de estos caracteres, y luego de los tres caracteres de apertura podemos indicar el lenguaje para que se cree una clase con la que podremos darle estilos con CSS:



```javascript
let target = True

for (var i = 0; i < 10; i++) {
    console.log(i)
}
```



``````html
<h1>Ejemplo de encabezado</h1>
``````



## Formato de texto



Podemos crear negritas, itálicas, o combinación de estas con el símbolo *****, encerrando con uno para *itálica* y dos para **negrita**.



Para el texto tachado usamos el símbolo **~**, ~~de esta manera~~ encerrando el texto en dos de estos.



<!-- Comentario -->



Para el texto <u>subrayado</u>, podemos usar la etiqueta **u** como en **HTML**.