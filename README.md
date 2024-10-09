<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pflege Fit App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Gesund & Stark in der Pflege</h1>

    <!-- Meditationstimer -->
    <div class="section">
      <h2>Meditationstimer: <span id="timer">05:00</span></h2>
      <button id="startTimer">Meditation starten</button>
    </div>

    <!-- Stresslevel-Tracker -->
    <div class="section">
      <h2>Stresslevel: <span id="stressLevelDisplay">0.0</span> / 10</h2>
      <input type="range" id="stressLevel" min="0" max="10" step="0.1" value="0">
    </div>

    <!-- Wasser- und Mahlzeiten-Tracker -->
    <div class="section">
      <button id="waterButton">Wasser: 0 Gläser</button>
      <button id="mealButton">Mahlzeiten: 0</button>
    </div>

    <!-- Tipp des Tages -->
    <div class="section">
      <h2 id="dailyTip">Tipp des Tages: Mach regelmäßig Pausen.</h2>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
