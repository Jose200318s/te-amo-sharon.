<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Amo, Sharon</title>
    <style>
        body {
            margin: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe4e1; /* Rosa claro */
            font-family: Arial, sans-serif;
            text-align: center;
        }

        h1 {
            color: #ff0000;
            font-size: 2.5rem;
            margin: 0;
            margin-bottom: 100px; /* Espacio grande debajo del título */
        }

        h2 {
            color: #ff0000;
            font-size: 1.5rem;
            margin: 0;
            margin-top: 100px; /* Espacio grande encima de la firma */
        }

        .heart {
            position: relative;
            width: 150px;
            height: 150px;
            background-color: red;
            transform: rotate(-45deg);
            animation: heartbeat 1s infinite;
        }

        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 150px;
            height: 150px;
            background-color: red;
            border-radius: 50%;
        }

        .heart::before {
            top: -75px;
            left: 0;
        }

        .heart::after {
            top: 0;
            left: 75px;
        }

        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1) rotate(-45deg);
            }
            50% {
                transform: scale(1.2) rotate(-45deg);
            }
        }
    </style>
</head>
<body>
    <h1>Te Amo, Sharon</h1>
    <div class="heart"></div>
    <h2>Att: tu novio Daniel</h2>
</body>
</html>

