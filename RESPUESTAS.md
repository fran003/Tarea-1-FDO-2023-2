¿Si ejecutas el comand git blame main.py qué ocurre?

Respuesta :
aparece el codigo de main.py por linea indicando quien es el autor del cambio y en que commit se realizo.

Explica cómo funciona el comando log del paso 5

Respuesta : se usa para ver la historia de commits de un repositorio, pero mostrando la información de una manera personalizada. En este caso, lo que hace es que cuando lo ejecutas, te muestra una lista de los commits con detalles específicos:
%h te muestra el número abreviado que identifica cada cambio.
%an muestra quién hizo ese cambio.
%as te da la fecha del cambio pero en un formato más compacto.
: %s muestra el mensaje asociado a ese cambio, es decir, lo que se escribió para describir qué se modificó.

¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?

Respuesta: el profesor modifico 6 veces  el archivo , lo determine usando el comando
 git log --pretty=format:" - %h %an %as: %s" README.md
  incluye  creación del archivo
  
 - 94c9920 Eduardo Díaz 2023-10-26: feat: add a question
 - 5a41842 Eduardo Díaz 2023-10-26: Update README.md
 - 335c0c2 Eduardo Díaz 2023-10-25: Update README.md
 - 329f5a9 Eduardo Díaz 2023-10-25: Update README.md
 - 886d0f0 Eduardo Díaz 2023-10-25: feat: Update README.md
 - 5c2c29d Eduardo Díaz 2023-10-25: feat: Create README.md



Anota los nombres de los integrantes del grupo que realizó la tarea
Francisca Valdés
