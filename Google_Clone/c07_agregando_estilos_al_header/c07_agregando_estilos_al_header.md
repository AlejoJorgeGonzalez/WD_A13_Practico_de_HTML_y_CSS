# Agregando Estilos al Header

HTML tiene dos tipos de etiquetas, las etiquetas contenedoras que son etiquetas de cajas y las etiquetas de contenido que son las que tiene todo el contenido que el usuario va a ver, como son los textos, las imagenes, los videos, etc. 

Utilizar el HTML semántico como el header, footer, el main, entre otras, nos va a permitir ubicar mejor el contenido, sin tener muchos problemas con el CSS.

Se trabajan tres tipos de layout que son los displays, el display es como las etiquetas contenedoras se comportan entre ellas y nos ayuda a posicionar su contenido. Hay tres tipos, el display layout, el display grid y el display flex. 

El header y el footer de la página se trabaja con estos tres tipos de layout.

Los navegadores por defecto tiene una parametros establecidos como son el margin o el padding, estos valores se puede resetear con la etiqueta *.  

```
*
{
    margin: 0;
    padding: 0;
}
```

Para este caso, no se coloca el *, sino directamente en el body.

```
body 
{
    margin: 0;
    padding: 0;
}
```

Para ocupar todo el ancho de la pantalla con el header se coloca un width del 100%.

```
header 
{
    width: 100%;
    height: 60px;
}
```

Para terminar y colocar los elementos al final de la pantalla, este se realiza por medio de un display flex con una alineación de flex-end.

```
header nav 
{
    display: flex;
    justify-content: flex-end;
}
```