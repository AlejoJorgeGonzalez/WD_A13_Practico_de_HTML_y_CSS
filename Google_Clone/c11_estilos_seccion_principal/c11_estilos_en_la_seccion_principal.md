# ESTILOS EN LA SECCIÓN PRINCIPAL

En esta clase se le dan los estilos a la etiqueta main del clone de google

## Cambios en el index.html
```

    <main>
        <section class="main-logo">
            <!-- Se agrega la url del logo de google -->
            <img src="https://cdn.pngsumo.com/google-logo-2015-png-image-purepng-free-transparent-cc0-png-google-logo-transparent-10000_3382.png" alt="">
        </section>
        <section class="main-input">
            <div class="main-input-container">
                <span class="search-icon">
                </span>
                <input type="text">
                <a class="micro-icon" href=""></a>
            </div>
        </section>
        <section class="main-buttons">
            <div>
                <button>Buscar con Google</button>
            </div>
            <div>
                <button>Me siento con suerte</button>
            </div>
        </section>
    </main>
```

## Cambios en el main.css
```
main
{
    /* Se le agrega espacio en la parte superior para separarlo
    del header */
    margin-top: 150px;
    /* Se centra el contenido */
    text-align: center;
}

/* Sección del logo */
main .main-logo
{
    width: 530px;
    /* El auto divide el espacio sobrante en dos y los asigna
    a cada lado para que quede centrado, en este caso de 
    manera horizontal */
    margin: 0 auto;
    margin-bottom: 35px;
}

/* Se ajusta el tamaño del logo a lo que se necesita para 
verse bien */
main .main-logo img
{
    width: 300px;
}
```
