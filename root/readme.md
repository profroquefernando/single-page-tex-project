## Elementos Semânticos

![semantic_web](https://www.w3schools.com/html/img_sem_elements.gif)

## Estrutura de pastas

    └── root/
        ├── images
        ├── pages
                sobre.html
        ├── samples/
        │   └── test
        ├── src/
        │   └── css
        ├── index.html
        └── readme-md

### Resolução de tela: 1920 X 1080

-   Pasta - R$ 56
-   Filé Mignon R$ 42
-   Spaghetti R$ 32
-   Sopa com vegetais R$ 16
-   Noodles R$ 21
-   Frango R$ 28
-   Pizza vegetariana R$ 45
-   Salmão R$ 84
-   Penne R$ 65

## Microdados

-   Parte do padrão HTML. Mecânismos de pesquisa e rastreadores consomem os dados com mais eficiência.-
-   Servem para aninhar metadados em conteúdo existente em páginas WEB. (Microdata,RDFa,JSON-LD)

### Microdata

<div itemscope itemtype="https://schema.org/SoftwareApplication">
  <span itemprop="name">Angry Birds</span> -

REQUIRES <span itemprop="operatingSystem">ANDROID</span><br>

  <link itemprop="applicationCategory" href="https://schema.org/GameApplication"/>

  <div itemprop="aggregateRating" itemscope itemtype="https://schema.org/AggregateRating">
    Pontuação:
    <span itemprop="ratingValue">4.6</span> (
    <span itemprop="ratingCount">8864</span> avaliações )
  </div>

  <div itemprop="offers" itemscope itemtype="https://schema.org/Offer">
    Preço: $<span itemprop="price">R$ 10.00</span>
    <meta itemprop="priceCurrency" content="USD" />
  </div>
</div>

## RDFa

<!DOCTYPE html>
<html lang="pt">
  <head>
    <title>Exemplo de documento</title>
  </head>
  <body vocab="http://schema.org/" >
    <p typeof="Blog" >
      Bem-vindo ao <a property="url" href="http://texpersts.com.br/blog">blog da T.EX</a>.
    </p>
  </body>
</html>

## JSON-LD (Link Data)

<html>
  <head>
    <title>Bolo de Café</title>
    <script type="application/ld+json">
    {
      "@context": "https://schema.org/",
      "@type": "Recipe",
      "name": "Bolo de Café",
      "author": {
        "@type": "Person",
        "name": "Fernando M. Sousa"
      },
      "datePublished": "2018-03-10",
      "description": "Este bolo é perfeito para sua festa.",
      "prepTime": "PT20M"
    }
    </script>
</head>
    <body>
      <h2>Bolo de Café</h2>
      <p>
        <i>por Fernando M.Sousa, 10-06-2022</i>
      </p>
      <p>
        Este bolo é perfeito para sua festa.
      </p>
      <p>
        Preparação: 20 minutos
      </p>
    </body>
</html>

[cooking](https://giphy.com/gifs/masterchef-chefs-home-cooks-masterchef-season-7-3oEjHC7al4GfnudR7y)

# Cores

W3Schools (color HTML)

<h1 style="color:green">Names</h1>

<h1 style="color:#ff0000">Hexadecimal</h1>
<h1 style="color:#0000ff">Hexadecimal</h1>
<h1 style="color:#0f0">Hexadecimal</h1>
<h1 style="color:#808080">Hexadecimal</h1>
<h1 style="color:rgb(180,200,84)">RGB</h1>
<h1 style="color:hsl(110,80%,40%)">HSL</h1>

<br/>
R     G     B<br/>
0     0     0 = preto<br/>
255   255   255 = branco<br/>
255   0     0 = vermelho<br/>
+++++++++++++++<br/>
FF    0     0 = vermelho<br/>

0123456789ABCDEF

<hr />

## LENGTH CSS

---

### px

> Medida angular
> ![](../images/../root/images/vision_angle.jpg)

### cm, in, mm

Mapeados para pixels

> 1cm == 37.8px <br />
> 1mm == 0.1cm == 3.78px <br />

## 1in == 96px

### em

> 1em == 16px == 12pt <br />
> font-size:14px <br />
> div > font-size:1.2em
> div > div > div (font-size) <br />
> 1ª = 16.8px > 2ª = 12.16px > 3ª = 24.192px

---

### rem

> Base no root (html)

---

### pt (print)

> 1pt == 1/72 polegadas

---

### pc (print)

> 1pc == 12pt

---

### %

> img width=50% relativo ao elemento que ela está contida<br />
> height (atenção com %)

---

### vh, vw

> 1vh == 1% da altura da janela de visualização<br />
> 1vw == 1$ da largura da janela de visualização<br />

---

### vmax, vmin

![](../images/../root/images/svg/vcompare.svg)

---

## TEXT

> color (names,hexa,rgb,hsl,gradient)[]

---

> ALIGN

-   text-align [x]
-   text-aling-last [x]
-   direction [x]
-   vertical-align [x]

---

> DECORATION

-   line [x]
-   color [x]
-   style [x]
-   thickness [x]
-   decoration [x]

> SPACING

-   text-indent [x]
-   letter-spacing [x]
-   line-height [x]
-   word-spacing [x]
-   white-space [x]

> TRANSFORM

-   uppercase [x]
-   lowercase [x]
-   capitalize [x]

---

# SELETORES

## Simples

-   Nomes, ids e classes

## Combinações

-   Relação entre elementos
-   Adjacente (+), Descendente ( ) <br />
-   ## Seletor filho (>), Seletor vizinho (~)

## Pseudo Elements

-   Partes de um elemento

::first-letter <br />
::marker <br />

> ---

## Pseudo Class

-   Estado de um elemento

:hover <br />
:checked<br />
:active

> ---

## Atributos

-   Atributos e valores de um elemento
    > input[type=text]

> ---

## Prefixo dos Browsers

-   webkit [-webkit] chrome, safari, opera+
-   moz [-moz] firefox
-   o [-o] opera-
-   ms [-ms] internet explorer, edge

## Fontes

> Com Serifa (serif)

---

<p style="font-size:40px;font-family:'times new roman'">Lorem Ipsum</p>

-   Georgia
-   Garamond

---

> Sem Serifa (sans-serif)

<p style="font-size:40px;font-family:'Arial'">Lorem Ipsum</p>

-   Verdana
-   Helvética

> Monoespaçadas (letras com a mesma largura fixa)

-   Courier New
-   Lucida Console

> Cursivas (imitam a escrita humana)

-   Lucida Handwriting
-   Brush Script MT
-   > Fantasia
-   Copperplate
-   Papyrus

---

# BOX MODEL

![](../images/png/../../root/images/png/box_model.png)

> width | height

> max-width | min-width

> margin: 0 0 0 0 (top right bottom left)

> padding: 0 0 0 0 (top right bottom left)

> border-width: 0 0 0 0 (top right bottom left)

> border-radius: 0 0 0 0 (top right bottom left)

## Variações

> margin:0 (todos os lados)

> margin: 0 0 (top/bottom right/left)

<p>BASE</p>
<div style="
border:outset 13px #fff;
min-width:200px;
margin:30px auto">
<div
style="width:70%;
border:4px solid #fff;
border-radius:12px 0 12px 0;
text-align:right;
margin:10px auto;
padding:0 10px 0 0;
">Lorem Ipsum</div>
</div>
<p>NEXT</p>

# POSITION

<div style="
border:solid 2px red;
min-width:200px;
position:relative;
height:250px;
margin:30px auto">
    <div style="
    border:solid 1px #fff;
    position:relative;
    width:80%;
    height:200px;
    margin:30px auto">
        <div
        style="width:40%;
        border:1px solid #fff;
        text-align:right;
        position:sticky;
        background-color:#fff;
        top:0;
        color:#000;
        padding:0 10px 0 0;
        ">Lorem Ipsum</div>
        </div>
</div>

---

>## position: sticky
>## display: none | inline-block | block
>## float
>## opacity

---

# GRID

<div style="
outline:dashed 1px yellow;
border:solid 2px red;
min-width:200px;
position:relative;
height:250px;
margin:30px auto">
    <div style="
    border:solid 1px #fff;
    width:80%;
    height:200px;
    margin:30px auto">
        <div
        style="width:40%;
        border:1px solid #fff;
        text-align:right;
        position:absolute;
        background-color:#fff;
        top:0;
        color:#000;
        padding:0 10px 0 0;
        ">Lorem Ipsum</div>
        </div>
</div>

#

<table>
<tr>
<th>Pratos</th>
<th>Sobremesas</th>
<th>Acompanhamentos</th>
<th>Bebidas</th>
</tr>
<tr>
<td>Picanha</td>
<td>Sorvete</td>
<td>Salada</td>
<td>Água com gás</td>
</tr>
<tr>
<td>Pasta Italiana</td>
<td>Bolo de Limão</td>
<td>Fritas</td>
<td>Água sem gás</td>
</tr>
<tr>
<td>Brasileira</td>
<td>Bolo de Laranja</td>
<td>Bacon</td>
<td>Chá Inglês</td>
</tr>
<tr>
<td>Feijoada</td>
<td>Pêssego em Calda</td>
<td>Macaxeira</td>
<td>Café Espresso</td>
</tr>
<tr>
<td>Baião de Dois</td>
<td>Bomba de Chocolate</td>
<td>Pirão</td>
<td>Suco de Graviola</td>
</tr>
</table>


# BootStrap

>Extra Small
- (< 576px = 100% )
  
>Small - sm
- ( > 576px = 540px )

>Medium - md
- (> 768px = 720px )

>Large - lg
- (> 992px = 960px)

>Extra Large
- ( > 1200px = 1440px )

>XXLarge
- ( >1400px = 1320px )



# Responsive Design


>Mobile (portrait)
- 320
- 375
- 414

>Mobile (landscape)
- 568
- 667
- 736
- 812

>Tablet (potrait)
- 768
- 834

>Tablet (landscape)
- 1024
- 1112

>Laptop 
- 1366
- 1440

>Desktop
- 1680
- 1920
- 2048
---
## Fluid Grids
---
Linhas e colunas que se ajustam mediante os breakpoints

---

## Breakpoints
Pontos de tamanho tela especificados no css associados a janela de visualização (@media)

---

## Flexible Images
Verificar o redimensionamento das imagens que é feito em porcentagem.

---
## Media Querie

Especificacões CSS que contém as informações sobre a janela de visualização
---
## Viewport

        <meta name="viewport" content="width=device-width, initial-scale=1.0" />

---
## Overflow

Elementos de tela que  estão fora do layout, ou parcialmente fora do layuot

---
## Fixed Size
Utilizam pixels como largura ou altura.

---

## Relative Size
Utilizam medidas como rem ou %

---

## Mobile First
Técnica de layout ue primeiro analisa telas menores, para depois pensar em telas mais largas

---
## Hamburguer Menu

<div style="background-color:#fff;width:8%;height:30px">
<img src="images/png/hamburger_icon.png">
</div>

---
---

# Box Sizing

>Width = Padding+Width+Border

>Height = Padding+Height+Border

<div style="
text-align:center;
width:200px;
background-color:orange;
border:none;">
Lorem Ipsum
</div><hr />

<div style="
text-align:center;
box-sizing:border-box;
width:200px;
border:3px solid #fff">
Lorem Ipsum
</div><hr />

<div style="
box-sizing:border-box;
text-align:center;
width:200px;
padding:5px;
border:2px solid #fff">
Lorem Ipsum
</div>
 <hr style="clear:left" />

---

# DropDown Menu
<style>
  .drop-bt{
    background-color:#4CAF50;
    color:#fff;
    border:none;
    padding:14px;
    cursor:pointer;
    width:100%;
  }
  .drop-bt:hover + div,.drop-content:hover{
    display:block;
  }
  .drop{
    position:relative;
    display:inline-block;
    margin:50px 0;
    min-width:160px
  }
  .drop-content{
    display:none;
    position:absolute;
    min-width:160px;
    box-shadow:8x 16px 0 rgba(0,0,0,0.2);
    background-color:#f9f9f9
  }
  .drop-content a{
    display:block;
    background-color:#eee;
  }
  .drop-content a:hover{
    background-color:#fff;
    text-decoration:none;
  }
</style>

<div class="drop">
  <button class="drop-bt">Menu DropDown</button>
  <div class="drop-content">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
</div>

<div style="clear:both;margin:50px 0"></div>

--- 
---

# Paginação
<style>
  .pag a{
    padding:0.5rem 1rem;
    color:#fff;
    display:inline-block;
  }
  .active{
    background:#f44336;
  }
  .active:hover{
    background-color:#fff;
    color:#000;
  }
</style>
<div class="pag">
  <a href="#">&laquo;</a>
  <a href="#">1</a>
  <a href="#">2</a>
  <a class="active" href="#">3</a>
  <a href="#">4</a>
  <a href="#">5</a>
  <a href="#">6</a>
  <a href="#">&raquo;</a>
</div>

<div style="clear:both"></div>

---
<div style="clear:both"></div>

# FLOAT

<div>
<img 
style="float:left;padding:0 12px 0 0"
src="images/baked-salmon-garnished-with-asparagus-and-tomatoes-with-herbs.jpg" width="60%" /> 
<p>
Lorem ipsum dolor sit amet consectetur
adipisicing elit. Id voluptates dolores
autem dolorem quos quis nulla illum pariatur
magnam.
</p>
</div>
<hr />
<div>
<img 
style="float:right;padding:0 0 0 12px"
src="images/baked-salmon-garnished-with-asparagus-and-tomatoes-with-herbs.jpg" width="60%" /> 
<p>
Lorem ipsum dolor sit amet consectetur
adipisicing elit. Id voluptates dolores
autem dolorem quos quis nulla illum pariatur
magnam.
</p>
</div>
<hr />
<div>
<button
style="float:left;
padding:2%"
>Lorem Isum</button>
<button 
style="float:right;
padding:2%"
>Lorem Isum</button>
</div>

<hr style="clear:both;margin:20px 0" />

<div style="clear:both">
<button
style="float:left;
padding:2%"
>Lorem Isum</button>
<button 
style="float:left;
padding:2%"
>Lorem Isum</button>
</div>
<button
style="float:left;
padding:2%"
>Lorem Isum</button>
<button 
style="float:left;
padding:2%"
>Lorem Ipsum</button>
</div>

<hr style="clear:both;margin:20px 0" />

