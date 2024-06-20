<!--
-------------------------------------------------------------------------------
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-------------------------------------------------------------------------------
-->

<!-- .slide: class="slide-title" data-background-image="assets/background-faded.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<h3 id="talk-title">
  Limitations in paleomagnetic data and modelling techniques
and their impact on Holocene geomagnetic field models
</h3>
<p id="talk-authors">
  <a>Yago Moreria Castro</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="row talk-info">
<div class="col-large">

<i class="fa fa-calendar-alt" style="margin: 0 10px 0 0"></i>
21 de Junho de 2024
<span style="margin: 0 20px"></span>
Seminário de Introdução ao Geomagnetismo

<!-- Permission to reuse and CC-BY license logo -->
<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Sinta-se à vontade para tirar capturas de tela/compartilhar/reutilizar esta apresentação
<span style="margin: 0 20px"></span>
<a href="https://creativecommons.org/licenses/by/4.0/"><i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>CC-BY 4.0 License</a>

</div>
<div class="col-medium">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
  <a href="https://www.iag.usp.br/"><img src="assets/iag.png" alt="Instituto de Astronomia, Geofísica e Ciências Atmosféricas"></a>
  <a href="https://www.usp.br/"><img src="assets/usp.png" alt="Universidade de São Paulo"></a>
</div>
</div>

</div>
</div>

===============================================================================
# Introdução
<h2 style="text-align: justify;">Modelos Globais do Campo Geomagnético</h2>

- Modelos são criados há 400 anos (Jackson et al. 2000);

- Permitem o mapeamento da evolução da estrutura do campo na superfície do núcleo da Terra.

- Usados para análises de variações globais e regionais do campo.

<h2 style="text-align: justify">Fontes de Dados Utilizadas</h2>

- <p style="text-align: justify;">Compilações de direções e intensidades do campo obtidas de artefatos arqueológicos, lavas e sedimentos. Em comparação com dados observacionais modernos ou históricos
</p>

===============================================================================

# Desafios Encontrados

- Dados arqueomagnéticos e paleomagnéticos contêm incertezas consideráveis.

  - Essas incertezas frequentemente não são bem compreendidas.

  - As incertezas afetam não apenas os valores dos campos magnéticos, mas também suas idades.

- A distribuição global desses dados é muito heterogênea.

===============================================================================
# Metodologias de Modelagem

- Diversas metodologias de modelagem foram testadas com o objetivo dessas metodologias é avaliar as influências dessas limitações.

# Série CALSx

- Cobertura dos últimos 3, 7 e 10 mil anos;
- Uso de expansões em harmônicos esféricos e funções base temporais de splines cúbicos;
- Aplicação de métodos de regularização;
- Objetivo: encontrar os modelos de complexidade mínima que se ajustem aos dados com a precisão desejada.

===============================================================================
# Licht et al. (2013)
- <p style="text-align: justify;">Apresentou três conjuntos de modelos de campo de baixo grau harmônico esférico (truncados nos graus e ordens 5) que abrangem os últimos três milênios.</p>
- <p style="text-align: justify;">Modelos construídos a partir de conjuntos de dados arqueomagnéticos, vulcânicos e sedimentares.</p>
- <p style="text-align: justify;">Apenas características de baixo grau podem ser resolvidas com os conjuntos de dados disponíveis.</p>
- <p style="text-align: justify;">Introduziram um erro de modelagem para contabilizar coeficientes de Gauss de ordem superior não modelados.</p>
- <p style="text-align: justify;">Aumentaram o peso dos dados arqueomagnéticos em comparação com os dados sedimentares, devido a erros de cronometragem nestes últimos.</p>

===============================================================================

# Nilsson et al. (2014)
- Considera questões de datação;
- Apresentaram novos modelos de campo geomagnético cobrindo os últimos 9000 anos;
- Utilizaram uma estratégia de modelagem nova;
  - Utilização de registros sedimentares reamostrados temporalmente de forma uniforme;
- Ajustes iterativos foram realizados nos escalonamentos dos registros sedimentares, considerando as incertezas nas idades.

===============================================================================

# SHA.DIF.14k

- Pavón-Carrasco et al. (2014b) propuseram um novo modelo de campo geomagnético holocênico;
- Cobertura dos últimos 14000 anos;
- Baseado exclusivamente em dados arqueomagnéticos e de fluxo de lava;
- Evita o uso de registros sedimentares.

===============================================================================

# Dados e Estimativas de Incertezas

