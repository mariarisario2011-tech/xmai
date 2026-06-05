# xmai
my website
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> my Website</title>

<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@300;500&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
background:
radial-gradient(#fff 2px, transparent 2px),
#ffeef7;
background-size:25px 25px;
font-family:'Fredoka', sans-serif;
color:#d4a7ce;
padding:20px;
}

.container{
max-width:1200px;
margin:auto;
background:#fdf5f7;
border:8px solid rgb(184, 150, 179);
border-radius:15px;
padding:15px;
box-shadow:0 0 20px rgba(0,0,0,.15);
}

header{
height:220px;
border-radius:10px;
overflow:hidden;
background:
linear-gradient(rgb(252, 243, 243),
rgba(255,255,255,.2)),
url("https://images.unsplash.com/photo-1518709268805-4e9042af2176?w=1200");
background-size:cover;
background-position:center;
display:flex;
align-items:flex-end;
padding:20px;
}

.logo{
font-size:4rem;
font-weight:bold;
color:white;
text-shadow:
3px 3px #ff9ac6,
6px 6px #ffdeef;
}

.subtitle{
background:#f8d8e7;
margin-top:8px;
padding:8px;
border-radius:8px;
text-align:center;
}

.layout{
display:grid;
grid-template-columns:220px 1fr 320px;
gap:15px;
margin-top:15px;
}

.box{
background:#fff;
border:2px solid #f3a9c7;
border-radius:10px;
padding:10px;
margin-bottom:12px;
}

.box h3{
color:#d977a9;
margin-bottom:8px;
}

