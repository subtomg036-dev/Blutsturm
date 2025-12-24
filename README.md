<!DOCTYPE html>
<html lang="ka">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BlutSturm - მეტალ ჯგუფი</title>
<link href="https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap" rel="stylesheet">
<style>
    /* დინამიური gradient ფონური ეფექტი */
    @keyframes gradientShift {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    body {
        margin: 0;
        font-family: Arial, sans-serif;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        min-height: 100vh;

        /* Gradient background */
        background: linear-gradient(90deg, #00bfff, #001f4d);
        background-size: 200% 200%;
        animation: gradientShift 15s ease infinite;

        color: #ffffff;
    }

    h1 {
        font-family: 'Metal Mania', cursive;
        font-size: 6em;
        margin-bottom: 20px;
        color: #00ffff;
        text-shadow: 2px 2px 4px #000000, 0 0 20px #00ffff;
    }

    .members {
        display: flex;
        flex-direction: column;
        gap: 15px;
        font-size: 1.5em;
        margin-bottom: 40px;
    }

    .member {
        background: rgba(0,0,0,0.3);
        padding: 10px 20px;
        border-radius: 10px;
        width: 350px;
        text-align: center;
        transition: transform 0.3s;
    }

    .member:hover {
        transform: scale(1.05);
        background: rgba(0,0,0,0.6);
    }

    .socials {
        display: flex;
        gap: 20px;
        font-size: 1.8em;
    }

    .socials a {
        color: #ffffff;
        text-decoration: none;
        transition: transform 0.3s, color 0.3s;
    }

    .socials a:hover {
        transform: scale(1.2);
        color: #ffcc00;
    }
</style>
</head>
<body>
    <h1>BlutSturm 🤘🔥</h1>
    <div class="members">
        <div class="member">🎤 გიორგი წიქარიშვილი - ვოკალი</div>
        <div class="member">🎹 საბა კაპანაძე - სინთეზატორი</div>
        <div class="member">🥁 გოჩა მეყანწიშვილი - დრამერი</div>
        <div class="member">🎸 გიორგი ფერაძე - გიტარა</div>
        <div class="member">🎸 ნიკა ნეკერაშვილი - გიტარა</div>
        <div class="member">🎸 ნიკა მაღლაკელიძე - გიტარა</div>
    </div>

    <div class="socials">
        <a href="https://www.tiktok.com" target="_blank">🎵 TikTok</a>
        <a href="https://www.youtube.com" target="_blank">📺 YouTube</a>
        <a href="https://www.instagram.com" target="_blank">📸 Instagram</a>
        <a href="https://www.twitter.com" target="_blank">🐦 Twitter</a>
    </div>
</body>
</html>
