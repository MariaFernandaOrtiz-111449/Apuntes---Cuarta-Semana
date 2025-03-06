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
**Practica en clase 📚**

en clase realizamos un ejercicio simple en simscape multibody, esto para familiarizarnos con el entorno, básicamente hicimos una especie de viga de dimensiona 0.2 , 0.5 y 0.05 metros. Puedes ampliar esta información

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/3a39dd7a5580a01779f72e208a761cef933d0134/Imagen%201.jpg)

![](https://github.com/MariaFernandaOrtiz-111449/Apuntes---Cuarta-Semana/blob/73b0fe50ca3d5afd7309d17f1583038d2bc05c12/Imagen%202.jpg)

## 3. Conclusiones
El uso de Simscape Multibody en la simulación de sistemas mecánicos permite una representación visual y dinámica de estructuras y mecanismos, facilitando su análisis sin necesidad de construir modelos físicos. A través del ejercicio realizado en clase, donde creamos una viga con dimensiones de 0.2, 0.5 y 0.05 metros, pudimos familiarizarnos con la interfaz y herramientas del entorno, comprendiendo cómo definir geometrías, asignar propiedades físicas y visualizar el comportamiento del modelo. Este tipo de simulaciones son fundamentales para el diseño y validación de sistemas mecánicos antes de su implementación real.

## 4. Referencias
MathWorks – Simscape Multibody Documentation, Disponible en: https://www.mathworks.com/help/physmod/sm/index.html
