
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ร้านข้าวไก่ทอด</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
    }

    header {
      background: #000;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      color: orange;
      margin: 0;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
    }

    nav a:hover {
      color: orange;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1606755962773-d324e2b0e4d5');
      background-size: cover;
      background-position: center;
    }

    .hero h2 {
      font-size: 60px;
      color: orange;
    }

    .hero p {
      font-size: 20px;
      margin: 20px 0;
    }

    .btn {
      background: orange;
      color: #000;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    .menu {
      padding: 50px 20px;
      text-align: center;
    }

    .menu h2 {
      color: orange;
    }

    .menu-items {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .item {
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
    }

    .item img {
      width: 100%;
      border-radius: 10px;
    }

    .item h3 {
      margin: 10px 0;
      color: orange;
    }

    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 14px;
      color: #aaa;
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <h1>new</h1>
    <nav>
      <a href="#">หน้าแรก</a>
      <a href="#">เมนู</a>
      <a href="#">ติดต่อ</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero">
    <h2>new!</h2>
    <p>อิ่ม เร็ว อร่อย ในราคาที่กินได้ทุกวัน</p>
    <a href="#" class="btn">สั่งเลย</a>
  </section>

  <!-- MENU -->
  <section class="menu">
    <h2>เมนูแนะนำ</h2>
    <div class="menu-items">

      <div class="item">
        <img src="download.jpg">
        <h3>menu1</h3>
        <p>เผ็ดหวาน เข้มข้น</p>
      </div>

      <div class="item">
        <img src="download1.jpg">
        <h3>menu2</h3>
        <p>กลมกล่อม หอมละมุน</p>
      </div>

      <div class="item">
        <img src="download2.jpg">
        <h3>menu3</h3>
        <p>เข้มข้น หอมเครื่องเทศ</p>
      </div>

    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2xxx ร้านxxxx | โทร: 08x-xxx-xxxx
  </footer>

</body>
</html>
