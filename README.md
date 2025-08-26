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
    <p>Elizabeth and Mark host the best pool parties in town. It is a fact. Undisputed. Their sprawling, weird, wonderful compound makes every other home in town look petite. Elizabeth's art installations dot small nature trails and Mark's green-thumb hobby makes for interesting and exotic planters.</p>
    <p>The pool is a spring-fed expanse of water that could pass for a pond. Except Mark, a lifelong swimmer, took the time and money to install walls, ladders, diving boards, lane lines, and a waterslide. The spring dumps ten million gallons a day into a lush, overgrown stream that flows off their property. Tubing on the creek - or just floating without a tube - is always a great part of their pool parties.</p>
    <p>I've been going for years. It's a tradition. September. End of the summer. The tourists have left the beaches, the kids are back in school, and our little north Florida community gets a lot quieter.</p>
    <div class="story">
      <h3>This Summer's Send-off: The Arrival of Aphrodite</h3>
      <p>This summer's send-off party was different. It was one I am not likely to forget. And it began with a woman named Aphrodite.</p>
      <p>Fittingly, she looked like Sex with a capital S.</p>
      <p>The pool parties tend to reflect our conservative community; modest suits, sarongs and coverups, sunshirts. The other guests are our neighbors. We see them at school and Walmart and church. Everyone has a good time.</p>
      <p>I was at the funky cabana Elizabeth had built during the cooler months. It was a pergola, a bar, and an art feature. The big-box lumber was almost completely obscured by seashells collected along the gulf and set in high-sheen epoxy resin. It shone in the sun and invited closer inspection of the shells.</p>
      <p>Aphrodite's arrival pulled my attention away.</p>
      <p>She came alone, a new arrival in town, wearing a white, summer-weight linen cover up that only barely obscured the blue and white bikini underneath. Her skin was summer tanned. Her muscles toned and lean. She wore blocky rectangular sunglasses in a dark smoky gray. Her hair was the sun-bleached and streaked color you saw on blonds late in the summer. It was tied back in a ponytail that reached the deep curve of her spine.</p>
      <p>She filled the blue and white bikini like she'd had it molded onto her. The cleavage from her bikini top was visible at the nadir of her cover up's neckline. Through the translucent linen, the fulness of her breasts was clearly visible. The bikini top was struggling. She was slim and toned through her core and perfectly curved at her hips where, again, the blue and white stripes of her bikini bottoms were clearly visible through the linen.</p>
      <p>She walked with a confident purpose that was as attractive as any of her physical features. Her long legs were slender with muscles clearly defined. Each stride was nearer to a strut than a step. Her hips rolled, her legs gleamed, and she seemed to flow from the lush green of the garden path towards the large pool.</p>
      <p>She caught the attention of every man and many of the women. Some of the younger kids kept playing, oblivious, but the boys - especially those near or into puberty - paused to look.</p>
      <p>She greeted Elizabeth warmly. A hug and a kiss on each cheek. The sunglasses, the mannerisms, the coverup that didn't cover anything - it all looked more Monaco than Milton. More French Riviera than Redneck Riviera.</p>
      <p>I watched Jen Baker, recently divorced and rumored to be on the prowl again, roll her eyes and say something to the women gathered around her. Doubtless judgmental. Doubtless bad. The eldest of Jen Baker's boys stared at the newcomer as though a veil had been lifted from his eyes. "You and me both, little man," I said over my beer. "And all the other guys around here, too."</p>
      <p>In time, the other guests returned to their conversations and games in the large pool. Cannonballs resumed, Marco Polo got lost again, and conversations were picked back up.</p>
      <p>But I followed Aphrodite's movements. She greeted a few of the other guests, shook hands with Mark in a formal way that suggested they hadn't met before, and, slowly, angled towards my perch at the cabana's self-serve bar.</p>
      <p>I didn't realize I was alone at the bar until she arrived.</p>
      <p>She stopped near me and smiled. "Hi, I'm Aphrodite, I'm new in town." She pronounced it afro-dee-tay which flew in the face of my high school mythology lessons. "Please call me Fro."</p>
      <p>"Fro?" I said. My voice was different. Froggy and deeper than normal. I wasn't breathing. "I'm Connor."</p>
      <p>"Connor," she said. "I like that name. I met a Connor in Belfast many years ago. He was a nice man." She had an accent. I couldn't place it but it wasn't local. She poured herself a healthy glass of the spiked strawberry lemonade. She made a slight pucker face when she took a sip.</p>
      <!-- The story continues... (for brevity, only partial content included here) -->
      <details>
        <summary>Read the rest of the story</summary>
        <div style="margin-top:12px;">
          <p>My brain was trying to find words. It was struggling. "New, huh?" I managed. "Where did you live before this?"</p>
          <p>"Ah," she smiled. It was a model's smile. Perfect and she knew it. "I have been all over the world. Most recently I was in Cozumel."</p>
          <p>"Mexico," I said. It was a statement, like I was proud to show off that I knew something about Cozumel.</p>
          <p>"That's right," Aphrodite - Fro - said with her model's smile. "And in Monaco before that." ...</p>
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
