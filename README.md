<html lang="uk">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>METRO SHOP</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Montserrat',sans-serif;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
    position:relative;

    background:
    linear-gradient(145deg,#0d0f12,#1a1d22,#090a0d);
}

/* Фонове світіння */

body::before{
    content:'';
    position:absolute;
    width:600px;
    height:600px;
    background:#5e6670;
    filter:blur(200px);
    opacity:0.12;
    top:-250px;
    left:-200px;
}

body::after{
    content:'';
    position:absolute;
    width:500px;
    height:500px;
    background:#2e333a;
    filter:blur(180px);
    opacity:0.14;
    bottom:-220px;
    right:-180px;
}

/* Карточка */

.card{
    width:90%;
    max-width:430px;

    padding:38px 28px;

    border-radius:34px;

    background:
    rgba(22,24,28,0.82);

    backdrop-filter:blur(18px);

    border:
    1px solid rgba(255,255,255,0.06);

    box-shadow:
    0 0 40px rgba(0,0,0,0.45),
    inset 0 0 15px rgba(255,255,255,0.02);

    position:relative;
    z-index:2;
}

/* Верхній текст */

.logo{
    text-align:center;
    color:white;

    font-size:38px;
    font-weight:800;

    margin-bottom:30px;

    text-shadow:
    0 0 15px rgba(255,255,255,0.10);
}

/* Кнопки */

.btn{
    width:100%;

    display:flex;
    align-items:center;
    justify-content:center;
    gap:14px;

    text-decoration:none;
    color:#fff;

    font-size:22px;
    font-weight:700;

    padding:21px;

    border-radius:22px;

    margin-bottom:18px;

    background:
    linear-gradient(145deg,
    #4c525b,
    #2a2f36);

    border:
    1px solid rgba(255,255,255,0.05);

    box-shadow:
    0 6px 20px rgba(0,0,0,0.35),
    inset 0 1px 0 rgba(255,255,255,0.04);

    transition:0.25s ease;
}

/* Hover */

.btn:hover{
    transform:
    translateY(-4px)
    scale(1.02);

    background:
    linear-gradient(145deg,
    #616975,
    #353b44);

    box-shadow:
    0 10px 30px rgba(0,0,0,0.45);
}

/* Іконки */

.icon{
    font-size:28px;
    filter:drop-shadow(0 0 6px rgba(255,255,255,0.15));
}

/* Адаптив */

@media(max-width:500px){

    .logo{
        font-size:32px;
    }

    .btn{
        font-size:20px;
        padding:19px;
    }

}

</style>
</head>

<body>

<div class="card">

    <div class="logo">
        Тицяй сюди 👇
    </div>

    <a class="btn" href="https://t.me/nagrani1233" target="_blank">
        <span class="icon">✈️</span>
        Наш TGK
    </a>

    <a class="btn" href="https://t.me/naGraniucshop" target="_blank">
        <span class="icon">💎</span>
        UC Shop
    </a>

    <a class="btn" href="https://t.me/naGranishop" target="_blank">
        <span class="icon">🎯</span>
        Metro Shop
    </a>

    <a class="btn" href="https://send.monobank.ua/jar/GxnmfnNyw" target="_blank">
        <span class="icon">❤️</span>
        Донат
    </a>

</div>

</body>
</html>
