# proyecto_colaborativo
Descripción del Código
Clases y Métodos

    AccesoDatosTUDU:
        Inicializa la interfaz gráfica.
        Establece la conexión a la base de datos y crea la colección de tareas si no existe.

    Conexion:
        Maneja la conexión a MongoDB.
        Permite insertar, actualizar y eliminar documentos y tareas.

    Tarea:
        Representa una tarea con descripción, estado (realizada o pendiente) y fecha.

    VistaTUDU:
        Proporciona la interfaz gráfica que permite al usuario gestionar las tareas.

Conexión a MongoDB

La conexión a MongoDB se establece a través de la URL mongodb://localhost:27017. Si MongoDB está en otro servidor o puerto, ajusta el enlace de conexión.
Contribuciones

Uso
1. Ejecutar la aplicación:

    Una vez configurado el proyecto, puedes ejecutar la clase AccesoDatosTUDU.java que es el punto de entrada de la aplicación.
    Se abrirá una interfaz gráfica de usuario (GUI) donde podrás agregar, modificar, eliminar y consultar tareas.

2. Interacción con la interfaz:

La interfaz tiene los siguientes controles:

    Campos de texto: Para ingresar la descripción de la tarea y la fecha.
    Botones de radio: Para seleccionar si la tarea está pendiente o ya está realizada.
    Botones:
        Agregar: Para agregar una nueva tarea.
        Modificar: Para modificar una tarea seleccionada.
        Eliminar: Para eliminar una tarea seleccionada.
    Lista de tareas: Se muestra una lista con todas las tareas disponibles en la base de datos.

3. Operaciones disponibles:

    Agregar tarea: Ingresa una descripción de tarea, fecha y estado, luego haz clic en "Agregar".
    Modificar tarea: Selecciona una tarea de la lista, edita los campos de texto y haz clic en "Modificar".
    Eliminar tarea: Selecciona una tarea de la lista y haz clic en "Eliminar".

4. Base de Datos:

    El proyecto utiliza MongoDB como base de datos para almacenar las tareas.
    Se crea una base de datos llamada tudu y una colección tareas, donde cada tarea es almacenada como un documento con fecha y datos asociados.
