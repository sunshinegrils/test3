<meta charset="utf-8">
	<title></title>
	<style type="text/css">
		#plane{
			background: radial-gradient(red,blue,green);
		}
		#plane img{
			animation: myplane 6s ease infinite forwards;
			position: absolute;
		}
		@keyframes myplane{
			0%{
				top: 0px;
				left: 0px;
			}
			50%{
				top:35%;
				left:90%;
				transform: rotate(360deg);
			}
			100%{
				top: 80%;
				left: 0px;
			}
		}
	</style>
</head>
<body>
<div id="plane">
	<img src="2.jpg" width="100" height="50">
</div>
</body>
</html>
