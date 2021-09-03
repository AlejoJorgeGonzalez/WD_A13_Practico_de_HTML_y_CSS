# MAQUETADO DE LA SECCIÓN PRINCIPAL

Para esta clase, se va a maquetar la etiqueta main, que contiene el logo de google, la barra de busqueda y de "voy a tener suerte"

```
<!-- Se maqueta la sección main del clone de google -->
    <main>
        <!-- La página de google consta de tres secciones -->
        <section class="main-logo">
            <!-- La primera secciones es la imagen de google -->
            <img src="" alt="">
        </section>
        <section class="main-input">
            <!-- Esta sección es un poco mas compleja, ya que
            tiene una barra que se sombre cuando el puntero 
            pasa por encima, ademas tiene nos íconos, uno de la
            lupa y el otro el del microfono -->
            <div class="main-input-container">
                <!-- Se agrega un span para el ícono de la lupa,
                note que este ícono no tiene ninguna 
                funcionalidad, por tanto se utliza span y no un
                ancla, se agrega la clase search-icon-->
                <span class="search-icon">
                </span>
                <!-- Input para que el usuario ingrese la 
                busqueda -->
                <input type="text">
                <!-- Ancla para agregar un ícono de microfono 
                que va a tener una funcionalidad -->
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