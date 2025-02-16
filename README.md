[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9045293&assignment_repo_type=AssignmentRepo)
# :wave: Los fundamentos de GitHub 

## 🤓  Visión general y resultados de aprendizaje

El objetivo de este curso es dar una breve introducción a GitHub. También proporcionará materiales para seguir aprendiendo y algunas ideas para comenzar en la plataforma. 🚀

## :octocat: Git y GitHub
 
Git es un **sistema de control de versiones distribuido (VCS)**, lo que significa que es una herramienta útil para rastrear fácilmente los cambios en su código, colaborar y compartir. Con Git puede realizar un seguimiento de los cambios que se realizan en un proyecto de modo que siempre hayaa un registro de lo que ha cambiado y se pueda volver fácilmente a una versión anterior si es necesario. También facilita el trabajo con otros: ¡grupos de personas pueden trabajar juntos en el mismo proyecto y fusionar sus cambios en una fuente final!

GitHub es una forma de usar las posibilidades de Git en línea con una interfaz fácil de usar. Se utiliza en todo el mundo del software y más allá para colaborar y mantener la historia de los proyectos.

GitHub aloja algunas de las tecnologías más avanzadas del mundo. Independientemente de si estás visualizando datos o construyendo un nuevo juego, hay toda una comunidad y un conjunto de herramientas en GitHub que pueden ayudarte a dar el siguiente paso. Este curso comienza con los conceptos básicos de GitHub, aunque profundizaremos en el resto más adelante.

## :octocat: Entendiendo el funcionamiento de GitHub 

The GitHub flow is a lightweight workflow that allows you to experiment and collaborate on your projects easily, without the risk of losing your previous work.
 
GitHub mantiene un flujo de trabajo ligero que le permite experimentar y colaborar en sus proyectos fácilmente, sin el riesgo de perder su trabajo anterior.

### Repositorios
 
Un repositorio es el lugar en el que tiene lugar el trabajo de su proyecto: es posible pensar en él como una carpeta de proyecto. Contiene todos los archivos y el historial de revisiones de su proyecto. Es posible trabajar de manera individual dentro de un repositorio o invitar a otros a colaborar en esos archivos.

###  Clonación

Al crear un repositorio con GitHub, este se almacena de forma remota en la nube ☁️. Es posible clonar un repositorio para crear una copia local en el equipo y, a continuación, utilizar Git para sincronizar los dos almacenamientos. Esto hace que sea más fácil solucionar problemas, agregar o eliminar archivos y enviar confirmaciones más grandes. También es posible elegir un editor de código de su elección en lugar de la interfaz de usuario de GitHub. La clonación de un repositorio también descarga todos los datos del repositorio que GitHub tiene en ese momento, ¡incluidas todas las versiones de cada archivo y carpeta para el proyecto! Esto permite modificar el proyecto y recuperar la versión anterior, si posteriormente así se decide.
Para obtener más información sobre la clonación, lea ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Commit and push

**Commit** y **push** son dos acciones que unidas permiten sincronizar los cambios realizados en la máquina local en el repositorio remoto en GitHub. De esa manera, los compañeros de equipo pueden ver la última versión del trabajo cuando esté listo para compartirlo. 
Un **commit** permite guardar los cambios deseados en el proyecto. Es útil hacerlo agregando un **mensaje de confirmación** para recordarse a sí mismo o a sus compañeros de equipo la modificación que se hizo (por ejemplo, 'Se agregó un archivo README con información sobre nuestro proyecto').

Una vez que haya uno o varios commits listos para sincronizar, se utilizará usar el comando **push** para agregar esos cambios a su repositorio remoto. El uso de **commit** y **push** puede parecer nuevo al principio, pero en breve será  una costumbre. 🙂

## 💻 GitHub: Terminos importantes 

### Repositorios 

Aunque ya hemos mencionado que los repositorios son el lugar donde se desarrolla el trabajo del proyecto, ¡hablemos un poco más sobre ellos! A medida que trabaje más en GitHub, tendrá muchos repositorios que pueden parecer confusos al principio. 
Afortunadamente, el ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ayuda a navegar fácilmente por los repositorios y ver información útil sobre ellos. ¡Asegúrate de haber iniciado sesión para verlo!

Los repositorios también contienen ficheros **README**s para informar a otras personas por qué su proyecto es útil, qué pueden hacer con su proyecto y cómo pueden usarlo. En este caso, estamos usando este README para explicar cómo aprender a usar Git y GitHub.😄 
Para aprender más sobre los repositorios, lee ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) y ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Ramas

 Las ramas en GitHub se utilizan para aislar el trabajo que aún no desea fusionar en su proyecto final. Permiten desarrollar características, corregir errores o experimentar de forma segura con nuevas ideas en un área limitada del repositorio. Normalmente, puede crear una nueva rama a partir de la rama predeterminada del repositorio: main. Esto crea una nueva copia de trabajo de su repositorio para que pueda experimentar. Una vez que se hayan revisado los nuevos cambios y se esté satisfecho con ellos, es posible combinar los cambios en la rama predeterminada del repositorio.
Para aprender más sobre las ramas, lee ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks

Un fork otro modo de copiar un repositorio, generalmente se usa cuando desea contribuir al proyecto de otra persona. ¡Hacer un fork de un repositorio un repositorio le permite experimentar libremente con cambios sin afectar el proyecto original y es muy popular cuando contribuye a proyectos de software de código abierto!
Para aprender más sobre fork, lee ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull requests
 
