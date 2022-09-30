# ProjetoDSD

Equipe: André Cristen e Lucas Levi Gonçalves

Detalhamento do projeto e técnicas

O projeto consiste em um jogo de tabuleiro para ensino do conceito de algoritmos na educação básica, a ideia é totalmente baseada em um artigo publicado na Revista Brasileira de Informática na Educação, chamado de “Desenvolvimento e Avaliação de um Jogo de Tabuleiro para Ensinar o Conceito de Algoritmos na Educação Básica” onde o trabalho realmente consistia em desenvolver um jogo de tabuleiro físico, onde tendo essa ideia como base iremos desenvolver uma versão online multijogador com as alterações e personalizações que forem necessárias para o cumprir as exigências das disciplinas de Projeto Integrador III e Desenvolvimento de Sistemas Paralelos e Distribuídos.

Vídeo de demonstração de como jogar a versão original a qual iremos nos basear: 
 https://www.youtube.com/watch?v=LVKKEDUIuNo.


# Requisitos Funcionais


* RF01: O sistema deve manter jogadores
* RF02: O sistema deve manter salas
* RF03: O sistema deve manter partidas
* RF04: O sistema deve manter cartas
* RF05: O sistema deve manter jogadas/movimentos
* RF06: O sistema deve manter tabuleiros/mapas
* RF07: O sistema deve manter entidades do tabuleiro/mapa



# Requisitos Não Funcionais


* RNF01: O sistema deve ter o backend e frontend em projetos separados
* RNF02: O backend deve ser desenvolvido em Python
* RNF03: O frontend deve ser desenvolvido em JavaScript
* RNF04: O sistema deve comportar no mínimo 3 jogadores por sala
* RNF05: O sistema deve comportar no máximo 5 jogadores por sala
* RNF06: O sistema deve apresentar o status dos usuários na sala(online/offline)

# Regras de Negócio


* RN01: O usuário deve realizar o login antes de entrar em uma salA
* RN02: Uma sala deve estar vinculada a uma ou mais partidas
* RN03: Para iniciar uma partida é necessário que ao menos 3 jogadores aceitem o início da mesma
* RN04: Caso durante a partida ocorram de jogadores serem desconectados o sistema deve aguardar 30 segundos antes de remover o jogador da sala automaticamente
* RN05: A partida deve encerrar automaticamente caso restem apenas 2 jogadores online
* RN06: Ao final da partida os jogadores devem ser redirecionados para a mesma sala que iniciou a partida





