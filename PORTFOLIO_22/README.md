Diseño de referencia -> https://purplefolio.framer.website/

Guía de Flexbox -> https://css-tricks.com/snippets/css/a-guide-to-flexbox/


ETIQUETAS SEMÁNTICAS DE HTML:

Son elementos de HTML de tipo contenedor (<div>) con "nombre"

- <nav></nav> -> etiqueta semántica que se usa para el contenido referente a la navegación de la web (menú)

- <header></header>

- <section></section>



EJERCICIO 28/03 ->

- Crear una nueva página de HTML llamada flexbox.html

- Generar todo el código de HTML de esta nueva página fijandonos en el index.html (el contenido del head será el mismo). En el cody solo será necesario añadir el div con la clase wrapper.

- Enlazar el index.html con el flexbox.html usando elementos <a></a>
(podemos crear en el menu del index.html una nueva opción que sea Flexbox y enlace con flexbox.html).

- En flexbox.html debemos crear un enlace a la guía de flexbox que se abra en una nueva pestaña del navegador y otro enlace para "Volver a la home" para volver al index.html.



EFECTO HOVER - PSEUDO CLASE HOVER

El efecto hover opsuedo clase hover es un estado de los elementos de HTML que podemos detectar usando un selector especial de CSS. Este estado se activa cuando el cursor del usuario está encima del elemento. Este efecto hover solo lo podemos detectar en la versión desktop de la web. Este efecto nos dar un feedback visual al usuario sobre la utilidad de algunos elementos e indicar que son clickables.


Propiedad -> transition

El transition se debe encontrar en el selector del estado inicial para que esta transicion funcione cuando el cursor pasa a estar encima del elemento y para cuando sale.


Propiedad -> transform

La propiedad transform puede tomar varias funciones como valores. Las más importantes son scale(), translate(), rotate(), skew(). 

Estas funciones solo van a hacer efecto sobre elementos tipo bloque -> display: block;

Lo mas interesante de estas funciones es que podemos modificar un elemento (en tamaño, posicion, rotacion, etc) sin afectar al resto de elementos o a la estructura.



POSICIONAMIENTO ABSOLUTO DE CSS:

Con el posicionamiento absoluto podemos colocar algunos elementos de HTML posicionados encima de otros en el eje z.

Para poder posicionar un elemento de forma absoluta usaremos la propiedad position: absolute; y controlaremos ese elemento dentro de un contenedor con la propiedad position: relative;




MEDIA QUERIES - MEDIA QUERY 

Es una regla especial de CSS que nos permite detectar el tipo de dispositivo que esta usando el usuario y las dimensiones de la pantalla de este dispositivo (device). Al detectar el ancho de la pantalla nosotros podremos activar ciertos selectores de CSS.

Estas reglas @media {} se encontrarán siempre al final del archivo de CSS y dependiendo de mis diseño y del funcioanmeinto de la web necesitare una o varias.