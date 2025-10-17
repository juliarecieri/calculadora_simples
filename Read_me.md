# Calculadora simples
Projeto criado para a conclusão do primeiro módulo de Phyton do curso de Ciência de Dados da EBAC.

# 🧮 Projeto: Calculadora simples e interativa em Python

Este é um projeto simples, mas robusto, de uma calculadora de linha de comando desenvolvida em Python. O objetivo principal foi criar uma ferramenta que se repete continuamente (loop), valida as entradas do usuário e lida com possíveis erros, como a divisão por zero e entradas não numéricas.

Além disso, o enunciado do exercício também exigia a conversão das entradas do usuário e a inclusão de pelo menos quatro operações matemáticas.

## 🚀 Funcionalidades

* **Operações fundamentais:** Realiza adição, subtração, multiplicação e divisão.
* **Loop contínuo:** Permite que o usuário realize múltiplos cálculos sem reiniciar o programa.
* **Menu de opções:** Apresenta as operações em formato de lista numérica para facilitar a escolha.
* **Tratamento de erros:** Captura e gerencia erros de entrada (não-números) e lida com a divisão por zero de forma segura.
* **Saída simples:** Oferece uma maneira clara de encerrar o programa.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.x

## ✨ O que aprendi neste projeto

Este projeto foi fundamental para consolidar conceitos essenciais da Lógica de Programação e da sintaxe Python, incluindo:

| Conceito | Descrição e Aplicação |
| :--- | :--- |
| **Estruturas de Repetição (`while`)** | Implementação do loop principal (`while True`) para manter a calculadora em funcionamento contínuo, reiniciando o processo após cada cálculo. |
| **Tratamento de exceções (`try...except`)** | Uso do bloco `try...except` para tornar o programa mais robusto, capturando erros como `ValueError` (quando o usuário digita texto onde se esperava um número) e impedindo o encerramento abrupto. |
| **Estruturas condicionais (`if/elif/else`)** | Utilização de condições aninhadas para realizar a operação correta com base na escolha do usuário e para validar a divisão por zero de forma segura. |
| **Listas e enumeração (`enumerate`)** | Definição de uma lista de operações e uso do `enumerate` para exibir as opções em um formato numerado, facilitando a interação do usuário. |
| **Manipulação de string (`.lower()` e f-strings)** | Uso do `.lower()` para padronizar as entradas de texto (ex: `sair`) e utilização de f-strings (`f"Olá, {name}"`) para formatação clara e concisa da saída. |
| **Variáveis de controle (`None` e `break`)** | Uso do `resultado = None` para inicializar a variável e servir como uma "flag" (bandeira), garantindo que o resultado só seja impresso se o cálculo foi bem-sucedido. |
| **Indentation (Indentação)** | Reforço da importância da indentação de 4 espaços em Python para definir corretamente os blocos de código (`while`, `try`, `if`, `for`, etc.) e evitar erros de sintaxe. |

---

## 💻 Como executar

1.  **Pré-requisitos:** Certifique-se de ter o Python 3 instalado em sua máquina.
2.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
    cd NOME_DO_REPOSITORIO
    ```
3.  **Execute o script:**
    ```bash
    python nome_do_arquivo.py
    ```

Siga as instruções na tela para realizar os cálculos ou digite `sair` a qualquer momento para fechar a calculadora.
