# TaskFLow
Sistema de gestión de tareas. Andrés Hinojosa - Sistemas de Información
--------Introducción
En un mundo cada vez más dinámico y exigente, la capacidad de gestionar eficazmente las tareas es esencial para el éxito personal y profesional. El proyecto TaskFlow nace con el objetivo de proporcionar a los usuarios una herramienta intuitiva y completa para administrar sus tareas de manera eficiente, permitiendo un seguimiento claro del progreso y una gestión óptima del tiempo.


--------Objetivos del Proyecto:

-Desarrollar un software de administración de tareas robusto y fácil de usar.
-Permitir a los usuarios agregar, modificar y eliminar tareas de manera ágil.
-Facilitar el cambio de estado de las tareas, incluyendo marcadores de pendiente, en curso y completadas.
-Generar informes detallados sobre el estado de las tareas en curso y las completadas.
-Mejorar la productividad y la organización personal de los usuarios mediante una gestión inteligente de tareas.

--------Características Principales:

Interfaz intuitiva: Diseño amigable y fácil de usar para usuarios de todos los niveles de habilidad.
Gestión flexible de tareas: Posibilidad de agregar, editar y eliminar tareas según las necesidades del usuario.
Seguimiento de estado: Permitir a los usuarios marcar el estado de las tareas para un seguimiento claro del progreso.
Generación de informes: Funcionalidad para generar informes detallados sobre el estado de las tareas, facilitando la toma de decisiones informadas.


--------Planificación

	16 de Febrero, 2024 (Viernes)
	Diseño de la Interfaz de Usuario
	Plazo de Cumplimiento: 16 de Febrero, 2024
	Responsable: Andrés Hinojosa 1

	17 de Febrero, 2024 (Sábado)
	Desarrollo del Sistema de Gestión de Tareas
	Plazo de Cumplimiento: 17 de Febrero, 2024
	Responsable: Andrés Hinojosa 2

	18 de Febrero, 2024 (Domingo)
	Implementación de la Funcionalidad de Agregar Tareas
	Plazo de Cumplimiento: 18 de Febrero, 2024
	Responsable: Andrés Hinojosa 1

	19 de Febrero, 2024 (Lunes)
	Implementación de la Funcionalidad de Modificar Tareas
	Plazo de Cumplimiento: 19 de Febrero, 2024
	Responsable: Andrés Hinojosa 2

	20 de Febrero, 2024 (Martes)
	Implementación de la Funcionalidad de Eliminar Tareas
	Plazo de Cumplimiento: 20 de Febrero, 2024
	Responsable: Andrés Hinojosa 1

	21 de Febrero, 2024 (Miércoles)
	Desarrollo del Sistema de Cambio de Estado de Tareas
	Plazo de Cumplimiento: 21 de Febrero, 2024
	Responsable: Andrés Hinojosa 2

	22 de Febrero, 2024 (Jueves)
	Implementación de la Funcionalidad de Generación de Informes
	Plazo de Cumplimiento: 22 de Febrero, 2024
	Responsable: Andrés Hinojosa 1



--------Diseño

#################################Estructura del Software
El software está diseñado para funcionar en la consola del navegador, lo que permite a los usuarios interactuar con el sistema a través de comandos de texto.
La estructura del software se divide en los siguientes componentes principales:

	Interfaz de Línea de Comandos (CLI): Permite a los usuarios ingresar comandos de texto para realizar acciones como agregar, modificar, eliminar y listar tareas.

	Manejador de Comandos: Interpreta los comandos ingresados por el usuario y ejecuta las acciones correspondientes en función de la entrada.

	Persistencia de Datos: Utiliza archivos JSON para almacenar y recuperar información sobre las tareas del usuario. Cada tarea se guarda como un objeto JSON con atributos como nombre, descripción, estado, etc.


#################################Funcionalidades Principales
El software ofrece las siguientes funcionalidades principales a través de su interfaz de línea de comandos:

	Agregar Tareas: Permite al usuario agregar nuevas tareas especificando detalles como nombre, descripción, fecha límite, etc.

	Modificar Tareas: Permite al usuario modificar los detalles de una tarea existente, como su nombre, descripción o fecha límite.

	Eliminar Tareas: Permite al usuario eliminar una tarea existente de la lista.

	Listar Tareas: Muestra una lista de todas las tareas almacenadas en el sistema, junto con detalles como su nombre, descripción, estado, etc.
