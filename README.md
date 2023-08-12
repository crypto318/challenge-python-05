# challenge-python-05 - Unit Testing

El unit testing es una forma de comprobar el correcto funcionamiento de una pieza de código, generalmente, una función. En Python, se trabaja con el módulo built-in `unittest`. Se debe crear una _suite_ o _batería de pruebas_ por cada conjunto de tests relacionados de alguna forma. Esto se realiza creando una clase que hereda de `unittest.TestCase`. Con los métodos `setUp` y `tearDown` se pueden inicializar y desechar valores necesarios para correr las pruebas.

### RETO

Aplicando la técnica TDD (Test Driven Development) y el principio FIRST, en el archivo `challenge.py` completa las funciones que retornan las areas de figuras geométricas simples, a partir de los datos necesarios. Antes de eso, elabora los tests que probarán tales funciones.

Aclaraciones:

- El archivo `tests.py` fue el trabajado en clase, puede servirte para recordar el concepto
- No necesitas instalar nada ni crear un entorno virtual, ya que todos los módulos que puedes usar vienen en el core de Python
- Utiliza Python 3 para resolver el reto
- ¡No leas las soluciones de tus compañeros! Es importante que te retes a ti mismo y pruebes tus habilidades

### Pistas

- Cada función en el archivo `challenge.py` recibe como parámetros los datos necesarios para calcular el area de cada figura geométrica respectivamente.
- Si no tienes bases en geometría introductoria, investiga en internet cuales son las fórmulas para calcular cada area.

### Enviar solución

Debes hacer un "Fork" de este proyecto, revolver los problemas y crear un Pull Request hacia este repositorio.

### Contribuir

Si alguien quiere agregar o mejorar algo, puede hacerlo directamente en este repositorio.

### Licencia

challenge-python-05 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).
