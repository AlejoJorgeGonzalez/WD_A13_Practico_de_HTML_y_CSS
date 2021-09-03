# ESTILOS EN LA SECCIÓN DEL INPUT

## Cambios en el main.css

```
/* Estilos para el input */
main .main-input
{
    width: 530px;
    /* Se centra de manera horizontal el input */
    margin: 0 auto;
    /* Separa el input de los botones */
    margin-bottom: 35px;
}

/* Clase que lleva directamente al input que contiene tres 
secciones */
main .main-input-container
{
    width: 525px;
    border-radius: 100px;
    /* Color del borde */
    border: 1px solid #dfe1e5;
    /* Se ajusta los elementos del input */
    display: flex;
    /* Se colocan los elementos en el centro */
    justify-content: center;
    align-items: center;
}

main .main-input input
{
    width: 450px;
    height: 40px;
    /* Se quita el borde oscuro */
    border: none;
    outline: none;
}
```