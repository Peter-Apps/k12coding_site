---
title: Recursos Para Docentes

# the default layout is 'page'
# icon: fas fa-info-circle
order: 3
lang: es
page_id: resources
permalink: /es/recursos/
---

Si te gustan las actividades y quieres integrar la programación en tu clase, escuela o distrito escolar, estaremos encantados de compartir lo que nos ha funcionado bien y lo que no. A continuación, encontrarás una breve descripción de cada una de las herramientas digitales que utilizamos, seguida de consejos para su implementación a distintas escalas.

**# Las herramientas que utilizamos**

**### Python**

[Python][Python] es un lenguaje de programación utilizado habitualmente en la investigación científica y la ciencia de datos. Es posible que hayas oído hablar de otros lenguajes, como C++, Java, Fortran o BASIC. Python tiende a tener menos reglas de sintaxis y caracteres adicionales, lo que hace que sea más fácil de leer para las personas que algunas de las alternativas. Esto significa que los estudiantes a menudo pueden deducir lo que hace el código simplemente al observarlo.

Como nos centramos principalmente en el contenido científico, estas actividades no enseñan programación de manera explícita. Si tú o tus estudiantes quieren aprender sobre bucles, condicionales, funciones y otros fundamentos de las ciencias de la computación, existen tutoriales gratuitos de alta calidad en la web. Consulta [Python.org][python-wiki], [Khan Academy]([https://www.khanacademy.org/computing/computer-science]%28https://www.khanacademy.org/computing/computer-science%29), [DataCamp.com]([https://www.datacamp.com/courses/intro-to-python-for-data-science]%28https://www.datacamp.com/courses/intro-to-python-for-data-science%29) y [Programming with Mosh][Mosh] en YouTube.

**### Jupyter**

[Jupyter]([https://jupyter.org/]%28https://jupyter.org/%29) es un software que permite escribir código y hacer cosas útiles como abrir un archivo de datos, realizar cálculos y crear gráficos. Lo utilizamos como utilizarías un programa de hojas de cálculo, pero en lugar de escribir en las celdas, escribes las instrucciones (**el código**) para analizar y visualizar los datos. Investigadores y científicos informáticos lo utilizan en lugares como CERN, NASA, IBM, Google y Microsoft. Los archivos de Jupyter se llaman **cuadernos** (*notebooks*), por lo que quizá notes que utilizamos ese término ocasionalmente para describir nuestras actividades.

Jupyter se ejecuta en una ventana del navegador, lo que hace que parezca más familiar —y menos intimidante— que la terminal de computadora vacía que quizá estés imaginando. Los cuadernos muestran el código y lo que este produce (texto, tablas y gráficos) en la misma ventana, y pueden incluir texto con formato (negrita, cursiva, distintos tamaños de fuente), hipervínculos e imágenes, de modo que las actividades pueden parecerse más a los materiales didácticos con los que los estudiantes suelen interactuar.

La forma más sencilla de ejecutar nuestras actividades es mediante un servicio interactivo en línea como Google Colaboratory, descrito a continuación. Si prefieres instalar Jupyter en tu computadora para ejecutar los programas «localmente», descarga e instala [Anaconda]([https://www.anaconda.com/products/individual]%28https://www.anaconda.com/products/individual%29). Contiene Jupyter, Python y todo lo demás que tu computadora necesitará en segundo plano. Puedes descargar nuestras actividades y datos desde el [GitHub del proyecto]([https://github.com/adamlamee/CODINGinK12]%28https://github.com/adamlamee/CODINGinK12%29): abre un archivo y luego haz clic con el botón derecho en «raw».

**### Colab**

Puedes instalar Jupyter localmente en tu dispositivo, pero en las escuelas K-12 la instalación de software puede ser desde difícil hasta prácticamente imposible. [Google Colaboratory]([https://colab.research.google.com/notebooks/basic_features_overview.ipynb]%28https://colab.research.google.com/notebooks/basic_features_overview.ipynb%29), o **Colab**, ha revolucionado la forma en que utilizamos los cuadernos de Jupyter con estudiantes y en la formación profesional de docentes. La única desventaja es que requiere una cuenta de Google. Si tu escuela utiliza Google Classroom, eso no supone un gran problema. Ejecutar un cuaderno en Colab es excelente para computadoras antiguas, ya que no utiliza el procesador de tu equipo para realizar el trabajo pesado. Al igual que un Documento, Hoja de cálculo o Presentación de Google, puedes guardarlo en tu Drive y compartirlo con otras personas, pero no admite que varios usuarios editen simultáneamente.

**### Alternativas a Colab**

Recientemente, muchos distritos escolares se están alejando de permitir Google Colab debido a preocupaciones sobre la privacidad. Actualmente, Google Colab no está incluido en su plataforma educativa, aunque esperamos que eso cambie en el futuro. Si buscas una alternativa, aquí tienes algunas sugerencias que otros docentes han utilizado con éxito.

* [Azure]([https://learn.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks?view=azureml-api-2]%28https://learn.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks?view=azureml-api-2%29): Si prefieres utilizar un producto de Microsoft, Azure permite ejecutar y guardar nuestros cuadernos en la nube utilizando tu cuenta de Microsoft o Outlook365. No hemos utilizado mucho este servicio (a mayo de 2020), pero es una opción si lo necesitas.

* [Binder]([https://mybinder.org]%28https://mybinder.org%29): Binder permite convertir un repositorio de Git en una colección de cuadernos interactivos accesibles para los estudiantes sin necesidad de crear cuentas. Comenzamos este proyecto en un servidor JupyterHub dedicado y luego pasamos a utilizar Binder. Este proyecto no habría podido ponerse en marcha sin el equipo de Binder.

* [GitHub Codespaces]([https://github.com/codespaces]%28https://github.com/codespaces%29): Si planeas almacenar todos tus cuadernos en un repositorio de GitHub y los estudiantes pueden crear su propia cuenta de GitHub, Codespaces es una forma integrada de ejecutar y modificar archivos de cuadernos. Cada cuenta recibe 120 horas de acceso gratuito al mes. Los estudiantes pueden hacer un *fork* del repositorio del docente y sus cambios se guardarán en su propio repositorio.

* [JupyterEverywhere]([https://www.jupytereverywhere.org/]%28https://www.jupytereverywhere.org/%29): Una implementación de JupyterNotebook basada en la web, sin necesidad de cuentas y con una interfaz simplificada, lo que la hace útil para estudiantes más jóvenes. Los docentes pueden subir un cuaderno y compartir el enlace con la clase. Los estudiantes tendrán que compartir su cuaderno terminado o descargar una copia para conservar sus cambios.

* [JupyterLite]([https://jupyter.org/try-jupyter/lab/]%28https://jupyter.org/try-jupyter/lab/%29): Otra opción sin cuentas para ejecutar estos cuadernos en un navegador. Se puede integrar directamente en un [sitio web]([https://codinginK12.org/jupyterLite]%28https://codinginK12.org/jupyterLite%29) utilizando GitHub Pages. Ejecuta bien los cuadernos, pero los estudiantes tendrán que descargar los archivos editados para guardar sus cambios.

* [Marimo]([https://molab.marimo.io/notebooks]%28https://molab.marimo.io/notebooks%29): Requiere que los estudiantes creen una cuenta, pero ofrece una interfaz similar a Colab y funciona rápidamente en cualquier navegador web. Los cambios se guardan en la cuenta del estudiante, pero pueden descargarse o compartirse con el docente.

**### GitHub**

[GitHub]([https://github.com/]%28https://github.com/%29) es almacenamiento en la nube, colaboración en equipo y control de versiones, todo en uno. Los programadores y las organizaciones profesionales lo utilizan para alojar su código y llevar un registro de quién realizó cada modificación y cuándo. Nosotros lo utilizamos para alojar nuestros cuadernos y los archivos de datos que estos analizan. Colab tiene una excelente función que nos permite crear una URL que abre un cuaderno de GitHub en tu propia ventana de Colab.

Los botones «Open In Colab» hacen precisamente eso.

![Open In Colab](\[https://colab.research.google.com/assets/colab-badge.svg]\(https://colab.research.google.com/assets/colab-badge.svg\))

**# Consejos para la implementación**

Utiliza nuestras actividades tal como están, edítalas y adáptalas a tus estudiantes, o deja que trabajemos con tu equipo. Podemos ayudarte a desarrollar un plan de implementación que se adapte a las necesidades y recursos de tu organización. Tenemos una sólida trayectoria ofreciendo formación profesional de alta calidad y planificación estratégica a nivel de distrito sobre programación, contenidos de ciencias físicas, pedagogía renovada y alfabetización digital. Programa una consulta escribiendo a [adamlamee@gmail.com](mailto:adamlamee@gmail.com).

**### Intenta llegar a la mayoría de los estudiantes**

* Un curso específico de ciencias de la computación puede no ser la respuesta, especialmente para los estudiantes cuyos horarios ya están llenos de cursos de recuperación o asignaturas optativas. Los estudiantes que van en autobús o que no tienen otro medio de transporte también pueden perderse los clubes extracurriculares.

* Integrar la programación en las asignaturas troncales obligatorias aumenta la equidad y el acceso, independientemente de los antecedentes o los ingresos familiares de cada estudiante. Por eso nuestras actividades están dirigidas a docentes de las distintas áreas de contenido. En este momento se trata principalmente de ciencias, pero puedes enviar sugerencias o contribuir con una actividad que hayas creado escribiendo a [adamlamee@gmail.com](mailto:adamlamee@gmail.com).

**### Consigue que estén de tu lado**

Los datos y los testimonios pueden ayudar a conseguir que estudiantes, padres, docentes y administradores se sumen a la iniciativa. Estos son algunos recursos que nos han resultado útiles:

* [What Most Schools Don’t Teach]([https://www.youtube.com/watch?v=nKIu9yen5nc]%28https://www.youtube.com/watch?v=nKIu9yen5nc%29), un video de CODE.org con muchas celebridades que promueven una mayor presencia de la programación en la educación K-12

* [Pair Programming]([https://www.youtube.com/watch?v=vgkahOzFH2Q]%28https://www.youtube.com/watch?v=vgkahOzFH2Q%29), un video tutorial de CODE.org

* [Ten quick tips for teaching programming]([https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006023]%28https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006023%29), de PLOS

* [AAPT Recommendations for Computational Physics in the Undergraduate Physics Curriculum]([https://www.aapt.org/Resources/upload/AAPT_UCTF_CompPhysReport_final_B.pdf]%28https://www.aapt.org/Resources/upload/AAPT_UCTF_CompPhysReport_final_B.pdf%29)

* [Salarios y antecedentes]([https://orlandodevs.com/blog/orlando-devs-salaries-2017]%28https://orlandodevs.com/blog/orlando-devs-salaries-2017%29) de los programadores informáticos de Florida Central, cortesía de [Orlando Devs]([https://orlandodevs.com/]%28https://orlandodevs.com/%29)

**### La formación es fundamental**

* Aprender las herramientas y aprender cómo la programación puede enriquecer tu curso actual lleva tiempo. No es como aprender a utilizar un nuevo programa de registro de calificaciones.

* No te preocupes por depurar código ni por descifrar mensajes de error. Sí debes capacitar a los docentes hasta que tengan la confianza necesaria para guiar a un estudiante que tenga dificultades a través del proceso de deshacer una edición, reiniciar el entorno de ejecución (o kernel) y volver a cargar una copia limpia del cuaderno.

* La [Declaración de posición de la NSTA sobre el desarrollo profesional]([https://www.nsta.org/about/positions/profdev.aspx]%28https://www.nsta.org/about/positions/profdev.aspx%29) es un excelente recurso para planificar un taller.

**### Hazlo tuyo**

* Nuestras actividades no tienen mucho formato adicional ni texto explicativo. Si prefieres que tus estudiantes tengan instrucciones más detalladas, es fácil editarlas para cambiar la presentación, la secuencia, el tipo de pregunta, etc.

* Ver lo que [Seminole County]([https://github.com/SCPSscience]%28https://github.com/SCPSscience%29) y [Orange County]([https://github.com/ocps-codes]%28https://github.com/ocps-codes%29) crearon para sus estudiantes puede darte algunas ideas.

* Nuestras actividades tienen licencia CC-BY-SA, lo que significa que son gratuitas para usar y modificar siempre que se dé el crédito correspondiente. Consulta la página «about» para ver el texto de la licencia. También puedes escribirnos a [adamlamee@gmail.com](mailto:adamlamee@gmail.com). Nos encanta saber cómo los docentes las están adaptando.

**### Alimenta a los estudiantes más avanzados**

Nuestras actividades permiten que los estudiantes interesados realicen más análisis del que se incluye en las instrucciones, y a menudo nos sorprende lo que consiguen. Si eso no es suficiente, prueba a sugerir estos otros recursos gratuitos (y extraordinarios):

* [CERN Open Data]([http://opendata.cern.ch/?ln=en]%28http://opendata.cern.ch/?ln=en%29) incluye recursos educativos sobre física de partículas y ofrece a los estudiantes (y al público en general) la oportunidad de acceder y analizar datos auténticos del Gran Colisionador de Hadrones. Sí, es bastante genial.

* [Particle Physics Playground]([http://particle-physics-playground.github.io/]%28http://particle-physics-playground.github.io/%29), de Matt Bellis, ofrece ejercicios de cuadernos de Jupyter con datos de detectores de partículas de CMS y CLEO.

* El trabajo de [Shawn Weatherford]([http://www.phys.ufl.edu/~sweatherford/]%28http://www.phys.ufl.edu/~sweatherford/%29) sobre vPython y Glowscript.

* [Let's Code Physics YouTube channel]([https://www.youtube.com/channel/UCWBTKIyw-zX-2k63cB6qciQ]%28https://www.youtube.com/channel/UCWBTKIyw-zX-2k63cB6qciQ%29)

* [STEM Coding]([https://u.osu.edu/stemcoding/]%28https://u.osu.edu/stemcoding/%29)

* [Actividades de Astronomía para secundaria de Dimitrios Theodorakis]([https://github.com/DimitriosAstro/Astronomy]%28https://github.com/DimitriosAstro/Astronomy%29)

[Mosh]: [https://www.youtube.com/watch?v=_uQrJ0TkZlc]\(https://www.youtube.com/watch?v=_uQrJ0TkZlc\)
[Python]: [https://www.python.org/]\(https://www.python.org/\)
[python-wiki]: [https://wiki.python.org/moin/BeginnersGuide/Programmers]\(https://wiki.python.org/moin/BeginnersGuide/Programmers\)
