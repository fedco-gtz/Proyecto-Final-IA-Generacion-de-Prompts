![Coderhouse](./Images/Readme/Coder.png)
# Inteligencia Artificial: Generación de Prompts - Comisión 84160
Profesor: SOSA, Alejandro &nbsp;&nbsp;[<img src="./Images/Readme/LinkedIn.png" alt="LinkedIn Logo" width="20" height="20">](https://www.linkedin.com/in/alejandrososa-encodeyourlife/)

Tutor Pedagógico: LUCERO, Edgardo &nbsp;&nbsp;[<img src="./Images/Readme/LinkedIn.png" alt="LinkedIn Logo" width="20" height="20">](https://www.linkedin.com/in/edgardolucero/)

Estudiante: GUTIERREZ, Federico &nbsp;&nbsp;[<img src="./Images/Readme/LinkedIn.png" alt="LinkedIn Logo" width="20" height="20">](www.linkedin.com/in/fedco-grrz)

![Proyecto Final](./Images/Readme/Portada.png)
## ÍNDICE

1. [Introducción](#introducción) 
2. [Objetivos](#objetivos) 
3. [Problema a abordar](#problema-a-abordar)  
4. [Propuesta de solución](#propuesta-de-solución)
5. [Viabilidad del proyecto](#viabilidad-del-proyecto)
6. [Metodología](#metodología)
7. [Herramientas y tecnologías](#herramientas-y-tecnologías)
8. [Implementación](#implementación)
9. [Actualizaciones del Proyecto Final](#actualizaciones-del-proyecto-final)
10. [Redes sociales y proyectos](#redes-sociales-y-proyecto)
_________________________________________________________________________________________________________
### INTRODUCCIÓN

El proyecto propuesto busca desarrollar un **Asistente Virtual para Profesores de Matemática** que simplifique la creación de actividades y exámenes mediante un sistema automatizado. Este asistente utilizará modelos de **Inteligencia Artificial (IA)** para generar ejercicios matemáticos personalizados, adaptados a diferentes niveles educativos y temas específicos. El proyecto busca mejorar la eficiencia del trabajo docente y contribuir a una experiencia de aprendizaje más enriquecedora para los estudiantes, combinando innovación tecnológica y necesidades pedagógicas. El asistente también incluirá una funcionalidad para **exportar los contenidos creados en formato PDF**, lo que facilita su presentación.

_________________________________________________________________________________________________________
### OBJETIVOS

El proyecto tiene **objetivos generales** y **objetivos específicos**.

Los **objetivos generales** del proyecto son:
*   Desarrollar un asistente virtual basado en inteligencia artificial que facilite a los profesores de Matemática la creación de actividades y exámenes personalizados, optimizando su tiempo y mejorando la calidad del material educativo.

Los **objetivos específicos** del proyecto son:
*   Diseñar un generador automático de problemas matemáticos adaptado a diferentes niveles educativos y temáticas.
*   Incorporar soluciones automáticas para los problemas generados, facilitando la corrección y revisión de los ejercicios.
*   Desarrollar una herramienta para exportar actividades y exámenes generados en formato PDF con diseño profesional.

______________________________________________________________________________________________________
### PROBLEMA A ABORDAR

El documento identifica como problema principal que la formulación de actividades y exámenes personalizados para estudiantes es una tarea que consume mucho tiempo y esfuerzo para los profesores de Matemática. Este proceso requiere diseñar problemas adecuados al nivel de los estudiantes, garantizar la variedad en los ejercicios y formatear los documentos de manera profesional. Todo esto puede generar estrés y reducir el tiempo disponible para otras actividades docentes.

*   La calidad de la enseñanza en Matemática depende en gran medida de la calidad de las actividades y evaluaciones diseñadas por los docentes.
*   Facilitar esta tarea mediante un asistente virtual que automatice parte del proceso permitiría a los profesores enfocarse en la enseñanza y en el acompañamiento de los estudiantes, mejorando la experiencia educativa.

______________________________________________________________________________________________________
### PROPUESTA DE SOLUCIÓN

La propuesta de solución es un **asistente virtual** basado en modelos de **Inteligencia Artificial (IA)** que ayude a los profesores de Matemática a generar actividades y exámenes de manera automática. Este asistente ofrecerá la opción de exportar las actividades generadas en **formato PDF**, listas para ser impresas o distribuidas digitalmente.

Las funciones claves del asistente incluyen:

*   **Generación de actividades:** Diseñar problemas matemáticos personalizados según el nivel educativo y los temas seleccionados por el profesor.
*   **Banco de preguntas:** Crear un banco de preguntas reutilizables que los docentes puedan consultar y modificar según sus necesidades.
*  **Exportación a PDF:** Formatear y exportar automáticamente las actividades y exámenes generados en un documento PDF con diseño profesional.

Los prompts a desarrollar incluyen:

*   **Diseño de problemas:** Generar ejercicios matemáticos en función de temas y niveles seleccionados (por ejemplo: álgebra, geometría, cálculo).
*   **Formato de documentos:** Personalizar el encabezado, pie de página y diseño general del PDF generado.
*  **Revisión automática:** Incluir soluciones a los problemas generados para facilitar la revisión y corrección.

_________________________________________________________________________________________________________
### VIABILIDAD DEL PROYECTO

El proyecto presenta una **viabilidad técnica** basada en la utilización de herramientas disponibles y un conjunto de datos existente.

*   **Herramientas disponibles**: Se utilizará **OpenAI** para la generación de problemas matemáticos y bibliotecas como **ReportLab o FPDF** para la exportación a formato PDF.
*   **Conjunto de datos**: El asistente podrá basarse en datos y estructuras de ejercicios matemáticos ya estandarizados, así como en patrones de diseño sugeridos por los usuarios.
*   **Etapas del proyecto**: El proyecto se desarrollará en etapas, incluyendo el desarrollo del generador de problemas, la integración de la funcionalidad de exportación, y las pruebas finales con docentes simulados.

La aplicación de **Inteligencia Artificial** permite la creación de actividades adaptadas a necesidades específicas, optimizando el tiempo de los docentes. Las herramientas seleccionadas son ampliamente utilizadas y documentadas, lo que garantiza un desarrollo eficiente y una curva de aprendizaje manejable.

_________________________________________________________________________________________________________
### METODOLOGÍA

La metodología del proyecto se enfoca en el **desarrollo** e **implementación** de un asistente virtual para profesores de matemáticas. Esta metodología incluye los siguientes pasos:

*   **Implementación del generador de problemas matemáticos**: Se utilizarán **modelos de lenguaje como chatGPT** para crear este generador.
*   **Creación de la funcionalidad de exportación a PDF**: Se integrará una herramienta que permita exportar las actividades y exámenes generados a formato PDF.
*   **Construcción del banco de preguntas reutilizables**: Se desarrollará una base de datos de preguntas que los docentes podrán usar y modificar.
*   **Recolección de requisitos**: Se consultará con docentes de matemáticas para identificar necesidades y casos de uso. Además, se definirán los niveles educativos y temáticas principales para la generación de ejercicios.
*  **Diseño del sistema**: Se planificará la arquitectura del asistente virtual, incluyendo la interfaz de usuario y las funcionalidades principales.
*   **Pruebas y validación**: Se realizarán pruebas con docentes para asegurar que las actividades generadas sean claras y útiles, ajustando el sistema según la retroalimentación.

_________________________________________________________________________________________________________
### HERRAMIENTAS Y TECNOLOGÍAS

El proyecto utilizará las siguientes **herramientas y tecnologías**:

*   **Lenguajes de programación**: Se utilizará **Python**.
*   **Inteligencia Artificial (IA)**: Se empleará **OpenAI GPT 3.5 API** para la generación de problemas matemáticos y **OpenAI DALL-E API**.
*  **Generación de documentos**: Se utilizará **ReportLab o FPDF** para la exportación a formato PDF.

Estas herramientas han sido elegidas debido a su amplia utilización y documentación, lo que facilita un desarrollo eficiente del proyecto. Además, la aplicación de **Inteligencia Artificial** permite la creación de actividades adaptadas a necesidades específicas, optimizando el tiempo de los docentes.

_________________________________________________________________________________________________________
### IMPLEMENTACIÓN
_________________________________________________________________________________________________________
### ACTUALIZACIONES DEL PROYECTO FINAL

- **Última actualización - 02/02/2025**
    - **Primer Pre-Entrega** &nbsp;[<img src="./Images/Readme/Carpeta.png" alt="Devolucion Logo" width="22" height="20">](https://drive.google.com/file/d/16Hz7f1YSEI3F2Ik3kmRbB_6n5l2xU1tU/view?usp=sharing)
    - **Segunda Pre-Entrega** &nbsp;[<img src="./Images/Readme/Carpeta.png" alt="Devolucion Logo" width="22" height="20">]()
    - **Proyecto Final** &nbsp;[<img src="./Images/Readme/Carpeta.png" alt="Devolucion Logo" width="22" height="20">]()
______________________________________________________________________________________________________
### REDES SOCIALES Y PROYECTOS

¡Seguime en mis redes sociales para conocer todos mis proyectos!

[<img src="./Images/Readme/Facebook.png" alt="Facebook Logo" width="30" height="30">](https://www.facebook.com/fedco.grrz/)
&nbsp;&nbsp;&nbsp;
[<img src="./Images/Readme/Instagram.png" alt="Instagram Logo" width="30" height="30">](https://www.instagram.com/grrz.fede/)
&nbsp;&nbsp;&nbsp;
[<img src="./Images/Readme/LinkedIn.png" alt="LinkedIn Logo" width="30" height="30">](https://www.linkedin.com/in/fedco-grrz/)
&nbsp;&nbsp;&nbsp;
[<img src="./Images/Readme/Github.png" alt="Github Logo" width="30" height="30">](https://github.com/fedco-gtz)

#### PROYECTOS
[<img src="./Images/Readme/Casamiento.png" alt="Casamiento Logo" width="140" height="80">](https://fedco-gtz.github.io/Nos-Casamos-Ger-y-Gabi/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Music-Store.png" alt="Music-Store Logo" width="80" height="80">](https://fedco-gtz.github.io/MusicStore-Codo-a-Codo/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Mascotas-Felices.png" alt="Mascotas-Felices Logo" width="80" height="80">](https://mascotas-felices.netlify.app/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/VuelaSmart.png" alt="VuelaSmart Logo" width="115" height="80">](https://vuelasmart.netlify.app/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/ZapaTienda.png" alt="ZapaTienda Logo" width="80" height="80">](https://zapatienda.vercel.app/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Funko-Paradise.png" alt="Funko-Paradise Logo" width="140" height="80">](https://funkoparadise.vercel.app/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Verde-Vital.png" alt="Verde-Vital Logo" width="130" height="80">]()
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/AdoptMe.png" alt="AdoptMe Logo" width="140" height="80">]()
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Piedra-Papel-Tijera.png" alt="Piedra,-Papel-o-Tijera Logo" width="140" height="80">](https://colab.research.google.com/drive/1Py7hTg2NZOFlR9G61eru9vgv5vQN7xwK?usp=sharing)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Inventario.png" alt="Inventario-de-Prodcutos Logo" width="140" height="80">](https://colab.research.google.com/drive/1SPE_t6KUmc47hlfKxNBiU3PI5W20-HXK?usp=sharing)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/Las-matemáticas-en-el-universo.png" alt="Las-matemáticas-en-el-universo Logo" width="80" height="80">](https://fedco-gtz.github.io/Fundamento-de-la-IA-Coderhouse/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/CAC-Movies.png" alt="CAC-Movies Logo" width="180" height="80">](https://cac-movie.onrender.com/)
&nbsp;&nbsp;
<img src="./Images/Readme/Linea-Vertical.png" alt="Linea" width="20" height="80">
&nbsp;&nbsp;
[<img src="./Images/Readme/MateAi.png" alt="MAteAi Logo" width="180" height="80">]()
_______________________________________________________________________________________________________
