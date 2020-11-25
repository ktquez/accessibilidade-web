# Terceira semana

## Índice
- [Tendo os usuários em mente](#tendo-os-usuários-em-mente)
- [Design participativo](#design-participativo)
- [Métodos participativos de design](#métodos-participativos-de-design)
- [Ferramentas de acessibilidade](#ferramentas-de-acessibilidade)

---

## Tendo os usuários em mente

### Resumo
Nessa aula Marcus dá mais detalhes sobre as diretrizes da WCAG, a importância dos testes com pessoas reais e cita exemplos com base nos 4 princípios (Perceptível, Operável, Compreensível e Robusto) para a criação de conteúdo da web acessível

### Anotações
- A WCAG são padrões desenvolvidos e mantidos pela W3C WAI (<span lang="en">Web Acessibility Initiative</span>), são padrões internacionais que todos os sites públicos atender;
- Apesar do uso de ferramentas de avaliação como aXe, Wave, Tenon e etc, ajudar você a identificar diversas falhas nos critérios, ainda sim é extremamente importante ir mais a fundo e fazer testes com pessoas reais;
- **Perceptível (<span lang="en">Perceivable</span>):** Significa que os usuários devem ser capazes de perceber a informação apresentada, por exemplo, Fornecer um texto alternativo para um conteúdo não textual, legendas e transcrição para vídeos, rotular ícones, inputs, botões links e auto-descritívos, construir um layout linear e organizado, autocomplete e etc.
- **Operável (<span lang="en">Operable</span>):** Significa que os usuários devem ser capazes de operar a interface, por exemplo, todas as funcionalidades devem ser possíveis de operar usando o teclado, construir layouts simples, estruturar o conteúdo de forma semântica, grandes áres para click e etc.
- **Compreensível (<span lang="en">Understandable</span>):** Significa que os usuários devem ser capazes de entender as informações, por exemplo, manter o texto o mais legível possível, idioma simples (sem muitas gírias ou expressões de linguagem), tornar as interações previsíveis e etc.
- **Robusto (<span lang="en">Robust</span>):** Significa que os usuários devem ser capazes de acessar o conteúdo conforme as tecnologias avançam, por exemplo, certifique-se de que o site continue funcionando, não use tecnologia que possam excluir pessoas (como pacotes de terceiros que não são acessíveis), use atributos ARIA quando o HTML nativo não for o suficiente, efetue testes de validação para manter o seu HTML sem erros.

### Links extras
- [Understanding the Four Principles of Accessibility](https://www.w3.org/WAI/WCAG21/Understanding/intro#understanding-the-four-principles-of-accessibility)

---

## Design participativo
### Resumo
Originalmente chamado de Design cooperativo, e atualmente co-design, é um método que busca envolver todos os interessados no processo de design para ajudar a garantir que o resultado seja preciso e utilizável.

### Anotações
- Facilita o compartilhanto de experiências entre o designer e seu conhecimento do que é possível, e o usuário e seu conhecimento do que é necessário;
- Design participativo para desenvolvimento de software acessível trata de envolver pessoas com deficiência como especialistas em suas próprias experiências, fazendo com que as necessidades sejam mais bem atendidas; 
- As diretrizes de acessibilidade pode ajudar a atender requisitos comuns em cenários já conhecidos, mas quando surgem novas situações envolvê-los é a melhor forma de garantir que o software permaneça acessível;
- O design participativo nos permite envolver as perspectivas das pessoas com necessidades de acessibilidade desde o início do design e garantir que essas perspectivas sejam ouvidas;
- A colaboração é mais do que apenas explorar o conhecimento das partes interessadas, mas também trata-se de descobrir perspectívas únicas e coletivas, o que torna vital criamos juntos;
- O Design participativo não é uma consulta ou aprovação do projeto pelo usuário final, pelo contrário, a sua participação deve ser plena no processo e suas constribuições devem ser igualmente consideradas.

### Links extras
- [Design participativo - Wikipédia](https://en.wikipedia.org/wiki/Participatory_design)
- [Co-design: uma força poderosa para criatividade e colaboração](https://medium.com/@thestratosgroup/co-design-a-powerful-force-for-creativity-and-collaboration-bed1e0f13d46)

---

## Métodos participativos de design
### Resumo
Como implementar o design participativo, armadilhas comuns e práticas recomendadas.

### Anotações
- **Cooperação:** O objetivo do design participativo é o compartilhamento de experiência entre ambos (design e usuário), isso não significa que o usuário irá liderar as decisões, como foi falado anteriormente as contribuições devem ser "consideradas" igualmente.
- **Suposições:** É possível que no processo de mediação o viés limite o espaço de opções que podem ser discutidas, ocasionando descarte de possíveis soluções mais efetivas.
- **Processo:** É mais efetivo quando há envolvimento do usuário no processo o mais cedo possível, pois quando o aplicativo já está em desenvolvimento pode limitar o espaço de possibilidades no que já foi desenvolvido.

---

## Ferramentas de acessibilidade
### Resumo
Foi solicitado que usássemos alguma ferramenta de acessibilidade, como por exemplo, um leitor de tela, ferramenta de ampliação de tela ou fonte de dislexia, para temos a experiência de usar a web em outra perspectiva.

### Anotações
- **Leitores de tela:** São ferramentas que traduzem o texto escrito em uma página em conteúdo de fala ou braille.
  - Normalmente para fazer alguns testes eu utilizo a combinação ([NVDA](https://www.nvaccess.org/download/) + Chrome) ou ([Extensão para chrome ChromeVox](https://chrome.google.com/webstore/detail/chromevox-classic-extensi/kgejglhpjiefppelpmljglcjbhoiplfn/related?hl=en));
  - Existem outros softwares, por exemplo, [JAWS](https://www.freedomscientific.com/products/software/jaws/), [Narrator](https://support.microsoft.com/en-us/windows/complete-guide-to-narrator-e4397a0d-ef4f-b386-d8ae-c172f109bdb1),	[TalkBack Android](https://support.google.com/accessibility/android/answer/6007100?hl=en&ref_topic=3529932),	[VoiceOver iOS](https://support.apple.com/guide/iphone/turn-on-and-practice-voiceover-iph3e2e415f/ios), [VoiceOver macOS](https://help.apple.com/voiceover/mac/10.15/);

- **Ferramenta de ampliação:** São ferramentas que permitem que o usuário amplie uma página ou parte dela e geralmente são úteis para pessoas com deficiência visual.
  - As ferramentas estão disponíveis por padrão no [Windows](https://support.microsoft.com/en-us/windows/use-magnifier-to-make-things-on-the-screen-easier-to-see-414948ba-8b1c-d3bd-8615-0e5e32204198) e [Mac](https://mcmw.abilitynet.org.uk/macos-mojave-magnifying-screen), e na maioria das máquinas Linux no pacote [Magnus](https://kryogenix.org/code/magnus/)

- **Fontes amigáveis para dislexia:** Existem fontes projetadas especificamente para serem legíveis por usuários disléxicos, pois geralmente quando usamos determinadas fontes ou estilos específicos dificultamos a leitura dos usuários com dislexia.
  - Atualmente nos sites que desenvolvo, disponibilizo uma forma para que o usuário altere a fonte dos posts para a [<span lang="en">Open Dyslexic font</span>](https://opendyslexic.org/);
  - Também existem extensões para navegadores desktop e mobile, por exemplo, [<span lang="en">OpenDyslexic Font for Chrome</span>](https://chrome.google.com/webstore/detail/opendyslexic-font-for-chr/cdnapgfjopgaggbmfgbiinmmbdcglnam?hl=en) e [<span lang="en">Mobile Dyslexic for Firefox</span>](https://addons.mozilla.org/en-US/firefox/addon/mobile-dyslexic/?src=search), ambas disponibilizada gratuitamente;

- As ferramentas de acessibilidade ajuda muito nos teste, mas existem alguns problemas, por exemplo:
  - Nas redes sociais o uso de emoji é confuso para todo tipo de usuário, porém se torna mais ilegível usando leitor de tela;
  - As ferramentas de ampliação costumam dificultar a compreensão do texto no contexto ou sua localização na página;

### Links extras
- [Screen Reader Keyboard Shortcuts and Gestures - Deque](https://dequeuniversity.com/screenreaders/)
- [Improving Your Tweet Accessibility - #emoji - Adrian Roselli](https://adrianroselli.com/2018/01/improving-your-tweet-accessibility.html#Emoji)
- **Vídeo** [Como você pode ler emojis se for cego?](https://www.youtube.com/watch?v=PpqLnO-1Kxw&ab_channel=SenseCharity)
