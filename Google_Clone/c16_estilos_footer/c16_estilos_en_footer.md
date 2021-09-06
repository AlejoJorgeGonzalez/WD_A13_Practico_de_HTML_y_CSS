# ESTILOS EN FOOTER

## Cambioes el main.css

```
/* Estilos al contenedor de footer en general */
footer
{
    /* Tamaño del footer */
    width: 100%;
    height: 50px;
    /* Se coloca el footer totalmente en el final de la
    pantalla */
    position: absolute;
    bottom: 0;
    /* Se coloca un display grid que sirve para despues con
    el grid-template.columns, dividirlos en 2 fracciones */
    display: grid;
    grid-template-columns: 1fr 1fr;
    /* Se alinean los elementos */
    align-items: center;
    /* Tamaño de la fuente */
    font-size: 13px;
    /* Color del footer */
    background-color: #f2f2f2;
    /* Agregamos un borde superior */
    border-top: 1px solid #e4e4e4;
}

footer ul
{
    /* Aumentamos el margen la lista  */
    margin: 10px;
    /* Se elimina los bullets de la lista */
    list-style: none;
    /* Se posiciona la lista de forma horizontal */
    display: flex;
    /* Acercamos los elementos a la izquierde de la pantalla */
    padding-left: 0;
}

footer .footer-left
{
    /* Se envia los elementos totalmente a la izquierda */
    justify-self: left;
}

footer .footer-right
{
    /* Se envia los elementos totalmente a la derecha */
    justify-self: right;
}

footer ul li a
{
    /* Se separan los elementos entre si */
    margin: 10px;
    /* Se camnbia el color de fuente */
    color: #5f6368;
}
```