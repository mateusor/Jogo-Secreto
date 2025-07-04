# 🎮 Jogo Secreto – Adivinhe o Número!

Um jogo simples e divertido em Python, onde o jogador precisa descobrir um número secreto de **4 dígitos (entre 1000 e 9999)** em até **10 tentativas**. Desenvolvido como atividade prática de lógica de programação.

---

## 👨‍💻 Desenvolvedores
- Lucas Xavier  
- Mateus Oliveira  
- Wanderley Vieira  
- Arthur Grizone

---

## 🕹️ Como funciona

- A cada tentativa, você recebe dicas sobre quais dígitos estão certos e em suas posições.
- A partir da **5ª tentativa**, o jogo fornece dicas extras:
  - Se o dígito é **maior ou menor que 5**
  - Se o dígito é **par ou ímpar**
- O jogo termina ao acertar o número ou após 10 tentativas.
- É possível jogar novamente ao final.

---

## 🚀 Tecnologias utilizadas

- **Python 3**
- Módulo `random`
- Entrada de dados com `input()`
- Estruturas condicionais e laços de repetição

---

## 📂 Como executar

1. Certifique-se de ter o **Python 3** instalado.
2. Baixe ou clone este repositório.
3. No terminal, execute o jogo com o seguinte comando:

```bash
python JogoLuciaCerto.py

 ===>  BEM-VINDO AO JOGO SECRETO!  <=== 
------------------------------------------------
Objetivo: Descobrir um número secreto de 4 dígitos (entre 1000 e 9999) em até 10 tentativas!
------------------------------------------------

Tentativa 1/10 - Digite um número entre 1000 e 9999: 1234

Dígitos corretos na posição: _ _ 3 _

Você acertou 1 dígito, mas está na posição errada.
