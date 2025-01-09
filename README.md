# legendary-website
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  color: white;
  background-color: black;
}

header {
  background: #222;
  padding: 1rem;
  text-align: center;
}

header h1 {
  margin: 0;
  color: #f4f4f4;
}

header ul {
  list-style: none;
  padding: 0;
  margin: 1rem 0 0;
  display: flex;
  justify-content: center;
  gap: 1rem;
}

header a {
  color: #00bcd4;
  text-decoration: none;
}

header a:hover {
  text-decoration: underline;
}

main {
  padding: 2rem;
}

section {
  margin-bottom: 2rem;
}

img {
  display: block;
  margin: 0 auto;
  border: 2px solid white;
}

blockquote {
  font-style: italic;
  text-align: center;
  margin: 1rem 0;
  color: #ffc107;
}

footer {
  background: #222;
  color: #f4f4f4;
  padding: 1rem;
  text-align: center;
}

a {
  color: #00bcd4;
}

a:hover {
  text-decoration: underline;
}


---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Legendary Guy - Rajveer Singh's Website">
  <title>Rajveer Singh - Legendary Guy</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <a href="#main-content" class="skip-link">Skip to content</a>
      <h1>Rajveer Singh</h1>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#wwe">WWE</a></li>
        <li><a href="#cricket">Cricket</a></li>
        <li><a href="#meme">Meme</a></li>
        <li><a href="#quote">Sigma Male Quote</a></li>
      </ul>
    </nav>
  </header>
  
  <main id="main-content">
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! I am Rajveer Singh, also known as the Legendary Guy. Welcome to my website where I share my interests, contact details, and more!</p>
    </section>
    
    <section id="contact">
      <h2>Contact Me</h2>
      <ul>
        <li><strong>Email (Gmail):</strong> <a href="mailto:legendryguy34@gmail.com">legendryguy34@gmail.com</a></li>
        <li><strong>Email (Microsoft):</strong> <a href="mailto:rajveer5743hsr@samsidh.in">rajveer5743hsr@samsidh.in</a></li>
        <li><strong>Roblox:</strong> Legendaryguy_456</li>
        <li><strong>Discord:</strong> legendary wrestler (Legend_3w)</li>
        <li><strong>WhatsApp:</strong> <a href="tel:+7892981268">+7892981268</a></li>
        <li><strong>Instagram:</strong> <a href="https://www.instagram.com/legendary_guy" target="_blank">legendary guy</a></li>
        <li><strong>Twitter (X):</strong> <a href="https://twitter.com/LegendaryG7008" target="_blank">@LegendaryG7008</a></li>
      </ul>
    </section>

    <section id="wwe">
      <h2>WWE Stuff</h2>
      <p>I love WWE! My favorite event is Survivor Series. I’m a big fan of iconic moments and legendary wrestlers.</p>
    </section>

    <section id="cricket">
      <h2>Cricket Stuff</h2>
      <p>Cricket is my passion! I follow the ICC World Cup, World Test Championship Finals, and the Champions Trophy closely. India’s performances always inspire me.</p>
    </section>
    
    <section id="meme">
      <h2>Here’s a Meme!</h2>
      <img src="https://i.imgflip.com/5yk54i.jpg" alt="Funny Meme" width="100%">
      <p><em>Never take life too seriously!</em></p>
    </section>
    
    <section id="rickroll">
      <h2>Wait, What’s This?</h2>
      <p><strong>Pls don't click!</strong> <a href="https://youtu.be/dQw4w9WgXcQ" target="_blank">Trust me, don't open it!</a></p>
    </section>
    
    <section id="quote">
      <h2>Sigma Male Quote</h2>
      <blockquote>
        "Lions don’t lose sleep over the opinions of sheep."
      </blockquote>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2025 Rajveer Singh - Legendary Guy. All rights reserved.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>