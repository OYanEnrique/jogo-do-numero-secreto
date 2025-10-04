# Jogo do Número Secreto

Um jogo de adivinhação desenvolvido em JavaScript durante o curso de JavaScript da Alura onde o jogador precisa descobrir um número secreto entre 1 e 10. O jogo utiliza síntese de voz para fornecer feedback em português.

🎮 **[Jogar Online](https://jogonumerosecreto-sigma-black.vercel.app/)**

## Sobre o Projeto

O jogador tenta adivinhar um número secreto e recebe dicas se o número é maior ou menor. O jogo conta as tentativas e utiliza a Web Speech API para falar as instruções e feedbacks em português brasileiro.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## Como Clonar o Repositório

```bash
git clone https://github.com/OYanEnrique/jogo-do-numero-secreto.git
cd jogo-do-numero-secreto
```

Após clonar, abra o arquivo `index.html` no seu navegador.

## Estrutura de Pastas

```
jogo-do-numero-secreto/
│
├── index.html          # Página principal
├── app.js              # Lógica do jogo
├── style.css           # Estilos
├── LICENSE             # Licença MIT
├── README.md           # Documentação
│
└── img/                # Imagens do projeto
    ├── ia.png
    ├── bg.png
    ├── code.png
    └── Ruido.png
```

## Funções JavaScript

### `exibirTextoNaTela(tag, texto)`
Exibe texto na tela e utiliza a Web Speech API para sintetizar voz em português.

### `gerarNumeroAleatorio()`
Gera um número aleatório entre 1 e 10 e evita repetições consecutivas usando um array de histórico.

### `verificarChute()`
Verifica o palpite do jogador e fornece feedback se o número secreto é maior, menor ou se o jogador acertou.

### `reiniciarJogo()`
Reinicia o jogo gerando um novo número secreto e resetando o contador de tentativas.

### `limparCampo()`
Limpa o campo de entrada após cada tentativa.

## Licença

Este projeto está sob a licença MIT.
