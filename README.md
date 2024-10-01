# NumPy-y-Pandas

NumPy es una librería de Python especializada en el cálculo numérico y el análisis de datos, especialmente para un gran volumen de datos.

Incorpora una nueva clase de objetos llamados arrays que permite representar colecciones de datos de un mismo tipo en varias dimensiones, y funciones muy eficientes para su manipulación.

La ventaja de Numpy frente a las listas predefinidas en Python es que el procesamiento de los arrays se realiza mucho más rápido (hasta 50 veces más) que las listas, lo cual la hace ideal para el procesamiento de vectores y matrices de grandes dimensiones.

La clase de objetos array
Un array es una estructura de datos de un mismo tipo organizada en forma de tabla o cuadrícula de distintas dimensiones.

Las dimensiones de un array también se conocen como ejes.

Arrays

Creación de arrays
Para crear un array se utiliza la siguiente función de NumPy

np.array(lista) : Crea un array a partir de la lista o tupla lista y devuelve una referencia a él. El número de dimensiones del array dependerá de las listas o tuplas anidadas en lista:

Para una lista de valores se crea un array de una dimensión, también conocido como vector.

Para una lista de listas de valores se crea un array de dos dimensiones, también conocido como matriz.

Para una lista de listas de listas de valores se crea un array de tres dimensiones, también conocido como cubo.

Y así sucesivamente. No hay límite en el número de dimensiones del array más allá de la memoria disponible en el sistema.
