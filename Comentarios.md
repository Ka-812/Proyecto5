---

## Universidad de Costa Rica
### Escuela de Ingeniería Eléctrica
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas

Segundo semestre del 2020

---

* Estudiante: **Katherine Chavarría Nájera**
* Carné: **B41841**
* Grupo: **1**


## `Proyecto 5` - Comentarios de los resultados obtenidos

De acuerdo con los resultados obtenidos en la implementación del código mostrado en el archivo P5.py, para la asignación de la sección 4.2, se observó que gracias al uso de las cadenas de Markov se logra determinar la probabilidad de ocurrencia de múltiples estados para el consumo energético diario del año 2019, éstos resultados se exponen en una **matriz de transición de estados** ![](https://latex.codecogs.com/gif.latex?%5CPi); donde por medio de la división del rango de valores de energía en **N = 10** se estipula la cantidad de estados que se desean estudiar, gererando así una matriz **N x N** que proporciona la probabilidad ![](https://latex.codecogs.com/gif.latex?%5CPi_%7Bij%7D) de transición de cada estado presente *i* a un estado próximo *j*, es decir, se logró obtener una predicción del consumo diario de energía retornando una probabilidad de transición entre cada *i* y *j*. Cabe destacar que cada fila, en dicha matriz, representa cada **estado presente *i***  y cada columna contiene a cada **estado futuro *j***.

Luego, para la asignación de la sección 4.3, a partir de la **matriz de transición de estados** obtenida en la sección anterior y utilizando los valores asignados por la función llamada "parametros_asignados" se construyó la matriz de transición de estados de orden  **𝑡 = 2**; la cuál, genera la probabilidad de estar en el estado  𝑗 ,  𝑡 = 2  días después de estar en el estado 𝑖 para todos los 10 estados de estudio. Sin embargo, a partir de esta matriz de transición de estados de orden  **𝑡 = 2**, específicamente se deseó determinar la probabilidad de estar en el estado  **𝑗 = 6** ,  **𝑡 = 2**  días después de estar en el estado  **𝑖 = 5** adquiriendo de esta forma un valor de 0.057, es decir, se predice una probabilidad del 5,7% de estar en el valor de consumo energético que caracteriza al estado **𝑗 = 6**, **𝑡 = 2** días después de estar en el estado **𝑖 = 5**.     
 
