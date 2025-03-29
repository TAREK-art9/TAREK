<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>المطبخ المغربي</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f8f1e4;
      font-family: 'Segoe UI', sans-serif;
      direction: rtl;
    }
    header {
      background-color: #b65d1f;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 30px;
      max-width: 1200px;
      margin: auto;
    }
    .dish {
      background-color: white;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }
    .dish:hover {
      transform: scale(1.05);
    }
    .dish img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .dish-content {
      padding: 15px;
    }
    .dish-content h2 {
      color: #b65d1f;
      margin: 0 0 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #b65d1f;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>المطبخ المغربي</h1>
    <p>اكتشف سحر الأكل المغربي 🇲🇦</p>
  </header>

  <div class="container">
    <div class="dish">
      <img src="koskos.png" alt="كسكس">
      <div class="dish-content">
        <h2>الكسكس</h2>
        <p>طبق تقليدي من السميد مع الخضر واللحم أو الدجاج. يُقدّم عادةً يوم الجمعة.</p>
      </div>
    </div>

    <div class="dish">
      <img src="tajine.png" alt="طاجين">
      <div class="dish-content">
        <h2>الطاجين</h2>
        <p>طبق يُطهى ببطء مع التوابل واللحم أو الدجاج أو السمك. يُقدّم مع الخبز.</p>
      </div>
    </div>

    <div class="dish">
      <img src="bstila.jpg" alt="بسطيلة">
      <div class="dish-content">
        <h2>البسطيلة</h2>
        <p>فطيرة حلوة ومالحة بالدجاج أو الحمام واللوز والقرفة.</p>
      </div>
    </div>

    <div class="dish">
      <img src="hrira.jpg" alt="حريرة">
      <div class="dish-content">
        <h2>الحريرة</h2>
        <p>حساء مغربي تقليدي بالعدس والحمص والطماطم والتوابل. مشهور في رمضان.</p>
      </div>
    </div>

    <div class="dish">
      <img src="msmn.png" alt="مسمن">
      <div class="dish-content">
        <h2>المسمن</h2>
        <p>فطائر مغربية مربعة تُقدّم غالبًا مع العسل والشاي بالنعناع.</p>
      </div>
    </div>

    <div class="dish">
      <img src="briwat.png" alt="بريوات">
      <div class="dish-content">
        <h2>البريوات</h2>
        <p>معجنات صغيرة محشوة باللحم أو الدجاج أو اللوز، مقلية أو مشوية.</p>
      </div>
    </div>
  </div>

  <footer>
    &copy; ٢٠٢٥ المطبخ المغربي. جميع الحقوق محفوظة.
  </footer>
</body>
</html>
