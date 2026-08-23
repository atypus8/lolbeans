Canvaのデザイン
      ↓
デザインを確認・画像素材を用意
      ↓
HTML + CSS + JavaScriptを作成
      ↓
index.html
style.css
script.js
images/
      ↓
Netlifyにアップロード
      ↓
https://○○.netlify.app/

<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PSM</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>PSM</h1>

    <nav>
        <a href="index.html">HOME</a>
        <a href="members.html">MEMBERS</a>
        <a href="about.html">ABOUT</a>
    </nav>
</header>

<main>
    <h2>PSM</h2>
    <p>Welcome to PSM.</p>
</main>

<script src="script.js"></script>

body {
    margin: 0;
    background: #000;
    color: #fff;
    font-family: Arial, sans-serif;
}

h1 {
    font-size: 60px;
    text-align: center;
}

p {
    text-align: center;
}

<a href="members.html">MEMBERS</a>


</body>
</html>
