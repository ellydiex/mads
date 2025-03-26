# mads
volta vida
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .buttons button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            transition: 0.3s;
        }
        #yes {
            background-color: lightgreen;
        }
        #no {
            background-color: lightcoral;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Três semanas foi só a versão beta... bora lançar a oficial? ❤️</h1>
        <div class="buttons">
            <button id="yes">Sim</button>
            <button id="no">Não</button>
        </div>
    </div>
    <script>
        document.getElementById("yes").addEventListener("click", function() {
            alert("Yay! 💕 You made my day!");
        });
        
        document.getElementById("no").addEventListener("click", function() {
            this.style.position = "absolute";
            this.style.top = Math.random() * window.innerHeight + "px";
            this.style.left = Math.random() * window.innerWidth + "px";
        });
    </script>
</body>
</html>
