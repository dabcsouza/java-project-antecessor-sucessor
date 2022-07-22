# Requisitos do desafio

## Antecessor e Sucessor


Desenvolva um algoritmo em Java que, após ler um número do console, imprime o seu antecessor e seu sucessor no seguinte formato: `O número X tem Y como seu antecessor e Z como seu sucessor.`. Use como base o código abaixo. 


```java
package com.trybe.acc.java;

import java.util.Scanner;

public class AntecessorSucessor {

	public static void main(String[] args) {
		// Ler a entrada de um número pelo console	
		Scanner scan = new Scanner(System.in);

		System.out.println("Digite um número:");
		int numero = scan.nextInt();
		
		// Seu código aqui
				
		// Imprime a saída no console. OBS: descomente a próxima linha
		//System.out.println("O número " + numero + " tem "+ antecessor + " como seu antecessor e " + sucessor + " como seu sucessor.");

	}

}
```
## Exemplos

### Exemplo 1

Supondo que o número inteiro seja 2, então a saída será:
```
O número 2 tem 1 como seu antecessor e 3 como seu sucessor. 
```

### Exemplo 2

Supondo que o número inteiro seja 34, então a saída será:
```
O número 34 tem 33 como seu antecessor e 35 como seu sucessor. 
```