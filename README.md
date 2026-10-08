# Ficha de Herói: Guaribaçu, o Grande Macaco

Projeto Prático (Parte 1) da disciplina de Tecnologia Web: uma página em HTML e CSS que funciona como a tela de status de um RPG, apresentando um personagem original.

## O personagem

**Sgt. Marcos Hedmar** é um soldado do Exército Brasileiro, de família simples e muito corajoso. Durante uma missão na Amazônia contra um laboratório secreto estadunidense que fazia experimentos com primatas, ele cai em um tanque de mutação e se transforma em um homem-gorila, com a força de uma fera e a mente de um soldado.

O Exército guarda o caso em segredo e o batiza de **Guaribaçu** (do tupi: *guariba*, macaco, e *guaçu*, grande). Os ribeirinhos acham que ele é o Mapinguari, mas ele é o **Guardião da Floresta Amazônica** e lidera o **Esquadrão Costas-Prateadas** na caça aos outros laboratórios.

## Seções da página

- **Sobre o Herói:** a história em 4 capítulos, a origem do nome, a lenda e a personalidade
- **Atributos & Habilidades:** barras de progresso (Força, Coragem, Resistência, Pontaria, Agilidade), habilidades e ponto fraco
- **Inventário:** itens com raridade (lendário, épico, raro e comum)
- **Conquistas & Objetivos:** missões concluídas e em andamento
- **Contato com o Esquadrão:** links e botão de mensagem

## Tecnologias

- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `footer`, `figure`)
- CSS3 em arquivo externo (`style.css`)
- Flexbox no menu e CSS Grid no inventário
- Media queries: 1 coluna no celular, 2 no tablet e 3 no desktop
- Variáveis CSS no `:root` com a paleta do universo
- Google Fonts (Black Ops One, Barlow e Barlow Condensed) e ícones do Font Awesome

## Estrutura de pastas

```
ficha-heroi-parte1/
├── index.html
├── style.css
├── README.md
└── imagens/
```

## Como abrir

Abra a pasta no VS Code e clique em **Go Live** (extensão Live Server), ou dê dois cliques no `index.html`.

## Decisões de UI/UX

- **Hierarquia visual:** o nome "Guaribaçu" é o maior texto da página e aparece logo na capa, ao lado da imagem do personagem. Depois vêm o subtítulo e os botões, guiando o olhar do herói para as ações.
- **Contraste e legibilidade:** fundo escuro (carvão e verde-escuro) com texto claro (areia e prata), seguindo a referência WCAG AA. O dourado é usado só em destaques.
- **Consistência:** todos os cards de item, missões e barras de atributo seguem o mesmo padrão de borda, cor, espaçamento e cantos, definidos nas variáveis do `:root`.
- **Affordance e feedback:** botões, links e cards mudam de cor e crescem levemente ao passar o mouse (`transition`), mostrando que são clicáveis.
- **Área de toque (Lei de Fitts):** botões e links do menu têm no mínimo 44px de altura, para facilitar o toque no celular.
- **Proximidade (Gestalt):** em cada atributo, o ícone, o nome, o valor e a barra ficam agrupados, e a explicação vem logo abaixo.
- **Fluxo de leitura:** a página segue uma ordem natural de cima para baixo: apresentação do herói, história, atributos, inventário, conquistas e, por último, o contato com o esquadrão.

## Autor

Rychard: projeto individual de Tecnologia Web.
