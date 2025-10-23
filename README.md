# ♟️ Java Chess System

Projeto desenvolvido durante o curso de **Java** do professor **Nélio Alves** na plataforma **Udemy**.  
O objetivo é construir um jogo de xadrez funcional para ser executado no terminal, aplicando de forma prática os conceitos de **Programação Orientada a Objetos (POO)** e a **estruturação de software em camadas**.

---

## 📌 Objetivos do Projeto

* Aplicar conceitos de POO: **Encapsulamento**, **Herança**, **Polimorfismo** e **Classes Abstratas**.  
* Implementar um sistema de xadrez com as regras fundamentais do jogo.  
* Estruturar o projeto em camadas lógicas:  
  * `boardgame` – lógica do tabuleiro  
  * `chess` – regras do xadrez  
  * `application` – interface com o usuário  
* Representar o tabuleiro utilizando matrizes.  
* Implementar tratamento de exceções personalizadas.  
* Criar uma interface de usuário no terminal com exibição colorida das peças.

---

## 🛠 Tecnologias Utilizadas

* **Java**  
* **Git / GitHub**  
* **Git Bash** (recomendado no Windows para exibição correta das cores no terminal)

---

## ✨ Funcionalidades e Conceitos Implementados

* **Representação do Tabuleiro:**  
  Uso de matriz bidimensional e classes `Position` e `ChessPosition` para gerenciamento de coordenadas.  

* **Camadas:**  
  Separação clara entre lógica do tabuleiro (`boardgame`), regras do jogo (`chess`) e interface (`application`).  

* **Peças:**  
  * Classe abstrata `Piece` e classe `ChessPiece`.  
  * Implementação das peças (`King`, `Rook`, `Pawn`, `Bishop`, `Knight`, `Queen`) utilizando **herança** e **polimorfismo**.  

* **Movimentação:**  
  * Cálculo de movimentos possíveis para cada peça (`possibleMoves`).  
  * Validação de origem e destino de movimentos.  
  * Lógica de captura de peças.  

* **Regras do Jogo:**  
  * Alternância de turnos entre jogadores.  
  * Lógica de **Check** e **Checkmate**.  
  * Contagem de movimentos por peça.  
  * Movimentos especiais: **Roque (Castling)**, **En Passant** e **Promoção do Peão**.  

* **Interface do Usuário (Terminal):**  
  * Impressão visual do tabuleiro no console.  
  * Cores diferentes para cada jogador.  
  * Indicação de movimentos possíveis.  
  * Exibição de peças capturadas.  
  * Leitura de coordenadas no formato de xadrez (ex: `a1`, `h8`).  

* **Tratamento de Exceções:**  
  Criação de exceções personalizadas (`BoardException`, `ChessException`) para lidar com erros de forma controlada.

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/heitorhidalgo/chess-system-java.git
   cd chess-system-java


---

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/heitorhidalgo/chess-system-java.git](https://github.com/heitorhidalgo/chess-system-java.git)
    cd chess-system-java
    ```

2.  **Pré-requisitos:**
    * Java JDK instalado e configurado.
    * (Recomendado no Windows) **Git Bash** para melhor visualização das cores no terminal.

3.  **Compile e Execute pela IDE (Ex: Eclipse/STS):**
    * Importe o projeto como um projeto Java existente.
    * Encontre a classe `Program.java` no pacote `application`.
    * Clique com o botão direito sobre ela e selecione `Run As > Java Application`.

4.  **Compile e Execute via Terminal (Opcional):**
    * Navegue até a pasta `bin` dentro do projeto (onde os arquivos `.class` são gerados pela sua IDE).
    * Execute o comando:
        ```bash
        java application/Program
        ```
    * *Observação: A compilação prévia pela IDE é necessária para este método.*

5.  **Jogando:**
    * O tabuleiro será exibido no terminal.
    * Siga as instruções para inserir a posição da peça de origem e a posição de destino (ex: `e2`, `e4`).

---

## 👤 Autor

**Heitor Hidalgo**
* **GitHub:** [heitorhidalgo](https://github.com/heitorhidalgo)
* **LinkedIn:** [Heitor Hidalgo](https://www.linkedin.com/in/heitorhidalgo)
---

## 🙏 Agradecimentos

* Gostaria de agradecer ao professor **Nélio Alves** pela excelente didática no curso.
* **Link do curso na Udemy:** [Curso Nélio](https://www.udemy.com/course/java-curso-completo)

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
