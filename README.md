Gestor de Tareas "TaskManager Pro"
Este proyecto es una aplicación web frontend desarrollada en Angular, diseñada para facilitar la administración de tareas en equipos remotos y mejorar la productividad. Forma parte de la primera versión funcional del producto "TaskManager Pro" de la empresa TechNova Solutions.

Requisitos Funcionales
La aplicación cumple con los siguientes requisitos funcionales:

Lista de Tareas: Muestra una lista de tareas con atributos como título, descripción, estado y prioridad.
Gestión de Tareas:
Permite agregar nuevas tareas mediante un formulario.
Permite editar una tarea existente.
Permite eliminar tareas.
Estado de Tareas: Permite marcar tareas como completadas o pendientes.
Fechas: Registra la fecha de creación y la fecha de vencimiento de cada tarea.
Tiempo Restante: Calcula y muestra automáticamente el tiempo restante hasta la fecha de vencimiento.
Informes Visuales: Genera un informe visual con el porcentaje de tareas completadas versus pendientes.
Filtrado y Búsqueda:
Filtra tareas por estado (completada, pendiente, vencida) y por prioridad.
Permite buscar tareas por palabra clave (título, descripción).
Notificaciones: Muestra alertas o notificaciones visuales para tareas próximas a vencer.
Validación de Formularios: Incluye validación de formularios (campos requeridos, fechas válidas, mínimo de caracteres).
Diseño Responsive: Aplica un diseño responsive y limpio, compatible con escritorio y móvil.
Componentes Reutilizables: Crea componentes reutilizables (por ejemplo, task-item, task-filter, etc.).
Conexión API Rest: Las tareas deben ser obtenidas desde una API Rest conectada a una Base de Datos.
Requisitos Generales
El proyecto debe estar alojado en un repositorio Git de Organización y mantener control de versiones.
Debe tener configurado el archivo .gitignore.
Se debe trabajar en ramas feature/* y realizar al menos 10 commits significativos.
Incluye un README.md con la descripción del proyecto, cómo ejecutarlo localmente y vía Docker.
Se debe crear un Dockerfile que compile y sirva la aplicación tanto para el frontend como para el backend.
Asegurar que el contenedor pueda ejecutarse sin errores en cualquier sistema con Docker instalado.
Cómo Ejecutar el Proyecto
Ejecución Local (Asumiendo un Proyecto Angular Típico)
Para ejecutar la aplicación localmente, asegúrate de tener Node.js y npm (o yarn) instalados en tu sistema.

Clonar el Repositorio:
Bash

git clone https://github.com/Yiss0/Solemne2.git
cd Solemne2
Instalar Dependencias:
Bash

npm install
# o
yarn install
Iniciar la Aplicación:
Bash

ng serve
La aplicación debería estar disponible en http://localhost:4200/ en tu navegador.
Ejecución con Docker
Para ejecutar la aplicación usando Docker, asegúrate de tener Docker instalado y funcionando en tu sistema.

Construir la Imagen Docker: Desde la raíz del proyecto donde se encuentra el Dockerfile:
Bash

docker build -t taskmanager-pro-frontend .
Ejecutar el Contenedor Docker:
Bash

docker run -p 4200:80 taskmanager-pro-frontend
La aplicación estará accesible en http://localhost:4200/.
Commits Significativos
No fue posible obtener la lista de commits significativos directamente desde el repositorio de GitHub. Para ver el historial de commits, por favor, visita la página del repositorio en GitHub o clona el repositorio y usa el comando git log.
