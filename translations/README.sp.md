[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="https://firstcontributions.github.io/assets/Readme/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/zt-1hg51qkgm-Xc7HxhsiPYNN3ofX2_I8FA)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)

# Primeras Contribuciones

Este proyecto tiene como objetivo simplificar y guiar la forma en que los principiantes hacen su primera contribución. Si estás buscando hacer tu primera contribución, sigue los pasos a continuación.

_**Si no te sientes cómodo con la línea de comandos, [aquí tienes tutoriales usando herramientas gráficas.](#tutoriales-usando-otras-herramientas)**_

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="haz un fork de este repositorio" />

**Si no tienes Git en tu máquina, [instálalo](https://docs.github.com/en/get-started/quickstart/set-up-git).**

## Haz un "Fork" de este repositorio

Haz un "fork" de este repositorio haciendo clic en el botón "Fork" en la parte superior de esta página.
Esto creará una copia de este repositorio en tu cuenta.

## Clona el repositorio

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clona este repositorio" />

Ahora clona el repositorio que hiciste "fork" a tu máquina. Ve a tu cuenta de GitHub, abre el repositorio que hiciste "fork", haz clic en el botón "Code" y luego haz clic en el icono de "copiar al portapapeles".

Abre tu terminal y ejecuta el siguiente comando de Git:

```bash
git clone "la URL que acabas de copiar"
Donde "la URL que acabas de copiar" (sin las comillas) es la URL de este repositorio (tu "fork" de este proyecto). Consulta los pasos anteriores para obtener la URL.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copia la URL al portapapeles" />
Por ejemplo:


git clone git@github.com:este-eres-tu/first-contributions.git
Donde este-eres-tu es tu nombre de usuario en GitHub. Aquí estás copiando el contenido del repositorio "first-contributions" en GitHub a tu computadora.

Crea una rama
Cambia al directorio del repositorio en tu computadora (si aún no estás allí):

cd first-contributions
Ahora crea una rama usando el comando git switch:


git switch -c tu-nueva-rama
Por ejemplo:


git switch -c agregar-alonzo-church
Realiza los cambios necesarios y realiza un "commit"
Ahora abre el archivo Contributors.md en un editor de texto, agrega tu nombre. No lo agregues al principio ni al final del archivo. Ponlo en cualquier otro lugar. Ahora, guarda el archivo.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="estado de git" />
Si vas al directorio del proyecto y ejecutas el comando git status, verás que hay cambios.

Agrega esos cambios a la rama que acabas de crear con el comando git add:


git add Contributors.md
Ahora haz un "commit" de esos cambios usando el comando git commit:


git commit -m "Agrega tu-nombre a la lista de Contribuidores"
Reemplaza tu-nombre con tu nombre.

Sube los cambios a GitHub
Sube tus cambios usando el comando git push:


git push -u origin tu-rama
Reemplaza tu-rama con el nombre de la rama que creaste anteriormente.

<details>
<summary> <strong>Si obtienes algún error al subir, haz clic aquí:</strong> </summary>
Error de Autenticación
   <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/<tu-nombre-de-usuario>/first-contributions.git/'</pre>
Ve a este tutorial de GitHub sobre cómo generar y configurar una clave SSH para tu cuenta.
</details>
Envía tus cambios para revisión
Si vas a tu repositorio en GitHub, verás un botón Compare & pull request. Haz clic en ese botón.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="crea una pull request" />
Ahora, envía la pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="enviar pull request" />
Pronto estaré fusionando todos tus cambios en la rama principal de este proyecto. Recibirás un correo electrónico de notificación una vez que los cambios se hayan fusionado.

¿Y ahora qué?
¡Felicidades! Acabas de completar el flujo de trabajo estándar fork -> clone -> edit -> pull request que a menudo encontrarás como contribuidor.

Celebra tu contribución y compártela con tus amigos y seguidores yendo a la aplicación web.

Puedes unirte a nuestro equipo en Slack si necesitas ayuda o tienes alguna pregunta. [Únete al equipo en Slack](https://join.slack.com/t/firstcontributors/shared_invite/zt-1n4y7xnk0-DnLVTaN6U9xLU