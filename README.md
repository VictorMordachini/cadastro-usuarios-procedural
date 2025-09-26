# CRUD de Usuários em Console com Java

![Java](https://img.shields.io/badge/Java-23-blue.svg) ![Maven](https://img.shields.io/badge/Maven-4.0.0-red.svg)

Aplicação de console desenvolvida em Java puro para realizar o gerenciamento completo de um cadastro de usuários. O projeto demonstra a manipulação de dados em memória (matrizes) e a persistência de informações em um arquivo de texto local (`bancoDeDados.txt`).

---

## 🚀 Visão Geral das Funcionalidades

* **Cadastro de Usuários:** Permite adicionar um ou mais novos usuários, informando Nome, Telefone e E-mail.
* **Listagem Completa:** Exibe todos os usuários cadastrados em uma tabela formatada no console.
* **Atualização de Dados:** Modifica as informações de um usuário existente a partir do seu ID.
* **Exclusão de Usuários:** Remove o registro de um usuário do sistema, também selecionado pelo ID.
* **Persistência de Dados:** Salva e carrega automaticamente todas as informações em um arquivo `bancoDeDados.txt`, garantindo que os dados não sejam perdidos entre as execuções do programa.

---

## 🛠️ Tecnologias Utilizadas

* **Java 23:** Linguagem principal do projeto, utilizando apenas bibliotecas nativas (`java.io` e `java.util`).
* **Maven:** Utilizado para a estrutura do projeto e gerenciamento do build.

---

## 🏃‍♀️ Como Rodar a Aplicação

1.  **Pré-requisitos:**
    * Java JDK 23 ou superior.
    * Apache Maven.

2.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/cadastro-usuarios-lopal.git](https://github.com/seu-usuario/cadastro-usuarios-lopal.git)
    cd cadastro-usuarios-lopal
    ```

3.  **Execute a aplicação:**
    * Você pode executar a classe `CadastroDeUsuario.java` diretamente pela sua IDE.
    * Ou, para criar um executável `.jar`, utilize o Maven:
        ```bash
        mvn package
        ```
    * Após o build, execute o arquivo JAR gerado na pasta `target`:
        ```bash
        java -jar target/CadastroDeUsuario-1.0-SNAPSHOT.jar
        ```

4.  A aplicação será iniciada no seu console, exibindo o menu de opções. O arquivo `bancoDeDados.txt` será criado automaticamente no diretório do seu usuário.
