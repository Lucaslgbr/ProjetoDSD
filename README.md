# ProjetoDSD

Equipe: André Cristen e Lucas Levi Gonçalves


Desenvolvimento de um jogo de tabuleiro online, com capacidade de três a quatro jogadores, onde irá funcionar inicialmente da seguinte forma:
Todos os jogadores rodam um dado um vez;
O valor do maior ao menor dos resultados dos dados é o que define a ordem de jogada de cada jogador;
Na sua vez de jogar o jogador rola o dado e caminha a quantidade de casas que o dado informar;
Ao decorrer do tabuleiro existem casas que irão dar vantagens ao jogador por exemplo uma carta “while”, uma carta “andar para trás” e uma carta “3 casas” onde o usuário poderá escolher entre usar nele mesmo ou então em um jogador adversário;
A ideia do jogo é estimular o usuário a usar as vantagens recebidas para melhorar sua posição ou prejudicar seus adversários na corrida;
Ao final de cada rodada (definida como rodada após todos os jogadores terem jogado uma vez) inicia-se uma etapa de minigames para definir a nova ordem de jogada.
Na etapa de minigames podemos definir como exemplos de minigames:
* Um quebra cabeça onde temos vários blocos de códigos espalhados e o jogador precisa organizar no menor tempo possível, sendo o ganhador quem organizar os blocos corretamente no menor tempo.
* Um labirinto onde o jogador precisa definir instruções do tipo andar, virar a esquerda, virar à direita, pular sendo o ganhador quem resolver corretamente no menor tempo.
* Uma série de 5 perguntas de múltipla escolha (estilo quiz) onde quem responder no menor tempo e com a maior quantidade de acertos será o ganhador.
* Um jogo da memória onde se associa por exemplo em uma carta existe uma forma de definir uma variável (var x = 0;) e na outra carta a definição de o que essa carta está dizendo (“Forma de se definir uma variável com o valor zero”).
Caça-palavras com termos técnicos onde a cada palavra encontrada apresenta-se uma definição de como fazer, por exemplo “condicional”, ao encontrar a palavra o jogo mostra como fazer um condicional em alguma linguagem de programação.
* Todas os minigames devem dar ao jogador a opção de desistir;
* Cada mini game deve dar ao jogador uma pontuação, pontuação que pode ser usada para comprar as cartas especiais (que também podem ser obtidas em casas específicas do tabuleiro).
* Ao final dos minigames se reinicia a jogada de dados e andar pelas casas
* O jogo acaba com o primeiro jogador chegando ao final do tabuleiro.
* A pontuação final de cada jogador se dá pela sua posição no tabuleiro e pela quantidade de pontos obtidos nos minigames.

As mensagens que serão enviadas irão conter informações dos jogadores: suas posições, pontuação e partida



# Requisitos Funcionais


* RF01: O sistema deve manter jogadores
* RF02: O sistema deve manter tabuleiro
* RF03: O sistema deve manter partida
* RF04: O sistema deve manter minigame

