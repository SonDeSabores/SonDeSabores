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
   <!-- Politica de cookies -->
   <script id="Cookiebot" src="https://consent.cookiebot.com/uc.js" data-cbid="77c7c238-0c79-4e60-8914-2b7cbf72d5a4" data-blockingmode="auto" type="text/javascript"></script>
   <meta charset="UTF-8"/>
   <title>Son de Sabores</title>
  </head>

<style>
.button {
  background-color: #0099e6;
  position: relative;
  top: 0%;
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

.button1 {width: 250px;}
.button2 {width: 250px; background-color: #006600;}
.button3 {width: 250px; background-color: #009900;}
.button4 {width: 250px; background-color: #cc9900;}
.button5 {width: 50%;   background-color: #992600;}


.hit-the-floor {
  color: #fff;
  font-size: 3em;
  line-height: 110%;
  font-weight: bold;
  font-family: Helvetica;
  text-shadow: 
    0 1px 0 #ccc, 
    0 2px 0 #c9c9c9, 
    0 3px 0 #bbb, 
    0 4px 0 #b9b9b9, 
    0 5px 0 #aaa, 
    0 6px 1px rgba(0,0,0,.1), 
    0 0 5px rgba(0,0,0,.1), 
    0 1px 3px rgba(0,0,0,.3), 
    0 3px 5px rgba(0,0,0,.2), 
    0 5px 10px rgba(0,0,0,.25), 
    0 10px 10px rgba(0,0,0,.2), 
    0 20px 20px rgba(0,0,0,.15);
}
.hit-the-floor {
  text-align: center;
}
<!-- body { -->
<!--    background-color: #f1f1f1; -->
<!-- } -->

</style>

<body>
<!-- Descomentar lo siguiente cuando sea necesario -->
<!--<p style="background:#FF813E; color:black; font-weight:bold; padding:15px; border:3px solid #B34F19; margin-top:5px; margin-bottom:5px; text-align:center; font-size:22px; border-radius:10px;">COVID-19: Temporalmente cerrado hasta que disminuya a niveles más seguros la incidencia de contagios, y con el fin de contribuir a que así sea
<br/>
<a href="https://www.google.com/search?q=COVID-19+%2BVinar%C3%B3s&oq=COVID19+%2BVinar%C3%B3s&aqs=chrome..69i57.27050j1j15&sourceid=chrome&ie=UTF-8" target="_blank"><button class="button button5">Información</button></a><br/>-->

<!-- Descomentar lo siguiente cuando sea necesario -->
<!-- Nos vemos en <span id="days"></span>d., <span id="hours"></span>h., <span id="minutes"></span>m. y <span id="seconds"></span>s. (más o menos) -->

<!-- Tienda Online Mercado (anterior): http://vinaros.mercadosexcelentes.com/tienda/son-sabores -->
</p>


<!-- <h1 style="color:white; text-align:center; font-size:400%;"> -->
<!--   <b>SON DE SABORES</b> -->
<!-- </h1> -->

<div class="hit-the-floor">SON DE SABORES</div>

<h1 style="color:white; text-align:center; font-size:150%;">
  <b>Comida Peruana en el Mercado Municipal de Vinaròs (Castellón)</b>
</h1>

<h1 style="color:white; text-align:center; font-size:100%;">
  En nuestra parada podrá encontrar comida peruana, tapas, helados, extractos de frutas naturales, batidos y zumos de frutas exóticas, postres caseros, cerveza Estrella Damm y Complot IPA, además de otras especialidades. Y todo tanto para consumir en las instalaciones del Mercado como para llevar
</h1>

<h1 style="color:white; text-align:center; font-size:130%;">
  <b>Horario temporal hasta que la incidencia <a href="https://www.google.com/search?q=%22covid-19%22+%2Bvinar%C3%B2s" style="color:#BDB76B" target="_blank">COVID-19</a> baje a niveles más seguros:<br/>
Jueves y Viernes: 10:00-14:00 y 17:30-20:00<br/>
Sábados: 10:00-14:00
</b>
</h1>

<p style="padding:15px; border:0px solid black; margin-top:10px; margin-bottom:10px; text-align:center; font-size:22px; border-radius:0px;">
<a href="https://drive.google.com/drive/folders/18_9FEFRLB9bzvI3kZfulINeRh2OaOTNI" target="_blank"><button class="button button1">Carta y precios</button></a><br/>
<a href="tel:+34 651 50 05 85"><button class="button button2">Pedido telefónico</button></a><br/>
<a href="mailto:SonDeSaboresPeruanos@gmail.com" target="_blank"><button class="button button3">Enviar eMail</button></a><br/>
<a href="https://vendaenlinia.mercatdevinaros.es/tienda/son-sabores" target="_blank"><button class="button button4">Tienda en el Mercado</button></a>
</p>

<script>
  document.addEventListener('DOMContentLoaded', () => {
  //===
  // VARIABLES
  //===
  // 15 de Marzo de 2011 a las 11:00 de la mañana
  const DATE_TARGET = new Date('15/02/2021 11:00 AM');
  // DOM for render
  const SPAN_DAYS = document.querySelector('span#days');
  const SPAN_HOURS = document.querySelector('span#hours');
  const SPAN_MINUTES = document.querySelector('span#minutes');
  const SPAN_SECONDS = document.querySelector('span#seconds');
  // Milliseconds for the calculations
  const MILLISECONDS_OF_A_SECOND = 1000;
  const MILLISECONDS_OF_A_MINUTE = MILLISECONDS_OF_A_SECOND * 60;
  const MILLISECONDS_OF_A_HOUR = MILLISECONDS_OF_A_MINUTE * 60;
  const MILLISECONDS_OF_A_DAY = MILLISECONDS_OF_A_HOUR * 24

  /* Method that updates the countdown and the sample */

  function updateCountdown() {
  // Calcs
    const NOW = new Date()
    const DURATION = DATE_TARGET - NOW;
    const REMAINING_DAYS = Math.floor(DURATION / MILLISECONDS_OF_A_DAY);
    const REMAINING_HOURS = Math.floor((DURATION % MILLISECONDS_OF_A_DAY) / MILLISECONDS_OF_A_HOUR);
    const REMAINING_MINUTES = Math.floor((DURATION % MILLISECONDS_OF_A_HOUR) / MILLISECONDS_OF_A_MINUTE);
    const REMAINING_SECONDS = Math.floor((DURATION % MILLISECONDS_OF_A_MINUTE) / MILLISECONDS_OF_A_SECOND);
    // Thanks to Pablo Monteserín (https://pablomonteserin.com/cuenta-regresiva/)

    // Render
    SPAN_DAYS.textContent = REMAINING_DAYS;
    SPAN_HOURS.textContent = REMAINING_HOURS;
    SPAN_MINUTES.textContent = REMAINING_MINUTES;
    SPAN_SECONDS.textContent = REMAINING_SECONDS;
    }

    // INIT
    updateCountdown();
    // Refresh every second
    setInterval(updateCountdown, MILLISECONDS_OF_A_SECOND);
    });

</script>

</body>

</html>
