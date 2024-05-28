# Desafio Controle Fluxo - DIO-Santander
## Descrição

O projeto `DesafioControleFluxo` é um exercício prático para aplicar os conceitos de controle de fluxo em Java, além de manipulação de exceções personalizadas. O sistema recebe dois números inteiros via terminal e realiza a impressão incremental de números com base na diferença entre esses dois valores. Caso o primeiro número seja maior ou igual ao segundo, uma exceção personalizada é lançada.

## Estrutura do Projeto

O projeto contém duas classes principais:

1. **ParametrosInvalidosException**
2. **Contador**

### Classe `ParametrosInvalidosException`

Esta classe define uma exceção personalizada que é lançada quando o segundo parâmetro é menor ou igual ao primeiro.

### Classe `Contador`

Esta é a classe principal do projeto, contendo a lógica de entrada de dados, validação e contagem incremental.

## Funcionalidades

- Receber dois números inteiros via terminal.
- Validar se o segundo número é maior que o primeiro.
- Lançar uma exceção personalizada (`ParametrosInvalidosException`) se a validação falhar.
- Imprimir números incrementados no console com base na diferença entre os dois números fornecidos.

## Fluxo de Execução

1. O usuário insere dois números inteiros.
2. O programa verifica se o primeiro número é maior ou igual ao segundo.
3. Se a validação falhar, uma exceção personalizada é lançada.
4. Se a validação passar, o programa calcula a diferença entre os dois números e imprime números incrementados no console.

## Como Compilar e Executar

### Pré-requisitos

- Java Development Kit (JDK) instalado
- Um terminal ou prompt de comando
- Um editor de texto ou IDE (por exemplo, Visual Studio Code, IntelliJ IDEA)

Interação com o Programa
O programa solicitará que você insira dois números inteiros.
Se o primeiro número for maior ou igual ao segundo, o programa exibirá a mensagem de erro.
Caso contrário, o programa imprimirá os números incrementados conforme a diferença entre os dois números.

Conclusão
O projeto DesafioControleFluxo demonstra como validar entradas de usuário, lançar exceções personalizadas e iterar sobre um conjunto de números em Java. Ele serve como uma boa base para entender os conceitos de controle de fluxo e manipulação de exceções na linguagem Java.


