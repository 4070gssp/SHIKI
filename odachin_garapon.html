<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>お駄賃決定！抽選ガラポン</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Kosugi+Maru&family=Dela+Gothic+One&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0;}
html,body{
  min-height:100%;
  background:linear-gradient(135deg,#ffe4f0 0%,#fff5cc 50%,#e4f5ff 100%);
  font-family:'Kosugi Maru',sans-serif;
}
body{
  display:flex;
  justify-content:center;
  padding:20px 12px 40px;
}
.wrap{width:100%;max-width:400px;}

/* BANNER */
.banner-wrap{border-radius:18px;overflow:hidden;margin-bottom:14px;box-shadow:0 6px 24px rgba(255,100,150,.25);}

/* GAME CARD */
.game-card{
  background:#fffbe8;border-radius:18px;padding:16px 14px 22px;
  border:2.5px solid #f0c840;overflow:hidden;position:relative;
  box-shadow:0 4px 20px rgba(200,140,0,.15);
}
.stage{display:flex;align-items:center;justify-content:center;position:relative;width:100%;}

/* confetti */
.confetti-box{position:absolute;top:0;left:0;right:0;bottom:0;pointer-events:none;overflow:hidden;z-index:30;}
.confetti-p{position:absolute;width:8px;height:8px;border-radius:2px;animation:cfall 1.3s ease-in both;}
@keyframes cfall{0%{transform:translateY(-8px) rotate(0);opacity:1;}100%{transform:translateY(320px) rotate(560deg);opacity:0;}}

/* flying ball overlay */
.ball-overlay{position:absolute;top:0;left:0;width:100%;height:100%;pointer-events:none;z-index:20;overflow:hidden;}

/* result */
.result-area{min-height:46px;display:flex;align-items:center;justify-content:center;margin:6px 0 10px;}
.rbadge{font-family:'Dela Gothic One',sans-serif;font-size:22px;padding:8px 28px;border-radius:50px;animation:popIn .45s cubic-bezier(.2,1.5,.5,1) both;}
@keyframes popIn{from{transform:scale(.3);opacity:0;}to{transform:scale(1);opacity:1;}}
.b1{background:#ffe84d;color:#9a5800;border:2.5px solid #dfa000;}
.b2{background:#e0e0e0;color:#444;border:2.5px solid #aaa;}
.b3{background:#ffd4a0;color:#9a4a00;border:2.5px solid #cc7a20;}
.b0{background:#ddeeff;color:#2a5588;border:2.5px solid #88aacc;}

/* spin button */
.btn-spin{
  font-family:'Dela Gothic One',sans-serif;font-size:18px;
  background:linear-gradient(135deg,#FF6B9D,#FF9F45);
  color:#fff;border:none;border-radius:50px;
  padding:15px 0;width:100%;cursor:pointer;
  box-shadow:0 5px 0 #cc3366,0 8px 18px rgba(255,100,150,.3);
  transition:all .12s;letter-spacing:1px;
}
.btn-spin:hover{filter:brightness(1.06);}
.btn-spin:active{transform:translateY(4px);box-shadow:0 1px 0 #cc3366;}
.btn-spin:disabled{opacity:.4;cursor:not-allowed;filter:none;transform:none;}

/* coupons */
.sec-lbl{font-size:12px;color:#b07a10;text-align:center;margin:14px 0 8px;letter-spacing:.5px;}
.coupon{
  background:#fff;border:2px dashed #f0a800;border-radius:14px;
  padding:12px 14px;display:flex;align-items:center;gap:12px;
  position:relative;animation:slideUp .35s cubic-bezier(.2,1.2,.5,1) both;
  margin-bottom:10px;box-shadow:0 2px 8px rgba(200,140,0,.08);
}
.coupon.used{opacity:.38;filter:grayscale(.85);}
@keyframes slideUp{from{transform:translateY(16px);opacity:0;}to{transform:translateY(0);opacity:1;}}
.c-icon{font-size:32px;flex-shrink:0;}
.c-info{flex:1;min-width:0;}
.c-title{font-family:'Dela Gothic One',sans-serif;font-size:16px;color:#b86800;}
.c-meta{font-size:11px;color:#bbb;margin-top:3px;}
.c-id{font-size:9px;color:#ccc;font-family:monospace;margin-top:2px;letter-spacing:.5px;}
.used-lbl{
  position:absolute;right:12px;top:50%;transform:translateY(-50%) rotate(-6deg);
  font-family:'Dela Gothic One',sans-serif;font-size:13px;
  color:#cc3333;border:2px solid #cc3333;border-radius:6px;
  padding:3px 8px;background:rgba(255,255,255,.95);
}
.btn-use{
  font-family:'Kosugi Maru',sans-serif;font-size:11px;
  background:#fff;color:#b86800;border:2px solid #f0c040;
  border-radius:20px;padding:6px 12px;cursor:pointer;
  white-space:nowrap;flex-shrink:0;transition:background .15s;
}
.btn-use:hover{background:#fff8e0;}
</style>
</head>
<body>
<div class="wrap">

<!-- ===== BANNER ===== -->
<div class="banner-wrap">
<svg width="100%" viewBox="0 0 380 200" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>お駄賃決定抽選バナー</title>
  <desc>子ども向けのお駄賃抽選ゲームのバナー</desc>
  <defs>
    <linearGradient id="bgGrad" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#FF6B9D"/>
      <stop offset="50%" stop-color="#FF9F45"/>
      <stop offset="100%" stop-color="#FFD93D"/>
    </linearGradient>
    <linearGradient id="coinGrad" x1="0.2" y1="0.1" x2="0.8" y2="0.9">
      <stop offset="0%" stop-color="#FFE566"/>
      <stop offset="100%" stop-color="#F5A800"/>
    </linearGradient>
    <linearGradient id="titleBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="rgba(255,255,255,.95)"/>
      <stop offset="100%" stop-color="rgba(255,240,200,.92)"/>
    </linearGradient>
    <linearGradient id="subBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="rgba(255,80,0,.82)"/>
      <stop offset="100%" stop-color="rgba(200,40,0,.85)"/>
    </linearGradient>
  </defs>
  <rect width="380" height="200" fill="url(#bgGrad)"/>
  <path d="M0,30 Q47,10 95,28 Q142,46 190,28 Q238,10 285,28 Q332,46 380,28 L380,0 L0,0 Z" fill="rgba(255,255,255,.15)"/>
  <path d="M0,172 Q47,190 95,172 Q142,154 190,172 Q238,190 285,172 Q332,154 380,172 L380,200 L0,200 Z" fill="rgba(255,255,255,.15)"/>
  <circle cx="18"  cy="18"  r="5" fill="rgba(255,255,255,.22)"/>
  <circle cx="50"  cy="8"   r="3" fill="rgba(255,255,255,.18)"/>
  <circle cx="340" cy="15"  r="6" fill="rgba(255,255,255,.20)"/>
  <circle cx="365" cy="40"  r="4" fill="rgba(255,255,255,.16)"/>
  <circle cx="10"  cy="80"  r="4" fill="rgba(255,255,255,.18)"/>
  <circle cx="370" cy="160" r="5" fill="rgba(255,255,255,.20)"/>
  <circle cx="25"  cy="175" r="3" fill="rgba(255,255,255,.16)"/>
  <g transform="translate(32,38) rotate(-15)"><polygon points="0,-14 4,-5 13,-5 6,1 9,11 0,5 -9,11 -6,1 -13,-5 -4,-5" fill="#FFFFFF" opacity=".9"/></g>
  <g transform="translate(348,45) rotate(10)"><polygon points="0,-10 3,-3 10,-3 4,1 7,8 0,4 -7,8 -4,1 -10,-3 -3,-3" fill="#FFFFFF" opacity=".85"/></g>
  <g transform="translate(28,155) rotate(8)"><polygon points="0,-9 2.5,-3 9,-3 4,1 6,7 0,3.5 -6,7 -4,1 -9,-3 -2.5,-3" fill="#FFE566" opacity=".9"/></g>
  <g transform="translate(352,148) rotate(-12)"><polygon points="0,-11 3,-4 11,-4 5,1 7,9 0,5 -7,9 -5,1 -11,-4 -3,-4" fill="#FFE566" opacity=".88"/></g>
  <g transform="translate(68,160) rotate(5)"><polygon points="0,-7 2,-2 7,-2 3,1 5,6 0,3 -5,6 -3,1 -7,-2 -2,-2" fill="rgba(255,255,255,.7)"/></g>
  <g transform="translate(312,60) rotate(-8)"><polygon points="0,-7 2,-2 7,-2 3,1 5,6 0,3 -5,6 -3,1 -7,-2 -2,-2" fill="rgba(255,255,255,.7)"/></g>
  <circle cx="52"  cy="98" r="28" fill="url(#coinGrad)" stroke="#C88010" stroke-width="2"/>
  <circle cx="52"  cy="98" r="21" fill="none" stroke="rgba(255,255,210,.5)" stroke-width="1.5"/>
  <text x="52"  y="105" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="17" fill="#7a4a00">¥</text>
  <circle cx="328" cy="98" r="28" fill="url(#coinGrad)" stroke="#C88010" stroke-width="2"/>
  <circle cx="328" cy="98" r="21" fill="none" stroke="rgba(255,255,210,.5)" stroke-width="1.5"/>
  <text x="328" y="105" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="17" fill="#7a4a00">¥</text>
  <rect x="82" y="22" width="216" height="66" rx="16" fill="url(#titleBg)" stroke="rgba(255,160,0,.35)" stroke-width="1.5"/>
  <text x="190" y="53"  text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="28" fill="#CC4400">お駄賃</text>
  <text x="190" y="78"  text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="18" fill="#E06000">決定！抽選ガラポン</text>
  <rect x="88" y="98" width="204" height="30" rx="15" fill="url(#subBg)"/>
  <text x="190" y="118" text-anchor="middle" font-family="'Kosugi Maru',sans-serif" font-size="13" fill="#FFFFFF">おてつだい1回 → 1回まわせるよ！</text>
  <rect x="92"  y="140" width="50" height="46" rx="10" fill="#FFD700" stroke="#C88800" stroke-width="1.5"/>
  <text x="117" y="158" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="11" fill="#7a4a00">1等</text>
  <text x="117" y="176" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="14" fill="#7a3000">300円</text>
  <rect x="150" y="140" width="50" height="46" rx="10" fill="#E8E8E8" stroke="#AAAAAA" stroke-width="1.5"/>
  <text x="175" y="158" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="11" fill="#555">2等</text>
  <text x="175" y="176" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="14" fill="#333">100円</text>
  <rect x="208" y="140" width="50" height="46" rx="10" fill="#FFB347" stroke="#CC7700" stroke-width="1.5"/>
  <text x="233" y="158" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="11" fill="#7a3a00">3等</text>
  <text x="233" y="176" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="14" fill="#7a3000">50円</text>
  <rect x="266" y="146" width="50" height="40" rx="10" fill="#ADE8F4" stroke="#4499BB" stroke-width="1.5"/>
  <text x="291" y="162" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="10" fill="#1a5566">参加賞</text>
  <text x="291" y="178" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="13" fill="#1a4455">10円</text>
  <path d="M72,52 C72,49 75,47 77,50 C79,47 82,49 82,52 C82,56 77,60 77,60 C77,60 72,56 72,52Z" fill="#FF6B9D" opacity=".85"/>
  <path d="M296,52 C296,49 299,47 301,50 C303,47 306,49 306,52 C306,56 301,60 301,60 C301,60 296,56 296,52Z" fill="#FF6B9D" opacity=".85"/>
  <g stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" opacity=".85">
    <line x1="42" y1="132" x2="48" y2="138"/><line x1="48" y1="132" x2="42" y2="138"/>
  </g>
  <g stroke="#FFFFFF" stroke-width="2" stroke-linecap="round" opacity=".85">
    <line x1="332" y1="130" x2="338" y2="136"/><line x1="338" y1="130" x2="332" y2="136"/>
  </g>
</svg>
</div>

<!-- ===== GAME CARD ===== -->
<div class="game-card">
  <div class="stage" id="stageWrap">
    <div class="confetti-box" id="confBox"></div>
    <!-- 玉飛び出しオーバーレイ (Canvas) -->
    <canvas id="ballCanvas" style="position:absolute;top:0;left:0;width:100%;height:100%;pointer-events:none;z-index:25;"></canvas>

    <svg id="gpSvg" width="100%" viewBox="0 0 340 220" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="gOct" x1="0.2" y1="0" x2="0.8" y2="1">
          <stop offset="0%" stop-color="#FFE566"/>
          <stop offset="40%" stop-color="#F5AA00"/>
          <stop offset="100%" stop-color="#C07800"/>
        </linearGradient>
        <linearGradient id="gOctR" x1="0" y1="0" x2="1" y2="0">
          <stop offset="0%" stop-color="#C88010"/>
          <stop offset="100%" stop-color="#8A5400"/>
        </linearGradient>
        <linearGradient id="gBase2" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#F5C830"/>
          <stop offset="100%" stop-color="#C08010"/>
        </linearGradient>
        <linearGradient id="gLeg2" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#E8B820"/>
          <stop offset="100%" stop-color="#A07010"/>
        </linearGradient>
        <linearGradient id="gTray2" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#FFFFFF"/>
          <stop offset="100%" stop-color="#E8E0D0"/>
        </linearGradient>
        <radialGradient id="gBell2" cx="35%" cy="28%" r="65%">
          <stop offset="0%" stop-color="#FFE566"/>
          <stop offset="100%" stop-color="#C08800"/>
        </radialGradient>
        <radialGradient id="gKnob2" cx="35%" cy="32%" r="60%">
          <stop offset="0%" stop-color="#E8E8E8"/>
          <stop offset="100%" stop-color="#909090"/>
        </radialGradient>
        <clipPath id="octClip2">
          <polygon points="155,38 181,28 207,28 233,38 243,64 243,136 233,162 207,172 181,172 155,162 145,136 145,64"/>
        </clipPath>
      </defs>
      <!-- トレー -->
      <rect x="128" y="160" width="110" height="30" rx="4" fill="url(#gTray2)" stroke="#C8A820" stroke-width="1.5"/>
      <rect x="133" y="165" width="100" height="18" rx="3" fill="rgba(0,0,0,.05)"/>
      <!-- 台座 -->
      <rect x="112" y="188" width="140" height="18" rx="8" fill="url(#gBase2)" stroke="#A07010" stroke-width="1.5"/>
      <rect x="116" y="189" width="132" height="6" rx="4" fill="rgba(255,255,210,.3)"/>
      <!-- 脚 -->
      <rect x="126" y="204" width="14" height="22" rx="5" fill="url(#gLeg2)" stroke="#906010" stroke-width="1"/>
      <rect x="222" y="204" width="14" height="22" rx="5" fill="url(#gLeg2)" stroke="#906010" stroke-width="1"/>
      <!-- 支柱フレーム -->
      <rect x="226" y="130" width="12" height="62" rx="5" fill="#E8E8E8" stroke="#BBBBBB" stroke-width="1.2"/>
      <rect x="148" y="130" width="12" height="62" rx="5" fill="#E8E8E8" stroke="#BBBBBB" stroke-width="1.2"/>
      <rect x="148" y="128" width="90" height="14" rx="6" fill="#E0E0E0" stroke="#BBBBBB" stroke-width="1.2"/>
      <!-- ドラム右側面 -->
      <polygon points="243,64 257,72 257,144 243,136" fill="url(#gOctR)" stroke="#8A5400" stroke-width="1"/>
      <polygon points="233,38 247,46 257,72 243,64"   fill="#C88010" stroke="#8A5400" stroke-width="1"/>
      <polygon points="233,162 247,170 257,144 243,136" fill="#A06000" stroke="#8A5400" stroke-width="1"/>
      <!-- 八角形正面 -->
      <polygon id="octFace"
        points="155,38 181,28 207,28 233,38 243,64 243,136 233,162 207,172 181,172 155,162 145,136 145,64"
        fill="url(#gOct)" stroke="#B07800" stroke-width="2"/>
      <polygon points="155,38 181,28 207,28 220,44 194,36 168,36 155,50" fill="rgba(255,255,210,.28)" stroke="none"/>
      <!-- 回転ライン -->
      <g id="spinGroup" clip-path="url(#octClip2)">
        <line id="sl1" x1="165" y1="28" x2="165" y2="172" stroke="rgba(160,90,0,.20)" stroke-width="2"/>
        <line id="sl2" x1="183" y1="28" x2="183" y2="172" stroke="rgba(160,90,0,.15)" stroke-width="2"/>
        <line id="sl3" x1="201" y1="28" x2="201" y2="172" stroke="rgba(160,90,0,.20)" stroke-width="2"/>
        <line id="sl4" x1="219" y1="28" x2="219" y2="172" stroke="rgba(160,90,0,.15)" stroke-width="2"/>
        <line id="sl5" x1="237" y1="28" x2="237" y2="172" stroke="rgba(160,90,0,.12)" stroke-width="2"/>
      </g>
      <!-- 窓 -->
      <circle cx="194" cy="100" r="32" fill="rgba(255,255,255,.14)" stroke="rgba(255,255,210,.55)" stroke-width="1.5"/>
      <circle cx="194" cy="100" r="20" fill="rgba(255,255,255,.08)" stroke="rgba(255,255,210,.35)" stroke-width="1"/>
      <!-- 穴 -->
      <circle cx="216" cy="82" r="7" fill="#A06000" stroke="#7A4800" stroke-width="1.3"/>
      <circle cx="216" cy="82" r="4" fill="#1e0c00"/>
      <circle cx="214" cy="80" r="1.4" fill="rgba(255,255,255,.7)"/>
      <text x="194" y="105" text-anchor="middle" font-family="'Dela Gothic One',sans-serif" font-size="10" fill="rgba(255,255,255,.85)">ガラポン</text>
      <!-- ハンドル -->
      <rect x="254" y="58" width="10" height="88" rx="4" fill="#D8D8D8" stroke="#AAAAAA" stroke-width="1"/>
      <rect x="256" y="90" width="36" height="9"  rx="4.5" fill="#DDDDDD" stroke="#AAAAAA" stroke-width="1.2"/>
      <circle cx="295" cy="94" r="11" fill="url(#gKnob2)" stroke="#AAAAAA" stroke-width="1.2"/>
      <circle cx="295" cy="94" r="6"  fill="#BFBFBF"/>
      <circle cx="293" cy="92" r="2"  fill="rgba(255,255,255,.7)"/>
      <!-- 排出口 -->
      <rect x="100" y="135" width="18" height="30" rx="4" fill="#C07800" stroke="#906000" stroke-width="1.2"/>
      <rect x="102" y="137" width="14" height="5"  rx="2" fill="rgba(255,255,220,.3)"/>
      <!-- ベル -->
      <g id="bellG">
        <rect x="49" y="60" width="6" height="22" rx="3" fill="#7a5800" stroke="#5a3800" stroke-width="1"/>
        <path d="M33,81 Q24,96 27,115 Q40,127 52,127 Q64,127 77,115 Q80,96 71,81 Q62,73 52,73 Q42,73 33,81Z" fill="url(#gBell2)" stroke="#B07800" stroke-width="1.8"/>
        <path d="M39,84 Q32,97 35,112 Q41,121 50,122" fill="none" stroke="rgba(255,255,200,.65)" stroke-width="2" stroke-linecap="round"/>
        <ellipse cx="52" cy="127" rx="25" ry="7" fill="#C08000" stroke="#906000" stroke-width="1"/>
        <line x1="52" y1="122" x2="52" y2="133" stroke="#6a4800" stroke-width="2.2"/>
        <circle cx="52" cy="137" r="5.5" fill="#B08000" stroke="#806000" stroke-width="1"/>
        <circle cx="50" cy="135" r="1.8" fill="rgba(255,255,200,.6)"/>
      </g>
      <!-- ベル光線 -->
      <line id="br1" x1="82" y1="100" x2="98" y2="96"  stroke="#F5C000" stroke-width="1.5" stroke-linecap="round" opacity="0"/>
      <line id="br2" x1="82" y1="112" x2="99" y2="114" stroke="#F5C000" stroke-width="1.5" stroke-linecap="round" opacity="0"/>
      <line id="br3" x1="82" y1="90"  x2="98" y2="84"  stroke="#F5C000" stroke-width="1.5" stroke-linecap="round" opacity="0"/>
      <!-- メイン飛び玉 (SVG内) -->
      <circle id="flyBall"  cx="108" cy="150" r="0" fill="#FFD700" stroke="#CC9900" stroke-width="1.5" opacity="0"/>
      <circle id="flyShine" cx="105" cy="147" r="0" fill="rgba(255,255,255,.75)" opacity="0"/>
      <!-- 静的紙吹雪装飾 -->
      <rect x="8"  y="66" width="7" height="5" rx="1" fill="#FF6B6B" transform="rotate(-28,11,68)" opacity=".9"/>
      <rect x="20" y="48" width="6" height="5" rx="1" fill="#4ECDC4" transform="rotate(15,23,50)"  opacity=".9"/>
      <rect x="3"  y="54" width="8" height="4" rx="1" fill="#FADA5E" transform="rotate(-12,7,56)"  opacity=".9"/>
      <rect x="16" y="34" width="6" height="5" rx="1" fill="#A29BFE" transform="rotate(22,19,36)"  opacity=".9"/>
      <rect x="30" y="28" width="7" height="4" rx="1" fill="#55CC88" transform="rotate(-20,33,30)" opacity=".9"/>
      <rect x="10" y="82" width="5" height="6" rx="1" fill="#FFB347" transform="rotate(10,12,85)"  opacity=".8"/>
    </svg>
  </div>

  <div class="result-area" id="resultArea"></div>
  <button class="btn-spin" id="spinBtn" onclick="doSpin()">🎲 まわす！</button>

  <div id="couponSection" style="display:none;">
    <p class="sec-lbl">📋 発行されたクーポン</p>
    <div id="couponArea"></div>
  </div>
</div>

</div><!-- /wrap -->

<script>
/* ===== 定数 ===== */
const PRIZES = [
  {rank:1, label:'🥇 1等！ 300円', bc:'b1', fill:'#FFD700', stroke:'#B8860B', emoji:'🌟', amount:300, chance:.005},
  {rank:2, label:'🥈 2等！ 100円', bc:'b2', fill:'#DDDDDD', stroke:'#888888', emoji:'⭐', amount:100, chance:.03},
  {rank:3, label:'🥉 3等！ 50円',  bc:'b3', fill:'#FF9933', stroke:'#CC6600', emoji:'✨', amount:50,  chance:.05},
  {rank:0, label:'🎀 参加賞 10円', bc:'b0', fill:'#66AAEE', stroke:'#3366BB', emoji:'🎁', amount:10,  chance:1},
];

/* 等級ごとに複数の玉色セット */
const BALL_COLORS = {
  1: ['#FFD700','#FFA500','#FF6600','#FFEE00'],
  2: ['#DDDDDD','#BBBBBB','#AADDFF','#CCCCFF'],
  3: ['#FF9933','#FF6600','#FFAA44','#FF8800'],
  0: ['#66AAEE','#44BBCC','#88CCFF','#5599DD'],
};

let spinning = false;
let coupons  = [];

/* ===== ユーティリティ ===== */
function pick() {
  let r = Math.random(), acc = 0;
  for (const p of PRIZES) { acc += p.chance; if (r < acc) return p; }
  return PRIZES[PRIZES.length - 1];
}
function genId() {
  return 'CP-' + Date.now().toString(36).toUpperCase().slice(-5)
       + '-' + String(Math.floor(Math.random()*1000)).padStart(3,'0');
}
function $(id){ return document.getElementById(id); }

/* ===== ドラム回転 ===== */
function animDrum(onDone) {
  const baseX = [165,183,201,219,237];
  const ids   = ['sl1','sl2','sl3','sl4','sl5'];
  let start = null, phase = 0;
  const dur = 1800;
  function frame(ts) {
    if (!start) start = ts;
    const t    = Math.min((ts - start) / dur, 1);
    const ease = t < .5 ? t*2 : 1-(t-.5)*2;
    phase += ease * 7;
    ids.forEach(function(id, i) {
      var el    = $(id);
      var shift = ((phase*2 + i*18) % 38) - 19;
      el.setAttribute('x1', baseX[i] + shift);
      el.setAttribute('x2', baseX[i] + shift);
    });
    if (t < 1) { requestAnimationFrame(frame); }
    else {
      ids.forEach(function(id,i){
        $(id).setAttribute('x1', baseX[i]);
        $(id).setAttribute('x2', baseX[i]);
      });
      onDone();
    }
  }
  requestAnimationFrame(frame);
}

/* ===== ベル ===== */
function ringBell() {
  var g    = $('bellG');
  var rays = ['br1','br2','br3'];
  var t = 0, frames = 48;
  function step() {
    t++;
    var a = Math.sin(t/3.5) * 24 * Math.max(0, (frames-t)/frames);
    g.setAttribute('transform', 'rotate('+a+',52,96)');
    var show = t > 10 && t < 38;
    rays.forEach(function(id){ $(id).setAttribute('opacity', show ? '1' : '0'); });
    if (t < frames) { requestAnimationFrame(step); }
    else {
      g.setAttribute('transform','');
      rays.forEach(function(id){ $(id).setAttribute('opacity','0'); });
    }
  }
  requestAnimationFrame(step);
}

/* ===== SVG内メイン飛び玉（穴→ベル） ===== */
function animMainBall(prize, onDone) {
  var ball  = $('flyBall');
  var shine = $('flyShine');
  ball.setAttribute('fill',   prize.fill);
  ball.setAttribute('stroke', prize.stroke);
  var t = 0, frames = 55;
  var sx=108, sy=150, ex=50, ey=108;
  function step() {
    t++;
    var p  = t / frames;
    var ep = 1-(1-p)*(1-p);
    var x  = sx + (ex-sx)*ep;
    var y  = sy + (ey-sy)*ep - Math.sin(p*Math.PI)*32;
    var r  = 10 * Math.min(p*4, 1);
    ball.setAttribute('cx', x); ball.setAttribute('cy', y);
    ball.setAttribute('r',  r); ball.setAttribute('opacity','1');
    shine.setAttribute('cx', x-3); shine.setAttribute('cy', y-3);
    shine.setAttribute('r',  r*.32); shine.setAttribute('opacity','1');
    if (t < frames) { requestAnimationFrame(step); }
    else {
      setTimeout(function(){
        ball.setAttribute('r',0);  ball.setAttribute('opacity',0);
        shine.setAttribute('r',0); shine.setAttribute('opacity',0);
        onDone();
      }, 300);
    }
  }
  requestAnimationFrame(step);
}

/* ===== Canvas 玉爆発演出 ===== */
function launchBalls(prize) {
  var canvas = $('ballCanvas');
  var stage  = $('stageWrap');
  var rect   = stage.getBoundingClientRect();
  canvas.width  = stage.offsetWidth;
  canvas.height = stage.offsetHeight;
  var ctx = canvas.getContext('2d');

  /* SVG座標→Canvas座標変換（viewBox 340x220 → 実ピクセル） */
  var scaleX = canvas.width  / 340;
  var scaleY = canvas.height / 220;
  /* 排出口 SVG座標 (109, 148) */
  var originX = 109 * scaleX;
  var originY = 148 * scaleY;

  var cols   = BALL_COLORS[prize.rank];
  var count  = prize.rank === 1 ? 18 : prize.rank === 2 ? 14 : prize.rank === 3 ? 10 : 6;
  var balls  = [];

  for (var i = 0; i < count; i++) {
    /* 左斜め上方向にランダムに射出 */
    var angle = (Math.PI * 1.1) + (Math.random() - 0.5) * Math.PI * 0.7;
    var speed = 3.5 + Math.random() * 4.5;
    balls.push({
      x:  originX,
      y:  originY,
      vx: Math.cos(angle) * speed,
      vy: Math.sin(angle) * speed,
      r:  5 + Math.random() * 5,
      color: cols[i % cols.length],
      alpha: 1,
      gravity: 0.18 + Math.random() * 0.10,
      delay: Math.floor(Math.random() * 12),
    });
  }

  var frame = 0;
  var maxFrames = 80;

  function draw() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    frame++;
    var alive = false;
    balls.forEach(function(b) {
      if (frame < b.delay) { alive = true; return; }
      b.vy += b.gravity;
      b.x  += b.vx;
      b.y  += b.vy;
      b.alpha = Math.max(0, 1 - (frame - b.delay) / (maxFrames * 0.85));
      if (b.alpha <= 0) return;
      alive = true;
      ctx.save();
      ctx.globalAlpha = b.alpha;
      /* グラデーション風の玉 */
      var grad = ctx.createRadialGradient(b.x - b.r*.3, b.y - b.r*.3, b.r*.1, b.x, b.y, b.r);
      grad.addColorStop(0, '#FFFFFF');
      grad.addColorStop(0.35, b.color);
      grad.addColorStop(1,   shadeColor(b.color, -40));
      ctx.beginPath();
      ctx.arc(b.x, b.y, b.r, 0, Math.PI*2);
      ctx.fillStyle = grad;
      ctx.fill();
      ctx.strokeStyle = shadeColor(b.color, -60);
      ctx.lineWidth   = 0.8;
      ctx.stroke();
      ctx.restore();
    });
    if (alive && frame < maxFrames + 20) {
      requestAnimationFrame(draw);
    } else {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
    }
  }
  requestAnimationFrame(draw);
}

/* 色を明暗調整するヘルパー */
function shadeColor(hex, amt) {
  var num = parseInt(hex.replace('#',''), 16);
  var r   = Math.min(255, Math.max(0, (num >> 16) + amt));
  var g   = Math.min(255, Math.max(0, ((num >> 8) & 0xFF) + amt));
  var b   = Math.min(255, Math.max(0, (num & 0xFF) + amt));
  return '#' + ((1<<24)|(r<<16)|(g<<8)|b).toString(16).slice(1);
}

/* ===== 紙吹雪 ===== */
function showConfetti(prize) {
  if (prize.rank === 0) return;
  var w    = $('confBox');
  w.innerHTML = '';
  var cols = ['#FFD700','#FF6B6B','#4ECDC4','#45B7D1','#96CEB4','#FFEAA7','#A29BFE','#FF6B9D'];
  var num  = prize.rank === 1 ? 34 : prize.rank === 2 ? 26 : 18;
  for (var i = 0; i < num; i++) {
    var el = document.createElement('div');
    el.className = 'confetti-p';
    el.style.background        = cols[i % cols.length];
    el.style.left              = (Math.random()*100) + '%';
    el.style.animationDelay    = (Math.random()*.6)  + 's';
    el.style.animationDuration = (.85 + Math.random()*.55) + 's';
    el.style.width             = (6 + Math.random()*6) + 'px';
    el.style.height            = (6 + Math.random()*6) + 'px';
    w.appendChild(el);
  }
  setTimeout(function(){ w.innerHTML=''; }, 2600);
}

/* ===== メインスピン ===== */
function doSpin() {
  if (spinning) return;
  spinning = true;
  $('spinBtn').disabled = true;
  $('resultArea').innerHTML = '';

  var prize = pick();

  animDrum(function() {
    ringBell();
    animMainBall(prize, function() {
      /* Canvas玉爆発 */
      launchBalls(prize);
      /* 紙吹雪 */
      showConfetti(prize);
      /* 結果表示 */
      $('resultArea').innerHTML = '<span class="rbadge ' + prize.bc + '">' + prize.label + '</span>';
      /* クーポン発行 */
      issueCoupon(prize);
      spinning = false;
      $('spinBtn').disabled = false;
    });
  });
}

/* ===== クーポン ===== */
function issueCoupon(prize) {
  var id  = genId();
  var now = new Date();
  var exp = new Date(now);
  exp.setDate(exp.getDate() + 30);
  var fmt = function(d) {
    return d.getFullYear() + '/'
      + String(d.getMonth()+1).padStart(2,'0') + '/'
      + String(d.getDate()).padStart(2,'0');
  };
  coupons.unshift({ id:id, prize:prize, used:false, issued:fmt(now), expires:fmt(exp) });
  renderCoupons();
}

function renderCoupons() {
  var area = $('couponArea');
  var sec  = $('couponSection');
  if (!coupons.length) { sec.style.display='none'; return; }
  sec.style.display = 'block';
  area.innerHTML = '';
  coupons.forEach(function(c, i) {
    var d = document.createElement('div');
    d.className = 'coupon' + (c.used ? ' used' : '');
    d.innerHTML =
      '<div class="c-icon">' + c.prize.emoji + '</div>'
      + '<div class="c-info">'
        + '<div class="c-title">' + c.prize.amount + '円 クーポン</div>'
        + '<div class="c-meta">発行:' + c.issued + ' / 期限:' + c.expires + '</div>'
        + '<div class="c-id">' + c.id + '</div>'
      + '</div>'
      + (c.used
        ? '<div class="used-lbl">使用済</div>'
        : '<button class="btn-use" onclick="useCoupon(' + i + ')">使用済にする</button>');
    area.appendChild(d);
  });
}

function useCoupon(i) {
  if (coupons[i]) { coupons[i].used = true; renderCoupons(); }
}
</script>
</body>
</html>
