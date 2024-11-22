<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Willkommen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1 {
            font-size: 2.5em;
            color: #007BFF;
        }
        p {
            font-size: 1.2em;
            margin: 10px 0;
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
            color: #fff;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Willkommen auf unserer Webseite!</h1>
    <p>Schön, dass du da bist. Entdecke spannende Inhalte und lass dich inspirieren.</p>
    <button onclick="showMessage()">Mehr erfahren</button>

    <script>
        function showMessage() {
            alert("Wir freuen uns, dass du hier bist! Viel Spaß beim Erkunden unserer Seite.");
        }
    </script>
</body>
</html>
