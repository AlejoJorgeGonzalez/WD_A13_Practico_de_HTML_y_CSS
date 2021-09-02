# MANEJO DE ÍCONOS E IMÁGENES EN ETIQUETAS

Se crea la clase para conectarse con el CSS para agregar la imagen del ícono y la imagen del usuario

```
 <ul class="nav-right-section">
                <li>
                    <a href="">Gmail</a>
                </li>
                <li>
                    <a href="">Imágenes</a>
                </li>
                <!-- Clase para colocar la imágen de menu -->
                <li class="menu-icon">
                    <a href=""></a>
                </li>
                <li>
                    <!-- Se agrega la imágen del perfil -->
                    <a href="">
                        <img src="https://lh3.googleusercontent.com/ogw/ADea4I4toqzumjiHhJKWsh4anU_OOIjmQjY0s7DWbqzSJg=s32-c-mo" alt="">
                    </a>
                </li>
            </ul>
```

Se agrega el ícono

```
nav .nav-right-section .menu-icon
{
    /* Se trae la imagen de manú desde internet */
    background-image: url('https://static.thenounproject.com/png/756729-200.png');
    /* Cuando queda un espacio en un contenedor, este trata de
    llenarlo repitiendo la imágen, por tanto se le dice que
    no se repita*/
    background-repeat: no-repeat;
    /* Se centra la imágen */
    background-position: center;
    /* El tamaño de la imagen se adapta al del contenedor*/
    background-size: contain;
    /* Tamaño de la imagen */
    width: 25px;
    height: 25px;
}
```

Se agrega la imágen 

```
nav .nav-right-section img 
{
    /* Se redondea los bordes para que se muestre como un 
    circulo */
    border-radius: 50%;
    /* Se separa la imágen del ícono de menú */
    margin-left: 10px;
}
```