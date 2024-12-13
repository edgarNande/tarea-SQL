# tarea-SQL
En este proyecto se da bajo el contexto de la segunda tarea práctica en SQL, en la cual, analizamos una serie de intrucciones. Incluye además, un archivo con extensión .sql que contenga todas las consultas realizadas para responder a las preguntas indicadas en las instrucciones del documento "Ejercicio práctico SQL.pdf".
## Contexto
El restaurante "Sabores del Mundo", es conocido por su auténtica cocina y su ambiente
acogedor.
Este restaurante lanzó un nuevo menú a principios de año y ha estado recopilando
información detallada sobre las transacciones de los clientes para identificar áreas de oportunidad y aprovechar al máximo sus datos para optimizar las ventas.
Objetivo
Identificar cuáles son los productos del menú que han tenido más éxito y cuales son los que menos han gustado a los clientes.


### Pasos a seguir
-a) Crear la base de datos con el archivo create_restaurant_db.sql

-b) Explorar la tabla “menu_items” para conocer los productos del menú. 

-1.- Realizar consultas para contestar las siguientes preguntas:

![image](https://github.com/user-attachments/assets/ddca72b6-1ed6-451f-bf96-25449011944b)

● ¿Cuántos platos americanos hay en el menú?

![image](https://github.com/user-attachments/assets/ac55f115-6185-42a2-8d94-f68f546a07c2)

● ¿Cuál es el precio promedio de los platos?



-c) Explorar la tabla “order_details” para conocer los datos que han sido recolectados.
- 1.- Realizar consultas para contestar las siguientes preguntas:
  ● ¿Cuántos pedidos únicos se realizaron en total?
  ![image](https://github.com/user-attachments/assets/7f97f425-fcd1-4db1-8f37-daf1e2f2d52f)

● ¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos?
  
![image](https://github.com/user-attachments/assets/926cbbe4-c4b4-43d4-a1b4-e874a8a0109e)


● ¿Cuándo se realizó el primer pedido y el último pedido?

![image](https://github.com/user-attachments/assets/019b0b71-23f8-439a-b77b-9b5bf5de19f1)

● ¿Cuántos pedidos se hicieron entre el '2023-01-01' y el '2023-01-05'?

![image](https://github.com/user-attachments/assets/4ba2a6e6-843e-40c1-8ae7-f54c4eb89dd2)

- d) Usar ambas tablas para conocer la reacción de los clientes respecto al menú.


● 1.- Realizar un left join entre entre order_details y menu_items con el identificador
item_id(tabla order_details) y menu_item_id(tabla menu_items).

![image](https://github.com/user-attachments/assets/a8d5845d-e7dd-448c-a431-43c3c7d234d9)

- e) Una vez que hayas explorado los datos en las tablas correspondientes y respondido las
preguntas planteadas, realiza un análisis adicional utilizando este join entre las tablas.

- El objetivo es identificar 5 puntos clave que puedan ser de utilidad para los dueños del
restaurante en el lanzamiento de su nuevo menú. Para ello, crea tus propias consultas y
utiliza los resultados obtenidos para llegar a estas conclusiones.

● 1. ¿Cuáles son los artículos más vendidos y cuántos se han vendido?
Esta consulta ayuda a identificar los artículos más populares del menú.

![image](https://github.com/user-attachments/assets/efd6e339-e0e6-432f-a899-14d4c8b4843f)

● 2. ¿Cuáles son los artículos menos vendidos y cuántos se han vendido?
Identificar artículos que podrían necesitar revisión o promoción.

![image](https://github.com/user-attachments/assets/feae61b5-73d8-4792-adb5-15be9db70a1c)

● 3. ¿Cuál es el ingreso generado por cada artículo del menú?
Ayuda a entender qué artículos generan más ingresos.

![image](https://github.com/user-attachments/assets/04c45bd8-4910-4514-b1a5-2262f42f0370)


● 4. ¿Qué categoría de platos (cuisine) es la más popular?
Esta consulta identifica qué tipo de comida prefieren los clientes.

![image](https://github.com/user-attachments/assets/f5d90cbe-7f42-4d48-95e1-656d220b817e)


● 5. ¿Cuál es el día con más pedidos y cuántos se realizaron?
Ayuda a identificar los días de mayor demanda para ajustar la logística.

![image](https://github.com/user-attachments/assets/b964224a-ef7f-4dd4-8023-1ee52eb7299e)






