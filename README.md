# Algoritmos-de-ordenamiento

La idea principal de un algoritmo de ordenamiento es que dado un arreglo o un conjunto de elementos, ordenarlos de menor a mayor, osea por ejemplo pasar de un arreglo  ```[5, 2, 3, 1, 4]```, ordenarlo de manera que quede como  ```[1, 2, 3, 4, 5]```.

Para realizar esto existen distintos algoritmos de ordenamiento que varian en la forma en que se va iterando para ordenar los datos y su complejidad, ya que algunos algoritmos son mas eficientes que otros.

## Clasificacion por eficiencia 

| Algoritmo | Complejidad |
| :--- | :---: | 
| Bubble Sort | O(n²) | 
| Selection Sort | O(n²)| 
| Insertion Sort | O(n²)|
| Merge Sort | O(nlog(n)) |
| Quick Sort | O(nlog(n)) |
| Heap Sort | O(nlog(n)) |

Vamos a analizar cada algoritmo de menos a mas eficiente.

 ## Bubble Sort

Se le llama burbuja ya que sus elemntos "burbujean" hasta el final, es el algoritmo menos eficiente de todos, el cual se utiliza actualmente mas que todo como ejercicio de aprendizaje y practica, su funcionamiento dado una lista desordenada se puede dividir en 4 etapas:
 1. Se compara el primer elemento con el segundo elemento, si el primer elemento es mayor al segundo se intercambian.
 2. Se avanza al siguiente par de elementos y se repite el proceso de comparacion e intercambio.
 3. El proceso se repite hasta llegar al final de la lista, una vez completado se puede afirmar que el ultimo elemento es el mas grande de la lista.
 4. Se repiten los pasos de la primera a tercera etapa, sin embargo, esta vez se ignora la ultima posicion ya que el elemnto mas grande ya se encuentra en la posicion final.

Ejemplo grafico:


### Implementacion:
sa

