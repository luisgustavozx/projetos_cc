# Jogo de Adivinhação Guess the Number XTREME

## 💡 Sobre o projeto
Esse circuito é referente ao projeto proposto na cadeira de Circuitos Digitais da UFCA e foi construído no Logisim. O mesmo trata-se de um jogo de adivinhação para dois jogadores, onde um ponto no espaço é sorteado aleatoriamente através de duas coordenadas X e Y, cada uma sendo um número de 4 bits, e os jogadores devem tentar descobrir quais são essas coordenadas.

## 🎲 Como jogar
1 - Dois números de 4 bits são sorteados aleatoriamente, representando as coordenadas X e Y de um ponto oculto.  
2 - O jogador da vez escolhe um número de 4 bits para sua coordenada X e confirma o palpite.  
3 - Em seguida, escolhe um número de 4 bits para sua coordenada Y e confirma o palpite.  
4 - O jogo informa se as coordenadas X e Y foram acertadas e se a soma das coordenadas do palpite é igual à soma das coordenadas do ponto oculto.  
5 - Um led RGB indica a proximidade entre a soma das coordenadas chutadas e a soma das coordenadas reais. Quanto mais próximo, mais vermelho o led ficará, e quanto mais distante, mais azul.  
6 - Caso o jogador acerte simultaneamente as coordenadas X e Y, ele ganha um ponto.  
7 - Após finalizar seu palpite, o turno passa para o próximo jogador e seu cronômetro começa a contar.  
8 - O jogo termina quando um dos jogadores alcança 15 pontos ou quando os dois cronômetros chegam ao fim.  
9 - Ao final, o circuito indica se o jogador A venceu, se o jogador B venceu ou se houve empate. 

## ⚙️ Funcionalidades
* Geração aleatória das coordenadas X e Y.
* Sistema de dois jogadores.
* Sistema de confirmação dos palpites.
* Verificação das coordenadas X e Y.
* Verificação da soma das coordenadas.
* Led RGB indicador de proximidade.
* Cronômetro individual para cada jogador.
* Sistema de alternância de turnos.
* Sistema de pontuação.
* Indicação do jogador da vez.
* Sistema de fim de jogo.
* Indicação de vitória ou empate.
* Sistema de reset do jogo.
