# ACTIVIDAD DIRIGIDA 2

En esta actividad consiste en comentar lo realizado como un ejercicio de programación.

### Paso a Paso
1. Lo primero fue entrar a mi repositorio en GitHub [sanchezcamarg16-web](https://github.com/nebrijas/sanchezcamarg16-web/settings/pages). Luego se procedió a configurar main y root. Esto convirtió el repositorio en HTML.
2. Posteriormente fui a (code) para crear un nuevo archivo (con Add file) y renombrarlo como ad2.md.
3. Los próximos cambios se dieron en el local, se descargó GitBash y se procedió a abrir e ir a la terminal (Se utilizaron una serie de comandos).
4. Se procedió a escrbiri las letras `pwd` y dar enter para entrar para ver en qué directorio nos encontramos.
5. Luego clonamos mi repositorio a través de git clone https://github.com/nebrijas/sanchezcamarg16-web y le damos enter para copiar el directorio de nuestro repositorio.
Para acceder a ella colocamos `cd` [sanchezcamarg16-web/], dar enter y escribir `ls` (para verificar el contenido).
Escribí `git config user.name` (seguido de mi usuario de GitHub sanchezcamarg16-web) y enter. Así mismo se escribió `git config user.mail maricarmen160190@gmail.com` (seguido del correo que utilizas en GitHub) y enter.
En el navegador, generamos un Token en [https://github.com/settings/token](https://github.com/settings/tokens).Le damos “Generate new token y darle el nombre del note que deseamos (ejemplo pd2). En expiration le colocamos 60 días, en select scopes seleccionar “repo” (para que se activen todas las casillas de repo) y le damos generar token (copiarlo).
De regreso en la terminal de GitBash se colocó `echo "(aquí dentro el token copiado previamente)" > ../.token`.
Escribimos nano REDME.md y le dimos entrar, se abre una consola para editar para poner un título y dos enlaces.
Después colocamos `git status` y damos enter para visualizar las modificaciones.
Luego con `git add` se añade los cambios realizados, luego `git commit -m “añado ad2.md”`y enter.
Ponemos `git push` y enter para guardar en contenido en GitHub.
Y comprobamos que está la nueva carpeta online.