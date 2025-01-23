<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Buttons</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: url('https://cdn.cnn.com/cnn/interactive/2022/12/world/best-space-photos-2022/media/images/webb-16-08-aug-Phantom_Galaxy_across_the_spectrum.jpg') no-repeat center center / cover;
            font-family: Arial, sans-serif;
        }

        .button-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .button {
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            color: #FFFFFF;
            background-color: #000000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .button:hover {
            background-color: #000000;
            transform: scale(1.1);
        }

        .button:active {
            background-color: #000000;
            transform: scale(0.95);
        }
    </style>
</head>
<body>
    <div class="button-container">
        <button class="button" onclick="document.location'https://google.com'">Play</button>
        <button class="button" onclick="openThisFile()">Instructions</button>
    </div>

    <script>
        function openPacman() {
            window.open('./PacMan.html', '_blank');
        }

        function openThisFile() {
            window.open('./Instructions.html', '_self'); 
        }
    </script>
</body>
</html>
