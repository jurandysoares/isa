Meias
=====

#. O que fazem os comandos abaixo?

* grep meia meias.txt
* grep Meia meias.txt

* grep -i meia meias.txt
* grep -vi meia meias.txt

* grep -c meia meias.txt
* grep -c Meia meias.txt
* grep -ci meia meias.txt

* grep não meias.txt
* grep -i não meias.txt
* grep -vi não meias.txt

* grep sim meias.txt
* grep Sim meias.txt
* grep -i sim meias.txt
* grep -w sim meias.txt
* grep -wi sim meias.txt

* grep '\*[a-z]\*' meias.txt
* grep -v '\*[a-z]\*' meias.txt

*  egrep '[0-9]+' meias.txt
*  egrep -o '[0-9]+' meias.txt
*  egrep -o '[0-9]{1}' meias.txt
*  egrep -o '[0-9]{2}' meias.txt
*  egrep -o '[0-9]{3}' meias.txt
*  egrep -qo '[0-9]{2}' meias.txt && echo "Achou!"
*  egrep -qo '[0-9]{3}' meias.txt || echo "Não achou!"


* grep '?$' meias.txt
* grep -v '?$' meias.txt



