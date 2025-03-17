<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mini Clash Game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Mini Clash Game</h1>
    <div id="game-container">
        <div id="base">
            <h3>Your Base</h3>
            <p id="health">Health: 100</p>
            <button onclick="trainTroops()">Train Troops</button>
            <button onclick="attackEnemy()">Attack Enemy</button>
        </div>
        <div id="enemy">
            <h3>Enemy Base</h3>
            <p id="enemy-health">Health: 100</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
