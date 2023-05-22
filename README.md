# SQL4
en este ejemplo se realiza lo siguiente:
1. Crea el modelo relacional
2. Inserta 5 pel�culas y 5 tags, la primera pel�cula tiene que tener 3 tags asociados, la segunda pel�cula debe tener dos tags asociados.
3. Cuenta la cantidad de tags que tiene cada pel�cula. Si una pel�cula no tiene tags debe mostrar 0.
preguntas, la primera pregunta debe estar contestada
4. Crea las tablas a partir del modelo relacional respetando los nombres, tipos, claves primarias y for�neas y tipos de datos.
5. Agrega datos, 5 usuarios y 5 preguntas, la primera pregunta debe estar contestada dos veces correctamente por distintos usuarios, la pregunta 2 debe estar contestada correctamente s�lo por un usuario, y las otras 2 respuestas deben estar incorrectas.
    a. Contestada correctamente significa que la respuesta indicada en la tabla respuestas es exactamente igual al texto indicado en la tabla de preguntas.
6. Cuenta la cantidad de respuestas correctas totales por usuario (independiente de la pregunta).
7. Por cada pregunta, en la tabla preguntas, cuenta cu�ntos usuarios tuvieron la respuesta correcta.
8. Implementa borrado en cascada de las respuestas al borrar un usuario y borrar el primer usuario para probar la implementaci�n.
9. Crea una restricci�n que impida insertar usuarios menores de 18 a�os en la base de datos.
10. Altera la tabla existente de usuarios agregando el campo email con la restricci�n de �nico.