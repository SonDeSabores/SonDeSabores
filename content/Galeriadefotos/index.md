---
title: Galería de Fotos
summary: Fotografías de lo que preparamos
date: "2021-02-01T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

{{< gallery album="fotos" >}}

<html>
<head>
	<style>
	.simplescrollup__button {
		position: fixed;
		bottom: 2rem;
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
