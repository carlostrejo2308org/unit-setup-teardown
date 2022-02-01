# SetUp y TearDown
Cuando usamos pruebas unitarias, a veces es necesario hacer pasos anteriores antes y después de cada prueba. Estos pueden ser, asegurar que algunos requisitos se cumplan, inicializar variables, tareas repetitivas, entre otros.

## SetUp
Este método se llama antes de llamar el método de prueba. Cualquier error que surja durante este paso, se considerara un error y no una falla de algún caso de prueba

## TearDown
Este método se llama justo después de cada caso de prueba.

## Actividad
1. Analiza la clase "FileReader" dentro de process.py

2. Crea un archivo llamado "test_process.py" donde escribirás tus casos de prueba

3. Escribe una clase llamada "TestFileReader" de la siguiente manera:

`class TestFileReader(unittest.TestCase):`

4. Escribe la funcion "setUp" donde harás una instancia a la clase FileReader, crees un archivo llamado "test1.txt" con varias lineas de texto

5. Escribe la funcion "tearDown" donde eliminaras el archivo "test1.txt" y borraras la instancia de "FileReader"

6. Crear suficientes casos de pruebas para probar la clase. Asegurate que todas las variables se computen de manera correcta, por ejemplo "num_lines", puede leer un archivo y devolver el texto dentro del archivo.

7. Asegurate de comprender casos de prueba suficientes, por ejemplo:
   1. ¿Que pasa si el archivo viene vació?
   2. ¿Que pasa si no existe el archivo?
   3. ¿Que pasa si quiere cerrar el archivo antes de abrirlo?
   4. ¿Que pasa si quiero abrirlo antes de decirle cual es su path?


Asegurate de comentar tu código y "guardarlo" (add, commit y push)