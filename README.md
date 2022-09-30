
## Hooks / React Router

Connect your login page submit button to your API Login Endpoint using useEffect hook and fetch:
Implement basic React Router scaffolding files and a basic landing page component
Render on your landing page the tasks list using your /tasks endpoint, make sure you populate your MongoDB Database with tasks, map every task to your UI component design.

BACK
Correr el back colocando la variable de entorno 
MONGODB_URI=mongodb+srv://natalia:natalia123@cluster0.v4yk0md.mongodb.net/laboratorio3?retryWrites=true&w=majority

Luego de ello se corre de forma local el back como se muestra a continuación 
 
Para validar que funcione se prueba en postman la lista de usuarios registrados
 
Si se desea se pueden registrar mas usuarios para probar que funcione de forma correcta el login en el front

FRONT
Instalar todos los paquetes colocando npm install en consola
Luego colocar npm start y se nos debe abrir la pagina de login como se muestra a continuación:
 
Para ingresar se debe colocar el nombre y apellido, por ahora se puede ingresar con los siguientes usuarios:
•	Username: natalia
•	Apellido: orjuela
•	Username: andres
•	Apellido: Sandoval

Al momento de colocar las credenciales correctas se nos abrirá la pagina de tareas

 
Se puede evidencias que hay dos tareas agregadas para poder agregar o consultar una tarea se debe dar clic en el botón SELECT TASK como se muestra a continuación
 

Si se selecciona una tarea en la tabla inferior se verá su información 

Si se selecciona Add task nos enviará a la pagina de agregar tareas


 
Si llenamos los datos y añadimos la tarea nos enviará a la pagina principal y podremos verla y seleccionarla
 


