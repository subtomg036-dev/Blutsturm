<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlutSturm | Metal Band</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #001a66; /* ლურჯი background */
            color: #ffffff;
        }
        header {
            text-align: center;
            padding: 60px 20px;
            background: #003399;
        }
        header h1 {
            font-size: 60px;
            margin: 0;
            color: #66ccff;
        }
        header p {
            font-size: 18px;
            opacity: 0.85;
            margin-top: 10px;
        }
        section {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }
        h2 {
            font-size: 28px;
            color: #66ccff;
            margin-bottom: 20px;
        }
        .members {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .member {
            background: #002266;
            padding: 15px;
            text-align: center;
            border-radius: 6px;
            transition: transform 0.2s;
        }
        .member:hover {
            transform: translateY(-3px);
        }
        .member h3 {
            margin: 5px 0;
            font-size: 20px;
        }
        .member span {
            font-size: 16px;
            opacity: 0.9;
        }
        .about {
            background: #002266;
            padding: 20px;
            border-left: 4px solid #66ccff;
            margin-bottom: 30px;
        }
        .socials {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .socials a {
            color: #ffffff;
            text-decoration: none;
            font-size: 16px;
            border: 1px solid #66ccff;
            padding: 8px 15px;
            border-radius: 5px;
            transition: background 0.2s;
        }
        .socials a:hover {
            background: #66ccff;
            color: #000;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #003399;
            font-size: 14px;
            opacity: 0.85;
        }
    </style>
</head>
<body>

<header>
    <h1>BlutSturm</h1>
    <p>ქართული მეტალ ჯგუფი</p>
</header>

<section>
    <h2>ჩვენს შესახებ</h2>
    <div class="about">
        BlutSturm არის ქართული მეტალ ჯგუფი, რომელიც აერთიანებს მძიმე რიფებს,
        ენერგიას და ბნელ ატმოსფეროს. ჩვენი მუსიკა არის სიბნელის,
        ძალის და თავისუფლების გამოხატულება.
    </div>
</section>

<section>
    <h2>ჯგუფის წევრები</h2>
    <div class="members">
        <div class="member">
            <h3>გიორგი წიქარიშვილი 🎤</h3>
            <span>ვოკალი</span>
        </div>
        <div class="member">
            <h3>საბა კაპანაძე 🎹</h3>
            <span>სინთეზატორი</span>
        </div>
        <div class="member">
            <h3>გოჩა მეყანწიშვილი 🥁</h3>
            <span>დრამერი</span>
        </div>
        <div class="member">
            <h3>გიორგი ფერაძე 🎸</h3>
            <span>ბასი</span>
        </div>
        <div class="member">
            <h3>ნიკა ნეკერაშვილი 🎸</h3>
            <span>გიტარა</span>
        </div>
        <div class="member">
            <h3>ნიკა მაღლაკელიძე 🎸</h3>
            <span>გიტარა</span>
        </div>
    </div>
</section>

<section>
    <h2>სოციალური ქსელები</h2>
    <div class="socials">
        <a href="#">YouTube</a>
        <a href="#">Instagram</a>
        <a href="#">Facebook</a>
    </div>
</section>

<footer>
    © 2025 BlutSturm | All Rights Reserved
</footer>

</body>
</html>
