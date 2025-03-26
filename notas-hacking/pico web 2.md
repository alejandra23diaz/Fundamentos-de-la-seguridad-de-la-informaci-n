Reto: GET aHEAD
Descripcion:

primero vamos al link que nos indican en el reto
![imagen](https://github.com/user-attachments/assets/c8ae33f2-0ed3-48c8-8adf-e1a25ac6ea33)
![imagen](https://github.com/user-attachments/assets/18c5176e-bf19-4f52-8a9f-5d3ac4b23921)

y despues entramos al codigo fuente, en el cual encontramos este codigo 
![imagen](https://github.com/user-attachments/assets/393d804c-7b66-474b-aab4-24d641db7085)
![imagen](https://github.com/user-attachments/assets/84272165-353f-49fb-a243-794f942cae02)
despues vamos a la terminal y probamos varios codigos por ejemplo curl -X GET http://mercury.picoctf.net:45028/index.php, curl -X POST http://mercury.picoctf.net:45028/index.php
curl -X HEADER http://mercury.picoctf.net:45028/index.php
 en el ultimo caso no funciono, por lo tanto cambiamos a curl -I http://mercury.picoctf.net:45028/index.php
 Con el cual nos entrega la bandera.
Solucion: picoCTF{r3j3ct_th3_du4l1ty_775f2530}
Notas adicionales:
Referencias:
