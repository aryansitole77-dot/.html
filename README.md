<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Purvii 🎉</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    height:100vh;
    background: radial-gradient(circle at top, #ff9a9e, #fad0c4, #fad0c4);
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
}

.card{
    background:white;
    padding:35px 45px;
    border-radius:25px;
    text-align:center;
    box-shadow:0 25px 60px rgba(0,0,0,0.3);
    animation:zoomIn 1s ease;
    max-width:360px;
    z-index:2;
}

@keyframes zoomIn{
    from{transform:scale(0);opacity:0;}
    to{transform:scale(1);opacity:1;}
}

h1{
    font-size:2.4rem;
    color:#ff2d75;
    text-shadow:0 0 15px #ff9ecb;
    animation:glow 2s infinite alternate;
}

@keyframes glow{
    from{text-shadow:0 0 10px #ff9ecb;}
    to{text-shadow:0 0 25px #ff2d75;}
}

h2{
    margin-top:10px;
    color:#333;
}

.cake{
    font-size:70px;
    margin:20px 0;
    animation:bounce 1.5s infinite;
}

@keyframes bounce{
    0%,100%{transform:translateY(0);}
    50%{transform:translateY(-12px);}
}

p{
    margin-top:15px;
    font-size:1rem;
    color:#555;
    line-height:1.6;
}

/* Floating Hearts */
.heart{
    position:absolute;
    bottom:-50px;
    font-size:25px;
    animation:floatUp 6s linear infinite;
}

@keyframes floatUp{
    from{transform:translateY(0);opacity:1;}
    to{transform:translateY(-120vh);opacity:0;}
}

/* Fireworks dots */
.spark{
    position:absolute;
    width:6px;
    height:6px;
    background:#fff;
    border-radius:50%;
    animation:sparkle 1.5s infinite;
}

@keyframes sparkle{
    0%{transform:scale(0);opacity:1;}
    100%{transform:scale(1.8);opacity:0;}
}
</style>
</head>

<body>

<!-- Hearts -->
<div class="heart" style="left:10%">💖</div>
<div class="heart" style="left:30%;animation-delay:1s;">💘</div>
<div class="heart" style="left:50%;animation-delay:2s;">❤️</div>
<div class="heart" style="left:70%;animation-delay:3s;">💞</div>
<div class="heart" style="left:90%;animation-delay:4s;">💕</div>

<!-- Card -->
<div class="card">
    <h1>Happy Birthday 🎉</h1>
    <h2>❤️ Purvii ❤️</h2>
    <div class="cake">🎂</div>
    <p>
        May you always stay happy,<br>
        keep shining like a star ✨<br><br>
        Aur hamesha aise hi<br>
        muskurati raho 💖
    </p>
</div>

<!-- Fireworks -->
<script>
for(let i=0;i<25;i++){
    let spark=document.createElement("div");
    spark.className="spark";
    spark.style.left=Math.random()*100+"vw";
    spark.style.top=Math.random()*100+"vh";
    spark.style.animationDelay=Math.random()*2+"s";
    document.body.appendChild(spark);
}
</script>

</body>
</html>
