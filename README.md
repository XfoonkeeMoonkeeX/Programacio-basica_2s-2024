# Programación Básica con Python

Este repositorio contiene ejercicios y actividades para aprender **Programación Básica con Python**. Cada clase está organizada en carpetas, y cada carpeta contiene archivos de código en Python y recursos relacionados. También se proporcionan archivos Markdown (`README.md`) para documentar el contenido de cada clase.

## Tabla de Contenidos

- [Programación Básica con Python](#programación-básica-con-python)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Requisitos Previos](#requisitos-previos)
  - [Instrucciones para Clonar y Configurar el Repositorio](#instrucciones-para-clonar-y-configurar-el-repositorio)
    - [Estructura del Proyecto](#estructura-del-proyecto)
  - [Descripción de las Clases y Contenido](#descripción-de-las-clases-y-contenido)
    - [Clase 1: Introducción a Python y Variables](#clase-1-introducción-a-python-y-variables)
- [Clase 1: Variables en Python](#clase-1-variables-en-python)
- [Mostrar información](#mostrar-información)
- [Clase 2: Condicionales en Python](#clase-2-condicionales-en-python)
- [Clase 3: Bucles en Python](#clase-3-bucles-en-python)
- [Clase 4: Funciones en Python](#clase-4-funciones-en-python)
- [Clase 5: Listas en Python](#clase-5-listas-en-python)
- [Clase 6: Manejo de Archivos en Python](#clase-6-manejo-de-archivos-en-python)

## Requisitos Previos

- **Python**: Asegúrate de tener Python 3.6 o superior instalado en tu máquina para ejecutar los archivos `.py`. Puedes descargarlo desde [python.org](https://www.python.org/downloads/).
- **Editor de Código**: Se recomienda usar un editor como [Visual Studio Code](https://code.visualstudio.com/), PyCharm o cualquier editor que soporte Python.
- **Terminal**: Para ejecutar los archivos de Python, necesitarás usar la terminal de tu sistema.

## Instrucciones para Clonar y Configurar el Repositorio

1. Clona el repositorio en tu máquina local con el siguiente comando:
    ```bash
    git clone https://github.com/tu-usuario/programacion-basica-con-python.git
    ```

2. Abre el proyecto en Visual Studio Code o en tu editor preferido:
    ```bash
    cd programacion-basica-con-python
    code .
    ```

3. Para ejecutar un archivo de Python, abre la terminal en Visual Studio Code y ejecuta:
    ```bash
    python clase_X_nombre_del_archivo.py
    ```

### Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

programacion-basica-con-python/ │ ├── clase_01_variables/ │ ├── clase_01_variables.py │ └── README.md │ ├── clase_02_condicionales/ │ ├── clase_02_condicionales.py │ └── README.md │ ├── clase_03_bucles/ │ ├── clase_03_bucles.py │ └── README.md │ ├── clase_04_funciones/ │ ├── clase_04_funciones.py │ └── README.md │ ├── clase_05_listas/ │ ├── clase_05_listas.py │ └── README.md │ ├── clase_06_manejo_archivos/ │ ├── clase_06_manejo_archivos.py │ └── README.md │ └── README.md

markdown
Copiar código

## Descripción de las Clases y Contenido

### Clase 1: Introducción a Python y Variables
- **Contenido**: En esta clase, cubrimos los conceptos básicos de Python, como la creación de variables, operaciones matemáticas y la impresión de resultados.
- **Archivo**: `clase_01_variables.py`
- **Ejecución**: Ejecuta el archivo para ver cómo funciona el código.

**Ejemplo de código**:
```python
# Clase 1: Variables en Python
nombre = "Adiel"
edad = 20

# Mostrar información
print(f"Hola, mi nombre es {nombre} y tengo {edad} años.")
Clase 2: Condicionales en Python
Contenido: En esta clase, aprendemos sobre las estructuras condicionales if, elif y else para tomar decisiones en el código.
Archivo: clase_02_condicionales.py
Ejecución: Ejecuta el archivo para ver cómo funciona el código.
Ejemplo de código:

python
Copiar código
# Clase 2: Condicionales en Python
edad = 20

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
Clase 3: Bucles en Python
Contenido: Aquí se exploran los bucles for y while para ejecutar un conjunto de instrucciones repetidamente.
Archivo: clase_03_bucles.py
Ejecución: Ejecuta el archivo para ver cómo funciona el código.
Ejemplo de código:

python
Copiar código
# Clase 3: Bucles en Python
for i in range(5):
    print(f"Repetición {i+1}")
Clase 4: Funciones en Python
Contenido: Aprenderemos a definir y usar funciones para organizar y reutilizar el código.
Archivo: clase_04_funciones.py
Ejecución: Ejecuta el archivo para ver cómo funciona el código.
Ejemplo de código:

python
Copiar código
# Clase 4: Funciones en Python
def saludar(nombre):
    print(f"Hola, {nombre}!")

saludar("Adiel")
Clase 5: Listas en Python
Contenido: Aquí se aprende a trabajar con listas, cómo agregar, acceder y modificar elementos en ellas.
Archivo: clase_05_listas.py
Ejecución: Ejecuta el archivo para ver cómo funciona el código.
Ejemplo de código:

python
Copiar código
# Clase 5: Listas en Python
frutas = ["manzana", "banana", "cereza"]
frutas.append("naranja")

for fruta in frutas:
    print(fruta)
Clase 6: Manejo de Archivos en Python
Contenido: En esta clase, exploramos cómo leer y escribir archivos desde Python.
Archivo: clase_06_manejo_archivos.py
Ejecución: Ejecuta el archivo para ver cómo funciona el código.
Ejemplo de código:

python
Copiar código
# Clase 6: Manejo de Archivos en Python
with open("saludos.txt", "w") as archivo:
    archivo.write("Hola, mundo!")

with open("saludos.txt", "r") as archivo:
    print(archivo.read())
Ejecución de los Archivos
Cada archivo .py dentro de las carpetas de clase contiene ejemplos de código que puedes ejecutar directamente desde la terminal.

Para ejecutar un archivo de Python:

Navega al directorio de la clase.
Ejecuta el archivo con el siguiente comando:
bash
Copiar código
python nombre_del_archivo.py
Contribuciones y Actualizaciones
Este repositorio será actualizado con nuevas clases y ejercicios conforme avancemos en el curso. Si deseas contribuir o mejorar el repositorio, sigue estos pasos:

Haz un fork del repositorio.
Realiza tus cambios en una nueva rama.
Envía un Pull Request para que los cambios sean revisados.
Recursos de Apoyo
Documentación oficial de Python
Tutoriales gratuitos de Python
Guía de Markdown
¡Espero que este repositorio te sea útil en tu aprendizaje de la programación con Python!