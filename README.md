<img src="assets/images/readme-images/cover.png">

<h1 align="center">Site HBO Max</h1>
<h4 align="center">Clone com modificações</h4>

<p align="center">
  O projeto é um clone do site <a href="https://www.hbomax.com/br/pt">HBO Max</a>, com o intuito de reproduzir a interface, com algumas modificações, aplicando os temas abordados ao longo das aulas de CSS da plataforma da <a href="https://dio.me">Digital Innovation One</a>.
</p>
<p align="center">
  O clone do site HBO Max foi apresentado como desafio de código pela instrutura Michele Ambrosio, presente na formação
  CSS Web Developer, da Digital Inovation One.
</p>

<a href="https://dmoprates.github.io/hbomax/">
  <img src="assets/images/readme-images/cover-2.png">
</a>

## 📎 Sumário

- [✨ Features](#features)
- [📦 Temas abordados](#topics)
- [🏆 Desafio](#challenges)
- [🌈 Demonstração](#demo)
- [💻 Autora](#author)

<h2 id="features">✨ Features</h2>

- Menu de navegação
- Cabeçalho com animação gradiente
- Cards com os planos de assinatura animados
- Lista de filmes e séries disponíveis na plataforma
- Formulário de login
- Rodapé com links importantes
- UI Responsiva

<h2 id="topics">📦 Temas abordados</h2>

O projeto possui como intuito aplicar os conceitos abordados na Trilha de CSS da <a href="https://dio.me">DIO</a>, ministrada pela instrutora Michele Ambrosio.

Recursos CSS presentes no projeto:

- Fundamentos do CSS
- Grid Layout
- Flexbox
- Responsividade
- Pseudo-elementos
- Pseudo-classes
- Transformações 2D e 3D
- Transições e animações
- Tratamento de campos inválidos no formulário

<h2 id="challenges">🏆 Desafio</h2>

Como parte do desafio final da Trilha de CSS, houve a proposta de reproduzir [esse projeto](https://micheleambrosio.github.io/hbomax/), sem realizar uma consulta do código final do site, presente na branch `master` deste repositório.

Para auxiliar na reprodução, foi utilizada a branch `template-desafio`.

Foi adicionado as variáveis CSS abaixo, que contém todas as cores e gradientes utilizados no projeto:

```css
  :root {
    --primary-color: #020228;
    --secondary-color: #ff00e5;
    --tertiary-color: #b535f6;
    --btn-bg-color-gradient: linear-gradient(
      45deg,
      #9b34ef 0%,
      #490cb0 20%,
      transparent 50%
    );
    --btn-link-bg-color: #fff;
    --btn-link-color: #000;
    --card-bg-color: linear-gradient(0deg, transparent, #3b1e63);
    --divider-bg-color: linear-gradient(
      90deg,
      #5516ba,
      rgba(255, 0, 229, 0.5) 80%
    );
    --nav-bg-color: rgba(0, 0, 0, 0.3);
    --text-color: #fff;
    --link-color: #9e86ff;
    --form-bg-color: rgba(211, 211, 211, 0.06);
    --form-field-bg-color: rgba(0, 0, 0, 0.2);
    --form-field-border: 1px solid rgba(255, 255, 255, 0.7);
    --form-field-placeholder: rgba(255, 255, 255, 0.7);
    --form-field-error: rgb(255, 76, 76);

    scroll-behavior: smooth;
  }
```

*A propriedade `scroll-behavior: smooth` irá fazer com que os links que levam para uma outra sessão do site, da mesma página, faça uma transição suave ao realizar a rolagem.*

Para implementar a barra de rolagem personalizada, como no exemplo, adicione na sua folha de estilos o seguinte trecho CSS:

```css
  /* Custom Scroll */

  ::-webkit-scrollbar {
    width: 8px;
  }

  ::-webkit-scrollbar-thumb {
    background: var(--tertiary-color);
    border-radius: 10px;
  }

  ::-webkit-scrollbar-thumb:hover {
    background: var(--secondary-color);
  }
```

O resultado final do projeto deve contemplar todas as [features](#features) presentes no <a href="https://micheleambrosio.github.io/hbomax/">resultado final</a>.

As fontes utilizadas no projeto foram:

- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand)
  
```css
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;700&display=swap");
```

*Para melhor orientação, assista ao vídeo de instruções do desafio, que está disponibilizado no Módulo 3 da Trilha de CSS.*


<h2 id="demo"> Demonstração</h2>

Você pode acessar ao resultado final do projeto [clicando aqui](https://dmoprates.github.io/hbomax/).


<h2 id="author">💻 Autora</h2>
<p>
    <img align=left margin=10 width=80 src="https://avatars.githubusercontent.com/u/55519539?v=4"/>
    <p>&nbsp&nbsp&nbspMichele Queiroz Ambrosio<br>
    &nbsp&nbsp&nbsp<a href="http://instagram.com/programi_">Instagram</a>&nbsp;|&nbsp;<a href="https://github.com/micheleambrosio">GitHub</a>&nbsp;|&nbsp;<a href="https://www.linkedin.com/in/michele-ambrosio-a4899661/">LinkedIn</a>&nbsp;|&nbsp;<a href="https://www.twitch.tv/michele_ambrosio">Twitch</a></p>
</p>
<br/><br/>
<p>