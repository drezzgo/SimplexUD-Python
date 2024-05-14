# SimplexUD
## Método Gráfico & Simplex con Python

Esta aplicación es una herramienta para resolver problemas de programación lineal, ofreciendo a los usuarios la capacidad de elegir entre métodos gráficos y Simplex. Está diseñada para ser intuitiva y fácil de usar, tanto para estudiantes como para profesionales.

## Características

- **Métodos disponibles:** Gráfico y Simplex.
- **Validación de datos de entrada.**
- **Ajuste automático** de parámetros según el método seleccionado.
- **Interfaz amigable** e intuitiva.

## Instalación

Para usar el aplicativo debes tener alguna versión de Python (se recomienda la 3.12).

1. **Clona el repositorio:**
    ```sh
    git clone https://github.com/drezzgo/SimplexUDgit
    ```

2. **Crea un entorno virtual de Python:**
    ```sh
    python -m venv venv
    ```

3. **Activa el entorno virtual (para Windows):**
    ```sh
    .\venv\Scripts\activate
    ```

4. **Instala las dependencias:**
    ```sh
    pip install reflex
    ```

## Dependencias

- **Numpy:** Se utiliza para realizar operaciones matemáticas con matrices y vectores de manera eficiente.
- **Itertools:** Se utiliza para generar secuencias de elementos de manera eficiente.
- **Linprog:** Es un módulo de optimización de SciPy que se utiliza para resolver problemas de optimización lineal de manera eficiente.
- **Pulp:** Se utiliza para resolver problemas de optimización lineal, entera y mixta.
- **Pyinstaller:** Se utiliza para empaquetar y crear un ejecutable .exe del proyecto (Por si necesitas entregarlo a un usuario solo desee usar el proyecto).

Dentro del archivo de librerías encontrarás un import que importa "funciones"; este hace referencia al archivo funciones.py.
