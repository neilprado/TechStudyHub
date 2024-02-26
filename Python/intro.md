# Introdução ao Python

Python é uma linguagem extremamente poderosa e simples de ser aprendida de alto nível e multiparadigmas. É uma linguagem de tipagem dinâmica, elegante e de um escopo léxico distinto.

A sintaxe básica do Python é bastante simples, existem inúmeras bibliotecas de suporte às aplicações e diversas estruturas de dados contidas na sintaxe como _tuplas_, _listas_ e _dicionários_.

Por ser bastante simples e com muitas bibliotecas à disposição, Python é uma das primeiras linguagens a ser aprendidas por alunos de programação atualmente.

Apesar de ser uma linguagem interpretada, existe todo um processo de compilação que é transparente para o programador, mas que pode ser explicada com a transformação do código texto (a partir do .py) em _bytecode_ que, por sua vez, é interpretado por uma máquina virtual, do inglês _virtual machine_ ou VM.

![Processo de compilação em Python](img/python01.png)

Como todas as linguagens, o Python também tem convenções acerca do estilo de código a ser escrito, a comunidade definiu o PEP-8 como um guia de estilos com os seguintes destaques:

- Use 4 espaços para indentação
- Não misture Tabs e espaços
- Tamanho máximo da linha é 79 caracteres
- As variáveis de nome composto devem ser separadas por underscore, o padrão SnakeCase (\_). Ex: nome_usuario
- As classes devem adotar o padrão CamelCase em sua nomenclatura. Ex: AnimalDomestico

## Preparando o ambiente

É preciso configurar o ambiente para programar em Python, para tal é preciso:

- Realizar o download do Python 3 e sua instalação em [https://www.python.org/downloads/]
- Realizar o download e a instalação do PyCharm em [https://www.jetbrains.com/pycharm/download/]

De forma opcional, porém altamente recomendado, será usada a plataforma beecrowd para realização de atividades com o intuito de fixar o aprendizado.

- Acesse [beecrowd](https://judge.beecrowd.com/pt/login?redirect=%2Fpt)
  - Realize o cadastro com e-mail, senha e a confirmação de senha

## Já preparei o ambiente e agora?

Abra o PyCharm e só para fins de teste exiba a mensagem _Hello World_ no console e digite a seguinte instrução:

```python
print('Hello World!')
```

A título de explicação, _print_ é uma função que exibe na saída padrão (tela do monitor) uma ou mais instruções passadas entre os parênteses.

## Tipos de dados

Em Python, existem alguns tipos de dados, os tipos de dados básicos são:

- Inteiros (int): `x = 10`
- Números de ponto flutuante (float): `y = 3.14`
- Strings: `text = 'Olá!!'`
- Booleanos (boolean): `condition = True`
- Nulos (None): `vazio = None`

## Exercícios

Realize o login na plataforma [beecrowd](https://judge.beecrowd.com/pt/login?redirect=%2Fpt) e resolva a questão [Olá Mundo](https://judge.beecrowd.com/pt/problems/view/1000)

Por hoje é só, dúvidas, sugestões e feedbacks, faça-o pessoalmente :p
