<!DOCTYPE html>
<html lang="ka">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlutSturm | Metal Band</title>

    <!-- Google Font for Metal Style -->
    <link href="https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: radial-gradient(circle at top, #1a0000, #000000 70%);
            color: #f2f2f2;
        }
        header {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(180deg, #2b0000, #000000);
            border-bottom: 3px solid #8b0000;
        }
        header h1 {
            font-family: 'Metal Mania', cursive;
            font-size: 80px;
            letter-spacing: 6px;
            margin: 0;
            color: #b30000;
            text-shadow: 0 0 20px rgba(139,0,0,0.8);
        }
        header p {
            font-size: 18px;
            opacity: 0.85;
            margin-top: 15px;
        }
        section {
            max-width: 1000px;
            margin: 60px auto;
            padding: 0 20px;
        }
        h2 {
            font-family: 'Metal Mania', cursive;
            font-size: 36px;
            border-bottom: 2px solid #8b0000;
            padding-bottom: 10px;
            margin-bottom: 30px;
            color: #e60000;
        }
        .members {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
        }
        .member {
            background: #0d0d0d;
            border: 1px solid #2a0000;
            padding: 25px;
            text-align: center;
            border-radius: 8px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .member:hover {
            transform: translateY(-6px) scale(1.02);
            box-shadow: 0 15px 30px rgba(139,0,0,0.6);
        }
        .member h3 {
            margin: 0 0 10px 0;
            font-size: 20px;
        }
        .member span {
            font-size: 14px;
            opacity: 0.7;
        }
        .about {
            background: #0a0a0a;
            padding: 30px;
            border-left: 4px solid #8b0000;
            line-height: 1.6;
        }
        .socials {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 30px;
        }
        .socials a {
            color: #f2f2f2;
            text-decoration: none;
            font-size: 18px;
            border: 1px solid #8b0000;
            padding: 10px 18px;
            border-radius: 6px;
            transition: background 0.3s, color 0.3s;
        }
        .socials a:hover {
            background: #8b0000;
            color: #000;
        }
        footer {
            text-align: center;
            padding: 25px;
            background: #000;
            font-size: 14px;
            opacity: 0.75;
            border-top: 2px solid #2a0000;
        }
    </style>
</head>
<body>

<header>
    <h1>BlutSturm</h1>
    <p>ქართული მეტალ ჯგუფი • Heavy / Dark Metal</p>
</header>

<section>
    <h2>ჩვენს შესახებ</h2>
    <div class="about">
        BlutSturm არის ქართული მეტალ ჯგუფი, რომელიც აერთიანებს მძიმე რიფებს,
        აგრესიულ ენერგიას და ბნელ ატმოსფეროს. ჩვენი მუსიკა არის სიბნელის,
        ძალის და თავისუფლების გამოხატულება.
    </div>
</section>

<section>
    <h2>ჯგუფის წევრები</h2>
    <div class="members">
        <div class="member">
            <h3>გიორგი წიქარიშვილი</h3>
            <span>ვოკალი</span>
        </div>
        <div class="member">
            <h3>საბა კაპანაძე</h3>
            <span>სინთეზატორი</span>
        </div>
        <div class="member">
            <h3>გოჩა მეყანწიშვილი</h3>
            <span>დრამერი</span>
        </div>
        <div class="member">
            <h3>გიორგი ფერაძე</h3>
            <span>ბასი</span>
        </div>
        <div class="member">
            <h3>ნიკა ნეკერაშვილი</h3>
            <span>გიტარა</span>
        </div>
        <div class="member">
            <h3>ნიკა მაღლაკელიძე</h3>
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
