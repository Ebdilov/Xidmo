<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GameKey Market — Laboratoriya 1</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f3f5f7;
      color: #111;
    }

    header {
      background: #0b1a2a;
      color: #fff;
      padding: 18px 16px;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 16px;
    }

    nav a {
      color: #cfe6ff;
      text-decoration: none;
      margin-right: 12px;
      font-weight: 600;
    }

    nav a:hover { text-decoration: underline; }

    .hero {
      background: #ffffff;
      border-radius: 12px;
      padding: 18px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.08);
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 16px;
      align-items: center;
    }

    .badge {
      display: inline-block;
      padding: 6px 10px;
      border-radius: 999px;
      background: #e8f2ff;
      color: #0b1a2a;
      font-size: 12px;
      font-weight: 700;
    }

    h1 { margin: 10px 0 6px; }
    p { line-height: 1.5; }

    .hero img {
      width: 100%;
      border-radius: 12px;
      border: 1px solid #e6e9ee;
    }

    .grid {
      margin-top: 16px;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }

    .card {
      background: #fff;
      border-radius: 12px;
      padding: 14px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
      border: 1px solid #eef1f5;
    }

    .card h3 { margin: 6px 0 8px; }
    .price { font-size: 18px; font-weight: 800; }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 12px;
      border-radius: 10px;
      background: #0b63ff;
      color: #fff;
      text-decoration: none;
      font-weight: 700;
    }

    .btn:hover { filter: brightness(0.95); }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 14px;
      background: #fff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
      border: 1px solid #eef1f5;
    }

    th, td {
      padding: 12px;
      border-bottom: 1px solid #eef1f5;
      text-align: left;
    }

    th {
      background: #e8f2ff;
      color: #0b1a2a;
    }

    footer {
      margin-top: 18px;
      padding: 16px;
      background: #0b1a2a;
      color: #cfe6ff;
    }

    .note {
      font-size: 12px;
      color: #445;
      background: #fff7d6;
      padding: 10px 12px;
      border-radius: 10px;
      border: 1px solid #ffe59a;
      margin-top: 14px;
    }

    @media (max-width: 800px) {
      .hero { grid-template-columns: 1fr; }
      .grid { grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>
  <header>
    <div class="container">
      <strong>GameKey Market</strong>
      <nav style="margin-top:10px;">
        <a href="#mehsullar">Məhsullar</a>
        <a href="#kampaniya">Kampaniyalar</a>
        <a href="#qiymetler">Qiymət cədvəli</a>
        <a href="#elaqe">Əlaqə</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <span class="badge">Laboratoriya işi №1 — HTML + CSS</span>
        <h1>Rəqəmsal Oyun Məhsulları Mağazası</h1>
        <p>
          Bu səhifə HTML sənəd strukturu, mətn formatlaşdırılması, siyahılar,
          cədvəllər və CSS dizaynı mövzularını praktik göstərmək üçün hazırlanıb.
        </p>

        <p>
          <b>Qeyd:</b> Burada <i>qanuni</i> rəqəmsal məhsullar (məs: oyun açarı, gift card) nümunə kimi göstərilir.
          <u>Hesab alqı-satqısı</u> kimi qayda pozan fəaliyyətlər üçün istifadə etməyin.
        </p>

        <a class="btn" href="https://store.steampowered.com" target="_blank">Steam mağazasına bax</a>
      </div>

      <img src="https://via.placeholder.com/520x320.png?text=GameKey+Market" alt="Mağaza banneri">
    </section>

    <section id="mehsullar">
      <h2>Populyar məhsullar</h2>

      <div class="grid">
        <div class="card">
          <h3>Steam Gift Card (10$)</h3>
          <p class="price">19 AZN</p>
          <p><small>Rəqəmsal kod, e-poçta göndərilir.</small></p>
          <a class="btn" href="#elaqe">Sifariş et</a>
        </div>

        <div class="card">
          <h3>Oyun Açarı — “Example Game”</h3>
          <p class="price">29 AZN</p>
          <p><small>Region: Global (nümunə).</small></p>
          <a class="btn" href="#elaqe">Sifariş et</a>
        </div>

        <div class="card">
          <h3>Coaching (1 saat)</h3>
          <p class="price">15 AZN</p>
          <p><small>Discord üzərindən təlim (nümunə xidmət).</small></p>
          <a class="btn" href="#elaqe">Sifariş et</a>
        </div>
      </div>
    </section>

    <section id="kampaniya">
      <h2>Kampaniyalar (Siyahı nümunəsi)</h2>

      <p><b>Bu həftənin üstünlükləri:</b></p>
      <ul>
        <li>24 saat içində çatdırılma (nümunə)</li>
        <li>Endirim kuponu: <b>LAB1</b></li>
        <li>Dəstək: <i>09:00–22:00</i></li>
      </ul>

      <p><b>Satınalma addımları:</b></p>
      <ol>
        <li>Məhsulu seç</li>
        <li>Əlaqə məlumatını göndər</li>
        <li>Ödəniş et</li>
        <li>Kodu qəbul et</li>
      </ol>

      <hr>
    </section>

    <section id="qiymetler">
      <h2>Qiymət cədvəli (Cədvəl nümunəsi)</h2>

      <table>
        <tr>
          <th>Məhsul</th>
          <th>Növ</th>
          <th>Çatdırılma</th>
          <th>Qiymət</th>
        </tr>
        <tr>
          <td>Steam Gift Card 10$</td>
          <td>Rəqəmsal kod</td>
          <td>10-30 dəq (nümunə)</td>
          <td>19 AZN</td>
        </tr>
        <tr>
          <td>Oyun Açarı “Example Game”</td>
          <td>Rəqəmsal açar</td>
          <td>1-2 saat (nümunə)</td>
          <td>29 AZN</td>
        </tr>
        <tr>
          <td>Coaching 1 saat</td>
          <td>Xidmət</td>
          <td>Razılaşma ilə</td>
          <td>15 AZN</td>
        </tr>
      </table>

      <div class="note">
        Bu cədvəl laboratoriyada “veb-səhifələr üçün cədvəllərin qurulması” hissəsini qarşılayır.
      </div>
    </section>

    <section id="elaqe">
      <h2>Əlaqə</h2>
      <p>
        Sifariş üçün: <b>example@mail.com</b> (nümunə) <br>
        Telegram: <i>@example</i> (nümunə)
      </p>
    </section>
  </main>

  <footer>
    <div class="container">
      <small>© 2026 GameKey Market — Laboratoriya işi №1 (nümunə sayt)</small>
    </div>
  </footer>
</body>
</html>
