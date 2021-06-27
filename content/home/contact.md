---
widget: contact
widget_id: contact
headless: true
weight: 130
title: Contacto
subtitle: null
content:
  autolink: true
  form:
    provider: netlify
    formspree:
      ? id
    netlify:
      captcha: false
design:
  columns: "2"
---

- Ver en [*Google Maps*](https://www.google.com/maps/place/Son+de+Sabores/@40.470255,0.47702,19z/data=!4m5!3m4!1s0x0:0x3d39b5d76862d8d4!8m2!3d40.4701768!4d0.4770107?hl=es).

- Ver [*reseñas de clientes*](https://www.google.com/search?hl=es-AU&gl=au&q=Son+de+Sabores,+Plaza+de+San+Agustín,+8+Mercado+Municipal+de,+Vinaroz&ludocid=4411757246760016084&#lrd=0x12a04f2be279daf9:0x3d39b5d76862d8d4,1,,,).

<html>
<head>
	<style>
	.simplescrollup__button {
		position: fixed;
		bottom: 1rem;
		right: 1rem;
		transition: 1s all;
		z-index: 10000;
		cursor: pointer;
	}
	.simplescrollup__button--show {
		transform: translateX(0);
	}
	.simplescrollup__button--hide {
		transform: translateX(100px);
	}
	</style>
</head>


<body>
<img src="../flechaparriba.png" id="btnup" class="simplescrollup__button simplescrollup__button- hide" alt="Parriba">
<script src="simplescrollup.js"></script>
</body>

</html>
