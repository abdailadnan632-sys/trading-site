<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>منصة تداول</title>
  <style>
    body {margin:0;font-family:Tahoma,Arial;background:#0f172a;color:#e5e7eb;}
    header {background:#020617;padding:20px;text-align:center;}
    header h1 {margin:0;color:#38bdf8;}
    nav {display:flex;justify-content:center;gap:25px;background:#020617;padding:12px;}
    nav a {color:#e5e7eb;text-decoration:none;font-weight:bold;}
    nav a:hover {color:#38bdf8;}
    .container {max-width:1200px;margin:auto;padding:25px;}
    .stats {display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;}
    .box {background:#020617;border-radius:16px;padding:20px;box-shadow:0 10px 30px rgba(0,0,0,0.4);}    
    .box h3 {margin-top:0;color:#38bdf8;}
    table {width:100%;border-collapse:collapse;margin-top:15px;}
    th,td {padding:12px;text-align:center;border-bottom:1px solid #1e293b;}
    th {color:#38bdf8;}
    .buy {color:#22c55e;font-weight:bold;}
    .sell {color:#ef4444;font-weight:bold;}
    footer {background:#020617;text-align:center;padding:15px;color:#94a3b8;margin-top:40px;}
    button {background:#38bdf8;color:#020617;border:none;padding:10px 20px;border-radius:12px;cursor:pointer;font-weight:bold;}
    button:hover {background:#0ea5e9;}
  </style>
</head>
<body><header>
  <h1>منصة التداول الذكية</h1>
  <p>تابع الأسواق – حلّل – اتخذ قرارك</p>
</header><nav>
  <a href="#dashboard">لوحة التحكم</a>
  <a href="#markets">الأسواق</a>
  <a href="#signals">الإشارات</a>
  <a href="#account">الحساب</a>
</nav><div class="container" id="dashboard">
  <h2>لوحة التحكم</h2>
  <div class="stats">
    <div class="box"><h3>الرصيد</h3><p>$10,250</p></div>
    <div class="box"><h3>الأرباح اليومية</h3><p class="buy">+$320</p></div>
    <div class="box"><h3>الصفقات المفتوحة</h3><p>3</p></div>
    <div class="box"><h3>نسبة المخاطرة</h3><p>2%</p></div>
  </div>
</div><div class="container" id="markets">
  <h2>الأسواق</h2>
  <div class="box">
    <table>
      <tr>
        <th>الأصل</th>
        <th>السعر</th>
        <th>الاتجاه</th>
        <th>تنفيذ</th>
      </tr>
      <tr>
        <td>BTC / USD</td>
        <td>42,300</td>
        <td class="buy">شراء</td>
        <td><button>تنفيذ</button></td>
      </tr>
      <tr>
        <td>ETH / USD</td>
        <td>2,250</td>
        <td class="sell">بيع</td>
        <td><button>تنفيذ</button></td>
      </tr>
      <tr>
        <td>Gold</td>
        <td>2021</td>
        <td class="buy">شراء</td>
        <td><button>تنفيذ</button></td>
      </tr>
    </table>
  </div>
</div><div class="container" id="signals">
  <h2>إشارات التداول (مباشر)</h2>
  <div class="stats">
    <div class="box"><h3>EUR/USD</h3><p class="buy">شراء – دخول 1.090</p></div>
    <div class="box"><h3>BTCUSDT</h3><p class="sell">بيع – دخول 42300</p></div>
    <div class="box"><h3>XAUUSD</h3><p class="buy">شراء – دخول 2015</p></div>
  </div>
</div><div class="container" id="chart">
  <h2>الشارت المباشر</h2>
  <div class="box">
    <div id="tradingview_widget"></div>
  </div>
</div><script type="text/javascript" src="https://s3.tradingview.com/tv.js"></script><script type="text/javascript">
  new TradingView.widget({
    "container_id": "tradingview_widget",
    "symbol": "BINANCE:BTCUSDT",
    "interval": "15",
    "timezone": "Asia/Baghdad",
    "theme": "dark",
    "style": "1",
    "locale": "ar",
    "toolbar_bg": "#020617",
    "enable_publishing": false,
    "allow_symbol_change": true,
    "hide_top_toolbar": false,
    "width": "100%",
    "height": 500
  });
</script><div class="box"><h3>BTC</h3><p class="sell">بيع – هدف 41,800</p></div>
<div class="box"><h3>XAUUSD</h3><p class="buy">شراء – هدف 2040</p></div>

  </div>
</div><div class="container" id="account">
  <h2>الحساب</h2>
  <div class="box">
    <p>👤 اسم المستخدم: Trader01</p>
    <p>📊 نوع الحساب: تجريبي</p>
    <button>تسجيل خروج</button>
  </div>
</div><footer>
  © 2026 منصة تداول – جميع الحقوق محفوظة
</footer></body>
</html>
