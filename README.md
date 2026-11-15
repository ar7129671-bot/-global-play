# -global-play
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Global Play - Play Together</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;
 font-family:Arial,sans-serif;
 background:#0b1020;
 color:white;
}
header{
 background:#151d35;
 padding:17px;
 display:flex;
 justify-content:space-between;
 align-items:center;
 position:sticky;
 top:0;
 z-index:5;
}
.logo{font-size:23px;font-weight:bold;color:#8b7cff}
nav a{
 color:white;text-decoration:none;
 margin-left:12px;font-size:13px
}
.hero{
 text-align:center;
 padding:65px 15px;
 background:linear-gradient(135deg,#30246c,#101b3d);
}
.hero h1{font-size:38px;margin:5px}
.hero p{color:#d2d5ec}
.btn{
 display:inline-block;
 padding:12px 22px;
 border:0;border-radius:9px;
 background:#8065ff;color:white;
 font-weight:bold;cursor:pointer;
 text-decoration:none;
}
section{padding:30px 16px}
h2{text-align:center;color:#a99aff}
.grid{
 display:grid;
 grid-template-columns:repeat(auto-fit,minmax(140px,1fr));
 gap:15px;
 max-width:900px;
 margin:auto;
}
.card{
 background:#18213b;
 padding:20px;
 border-radius:14px;
 text-align:center;
 border:1px solid #303b60;
}
.emoji{font-size:38px}
.card button{margin-top:10px}
.gamebox{
 max-width:340px;
 margin:auto;
 text-align:center;
 background:#18213b;
 padding:20px;
 border-radius:15px;
}
.board{
 display:grid;
 grid-template-columns:repeat(3,1fr);
 gap:7px;
}
.cell{
 height:85px;
 font-size:35px;
 border:0;
 border-radius:9px;
 background:#293657;
 color:white;
 cursor:pointer;
}
input{
 padding:12px;
 width:100%;
 margin:7px 0;
 border-radius:7px;
 border:1px solid #596483;
 background:#10182d;
 color:white;
}
footer{
 text-align:center;
 background:#151d35;
 padding:25px;
 color:#aaa;
}
.small{font-size:13px;color:#aab3d0}
</style>
</head>
<body>

<header>
 <div class="logo">🌍 Global Play</div>
 <nav>
  <a href="#games">Games</a>
  <a href="#chat">Chat</a>
  <a href="#about">About</a>
 </nav>
</header>


<div class="hero">
 <h1>Play Together 🌎</h1>
 <p>Meet the World. Make Friends. Play Games.</p>
 <p>Connect with people around the world!</p>
 <a class="btn" href="#games">Explore Games</a>
</div>

<section id="games">
 <h2>🎮 Popular Games</h2>
 <div class="grid">
  <div class="card">
   <div class="emoji">⭕</div>
   <h3>Tic Tac Toe</h3>
   <p class="small">Play a fun game</p>
   <a class="btn" href="#play">Play Now</a>
  </div>
  <div class="card">
   <div class="emoji">♟️</div>
   <h3>Chess</h3>
   <p class="small">Coming Soon</p>
  </div>
  <div class="card">
   <div class="emoji">🎲</div>
   <h3>Ludo</h3>
   <p class="small">Coming Soon</p>
  </div>
