---
advanced:
  css_style: ""
  css_class: ""
widget: blank
active: true
author: admin
widget_id: about
headless: true
weight: 20
title: ""
subtitle: ""
design:
  columns: "1"
  background:
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

<!DOCTYPE html>
<html>
<head>

<style>
#main { /* Contenedor para el texto y los botones */
  padding: 0px 0px;
  position: absolute;
  top: 0%;
  /* width:250px; */
  width: 100%;
  left: 0%;
  height: 800px;  
  display: center;
  align-items: center;
  text-align: center;
  border: 2px solid black;
}

#main div {
   flex: 1;
}
</style>

<style>
.button {
  background-color: #0099e6;
  position: relative;
  top: 5%;
  /* border: none; */
  border: 0px solid black;
  color: white;
  padding: 15px 32px;
  text-decoration: none;
  text-align: center;
  display: center;
  border-radius: 6px;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  transition-duration: 0.4s;
  overflow: hidden;
}

.button:hover{
    color: black;
    background-color: #FFF8C2;
}
  
.button:after {
  content: "";
  background: #ffffff;
  display: block;
  position: absolute;
  padding-top: 300%;
  padding-left: 350%;
  margin-left: -40px !important;
  margin-top: -120%;
  opacity: 0;
  transition: all 0.8s
}

.button:active:after {
  padding: 0;
  margin: 0;
  opacity: 1;
  transition: 0s
}

.button1 {width: 98%;}
.button2 {width: 98%; background-color: #009900;}
.button3 {width: 98%; background-color: #006600;}
.button4 {width: 98%; background-color: #cc9900;}
</style>
</head>

<body>

<p style="background:#FF813E; color:black; font-weight:bold; padding:15px; border:3px solid #B34F19; margin-top:20px; margin-bottom:20px; text-align:center; font-size:22px; border-radius:10px;">COVID-19: Temporalmente cerrado debido al cierre total de la Hostelería decretado por parte de la Generalitat Valenciana desde el 21 de Enero de 2021
<br/>
<a class="button button2" href="https://www.google.com/search?q=COVID-19+%2BVinar%C3%B3s&oq=COVID19+%2BVinar%C3%B3s&aqs=chrome..69i57.27050j1j15&sourceid=chrome&ie=UTF-8" target="_blank">Información</a>
</p>

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

<div id="main">
<a class="button button1" href="https://drive.google.com/drive/folders/18_9FEFRLB9bzvI3kZfulINeRh2OaOTNI?usp=sharing" target="_blank">Productos y precios</a><br>
<a class="button button2" href="tel:+34 651 94 55 87">Pedido telefónico</a><br>
<a class="button button3" href="mailto:SonDeSaboresPeruanos@gmail.com" target="_blank">Enviar eMail</a><br>
<a class="button button4" href="http://vinaros.mercadosexcelentes.com/tienda/son-sabores" target="_blank">Tienda del Mercado</a>
</div>

</body>
</html>
