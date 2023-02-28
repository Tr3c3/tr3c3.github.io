<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Fulano de Tal - CV</title>
</head>

<style>
#header {
	position: sticky;
	top: 8px;
	width: 100%
}

#personal-nm {
	position: fixed;
	width: 30%
}
</-- Full responsiveness -->
@media (max-width: 600px) {
	#navbar-m, #personal-m {
		display: block;
	}
	#navbar-nm, #personal-nm {
		display: none;
	}
	#cv-body{
		margin-left: none;
	}
}
@media (min-width: 601px) {
	#navbar-m, #personal-m {
		display: none;
	}
	#navbar-nm, #personal-nm {
		display: block;
	}
	#cv-body{
		margin-left: 30%;
	}
}


</style>

<body>
	<div class="container-fluid" id="header"><h1>Currículum Vitae</h1></div>
	<div 
	<div class="container-fluid" id="navbar-m"><p>Barra de navegación (mobile)</p></div>
	<div id="personal-nm"><p>Datos personales en columna izquierda (non-mobile)</p></div>
	<div id="cv-body">
		<div id="navbar-nm"><p>Barra de navegación (non-mobile)</p></div>
		<div id="personal-m"><p>Datos personales (mobile)</p></div>
		<div id="workexp"><p>Experiencia laboral</p></div>
		<div id="studies"><p>Estudios cursados</p></div>
		<div id="skills"><p>Habilidades</p></div>
	</div>
</body>
</html>
