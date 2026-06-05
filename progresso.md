Metodologia das Aulas

Projeto novo a cada aula, com repositório no GitHub
Professor ensina, pergunta, aluno tenta, professor corrige
Respostas não são dadas diretamente — o aluno é guiado a pensar
Se algo não ficou claro, o professor explica de novo de forma mais simples
Sugestões de melhoria são dadas quando faz sentido
Resumo no final de cada aula para atualizar o progresso.md

#progresso das Aulas

## Aula 1 - Diagnóstico HTML e CSS
- Nível atual: intermediário alto em HTML e CSS
- Semântica HTML: header, nav, main, section, footer
- Hierarquia de títulos: h1 → h2 → h3
- Box model e box-sizing: border-box
- Variáveis CSS com :root
- Flexbox aplicado em cards e navegação
- 100vh: quando usar e quando não usar
- Mobile First: conceito e filosofia
- Media queries: sintaxe e breakpoints

## Aula 2 - Git pelo terminal
- git init, git add, git commit, git log
- git remote add origin, git push
- Repositório criado: https://github.com/s-a-m-i-o/projeto-git
- Responsividade com Mobile First
- Media queries na prática
- Espaçamento com padding em vez de altura fixa
- Seletores perigosos com vígula
- Fluxo git completo num projeto real
- Criar e conectar repositório do zero

## Aula 3 - projeto : Quadro de Anúncios
- Repositório: https://github.com/s-a-m-i-o/quadro-de-anuncios
- Objetivo: viewer de imagens semanais com navegação anterior/próxima
- Mobile First desde o início
- Criado site HTML CSS e JS
- HTML semantico, importado links externos no head (googleFots, font awesome)
- CSS: separado por, reset, root e estilo, tres arquivos diferentes
- JS: função addEventListener: botão direiro proxima imagem, botão esquerdo imagem anterior

## Continuação da aula 3
- JS: Adicionado um Stop na primeira e ultima imagem
- Criando novo Index e paginas - REUNIÃO DA SEMANA, REUNIÃO PUBLICA, LIMPEZA e PREGAÇÃO
- Adicionado botão de voltar nas paginas
- JS: Adiciondo menu hamburger
- Criado README.md
- Finalizar projeto e adicionar README
- Projeto finalizado e publicado - https://s-a-m-i-o.github.io/quadro-de-anuncios/

## Aula 4 - CSS Avançado: Animações e Transitions

- Repositório: https://github.com/s-a-m-i-o/transitions_animacoes
- Projeto: Portfólio fictício de Bruce Wayne
- Comandos novos do terminal: mkdir, touch, mv
- transition: suaviza mudança entre estados, precisa de um gatilho (:hover, :focus, etc)
- Sintaxe do transition: propriedade duração timing
- transform: propriedade ideal pra animar, não afeta o layout ao redor
- Funções do transform: translateX, translateY, scale, rotate, skew
- @keyframes: define os quadros da animação com porcentagens (0%, 50%, 100%)
- animation: chama o @keyframes pelo nome e define duração, timing e repetição
- Diferença entre transition e animation: transition precisa de gatilho, animation roda sozinha
- Timing functions na prática: linear ideal pra rotação contínua, ease-in-out pra movimentos naturais
- Variáveis CSS funcionam pra qualquer valor, não só cores
- Página de exemplos criada com vários modelos de animações combinando transform, cores e box-shadow

## Aula 5 - CSS Avançado: Pseudo-elementos e Seletores Avançados

- Repositório: https://github.com/s-a-m-i-o/pseudo-elementos
- Projeto: Card de produto com selo de oferta e animação
- ::before e ::after: criam elementos "fantasma" antes e depois do conteúdo, sem tocar no HTML
- content é obrigatório nos pseudo-elementos, mesmo vazio content: ""
- Pseudo-elementos precisam de display: block ou display: flex pra aceitar width e height
- position: relative no pai + position: absolute no filho = filho se posiciona em relação ao pai
- Diferença entre pseudo-classes (:): representam um estado — e pseudo-elementos (::): criam uma parte do elemento

- - Seletores avançados:

- :first-child — seleciona o primeiro filho
- :last-child — seleciona o último filho
- :nth-child(n) — seleciona o filho pela posição
- :not() — seleciona todos exceto o especificado
- > — seleciona apenas filhos diretos
- + — seleciona o elemento imediatamente após outro
- ~ — seleciona todos os irmãos após um elemento