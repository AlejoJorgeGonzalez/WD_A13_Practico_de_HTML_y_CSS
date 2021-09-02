# POSICIONAR UNA LISTA EN HORIZONTAL 

En esta clase se va a posicionar los elementos del header de manera horizontal.

Es de recordar que en el HTML se pueden crear clases con el fin de tener un identificador con el cuál conectarse con el CSS y darle un estilo unico, tambien existen los id, su diferencia radica en que las clases son genericos mientras que los id son para elementos unicos.

En el HTML se crea la clase para conectarse con el CSS

```
<ul class="nav-right-section">
```

El height ya tiene una altura dada por su etiqueta padre header, por lo que se coloca auto, para que se acomode a la altura de su etiqueta padre. se retira los bullets con list-style y por último se coloca los elementos de manera horizontal con justify-content y align-items.

```
header nav .nav-right-section 
{
    width: 250px;
    
    height: auto;
    display: flex;
    list-style: none;
    justify-content: center;
    align-items: center;
}
```

Se separan los elementos de header y se le da color a la fuente.

```
nav .nav-right-section a
{
    margin-right: 10px;
    color: #000000;
}
```

Por último se eliminan el subrayado de los elementos que estan dentro una etiqueta ancla con text-decoration y se agrega el efecto de una mano en el puntero del mouse cuando se pasa por encima del elemento con cursor: pointer.

```
a 
{
    text-decoration: none;
    cursor: pointer;
}
```