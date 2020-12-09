---

## Universidad de Costa Rica
### Escuela de Ingeniería Eléctrica
#### IE0405 - Modelos Probabilísticos de Señales y Sistemas

Segundo semestre del 2020

---

* Estudiante: **Katherine Chavarría Nájera**
* Carné: **B41841**
* Grupo: **1**


## `P5` - Comentarios de los resultados obtenidos
> Esta actividad extiende el análisis y modelado realizados anteriormente sobre la demanda eléctrica del país a partir de una base de datos del Instituto Costarricense de Electricidad, del 2019. El estudio se orienta ahora en el uso de las cadenas de Markov para determinar la probabilidad de ocurrencia de múltiples estados para el consumo energético diario.

De acuerdo con los resultados obtenidos, para la asignación de la sección 4.2, se observó que gracias al uso de las cadenas de Markov se logra determinar la probabilidad de ocurrencia de múltiples estados para el consumo energético diario del año 2019, éstos resultados se exponen en una **matriz de transición de estados** ![](https://latex.codecogs.com/gif.latex?%5CPi); donde por medio de la división del rango de valores de energía en **N = 10** se estipula la cantidad de estados que se desean estudiar, gererando así una matriz **N x N** que proporciona la probabilidad ![](https://latex.codecogs.com/gif.latex?%5CPi_%7Bij%7D) de transición de cada estado presente *i* a un estado próximo *j*, es decir, se logra obtener una predicción del consumo diario de energía retornando una probabilidad de transición entre cada *i* y *j*. 

Luego, para la asignación de la sección 4.3, a partir de la **matriz de transición de estados** obtenida en la sección anterior y utilizando los valores asignados por la función llamada "parametros_asignados" se construyó la matriz de transición de estados de orden  **𝑡 = 2**; la cuál, genera la probabilidad de estar en el estado  *𝑗* ,  *𝑡*  días después de estar en el estado  *𝑖* para todos los 10 estados presentes. Además, específicamente se determinó la probabilidad de estar en el estado  **𝑗 = 6** ,  **𝑡 = 2**  días después de estar en el estado  **𝑖 = 5**.  
 
