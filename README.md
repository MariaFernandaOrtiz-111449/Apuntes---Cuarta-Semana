# Apuntes---Cuarta-Semana
Apuntes control de movimiento primer corte, Cuarta Semana

# SIMSCAPE MULTIBODY
Simscape multibody, es un entorno que permite modelar piezas en 3D y al mismo tiempo hacer ensambles de varias piezas. Entre las muchas funciones que tiene este entorno, es que que aparte de permitirnos visualizar animaciones en 3D, importar sistemas hifraulicos, electricos y neumaticos; permite resolver ecuaciones del movimiento del sistema, es decir permite determinar la cinematica del sistema a partir de matrices en MatLab. Es un entorno bastante sencillo que funciona mediante bloques de componentes. 

## 1. Definir Parametros
Se realizó un ejemplos bastante sencillo en donde se configuraban ciertos parametros y se obtenía un diseño 3D en el entorno de Simscape multibody.
Entre los bloque que se observaron, estaba el bloque de "Mechanism Configuration", en donde podemos configurar la gravedad a la que queremos someter el objeto, esta variable puede llegar a influir en el analisis cinimatico de los objetos.

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/774868dcb56534e6e24e083fe763ef14f4e8c8d0/parametro%201.jpg)

También encontramos las configuraciones del bloque "Revolute Joint", este bloque representa una unión rotativa entre dos cuerpos rígidos, permitiendo que un cuerpo gire en torno a un eje fijo respecto al otro. Este bloque es esencial en la simulación de mecanismos como brazos robóticos, motores, bisagras, y otras aplicaciones que requieren movimiento rotacional.

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/f2e499c4a2ee45e15f2aaabca6f1d700ab0fb910/parametro%202.jpg)

De este bloque, podemos variar parametros como:
* **Degrees of Freedom:** Indica que este bloque permite un grado de libertad (1-DOF) en rotación sobre un eje fijo.
* **Automatically Computed :** Simscape define automáticamente el eje de rotación con base en la geometría.
* **Provided by the User :** Permite especificar manualmente la dirección del eje de rotación.
* **Axis of Rotation:** Define la dirección del eje de rotación en coordenadas (X, Y, Z).

## 2. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/3a39dd7a5580a01779f72e208a761cef933d0134/Imagen%201.jpg)

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/73b0fe50ca3d5afd7309d17f1583038d2bc05c12/Imagen%202.jpg)
## 3. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 4. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
