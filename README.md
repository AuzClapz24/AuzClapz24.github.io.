<!DOCTYPE html>
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
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ff7e5f, #feb47b);
            font-family: Arial, sans-serif;
        }

        .button-container {
            display: flex;
            gap: 20px;
        }

        .button {
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            color: #fff;
            background-color: #4caf50;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .button:hover {
            background-color: #45a049;
            transform: scale(1.1);
        }

        .button:active {
            background-color: #3e8e41;
            transform: scale(0.95);
        }
    </style>
</head>
<body>
    <div class="button-container">
        <button class="button" onclick="alert('Button 1 Clicked!')">Button 1</button>
        <button class="button" onclick="alert('Button 2 Clicked!')">Button 2</button>
    </div>
</body>
</html>
