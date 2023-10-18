Creación de un Repositorio en GitHub

(Terminal: git clone URL_REPOSITORIO)

Crear Rama Principal "main" en VSCode

Asegúrate de que te encuentras en la rama "main" (puede que por defecto se llame "master" dependiendo de tu configuración).
En la esquina inferior izquierda, haz clic en el nombre de la rama (por defecto "master").
Selecciona "R
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

Regresa a tu repoirectamente.
Haz clic en "Mark as resolved" y luego "Commit merge".

Fusionar el Pull Request

Haz clic en "Merge pull request", luego "Confirm merge".
