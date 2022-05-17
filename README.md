# -PR4.5.-eefactorizando-en-eclipse

En Eclipse la refactorización queda resumida en el menú Refactor. Documenta, a ser posible en tu propio código del módulo de programación,  su uso en los siguientes casos:

**1. Renombrar métodos**

Le damos click derecho sobre el método, Refactor > Extract Method...
![?](imagenes/img1.PNG)

Escribimos el nuevo nombre que queramos darle al método y le damos a "OK" para que se realice el cambio
![?](imagenes/img1.2.PNG)

Podemos ver como en todos los métodos que antes se llamaban "estaMuerto" ahora se llaman "redEstaMuerto"
![?](imagenes/img1.3.PNG)


**2. Renombrar paquetes**

Le damos en el paquete click derecho y:
![?](imagenes/img2.PNG)

Ponemos el nuevo nombre que queramos darle al paquete
![?](imagenes/img2.1.PNG)

Podemos observar como se ha cambiado el nombre tanto en el paquete como en los documentos que usan ese paquete de referencia
![?](imagenes/img2.2.PNG)



**3. Encapsula campo**

Click derecho sobre el campo que queramos encapsular y:
![?](imagenes/img3.PNG)

Seleccionamos si queremos los setters, los getters, o ambos
![?](imagenes/img3.1.PNG)

Podemos observar como ha emcapsulado el peso (antes era simplemente peso++/peso--)
![?](imagenes/img3.3.PNG)


**4. Extrae clase**

Click derecho en el documento y:
![?](imagenes/img4.PNG)

Extraemos la clase con los datos que decidamos
![?](imagenes/img4.1.PNG)

Podemos ver como nos genera otro documento con el nombre que le hemos dado y con los datos que hemos escogido
![?](imagenes/img4.2.PNG)


**5. Extrae interface**

Click derecho en el documento y:
![?](imagenes/img5.PNG)

Extraemos la interfaz con el nombre y datos que decidamos
![?](imagenes/img5.1.PNG)

Podemos observar como nos genera otro documento con el nombre y datos que hemos asignado
![?](imagenes/img5.2.PNG)


**6. Extrae constante**

Seleccionamos el dato que queramos tomar como constante (normalmente es un dato que se vaya a repetir varias veces, asi cuando queramos cambiar su valor solo lo cambiamos en la constante, y ya afecta a todo el documento) y:
![?](imagenes/img6.PNG)

Le damos el nombre que encontremos mas adecuado:
![?](imagenes/img6.1.PNG)

Podemos observar como al inicio de nuestro documento nos sale la constante y su valor
![?](imagenes/img6.2.PNG)

Antes aquí nos salía el valor de la constante (1), ahora nos sale el nombre que le hemos asignado
![?](imagenes/img6.3.PNG)





**7. Extrae método**



**8. Extrae variable local**



**9. Todo en una línea (inlining)**



**10. Subir/bajar (pull up/push down)**