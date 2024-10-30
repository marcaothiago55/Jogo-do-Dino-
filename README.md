Projeto do Jogo do Dinossauro em Arduino
Objetivo do Jogo
Desviar de obstáculos e acumular pontos.

Componentes Utilizados

Arduino Uno
Display OLED (SSD1306)
Display de 7 Segmentos (TM1637)
Botão para controle
Estrutura do Código

setup(): Inicializa displays e botão.
loop(): Controla o fluxo do jogo.
Funções Principais

showScore(): Exibe a pontuação.
startStopGame(): Inicia e para o jogo.
moveDino(): Controla movimento do dinossauro.
moveObstacles(): Gerencia obstáculos que aparecem.
checkCollision(): Verifica colisões com obstáculos.
Jogabilidade
Botão inicia o jogo e faz o dinossauro saltar.
Obstáculos se movem; jogador deve evitá-los.
Pontuação aumenta com o tempo.

Lógica de Jogo
Loop contínuo atualiza a tela e verifica entradas.
Lógica de salto muda estado entre chão e ar.

Extensões e Melhorias

Níveis de dificuldade.
Mais tipos de obstáculos.
Sons para feedback ao jogador.
Conclusão
Combina programação e design de jogos,
aprendendo sobre lógica, controle de hardware e interatividade.
Se precisar de ajuda, é só avisar!
