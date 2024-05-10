# Trabajo práctico 1​: Codificación y validaciones​
Idiarte, Milagros y Desteffani, Nuria

### Codificación: 

Utilizaríamos una codificación mnemotécnica combinada con una codificación por bloques secuenciales múltiples.
Para la primera parte del código utilizaríamos el nemotécnico para identificar la ubicación de las prendas en la tienda de la siguiente manera:
- Las primeras dos letras representarían el tipo de prenda, la siguiente letra seria “F“ o “M” que representaría Femenino o Masculino respectivamente, las siguientes dos letras representarían el color principal de la prenda, luego se pondrían la cantidad de letras necesarias para indicar el talle (S, M, L, XL, etc.) y por último colocaríamos el año en que la prenda fue lanzada.
A continuación, para la segunda parte del código, asociaríamos al código nemotécnico un código de bloque secuencial múltiple con el cual identificaríamos a cada prenda de forma más específica y única, y lo utilizaríamos de la siguiente manera:
- El primer bloque se utilizaría para identificar el tipo de corte que tiene la prenda, el segundo bloque seria para identificar el tipo de tela con el que está hecho, el tercer bloque seria la temporada del año en el que la prenda salió al mercado y el cuarto y último bloque del código seria para identificar el estilo que tiene la prenda (deportivo, casual, formal, etc.)
Elegimos la combinación de estas dos codificaciones porque nos permite una identificación rápida y eficiente tanto de la ubicación de la prenda en la tienda como de sus características específicas. Los empleados pueden utilizar esta codificación para organizar y encontrar prendas fácilmente. Además, al incluir la ubicación en la estantería en el código, se facilita la reposición y el mantenimiento del inventario.
***
### Validación:

- Verificar que el código tenga la longitud esperada para cada atributo (tipo de prenda, género, color, talla, año).
- Asegurarse de que cada parte del código cumpla con el formato y orden especificado (por ejemplo, las primeras dos letras para el tipo de prenda, la tercera letra para el género, etc.).
- Verificar que los valores utilizados para cada parte del código sean válidos según las especificaciones establecidas (por ejemplo, solo permitir letras para el tipo de prenda, solo permitir “F” o “M” para el género, etc.).
- Verificar que los códigos nemotécnicos y los códigos de bloque secuencial múltiple estén asociados de manera correcta y coherente.
- Asegurarse de que no haya conflictos o inconsistencias entre los datos codificados en ambos sistemas.
- Realizar pruebas utilizando valores extremos y casos límite para garantizar que el sistema pueda manejar diferentes situaciones de manera adecuada.
- Implementar controles de entrada para evitar errores humanos al ingresar los códigos, como la validación de campos obligatorios, formatos incorrectos, etc.