<div class="row">
  <div class="col">

  - CALS10k.1b foi construído usando dados paleomagnéticos que abrangem os últimos 10 mil anos.
  - A cobertura de dados é consideravelmente limitada no Hemisfério Sul;
  - Diferenças nos resultados são observadas devido ao tipo de dados utilizados (sedimentares vs arqueomagnéticos);

  </div>
  <div class="col centered">
      <img style="width: 150%;" src="assets/model-vp-vs.png">
  </div>
</div>


===============================================================================

# Dados e Estimativas de Incertezas

- O conjunto completo de dados inclui 85.500 pontos:

  - 4% sendo dados de declinação arqueomagnética;
  - 6% de inclinação arqueomagnética;
  - 5% de intensidade arqueomagnética absoluta.
  - Os dados paleomagnéticos de sedimentos contribuem com:
    - 35% para a declinação relativa;
    - 37% para a inclinação;
    - 13% para o Índice de Paleointensidade Relativa (RPI).

===============================================================================

<!-- .slide: data-background-image="assets/agu2019.svg" data-background-size="contain" data-background-opacity="0.3" data-background-color="#ffffff" -->

<div class="quote dark">

Light fade of the background with a dark quote.

</div>

===============================================================================

# Two column layout

<div class="row">
<div class="col">

## Theory

Explain something here.
This is how you make a FontAwesome list:

<ul class="fa-ul">

<li>
<span class="fa-li"> <i class="fa fa-lightbulb fa-fw"></i> </span>
Make a list with
</li>

<li>
<span class="fa-li"> <i class="fa fa-file-alt fa-fw"></i> </span>
some awesome icons
</li>

<li>
<span class="fa-li"> <i class="fa fa-users fa-fw"></i> </span>
instead of bullet points
</li>

</ul>

</div>
<div class="col tiny">

<img src="assets/halfspace-temperature.png">

Some text explaining the figure.
Maybe even a bit of maths like $\gamma$.

</div>
</div>

<div class="footnote">

Good place for a citation or image credit.
This one is by Leonardo Uieda (CC-BY).

</div>

===============================================================================

<div class="r-stretch centered">
<div>

# Multiple columns

Place as many `col`s as you want. They will have the same size.

<div class="row">
<div class="col">

Bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
bla bla.

</div>
<div class="col tiny">

<img src="assets/nbr_thomas_fire.jpg">

Bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
bla bla.

</div>
<div class="col tiny">

<img src="assets/halfspace-temperature.png">

Bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla
bla bla.

</div>
</div>

</div>
</div>
<div class="footnote">

Images by Leonardo Uieda (CC-BY).

</div>

===============================================================================

# This one has columns of different size

<div class="row">
<div class="col-large tiny">

<img style="width: 95%;" src="assets/nbr_thomas_fire.jpg">

This way the image is larger on the screen. Use it for maps or main figures.

</div>
<div class="col small">

Explain what is shown on the image.
Use the `small` class to adjust font size.

Maybe include some maths:

$ D\dfrac{\partial^4 w}{\partial x^4} = q - g (\rho_m - \rho_w) w $

</div>
</div>

===============================================================================

<div class="row">
<div class="col tiny">

<img src="assets/japan-trench-globalcmt.png">

This way the image is narrow so it should be in a smaller column.

</div>
<div class="col-medium">

# Column sizes

Columns come in 3 sizes:

1. `col`
1. `col-medium`
1. `col-large`

These are more proportions than fixed sizes.

</div>
</div>

===============================================================================

# Code

Example of using PyGMT to make a map:

<div class="row">
<div class="col-large fragment small">

This code:

```python
import pygmt

# Load built-in topography data
grid = pygmt.datasets.load_earth_relief()

fig = pygmt.Figure()
# Pseudo-color map of topography
fig.basemap(
    region=[-150, -30, -60, 60],
    projection="I-90/6i",
    frame=True,
)
fig.grdimage(grid=grid, cmap="viridis")
# Mask continents in dark grey
fig.coast(land="#333333")
# Display in Jupyter or pop-up window
fig.show()
```
</div>
<div class="col-medium fragment small">

Makes this map 👇

<img style="width: 90%" src="assets/pygmt-example.png">

</div>

===============================================================================

<!-- .slide: class="slide-contact" data-background-image="assets/contact-slide.svg" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch centered">
<div>

<i class="fas fa-comments"></i>
<br>
Contact:
<a href="https://www.leouieda.com">www.leouieda.com</a>

<i class="fab fa-github"></i>
<br>
Source code for this presentation:
<br>
[github.com/leouieda/talk-template](https://github.com/leouieda/talk-template)

<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
<br>
Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>
<div class="footnote-left dark">

The background image is a Landsat 9 scene of the city of São Paulo, Brazil,
showing the USP campus in the center.

</div>
