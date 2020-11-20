# Primeira semana

## Índice
- [Bem vindo ao curso](#bem-vindo-ao-curso)
- [Quem é afetado pelos problemas de acessibilidade](#quem-é-afetado-pelos-problemas-de-acessibilidade)
- [Acessibilidade em serviços de streaming online](#acessibilidade-em-serviços-de-streaming-online)
- [Projetando com acessibilidade em mente](#projetando-com-acessibilidade-em-mente)
- [Acessibilidade: o que fazer e o que não Fazer](#acessibilidade-o-que-fazer-e-o-que-não-fazer)
- [Análise automatizada de acessibilidade](#análise-automatizada-de-acessibilidade)

---

## Bem vindo ao curso

### Resumo
Marcus Ophir fala sobre seu trabalho de consultoria em acessibilidade e sobre sua necessidades de acessibilidade.
O Marcus tem Dislexia e Síndrome de Usher, que é uma doença genética (hereditária) que causa surdez e perda gradual da visão.

**Duração:** 3:29 min

### Anotações
- A Síndrome de Usher é seguimentada em 4 tipos
  - Tipo 1: Você já nasce cego ou surdo;
  - Tipo 2 e 3: Após a puberdade começa a desenvolver os sintomas;
  - Tipo 4: É um tipo mais raro, afeta apenas 10% da população acometida pela Síndrome de Usher;


### Links extras
- [Síndrome de Usher Brasil](https://en.sindromedeusherbrasil.com.br/)
- [Síndrome de Usher - FIOCRUZ](http://www.fiocruz.br/biosseguranca/Bis/infantil/sindrome-usher.htm)

---

## Quem é afetado pelos problemas de acessibilidade

### Resumo
Marcus fala sobre o escopo dos problemas de acessibilidade e a ampla gama de diferentes condições e deficiências;

**Duração:** 2:20 min

### Anotações
- As diretrizes de acessibilidade são importantes para todos os envolvidos, desenvolvedores, designers e criadores;
- Se seu app não está acessível a todos, você está excluíndo diversas pessoas que precisam de sua tecnologia;
- Não fazer um app acessível, não é uma escolha, é o jeito certo de desenvolver (e a lei);
- Aproximadamente 1 em cada 5 pessoas no mundo vive com alguma deficiência, tendo assim a sua capacidade de usar a tecnologia afetada.
- Algumas deficiências incluem:
  - Visuais, com 258M de pessoas no mundo, nas quais 39M são cegas;
  - Auditivas, com 466M de pessoas no mundo, que significa 6.1% da população mundial;
  - Dislexia, estima-se que 1 em cada 10 pessoas tenha;
  - Autismo;
  - Motoras;
  - Alzheimer;
  - Dentre outras;

### Links extras
- [Diverse Abilities and Barriers - W3C WAI](https://www.w3.org/WAI/people-use-web/abilities-barriers/)

---

## Acessibilidade em serviços de streaming online

### Resumo
Marcus fala sobre as opções  de acessibilidade da BBC iPlayer e como elas podem ser melhoradas e compara com as disponíveis na Netflix.

**Duração:** 6:06 min

### Anotações
- No suporte de acessibilidade do BCC iPlayer tem diversas opções que melhoram a experiência para visão parcial e cego, problemas de audição e também dilexia, porém peca em não disponibilizar ao usuário a possibilidade de mudar a aparência do site, o site de suporte tem um layout completamente diferente do site principal, trazendo confusão para os usuários. O site de supporte não usa conexão segura, coisa que viola o GDPR (General Data Protection Regulation);
- Já na Netflix, as configurações de acessibilidade ficam no mesmo domínio (na configuração do usuário), porém muito difícil de encontrar, com textos de baixo contraste;
- O Marcus mostra um redesign do BBC iPlayer, mantendo essas personalizações no mesmo ambiente web;
- O uso de ícones na interface, junto com seu rótulo (texto), ajudam aqueles usuários que tem dificuldades de leitura a entender a ação;
- A personalização do usuário é uma parte crítica da experiência do usuário moderno;
- Será que todos os serviços de streaming tem opções acessível? Quais são? Será que são fáceis de encontrar?
- Creio que a melhor abordagem é testar com pessoas de diferentes tipos de dificuldades e buscar soluções usando os feedbacks;

### Links extras
- [BBC iPlayer](https://www.bbc.co.uk/iplayer);
- [Netflix](https://www.netflix.com/browse);
- [Broaden your audience: accessibility features in video streaming - Unified Streaming](https://www.unified-streaming.com/blog/broaden-your-audience-accessibility-features-video-streaming)

---

## Projetando com acessibilidade em mente

### Resumo
É importante que a acessibilidade seja considerada em todas as etapas do processo de design, não somente adicionar um menu para determinadas personalizações.

**Duração de leitura:** 2:30 min

### Anotações
- Existe um conceito chamado "born accessible", que é um conceito usado quando a acessibilidade é considerada desde o início do projeto/produto, ou para qualquer outra coisa, como por exemplo, eventos, publicações, organizações e etc;
- Ao projetar um produto normalmente é criada diversas "suposições" implícitas, algumas dicas foram dadas para ajudar a mitigar a dificuldade de alguns usuários ao usar:
  - Tornar as suposições explicitas;
  - Referindo-se a elas durante todo o processo de design;
  - Entender quais dessas suposições estão potencialmente dificultando as coisas para determinados usuários;
  - Tomar decisões de design para mitigar (diminuir) esses problemas;

### Links extras
- [The Labor Pains of Born Accessible](https://www.youtube.com/watch?v=N4GIy8KpVHI);

---

## Acessibilidade: o que fazer e o que não Fazer

**Duração:** 1:30 min

### Anotações
#### [Projetando para usuários com espectro autista](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-BR/autistic-spectrum_pt-BR.pdf)
- Você deve fazer: 
  - Usar cores simples;
  - Escrever o idioma de maneira simples;
  - Usar frases e marcadores simples;
  - Tornar os botões auto-descritivos;
  - Construir layouts simples e construtivos;

- Você **NÃO** deve fazer:
  - Usar cores brilhantes e contrastantes;
  - Usar figuras de linguagem e expressões/gírias;
  - Criar uma parede de texto (Isso acontece quando criamos parágrafos bem longos);
  - Botões vagos ou imprevisíveis (Por exempl: clique aqui)
  - Construir layouts complexos e desordenados;

#### [Projetando para usuários de leitores de tela](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-BR/screenreader_pt-BR.pdf)
- Você deve fazer:
  - Descrever as imagens (usando o atributo alt);
  - Fornecer transcrição de vídeos;
  - Construir um layout linear e lógico;
  - Estruturar o conteúdo usando HTML5;
  - Construir para uso apenas do teclado;
  - Escrever links e títulos auto-descritivos;

- Você **NÃO** deve fazer:
  - Mostrar informações apenas em imagem ou vídeo;
  - Espalhar conteúdo por toda a página;
  - Estrutura dependendo do tamanho do texto e do posivionamento;
  - Focar uso do mouse ou da tela;
  - Escrever links e títulos não informativos;

#### [Projetando para usuários com baixa visão](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-BR/low-vision_pt-BR.pdf)
- Você deve fazer:
  - Usar bons contrastes de cores;
  - Usar um tamanho de fonte legível;
  - Publicar todas as informações diretamente em páginas HTML;
  - Usar combinações de cores, texto e formas;
  - Garantir boa leitura quando ampliado (+200% de zoom);
  - Construir botões e notificações dentro de um contexto;

- Você **NÃO** deve fazer:
  - Usar baixo contraste;
  - Fonte com tamanho pequeno;
  - Esconder informações em arquivos para download;
  - Usar apenas cores para transmitir significado;
  - Espalhar o conteúdo em toda a página e exigir que o usuário role a tela em apliações;
  - Separar ações do contexto;

#### [Projetando para usuários com deficiência física ou motora](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-BR/motor-disabilities_pt-BR.pdf)
- Você deve fazer:
  - Criar grandes áreas de click;
  - Um bom espaçamento entre campos de formulário;
  - Projetar para usar apenas com o teclado ou voz;
  - Projetar para telas móveis e tocáveis;
  - Fornecer atálhos (por exemplo, agilizar o preenchimento do endereço com busca pelo cep);

- Você **NÃO** deve fazer:
  - Necessidade de precisão, com pequena ou sem área de click;
  - Agrupamento de interações próxima;
  - Conteúdo dinâmico que requer muito movimento do mouse;
  - Exibir mensagens em um curto período de tempo (por exemplo um toast notification que desaparece em poucos segundos);
  - Cansar o usuário com muita digitação e rolagem (Por exemplo, um formulário grande);

#### [Projetar para usuários surdos ou com deficiência auditiva](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-BR/deaf_pt-BR.pdf)
- Você deve fazer:
  - Escreva de forma simples e clara;
  - Forneça legendas e/ou transcrição para os vídeos;
  - Construir layouts simples e consistentes;
  - Dividir o conteúdo com sub-título, imagens e vídeos;
  - Permitir que o usuário escolha o seu melhor meio de comunicação (Por exemplo disponibilizar algum app de libras no seu site);

- Você **NÃO** deve fazer:
  - Usar figuras de linguagem ou expressões idiomáticas;
  - Usar conteúdo apenas em áudio ou vídeo;
  - Construir layouts complexos e desordenados;
  - Construir longos blocos de conteúdo;
  - Não faça do telefone o único meio de contato para os usuários;

#### [Projetando para usuários com Dislexia](https://github.com/UKHomeOffice/posters/blob/master/accessibility/dos-donts/posters_pt-PT/dyslexia_pt-PT.pdf)
- Você deve fazer:
  - Usar imagens e diagramas para apoiar o texto;
  - Texto alinhado a direita e layout consistente;
  - Considere também o uso de conteúdo em áudio e vídeo;
  - Mantenha o conteúdo curto, claro e simples;
  - Permitir que os usuários alterem o contraste entre o fundo e o texto;

- Você **NÃO** deve fazer:
  - Usar bloco de texto pesados;
  - Sublinhe palavras, use itálico ou escreva maiúsculas;
  - Forçar o usuário a lembrar de coisas das páginas anteriores;
  - Depender de ortografia precisa - Use a correção automática ou forneça sugestões (por exemplo, o Google search fornece sugestões quando escrito de maneira errada);
  - Coloque muita informação em um só lugar;

### Links extras
- [Cartazes de 'Fazer e o que não Fazer'](https://github.com/UKHomeOffice/posters/tree/master/accessibility/dos-donts/posters_pt-BR)
- [Dos and don'ts on designing for accessibility](https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/);
- [Anki Deck](https://ankiweb.net/shared/info/128807691)

## Análise automatizada de acessibilidade

**Duração de leitura:** 2 min

### Anotações
- Já conheço diversas ferramentas de analises de acessibilidade, elas são interessantes para analisar automaticamente quando se trata de conformidade com a WCAG e algumas ainda nos educa com explicações e soluções;
- Uma das ferramentas mais conhecidas de analise de websites é o [aXe](https://www.deque.com/axe/) da [Deque Systems](https://www.deque.com/), eu até criei um pacote ([vue-axe](https://github.com/vue-a11y/vue-axe-next)) para o projeto [Vue-A11y](https://vue-a11y.com/) baseado no [axe-core](https://github.com/dequelabs/axe-core), sempre ao desenvolver apps com Vue uso para ter feedback em tempo real;
- Foi indicado [WAVE](https://wave.webaim.org/) e o [scanner AlumniOnline](https://www.alumnionlineservices.com/accessibility/scanner/), essa segunda eu não conhecia, mas achei interessate, pois analisa sites online e checa tanto para WCAG 2.0, quanto para [Section 508](https://www.section508.gov/);
- Eu costumo usar (além do aXe) e recomendo muito é a extensão chamada [Accessibility Insights for Web](https://accessibilityinsights.io/docs/en/web/overview/) by Microsoft, acho ela incrível, didática e bem completa.

### Links extras
- Para outras opções eu sempre pesquiso em [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/) (da W3C) que lista dezenas de ferramentas de avaliação;