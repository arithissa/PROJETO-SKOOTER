# PROJETO-SKOOTER
Versão do jogo Skooter desenvolvido em linguagem orientada a objetos Java por Aríthissa Vitória e João Pedro de Andrade

# 1. Plataforma de Desenvolvimento
NetBeans IDE 8.2.

# 2. Sobre o funcionamento do jogo
A dinâmica do jogo é semelhante às 4 primeiras fases do jogo Skooter original, que tem por objetivo resolver os puzzles propostos, coletando itens e desviando dos inimigos pelo caminho. O jogo é ganho quando o jogador passa por todas as fases implementadas.

2.1. Controles
Seta para cima: movimenta o herói para cima (se possível).
Seta para baixo: movimenta o herói para baixo (se possível).
Seta para a direita: movimenta o herói para a direita (se possível).
Seta para a esquerda: movimenta o herói para a esquerda (se possível).
Barra de espaço: explode um bloco verde diante do herói.
F: desiste do jogo, game over automático.

2.2. Observações

2.2.1. Apenas os blocos verdes, independentemente do desenho, podem ser
“explodidos” pelo herói.

2.2.2. Apenas os blocos de “tijolo”, independentemente da cor, podem ser
movimentados pelo herói.

2.2.3. Assim como no jogo original, é explodido o bloco cuja direção em relação
ao herói corresponde à última seta apertada. Ou seja: se a última seta apertada
foi a seta para cima, o bloco explodido será o que está na célula acima do herói.

2.2.4. Se o jogador empurrar um bloco vermelho móvel em cima de um cogumelo
de forma que seja impossível tirá-lo dali, o jogador deverá apertar F e ir para a
tela de game over.

2.2.5. Tanto na tela de vitória quanto na tela de game over, basta pegar o
cogumelo para jogar novamente.

2.2.6. Diferentemente do Skooter original, os monstrinhos se movimentam
aleatoriamente pelo mapa, adicionando um fator de imprevisibilidade que altera
ligeiramente a dinâmica do jogo.
