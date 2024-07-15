
<div align="center">
<a href="https://felipe0424.github.io/PortfolioDev/HTML/index.html"><img src="https://github.com/user-attachments/assets/b0cd55d7-f6f0-4cf9-a90d-db45c1832215" alt="html" width="70" align="center"></a>

# **Estrutura HTML**
</div>

## :bookmark_tabs:	Índice
* [Header (Cabeçalho)](#header-cabeçalho)
* [Footer (Rodapé)](#footer-rodapé)
* [Section (Seção)](#section-seção)
* [Nav (Menu de navegação)](#nav-menu-de-navegação)
* [Aticle (Artigo)](#aticle-artigo)
* [Aside ()](#aside-)

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
A tag `<main>` especifica o conteúdo principal do documento.
```r
<main>
  <h1>Conteúdo Principal</h1>
  <p>Este é o conteúdo principal da página.</p>
</main>
```

### 9. Figure (Figura)
A tag `<figure>` especifica conteúdo que é auto-contido, como ilustrações, diagramas, fotos, etc.
```r
<figure>
  <img src="imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem.</figcaption>
</figure>
```

### 10. Figcaption (Legenda da figura)
A tag `<figcaption>` define uma legenda para o elemento <figure>.
```r
<figure>
  <img src="imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem.</figcaption>
</figure>
```



Main (Conteúdo principal)
html
Copiar código

Figure (Figura)
html
Copiar código

Figcaption (Legenda da figura)
html
Copiar código

Esses exemplos mostram como cada tag pode ser usada para estruturar o conteúdo de uma página HTML de maneira semântica e organizada.

dentro de um main eu posso ter divs, sections e mais?
ChatGPT
Sim, dentro de um elemento <main>, você pode ter <div>, <section>, e outros elementos HTML. O <main> é usado para envolver o conteúdo principal de uma página, e pode conter uma variedade de elementos de bloco para estruturar esse conteúdo.

Aqui está um exemplo:

html
Copiar código
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
Neste exemplo, o <main> contém um <header>, várias <section>, <div>, <article>, <aside>, <figure>, e um <footer>, mostrando como é possível estruturar diversos tipos de conteúdo dentro do elemento principal da página.


2/2

e o body?
ChatGPT
O <body> é o contêiner principal para todo o conteúdo de uma página HTML. Dentro do <body>, você pode incluir qualquer elemento HTML, incluindo <main>, <header>, <footer>, <section>, <div>, <article>, <aside>, e muitos outros.

Aqui está um exemplo completo que mostra como você pode estruturar um documento HTML com todos esses elementos:

html
Copiar código
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exemplo de Estrutura HTML</title>
  <link rel="stylesheet" href="styles.css">
</head>
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
</html>
Neste exemplo, o documento HTML está estruturado da seguinte forma:

O <header> contém o título do site e o menu de navegação.
O <main> contém o conteúdo principal, incluindo uma <section>, um <div>, um <article>, um <aside>, e um <figure>.
O <footer> contém o rodapé do site.
Todos esses elementos estão aninhados dentro do <body>, que é o contêiner principal para o conteúdo da página.