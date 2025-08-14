# Bytebank 🏦

Este é um projeto de simulação de um sistema bancário simples, desenvolvido como parte dos estudos de Java e Programação Orientada a Objetos. A ideia é aplicar conceitos fundamentais da linguagem para criar uma estrutura funcional de contas, clientes e operações bancárias.

## 📜 Descrição do Projeto

O Bytebank permite a criação de contas bancárias, associando-as a clientes. Cada conta possui funcionalidades básicas como depósito, saque e transferência de valores entre contas, com validações simples para garantir a consistência dos dados.

## ✨ Funcionalidades

-   **Criação de Contas**: Permite a criação de novas contas, registrando agência e número.
-   **Gestão de Clientes**: Associa um objeto do tipo `Client` a uma `Account`, armazenando dados como nome, CPF e profissão.
-   **Operações Bancárias**:
    -   `depositar()`: Adiciona um valor ao saldo da conta.
    -   `sacar()`: Retira um valor do saldo, verificando se há fundos suficientes.
    -   `transferir()`: Transfere um valor de uma conta para outra.
-   **Controle de Contas**: O sistema monitora o número total de contas criadas.

## 🛠️ Tecnologias Utilizadas

-   **Java**

## 🚀 Como Executar o Projeto

Para testar a aplicação, você pode compilar os arquivos `.java` e executar as classes de teste que demonstram as funcionalidades do sistema.

**Pré-requisitos:**
* É necessário ter o **JDK (Java Development Kit)** instalado na sua máquina.

**Passos:**

1.  Faça o download ou clone o repositório em sua máquina.
2.  Abra um terminal e navegue até a pasta raiz do projeto.
3.  Compile os arquivos-fonte `.java` com o seguinte comando:
    ```bash
    javac *.java
    ```
4.  Execute as classes de teste para ver o sistema em ação:
    ```bash
    # Para testar a criação de contas e o totalizador
    java ValuesTest

    # Para testar os getters e setters de Cliente e Conta
    java GetSetTest
    ```