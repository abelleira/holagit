>mkdir /lab01
>cd /lab01
Crear los ficheros:
hola.txt
  hola
git.txt
  git
README (este fichero)

>git init
>git add .
>git commit -m "versión inicial"

echo "# holagit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:abelleira/holagit.git
git push -u origin main