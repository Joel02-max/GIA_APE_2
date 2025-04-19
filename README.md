# APE_2 - Matrices Aleatorias y Operaciones

Este proyecto consiste en una aplicación de escritorio en Windows Forms en C# que permite generar matrices aleatorias de tamaño variable, realizar operaciones matemáticas entre matrices, y mostrar los resultados en una interfaz gráfica. Las operaciones realizadas incluyen suma, resta, multiplicación y división. Además, la aplicación permite mostrar la matriz traspuesta de los resultados obtenidos.

## Descripción

La aplicación genera dos matrices de tamaño aleatorio, realiza operaciones entre ellas y luego muestra los resultados de las operaciones en una tercera matriz. Las operaciones realizadas son:

- **Suma**: Suma de las matrices.
- **Resta**: Resta de las matrices.
- **Multiplicación**: Multiplicación de las matrices.
- **División**: División de las matrices (se maneja el caso de división por cero).
- **Matriz Traspuesta**: Generación de la matriz traspuesta de los resultados obtenidos.

Además, el usuario puede generar nuevas matrices aleatorias y realizar nuevamente las operaciones con el botón de "Generar".

## Funcionalidades

- **Generación de matrices aleatorias**: Se generan matrices de tamaño aleatorio entre 2 y 5 filas y columnas.
- **Operaciones matemáticas**: Suma, resta, multiplicación y división entre las matrices generadas.
- **Visualización de resultados**: Los resultados de las operaciones son mostrados en una matriz de resultados.
- **Matriz traspuesta**: La aplicación muestra la matriz traspuesta de los resultados obtenidos.
- **Interfaz de usuario**: La interfaz es sencilla y está compuesta por varios `DataGridView` para mostrar las matrices y los resultados.

## Requisitos

- Visual Studio 2019 o superior.
- .NET Framework 4.7.2 o superior.
  
## Ejecución
1. Clona el repositorio en tu máquina local:
2. Abre el proyecto en Visual Studio.
3. Compila y ejecuta la aplicación.

## Estructura del Proyecto
- Form1.cs: Contiene la interfaz principal y la lógica para generar las matrices y realizar las operaciones.
- MRandomica.cs: Lógica que permite realizar las operaciones de matrices aleatorias, así como la generación de la matriz traspuesta.
- Inicio.cs: Formulario para retornar a la pantalla principal de la aplicación.
