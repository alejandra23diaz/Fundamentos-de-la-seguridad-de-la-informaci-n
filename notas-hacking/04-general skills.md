

Reto: Insp3ct0r
Descripción: necesita inspeccion,
 se debe seguir un link en el cual muestra 2 ventanas una que dice: yo hice esto y la segunda que nos indica el como en este caso inspeccionamos el codigo fuente y nos encontramos con una parte de la bandera 
![imagen](https://github.com/user-attachments/assets/ada31da1-1002-4990-ac1d-13a3fc15cdd8)

despues entramos en la pagina de estilos en donde vamos hasta el final de la pagina en donde encontramos la segunda parte de la bandera
![imagen](https://github.com/user-attachments/assets/ed3c1397-7dae-4214-9f91-d10964044d92)
para encontrar la ultima parte de la bandera lo encontramos en un archivo de java script.
![imagen](https://github.com/user-attachments/assets/fe849696-3cce-4c16-99db-0718643de52b)


Solución:  picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699}
Notas adicionales:
Referencias

__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________

Reto: Where are the robots
Descripción: debemos encontrar que parte del sitio web el progrmador no quiere que miremos, por lo tanto investigamos a que se refiere el termino robot, por lo cual encontramos que es un archivo el cual indica que archivo no podemos utilizar.
![imagen](https://github.com/user-attachments/assets/2c12b923-9159-458b-b39c-067ab0f221e1)
por lo tanto procedemos a buscar ese archivo en el buscador de la pagina principal
![imagen](https://github.com/user-attachments/assets/67ba5d3a-4115-4faf-83b8-2b835510c2d6)
lo cual nos entrega la bandera que necesitamos.
![imagen](https://github.com/user-attachments/assets/3af712f8-f3ac-41c9-b2a4-3c7569ce56ae)

investigamos como funciona el http en un modelo de cliente- servidor
Solución:  picoCTF{ca1cu1at1ng_Mach1n3s_8028f} 
Notas adicionales:
Referencias:
https://developers.google.com/search/docs/crawling-indexing/robots/intro?hl=es


__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________

Reto: Logon
Descripcion: debemos seguir una liga la cual es una pagina de login despues entramos en el login como usuario: admin y contraseña: holamundo, el cual nos permite entrar al login 
![imagen](https://github.com/user-attachments/assets/599b09e1-1fe2-44c7-94fd-5543fbfcdd48)

investigamos como funciona el http en un modelo de cliente- servidor
despues de estar inspeccionando los complementos del html, entramos a la parte de las cookies para modificar el valor que tiene, para esto descargamos un complemento en el navegador el cual nos ayudara a editar las cookies y cambiar la opcion del admin a verdadero para poder observar la bandera que necesitamos 
![imagen](https://github.com/user-attachments/assets/064e5f69-f931-4cb9-834a-927d271f45d5)
refrescamos el sitio y asi nos aparece la bandera.icobrowser
![imagen](https://github.com/user-attachments/assets/7906384a-eedf-4938-8a04-eb9b9835e302)


Solucion:picoCTF{th3_c0nsp1r4cy_l1v3s_d1c24fef}
Notas adicionales:
Referencias:
https://developer.mozilla.org/es/docs/Web/HTTP


__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
Reto: dont-use-client-side

Descripcion:
Entramos al link que nos indica en el reto, lo cual nos lleva a una pagina donde debemos verificar una contraseña, sin embargo, como no nos permite ingresar, entramos al codigo fuente de la pagina, en el cual aparece una serie de instrucciones en el cual valida la contraseña, pero notamos que ahi se encuentra la bandera, por lo tanto debemos formarla ya que esta dividida en 8 partes
![imagen](https://github.com/user-attachments/assets/3e621865-eb44-436e-a9b7-3764424dd66a)

Solucion:picoCTF{no_clients_plz_1a3c89}
Notas adicionales:
Referencias:

__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
Reto: Client-side-again
Descripcion: Entramos al link que nos entregan en el reto el cual nos abre una pagina para ingresar la contraseña nuevamente, sin embargo en este caso vamos directamente al inspector de codigo, despues entramos a la parte de depurar el codigo, para encontrarnos con un texto el cual parece ser la bandera, 
![imagen](https://github.com/user-attachments/assets/1128da0a-8ad0-48ff-9975-efb097ce7ba5)

sin embargo esta demasiado ofuscado, por lo tanto entramos a una pagina llamada  Js nice, la cual nos ayuda a acomodar el texto y asi entender un poco mas el texto
![imagen](https://github.com/user-attachments/assets/0b099456-3bb0-43e6-a33c-a806ca179229)
 despuess copiamos la variable que se encuentra al inicio y la pegamos en la consola, lo cual nos ayudara a formar de manera mas facil la bandera.
 ![imagen](https://github.com/user-attachments/assets/a7301bd5-13b7-4a6e-9595-e6c695384b3d)


Solucion:picoCTF{not_this_again_337115}
Notas adicionales:
Referencias:

__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
