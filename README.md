# Tarea 1: Introcuccion a Git

## Descripción
El programa imprime un mensaje en pantalla que al inicio es Hola mundo y al final es Hola Git, la tarea es para comprender los conceptos basicos de Git.

## Instrucciones de uso
Para que nuestro programa funcione los comandos que usamos son javac HolaMundo.java y java HolaMundo.

## Comandos utilizados
+ git init
+ git remote add origin URL-GIT-REPOSITORIO-REMOTO
+ touch .gitignore
+ git add -A
+ git commit -m "mensaje del commit"
+ git push origin master

## Notas sobre el archivo .gitignore
El archivo .gitignore se creo para ignorar los archivos .log, en especifico el debug.log, y asi evitar que estos se suban al repositorio.
El programa al ejecutarse debe mostrar "Hola Git".
Para verificar que debug.log no se subio al repositorio basta con checar los archivos que se encuentrar en el repositorio de GitHub. Si .gitignore se configuro bien, no deberia de estar debug.log en nuestros archivos.
