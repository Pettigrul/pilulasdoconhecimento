Identidade das aulas **Pílulas do Conhecimento**, da Auditoria Interna do Banco BV. Tudo aqui foi extraído da vinheta de abertura: um frasco com um cérebro no rótulo solta cápsulas azuis e brancas, que viram o chão onde nasce o título. A ideia é que cada aula seja uma dose curta, concentrada e fácil de engolir.

## Conceito

- **Uma pílula, um assunto.** Cada aula resolve uma dúvida só. Se o conteúdo pede dois títulos de capa, são duas pílulas.
- **Metade azul, metade branca.** A cápsula dividida é o elemento gráfico central. Ela aparece na barra-assinatura, no selo de numeração, nos marcadores e nos botões. Sempre na ordem azul à esquerda, branco à direita.
- **Palco escuro, luz no centro.** O fundo é um radial azul que clareia atrás do conteúdo e escurece nas bordas. O olho vai para onde está a luz.

## Voz e texto

- Escreva em português do Brasil, segunda pessoa informal ("você"), frases curtas.
- Títulos de slide em caixa de frase ("As três linhas na prática"). Caixa alta só na assinatura (`display-marca`, `sobretitulo`) e em slides divisores (`titulo-secao`).
- Um tópico cabe em uma linha de `corpo`. Máximo de cinco tópicos por slide.
- Nomes de área e marca exatamente assim: **Auditoria Interna**, **Banco BV**, separados por uma barra vertical em `acento` no rodapé.
- Sem emoji. Ícones de linha, no traço do `icone-cerebro`, quando necessário.
- Chame as aulas de "pílula" e numere com dois dígitos: Pílula 01, Pílula 02.

## Cor

- Todo slide nasce do `fundo` com uma das três imagens de fundo por cima (grupo Fundos). Nunca use fundo branco no tema `palco`.
- `texto` para títulos e corpo, `texto-suave` para sobretítulos, legendas e rodapé, `destaque` para uma palavra-chave por frase.
- `acento` (azul elétrico #005FFD) é cor de forma: barra, separador, número grande, marcador. Como texto só a partir de 24px, porque tem 3,45:1 sobre `azul-abismo`.
- `superficie` para cartões, `superficie-realce` para o único cartão que merece o olhar primeiro.
- `sinal-atencao` e `sinal-critico` existem para risco e achados de auditoria. Sempre com a palavra escrita ao lado ("Risco alto"), nunca só a cor.
- Proporção de uso no palco: cerca de 70% azuis escuros, 20% branco-gelo, 10% azul elétrico.
- Tema `papel` serve para apostilas, e-mails e documentos impressos: fundo branco-gelo, texto azul-abismo, destaque azul-capsula.

## Tipografia

- Família única: **Poppins** (Google Fonts, arquivos em `fonts/`). Pesos usados: 400, 500, 600, 700, 800, 900.
- `display-marca` (900, caixa alta) só na capa e na assinatura. Sempre com o brilho de texto `text-shadow: 0 0 24px rgba(61,123,255,.75)`.
- `sobretitulo` (600, caixa alta, espaçamento 0,3em) acima de todo título de capa ou divisor.
- Em slide: `titulo-slide` 64px/800, `subtitulo` 36px/600, `corpo` 32px/400. Nada abaixo de 24px (`legenda` e `rodape`).
- Tamanhos são para a tela de referência 1920×1080. Em PowerPoint 13,33×7,5 pol, divida por 2 e use pt: título 32pt, corpo 16pt, legenda 12pt.

## Forma e espaço

- `raio-capsula` em tudo que for barra, selo ou botão. `raio-cartao` em caixas de conteúdo. Não misture cantos retos.
- Margem de segurança de `espaco-12` (96px) nas laterais e no topo; 160px na base, onde fica o rodapé.
- Grade de 12 colunas na área útil de 1728px, gutter de `espaco-3`.
- Cartões recebem `sombra-cartao`; só elementos em `acento` recebem `brilho-acento`.

## Elementos de marca

- **Assinatura**: PÍLULAS DO / CONHECIMENTO / barra-assinatura / Auditoria Interna | Banco BV. Use o arquivo `lockup-pilulas-do-conhecimento.png` (o SVG depende da Poppins instalada). Área de proteção: a altura do "C" de CONHECIMENTO em volta de tudo. Não recolorir, não distorcer, não usar sobre fundo claro.
- **Barra-assinatura**: 500×20 na assinatura; em slides internos serve de indicador de progresso da aula (a parte azul cresce da esquerda).
- **Chão de pílulas**: faixa de cápsulas espalhadas, só na capa e no encerramento, colada à base do slide.
- **Frasco com cérebro**: mascote da série. Use na capa alternativa, no slide de pausa e no encerramento. Um por slide, nunca cortado.
- **Pílula solta**: marcador de tópico e ícone de "dica". Pode girar entre -35° e 35°.
- Logotipo do Banco BV não está incluído: a vinheta usa só o nome em texto. Se precisar do logo, peça a versão oficial ao time de marca.

## Movimento (vinheta, 10s)

- 0,0–1,5s frasco surge em fade e flutua. 2,0s a tampa salta. 2,5–4,5s cápsulas caem e formam o chão. 5,5s o frasco sobe e some. 5,8–7,0s letras de PÍLULAS DO e CONHECIMENTO sobem em cascata. 7,0s a barra cresce do centro. 7,5s o subtítulo entra em fade. 8–10s brilho percorre o título.
- Em slides, transições só de fade (0,3s) ou empurrar para a esquerda. Tópicos entram um a um de baixo para cima, 0,2s cada.
