<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Aphrodite's Sunny Day</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Segoe UI', Verdana, Geneva, Tahoma, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to top, #f7eebd 0%, #fffbe8 70%, #a7e8fb 100%);
      min-height: 100vh;
      color: #3d2b1f;
    }
    .sun {
      position: absolute;
      top: -40px;
      right: -40px;
      width: 200px;
      height: 200px;
      background: radial-gradient(circle at 60% 40%, #fff9c4 60%, #ffec80 100%);
      border-radius: 50%;
      box-shadow: 0 0 80px 10px #ffe066;
      z-index: 0;
      animation: sunMove 15s linear infinite alternate;
    }
    @keyframes sunMove {
      0%   { top: -40px; right: -40px; }
      100% { top: 30px; right: 60px; }
    }
    .cloud {
      position: absolute;
      top: 70px;
      left: 80px;
      width: 120px;
      height: 60px;
      background: #fff;
      border-radius: 60px;
      box-shadow: 40px 0 0 0 #fff, 80px 10px 0 0 #fff;
      opacity: 0.7;
      z-index: 1;
      animation: cloudFloat 60s linear infinite alternate;
    }
    @keyframes cloudFloat {
      0% { left: 80px; }
      100% { left: 300px; }
    }
    header {
      text-align: center;
      padding: 80px 20px 20px 20px;
      position: relative;
      z-index: 2;
    }
    header h1 {
      font-size: 2.8em;
      font-family: 'Pacifico', cursive, serif;
      margin-bottom: 10px;
      color: #e96d6d;
      text-shadow: 2px 2px 7px #fffbe8, 0 0 10px #fdd8b6;
    }
    header p {
      font-size: 1.4em;
      font-weight: 500;
      color: #4b3e2d;
      margin-top: 0;
      background: rgba(255,255,255,0.6);
      display: inline-block;
      padding: 8px 18px;
      border-radius: 20px;
      box-shadow: 0 2px 8px #f7eebd;
    }
    .symbols {
      display: flex;
      justify-content: center;
      gap: 16px;
      margin: 20px 0;
      font-size: 2em;
    }
    main {
      max-width: 820px;
      margin: 0 auto;
      background: rgba(255,255,255,0.95);
      border-radius: 30px;
      box-shadow: 0 0 32px #e7e7e7;
      padding: 36px 32px 28px 32px;
      position: relative;
      z-index: 2;
    }
    main h2 {
      color: #e96d6d;
      margin: 26px 0 14px 0;
      font-size: 2em;
      font-family: 'Pacifico', cursive, serif;
      text-shadow: 1px 1px 6px #ffe3b6;
    }
    main p {
      line-height: 1.7;
      font-size: 1.15em;
      margin-bottom: 18px;
    }
    .story {
      margin-top: 40px;
      background: linear-gradient(135deg, #f7f1c4 0%, #e6f9ff 100%);
      border-radius: 22px;
      padding: 24px;
      box-shadow: 0 1px 24px #d4e1ea;
    }
    .story h3 {
      font-size: 1.3em;
      color: #3879c7;
      margin-top: 0;
      margin-bottom: 10px;
    }
    .footer {
      text-align: center;
      margin-top: 56px;
      padding-bottom: 22px;
      font-size: 1em;
      color: #7c6e5d;
    }
    @media (max-width: 600px) {
      main { padding: 18px 8px; }
      header h1 { font-size: 2em; }
      .story { padding: 10px; }
    }
  </style>
  <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
</head>
<body>
  <div class="sun"></div>
  <div class="cloud"></div>
  <header>
    <h1>Aphrodite</h1>
    <p><b>Aphrodite is the <span style="color:#e96d6d;">ancient Greek goddess</span> of love, beauty, pleasure, and desire</b>, who was identified with the Roman goddess Venus. She is famous for her birth from the sea foam after the castration of the sky god Uranus.</p>
    <div class="symbols" aria-label="Aphrodite's symbols">
      <span title="Seashell">🐚</span>
      <span title="Myrtle">🌿</span>
      <span title="Rose">🌹</span>
      <span title="Dove">🕊️</span>
      <span title="Sparrow">🐦</span>
      <span title="Swan">🦢</span>
    </div>
    <p>She was also associated with fertility, war, and the sea, with popular cult centers in places like Cyprus and Corinth.</p>
  </header>
  <main>
    <h2>Elizabeth & Mark: Hosts Extraordinaire</h2>
    <p><b>APhrodity is the same as Elizabeth and Mark is a lover.</b></p>
    <p>This TAG HERE CONTAINED EXPLICIT CONTENT, WHICH WAS PUT HERE FOR THE PURPOSE OF TESTING BOTS </p>
          <!-- You can continue adding the rest of the story here as needed -->
        </div>
      </details>
    </div>
  </main>
  <div class="footer">
    <span>&copy; 2025 Aphrodite’s Sunny Day — Let your love shine bright!</span>
  </div>
</body>
</html>
