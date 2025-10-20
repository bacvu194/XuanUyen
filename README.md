<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chúc mừng 20/10 - Xuân Uyên 🌸</title>
  <style>
    :root{
      --bg:#fff6f9;
      --card:#ffffff;
      --accent:#ff6fa3;
      --accent-2:#ffd1e6;
      --text:#333;
      --muted:#7a7a7a;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: radial-gradient(circle at 10% 10%, #fff0f4 0%, var(--bg) 25%) , linear-gradient(180deg,#fff 0%, #fff5f7 100%);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:2rem;
      display:flex;
      align-items:center;
      justify-content:center;
      min-height:100vh;
    }

    .card{
      width:100%;
      max-width:900px;
      background:var(--card);
      border-radius:18px;
      box-shadow:0 12px 30px rgba(0,0,0,0.08);
      overflow:hidden;
      display:grid;
      grid-template-columns: 1fr 380px;
      gap:0;
      align-items:stretch;
      position:relative;
    }

    /* Left content */
    .left{
      padding:34px;
    }
    .badge{
      display:inline-block;
      background:linear-gradient(90deg,var(--accent),#ff9fc1);
      color:white;
      padding:8px 14px;
      border-radius:999px;
      font-weight:700;
      letter-spacing:0.4px;
      box-shadow:0 6px 18px rgba(255,111,140,0.18);
    }
    h1{
      margin:18px 0 6px;
      font-size:36px;
      line-height:1.05;
      color:#2b2b2b;
    }
    .sub{
      color:var(--muted);
      margin-bottom:18px;
    }
    .message{
      background:linear-gradient(180deg, rgba(255,241,247,0.9), rgba(255,250,250,0.6));
      border-radius:12px;
      padding:18px;
      border:1px solid rgba(255,200,220,0.6);
      margin-bottom:20px;
      font-size:16px;
      color:#3b3b3b;
    }

    .flowers{
      display:flex;
      gap:10px;
      margin:14px 0 22px;
    }
    .flower{
      width:62px;
      height:62px;
      border-radius:50%;
      background:var(--accent-2);
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:26px;
      box-shadow:0 8px 18px rgba(255,120,160,0.12);
      transform-origin:center;
      animation:float 4s ease-in-out infinite;
    }
    .flower:nth-child(2){ animation-delay: .4s }
    .flower:nth-child(3){ animation-delay: .8s }
    @keyframes float{
      0%{ transform:translateY(0) }
      50%{ transform:translateY(-8px) }
      100%{ transform:translateY(0) }
    }

    .btns{
      display:flex;
      gap:12px;
      margin-top:6px;
    }
    .btn{
      padding:10px 16px;
      border-radius:10px;
      border:0;
      cursor:pointer;
      font-weight:700;
      box-shadow:0 8px 18px rgba(0,0,0,0.06);
    }
    .btn-primary{
      background:linear-gradient(90deg,var(--accent),#ff8ab2);
      color:white;
    }
    .btn-ghost{
      background:transparent;
      border:1px solid rgba(200,140,160,0.18);
      color:var(--accent);
    }

    /* Right panel */
    .right{
      background: linear-gradient(180deg, #fff0f6 0%, #fff6fb 100%);
      padding:26px;
      display:flex;
      flex-direction:column;
      gap:14px;
      align-items:center;
      justify-content:center;
      border-left:1px dashed rgba(255,120,160,0.12);
    }
    .portrait{
      width:220px;
      height:220px;
      border-radius:16px;
      background:linear-gradient(135deg,#fff,#ffeef8);
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:64px;
      color:var(--accent);
      box-shadow:0 12px 30px rgba(255,120,160,0.12);
      position:relative;
      overflow:hidden;
    }
    .portrait .initials{
      font-size:56px;
      font-weight:800;
      letter-spacing:1px;
    }
    .meta{
      text-align:center;
      color:var(--muted);
    }
    .meta h3{ margin:8px 0 4px; font-size:20px; color:#3b3b3b }
    .meta p{ margin:0; font-size:14px }

    /* confetti */
    .confetti-piece{
      position:absolute;
      width:10px;height:18px;
      background:var(--accent);
      top:-10%;
      left:50%;
      transform:translateX(-50%) rotate(0deg);
      opacity:0.95;
      animation:fall 3.6s linear infinite;
    }
    .confetti-piece:nth-child(1){ left:20%; animation-delay:0s }
    .confetti-piece:nth-child(2){ left:40%; animation-delay:.2s; background:#ffd1e6 }
    .confetti-piece:nth-child(3){ left:60%; animation-delay:.4s; background:#ff9fc1 }
    .confetti-piece:nth-child(4){ left:80%; animation-delay:.6s; background:#ffe0f0 }
    @keyframes fall{
      0%{ top:-10%; transform:translateY(0) rotate(0deg); opacity:1 }
      100%{ top:110%; transform:translateY(100vh) rotate(540deg); opacity:0.9 }
    }

    footer{
      position:absolute;
      left:20px;
      bottom:14px;
      font-size:13px;
      color:var(--muted);
    }

    /* responsive */
    @media (max-width:880px){
      .card{ grid-template-columns: 1fr; padding:0 }
      .right{ order:-1; border-left:0; border-bottom:1px dashed rgba(255,120,160,0.08); padding:18px }
      h1{ font-size:28px }
    }
  </style>
</head>
<body>
  <div class="card" role="article" aria-label="Thiệp chúc mừng 20/10 cho Xuân Uyên">
    <div class="left">
      <span class="badge">20/10</span>
      <h1>Chúc mừng Ngày Phụ nữ Việt Nam, Xuân Uyên! 🌸</h1>
      <div class="sub">Một ngày thật ấm áp, đầy yêu thương và những nụ cười dành cho bạn.</div>

      <div class="message">
        Gửi Uyên thân mến,<br>
        Cảm ơn Uyên vì nụ cười, sự dịu dàng và trái tim ấm áp mà bạn mang đến cho mọi người xung quanh. 
        Chúc bạn luôn mạnh khỏe, hạnh phúc và đạt được mọi ước mơ. Hôm nay hãy để mọi lo toan nhường chỗ cho niềm vui nhé!
      </div>

      <div class="flowers" aria-hidden="true">
        <div class="flower">🌷</div>
        <div class="flower">🌺</div>
        <div class="flower">🌸</div>
      </div>

      <div style="display:flex;gap:18px;align-items:center;flex-wrap:wrap;">
        <div>
          <button class="btn btn-primary" onclick="playSurprise()">Mở lời chúc 🎁</button>
        </div>
        <div>
          <button class="btn btn-ghost" onclick="downloadCard()">Tải thiệp</button>
        </div>
      </div>

      <div style="margin-top:18px;color:var(--muted);font-size:14px;">
        Một vài câu nói cho ngày 20/10:
        <ul>
          <li>“Chúc em luôn xinh, luôn vui, luôn rạng rỡ.”</li>
          <li>“Mọi điều tốt đẹp sẽ đến với trái tim dịu dàng như em.”</li>
        </ul>
      </div>

      <footer>Thiệp số — Gửi bởi một người bạn thân thương</footer>
    </div>

    <div class="right">
      <div class="portrait" id="portrait" aria-hidden="true">
        <div class="initials">XU</div>
      </div>
      <div class="meta">
        <h3>Xuân Uyên</h3>
        <p>Người con gái dịu dàng — luôn tỏa sáng ✨</p>
      </div>

      <!-- decorative confetti pieces -->
      <div class="confetti-piece" style="height:14px"></div>
      <div class="confetti-piece" style="height:20px"></div>
      <div class="confetti-piece" style="height:16px"></div>
      <div class="confetti-piece" style="height:12px"></div>
    </div>
  </div>

  <audio id="surprise-audio" src="" preload="auto"></audio>

  <script>
    // Tương tác nhỏ: hiển thị popup chúc mừng và hiệu ứng âm thanh (âm thanh rỗng — nếu bạn muốn, thay bằng URL file mp3)
    function playSurprise(){
      // Hiển thị modal đơn giản
      const name = "Xuân Uyên";
      const msg = `Chúc mừng 20/10, ${name}! Chúc bạn luôn hạnh phúc và thành công 💐`;
      alert(msg);
      // Nếu muốn thêm nhạc, đặt src cho #surprise-audio
      // document.getElementById('surprise-audio').src = 'path/to/your/sound.mp3';
      // document.getElementById('surprise-audio').play().catch(()=>{});
    }

    // Tải thiệp: tạo bản chụp đơn giản bằng in trang (user có thể lưu dưới dạng PDF)
    function downloadCard(){
      const proceed = confirm("Bạn có muốn in / lưu thiệp này (in thành PDF) không?");
      if(proceed){
        window.print();
      }
    }

    // Tùy chỉnh: nếu muốn thay tên hiển thị, có thể sửa biến dưới đây
    (function personalize(){
      // Nếu tên có dấu, lấy chữ hoa đầu làm initials (ví dụ: "Xuân Uyên" -> "XU")
      const fullName = "Xuân Uyên";
      const parts = fullName.trim().split(/\s+/);
      let initials = parts.map(p => p.charAt(0)).slice(0,2).join('').toUpperCase();
      document.querySelector('.initials').textContent = initials;
      document.querySelector('.meta h3').textContent = fullName;
      document.querySelector('h1').innerHTML = `Chúc mừng Ngày Phụ nữ Việt Nam, <strong>${fullName}</strong>! 🌸`;
    })();
  </script>
</body>
</html>

