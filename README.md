<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hey Pritha 👋</title>

  <style>
    body {
      background: linear-gradient(135deg, #667eea, #764ba2);
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: white;
      text-align: center;
    }

    .box {
      background: rgba(255,255,255,0.1);
      padding: 30px;
      border-radius: 15px;
      backdrop-filter: blur(10px);
    }

    h1 {
      margin-bottom: 10px;
    }

    button {
      display: block;
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-size: 16px;
      background: white;
      color: #764ba2;
      font-weight: bold;
      transition: 0.3s;
    }

    button:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>

<div class="box">
  <h1>Hey Pritha, what’s up? 😄</h1>
  <p>What are you doing?</p>

  <button onclick="reply('a')">A) Studying 📚</button>
  <button onclick="reply('b')">B) Scrolling reels 😎</button>
  <button onclick="reply('c')">C) Missing me na 🫠</button>
  <button onclick="reply('d')">D) Option C 😂</button>
</div>

<script>
function reply(option) {
  let message = "";

  if(option === 'a') {
    message = "Then why did you open Instagram 😂😂 Go and study!";
  }
  else if(option === 'b') {
    message = "Great job 😎 but at least react to my reels 😭😭";
  }
  else if(option === 'c') {
    message = "I knew it 😌❤️";
  }
  else if(option === 'd') {
    message = "Haha caught you 😂";
  }

  document.body.innerHTML = `
    <div class="box">
      <h1>${message}</h1>
    </div>
  `;
}
</script>

</body>
</html># Fun-question-
