<!DOCTYPE html>
<html>
<head>
  <title>Contoh Website Responsif dengan JavaScript</title>
  <style>
    /* Gaya untuk tampilan umum */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Gaya untuk tampilan layar lebar */
    @media screen and (min-width: 768px) {
      .container {
        width: 960px;
        margin: 0 auto;
      }
      .column {
        width: 50%;
        float: left;
      }
    }

    /* Gaya untuk tampilan layar sempit */
    @media screen and (max-width: 767px) {
      .container {
        width: 100%;
        padding: 10px;
      }
      .column {
        width: 100%;
        float: none;
        margin-bottom: 10px;
      }
    }

    /* Gaya tambahan */
    .header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .content {
      padding: 20px;
      background-color: #f9f9f9;
    }
    .footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    .button {
      background-color: #4CAF50;
      border: none;
      color: #fff;
      padding: 10px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      margin: 4px 2px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Website Responsif dengan JavaScript</h1>
    </div>
    <div class="content">
      <div class="column">
        <h2>Konten 1</h2>
        <p>Ini adalah konten 1.</p>
        <button class="button" onclick="gantiWarna()">Ganti Warna</button>
      </div>
      <div class="column">
        <h2>Konten 2</h2>
        <p>Ini adalah konten 2.</p>
        <button class="button" onclick="gantiUkuran()">Ganti Ukuran</button>
      </div>
    </div>
    <div class="footer">
<!DOCTYPE html>
<html>
<head>
  <title>Contoh Website Responsif dengan JavaScript</title>
  <style>
    /* Gaya untuk tampilan umum */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Gaya untuk tampilan layar lebar */
    @media screen and (min-width: 768px) {
      .container {
        width: 960px;
        margin: 0 auto;
      }
      .column {
        width: 50%;
        float: left;
      }
    }

    /* Gaya untuk tampilan layar sempit */
    @media screen and (max-width: 767px) {
      .container {
        width: 100%;
        padding: 10px;
      }
      .column {
        width: 100%;
        float: none;
        margin-bottom: 10px;
      }
    }

    /* Gaya tambahan */
    .header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .content {
      padding: 20px;
      background-color: #f9f9f9;
    }
    .footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    .button {
      background-color: #4CAF50;
      border: none;
      color: #fff;
      padding: 10px 20px;
      text-align: center;
      text-decoration: none;
      display: inline-block;
      font-size: 16px;
      margin: 4px 2px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Website Responsif dengan JavaScript</h1>
    </div>
    <div class="content">
      <div class="column">
        <h2>Konten 1</h2>
        <p>Ini adalah konten 1.</p>
        <button class="button" onclick="gantiWarna()">Ganti Warna</button>
      </div>
      <div class="column">
        <h2>Konten 2</h2>
        <p>Ini adalah konten 2.</p>
        <button class="button" onclick="gantiUkuran()">Ganti Ukuran</button>
      </div>
    </div>
    <div class="footer">
      &copy; 2023 Website Responsif. All rights reserved.
    </div>
  </div>

  <script>
    function gantiWarna() {
      var elem = document.querySelector('.content');
      elem.style.backgroundColor = getRandomColor();
    }

    function gantiUkuran() {
      var elem = document.querySelector('.column');
      var ukuran = Math.floor(Math.random() * 50) + 10;
      elem.style.fontSize = ukuran + 'px';
    }

    function getRandomColor() {
      var letters = '0123456789ABCDEF';
      var color = '#';
      for (var i = 0; i < 6; i++) {
        color += letters[Math.floor(Math.random() * 16)];
      }
      return color;
    }
  </script>
</body>
</html>
