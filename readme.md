# Actividad Presencial 2 de Jquery

https://github.com/DesafioLatam/Blearning-Frontend-E14CP2A1

## Se pide construir una aplicación para listar tareas pendientes, o sea una aplicación del tipo To Do.

- La aplicación consiste en la creación de tareas que pueden ser editadas, marcadas como completadas y eliminadas.

- Utilizando sistema de *grids* se debe dividir la página en **2 columnas** (Se puede utilizar Bootstrap):
    - En la columna de la izquierda: Crear un campo de texto donde el usuario pueda ingresar el texto del *ToDo* y un botón para confirmar la creación.
    - En la columna de la derecha: Se deben listar los *ToDo* creados. Cada *ToDo* en un *row*.

- Cada *ToDo* de la lista debe tener a su lado un botón para marcar como completado y uno para eliminar el *ToDo*.

- El botón para marcar como completado debe tener una clase ***class='completable'***

- Seleccionar con jQuery la clase *completable* y agregar el evento **.onclick**.

- Al marcar un *ToDo* como completado:
    - El botón para marcar como completado debe cambiar de color.
    - El texto del *ToDo* debe ser tachado. (*text-decoration: line-through*)

- El botón de eliminar debe remover el *ToDo* de la lista.
