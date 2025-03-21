

Reto: Insp3ct0r
Descripción: necesita inspeccion,
 se debe seguir un link en el cual muestra 2 ventanas una que dice: yo hice esto y la segunda que nos indica el como en este caso inspeccionamos el codigo fuente y nos encontramos con una parte de la bandera 
 ![imagen](https://github.com/user-attachments/assets/bac090a4-5606-4c50-8bbe-7a5c56031736)
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
refrescamos el sitio y asi nos aparece la bandera.

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
Solucion:
Notas adicionales:
Referencias:

__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________
