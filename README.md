<style>
  body {
    font-family: "Shabnam", sans-serif;
    background:#121212;
    color:#e0e0e0;
    margin:0;
    line-height:1.8;
  }
  h2 {
    color:#81c784;
    border-right:4px solid #66bb6a;
    padding-right:10px;
  }
  section{padding:2rem;direction:rtl;text-align:right;}
  .skills,.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:1rem;margin-top:1rem;
  }
  .card{
    background:#1e1e1e;
    border-radius:12px;
    padding:1rem;
    box-shadow:0 4px 10px rgba(0,0,0,.4);
    border:1px solid #2e7d32;
    transition:.3s;
  }
  .card:hover{
    transform:translateY(-5px);
    border-color:#66bb6a;
    box-shadow:0 6px 14px rgba(0,0,0,.6);
  }
  a{color:#a5d6a7;text-decoration:none;}
  a:hover{color:#fff;text-decoration:underline;}
  footer{
    background:#1b5e20;
    color:#fff;
    text-align:center;
    padding:1rem;
    font-size:.9rem;
  }
</style>

<section>
  <h2>درباره من</h2>
  <p>
    من یه برنامه‌نویس تازه‌کارم که عاشق ساختن وب‌سایت‌ها، وب اپلیکیشن و اپلیکیشن‌های کاربردی‌ام.
    هدفم اینه که مهارت‌هامو در زمینه‌ی HTML، CSS، JavaScript و C# توسعه بدم و پروژه‌های جالب‌تری بسازم.
  </p>
</section>

<section>
  <h2>مهارت‌ها</h2>
  <div class="skills">
    <div class="card">HTML</div>
    <div class="card">CSS</div>
    <div class="card">JavaScript</div>
    <div class="card">Git & GitHub</div>
    <div class="card">C#</div>
  </div>
</section>

<section>
  <h2>پروژه‌ها</h2>
  <div class="projects">
    <div class="card">
      <h3>📝 فرم ثبت نام رانندگی</h3>
      <p>یک فرم ساده و کاربردی برای ثبت اطلاعات کاربران جهت دریافت گواهینامه رانندگی.</p>
    </div>
    <div class="card">
      <h3>🏨 سایت رزرواسیون هتل</h3>
      <p>یک وب‌سایت برای رزرو آنلاین هتل‌ها با نمایش لیست اتاق‌ها، قیمت‌ها و امکانات.</p>
    </div>
    <div class="card">
      <h3>💻 وب‌سایت شخصی</h3>
      <p>همین وب‌سایتی که الان می‌بینید! برای معرفی و نمایش پروژه‌هام ساخته شده.</p>
    </div>
  </div>
</section>

<section>
  <div class="card">
    <h3>تماس با من</h3>
    <p>📞 شماره تماس: 09117621323</p>
    <p>📧 ایمیل: <a href="mailto:mj_tajaddod@yahoo.com">mj_tajaddod@yahoo.com</a></p>
  </div>
</section>

<footer>✨ ساخته‌ شده توسط محمد جواد تجدد ✨</footer>
