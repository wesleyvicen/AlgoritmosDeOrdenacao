## Algoritmos de Ordenação
Este código ajuda você a entender os diferentes algoritmos de classificação. Os algoritmos de ordenação descritos neste código são:

  - Bubble Sort
  - Insertion Sort
  - Selection Sort
  - Merge Sort
  - Quick Sort

### Requisitos de código
O código de exemplo está em Java ([versão 1.8] (https://java.com/en/download/) ou superior funcionará).

### Descrição
Um algoritmo de ordenação é um algoritmo composto de uma série de instruções que toma uma matriz como entrada, realiza operações especificadas na matriz, algumas vezes chamada de lista e gera uma matriz ordenada.
 A classificação eficiente é importante para otimizar o uso de outros algoritmos (como algoritmos de busca e mesclagem) que exigem que os dados de entrada estejam nas listas classificadas; também é frequentemente útil para canonizar dados e para produzir resultados legíveis por humanos. Mais formalmente, a saída deve satisfazer duas condições:

    A saída está em ordem não decrescente.
    A saída é uma permutação (reordenação) da entrada.
	
<img src="https://github.com/wesleyvicen/AlgoritmosDeOrdenacao/blob/master/imgs/sort.gif">


```java

	switch (ch) {
			case 1:
				bubbleSort(a, n);
				break;
			case 2:
				InsertionSort(a, n);
				break;
			case 3: 
				SelectionSort(a, n);
				break;
			case 4:
				MergeSort(a, n);
				print(a, n);

				break;
			case 5:
				int start = 0;
				int end = n - 1;
				QuickSort(a, start, end);
				print(a, n);
				break;
			}
``` 


Você pode selecionar qualquer algoritmo da lista e, em seguida, inserir uma matriz que seria classificada pelo algoritmo selecionado.


### Execução
Para compilar o código, simplesmente execute o `javac principal.java`.
Para executar o código, digite `java principal`

`` `
javac principal.java
java principal
`` `
