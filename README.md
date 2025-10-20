<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="پورتفولیوی حرفه‌ای محمد جواد تجدد با پس‌زمینه متحرک و پروژه‌های قابل کلیک">
  <title>پورتفولیوی محمد جواد تجدد</title>
  <link href="https://fonts.googleapis.com/css2?family=Shabnam:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    /* ===== پایه ===== */
    body {
      font-family: "Shabnam", sans-serif;
      margin:0;
      line-height:1.8;
      scroll-behavior:smooth;
      background: linear-gradient(-45deg, #121212, #1b5e20, #0d0d0d, #2e7d32);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      color:#e0e0e0;
    }
    a { text-decoration:none; color:inherit; transition:.3s; }
    a:hover { color:#fff; text-decoration:underline; }

    /* ===== نوار ناوبری ===== */
    nav {
      position:sticky;
      top:0;
      background:rgba(27,94,32,0.9);
      padding:1rem 2rem;
      display:flex;
      justify-content:flex-end;
      gap:1.5rem;
      z-index:1000;
      backdrop-filter: blur(5px);
      box-shadow:0 2px 12px rgba(0,0,0,.6);
    }
    nav a { color:#fff; font-weight:600; }
    nav a:hover { color:#c8e6c9; }

    /* ===== هدر ===== */
    header { text-align:center; padding:4rem 1rem 2rem; }
    header h1 { color:#a5d6a7; font-size:2.4rem; margin-bottom:.5rem; text-shadow:0 0 20px #66bb6a88; }
    header p.subtitle { color:#bdbdbd; font-size:1.2rem; }

    /* ===== بخش‌ها ===== */
    section { padding:2rem 1rem; max-width:900px; margin:auto; }
    h2 { color:#81c784; border-right:4px solid #66bb6a; padding-right:10px; margin-bottom:1rem; }

    /* ===== کارت‌ها ===== */
    .grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:1rem; }
    .card {
      background:rgba(30,30,30,0.9);
      border-radius:12px;
      padding:1rem;
      box-shadow:0 6px 18px rgba(0,0,0,.6);
      border:1px solid #66bb6a;
      transition:.3s;
      backdrop-filter: blur(5px);
    }
    .card:hover { transform:translateY(-7px) scale(1.03); border-color:#a5d6a7; box-shadow:0 10px 25px rgba(0,0,0,.8); }
    .card h3 { margin-top:0; color:#a5d6a7; }

    /* ===== فوتر ===== */
    footer { background:#1b5e20; color:#fff; text-align:center; padding:1rem; font-size:.9rem; margin-top:2rem; text-shadow:0 0 10px #66bb6a55; }

    /* ===== ریسپانسیو ===== */
    @media(max-width:600px){
      nav { justify-content:center; flex-wrap:wrap; gap:1rem; }
    }

    /* ===== انیمیشن‌ها ===== */
    .fade { opacity:0; transform:translateY(25px); animation:fadeUp 1s forwards; }
    .fade.delay-1{ animation-delay:.2s; }
    .fade.delay-2{ animation-delay:.4s; }
    .fade.delay-3{ animation-delay:.6s; }

    @keyframes fadeUp {
      to { opacity:1; transform:translateY(0); }
    }
    @keyframes gradientBG {
      0%{background-position:0% 50%;}
      50%{background-position:100% 50%;}
      100%{background-position:0% 50%;}
    }
  </style>
</head>
<body>

  <nav>
    <a href="#about">درباره من</a>
    <a href="#skills">مهارت‌ها</a>
    <a href="#projects">پروژه‌ها</a>
    <a href="#contact">تماس</a>
  </nav>

  <header>
    <h1 class="fade">👋 سلام! من محمد جواد تجدد هستم</h1>
    <p class="subtitle fade delay-1">برنامه‌نویس محیط زیستی | عاشق یادگیری و ساختن</p>
  </header>

  <section id="about" class="fade delay-2">
    <h2>درباره من</h2>
    <p>من یه برنامه‌نویس تازه‌کارم که عاشق ساختن وب‌سایت‌ها، وب اپلیکیشن و اپلیکیشن‌های کاربردی‌ام. هدفم اینه که مهارت‌هامو در زمینه‌ی HTML، CSS، JavaScript و C# توسعه بدم و پروژه‌های جالب‌تری بسازم.</p>
  </section>

  <section id="skills" class="fade delay-3">
    <h2>مهارت‌ها</h2>
    <div class="grid">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">JavaScript</div>
      <div class="card">Git & GitHub</div>
      <div class="card">C#</div>
    </div>
  </section>

  <section id="projects" class="fade delay-1">
    <h2>پروژه‌ها</h2>
    <div class="grid">
      <a href="https://javadtajadod1372.github.io/driver/" class="card" aria-label="فرم ثبت نام رانندگی — مشاهده پروژه">
        <h3>📝 فرم ثبت نام رانندگی</h3>
        <p>یک فرم ساده و کاربردی برای ثبت اطلاعات کاربران جهت دریافت گواهینامه رانندگی.</p>
        <div style="margin-top:12px; text-align:left;">
    <a href="driver/driver.html" class="btn" style="padding:8px 12px; font-size:0.95rem;">مشاهده پروژه</a>
  </div>
</a>
      </a>
      <a href="#" class="card" aria-label="سایت رزرواسیون هتل">
        <h3>🏨 سایت رزرواسیون هتل</h3>
        <p>یک وب‌سایت برای رزرو آنلاین هتل‌ها با نمایش لیست اتاق‌ها، قیمت‌ها و امکانات.</p>
      </a>
      <a href="#" class="card" aria-label="وب‌سایت شخصی">
        <h3>💻 وب‌سایت شخصی</h3>
        <p>همین وب‌سایتی که الان می‌بینید! برای معرفی و نمایش پروژه‌هام ساخته شده.</p>
      </a>
    </div>
  </section>

  <section id="contact" class="fade delay-2">
    <div class="card">
      <h3>تماس با من</h3>
      <p>📞 شماره تماس: 09117621323</p>
      <p>📧 ایمیل: <a href="mailto:mj_tajaddod@yahoo.com">mj_tajaddod@yahoo.com</a></p>
    </div>
  </section>

  <footer>✨ ساخته شده توسط محمد جواد تجدد ✨</footer>

</body>
</html>

