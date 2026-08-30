<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>روستای سرسبز قلعتین</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Tahoma, sans-serif;
            background: #f4f8f3;
        }

        .hero {
            width: 100%;
            height: 450px;
            background-image: url("roosta.jpg");
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .hero::before {
            content: "";
            position: absolute;
            inset: 0;
            background: rgba(0, 0, 0, 0.35);
        }

        .hero-text {
            position: relative;
            color: white;
            text-align: center;
        }

        .hero-text h1 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero-text p {
            font-size: 20px;
        }

        .content {
            padding: 35px 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <section class="hero">
        <div class="hero-text">
            <h1>روستای سرسبز قلعتین</h1>
            <p>نگینی زیبا در استان مرکزی</p>
        </div>
    </section>

    <div class="content">
        <h2>به روستای قلعتین خوش آمدید 🌿</h2>
        <p>اینجا معرفی روستا، طبیعت زیبا و جاذبه‌های قلعتین را خواهیم داشت.</p>
    </div>

</body>
</html>
