<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday 🎉</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
    }

    body {
        height: 100vh;
        background: linear-gradient(135deg, #ff5edf, #04c8de);
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
    }

    .card {
        background: white;
        padding: 30px 40px;
        border-radius: 20px;
        text-align: center;
        box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        animation: pop 1s ease;
        max-width: 350px;
    }

    @keyframes pop {
        0% { transform: scale(0.5); opacity: 0; }
        100% { transform: scale(1); opacity: 1; }
    }

    h1 {
        font-size: 2.2rem;
        color: #ff4081;
        text-shadow: 0 0 10px #ff9ecb;
        animation: glow 2s infinite alternate;
    }

    @keyframes glow {
        from { text-shadow: 0 0 10px #ff9ecb; }
        to { text-shadow: 0 0 20px #ff4081; }
    }

    h2 {
        margin-top: 10px;
        color: #333;
    }

    p {
        margin-top: 20px;
        color: #555;
        font-size: 0.95rem;
    }

    .cake {
        font-size: 60px;
        margin: 15px 0;
        animation: bounce 1.5s infinite;
    }

    @keyframes bounce {
        0%,100% { transform: translateY(0); }
        50% { transform: translateY(-10px); }
    }

    .balloon {
        position: absolute;
        bottom: -100px;
        font-size: 40px;
        animation: float 6s linear infinite;
    }

    @keyframes float {
        from { transform: translateY(0); }
        to { transform: translateY(-120vh); }
    }
</style>
</head>

<body>

<div class="balloon" style="left:10%;">🎈</div>
<div class="balloon" style="left:40%; animation-delay:1s;">🎉</div>
<div class="balloon" style="left:70%; animation-delay:2s;">🎈</div>

<div class="card">
    <h1>Happy Birthday </h1>
    <h2>❤️ Purvii......❤️ </h2>
    <div class="cake">🎂</div>
    <p>
        MAY YOU ALWAYS BE HAPPY 
        AND KEEP SHINE,
  
       OR HAMESHA MUSKURATE RAHO💖
    </p>
</div>

</body>
</html>
