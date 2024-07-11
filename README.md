<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #6a0dad;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #4b0082;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #6a0dad;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>我的個人網站</h1>
    </header>
    <nav>
        <a href="#about">關於我</a>
        <a href="#contact">聯絡資訊</a>
        <a href="#blog">博客文章</a>
    </nav>
    <section id="about">
        <h2>關於我</h2>
        <p>這裡是你的個人簡介。</p>
    </section>
    <section id="contact">
        <h2>聯絡資訊</h2>
        <p>這裡是你的聯絡資訊。</p>
    </section>
    <section id="blog">
        <h2>博客文章</h2>
        <p>這裡是你的博客文章。</p>
    </section>
    <footer>
        <p>© 2024 我的個人網站</p>
    </footer>
</body>
</html>
