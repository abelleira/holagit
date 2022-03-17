Crear directorio
>mkdir /lab01
Ponerse en el directorio
>cd /lab01

Crear los ficheros:
hola.txt
  hola
git.txt
  git
README.md (este fichero)

Iniciar
>git init
Añadir el conteniod
>git add .
Primer commint
>git commit -m "versión inicial

Crear en Github un repositorio en blanco.
Conectamos el local con el remoto.
git remote add origin git@github.com:abelleira/holagit.git
Primer push, subimos el contenido al remoto
git push -u origin main
