
# Complex Numbers Library

Librería en Python para realizar operaciones con números complejos modelados como tuplas.

## Getting Started
Este proyecto proporciona una librería para trabajar con números complejos sin utilizar el tipo de dato `complex` de Python. A continuación, se describen los pasos para obtener y ejecutar el proyecto.


### Prerequisites
Python 3.8 o superior.

### Installing
1. Clona el repositorio:
   ```bash
   git clone https://github.com/jsfa2002/complex_numbers_project.git
   cd complex_numbers_project

### Uso 
La librería operations.py contiene funciones para realizar las siguientes operaciones con números complejos:

Suma: Suma dos números complejos.

Resta: Resta dos números complejos.

Producto: Multiplica dos números complejos.

División: Divide dos números complejos.

Módulo: Calcula el módulo de un número complejo.

Conjugado: Obtiene el conjugado de un número complejo.

Conversión a polar: Convierte un número complejo de cartesiano a polar.

Conversión a cartesiano: Convierte un número complejo de polar a cartesiano.

Fase: Obtiene la fase de un número complejo.

#### Ejemplo de uso:
from complex_numbers.operations import suma, resta, producto, division

Definir números complejos
z1 = (3, 4)  # 3 + 4i
z2 = (1, 2)  # 1 + 2i

Sumar dos números complejos
resultado_suma = suma(z1, z2)
print(f"Suma: {resultado_suma}")

Restar dos números complejos
resultado_resta = resta(z1, z2)
print(f"Resta: {resultado_resta}")

### Ejecutar las pruebas
El proyecto incluye pruebas automáticas que aseguran que todas las funciones de la librería funcionen correctamente. Puedes ejecutar estas pruebas usando el framework unittest de Python.

Ejecuta las pruebas automáticas con el siguiente comando:

```bash
   python -m unittest discover tests/
``` 
El sistema ejecutará las pruebas definidas en el directorio tests/ y te mostrará los resultados.

### Deployment

Este proyecto está listo para ser utilizado como una librería local. Puedes integrarlo fácilmente en otros proyectos de Python que necesiten realizar operaciones con números complejos sin usar el tipo de dato complex.

### Built With
Python - Lenguaje de programación utilizado
unittest - Framework para pruebas automáticas
### License
Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE.md para más detalles.

### Acknowledgments
Gracias a la comunidad de Python por el soporte y las bibliotecas que hacen posible proyectos como este.

