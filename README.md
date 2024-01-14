# basico.py
Python é uma linguagem de programação de alto nível, de propósito geral, conhecida por sua sintaxe clara e legível. Aqui estão alguns fundamentos importantes do Python:

Variáveis e Tipos de Dados:
As variáveis em Python são declaradas sem a necessidade de especificar o tipo. Exemplo: x = 10.
Tipos de dados comuns incluem inteiros (int), números de ponto flutuante (float), strings (str), listas (list), tuplas (tuple), dicionários (dict), entre outros.

# Exemplo de variáveis e tipos de dados
nome = "João"
idade = 25
altura = 1.75
lista_numeros = [1,2,3,4,5,]

Estruturas de Controle:
Python utiliza indentação para definir blocos de código. Não há chaves como em algumas outras linguagens.
Estruturas de controle incluem if, else, elif, for e while.


# Exemplo de estrutura de controle
idade = 18

if idade >= 18:
    print("É maior de idade")
else:
    print("É menor de idade")

Funções:
Funções são definidas usando a palavra-chave def.
Argumentos podem ser passados para funções.

# Exemplo de função
def saudacao(nome):
    print("Olá, " + nome + "!")

saudacao("Maria")

Listas e Tuplas:
Listas são mutáveis, enquanto tuplas são imutáveis.
Listas são definidas com colchetes [] e tuplas com parênteses ().

# Exemplo de lista e tupla
lista_frutas = ["maçã", "banana", "laranja"]
tupla_cores = ("vermelho", "verde", "azul")

Dicionários:
Dicionários armazenam dados no formato chave-valor.
São definidos usando chaves {}.

Loops:
O loop for é comumente usado para iterar sobre sequências (como listas ou strings).
O loop while é usado quando a condição é verdadeira.

# Exemplo de loop
for numero in range(1, 4):
    print(numero)

Tratamento de Exceções:
Erros são tratados usando blocos try, except.

# Exemplo de tratamento de exceção
try:
    resultado = 10 / 0
except ZeroDivisionError:
    print("Não é possível dividir por zero.")

Módulos e Bibliotecas:
Python tem uma ampla variedade de módulos e bibliotecas que podem ser importados para estender suas funcionalidades.

# Exemplo de importação de módulo
import math
print(math.sqrt(25))  # Raiz quadrada de 25


Esses são apenas alguns conceitos básicos do Python
