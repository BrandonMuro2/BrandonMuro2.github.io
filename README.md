

<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Barra de LEDs</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #333;
            color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #222;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1, h2 {
            color: #fff;
        }
        img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
        }
        .content {
            font-size: 18px;
            color: #ccc;
        }
        .features, .specifications, .applications, .how-to-use, .example {
            margin-top: 20px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
        }
        .spec-img {
            display: block;
            margin: 0 auto;
            max-width: 80%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Barra de LEDs</h1>
        <p><strong>Muro Andrade Brandon Arturo</strong><br>Estudiante: 20211818</p>
        <div class="content">
            Las barras de LEDs son un grupo de LEDs independientes dispuestos uno al lado del otro. Vienen en una variedad de colores y cuentan con una cantidad de LEDs personalizable.
        </div>
        <img src="https://www.makerguides.com/wp-content/uploads/2022/10/the-LED-light-bar-graphs-from-Everlight.jpg" alt="Barra de LEDs">
        <h2>Características:</h2>
        <ul class="features">
            <li>10 LEDs con control individual</li>
            <li>Alto brillo</li>
            <li>Alta intensidad</li>
            <li>Económicamente asequible</li>
            <li>Compatible con protoboard o placa de pruebas</li>
            <li>Cumple con la normativa RoHS</li>
            <li>Amplio ángulo de visión</li>
            <li>Colores disponibles: Rojo, verde, azul, amarillo, naranja y ámbar</li>
        </ul>
         <div class="specifications">
            <h2>Especificaciones:</h2>
            <p>20 pines (10 ánodos y 10 cátodos, un par para cada LED)</p>
            <img class="spec-img" src="https://components101.com/sites/default/files/component_pin/LED-Bar-Graph-Pinout.png" alt="Especificaciones">
        </div>
        <div class="applications">
            <h2>¿Dónde se usa?</h2>
            <p>Generalmente, podemos utilizar la barra de LEDs como indicador de nivel de batería, en equipos de audio y en paneles de control industrial. Existen muchas otras aplicaciones para la barra de LEDs.</p>
        </div>
        <div class="how-to-use">
            <h2>¿Cómo se usa?</h2>
            <p>La conexión es similar a la de 10 LEDs individuales.</p>
        </div>
        <div class="example">
            <h2>Ejemplo con Arduino Uno:</h2>
            <p><a href="https://wokwi.com/projects/309829489359061570">Ver ejemplo</a></p>
        </div>
    </div>
</body>
</html>
