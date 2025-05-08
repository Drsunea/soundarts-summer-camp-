# soundarts-summer-camp-
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>サウンドアーツ夏合宿</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Rubik', sans-serif;
    }
    body {
      background: #ffffff;
      color: #111;
      overflow-x: hidden;
    }
    section {
      width: 100vw;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      flex-direction: column;
      text-align: center;
    }
    section:nth-child(even) {
      background-color: #f4f4f4;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 20px;
      color: #ff0055;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2rem;
      max-width: 600px;
    }
    .fadein {
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.8s ease;
    }
    .fadein.active {
      opacity: 1;
      transform: translateY(0);
    }
    .hero {
      background: url('https://source.unsplash.com/1600x900/?music,summer') center/cover no-repeat;
      color: white;
    }
    .hero h1 {
      color: white;
      text-shadow: 2px 2px 5px #000;
    }
  </style>
</head>
<body>
  <section class="hero fadein">
    <h1>サウンドアーツ夏合宿 2025</h1>
    <p>この夏、一緒に最高の音を響かせよう！</p>
  </section>

  <section class="fadein">
    <h2>📅 開催日</h2>
    <p>8月25日〜27日</p>
  </section>

  <section class="fadein">
    <h2>📍 開催場所</h2>
    <p>寺尾温泉</p>
  </section>

  <section class="fadein">
    <h2>🎵 スケジュール</h2>
    <p>
      1日目：移動＆バンド練習<br>
      2日目：合宿ライブ本番！<br>
      3日目：海へGO！そして帰宅🌊
    </p>
  </section>

  <section class="fadein">
    <h2>💰 参加費</h2>
    <p>3万円〜4万円（人数が増えると安くなります！助けて！）</p>
  </section>

  <section class="fadein">
    <h2>📨 申し込み方法</h2>
    <p>全体LINEに応募フォームを投稿予定！見逃さないで！</p>
  </section>

  <section class="fadein">
    <h2>🎤 主催</h2>
    <p>サウンドアーツ</p>
  </section>

  <script>
    // スクロールでフェードイン（重複防止のため関数名を変更）
    const fadeElements = document.querySelectorAll('.fadein');

    const triggerFadeInScroll = () => {
      const windowHeight = window.innerHeight;
      fadeElements.forEach(el => {
        const elementTop = el.getBoundingClientRect().top;
        if (elementTop < windowHeight - 100) {
          el.classList.add('active');
        }
      });
    }

    window.addEventListener('scroll', triggerFadeInScroll);
    window.
