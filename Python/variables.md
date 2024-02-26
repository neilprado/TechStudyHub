# Variáveis

As variáveis desempenham um papel fundamental em qualquer linguagem de programação, e Python não é exceção. Elas são essenciais para armazenar e manipular dados durante a execução de um programa. Neste conteúdo, vamos explorar o conceito de variáveis em Python, entender como declará-las, atribuir valores e explorar os diferentes tipos de dados que podem ser armazenados.

## O que são variáveis em Python

Em Python, uma variável é um nome que se refere a um valor específico. Elas são utilizadas para armazenar dados que podem ser modificados ao longo do tempo. Ao contrário de algumas linguagens de programação, em Python, não é necessário declarar explicitamente o tipo de uma variável. O interpretador Python faz essa inferência automaticamente.

Para declarar uma variável em Python, basta atribuir um valor a um nome. Conforme esse exemplo simples abaixo:

```python
nome = "Python"
idade = 30
```

É possível que variáveis recebam valores de duas formas diferentes, por atribuição e por entrada de dados (digitando no teclado)

### Atribuições

Pode-se atribuir um valor a uma variável de forma arbitrária. Em Python uma atribuição se dá pelo operador **=** e deve ser feito assim:

```python
# variavel = expressão
idade = 35
```

### Buscando dados via terminal

Para atribuir valores às variáveis via terminal, é usada a função _input()_, o programa será pausado e ficará no aguardo da digitação de um valor. Como por exemplo:

```python
nome = input('Digite o seu nome: ')
```

É necessário entender que o retorno da função input() é um **string**, ou seja, qualquer entrada via teclado, será tratada como texto, independente de ser tratado no programa como texto ou não, para tal, o Python tem funções conversoras. Um exemplo se fará necessário sobre a forma que a função input funciona.

```python
n1 = input('Digite o primeiro número: ') # 1
n2 = input('Digite o segundo número: ') # 1
print(n1 + n2)

# Saída do programa: 11

n1 = int(input('Digite o primeiro número: ')) # 1
n2 = int(input('Digite o segundo número: ')) # 1
print(n1 + n2)

# Saída do programa: 2
```

## Exercícios

Antes da seção de exercícios, é preciso que seja entendido quais são e para que servem os operadores. Para tal, acesse a seção operadores.

Supondo que agora que sabe para que serve e como utilizar os operadores, realize os exercícios 1001 a 1012, do beecrowd, lembrando que é por ordem de dificuldade.
