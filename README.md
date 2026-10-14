# Subúrbio Morto

Jogo de sobrevivência com zombies em 3D, feito numa única página HTML (Three.js). Explora edifícios, repara o rádio e o gerador com um minijogo de fiação, fabrica armas e defesas com pontuação de 0 a 100%, e aguenta as noites de lua cheia e nevoeiro.

## Jogar no teu computador

Abre o `index.html` no browser. Precisa de internet para carregar o Three.js e os tipos de letra. Se preferires um servidor local: `python3 -m http.server` e abre `http://localhost:8000`.

## Usar sem internet

Descarrega https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js e guarda-o na mesma pasta do `index.html` com o nome `three.min.js`. A página usa essa cópia quando não consegue carregar a da internet.

## Controlos

- **Mover:** WASD ou setas, ou clicar no chão. No telemóvel há um joystick.
- **Câmara:** Q e R rodam, a roda do rato aproxima.
- **Atacar:** Espaço ou o botão Atacar.
- **Ação do objeto mais próximo:** E (também há botões no fundo do ecrã).
- **Mochila:** I.
- **Pausa:** Esc ou P.

## Gravação

O jogo grava no browser (3 espaços e uma gravação automática, no menu de pausa). As gravações ficam no browser e no endereço onde jogas: mudar de browser, de dispositivo ou de endereço começa um jogo limpo.

## Licenças

O código do jogo é teu. O Three.js (r128) é distribuído sob licença MIT: https://github.com/mrdoob/three.js
