<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday My Kuchupuchu ❤️</title>

<style>
body{
margin:0;
font-family: Arial, sans-serif;
background: linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
text-align:center;
overflow-x:hidden;
}

header{
padding:50px 20px;
}

h1{
font-size:40px;
}

.date{
font-size:20px;
margin-top:10px;
}

.heart{
font-size:50px;
animation: beat 1s infinite;
}

@keyframes beat{
0%{transform:scale(1);}
50%{transform:scale(1.2);}
100%{transform:scale(1);}
}

.letter{
max-width:700px;
margin:40px auto;
background:rgba(255,255,255,0.15);
padding:30px;
border-radius:20px;
font-size:18px;
line-height:1.6;
}

footer{
margin-top:40px;
padding:20px;
font-size:16px;
}

button{
padding:12px 25px;
border:none;
border-radius:30px;
background:white;
color:#ff4b7d;
font-size:16px;
cursor:pointer;
margin-top:20px;
}

</style>
</head>

<body>

<header>
<h1>Happy Birthday My Kuchupuchu 🎂</h1>
<div class="date">23 March ❤️</div>
<div class="heart">❤️</div>
</header>

<button onclick="playMusic()">Play Our Song 🎵</button>

<audio id="song" autoplay loop>
<source src="madeinjapan.mp3" type="audio/mpeg">
</audio>

<div class="letter">

<h2>A Letter For You 💌</h2>

<p>
My dearest Kuchupuchu,
</p>

<p>
Happy Birthday to the most special person in my life.  
From the moment you came into my life, everything became brighter and happier.  
Your smile makes my day better, and your love makes my life beautiful.
</p>

<p>
I feel so lucky to have you. No matter what happens, I promise to always care for you, support you, and make you smile.
</p>

<p>
Today is your day, and I hope it is filled with love, laughter, and happiness.  
You deserve all the happiness in the world.
</p>

<p>
I love you so much ❤️  
Forever yours.
</p>

<p>
— From Your Love
</p>

</div>

<footer>
Made with ❤️ for My Kuchupuchu
</footer>

<script>
function playMusic(){
document.getElementById("song").play();
}
</script>

</body>
</html>
