<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>⚡ Technologies & Tools - Banner</title>
  <style>
    :root{
      --bg: #ffffff;
      --text: #111827;
      --muted: #6b7280;
      --card: #f8fafc;
      --border: #e5e7eb;
      --radius: 14px;
      /* برند رنگ‌ها */
      --html: #e34f26;
      --css: #1572B6;
      --js: #f7df1e;
      --ts: #3178c6;
      --react: #61dafb;
      --next: #000000;
      --tailwind: #38bdf8;

      --node: #3c873a;
      --laravel: #f9322c;
      --dotnet: #512bd4;

      --postgres: #336791;
      --mysql: #00758f;
      --mongo: #10aa50;

      --docker: #0db7ed;
      --git: #f14e32;
      --github: #181717;
      --vscode: #007acc;
    }

    * { box-sizing: border-box; }
    html, body { margin:0; padding:0; background: var(--bg); color: var(--text); font-family: "Inter", "Segoe UI", "Vazirmatn", sans-serif; }
    .container { max-width: 1100px; margin: 28px auto 60px; padding: 0 20px; }

    /* بنر بالایی (منظره گرم) */
    .hero {
      width: 100%;
      border-radius: var(--radius);
      overflow: hidden;
      border: 1px solid var(--border);
      background: #fff;
    }
    .hero svg { display:block; width: 100%; height: auto; }

    /* عنوان */
    .title {
      margin: 22px 0 14px;
      font-weight: 800;
      font-size: 28px;
      letter-spacing: -0.01em;
      display:flex;
      align-items:center;
      gap:10px;
    }
    .title .zap {
      display:inline-flex; align-items:center; justify-content:center;
      width: 32px; height: 32px; border-radius: 10px;
      background: #ffe15a; color:#3b3b3b; font-weight: 900;
    }
    .subtitle { color: var(--muted); margin-top: 4px; font-size: 14px; }

    /* کارت دسته‌بندی */
    .section {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 16px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 16px;
    }
    @media (max-width: 720px) {
      .grid { grid-template-columns: 1fr; }
    }

    .section h3 {
      margin: 0 0 12px;
      font-size: 16px;
      font-weight: 700;
      color: #111827;
    }

    /* سطر بَدج‌ها */
    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    /* بَدج عمومی */
    .badge {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-width: 44px;
      height: 40px;
      padding: 0 10px;
      border-radius: 12px;
      color: #fff;
      font-weight: 800;
      font-size: 14px;
      letter-spacing: 0.2px;
      box-shadow: 0 1px 0 rgba(0,0,0,0.06), inset 0 1px 0 rgba(255,255,255,0.1);
      border: 1px solid rgba(0,0,0,0.06);
      user-select: none;
    }
    .badge.light {
      color: #111827;
      border-color: rgba(0,0,0,0.08);
    }
    .badge .label {
      display:inline-block;
      line-height: 1;
    }

    /* رنگ‌های اختصاصی */
    .html   { background: var(--html); }
    .css    { background: var(--css); }
    .js     { background: var(--js); color:#111827; }
    .ts     { background: var(--ts); }
    .react  { background: var(--react); color:#0b2230; }
    .next   { background: var(--next); }
    .tailwind { background: var(--tailwind); color:#0b2230; }

    .node   { background: var(--node); }
    .laravel{ background: var(--laravel); }
    .dotnet { background: var(--dotnet); }

    .postgres{ background: var(--postgres); }
    .mysql  { background: var(--mysql); }
    .mongo  { background: var(--mongo); }

    .docker { background: var(--docker); }
    .git    { background: var(--git); }
    .github { background: var(--github); }
    .vscode { background: var(--vscode); }

    /* توضیح کوچک زیر عنوان بخش */
    .hint {
      color: var(--muted);
      font-size: 12px;
      margin-top: -6px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- بنر منظره گرم -->
    <div class="hero" aria-label="بنر منظره مینیمال با رنگ‌های گرم">
      <svg viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Landscape banner">
        <defs>
          <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#ffb16e"/>
            <stop offset="100%" stop-color="#ffd4a3"/>
          </linearGradient>
          <linearGradient id="hills" x1="0" y1="0" x2="1" y2="0">
            <stop offset="0%" stop-color="#e1572c"/>
            <stop offset="100%" stop-color="#f37b3f"/>
          </linearGradient>
          <linearGradient id="hills2" x1="0" y1="0" x2="1" y2="0">
            <stop offset="0%" stop-color="#d84c24"/>
            <stop offset="100%" stop-color="#e96a34"/>
          </linearGradient>
        </defs>

        <!-- آسمان -->
        <rect x="0" y="0" width="1200" height="320" fill="url(#sky)" />

        <!-- تپه‌ها -->
        <path d="M0,220 C300,180 500,260 800,210 C980,185 1100,200 1200,190 L1200,320 L0,320 Z" fill="url(#hills)" />
        <path d="M0,240 C280,210 520,270 760,240 C940,220 1080,235 1200,225 L1200,320 L0,320 Z" fill="url(#hills2)" opacity="0.9" />

        <!-- خانه -->
        <g transform="translate(760,150)">
          <rect x="0" y="40" width="60" height="40" fill="#7a3b2e" />
          <polygon points="0,40 30,10 60,40" fill="#5a2a20" />
          <rect x="40" y="55" width="12" height="12" fill="#ffd27a" />
        </g>

        <!-- درخت -->
        <g transform="translate(850,160)">
          <rect x="18" y="50" width="6" height="26" fill="#5a2a20" />
          <circle cx="21" cy="50" r="22" fill="#7a9e57" />
        </g>
      </svg>
    </div>

    <!-- عنوان -->
    <div class="title" aria-label="عنوان بخش تکنولوژی‌ها و ابزارها">
      <span class="zap">⚡</span>
      <span>Technologies & Tools</span>
    </div>
    <div class="subtitle">دسته‌بندی مهارت‌های تو با باکس‌های رنگی و حرف اول هر تکنولوژی</div>

    <!-- شبکه بخش‌ها -->
    <div class="grid" style="margin-top:18px;">
      <!-- Front-End -->
      <div class="section">
        <h3>Front-End</h3>
        <div class="hint">حرف اول هر تکنولوژی داخل باکس رنگی</div>
        <div class="badges" aria-label="Front-End badges">
          <span class="badge html"><span class="label">H</span></span>
          <span class="badge css"><span class="label">C</span></span>
          <span class="badge js light"><span class="label">JS</span></span>
          <span class="badge ts"><span class="label">TS</span></span>
          <span class="badge react light"><span class="label">R</span></span>
          <span class="badge next"><span class="label">Nx</span></span>
          <span class="badge tailwind light"><span class="label">T</span></span>
        </div>
      </div>

      <!-- Back-End & Others -->
      <div class="section">
        <h3>Back-End & Others</h3>
        <div class="badges" aria-label="Back-End badges">
          <span class="badge node"><span class="label">N</span></span>
          <span class="badge laravel"><span class="label">L</span></span>
          <span class="badge dotnet"><span class="label">NET</span></span>
        </div>
      </div>

      <!-- Databases -->
      <div class="section">
        <h3>Databases</h3>
        <div class="badges" aria-label="Database badges">
          <span class="badge postgres"><span class="label">P</span></span>
          <span class="badge mysql"><span class="label">M</span></span>
          <span class="badge mongo"><span class="label">MG</span></span>
        </div>
      </div>

      <!-- DevOps & Tools -->
      <div class="section">
        <h3>DevOps & Tools</h3>
        <div class="badges" aria-label="DevOps badges">
          <span class="badge docker"><span class="label">D</span></span>
          <span class="badge git"><span class="label">G</span></span>
          <span class="badge github"><span class="label">GH</span></span>
          <span class="badge vscode"><span class="label">V</span></span>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
