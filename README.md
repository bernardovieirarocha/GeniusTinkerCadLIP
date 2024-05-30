## Genius Tinkercad Circuit 

**Visão Geral do Projeto:**

Este projeto tem como objetivo desenvolver uma implementação funcional do popular jogo de memória "Genius" usando Tinkercad Circuits para a disciplina de LIP (Laboratório de Introdução à Programação). O jogo conta com quatro LEDs coloridos e quatro botões correspondentes para a interação do usuário. O objetivo é desafiar a memória dos jogadores apresentando uma sequência de cores que deve ser repetida corretamente pressionando os botões correspondentes.

**Dinâmica do Jogo:**

1. **Inicialização:**
   - O jogo começa piscando uma única cor aleatória de um dos quatro LEDs disponíveis, indicando o início da sequência.

2. **Entrada do Jogador:**
   - O jogador deve pressionar o botão correspondente à cor que piscou, recebendo uma resposta auditiva (piezo) do botão pressionado.

3. **Expansão da Sequência:**
   - Após uma entrada bem-sucedida, uma nova cor aleatória é adicionada à sequência e toda a sequência é piscada novamente.

4. **Desafio de Memória:**
   - O jogador deve repetir toda a sequência de cores pressionando os botões correspondentes na ordem correta.

5. **Tratamento de Erros:**
   - Se o jogador cometer um erro em qualquer ponto, todos os LEDs piscarão simultaneamente e será emitido um som de alerta, indicando uma resposta incorreta.
   - Com a falha é preciso reiniciar a simulação para começar a jogar novamente.

6. **Progressão de Dificuldade:**
   - A dificuldade do jogo aumenta a cada rodada bem-sucedida, adicionando mais cores à sequência e testando a capacidade de memória do jogador.

**O Circuito no Tinkercad:**

- O Tinkercad Circuits criado inclui::
  - Quatro LEDs coloridos (vermelho, verde, azul, amarelo)
  - Quatro botões para a entrada do jogador (INPUT_PULLUP MODE)
  - Placa controladora (ex: Arduino Uno)
  - Resistores para a conexão LED
  - Fios de conexão
