# apache beam aproach

this program runs apache beam pipelines to read a file and get filtered data,
in this particular case we get a sorted list of most used words in the text,
the program receives as aparameter the number of words we want in the list using the
** --n-palabras variable**

> Reqquirements:
*apache-beam[gcp]

> command to run:  
* python3 main.py  --n-palabras 100 --entrada ./muestra.txt --salida out/salida.txt --runner DirectRunner# apache-beam
