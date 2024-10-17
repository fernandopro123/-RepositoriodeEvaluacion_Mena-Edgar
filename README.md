# -RepositoriodeEvaluacion_Mena-Edgar
Practica 2,17

Edgar Fernando Mena Salinas

El objetivo de la practica es usar la funcion array para 5 empleados y su pagp mensual y usando array push agrgar 2 empleados.

El codigo es el siguiente:
<!DOCTYPE html>
<html>
<head>
    <title>Empleados y Sueldo</title>
    <style type="text/css">
        body {
            background: black;
            color: #f7f9f9;
            font-family: Arial;
            text-align: justify-all;
        }
        img {
            width: 300px; 
            margin: 10px 0;
        }
      
    </style>
</head>
<body>

<img src="https://i8.amplience.net/i/naras/microsoftteams-image_8.png.jpg?w=821&sm=c" >
<?php 
$empleados=array(
"Beyonce"=> 100000,
"Taylor Swift"=>20000,
"Kanye West"=> 50000,
"Adele"=> 150000,
"Lizo"=> 30000,
);
 echo "<h1>Empleados Y Sueldo Mensual</h1>";
foreach ($empleados as $sueldo => $total) {
echo "<li>$sueldo: $$total</li>";
}

echo "<h1>Empleados Completos Y Sueldo Mensual</h1>";

array_push($empleados,"P.Diddy:",500000,"Justin Bieber:",1500);
foreach ($empleados as $sueldo => $total) {
echo "<li>$sueldo: $$total</li>";
}
 ?>

</body>
</html>
