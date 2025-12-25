<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <title>RockFord RP — Minecraft RP сервер</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="RockFord RP — Minecraft Roleplay сервер. Java 1.21.10, Bedrock 1.21.100. IP: rockford.gomc.fun. Сервер: ON.">
  <style>
    body {
      margin:0; font:16px/1.6 system-ui, sans-serif;
      background:#0d1117; color:#e6edf3;
    }
    header {
      background:linear-gradient(135deg,#0b6623,#1c9b3b,#7cfc00);
      padding:20px; text-align:center; color:#fff;
    }
    .logo {
      font-size:2rem; font-weight:800; text-shadow:0 2px 4px rgba(0,0,0,.5);
    }
    .tag { font-size:1rem; margin-top:6px; }
    main { max-width:1000px; margin:20px auto; padding:20px; }
    h2 { border-bottom:1px solid #2b3139; padding-bottom:.3rem; }
    .card {
      background:#0f141a; border:1px solid #2b3139;
      border-radius:12px; padding:16px; margin-bottom:20px;
      box-shadow:0 6px 18px rgba(0,0,0,.35);
    }
    .status {
      display:inline-flex; align-items:center; gap:8px;
      padding:.35rem .6rem; border-radius:10px;
      background:rgba(0,200,83,.18); border:1px solid rgba(0,200,83,.35);
      font-weight:600; color:#b7ffd8;
    }
    .dot { width:10px; height:10px; border-radius:50%; background:#00c853; box-shadow:0 0 10px #00c853; }
    .kbd {
      font-family:monospace; padding:.08rem .35rem;
      border:1px solid #2b3139; border-radius:6px;
      background:rgba(255,255,255,.06);
    }
    .ip-box { display:flex; gap:8px; align-items:center; flex-wrap:wrap; }
    .copy {
      padding:.45rem .75rem; border-radius:8px;
      border:1px solid #2b3139; background:rgba(255,255,255,.08);
      cursor:pointer;
    }
    .copy:hover { background:rgba(255,255,255,.12); }
    footer {
      text-align:center; padding:14px; color:#9aa7b2;
      border-top:1px solid #2b3139; margin-top:20px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">RockFord RP</div>
    <div class="tag">Minecraft Roleplay сервер</div>
  </header>

  <main>
    <section class="card">
      <h2>Информация о сервере</h2>
      <p><strong>Java Edition:</strong> 1.21.10</p>
      <p><strong>Bedrock:</strong> 1.21.100</p>
      <div class="status"><span class="dot"></span> Сервер: ON</div>
    </section>

    <section class="card">
      <h2>IP сервера</h2>
      <div class="ip-box">
        <span><strong>rockford.gomc.fun</strong></span>
        <button class="copy" id="copyBtn">Скопировать</button>
      </div>
    </section>

    <section class="card">
      <h2 id="java">Подключение — Java Edition</h2>
      <ol>
        <li><span class="kbd">Запустите Minecraft Java 1.21.10</span></li>
        <li><span class="kbd">Многопользовательская игра → Добавить сервер</span></li>
        <li><strong>Название:</strong> RockFord RP</li>
        <li><strong>Адрес:</strong> <span class="kbd">rockford.gomc.fun</span></li>
        <li>Сохраните и подключайтесь.</li>
      </ol>
    </section>

    <section class="card">
      <h2 id="bedrock">Подключение — Bedrock Edition</h2>
      <ol>
        <li><span class="kbd">Откройте Minecraft Bedrock 1.21.100</span></li>
        <li><span class="kbd">Играть → Серверы → Добавить</span></li>
        <li><strong>Название:</strong> RockFord RP</li>
        <li><strong>Адрес:</strong> <span class="kbd">rockford.gomc.fun</span></li>
        <li>Подтвердите и подключайтесь.</li>
      </ol>
    </section>

    <section class="card">
      <h2>О сервере</h2>
      <ul>
        <li>Ролевые профессии: полиция, медики, бизнес, СМИ и др.</li>
        <li>Экономика: торговля, зарплаты, недвижимость.</li>
        <li>События: сезонные ивенты, RP‑сценарии.</li>
      </ul>
    </section>
  </main>

  <footer>
    © RockFord RP — Minecraft Roleplay сервер • IP: rockford.gomc.fun • Java 1.21.10 • Bedrock 1.21.100
  </footer>

  <script>
    // Копирование IP
    document.getElementById('copyBtn').addEventListener('click', async () => {
      const ip = 'rockford.gomc.fun';
      try {
        await navigator.clipboard.writeText(ip);
        const btn = document.getElementById('copyBtn');
        btn.textContent = 'Скопировано!';
        setTimeout(()=>{btn.textContent='Скопировать';},1200);
      } catch(e) {
        alert('Скопируйте вручную: ' + ip);
      }
    });
  </script>
</body>
</html>
