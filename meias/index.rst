Meias
=====

#. O que fazem os comandos abaixo?

Meia?
-----

* grep meia meias.txt
* grep Meia meias.txt

* grep -i meia meias.txt
* grep -vi meia meias.txt

* grep -c meia meias.txt
* grep -c Meia meias.txt
* grep -ci meia meias.txt

Não?
----

* grep não meias.txt
* grep -i não meias.txt
* grep -vi não meias.txt

Sim?
----

* grep sim meias.txt
* grep Sim meias.txt
* grep -i sim meias.txt
* grep -w sim meias.txt
* grep -wi sim meias.txt

Texto?
------

* grep '\*[a-z]\*' meias.txt
* grep -v '\*[a-z]\*' meias.txt

Número?
--------

*  egrep '[0-9]+' meias.txt
*  egrep -o '[0-9]+' meias.txt
*  egrep -o '[0-9]{1}' meias.txt
*  egrep -o '[0-9]{2}' meias.txt
*  egrep -o '[0-9]{3}' meias.txt
*  egrep -qo '[0-9]{2}' meias.txt && echo "Achou!"
*  egrep -qo '[0-9]{3}' meias.txt || echo "Não achou!"

Palavras?
---------

* egrep '\b[a-z]{1}\b' meias.txt
* egrep '\b[a-z]{2}\b' meias.txt
* egrep '\b[a-z]{3}\b' meias.txt
* egrep '\b[a-z]{4}\b' meias.txt
* egrep '\b[a-z]{5}\b' meias.txt
* egrep '\b[a-z]{6}\b' meias.txt
* egrep '\b[a-z]{4,6}\b' meias.txt
* egrep -i '\b[a-z]{4,6}\b' meias.txt
* egrep -ci '\b[a-z]{4,6}\b' meias.txt
* egrep -oi '\b[a-z]{4,6}\b' meias.txt
* egrep -vio '\b[a-z]{4,6}\b' meias.txt
* egrep -qio '\b[a-z]{4,6}\b' meias.txt

Pontuação?
------------

* grep '?$' meias.txt
* grep -v '?$' meias.txt
* grep '.$' meias.txt
* grep '\.$' meias.txt
* grep -c '\.$' meias.txt
* grep -v '\.$' meias.txt
* grep -vc '\.$' meias.txt
