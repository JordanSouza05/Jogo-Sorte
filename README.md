O **Jogo Sorte** é um jogo de texto desenvolvido em Java onde o usuário controla o destino de um personagem, tomando decisões que dependem da sorte.

## Funcionalidades e Mecânicas

1. **Pontuação Inicial:** O personagem inicia a jornada com 30 pontos. Logo em seguida, o usuário se depara com 7 opções de caminhos/aventuras para escolher.
2. **Sistema de Sorte (50/50):** O código utiliza a classe `Random` para sortear o desfecho de cada escolha. Há 50% de chance do evento ser positivo (ganhar pontos) e 50% de chance de ser negativo (perder pontos).
3. **Atualização em Tempo Real:** Após a escolha do jogador, o sistema processa o evento, exibe o resultado na tela e atualiza a pontuação atual do personagem.
4. **Loop de Jogo:** O usuário é perguntado se pretende continuar jogando:
   * **Sim:** O jogo é reiniciado com todas as informações de pontuação atualizadas dentro de um loop (`do-while`).
   * **Não:** O jogo é encerrado e o terminal exibe o status final com a pontuação acumulada do personagem.

## Tecnologias Utilizadas

* **Java** (Única linguagem)
* **IntelliJ** (IDE utilizada)
* **`java.util.Random`** (Mecânica de sorteio)
* **`java.util.Scanner`** (Leitura de dados no terminal)
