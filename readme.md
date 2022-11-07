<div align="center">
<h2>Estudo: Carousel Slider</h2>
<h3>Seção 7: Bootstrap 4 & Design responsivo</h3>
<p>Curso Desenvolvimento Web Completo 2022</p>
</div>

## ❓ O que é:
Um componente de slideshow para fazer um giro através de elementos (imagens ou slides de texto), como se fosse um carrosel.

## 💭 Tipos:

### A) Slider simples:

- utilizar class="carousel slide" e data-ride="carousel" na div;
- incluir mais uma div, onde será aplicada a class="carousel-inner";
- adicionar outra div com a class="carousel-item", onde adicionaremos os itens que queremos exibir -> incluir divs iguais a essa com os itens a serem exibidos;
- adicionar o atributo "active" para definif a primeira imagem a aparecer.
- obs: lembrar de adicionar a class="img-fluid" nas imagens;
- posteriormente, utilizando JavaScript e jQUery, poderemos definir o tempo e mdo de exibição das imagens.

### B) Slider com controles:

- abaixo do fechamento da div inner, adicionar um link na tag &lt;a&gt;, com a class="carousel-control-prev", e atributo data-slide="data-slide";
- no span, adicionar uma class="carousel-control-prev-icon";
- definir um id na primeira div do carousel, e nos referi-lo a ele no href da tag a;
- copiar e colar o procedimento acima, trocando "prev" por "next".

### C) Slider com controles/indicadores:

- para definir os indicadores, incluir abaixo de carousel e acima de inner;
- criar uma ol, com class="carousel-indicators";
- criar os itens (li), com data-target="id colocado na div carousel", data-slide-to="0" (e adicionar 1 a cada item) e class="active".

### D) Slider com legendas:

- criar uma div abaixo da imagem, com a class="carousel-caption", e incluir as tags de texto e conteúdos em seu interior;
- pode ser incluída também uma nova div para adicionar formatações.