.sidebar .menu a{
display:block;
padding:8px;
margin:5px 0;
text-decoration:none;
background:linear-gradient(#e5d2e9,#ffe4f1);
border:1px solid #e6b5c8;
border-radius:5px;
color:#000000;
text-align:center;
}

.sidebar .menu a:hover{
background:#ffd6ea;
}

.profile{
display:flex;
gap:10px;
align-items:center;
}

.profile img{
width:90px;
border-radius:10px;
}

.featured img{
width:100%;
border-radius:10px;
}

.gallery{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:5px;
}

.gallery img{
width:100%;
border-radius:8px;
}

.status{
background:#ffe0ef;
padding:8px;
border-radius:8px;
margin-top:8px;
}

footer{
margin-top:15px;
text-align:center;
font-size:.9rem;
color:#777;
}

</style>
</head>
<body>

<div class="container">

<header>
<div>
<div class="logo">presentation</div>
<div style="font-size:2rem;color:rgb(205, 173, 204);">
Hi, my name is Mai, and this is my page to learn more about me
</div>
</div>
</header>

<div class="subtitle">
my tastes
</div>

<div class="layout">

<!-- IZQUIERDA -->

<aside class="sidebar">

<div class="box">
<h3>anime that I like</h3>

<div class="menu">
<a href="#">tokyo revengers</a>
<a href="#">soul eater</a>
<a href="#">dr.stone</a>
<a href="#">lovely complex</a>
<a href="#">gachiakuta</a>
<a href="#">needy girl overdose</a>
<a href="#">ouran high school host club</a>
</div>
</div>

<div class="box">
<h3>more fandoms</h3>

<div class="menu">
<a href="#">batman</a>
<a href="#">rottmnt</a>
<a href="#">eltingville club</a>
<a href="#">harry potter</a> 
<a href="#">vocaloid</a>
<a href="#">percy jackson
    <a href="#">wos
        <a href="#">invincible</a>
      <a href="#">my litte pony </a>
    </a>
</a>
</div>
</div>

</aside>

<!-- CENTRO -->

<main>

<div class="box">
<h3>my style</h3>

<p>
My style is Jirai Kei, I'm still a baby Jirai since I discovered it this year but I'd love to have more friends with my style :v
</p>
</div>

<div class="box">

<h3>About Me</h3>

<div class="profile">

<img src="c:\Users\MuniUWU\Downloads\_𓏼_̣̣_ȷіrᥲі_͝_໒______og_fanart_by__mxxx_n_xxxu_on_X-removebg-preview.png">

<p>
My name is Maria, I'm from Argentina and I'm 15 years old, yay! I like music and I'm multifandom. My dream is to go to Japan on an exchange program, hehe. I love to draw but I hate to paint. I like to talk about politics, I like video games like Minecraft and Roblox, and I like to collect My Little Pony cards.
</p>

</div>

<div class="status">
I'm sleepy
</div>

</div>

<div class="box">

<h3>so cool</h3>

<div class="gallery">

<img src="c:\Users\MuniUWU\Downloads\⍰̼ㅤ❀ㅤ𝐚ׁ𝐫𝐜𝐡𝐢𝐯𝐞𝐬ִㅤ💗ׁ🦇.jpeg">
<img src="c:\Users\MuniUWU\Downloads\ׅ  ѵ̼αι͠𝗇ι⃨𝗅𝗅α   ׄ   🖤⃝໋་̴͚  ׅ 𓂅                     Ი𐑼  ׅ     🅑α꯭𝗄𝖾ɾყ.jpeg">
<img src="c:\Users\MuniUWU\Downloads\IMG_6036_gif 402×402 pixels.gif">
<img src="c:\Users\MuniUWU\Downloads\download (11).jpeg">

</div>
<div class="extras">

    <!-- COMMENTS -->

    <div class="box extra-box">

        <h3>♡ comments ♡</h3>

        <textarea placeholder="leave a comment..."></textarea>

        <button class="cute-btn">send</button>

    </div>

    <!-- VISITORS -->

    <div class="box extra-box">

        <h3>✦ visitors ✦</h3>

        <div class="counter">
            visitor #000001
        </div>

        <img src="c:\Users\MuniUWU\Downloads\﹕　 ♡ᵎ   　𓈒　⁺　　sonico.gif" width="120">

    </div>

    <!-- MUSIC PLAYER -->

    <div class="box extra-box">

        <h3>music

        <audio id="bgMusic" loop>
            <source src="c:\Users\MuniUWU\Downloads\wensite\手描きワールドイズマインPV Hatsune Miku - World is Mine.mp3" type="audio/mpeg">
        </audio>

        <button class="music-btn"
        onclick="document.getElementById('bgMusic').play()">
           play music
        </button>

        

        


        </a>

    </div>

</div>

</div>

</main>

<!-- DERECHA -->

<aside>

<div class="box featured">
<h3></h3>

<img src="c:\Users\MuniUWU\Downloads\﹒               ♡          ⊹                                                 ₊ (1).gif">
<p>
        so cute 
</p>

<style>
/* EXTRA BOXES */

.extras{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:15px;
    margin-top:15px;
}

.extra-box{
    min-height:220px;
}

.extra-box textarea{
    width:100%;
    height:120px;
    resize:none;
    border:2px solid #f3a9c7;
    border-radius:10px;
    padding:10px;
    font-family:'Fredoka',sans-serif;
    background:#fff8fb;
}

.cute-btn{
    margin-top:10px;
    background:#ffd6ea;
    border:2px solid #f3a9c7;
    padding:8px 15px;
    border-radius:10px;
    cursor:pointer;
    font-family:'Fredoka',sans-serif;
}

.cute-btn:hover{
    background:#ffe4f1;
}

.counter{
    background:#ffe4f1;
    padding:15px;
    border-radius:10px;
    text-align:center;
    margin:10px 0;
    font-size:1.1rem;
}

.music-btn{
    background:linear-gradient(#ffd6ea,#ffc0dc);
    border:2px solid #f3a9c7;
    border-radius:20px;
    padding:12px 24px;
    color:#a85c87;
    font-family:'Fredoka',sans-serif;
    font-size:1rem;
    font-weight:bold;
    cursor:pointer;
    box-shadow:
        0 0 10px rgba(255,192,220,.8),
        3px 3px 0 #f3a9c7;
    transition:.2s;
}

.music-btn:hover{
    background:#ffe4f1;
    transform:translateY(-2px);
}

.music-btn:active{
    transform:translateY(2px);
}

.extra-box a{
    color:#d977a9;
    text-decoration:none;
    font-weight:bold;
}






</style>

</div>


<div class="box">

<h3>my favorite songs</h3>

<p>
word is mine - Hatsune Miku<br>
teto territory - Kasane Teto<br>
tuna song - Luka <br>
Luka Luka night fever - luka
</p> 

   <img src="c:\Users\MuniUWU\Downloads\﹕　 ♡ᵎ   　𓈒　⁺　　chocola (1).gif" style="width:100%; border-radius:10px;">
</div>

</div>

</aside>

</div>

<footer>
uwu© 2025
</footer>

</div>





<button class="music-btn"

onclick="document.getElementById('bgMusic').play()">

music :v
</button>

</div>
</body>
</html>

```


