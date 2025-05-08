# soundatrs-2025
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SOUND ARTS 夏合宿 2025</title>
  <link href="https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Rock Salt', cursive;
      background: linear-gradient(135deg, #ff0080, #00ffff);
      color: #fff;
      overflow-x: hidden;
    }
    header {
      background: #000;
      padding: 50px 20px;
      text-align: center;
      color: #ffcc00;
      font-size: 3em;
      animation: neonFlash 1.5s infinite alternate;
    }
    @keyframes neonFlash {
      from { text-shadow: 0 0 10px #ffcc00, 0 0 20px #ffcc00; }
      to { text-shadow: 0 0 20px #ff00ff, 0 0 40px #00ffff; }
    }
    .info-section, .fun-section, .gallery-section {
      padding: 60px 20px;
      text-align: center;
    }
    .info-section h2, .fun-section h2, .gallery-section h2 {
      color: #000;
      background: #fff700;
      padding: 10px;
      display: inline-block;
      border-radius: 10px;
      box-shadow: 0 0 20px #fff;
    }
    .info-box {
      margin-top: 30px;
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    .info-box div {
      background: #000;
      padding: 20px;
      font-size: 1.2em;
      border: 2px dashed #fff700;
      transform: rotate(-1deg);
    }
    .fun-img {
      width: 250px;
      animation: crazySpin 3s infinite linear;
      margin: 30px 0;
    }
    @keyframes crazySpin {
      0% { transform: rotate(0deg) scale(1); }
      50% { transform: rotate(180deg) scale(1.2); }
      100% { transform: rotate(360deg) scale(1); }
    }
    .cta {
      background: #ffcc00;
      padding: 25px;
      text-align: center;
      font-size: 1.5em;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.3s, background 0.3s;
      margin-top: 40px;
    }
    .cta:hover {
      transform: scale(1.2) rotate(-2deg);
      background: #fff700;
    }
    .qr-section {
      background: #111;
      padding: 50px 20px;
      text-align: center;
    }
    .qr-section h2 {
      color: #00ff99;
      margin-bottom: 20px;
    }
    .qr-img {
      width: 200px;
      background: #fff;
      padding: 10px;
      border-radius: 10px;
    }
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .gallery-grid img {
      width: 100%;
      border-radius: 15px;
      border: 3px solid #fff;
      transition: transform 0.3s;
    }
    .gallery-grid img:hover {
      transform: scale(1.1);
    }
    /* Aboutセクション */
    #about {
      padding: 40px;
      background-color: #222;
      color: #fff;
      border-radius: 10px;
      box-shadow: 0 0 15px #fff;
      margin-top: 40px;
    }
    #about h2 {
      text-align: center;
      color: #ffcc00;
      font-size: 2em;
    }
    #about ul {
      padding-left: 20px;
      list-style-type: square;
    }
    #about li {
      font-size: 1.3em;
      margin: 10px 0;
    }
    /* Aboutリンク */
    .about-link {
      display: block;
      text-align: center;
      margin: 40px auto;
      font-size: 1.5em;
      color: #ffcc00;
      cursor: pointer;
      text-decoration: underline;
    }
    .about-link:hover {
      color: #fff700;
    }
  </style>
</head>
<body>
  <header>SOUND ARTS 夏合宿 2025🔥</header>

  <section class="info-section">
    <h2>📅 合宿詳細</h2>
    <div class="info-box">
      <div>日程：2025年8月25日〜27日</div>
      <div>場所：寺尾温泉</div>
      <div>対象：部員全員</div>
      <div>料金：3万〜（人が増えるほど安くなります！！）</div>
    </div>
  </section>

  <section class="fun-section">
    <h2>🎉 内容盛りだくさん！</h2>
    <p>バンド練習、ライブ、海水浴、そして…</p>
    <img src="https://media.giphy.com/media/IThjAlJnD9WNO/giphy.gif" alt="fun gif" class="fun-img">
    <p style="font-size: 1.5em; color: #ff0077;">＼謎イベント勃発の予感！／</p>
    <p style="font-size: 1.2em; color: #00ffcc;">何が起こるかは当日までヒミツ！</p>
  </section>

  <section class="gallery-section">
    <h2>📸 写真で見る合宿の様子</h2>
    <div class="gallery-grid">
      <img src="https://www.info-toyama.com/storage/tourism_attractions/99815/responsive_images/e0UTRRocVxL9AJfbhqjlq4XLuIErvNDRX2pc79yG__666_387.png" alt="温泉施設">
      <img src="https://terao.more-resort.com/_assets/facility/alt7f_1.jpg" alt="バンド練習風景">
      <img src="https://www.info-toyama.com/storage/tourism_attractions/11038/responsive_images/XroSwWV8Pweq4FtEcOL8PG5rCouM1Sdphjy4MiYG__777_583.jpeg" alt="海水浴">
      <img src="https://terao.more-resort.com/_assets/facility/music_main.jpg" alt="ライブの様子">
    </div>
  </section>

  <div class="cta" onclick="alert('参加申し込みは部内LINEで受付中！')">
    参加するしかないっしょ！🔥
  </div>

  <!-- Aboutリンク -->
  <div class="about-link" onclick="document.getElementById('about').scrollIntoView({ behavior: 'smooth' })">
    About 合宿詳細
  </div>

  <!-- Aboutセクション -->
  <section id="about">
    <h2>持ち物リスト・イベントの流れ</h2>
    <h3>持ち物リスト</h3>
    <ul>
      <li>着替え（3日分）</li>
      <li>水着・バスタオル（海水浴用）</li>
      <li>楽器・シールド・チューナーなど必要な機材</li>
      <li>常備薬・保険証（コピーでも可）</li>
      <li>お風呂セット（シャンプー・ボディソープ等）</li>
      <li>合宿代（詳細が決まり次第発表）</li>
    </ul>
    <h3>イベントの流れ（しおり）</h3>
    <ul>
      <li><strong>8月25日</strong>：移動 → チェックイン → 練習 → ご飯 → 夜練習</li>
      <li><strong>8月26日</strong>：朝ごはん → 昼ごはん → ライブ本番 → 入浴 → ご飯 → 自由時間</li>
      <li><strong>8月27日</strong>：朝ごはん → 集合写真 → 海水浴 → 帰宅</li>
    </ul>
  </section>

  <!-- QRコードセクション -->
  <section class="qr-section">
    <h2>📱 QRコードでこのページをシェア！</h2>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&
