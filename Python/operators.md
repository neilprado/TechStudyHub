# Operadores em Python

Operadores desempenham um papel vital na programação, permitindo a manipulação e interação entre dados. Em Python, existem diversos tipos de operadores que realizam diferentes operações, desde aritméticas simples até operações lógicas e de comparação mais complexas. Neste conteúdo, exploraremos os principais tipos de operadores em Python e como utilizá-los para realizar tarefas diversas.

## Operadores Aritméticos

Os operadores aritméticos são usados para realizar operações matemáticas básicas. Alguns dos operadores aritméticos comuns em Python incluem:

- \+ (adição)
- \- (subtração)
- \* (multiplicação)
- / (divisão)
- // (divisão inteira)
- % (módulo, retorna o resto da divisão)
- \*\* (exponenciação)

Exemplo:

```python
a = 10
b = 3

soma = a + b
subtracao = a - b
multiplicacao = a * b
divisao = a / b
```

### Operadores de atribuição

Os operadores de atribuição são utilizados para atribuir valores a variáveis. O operador mais comum é =.

```python
x = 5
```

Além disso, existem operadores de atribuição combinados, como +=, -=, \*=, que são atalhos para realizar uma operação e atribuir o resultado à variável.

## Operadores de comparação

Esses operadores comparam dois valores e retornam um resultado booleano (True ou False). Alguns exemplos incluem:

- == (igual a)
- != (diferente de)
- < (menor que)
- \> (maior que)
- <= (menor ou igual a)
- \>= (maior ou igual a)

Operadores de comparação tem como retorno operadores booleanos, ou seja, True ou False.

Exemplo:

```python
idade = 20
idade_maior_que_dezoito = idade > 18
```

## Operadores Lógicos

Operadores lógicos são utilizados para combinar expressões lógicas. Os principais são and, or e not.

Exemplo:

```python
tem_idade_e_nome = (idade > 18) and (nome == "Alice")
```

## Operadores de Identidade e Associação

Operadores de identidade (is e is not) são usados para comparar a identidade de objetos, enquanto operadores de associação (in e not in) são utilizados para verificar se um valor está presente em uma sequência.

Exemplo

```python
lista = [1, 2, 3]
esta_na_lista = 2 in lista
```
