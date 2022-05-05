# Permanent_1c
Programa contador de urls


Maso por la linea 110 empieza el codigo
En las lineas de antes esta el diccionario con los enlaces
110 Ponemos el rank, para que haga el ranking y una lista vacia, para luego llenarla con los elementos ya procesados en el ranking
112 Utilizamos for o,g in web, para referirnos a los elementos del diccionario llamada web, asi se va a iterar en todo el diccionario, dividiendolo en dos partes
113 Definimos s y usamos count para que cuente los links que estan compuestos por "https", tambien definimos e=0 para usarlo luego
115 Ponemos un for dentro del anterior for, para que itere la iteracion anterior, y es igual a la cuenta de los links, por eso definimos e=0, para sumarle y, que es la cuenta de los links
118 dentro del for anterior agregamos un if para que cuando el valor de e sea igaul o menor a 0 se le sume 1, para que no se de error por division entre 0
121  De esta linea hasta la linea 122 esta el print de los links entrantes y salientes y su y y s
123 Hacemos la division para el ranking y dividimos r/s
