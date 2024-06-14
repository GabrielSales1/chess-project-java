# Projeto de Xadrez em Java (CLI)

Bem-vindo ao repositório projeto de Xadrez! Este projeto é uma implementação do jogo de Xadrez usando Java, com uma interface de linha de comando (CLI). Siga os passos abaixo para configurar e executar o projeto em seu ambiente local.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Executando o Jogo](#executando-o-jogo)
- [Como Jogar](#como-jogar)
  
## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado em seu sistema:

- [Java Development Kit (JDK) 8 ou superior](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Git](https://git-scm.com/)

## Instalação

1. Clone o repositório para o seu ambiente local usando o comando abaixo:

    ```bash
    git clone https://github.com/GabrielSales1/chess-project-java.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd chess-project-java
    ```

3. Compile os arquivos Java:

    ```bash
    javac -d bin src/application.java
    ```

## Executando o Jogo

Após compilar os arquivos, você pode iniciar o jogo executando o seguinte comando:

```bash
java -cp bin src/application

```

## Como Jogar
Ao iniciar o jogo, você verá o tabuleiro de xadrez representado na linha de comando. Use as seguintes instruções para jogar:

- Para mover uma peça, insira os comandos no formato e2 e4 onde e2 é a posição inicial da peça e e4 é a posição final.
Siga as regras tradicionais do xadrez para movimentos e capturas de peças.
