# ÍCONOS Y MANEJO DE BACKGROUD HOVER

El background hover es la animación que cuando se pasa el cursor por encima de un objeto, aparece una sombra alrededor.

Cambios en main.css

```
/* Se crea el hover en el main input container. El hover es que
cuando pase el cursor por encima haz algo */
main .main-input-container:hover
{
    /* Se genera el sombreado alrededor del contenedor */
    box-shadow: 0 1px 6px 0 #20212447;
    /* Se agrega un tono mas oscuro al border del contenedor */
    border-color: #dfe1e500;
}

/* Ícono de la lupa */
main .main-input .search-icon
{
    /* se agregan el íconos */
    background-image: url('https://img.icons8.com/android/24/000000/search.png');
    /* No se repita el icono si hay espacio */
    background-repeat: no-repeat;
    /* Se centra el icono */
    background-position: center;
    /* Se ajusta al contenedor */
    background-size: contain;
    /* Tamaño de la imagen  */
    width: 18px;
    height: 18px
}

/* Ícono del microfono */
main .main-input .micro-icon
{
    /* se agregan el íconos */
    background-image: url('https://www.gstatic.com/images/branding/googlemic/2x/googlemic_color_24dp.png');
    /* No se repita el icono si hay espacio */
    background-repeat: no-repeat;
    /* Se centra el icono */
    background-position: center;
    /* Se ajusta al contenedor */
    background-size: contain;
    /* Tamaño de la imagen  */
    width: 18px;
    height: 18px;
    /* Como este icono si es interativo se agrega el cursor 
    de una mano */
    cursor: pointer;
}
```