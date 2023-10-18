Creación de un Repositorio en GitHub

(Terminal: git clone URL_REPOSITORIO)

Crear Rama Principal "main" en VSCode

Asegúrate de que te encuentras en la rama "main" (puede que por defecto se llame "master" dependiendo de tu configuración).
En la esquina inferior izquierda, haz clic en el nombre de la rama (por defecto "master").
Selecciona "Rename Branch" y cambia el nombre a "main".
(Terminal: git branch -m master main)

Crear archivo README.md Vacío en la Rama Main

En el explorador de archivos de VSCode, haz clic derecho en el espacio vacío y selecciona "Nuevo archivo".
Nombralo "README.md".
En la pestaña "Source Control", verás el nuevo archivo. Haz clic en "+" para stagearlo.
Ingresa un mensaje de commit como "Añadir README.md vacío" y haz clic en el ícono de check para hacer commit.
Haz clic en el ícono de "Cloud" en la parte superior para subir ("push") los cambios a GitHub.
Si te sale un error que dice que no existe la rama "main" en el repositorio remoto, deberás realizar el push desde la terminal.
(Terminal: git add README.md seguido de git commit -m "Añadir README.md vacío" y luego git push)

Crear una Rama en VSCode

En la esquina inferior izquierda, haz clic en "main" (o el nombre de la rama actual).
Selecciona "Create New Branch" y nómbrala "feature/mi-nueva-caracteristica".
Asegúrate de que se ha cambiado automáticamente a la nueva rama.
(Terminal: git checkout -b feature/mi-nueva-caracteristica)

Realizar un Cambio en Local y Commit

Edita el archivo "README.md" y añade el contenido sugerido anteriormente.
En la pestaña "Source Control", verás los cambios. Haz clic en "+" para stagearlos.
Usa la extensión "Conventional Commits" para hacer commit.
(Terminal: git add README.md seguido de git commit -m "mensaje")

Subir Cambios a GitHub desde VSCode

En la pestaña "Source Control", haz clic en el ícono de "Cloud" en la parte superior para pushear los cambios a la rama en GitHub.
(Terminal: git push -u origin feature/mi-nueva-caracteristica)

Forzar un Conflicto

En GitHub, ve a tu archivo "README.md" y haz clic en el ícono de lápiz para editarlo.
Cambia algo en el mismo lugar que editaste localmente y haz commit directamente en GitHub.
Esto provocará un conflicto cuando intentes fusionar o hacer pull más tarde.

Crear un Pull Request en GitHub

Regresa a tu repositorio y haz clic en "Pull request".
Selecciona "New pull request" y asegúrate de comparar main con feature/mi-nueva-caracteristica.
Haz clic en "Create pull request".

Solucionar Conflictos en GitHub

GitHub te mostrará que hay conflictos en el Pull Request.
Haz clic en "Resolve conflicts".
Decide qué versión del contenido quieres mantener o combinar y edita directamente.
Haz clic en "Mark as resolved" y luego "Commit merge".

Fusionar el Pull Request

Haz clic en "Merge pull request", luego "Confirm merge".
