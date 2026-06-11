# Interpretador de Linguagem Simples em Python

Este projeto implementa um **interpretador de linguagem simplificada**, construído em Python, com suporte a análise léxica, interpretação de código e execução de estruturas básicas como variáveis, expressões e condicionais.

---

## 🚀 Visão geral

O sistema funciona como uma mini-linguagem própria, contendo:

- Análise léxica (Lexer com Regex)
- Interpretador manual (Parser + Executor)
- Variáveis dinâmicas
- Operações matemáticas
- Operadores lógicos
- Estruturas condicionais (`if / else`)
- Bloco principal (`main { }`)

---

## 🧠 Como o projeto funciona

### 🔤 Lexer
O código é convertido em tokens usando expressões regulares, identificando:

- Números
- Identificadores
- Palavras-chave (`var`, `if`, `else`, `main`)
- Operadores (`+ - * / == != >= <=`)
- Símbolos (`{ } ( ) ; :`)

---

### 🧩 Interpretador
Após a tokenização, o interpretador:

- Executa comandos sequencialmente
- Gerencia variáveis em memória (`self.vars`)
- Avalia expressões matemáticas e lógicas
- Controla fluxo de execução (`if/else`, blocos)

---

## 🖼️ Ilustração 
<img width="1439" height="1019" alt="1000312958" src="https://github.com/user-attachments/assets/bf77ad75-1c01-46ba-82c3-91cec6df2c6b" />

---

## 📌 Exemplo de código suportado

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


