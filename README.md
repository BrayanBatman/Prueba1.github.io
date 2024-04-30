html

<!DOCTYPE html>

<html>

<head>

    <title>¿Quién te gusta más?</title>

</head>

<body>

    <h2>¿Quién te gusta más?</h2>

    <button onclick="mostrarTarjeta('Brayan')">Brayan</button>

    <button onclick="mostrarTarjeta('Batman')">Batman</button>



    <script>

        function mostrarTarjeta(nombre) {

            if (nombre === 'Brayan') {

                window.location.href = 'tarjeta_brayan.html';

            } else if (nombre === 'Batman') {

                window.location.href = 'tarjeta_batman.html';

            }

        }

    </script>

</body>

</html>

html

<!DOCTYPE html>

<html>

<head>

    <title>Tarjeta de cumpleaños para Brayan</title>

    <style>

        body {

            background-color: #FFC0CB; /* Color rosa */

        }

        h1 {

            color: #800000; /* Color rojo oscuro */

            text-align: center;

        }

    </style>

</head>

<body>

    <h1>Lo sé, Feliz cumpleaños mi amor</h1>

</body>

</html>

html

<!DOCTYPE html>

<html>

<head>

    <title>Tarjeta de cumpleaños para Batman</title>

    <style>

        body {

            background-color: #ADD8E6; /* Color azul claro */

        }

        h1 {

            color: #000080; /* Azul marino */

            text-align: center;

        }

    </style>

</head>

<body>

    <h1>Lo sé, Feliz cumpleaños mi amor</h1>

</body>

</html>
