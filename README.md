# Archana-
<!DOCTYPE html>
<html>
<head>
    <title>Background Color Changer</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            margin-top: 100px;
            transition: background-color 0.5s;
        }

        button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: blue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>

    <h1>Background Color Changer</h1>
    <button onclick="changeColor()">Change Color</button>

    <script>
        function changeColor() {
            let colors = ["red", "green", "blue", "yellow", "pink", "orange", "purple"];
            let randomColor = colors[Math.floor(Math.random() * colors.length)];
            document.body.style.backgroundColor = randomColor;
        }
    </script>

</body>
</html>