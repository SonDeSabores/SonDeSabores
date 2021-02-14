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

<html>
    <head>
	<style>
	.simplescrollup__button {
		position: fixed;
		bottom: 4rem;
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
        <!-- Contenido HTML -->
	<img src="../flechaparriba.png" id="btnup" class="simplescrollup__button simplescrollup__button- hide" alt="Parriba">
	<script src="simplescrollup.js"></script>
    </body>

</html>
