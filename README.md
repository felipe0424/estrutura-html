
<div align="center">
<a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b0cd55d7-f6f0-4cf9-a90d-db45c1832215" alt="html" width="70" align="center"></a>

# **Estrutura HTML**
### `Principais tags da estrutura de uma página HTML`
</div>

## :bookmark_tabs:	Índice
* [1. Div (Divisão ou seção)](#1-div-divisão-ou-seção)
* [2. Header (Cabeçalho)](#2-header-cabeçalho)
* [3. Footer (Rodapé)](#3-footer-rodapé)
* [4. Section (Seção)](#4-section-seção)
* [5. Nav (Menu de navegação)](#5-nav-menu-de-navegação)
* [6. Aticle (Artigo)](#6-article-artigo)
* [7. Aside (Conteúdo)](#7-aside-conteúdo-relacionado)
* [8. Main (Conteúdo principal)](#8-main-conteúdo-principal)
* [9. Body (Conteúdo de uma página HTML)](#9-body)
* [10. Figura](#10-figure-figura)
* [11. Legenda da Figura](#11-figcaption-legenda-da-figura)

## :computer:	Ferramentas e linguagens utilizadas no desenvolvimento
<div align="auto">
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b0cd55d7-f6f0-4cf9-a90d-db45c1832215" alt="html" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/6bcb928a-c5f9-4030-9258-3cacee37f553" alt="css" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/64486d67-8973-4b62-bdfc-212cf9f16709" alt="md" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/d3813ef4-1409-40c9-9bfb-6e988f79b2c8" alt="Git" width="50"></a>
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b03adba8-e155-4555-8737-2afaf449620d" alt="Node" width="50"></a>
</div>

## :books:	Conteúdo

### 1. Div (Divisão ou seção)
A tag `<div>` é usada como um contêiner genérico para agrupar elementos de bloco para fins de estilo (usando CSS) ou scripting (usando JavaScript).
```r
<div class="container">
  <p>Este é um parágrafo dentro de um div.</p>
</div>
```

### 2. Header (Cabeçalho)
A tag `<header>` representa um cabeçalho de introdução ou grupo de navegação.
```r
<header>
  <h1>Meu Site</h1>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">Sobre</a></li>
      <li><a href="#contact">Contato</a></li>
    </ul>
  </nav>
</header>
```

### 3. Footer (Rodapé)
A tag `<footer>` define o rodapé para um documento ou seção.
```r
<footer>
  <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
</footer>
```

### 4. Section (Seção)
A tag `<section>` define uma seção em um documento.
```r
<section>
  <h2>Seção 1</h2>
  <p>Conteúdo da seção 1.</p>
</section>
```

### 5. Nav (Menu de navegação)
A tag `<nav>` define um conjunto de links de navegação.
```r
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">Sobre</a></li>
    <li><a href="#services">Serviços</a></li>
    <li><a href="#contact">Contato</a></li>
  </ul>
</nav>
```

### 6. Article (Artigo)
A tag `<article>` define conteúdo independente e isolável que é relevante dentro do contexto de um documento.
```r
<article>
  <h2>Título do Artigo</h2>
  <p>Este é o conteúdo do artigo.</p>
</article>
```

### 7. Aside (Conteúdo relacionado)
A tag `<aside>` é usada para definir um conteúdo adicional que pode ser considerado separado do conteúdo principal.
```r
<aside>
  <h3>Informações Adicionais</h3>
  <p>Conteúdo relacionado ao artigo principal.</p>
</aside>
```

### 8. Main (Conteúdo principal)
Neste exemplo, o `<main>` contém um `<header>`, várias `<section>`, `<div>`, `<article>`, `<aside>`, `<figure>`, e um `<footer>`, mostrando como é possível estruturar diversos tipos de conteúdo dentro do elemento principal da página.
```r
<main>
  <header>
    <h1>Título Principal</h1>
  </header>
  
  <section>
    <h2>Seção 1</h2>
    <p>Conteúdo da seção 1.</p>
  </section>

  <div class="container">
    <h2>Divisão</h2>
    <p>Conteúdo dentro de um div.</p>
  </div>
  
  <article>
    <h2>Artigo</h2>
    <p>Este é o conteúdo do artigo.</p>
  </article>

  <aside>
    <h3>Informações Adicionais</h3>
    <p>Conteúdo relacionado ao artigo principal.</p>
  </aside>
  
  <figure>
    <img src="imagem.jpg" alt="Descrição da imagem">
    <figcaption>Legenda da imagem.</figcaption>
  </figure>

  <footer>
    <p>Rodapé do conteúdo principal.</p>
  </footer>
</main>
```
### 9. Body
O `<body>` é o contêiner principal para todo o conteúdo de uma página HTML. Pode incluir qualquer elemento HTML, incluindo `<main>`, `<header>`, `<footer>`, `<section>`, `<div>`, `<article>`, `<aside>`, e muitos outros.

`<header>` contém o título do site e o menu de navegação.
`<main>` contém o conteúdo principal, incluindo uma `<section>`, um `<div>`, um `<article>`, um `<aside>`, e um `<figure>`.
`<footer>` contém o rodapé do site.

Todos esses elementos estão aninhados dentro do `<body>`, que é o contêiner principal para o conteúdo da página.
```r
<body>
  <header>
    <h1>Meu Site</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">Sobre</a></li>
        <li><a href="#services">Serviços</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Seção 1</h2>
      <p>Conteúdo da seção 1.</p>
    </section>

    <div class="container">
      <h2>Divisão</h2>
      <p>Conteúdo dentro de um div.</p>
    </div>
    
    <article>
      <h2>Artigo</h2>
      <p>Este é o conteúdo do artigo.</p>
    </article>

    <aside>
      <h3>Informações Adicionais</h3>
      <p>Conteúdo relacionado ao artigo principal.</p>
    </aside>
    
    <figure>
      <img src="imagem.jpg" alt="Descrição da imagem">
      <figcaption>Legenda da imagem.</figcaption>
    </figure>
  </main>

  <footer>
    <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
  </footer>
</body>
```

### 10. Figure (Figura)
A tag `<figure>` especifica conteúdo que é auto-contido, como ilustrações, diagramas, fotos, etc.
```r
<figure>
  <img src="imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem.</figcaption>
</figure>
```

### 11. Figcaption (Legenda da figura)
A tag `<figcaption>` define uma legenda para o elemento `<figure>`.
```r
<figure>
  <img src="imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem.</figcaption>
</figure>
```
## :telephone_receiver:	Contato
Para saber mais sobre meus trabalhos, entre em contato comigo através do <a href="https://www.linkedin.com/in/jfeliperamos/">LinkedIn</a> ou visite meu <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html">GitHub.</a> 

<div align=center>
    <a href="https://www.linkedin.com/in/jfeliperamos/">
        <img src="https://github.com/user-attachments/assets/0350e54a-100e-4273-aa51-81aa9fce3d79" alt="LinkedIn" width="25">
    </a> 
    <a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html">
        <img src="https://github.com/user-attachments/assets/3fda6271-fd40-4485-bb7c-60b927b9feae" alt="GitHub" width="25">
    </a>
</div>


> [!WARNING]
> Este código é disponibilizado exclusivamente para fins de estudo e aprendizado. A reprodução total ou parcial deste código, sem autorização prévia, é expressamente proibida. A utilização deste código em projetos comerciais, distribuição não autorizada ou qualquer outro uso que não seja educativo pode resultar em sanções legais. Ao utilizar este código, você concorda em respeitar os termos de uso e a propriedade intelectual do autor.