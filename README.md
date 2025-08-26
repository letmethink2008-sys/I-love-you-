# I-love-you-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I Love You Buttons App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>I Love You 🌍</h1>
    <p>Press a button to say "I love you" in that language:</p>
    
    <div class="buttons">
      <button onclick="sayLove('english')">English</button>
      <button onclick="sayLove('spanish')">Spanish</button>
      <button onclick="sayLove('french')">French</button>
      <button onclick="sayLove('german')">German</button>
      <button onclick="sayLove('japanese')">Japanese</button>
    </div>
    
    <div id="output" class="output-box"></div>
  </div>
  
  <script src="script.js"></script>
</body>
</html>
