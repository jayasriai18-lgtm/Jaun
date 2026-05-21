<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Tharun</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fad0c4);
      overflow:hidden;
    }

    .card{
      text-align:center;
      background:white;
      padding:40px;
      border-radius:25px;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
      animation: pop 1s ease;
    }

    h1{
      font-size:50px;
      color:#ff4081;
      margin-bottom:15px;
    }

    h2{
      font-size:35px;
      color:#6a1b9a;
    }

    .emoji{
      font-size:40px;
      margin-top:20px;
      animation: float 2s infinite;
    }

    @keyframes pop{
      from{
        transform:scale(0.5);
        opacity:0;
      }
      to{
        transform:scale(1);
        opacity:1;
      }
    }

    @keyframes float{
      0%{ transform: translateY(0px);}
      50%{ transform: translateY(-10px);}
      100%{ transform: translateY(0px);}
    }
  </style>
</head>

<body>

  <div class="card">
    <h1>Happy Birthday ✨</h1>
    <h2>Tharun 💖</h2>
<h3> Stay happy 😊 always 💥 keep rocking 💫
My dear😍
This year you achieve all your dreams and great things ❤️‍🔥</h3>

    <div class="emoji">
      🎂 🎈 🎁 ✨
    </div>
  </div>

</body>
</html>
