# Espaco de Gabriel

Espaco de Gabriel e um jogo 2D de acao com visual inspirado no Game Boy Color. O projeto foi construido em um unico arquivo HTML e funciona tanto no computador quanto no celular, com foco em jogabilidade rapida, visual retro e acesso simples sem instalacao.

## Sobre o jogo

No jogo, o jogador atravessa uma arena infinita, coleta estrelas, pega armas espalhadas pelo mapa e enfrenta monstros que surgem ao redor da camera. O objetivo e sobreviver, marcar pontos e evoluir durante a partida.

## Destaques

- Visual retro inspirado no Game Boy Color
- Arena infinita com camera acompanhando o jogador
- Suporte a teclado e controles touch
- Tres tipos de arma com comportamentos diferentes
- Pickups de arma espalhados pelo mapa
- Sistema de pontos, vida, nivel e tempo de partida
- Jogo responsivo em um unico arquivo `HTML`

## Controles

### Computador

- `Setas`: mover
- `A`: atirar
- `B`: turbo
- `C`: trocar arma
- `Enter`: comecar ou reiniciar

### Celular

- Direcional na tela: mover
- Botao `A`: atirar
- Botao `B`: turbo
- Botao `C`: trocar arma
- `Start`: comecar ou reiniciar
- `Select`: trocar arma

## Armas

- `Blaster`: tiro rapido e preciso
- `Espalhadora`: varios disparos em abertura
- `Plasma`: tiro mais forte e com maior impacto

## Como executar

Nao e preciso instalar dependencias.

1. Clone ou baixe este repositorio.
2. Abra o arquivo `index.html` em qualquer navegador moderno.

Se quiser usar um servidor local, uma opcao simples e:

```bash
python3 -m http.server
```

Depois disso, abra o navegador no endereco informado pelo terminal.

## Estrutura do projeto

```text
.
├── index.html
└── README.md
```

## Tecnologias usadas

- `HTML5`
- `CSS3`
- `JavaScript`
- `Canvas API`

## Objetivos do projeto

- Criar um jogo leve e facil de abrir
- Entregar uma experiencia retro com identidade visual propria
- Funcionar bem em desktop e mobile
- Manter toda a logica central em um unico arquivo para facilitar estudo e compartilhamento

## Proximos passos sugeridos

- Adicionar efeitos sonoros e musica retro
- Criar chefes e inimigos com padroes diferentes
- Salvar recorde local no navegador
- Incluir tela de pausa e menu de opcoes
- Publicar no GitHub Pages

## Autor

Projeto criado para o jogo **Espaco de Gabriel**.
