# ExamenDes.Apli.Dist1erBimestre_Hilos
Examen Desarrollo de Aplicaciones distribuidas ejemplo de hilos

Empezamos importando la libreria "Threading" la cual nos permite ejecutar multiples procesos de manera simultanes.
![image](https://user-images.githubusercontent.com/58209320/178613691-4bb1e0a1-ccf5-4b87-b762-c990cd873f95.png)

Definimos una funcion en la cual definimos un entero el cual se va incrementando en 1 en la duracion de un ciclo, esto mientras el valor sea inferior a 10 como se define en el bucle, que a su ves se presenta con el print en la ejecucion de cada aumento. Como segundo argumento pasamos name que identifica los procesos simultaneos que van a pasar.

![image](https://user-images.githubusercontent.com/58209320/178614152-c9d67f5b-0b58-46a9-a37b-37d903414257.png)

A continuacion definimos tres objetos (t,t2,t3) que junto al metodo threading.Thread creara cada uno de los procesos que se ejecutan de manera simultanea. Las siguientes dos variables, target que establece la funcion que ejecuta cada proceso, y arg, que establece el valor inicial de n.

![image](https://user-images.githubusercontent.com/58209320/178614581-b03ba763-d1ea-4e98-8172-9324dfbe6ac0.png)

Por ultimo inicamos cada uno de los procesos con strat()

![image](https://user-images.githubusercontent.com/58209320/178614661-af9eca28-497c-4c02-a77f-69ed706b1ec4.png)


Resultados
![image](https://user-images.githubusercontent.com/58209320/178614819-31484dd1-7445-4634-8289-ea4bb2fef71a.png)
![image](https://user-images.githubusercontent.com/58209320/178614843-4a5d7e21-9801-44eb-82e4-9e5919bad81d.png)