Al trabajar con ramas, puede usar un **pull request** para informar a otros usuarios sobre los cambios que desea realizar y solicitar sus comentarios. Una vez que se abre un pull request, puede discutir y revisar los posibles cambios con los colaboradores y agregar más cambios si es necesario. ¡Puede agregar personas específicas como revisores del pull request, lo que demuestra que desea sus comentarios sobre sus cambios! Una vez que se han completado los cambios que se desean hacer en un pull request en una rama secundaria, se puede fusionar con su rama principal principal.

Para obtener más información sobre los pull requests, lee ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

### Issues
 
Los **issues** son una forma de realizar un seguimiento de las mejoras, tareas o errores del trabajo en GitHub. Son una excelente manera de realizar un seguimiento de todas las tareas en las que desea trabajar en el su proyecto y dejar que otros conozcan la planificación del mismo. ¡También se puede usar issues para informar sobre un error que se encontró o una característica que cree que sería genial agregar en un proyecto de código abierto!

Para proyectos más grandes, puede realizar un seguimiento de muchos issues en un panel de proyecto. Los proyectos de GitHub ayudan a organizar y priorizar el trabajo y puedes leer más sobre ellos [en este documento "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Es probable que no necesite un panel de proyectos para sus tareas, pero una vez que se trabaja con proyectos más grandes, ¡son una excelente manera de organizar el trabajo de su equipo!

También puede vincular solicitudes de pull requests and issues para mostrar que una solución está en curso y para cerrar automáticamente el issue cuando alguien realice pull request asociado a él.

Para obtener más información sobre los issues y vincularlos a pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### El perfil de usuario

El perfil informa a otros usuarios de GitHub la historia de tu trabajo a través de los repositorios que te interesan, las contribuciones que has hecho y las conversaciones que has tenido. También puede darle al mundo una visión única de quién es usted con su perfil README. ¡Puede usar su perfil para que los futuros empleadores potenciales sepan sobre usted!

Para obtener más información sobre su perfil de usuario y agregar y actualizar su perfil README, lea ['Administrar su perfil README'](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

Es posible agregar un estilo divertido a los issues, pull requests y archivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) es una forma fácil de aplicar estilo a los issues, pull request y archivos con una sintaxis simple. Esto puede ser útil para organizar su información y facilitarle la lectura a los demás. ¡También se pueden usar gifs e imágenes para ayudar a entender el proyecto!

Para obtener más información sobre el uso del lenguaje de marcado de GitHub, lee ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engaging with the GitHub community

La comunidad de GitHub es amplia. Hay muchos tipos de personas que usan GitHub en su día a día: estudiantes, desarrolladores profesionales, aficionados que trabajan en proyectos de código abierto y algunos que están saltando al mundo del desarrollo de software por su cuenta. Hay muchas maneras de interactuar con la comunidad más grande de GitHub, pero aquí hay tres modos para comenzar:

#### Repositorios destacados 
 
Si encuentras un repositorio interesante o quieres seguirle, ¡Destácalo! (star). Cuando se marca un repositorio como destacado, es un modo de promocionar ese repositorio para mostrarle entre las mejores recomendaciones en github.com/explore. Si desea desmarcar sus repositorios destacados, puede hacerlo a través de su perfil de usuario. Para obtener más información sobre los repositorios protagonistas, lea ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Seguimiento de usuarios

En GitHub puedes seguir a otros usuarios para recibir notificaciones sobre su actividad y descubrir proyectos en sus comunidades. Al seguir a un usuario, su actividad pública de GitHub aparecerá en tu panel de control para que puedas ver todas las cosas geniales en las que están trabajando.

Para obtener más información sobre los siguientes usuarios, lea ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Consultando GitHub Explore 

GitHub Explore es un gran lugar para hacer precisamente eso ... explore 🙂 Puedes encontrar nuevos proyectos, eventos y desarrolladores con los que interactuar.
Puedes visitar la web de GitHub Explore [at github.com/explore](https://github.com/explore).

## 📝 Siguientes pasos (opcional) 

* Abre un pull request y cuéntame que has terminado este curso.  
* Crea un nuevo archivo de markdown en este repositorio. ¡Hazles saber lo que aprendiste y aquello que aún te resulta confuso! ¡Experimenta con diferentes estilos!
* Crea tu perfil README. ¡Deja que el mundo sepa un poco más sobre ti! ¿Qué te interesa aprender? ¿En qué estás trabajando? ¿Cuál es tu pasatiempo favorito? Obtén más información sobre cómo crear el archivo README de tu perfil en el documento , ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Crea un nuevo repositorio en tu panel de usuario. Experimenta con las características dentro de ese repositorio para familiarizarse con ellas.
* [Dinos lo que le gustó o no le gustó del contenido de este curso] (https://support.github.com/contact/education). ¿De qué te gustaría ver más? ¿Qué sería interesante o útil para su viaje de aprendizaje?

## 📚  Resources 

* [video explicativo de lo que es GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub recursos de aprendizaje](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Entendiendo el trabajo en GitHub](https://guides.github.com/introduction/flow/)
* [Uso de las ramas en GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiales interactivos para aprender a manejar Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
