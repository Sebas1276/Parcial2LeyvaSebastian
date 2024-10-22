# Parcial2LeyvaSebastian
Estes es un arreglo sobre unos carros y sus precios asi como sus marcas como por ejemplo Toyota y su respectivo precio

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>

<<?php 
$carros = array(
    "Buggati" => 640000,
    "Nissan" => 200000,
    "Toyota" => 110000,
    "Chevrolet" => 180000,
    "Volkswagen" => 150000
);

echo "Lista inicial de carros:<br>";
foreach ($carros as $nombre => $precio) {
    echo "$nombre: $$precio<br>";
}

$carros["Ferrari"] = 770000;
$carros["Tesla"] = 980000;

echo "<br>Lista después de agregar y ordenar:<br>";
asort($carros);

foreach ($carros as $nombre => $precio) {
    echo "$nombre: $$precio<br>";
}


 ?>

</body>
</html>
