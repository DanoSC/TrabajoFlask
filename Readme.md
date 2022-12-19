# flask - SQLAlchemy

##Instalacion



![captura imagen 1](imagenes/1.jpg)
 
 Para usar flask y sqlalchemy, creamos un espacion virtual env que como podemos ver en la captura tenemos ya instanciado 
---


![captura imagen 2](imagenes/2.jpg)

Ahora para tener en este entorno instalamos con el comando pip el flask y el flask-sqlalchemy 
---

Ahora en nuesto archivo de python creamos las bases de nuestra base de datos, primero creamos nuestras tablas con sus enlaces. En la siguiente captura se puede ver las 3 tablas creadas, customer order y products  

![captura imagen 3](imagenes/3.jpg)

---

En esta captura podemos ver como se ha creado la base de datos, mediante el flask shell, y con el sqlite3 podemos ver las tablas y su schema

![captura imagen 4](imagenes/4.jpg)

---


##Queries


En esta querri tenemos que añadir a nuestra base de datos 100 cusmer, que los creamos con la funcion add_customers que va creando uno a uno hasta 100 customers y los añade. 
Con add_orders añade 1000 ordenes una a una.
Con add_products añadimos 10 productos a nuestra base de datos 

![captura imagen 1](imagenes/codigoQuerries1a.jpg)
![captura imagen 1](imagenes/codigoQuerries1b.jpg)


Ahora adjunto el codigo resulta de los customer de nuestra base de datos 
![captura imagen 1](imagenes/Queries1.jpg)

---

En esta querri tenemos que imprimir las orders de la base da datos y ordenarlos por el customer id y imprimimos el order_date de cada uno de las orders 

![captura imagen 1](imagenes/codigoQueries2.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries2.jpg)

---

En esta querri tenemos que imprimir las orders pendientes las cuales se ordenaran de manera descendenete 

![captura imagen 1](imagenes/codigoQueries3.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries3.jpg)

---

En esta querri tenemos que imprimir el numero de customer que hay en la tabla, el cual con un count se imprime

![captura imagen 1](imagenes/codigoQueries4.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries4.jpg)

---

En esta querri tenemos que imprimir todos los codigos de las orders, pero sin que el codigo 'FREESHIPPING', por lo cual, acemor un filtro para que no haya ninguno vacion y ademas otro para que no sea del que no queremos y entonces los imprimimos

![captura imagen 1](imagenes/codigoQueries5.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries5.jpg)

---

En esta querri tenemos que imprimir los dias que faltan para el renove pasados tantos dias, por ello tenemos que sumar todos los dias, ademas de hacer joins para saber que dias tenemos que sunmar y con las tablas lo podemos encontrar

![captura imagen 1](imagenes/codigoQueries6.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries6.jpg)

---

En esta querri tenemos que imprimir la media de todos los ordes.shipped_date 
![captura imagen 1](imagenes/codigoQueries7.jpg)


Ahora adjunto el codigo resultante 
![captura imagen 1](imagenes/Queries7.jpg)

---





