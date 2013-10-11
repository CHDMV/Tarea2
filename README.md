<!DOCTYPE html>

<html lang="es">
 <link rel="stylesheet" href="stylesheet.css">
	<head>

    </head>
	
	<body onload="generar()">

		<div id="contenedor"></div>
		
	</body>
	
</html>



<script type="text/javascript">
			
			
				
				
	
			
			
	
	
		function generar()
	{

		var contenido ="<canvas id='myCanvas' width='1000' height='200'></canvas>";
		contenido+="<div id='contenido'>"+
			"<header>"+
				"<nav>"+
					"<ul><li><a href='/Biblioteca/index.html'>INICIO</a></li>"+
						"<li><a href='registro-login.html'>LOGIN</a></li></ul>"+
				"</nav>"+
			"</header>"+
			
			"<section>"+
			
				"<div id='textPr'>"+
					"<article>"+
						"<hgroup>"+
							"<h1>Bienvenidos a Nuestra Página Web</h1>"+
						"</hgroup>"+
						"<p>Somos una tienda online de ropa para hombre, mujer, niños, calzado y complementos.Aprovecha nuestras últimas rebajas en ropa. También tenemos liquidación de stock para tiendas. </p>"+
					"</article>"+
					"<br>"+
					"<div>"+
						"<IMG SRC='ropa-mintmelon.jpg' align='right' >"+
						"</div>"+
						"<div>"+
					"<div>"+
					"<aside>"+
							"<button style='width:210px; height:50px'>"+
								"<b>  Ropa pada ninos  </b>"+
								"<br>"+
							"</button><br>"+
							"<button style='width:210px; height:50px'>"+
								"<b> Ropa para ninas  </b><br>"+
							"</button>"+
								"<br>"+
							"<button style='width:210px; height:50px'>"+
								"<b> Ropa para damas  </b>"+
								"<br>"+
							"</button>"+
								"<br>"+
							"<button style='width:210px; height:50px'>"+
								"<b>Ropa para caballeros</b><br>"+
							"</button>"+
								"<br>"+
							"<button style='width:210px; height:50px'>"+
								"<b>Accesorios para damas</b>"+
								"<br></button>"+
								"<br><button style='width:210px; height:50px'>"+
								"<b>Accesorios para caballeros</b>"+
								"<br>"+
							"</button>"+
								
						
					"</aside>"+
					
						
						"<br>"+
						"<br><br><br>"+
						"<video  autoplay='autoplay' loop='loop' muted='muted'  >"+
		
							"<source src='Lightmirror - Videos para Fondos HD .wmv.mp4' type='video/mp4' />"+
						"</video>"+
						
						"<hgroup>"+
							"<h>Visita nuestro <a href='http://www.youtube.com/'>Canal de Youtube</a></h5>"+
						"</hgroup> "+
						
						
						"<br><br>"+
					"<div style='overflow:hidden; width:960px; margin:100 auto; padding:0 20px;'>"+
                "</div>"+
				"</div>"+
			"</section>"+
		"</div>"+
		"<footer>"+
			
			
	 
					"</div>"+
				"</div>"+
			"</section>"+
		"</div>"+
		"<audio src='Pra Voc.mp3' preload='auto' controls> </audio>";

		
		document.getElementById("contenedor").innerHTML=contenido;
		

				var canvas = document.getElementById("myCanvas");
				var context = canvas.getContext("2d");
				var x = 400;
				var y = 150;
 
				context.font = "60pt Calibri";
				context.lineWidth = 4;

				context.strokeStyle = "pink";
				context.strokeText("Ventas Online", x, y);
				context.beginPath();
				context.moveTo(x,y);
	
				context.font = 'italic 40px Calibri';
			
			
		
	}			
	
				
				

	
	
				
</script>
		
