# ESTILOS EN LOS BOTONES

En esta clase se crean los estilos en los botones que faltan en la etiqueta main

## Cambios en el main.css

```
main .main-buttons
{
    /* Tamaño de los botones */
    width: 530px;
    /* Se posicionan en el crentro  y sean mas flexibles */
    margin: 0 auto;
}

main .main-buttons div
{
    /* Se colocan los botones en forma horizontal */
    display: inline-block;
}

main .main-buttons button
{
    /* Altura a los botones */
    height: 36px;
    /* Color de fondo de los botones */
    background-color: #f2f2f2;
    /* Se elimina el borde de los botones */
    border: 0;
    /* Tamaño de fuente */
    font-size: 14px;
    /* Color de la fuente */
    color: #5f6368;
    /* bordes mas grandes */
    border-radius: 5px;
    /* Espacio del boton dentro del contenedor padre, de 0 
    pixeles arriba y abajo y 15 pixeles derecha e izquierda */
    padding: 0 15px;
    /* Se separan mas los botones entre ellos */
    margin-right: 15px;
}

/* Efecto cuando pasa el cursor encima */
main .main-buttons button:hover
{
    /* Color de sombreado del borde del boton */
    border: 1px solid #c6c6c6;
    /* Sombra del  boton */
    box-shadow: 0 1px 1px #000001;
    /* Cambio de color de la fuente */
    color: #222;
}
```