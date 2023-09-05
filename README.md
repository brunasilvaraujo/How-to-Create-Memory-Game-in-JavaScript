# Memory-Game

Um jogo da memória (Memory Game) que utiliza emojis como cartas. O objetivo do jogo é encontrar todos os pares de emojis correspondentes no tabuleiro, virando as cartas e combinando-as.

<img src="Captura de tela 2023-07-31 190918.png" alt="Foto do projeto"/>

## 🛠 Tecnologias utilizadas
- HTML
- CSS
- JavaScript

## Funcionalidades do Códgio

- Estrutura do Jogo: O código define a estrutura básica do jogo em HTML, incluindo um título, um tabuleiro de jogo e um botão de reinicialização.

- Emojis e Embaralhamento: Ele cria um conjunto de emojis em pares e os embaralha aleatoriamente, garantindo que cada jogo seja diferente.

- Criação do Tabuleiro: Utiliza um loop para criar cartas (elementos 'div') no tabuleiro do jogo, cada uma exibindo um emoji embaralhado.

- Lógica do Jogo: Quando um jogador clica em uma carta, ela é revelada. O código verifica se duas cartas abertas são iguais. Se forem, elas permanecem abertas (cartas combinadas), caso contrário, são fechadas novamente.

- Verificação de Vitória: O código verifica constantemente se todas as cartas foram combinadas. Quando isso acontece, uma mensagem de vitória é exibida.

- Reiniciar o Jogo: O botão "Reset Game" permite ao jogador recomeçar o jogo, recarregando a página.
