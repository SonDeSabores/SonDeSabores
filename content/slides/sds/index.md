---
title: SdS
date: 2021-04-28T17:45:47.080Z
draft: false
slides:
  theme: black
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
<html>
<head>
    <style>	
        @keyframes tipsy {
            0 {
                transform: translateX(-50%) translateY(-50%) rotate(0deg);
            }
            100% {
                transform: translateX(-50%) translateY(-50%) rotate(360deg);
            }
        }
        
        body {
            font-family: helvetica, arial, sans-serif;
            background-color: #2e2e31;
        }
        
        a {
            display: block;
            color: #fffbf1;
            font-size: 80px;
            font-weight: bold;
            letter-spacing: -3px;
            margin: 0;
            text-decoration: none;
            text-shadow: 0 20px 25px #2e2e31, 0 40px 60px #2e2e31;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translateX(-50%) translateY(-50%);
        }
        
        a:before,
        a:after {
            content: '';
            padding: .9em .4em;
            position: absolute;
            left: 50%;
            width: 100%;
            top: 50%;
            display: block;
            border: 15px solid red;
            transform: translateX(-50%) translateY(-50%) rotate(0deg);
            animation: 10s infinite alternate ease-in-out tipsy;
        }
        
        a:before {
            border-color: #d9524a #d9524a rgba(0, 0, 0, 0) rgba(0, 0, 0, 0);
            z-index: -1;
        }
        
        a:after {
            border-color: rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) #d9524a #d9524a;
            box-shadow: 25px 25px 25px rgba(46, 46, 49, .8);
        }
    </style>
</head>

<body>
	<!-- <a >Son de Sabores</a> -->
	<!-- Código de James Mellers -->
	<a >&copy; 2021 SdS</a>
</body>

</html>