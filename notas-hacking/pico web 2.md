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
![imagen](https://github.com/user-attachments/assets/9419cbe7-af0c-4397-9740-9b8221e17ea4)

Solucion: picoCTF{r3j3ct_th3_du4l1ty_775f2530}
Notas adicionales:
Referencias:

										
Reto: Cookies
Descripcion: 
Entramos al sitio que nos indica el reto
http://mercury.picoctf.net:64944/

![imagen](https://github.com/user-attachments/assets/df5e4bf3-286a-471a-a00f-682dfd1fb673)
![imagen](https://github.com/user-attachments/assets/d10d7559-529e-4557-97bf-5c224bd0941b)



vamos a tomar el diagonal check desde la terminal

http://mercury.picoctf.net:64944/check

despues vamos a escribir lo siguiente en nuestra terminal:
 curl -s  http://mercury.picoctf.net:64944/check -H "Cookie: name=18";
por lo cual nos indicara el valor de la cookie

![imagen](https://github.com/user-attachments/assets/6e00b047-1189-4d67-8d60-63e382bb214d)


solucion: picoCTF{3v3ry1_l0v3s_c00k135_cc9110ba}
Notas adicionales:
Referencias:

Reto: Cookies
Descripcion: 
Entramos al sitio que nos indica el reto
http://mercury.picoctf.net:64944/
![imagen](https://github.com/user-attachments/assets/0f3da235-9710-4cf1-882c-3e8cb1cf11c7)

![imagen](https://github.com/user-attachments/assets/b02eef9c-b7ba-43d6-b78c-5300aec22939)

vamos a tomar el diagonal check desde la terminal

http://mercury.picoctf.net:64944/check

despues vamos a escribir lo siguiente en nuestra terminal:
 curl -s  http://mercury.picoctf.net:64944/check -H "Cookie: name=18";
por lo cual nos indicara el valor de la cookie
![imagen](https://github.com/user-attachments/assets/782460bb-04ee-4b7c-90b3-68e2c689fe18)


solucion: picoCTF{3v3ry1_l0v3s_c00k135_cc9110ba}
Notas adicionales:
Referencias:


Reto: Scavenger Hunt
![imagen](https://github.com/user-attachments/assets/fc445af6-487b-45b7-a614-1273bccf81e0)


Descripcion: 
buscaremos en el link que se nos dio y encontraremos una pagina web, 
despues iremos al  codigo fuente y encontraremos la parte inicial de la bandera
![imagen](https://github.com/user-attachments/assets/af4b1d50-92fe-4703-811c-69b6991cfb45)

y de ahi encongtramos un archivo con terminacion .css en el cual encontraremos la parte 2 de la bandera
![imagen](https://github.com/user-attachments/assets/d29f7a3a-911f-4bae-8c60-8a22c288ed36)

despues nos iremos al final de la URL en la cual escribiremos /robots.txt
![imagen](https://github.com/user-attachments/assets/af40c18a-c985-471b-b476-c889ea77a1d7)

despues vamos a copiar .htaaccess al final de la URL lo cual nos dara otra parte de la solucion
![imagen](https://github.com/user-attachments/assets/c9d0a10f-ddd0-44bf-9f83-74a91c5be8b2)


despues apuntaremos .DS_Store al final de la URL lo cual nos dara la parte final de la bandera
![imagen](https://github.com/user-attachments/assets/f5644702-fab7-4284-962e-5fcf43f22998)
Solucion: picoCTF{th4ts_4_l0 t_0f_pl4c3s_2_lO0k_d375c750}
Notas adicionales:
Referencias:
