# Documentação do Projeto Jogo da Forca

## Introdução
Este projeto consiste em um jogo da forca implementado em HTML, CSS e JavaScript, onde o jogador tenta adivinhar uma palavra oculta escolhida aleatoriamente. O jogador tem um número limitado de tentativas para adivinhar todas as letras da palavra corretamente antes que a imagem de um enforcado seja totalmente desenhada.

## Funcionalidades Principais
### 1. Iniciar o Jogo
- Ao clicar no botão "Jogar", o jogo é iniciado.
- Uma palavra é escolhida aleatoriamente.
- Uma dica para a palavra é exibida.
- As letras do alfabeto são exibidas para que o jogador possa selecionar.

### 2. Tentar uma Letra
- O jogador pode clicar em uma letra para tentar adivinhar se ela está presente na palavra oculta.
- Se a letra estiver correta, ela é exibida na posição correta na palavra.
- Se a letra estiver errada, a imagem do enforcado é atualizada para mostrar o progresso do erro.

### 3. Verificar Vitória ou Derrota
- O jogo verifica se o jogador conseguiu adivinhar todas as letras da palavra corretamente.
- Se o jogador conseguir, uma mensagem de parabéns é exibida e o próximo nível é iniciado.
- Se o jogador falhar em adivinhar a palavra dentro do número máximo de tentativas, uma mensagem de "GAME OVER" é exibida.

### 4. Reiniciar o Jogo
- O jogador pode reiniciar o jogo a qualquer momento clicando no botão "TENTAR OUTRA VEZ".
- Se o jogador ganhar, sua pontuação aumentará. Se perder, a pontuação será reiniciada.

## Link para Jogar
Clique [aqui](https://jntcruz99.github.io/Jogo-Da-Forca/) para jogar o Jogo da Forca.

## Estrutura do Projeto
- **HTML**: Define a estrutura do jogo e os elementos visuais.
- **CSS**: Fornece estilos visuais para os elementos HTML.
- **JavaScript**:
  - **Funções de Controle**: Contém funções para iniciar o jogo, reiniciar o jogo, verificar letras e verificar vitória ou derrota.
  - **palavraRadom.js**: Arquivo externo que contém uma função para gerar uma palavra aleatória e sua dica.

## Requisitos do Projeto
- Navegador da Web compatível com HTML5.
- Conexão com a internet para carregar bibliotecas externas (jQuery e Bootstrap).

## Bibliotecas Externas Utilizadas
- **jQuery**: Utilizado para facilitar a manipulação do DOM e simplificar o código JavaScript.
- **Bootstrap**: Utilizado para aplicar estilos de forma rápida e responsiva aos elementos HTML.

## Considerações Finais
Este projeto é uma implementação simples do jogo da forca utilizando tecnologias web básicas. Pode ser expandido e melhorado adicionando mais recursos, como múltiplos níveis, pontuação detalhada, animações e efeitos sonoros.
