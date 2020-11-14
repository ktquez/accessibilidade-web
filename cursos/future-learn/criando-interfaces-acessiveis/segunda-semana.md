# Segunda semana

## Índice
- [Por que consistência?](#por-que-consistência)
- [Por que personalização?](#por-que-personalização)
- [Resumo da segunda semana](#resumo-da-segunda-semana)

---

## Por que consistência?

### Resumo
Fala da importância em manter os sites com uma aparência e um comportamento consistênte.

### Anotações
- A consitência permite que os usuários criem atalhos mentais e reduz o tempo para realização uma ação/tarefa;
- A consistência de comportamento é mais importante do que a consistência de estilo;
- A falta de consistência de estilo pode afetar particularmente usuários com deficiência, pode causar confusão em usuários com deficiências cognitivas ou com que leitores de tela funcionem incorretamente;
- Falando em consistência, me lembrei de um assunto em uns dos comentários no curso, que foi o lançamento dos novos ícones dos apps do Google, aparentemente os ícones de multicores tem sim uma boa consitãncia, mas para outras pessoas a identificação de qual app era, ficou um pouco confuso;

### Links extras
- [Clear Layout and Design - W3C WAI](https://www.w3.org/WAI/perspective-videos/layout/);
- [Designing for Web Accessibility - W3C WAI](https://www.w3.org/WAI/tips/designing/);
- [Why Consistency is Important to Accessible Design](https://www.boia.org/blog/why-consistency-is-important-to-accessible-design);
- [Tweet de um perfil chamado "Killed by Google" mostra o quão confuso pode ser os novos ícones](https://twitter.com/killedbygoogle/status/1320823388219133952);

---

## Por que personalização?

### Resumo
Apps que fornecem formas de mudar sua aparência, são mais acessível e utilizáveis.

### Anotações
- As pessoas tem suas preferências, então se torna uma experiência bastante positiva quando podemos personalizar a aplicação;
- A personalização não precisa ser somente alterar de modo claro e escuro, para determinados usuários, poder personalizar espaçamento, tipo de fonte (por exemplo uma fonte apropriada para usuários com dislexia) e etc;
- No curso fala sobre ação para aumentar e diminuir o tamanho da fonte via css e js, porém nos dias atuais (estou escrevendo essas anotações em 2020) isso não é mais um requisito de acessibilidade, já que você pode obter zoom satisfatório nativamente através do seu browser;
- Recomendo até mesmo você que está lendo isso, testar seu site com zoom de no mínimo 200% e ver se seu site ainda está legível, caso não esteja, você irá falhar na [SC 1.4.4](https://www.w3.org/TR/WCAG21/#resize-text);
- Ao fazer o teste do zoom que me referi no item anterior, é importante também verificar que não ocorra perda de conteúdo, onde o usuário tenha que fazer rolagem horizontal ou por você ter aplicado `overflow: hidden` em algum lugar, caso isso ocorra você irá falhar na [SC 1.4.10](https://www.w3.org/TR/WCAG21/#reflow).
- Por isso que a responsividade é extremamente importante para ter um design acessível;

### Links extras
- [Accessibility in Resizing Text - 24 A11y](https://www.24a11y.com/2017/accessibility-resizing-text/);
- [Text Zoom Accessibility Tips](https://scottvinkle.me/blogs/blog/text-zoom);

---

## Resumo da segunda semana

A segunda semana focou para iniciantes na web, foi apresentado para nós uma plataforma chamada [MIMIC](https://mimicproject.com/), que é um ambiente de codificação online interativo.

Os vídeos ensinaram o básico de HTML, CSS e JavaScript, pelos comentários de cada aula, muita gente não tinha conhecimento dessas tecnologias e foi bem legal ver a empolgação deles.

Eu não fiz anotações da parte de codificação, pois foi a nível bem básico, se você já desenvolve para web dá para assistir os vídeos sem precisar fazer alguma anotação específica, mas recomendo assistir devido a dicas sobre acessibilidade que rolou em alguns.

