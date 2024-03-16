# CSS (Cascading Style Sheets)

## Introdução
- O que é CSS?
  - Folhas de estilo em cascata para estilizar páginas HTML.
- Importância do CSS no desenvolvimento web
  - Separar a estrutura (HTML) do estilo (CSS), o que facilita a manutenção e a alteração do design.
- Sintaxe básica do CSS
  - Regras CSS são compostas por um seletor e um bloco de declaração.

## Seletores CSS
- Seletores de elemento
  - Seletor que seleciona todos os elementos de um determinado tipo.
- Seletores de classe
  - Seletor que seleciona elementos com um determinado valor de classe.
- Seletores de ID
  - Seletor que seleciona um elemento com um ID específico.
- Seletores de atributo
  - Seletor que seleciona elementos com um atributo específico.
- Seletores combinados
  - Seletor que combina dois ou mais seletores simples.
- Seletores pseudo-classe
  - Seletor que especifica um estado especial do elemento.
- Seletores pseudo-elemento
  - Seletor que especifica uma parte específica de um elemento.

## Propriedades CSS
- Tipografia
  - font-family: Define a família de fontes.
  - font-size: Define o tamanho da fonte.
  - font-weight: Define a espessura da fonte.
  - font-style: Define o estilo da fonte (normal, itálico, etc.).
  - text-align: Define o alinhamento do texto.
  - text-decoration: Define a decoração do texto (sublinhado, tachado, etc.).
- Cores e Fundos
  - color: Define a cor do texto.
  - background-color: Define a cor de fundo.
  - background-image: Define uma imagem de fundo.
  - opacity: Define a opacidade do elemento.
- Layout
  - width: Define a largura do elemento.
  - height: Define a altura do elemento.
  - margin: Define as margens externas.
  - padding: Define o preenchimento interno.
  - display: Define o método de exibição do elemento.
  - position: Define o método de posicionamento.
  - float: Define a flutuação do elemento.
  - flexbox: Define um layout flexível.
  - grid: Define um layout de grade.
- Bordas
  - border-style: Define o estilo da borda.
  - border-width: Define a largura da borda.
  - border-color: Define a cor da borda.
  - border-radius: Define o raio da borda.
- Espaçamento
  - margin: Define as margens externas.
  - padding: Define o preenchimento interno.
- Posicionamento
  - position: Define o método de posicionamento.
  - top, right, bottom, left: Define a posição absoluta ou relativa.
- Overflow
  - Define o comportamento do conteúdo que estoura seus limites.
- Box Model
  - Modelo que descreve como os elementos HTML são renderizados e tratados em layout.

## Unidades de Medida
- px: Pixels, uma unidade absoluta.
- em: Relativa ao tamanho da fonte do elemento pai.
- rem: Relativa ao tamanho da fonte do elemento raiz.
- %: Porcentagem, relativa ao tamanho do elemento pai.
- vw, vh: Relativa à largura da janela de visualização e à altura da janela de visualização, respectivamente.

## Pseudo-classes e Pseudo-elementos
- :hover: Aplica estilos quando o cursor está sobre o elemento.
- :active: Aplica estilos quando o elemento é clicado.
- :focus: Aplica estilos quando o elemento está em foco.
- :nth-child: Seleciona elementos com base em sua posição em relação aos irmãos.
- :first-child: Seleciona o primeiro filho de um elemento pai.
- :last-child: Seleciona o último filho de um elemento pai.
- ::before: Cria um pseudo-elemento antes do conteúdo do elemento.
- ::after: Cria um pseudo-elemento após o conteúdo do elemento.

## Media Queries
- Introdução às Media Queries
  - Permitem aplicar estilos com base em características do dispositivo, como largura da tela.
- Utilização de Media Queries para Responsividade
  - Técnica para criar layouts responsivos que se adaptam a diferentes dispositivos.
- Breakpoints comuns para diferentes dispositivos
  - Pontos de interrupção comuns usados para definir estilos em diferentes tamanhos de tela.

## Flexbox
- O que é Flexbox?
  - Modelo de layout unidimensional que permite o alinhamento de itens em uma linha ou coluna.
- Propriedades do Flexbox
  - flex-direction, justify-content, align-items, flex-wrap, flex-grow, flex-shrink, flex-basis, align-self.
- Exemplos práticos de layout com Flexbox

## Grid Layout
- O que é Grid Layout?
  - Modelo de layout bidimensional que permite o alinhamento de itens em linhas e colunas.
- Propriedades do Grid Layout
  - grid-template-rows, grid-template-columns, grid-gap, grid-row, grid-column, justify-items, align-items.
- Exemplos práticos de layout com Grid

## Transformações e Transições
- Transformações 2D e 3D
  - Translate, rotate, scale, skew.
- Transições CSS
  - Efeitos de transição suaves entre diferentes estados de um elemento.
- Animações CSS
  - Criação de animações personalizadas usando keyframes.

## Pré-processadores CSS
- Introdução aos Pré-processadores CSS
  - Ferramentas que estendem a sintaxe do CSS, como SASS, LESS e Stylus.
- SASS/SCSS
  - Um dos pré-processadores CSS mais populares, com recursos como variáveis, mixins, e nesting.
- LESS
  - Outro pré-processador CSS que simplifica o desenvolvimento de estilos.
- Stylus
  - Um pré-processador CSS com uma sintaxe mais minimalista.

## Metodologias CSS
- BEM (Block, Element, Modifier)
  - Metodologia de nomenclatura para tornar o código CSS mais modular e reutilizável.
- OOCSS (Object-Oriented CSS)
  - Metodologia que enfatiza a reutilização de estilos e a separação de estrutura e estilo.
- SMACSS (Scalable and Modular Architecture for CSS)
  - Metodologia que organiza estilos em categorias como Base, Layout, Módulos e Temas.

## Frameworks CSS
- Bootstrap
  - Um dos frameworks CSS mais populares para desenvolvimento web responsivo.
- Foundation
  - Framework CSS que oferece uma abordagem modular e flexível para criar layouts responsivos.
- Materialize CSS
  - Framework CSS baseado no conceito de Material Design do Google, oferecendo componentes pré-projetados e estilos modernos.

## Ferramentas de Desenvolvimento
- DevTools do navegador
  - Conjunto de ferramentas integradas nos navegadores para inspecionar e depurar código CSS e HTML.
- Autoprefixer
  - Ferramenta que adiciona automaticamente prefixos de fornecedor ao código CSS para garantir compatibilidade entre navegadores.
- CSS Reset vs. Normalize.css
  - Técnicas para criar uma base consistente de estilos em diferentes navegadores.
- PostCSS
  - Ferramenta que permite manipular e transformar CSS usando JavaScript.
- Grunt, Gulp, Webpack
  - Ferramentas de automação e construção para simplificar o processo de desenvolvimento front-end.

## Melhores Práticas
- Performance CSS
  - Estratégias para otimizar o desempenho do CSS, como reduzir o número de solicitações HTTP e evitar seletores complexos.
- Organização do código CSS
  - Padrões de organização de arquivos CSS, como agrupamento por componente ou funcionalidade.
- Compatibilidade entre navegadores
  - Considerações para garantir que o CSS seja compatível com diferentes navegadores e versões.
- Testes e Debugging
  - Métodos para testar e depurar o código CSS, como inspeção de elementos e testes em navegadores diferentes.
