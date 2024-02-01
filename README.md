🌍 Curso de Economía de Equilibrio General 📊

¡Bienvenidos a la página del curso de Economía de Equilibrio General! Este repositorio está diseñado para ser un recurso integral para estudiantes que se embarcan en un emocionante viaje hacia el mundo del modelado económico y la inferencia causal. Aquí encontrarás una variedad de materiales, códigos y recursos meticulosamente elaborados para mejorar tu comprensión de la teoría del equilibrio general y sus aplicaciones.

Acerca de Este Curso 🏫

La Economía de Equilibrio General es un área crucial en el estudio de la economía que se ocupa de las complejas interrelaciones entre diferentes mercados y agentes en una economía. En este curso, exploraremos los fundamentos del modelado económico, nos adentraremos en la microeconometría y entenderemos las sutilezas de la inferencia causal en economía.

Contenidos del Curso 📚

Apuntes de Clases: Notas detalladas que cubren cada tema. Encuentra explicaciones teóricas junto con ejemplos del mundo real.
Ejemplos de Código: Fragmentos de código prácticos en Python/R que demuestran cómo implementar varios modelos de equilibrio general.
Tareas: Tareas semanales para probar tu comprensión y aplicación de los conceptos aprendidos.
Pautas del Proyecto: Información sobre el proyecto del curso, incluyendo objetivos, cronogramas y criterios de evaluación.
Comenzando 🚀

Para comenzar con el curso:

Clona el Repositorio: Usa git clone [enlace-del-repositorio] para obtener una copia local de este material del curso.
Instala las Dependencias: Asegúrate de tener instalado todo el software y las bibliotecas necesarias. Consulta requirements.txt.
Explora el Material: Comienza con las notas introductorias y trabaja progresivamente en las lecciones y ejercicios de codificación.
Contribuyendo al Curso 🤝

¡Tus contribuciones hacen este curso mejor para todos! Si deseas contribuir, por favor:

Envía Pull Requests: Para agregar recursos, corregir errores o proporcionar códigos mejorados.
Reporta Problemas: Si encuentras errores o tienes sugerencias, no dudes en reportar un problema.
Mantente Conectado 📡

Foro del Curso: Únete a la discusión, haz preguntas y colabora con compañeros estudiantes y profesores.
Formulario de Retroalimentación: Tu retroalimentación es invaluable para mejorar este curso.
Agradecimientos 🙏

Gracias a todos los contribuyentes, estudiantes y personal que hacen posible este curso.


Tutorial: Configuración de Julia con Jupyter en Visual Studio Code

Introducción

En este tutorial aprenderás a instalar y configurar Julia, Visual Studio Code (VS Code), y las herramientas necesarias para trabajar con Jupyter Notebooks en VS Code utilizando el lenguaje de programación Julia. Esta guía está pensada para que incluso quienes no tengan experiencia previa puedan seguir los pasos fácilmente.

Paso 1: Descargar e Instalar Julia

Visita la página oficial de Julia: Ve a https://julialang.org/downloads/ para encontrar la versión más reciente de Julia.
Elige la versión adecuada para tu sistema operativo (Windows, MacOS, Linux).
Descarga el instalador y ejecútalo. Sigue las instrucciones en pantalla para completar la instalación.
Durante la instalación, asegúrate de marcar la opción para agregar Julia al PATH si estás en Windows. Esto facilitará ejecutar Julia desde cualquier terminal.
Verifica la instalación: Abre una terminal (o Command Prompt en Windows) y escribe julia. Deberías ver la interfaz de Julia.
Paso 2: Descargar e Instalar Visual Studio Code (VS Code)

Visita la página oficial de VS Code: Ve a https://code.visualstudio.com/ y descarga el instalador para tu sistema operativo.
Ejecuta el instalador y sigue las instrucciones en pantalla.
Abre VS Code una vez instalado.
Paso 3: Instalar la Extensión de Julia para VS Code

Abre VS Code.
Ve a Extensiones: Puedes hacerlo haciendo clic en el ícono de extensiones en la barra lateral izquierda o presionando Ctrl+Shift+X.
Busca "Julia" en la barra de búsqueda de extensiones.
Instala la extensión Julia desarrollada por 'julialang'. Esta extensión proporciona soporte para el lenguaje Julia, incluyendo características como autocompletado, snippets, y soporte para Jupyter Notebooks.
Paso 4: Configurar Jupyter Notebooks para Julia en VS Code

Abre VS Code y luego abre una nueva terminal dentro de VS Code (puedes hacerlo con Ctrl+).
En la terminal, escribe julia para iniciar Julia.
En el prompt de Julia, instala el paquete IJulia, que proporciona soporte para Jupyter. Hazlo ejecutando el siguiente comando:
julia
Copy code
using Pkg
Pkg.add("IJulia")
Espera a que la instalación finalice. Esto puede tomar unos minutos.
Paso 5: Crear un Nuevo Jupyter Notebook con Julia

En VS Code, ve a la vista de Explorer y haz clic en el botón "New File" (nuevo archivo).
Nombra el archivo con la extensión .ipynb (por ejemplo, mi_notebook.ipynb). Esto creará automáticamente un Jupyter Notebook.
Selecciona el kernel de Julia en la esquina superior derecha del notebook. Si has instalado Julia y el paquete IJulia correctamente, deberías ver un kernel de Julia disponible.
¡Listo! Ahora puedes escribir y ejecutar código de Julia dentro de tu Jupyter Notebook en VS Code.
Consejos Finales

Explora las funcionalidades: VS Code y Julia tienen muchas funcionalidades y paquetes interesantes. No dudes en explorar y experimentar.
Consulta documentación y foros: Si tienes dudas o problemas, la documentación oficial de Julia, VS Code y los foros de la comunidad pueden ser de gran ayuda.
Practica con ejemplos: Una buena manera de aprender es practicando con ejemplos de código y modificándolos para ver qué sucede.
¡Eso es todo! Has configurado exitosamente Julia con Jupyter en VS Code y estás listo para comenzar a programar. Recuerda que la práctica y la curiosidad son claves en el aprendizaje de cualquier lenguaje de programación. ¡Disfruta explorando las posibilidades que Julia te ofrece en el mundo de la ciencia de datos y más allá!