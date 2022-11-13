> [Versió en català](README-ca.md) | [English version](README.md)
___

## Laboratorio git-it

Para empezar a aprender git, puede empezar haciendo el laboratorio [git-it](https://github.com/jlord/git-it-electron). Este laboratorio tiene una colección de 11 retos que debe resolver. Estos retos se explican [aquí] (http://jlord.us/git-it/) y también en la propia aplicación (en diferentes idiomas).

Deberá descargar e instalar la aplicación ``git-it-electron``:

[baja git-it para Linux](https://drive.google.com/uc?id=1EYkA_TpGpBnhHsLKX-3ttSyS4xguCWU0&export=download)

[descargue git-it para Windows](https://github.com/jlord/git-it-electron/releases/download/4.4.0/Git-it-Win-ia32.zip)

[descargue git-it para Mac](https://github.com/jlord/git-it-electron/releases/download/4.4.0/Git-it-Mac-x64.zip)

> Por favor, añada una captura de pantalla a este repo que muestre los retos finalizados.

## test w3schools

Una vez que haya terminado el git-it lab, continúe con el cuestionario que encontrará en [w3schools git quiz](https://www.w3schools.com/git/git_quiz.asp)

> Por favor, añada una captura de pantalla a este repositorio que muestre sus resultados después de terminar el cuestionario.

## Para principiantes 

En inglés:

[git cheat sheet](https://www.freecodecamp.org/news/git-cheat-sheet/)

[A Beginner's Guide to Git](https://www.freecodecamp.org/news/what-is-git-learn-git-version-control/)

___

# :wave: Fundamentos de GitHub

## 🤓 Visión general del curso y resultados de aprendizaje

El objetivo de este curso es darle una breve introducción a GitHub y git. También le proporcionaremos materiales para un aprendizaje adicional y algunas ideas para empezar a utilizar nuestra plataforma. 🚀

## :octocat: Git y GitHub

Git es un **Sistema de control de versiones distribuido (VCS)**, lo que significa que es una herramienta útil para hacer un seguimiento fácil de los cambios en su código, colaborar y compartir. Con Git puede realizar un seguimiento de los cambios que haga en su proyecto para que siempre tenga un registro de lo que ha trabajado y puede volver fácilmente a una versión anterior si es necesario. También facilita el trabajo con otras personas: grupos de personas pueden trabajar juntos en el mismo proyecto y combinar sus cambios en un repositorio fuente final.

GitHub es una manera de utilizar la misma potencia de Git online pero con una interfaz fácil de utilizar. Se utiliza en todo el mundo del software y, más allá, para colaborar y mantener el historial de los proyectos.

GitHub alberga algunas de las tecnologías más avanzadas del mundo. Tanto si visualiza datos como si está creando un juego nuevo, en GitHub hay toda una comunidad y un conjunto de herramientas que le pueden llevar al siguiente paso. Este curso comienza con los conceptos básicos de GitHub, pero nos profundizaremos en el resto más adelante.

## :octocat: Entendiendo el GitHub flow

El flujo de GitHub es un flujo de trabajo ligero que le permite experimentar y colaborar en sus proyectos fácilmente, sin riesgo de perder su trabajo anterior.

### Repositorios

Un repositorio es donde se hace el trabajo de su proyecto; piense como carpeta de su proyecto. Contiene todos los archivos de su proyecto y el historial de revisiones. Puede trabajar dentro de un repositorio individualmente o invitar a otras personas a colaborar con usted en estos archivos.

### Clonación

Cuando se crea un repositorio con GitHub, se almacena de forma remota en la nube ☁️. Puede clonar un repositorio para crear una copia local en su ordenador y luego utilizar Git para sincronizar ambas copias (la local y la de github). Esto hace que sea más fácil solucionar problemas, añadir o eliminar archivos y subir commits más grandes. También puede utilizar la herramienta de edición que elija en lugar de la interfaz de usuario de GitHub. La clonación de un repositorio también descarga todos los datos del repositorio que tiene GitHub en ese momento, incluidas todas las versiones de cada archivo y carpeta del proyecto. Esto puede ser útil si experimenta con su proyecto y luego se da cuenta de que le gustaba más una versión anterior.
Para obtener más información sobre la clonación, lea ["Clonación de un repositorio"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committing y pushing

**Committing** y **pushing** son los pasos a realizar cuando desea añadir los cambios que ha hecho a su máquina local en el repositorio remoto de GitHub. De esta manera, su instructor y/o compañeros de equipo podrán ver su último trabajo cuando esté preparado para compartirlo. Puede realizar un commit cuando haya hecho cambios en su proyecto que desee "congelar" (_checkpoint_). También puede añadir un **mensaje de commit** útil para recordarle a usted mismo oa sus compañeros de equipo qué trabajo ha hecho (p. ej., "Se ha añadido un README con información sobre nuestro proyecto ").

Una vez que tenga un commit o varios commits preparados para añadir a su repositorio, puede utilizar el mandato push para añadir estos cambios a su repositorio remoto. Commit y push puede parecer nuevo al principio, pero le prometemos que se acostumbrará 🙂

## 💻 Términos de GitHub a conocer

### Repositorios

Ya hemos mencionado los repositorios: están donde se hace el trabajo de su proyecto, ¡pero hablemos un poco más sobre los detalles! A medida que trabaje más en GitHub, tendrá muchos repositorios que al principio pueden resultar confusos. Afortunadamente, su ["Panel de control de Github"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal- dashboard) le ayudará a navegar fácilmente por sus repositorios ya consultar información útil sobre ellos. ¡Asegúrate de haber iniciado sesión para verlo!

Los repositorios también contienen **README**. Puede añadir un archivo README a su repositorio para explicar a otras personas por qué es útil su proyecto, qué pueden hacer con su proyecto y cómo pueden utilizarlo. Estamos utilizando este mismo READMO que ahora lea, para comunicarse cómo aprender Git y GitHub. 😄
Para obtener más información sobre los repositorios, lea ["Crear, clonar y archivar repositorios](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) y [ "En cuanto a README's"] (https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Ramas
Puede utilizar ramas en GitHub para **aislar** el trabajo que todavía no desea combinar en su proyecto final. Las ramas le permiten desarrollar funciones, corregir errores o experimentar de forma segura con nuevas ideas en un área contenida de su repositorio. Normalmente, puede crear una nueva rama desde la rama predeterminada de su repositorio: la rama principal (_main_). Esto creará una nueva copia de trabajo, en una nueva rama, de su repositorio _main_ para que experimente. Una vez que sus cambios hayan sido revisados ​​por un compañero de equipo, o bien esté satisfecho, puede combinar sus cambios en la rama predeterminada de su repositorio.
Para obtener más información sobre las ramificaciones, lea ["Sobre las ramas"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Bifurcaciones (_forks_)
Una bifurcación es otra forma de copiar un repositorio, pero normalmente se utiliza cuando desea contribuir al proyecto de otra persona. La bifurcación de un repositorio le permite experimentar libremente con los cambios sin afectar al proyecto original y es muy popular cuando contribuye a proyectos de software de código abierto!
Para obtener más información sobre la bifurcación, lea ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull Requests (PRs)
Cuando trabaje con ramas, puede utilizar un _pull request_ (o PR) para informar a los demás sobre los cambios que desea hacer y pedir sus comentarios. Una vez abierta una PR, puede discutir y revisar los posibles cambios con los colaboradores y añadir más cambios si es necesario. Puede añadir personas específicas como revisores de su PR, lo que muestra que acepta sus comentarios sobre sus cambios. Una vez una PR esté preparada, se puede fusionar en su rama principal.
Para obtener más información sobre las PRs, lea ["Sobre las Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) .

### Issues
Los problemas o _issues_ son una manera de realizar un seguimiento de las mejoras, tareas o errores de su trabajo en GitHub. Los _issues_ son una manera fantástica de hacer un seguimiento de todas las tareas en las que desea trabajar para su proyecto y que los demás sepan en qué tiene previsto trabajar. También puede utilizar los issues para explicar a un proyecto de código abierto, un error que ha encontrado o una función que cree que sería fantástico añadir!

Para proyectos más grandes, puede realizar un seguimiento de muchas salidas en un tablero de proyecto. Los proyectos de GitHub le ayudan a organizar y priorizar su trabajo y puede leer más información [en este documento sobre los tableros de proyectos] (https://docs.github.com/en/github/managing-your-work -on-github/ about-project-boards). Es probable que no necesites un tablero de proyectos para tus tareas, pero una vez que pases a proyectos aún mayores, son una manera fantástica de organizar el trabajo de tu equipo!
También puede enlazar PRs y _issues_ para mostrar que hay una solución en curso y para cerrar automáticamente la _issue_ cuando alguien fusione la PR.
Para obtener más información sobre las _issues_ y enlazarlos a sus PRs, lea ["Sobre las issues"](https://docs.github.com/en/github/managing-your-work-on-github/about -issues).

### Tu perfil de usuario

Tu página de perfil le explica a la gente la historia de tu trabajo a través de los repositorios que te interesan, las contribuciones que has hecho y las conversaciones que has tenido. También puede dar al mundo una visión única de quien es usted con su perfil README. Puedes utilizar tu perfil para que los futuros empleadores sepan todo sobre ti!
Para obtener más información sobre su perfil de usuario y añadir y actualizar su perfil README, lea ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and -managing-your-github -perfil/gestionar-su-perfil-léame).

### Utilizando Markdown en GitHub

Es posible que ya lo haya notado, pero puede añadir un estilo divertido a sus problemas, PRs y archivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) es una manera sencilla de estilizar sus _issues_, PRs y archivos con una sintaxis sencilla. Esto puede ser útil para organizar su información y facilitar la lectura para los demás. También puede introducir gifs e imágenes para ayudar a transmitir su mensaje!
Para obtener más información sobre cómo utilizar el markdown de GitHub, lea ["Sintaxis de escritura y formato básico"](https://docs.github.com/en/github/writing-on-github/basic-writing-and -formatting-syntax ).

### Interacción con la comunidad de GitHub

La comunidad GitHub es amplia. Hay muchos tipos de personas que utilizan GitHub en su día a día: estudiantes como tú, desarrolladores profesionales, aficionados que trabajan en proyectos de código abierto y exploradores que están saltando en el mundo del desarrollo de software por su cuenta. Hay muchas maneras de interactuar con la comunidad de GitHub más grande, pero aquí hay tres lugares donde puede empezar.

#### Repositorios destacados

Si encuentra un repositorio interesante o desea realizar un seguimiento, ¡destácalo! Cuando destaca un repositorio, también se utiliza como señal para mostrar mejores recomendaciones en github.com/explore. Si desea volver a sus repositorios destacados, puede hacerlo mediante su perfil de usuario.
Para obtener más información sobre cómo destacar los repositorios, lea ["Guardar los repositorios con estrellas"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with- stars).

#### Siguiendo usuarios

Puedes seguir personas en GitHub para recibir notificaciones sobre su actividad y descubrir proyectos en sus comunidades. Cuando siga un usuario, su actividad pública de GitHub se mostrará en su panel de control para que pueda ver todas las cosas interesantes en las que están trabajando.
Para obtener más información sobre cómo seguir usuarios, lea ["Seguir personas"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Navegando por GitHub Explore

GitHub Explore es un lugar fantástico para... explore :smile: Puede encontrar nuevos proyectos, eventos y desarrolladores con los que interactuar.

Puede consultar el sitio web de GitHub Explore [en github.com/explore] (https://github.com/explore). Cuanto más interactúe con GitHub, más adaptada será su vista de exploración.

## 📝 Siguientes pasos opcionales

* Abre una PR y haz saber a tu profesor que has terminado este curso.
* Cree un nuevo archivo de markdown en este repositorio. ¡Utilízalo para mostrar qué ha aprendido y qué todavía le confunde! ¡Experimenta con diferentes estilos!
* Crea tu perfil README. ¡Que el mundo sepa un poco más sobre ti! ¿Qué te interesa aprender? ¿En qué estás trabajando? ¿Cuál es tu afición favorita? Obtenga más información sobre cómo crear su perfil README en el documento ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing - su-perfil-léame).
* Vaya a su panel de usuario y cree un repositorio nuevo. Experimente con las funciones de este repositorio para familiarizarse con él.
* [Háganos saber qué te ha gustado o qué no del contenido de este curso] (https://support.github.com/contact/education). ¿Qué te gustaría ver más? ¿Qué sería interesante o útil para su viaje de aprendizaje?

## 📚 Recursos
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
