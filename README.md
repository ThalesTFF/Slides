# Slides
Cada commit representa um tipo de slide diferente , cada um mais avançado que o outro

V2 slider com timer e reposionamento dinamico

    Um slider simples de movimento automatico baseado em um timer que 
    ao passar certo tempo, move o slider para a esquerda
    com base na largura do slide atual

    Após reposicionar o primeiro slide para o fim do slider-track
    realiza uma sequencia de ações para reorganização do DOM e reset de margem


    track.style.transition = 'none';              // Desativa animação
    track.style.marginLeft = '0px';               // Volta pra posição inicial
    void track.offsetWidth;                       // Força reflow
    track.style.transition = 'all linear 0.5s';   // Reativa animação

    ✔️ Essa sequência está correta e evita qualquer glitch visual.


