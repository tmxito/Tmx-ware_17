<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tmx-ware</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            flex-direction: column;
        }

        h1 {
            font-size: 3rem;
            cursor: pointer;
            opacity: 0;  /* Inicialmente invisible */
            animation: lightUp 3s ease-in-out forwards;  /* Aplica la animación */
            color: white;  /* Establece el color de la letra en blanco */
        }

        /* Definir la animación de iluminación */
        @keyframes lightUp {
            0% {
                opacity: 0;
                text-shadow: 0 0 5px white, 0 0 10px white, 0 0 15px white, 0 0 20px white;
            }
            100% {
                opacity: 1;
                text-shadow: 0 0 15px white, 0 0 25px white, 0 0 35px white, 0 0 50px white;
            }
        }

        h1:hover {
            color: white;  /* Asegura que el color se mantenga blanco al pasar el ratón */
        }
    </style>
</head>
<body>
    <h1 onclick="redirectToVSBM()">tmx-ware</h1>

    <script>
        function redirectToVSBM() {
            window.location.href = "https://cznull.github.io/vsbm";  // Redirige a la página indicada
        }
    </script>
</body>
</html>
