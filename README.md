<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>安心サポートサービス</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #00897b;
      --accent-color: #4db6ac;
      --background-light: #f0f4f8;
      --text-dark: #2c3e50;
      --text-light: #ffffff;
      --font-family: 'Outfit', sans-serif;
    }

    body {
      font-family: var(--font-family);
      margin: 0;
      padding: 0;
      background: var(--background-light);
      color: var(--text-dark);
      line-height: 1.7;
    }

    header {
      background: var(--primary-color);
      color: var(--text-light);
      padding: 60px 20px 40px;
      text-align: center;
      position: relative;
    }

    header::after {
      content: '';
      position: absolute;
      bottom: -20px;
      left: 50%;
      transform: translateX(-50%);
      width: 80px;
      height: 4px;
      background: var(--accent-color);
      border-radius: 2px;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 24px;
      margin: 30px 0 0;
      padding: 0;
    }

    nav a {
      color: var(--text-light);
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--accent-color);
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    section {
      margin-bottom: 70px;
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 20px;
      border-left: 6px solid var(--primary-color);
      padding-left: 15px;
    }

    h3 {
      color: var(--primary-color);
      margin-top: 0;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.07);
      margin-bottom: 30px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    img, video {
      width: 100%;
      border-radius: 10px;
      margin-top: 15px;
    }

    form {
      display: grid;
      gap: 20px;
    }

    input, textarea, button {
      font-size: 1rem;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-family: var(--font-family);
    }

    button {
      background-color: var(--primary-color);
      color: white;
      border: none;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background-color: #00796b;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 10px;
    }

    footer {
      background: var(--primary-color);
      color: white;
      text-align: center;
      padding: 40px 20px;
      margin-top: 40px;
    }

    .testimonial p {
      font-style: italic;
    }
  </style>
</head>
<body>
  <header>
    <h1>安心サポートサービス</h1>
    <p>〜あなたとご家族の健康と安心を支える〜</p>
    <nav>
      <ul>
        <li><a href="#services">サービス内容</a></li>
        <li><a href="#pricing">料金表</a></li>
        <li><a href="#testimonials">お客様の声</a></li>
        <li><a href="#contact">お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <div class="container">
    <section id="services">
      <h2>サービス内容</h2>
      <div class="card">
        <h3>インフォームドコンセント付き添い</h3>
        <p>医師からの説明を一緒に聞き、内容の理解をサポート。必要に応じてご家族への説明も代行いたします。</p>
        <img src="https://source.unsplash.com/featured/?doctor,consultation" alt="医師との相談">
      </div>
      <div class="card">
        <h3>通院付添・送迎</h3>
        <p>病院への通院に付き添い、移動の負担を軽減。安心して医療を受けていただけるようサポートします。</p>
        <img src="https://source.unsplash.com/featured/?transport,elderly" alt="送迎サポート">
      </div>
      <div class="card">
        <h3>家族代行</h3>
        <p>ご家族に代わり、生活の見守りや買い物などをサポート。遠方にお住まいのご家族にも安心をお届けします。</p>
        <img src="https://source.unsplash.com/featured/?elderly,care" alt="高齢者支援">
      </div>
      <div class="card">
        <h3>頭痛改善マッサージ</h3>
        <p>慢性的な頭痛を緩和するためのリラクゼーションマッサージ。丁寧な施術で心と身体を整えます。</p>
        <video src="https://cdn.pixabay.com/video/2024/02/12/200219-910891847_large.mp4" controls poster="https://cdn.pixabay.com/photo/2022/10/10/11/41/headache-7510659_1280.jpg"></video>
      </div>
      <div class="card">
        <h3>健康相談</h3>
        <p>日常の健康不安や生活習慣に関する相談を受付中。専門スタッフが親身にアドバイスいたします。</p>
        <img src="https://source.unsplash.com/featured/?healthcare,consultation" alt="健康相談">
      </div>
    </section>

    <section id="pricing">
      <h2>料金表</h2>
      <div class="card">
        <ul>
          <li>インフォームドコンセント付き添い：5,000円／回</li>
          <li>通院付添・送迎：3,000円〜／回（距離により変動）</li>
          <li>家族代行：2,500円〜／回</li>
          <li>頭痛改善マッサージ：4,000円／30分</li>
          <li>健康相談：無料（初回30分）</li>
        </ul>
      </div>
    </section>

    <section id="testimonials">
      <h2>お客様の声</h2>
      <div class="card testimonial">
        <p>「母の通院に付き添ってもらい、とても安心できました。対応も丁寧で助かりました。」<br>— 50代女性</p>
      </div>
      <div class="card testimonial">
        <p>「頭痛が軽減され、仕事にも集中できるようになりました。ありがとうございます。」<br>— 30代男性</p>
      </div>
    </section>

    <section id="contact">
      <h2>お問い合わせ・ご予約</h2>
      <div class="card">
        <p>サービスに関するご質問やご予約は、以下よりお気軽にご連絡ください。</p>
        <form>
          <input type="text" name="name" placeholder="お名前" required>
          <input type="email" name="email" placeholder="メールアドレス" required>
          <textarea name="message" placeholder="お問い合わせ内容" rows="5" required></textarea>
          <button type="submit">送信</button>
        </form>
        <p style="margin-top: 20px;">電話：012-345-6789<br>Email：info@example.com</p>
      </div>
    </section>

    <section>
      <h2>アクセス</h2>
      <div class="card">
        <p>当事業所へのアクセスマップはこちら：</p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3242.858650223612!2d139.74477!3d35.658034!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b6d4f8d88c5%3A0x2d92e8e7e3511122!2z44CSMTAwLTAwMTIg5p2x5Lqs6YO95riv5Yy65pel5pys55S677yT5LiB55uu77yR4oiS77yR77yX!5e0!3m2!1sja!2sjp!4v1615331778936!5m2!1sja!2sjp" allowfullscreen="" loading="lazy"></iframe>
      </div>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 安心サポートサービス. All rights reserved.</p>
  </footer>
</body>
</html>
