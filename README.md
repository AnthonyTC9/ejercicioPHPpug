# ejercicioPHPpug
Ejercicio de uso de sintaxis php con pug

para dejar observando los archivos en pug, para que se auto guarden los cambios es:

pug -w . -o ./ -P

o si queremos que se actualice solo cierto archivo

pug -w index.pug -o ./ -P

y si quieremos crear un html desde un archivo pug se usa

pug index.pug

y asi creamos el html del index pug

para creear un archivo php desde un pug es:

pug -w index.pug -o ./ -P -E php

y esto nos creara index.php de nuestro index.pug
