# Sprint 9

- Contenido

  - NodeJs

- Objetivos:

  - Aplicar los conocimientos dados en clase.

  - Entender cómo y para qué se usan los métodos HTTPS.

  - Crear un API conectado a una base de datos.

- Proyecto
  - Crear un API para crear y actualizar tareas
    - Referencia - https://github.com/Angatupyry/sprint-5-ft/tree/day-6-node

Día 1

- ¿Qué es Node JS?

  - El alumno debe entender que NodeJs es un entorno de ejecución. La mejor manera de compararlo es aplicando el ejemplo de cómo Google Chrome puede leer código Javascript. Es decir, Node permite que código Javascript puede ser usado en el backend.

- ¿Es Node JS un lenguaje de programación?

- Instalar Node Js

Día 2

- Escribir algún código de Javascript y luego ejecutar desde la terminal
  - node index.js
- ¿Puedo tener acceso al DOM desde Node JS?, ¿por qué?

Día 3

- Inicializar un proyecto con npm

- ¿Qué diferencia existe en instalar una dependencia agregando –dev?

- Instalar las dependencias a utilizar. Si ya conocen cuáles serán las que se necesitan para el proyecto ya se pueden instalar Ej:
  - Express
  - Sequelize o Knex
  - Cors
  - Nodemon

Día 4

- ¿Qué es Express?
- ¿Hay algún otro framework en NodeJs que hace algo similar a Express?
- ¿Por qué express frente a otros frameworks?

Día 5

- Crear el proyecto con Express
- Crear una ruta que retorne un “Hola mundo”

Día 6

- Crear una ruta que retorne el objeto `task.js` adjunto
- Manejar los errores y mandar un mensaje de error al cliente.
- Ejemplo de retorno:

```js
    {
        "success": true,
        "message": "Lista de tareas",
        "data": task
    }
```

Día 7

- Crear una ruta que agregue una tarea.
- La ruta deberá de agregar un objeto al array de tareas (adjunto en el proyecto) y guardarlo en memoria

Día 8

- Actualizar una tarea por id.
- La ruta deberá de modificar alguna propiedad del objeto seleccionado.
- Reestructurar el proyecto usando routes
- Crear un archivo para las rutas de tareas

Día 9

- Crear la conexión con la base de datos.
- Utilizar algún ORM para la conexión.

Día 10

- El get debe traer las tareas existentes de la base de datos

  - Realizar la lógica correspondiente al ORM seleccionado

- Las rutas post y put deben estar conectados a la base de datos

  - Realizar la lógica correspondiente al ORM seleccionado
