# Python Fundamentals - DIO

Este repositório contém minhas soluções para os desafios do curso **Python Fundamentals** da [DIO](https://www.dio.me).

A proposta é praticar os fundamentos da linguagem Python resolvendo exercícios práticos e organizando o código por módulos.

---

## 📂 Estrutura
- `desafios/`: diretório com os arquivos Python para cada exercício.
- Cada desafio possui um arquivo separado com a respectiva solução.

---

## 🚀 Desafios Resolvidos

### 1. Soma de elementos em uma tupla
**Descrição:**  
Desenvolva uma função em Python que recebe uma tupla de números inteiros e retorna a soma de todos os elementos dessa tupla. A função deve ser capaz de lidar com tuplas de qualquer tamanho, contanto que todos os elementos sejam números inteiros. O objetivo é praticar a manipulação de tuplas e a utilização de funções em Python.

**Explicação de resolução:**  
1. Converta cada string na `lista_strings` em um número inteiro utilizando a função `int()`.  
2. Use a função `map()` para aplicar a função `int()` a cada elemento da `lista_strings`.  
3. Armazene o resultado em uma variável chamada `elementos`.  

---

### 2. Elementos comuns em duas listas
**Descrição:**  
Desenvolva uma função que receba duas listas de números inteiros separados por espaço e retorne uma lista contendo apenas os elementos que são comuns a ambas as listas, sem duplicatas.

**Detalhamento:**  
- Crie a função `elementos_comuns`.  
- Converta cada elemento das listas `lista1` e `lista2` para inteiro usando `map(int, lista)`.  
- Transforme as listas em conjuntos (`set`) e encontre a interseção entre eles.  
- Isso garante que os elementos sejam tratados corretamente como números inteiros e não como strings.  

---

### 3. Contagem de caracteres em uma string
**Descrição:**  
O desafio consiste em adicionar à função `contar_caracteres` um dicionário vazio chamado `contador` para armazenar as contagens de caracteres.  
Itere através de cada caractere na string. Para cada caractere:  
- Se já estiver no dicionário `contador`, incremente o valor associado.  
- Caso contrário, adicione a chave ao dicionário com valor inicial **1**.  

**Entrada:**  
- A função recebe uma única string como entrada (apenas strings textuais).  

**Saída:**  
- Retorna um dicionário onde:  
  - **chaves** → caracteres da string  
  - **valores** → número de ocorrências de cada caractere  

**Documentação Oficial:**  
[Python Docs – Estruturas de Dados (Dicionários)](https://docs.python.org/pt-br/3/tutorial/datastructures.html#dictionaries)

---

## ▶️ Como executar
Clone o repositório e execute qualquer desafio individualmente:

```bash
git clone git@github.com:FerrazVinicius96/python-fundamentals-dio.git
cd python-fundamentals-dio/desafios
python desafio_01.py
