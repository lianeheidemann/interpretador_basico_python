## 🧠 Mini Interpretador de Linguagem em Python

<p align="center">
  <img src="https://img.shields.io/badge/Projeto-Interpretador%20de%20Linguagem-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge"/>
</p>

---

## 📌 Sobre o Projeto

Este projeto consiste na construção de um **mini interpretador de linguagem de programação**, desenvolvido em Python, com foco em:

- Análise léxica (Lexer)
- Parsing básico
- Interpretação de código
- Execução de expressões e controle de fluxo

A linguagem criada suporta variáveis, operações matemáticas, operadores lógicos e estruturas condicionais.

---

## ⚙️ Funcionalidades

✔️ Declaração de variáveis (`var`)  
✔️ Tipos básicos (`int`, `float`, `bool`)  
✔️ Operações matemáticas (`+ - * /`)  
✔️ Operadores lógicos (`and`, `or`, `not`)  
✔️ Comparações (`== != > < >= <=`)  
✔️ Estruturas condicionais (`if / else`)  
✔️ Blocos de código `{ }`  
✔️ Execução sequencial de instruções  
✔️ Modo DEBUG para análise da execução  

---

## 🧪 Exemplo de Código

```txt
var x:int = 10;
var y:int = 5;
var z:int = 0;

main {
    x = x + 3;
    y = y * 2;

    if x > 10 {
        z = 1;
    } else {
        z = 2;
    }

    if y < 5 or z == 1 {
        x = x + 1;
    }
}
