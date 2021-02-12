---
advanced:
  css_style: ""
  css_class: ""
widget: blank
widget_id: about
headless: true
author: 'admin'
weight: 20
title: ""
subtitle: ""
active: true
design:
  columns: "1"
  background:
    # gradient_start: DarkGreen
    # gradient_end: ForestGreen
    # text_color_light: true
    text_color_light: false
    image_darken: 0
    image: sds-portada-01.jpg
  spacing:
    padding:
      - 20px
      - "0"
      - 20px
      - "0"
---

<html>
<body>

<h1 style="color:white; text-align:center; font-size:400%;">
  <b>SON DE SABORES</b>
</h1>

<h1 style="color:white; text-align:center; font-size:150%;">
  <b>Comida Peruana en el Mercado Municipal de Vinaròs (Castellón)</b>
</h1>

<h1 style="color:white; text-align:center; font-size:100%;">
  En nuestra parada podrá encontrar comida peruana, tapas, helados, extractos de frutas naturales, batidos y zumos de frutas exóticas, postres caseros, cerveza Estrella Damm y Complot IPA, además de otras especialidades. Y todo tanto para consumir en las instalaciones del Mercado como para llevar
</h1>

<br/>
<br/>

<div class="content">  
  <div class="flex-parent jc-center">
    <button type="submit">Inline-block button</button>
  </div>
    
  <div class="flex-parent jc-center">
<button type="submit" class="block magenta">Block button</button>
  </div>  
</div>

$bodyBg: #030018;
$dkGray: #1E1F26;

$brightAqua: #00FFED;
$medBlue: #2245AD;

$dkBluePurple: #170F50;
$purple: #292477;

$warmDarkWine: #850178;
$magenta: #AD2266;
$brightPink: #FFA4F9;

$medRed: #a90e0e;
$orange: #fa952a;
$yellow: #f7ea1c;
$green: #13693B;

@mixin bgGradient($color){
  background-image: linear-gradient(lighten($color, 12%) 0%, $color 70%);  
}
  
html {
  box-sizing: border-box;
  font-size: 100%;
}

*, *:before, *:after {
  box-sizing: inherit;
}

body {
  background: $dkGray;
  color: #ffffff;
  font-family: 'Roboto', sans-serif;
  padding: 20px;
  max-width: 700px;
}

div {
  padding: 20px; // 15px 25px;
  font-size: 1.5rem;
  border-radius: 10px;  
  overflow: hidden;
  margin: 0;
  min-height: 150px;  
  font-size: 1.25rem;
  line-height: 1.5;
  letter-spacing: 3px;
  //text-transform: uppercase;
  font-weight: normal;
}

.purple {
  background-color: $dkBluePurple;
  @include bgGradient($dkBluePurple);
}

.wine {
  background-color: $warmDarkWine;
  @include bgGradient($warmDarkWine);
}

.green {
  background-color: $green;
  @include bgGradient($green);
}

.aqua {
  background-color: $brightAqua;
  @include bgGradient($brightAqua);  
  color: $dkGray;
}

.blue {
  background-color: $medBlue;
  @include bgGradient($medBlue);  
}

.red {
  background-color: $medRed;
  @include bgGradient($medRed);  
}

.orange {
  background-color: $orange;
  @include bgGradient($orange);  
}

.yellow {
  background-color: $yellow;
  @include bgGradient($yellow);  
}

.pink {
  background-color: $brightPink;
  @include bgGradient($brightPink);  
  color: $dkGray;
}

.magenta {
  background-color: $magenta;
  @include bgGradient($magenta);  
}

.grid-parent {
  display: grid;
}
.flex-parent {
  display: flex;
  min-height: 0px;
}

.jc-center {
  justify-content: center;
}

.content {
  font-size: 2rem;
  border: 2px solid $magenta;
  padding: 20px;
  margin-bottom: 40px;
}

.text-center {
  text-align: center;
}

button {
  border: 2px solid #ffffff;
  border-radius: 8px;
  background: $medBlue;
  padding: 15px 40px;
  color: #ffffff;
  font-size: 1.25rem;
  cursor: pointer;
  transition: all 150ms ease-in-out;
  
  &:hover {
    background: darken($medBlue, 8%);  
  }
  
  &.block {
    display: block;
    width: 200px;
    color: #000000;
    
    &:hover {
      background: $magenta;
    }
  }
  
  &.margin-auto {
    margin: 0 auto;    
  }
  
  &.margin-right {
    margin-right: 20px;
  }
}





<p style="font-family:lato,arial">
<a class="boton_personalizado1" href="https://drive.google.com/drive/folders/18_9FEFRLB9bzvI3kZfulINeRh2OaOTNI?usp=sharing" target="_blank">Productos y precios</a>
<br/>
<a class="boton_personalizado2" href="tel:+34 651 94 55 87">Pedido telefónico</a>
<br/>
<a class="boton_personalizado3" href="mailto:SonDeSaboresPeruanos@gmail.com" target="_blank">Enviar eMail</a>
<br/>
<a class="boton_personalizado1" href="https://drive.google.com/file/d/1uZ6UECWq5DOgjf6Bd5E0aEViQpXC211Q/view" target="_blank">Ir a la Tienda del Mercado</a>
</p>

<style type="text/css">
  .boton_personalizado1{    
    text-decoration: none;
    padding: 6px;
    font-weight: 600;
    font-size: 20px;
    color: white;
    background-color: #C7E8F7;
    border-radius: 6px;
    border: 2px solid #000000;
    display: center;
    justify-content: center;
    align-items: center;
  }
  .boton_personalizado1:hover{
    color: #C7E8F7;
    background-color: #FFF8C2;
  }

  .boton_personalizado2{
    text-decoration: none;
    padding: 6px;
    font-weight: 600;
    font-size: 20px;
    color: #ffffff;
    background-color: #62CC80;
    border-radius: 6px;
    border: 2px solid #000000;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .boton_personalizado2:hover{
    color: #62CC80;
    background-color: #FFF8C2;
  }

  .boton_personalizado3{
    text-decoration: none;
    padding: 6px;
    font-weight: 600;
    font-size: 20px;
    color: #ffffff;
    background-color: #84A5AE;
    border-radius: 6px;
    border: 2px solid #000000;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .boton_personalizado3:hover{
    color: #84A5AE;
    background-color: #FFF8C2;
  }
</style>

</body>
</html>
