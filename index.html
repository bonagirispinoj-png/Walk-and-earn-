<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,user-scalable=no"/>
<meta name="theme-color" content="#0a2218"/>
<title>Health is Wealth — Walk & Earn</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;800&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet"/>
<script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-app-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-auth-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-firestore-compat.js"></script>
<style>
:root{--g1:#071c10;--g2:#0d4a28;--g3:#12803e;--g4:#1ab358;--gold:#f0b429;--gold2:#fad369;--bg:#f2faf5;--bg2:#e0f4ea;--surf:#fff;--bdr:#b8ddc8;--bdr2:#90c8a8;--txt:#061810;--txt2:#1a3828;--txt3:#2e6040;--txt4:#5a9070;--green:#0d9e4a;--green2:#c8f0dc;--red:#c82020;--red2:#ffe0e0;--amber:#b86a00;--amber2:#fff0cc;--r:16px;--ra:24px;--ease:cubic-bezier(.4,0,.2,1);--spring:cubic-bezier(.34,1.56,.64,1);}
[data-theme=dark]{--bg:#060f08;--bg2:#0a1a0e;--surf:#0d1f12;--bdr:#1a3422;--bdr2:#244830;--txt:#d8f0e2;--txt2:#a0c8b0;--txt3:#609870;--txt4:#3a7050;--green2:#0a2416;--red2:#280808;--amber2:#180f00;}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;-webkit-font-smoothing:antialiased;}
html,body{height:100%;overflow-x:hidden;}
body{font-family:"DM Sans",sans-serif;background:var(--bg);color:var(--txt);min-height:100vh;}
h1,h2,h3{font-family:"Playfair Display",serif;}
button,input,select,textarea{font-family:"DM Sans",sans-serif;}
::-webkit-scrollbar{width:4px;}::-webkit-scrollbar-thumb{background:var(--bdr2);border-radius:2px;}
#splash{position:fixed;inset:0;z-index:9999;background:linear-gradient(160deg,#040e08,#071c10,#0a3018);display:flex;flex-direction:column;align-items:center;justify-content:center;transition:opacity .6s,visibility .6s;}
#splash.gone{opacity:0;visibility:hidden;pointer-events:none;}
.sp-logo{width:80px;height:80px;border-radius:50%;background:radial-gradient(circle,#1ab358,#071c10);border:2px solid rgba(240,180,41,.3);display:flex;align-items:center;justify-content:center;font-size:2.4rem;animation:pr 2s ease infinite;margin-bottom:16px;}
@keyframes pr{0%,100%{box-shadow:0 0 0 0 rgba(240,180,41,.4);}50%{box-shadow:0 0 0 16px rgba(240,180,41,0);}}
.sp-title{font-family:"Playfair Display",serif;font-size:1.9rem;color:#fff;font-weight:800;}.sp-title span{color:#fad369;}
.sp-sub{font-size:.66rem;color:rgba(255,255,255,.35);letter-spacing:4px;text-transform:uppercase;margin-top:5px;}
.sp-bar{width:180px;height:2px;background:rgba(255,255,255,.08);border-radius:1px;margin-top:26px;overflow:hidden;}
.sp-fill{height:100%;background:linear-gradient(90deg,transparent,#fad369,transparent);animation:ss 2s ease-in-out forwards;}
@keyframes ss{from{transform:translateX(-100%);}to{transform:translateX(100%);}}
/* AUTH */
#authScreen{min-height:100vh;display:none;flex-direction:column;align-items:center;justify-content:center;background:linear-gradient(160deg,#040e08,#071c10,#0a3018);padding:20px;}
.auth-box{width:100%;max-width:380px;background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.12);border-radius:var(--ra);padding:28px 22px;backdrop-filter:blur(20px);}
.auth-logo{text-align:center;margin-bottom:20px;}
.auth-ico{font-size:2.8rem;filter:drop-shadow(0 0 16px rgba(26,179,88,.5));margin-bottom:8px;}
.auth-logo h1{font-size:1.8rem;font-weight:800;color:#fff;}.auth-logo h1 span{color:#fad369;}
.auth-logo p{font-size:.64rem;color:rgba(255,255,255,.3);letter-spacing:3px;text-transform:uppercase;margin-top:4px;}
.auth-tabs{display:flex;background:rgba(0,0,0,.3);border-radius:10px;padding:3px;margin-bottom:18px;gap:3px;}
.auth-tab{flex:1;padding:9px;border:none;border-radius:8px;cursor:pointer;font-size:.82rem;font-weight:600;transition:.2s;background:transparent;color:rgba(255,255,255,.38);}
.auth-tab.on{background:linear-gradient(135deg,#0d6e3a,#1ab358);color:#fff;}
.ai{width:100%;padding:12px 13px;margin-bottom:10px;background:rgba(255,255,255,.07);border:1.5px solid rgba(255,255,255,.13);border-radius:10px;color:#fff;font-size:.88rem;outline:none;transition:.2s;}
.ai:focus{border-color:#1ab358;}.ai::placeholder{color:rgba(255,255,255,.28);}
.pw-row{position:relative;margin-bottom:10px;}.pw-row .ai{margin-bottom:0;padding-right:42px;}
.pw-eye{position:absolute;right:12px;top:50%;transform:translateY(-50%);background:none;border:none;color:rgba(255,255,255,.38);cursor:pointer;font-size:.95rem;}
.btn-gold{width:100%;padding:13px;border:none;border-radius:10px;cursor:pointer;background:linear-gradient(135deg,#8a6210,#f0b429,#fad369);color:#071c10;font-weight:800;font-size:.9rem;box-shadow:0 6px 22px rgba(240,180,41,.45);transition:.2s;}
.btn-gold:hover{transform:translateY(-1px);}.btn-gold:disabled{opacity:.5;cursor:not-allowed;transform:none;}
.auth-err{color:#ff9090;font-size:.74rem;text-align:center;min-height:16px;margin-top:5px;font-weight:500;}
.auth-ok{color:#6ee7b7;font-size:.74rem;text-align:center;font-weight:500;}
.auth-forgot{text-align:right;margin-bottom:8px;}.auth-forgot button{background:none;border:none;color:rgba(255,255,255,.35);font-size:.72rem;cursor:pointer;}
.auth-admin-link{text-align:center;margin-top:14px;padding-top:12px;border-top:1px solid rgba(255,255,255,.07);}
.auth-admin-link button{background:none;border:none;color:rgba(255,255,255,.18);font-size:.66rem;cursor:pointer;}
/* APP */
#userApp{display:none;min-height:100vh;padding-bottom:72px;}
.topbar{background:linear-gradient(135deg,#071c10,#0d6e3a);position:sticky;top:0;z-index:400;display:flex;align-items:center;justify-content:space-between;padding:11px 15px;box-shadow:0 3px 18px rgba(0,0,0,.35);}
.tb-brand{display:flex;align-items:center;gap:7px;}
.tb-ico{font-size:1.3rem;}
.tb-name{font-family:"Playfair Display",serif;font-size:.95rem;font-weight:700;color:#fff;}.tb-name span{color:#fad369;}
.tb-right{display:flex;align-items:center;gap:5px;}
.tb-pill{background:rgba(240,180,41,.18);border:1px solid rgba(240,180,41,.35);color:#fad369;padding:4px 9px;border-radius:14px;font-size:.7rem;font-weight:700;cursor:pointer;}
.tb-btn{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.18);color:rgba(255,255,255,.65);padding:5px 8px;border-radius:7px;cursor:pointer;font-size:.75rem;}
.tb-logout{background:rgba(200,32,32,.15);border:1px solid rgba(200,32,32,.3);color:#ff9090;padding:5px 9px;border-radius:7px;cursor:pointer;font-size:.7rem;}
.bnav{position:fixed;bottom:0;left:0;right:0;z-index:400;background:var(--surf);border-top:2px solid var(--bdr);display:none;padding-bottom:env(safe-area-inset-bottom);}
.bn-item{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px;padding:8px 2px;background:none;border:none;cursor:pointer;transition:.2s;}
.bn-item.on{color:var(--green);}.bn-item.on .bn-ico{transform:translateY(-2px) scale(1.12);}
.bn-item:not(.on){color:var(--txt4);}
.bn-ico{font-size:1.1rem;line-height:1;transition:.2s;}.bn-lbl{font-size:.5rem;font-weight:700;letter-spacing:.2px;text-transform:uppercase;}
.pg{display:none;}.pg.on{display:block;}
.wrap{max-width:480px;margin:0 auto;padding:13px 13px 15px;}
.card{background:var(--surf);border:1.5px solid var(--bdr);border-radius:var(--r);padding:15px;margin-bottom:12px;}
.card-hd{font-family:"Playfair Display",serif;font-size:1rem;font-weight:700;color:var(--txt);margin-bottom:11px;display:flex;align-items:center;gap:7px;}
.card-hd::before{content:"";width:3px;height:15px;background:linear-gradient(180deg,var(--g4),var(--gold));border-radius:2px;flex-shrink:0;}
.sect-hd{font-size:.66rem;color:var(--txt4);letter-spacing:2.5px;text-transform:uppercase;margin:15px 0 8px;display:flex;align-items:center;gap:7px;}
.sect-hd::after{content:"";flex:1;height:1px;background:var(--bdr);}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:5px;padding:9px 15px;border:none;border-radius:10px;cursor:pointer;font-weight:700;font-size:.82rem;transition:.2s;}
.btn-primary{background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;}.btn-primary:hover{transform:translateY(-1px);}
.btn-red{background:linear-gradient(135deg,#8a1010,#c82020);color:#fff;}
.btn-outline{background:transparent;border:1.5px solid var(--bdr);color:var(--txt2);}
.btn-full{width:100%;display:flex;}.btn:disabled{opacity:.45;cursor:not-allowed;transform:none!important;}
.inp{width:100%;padding:11px 12px;border:1.5px solid var(--bdr);border-radius:10px;font-size:.86rem;outline:none;background:var(--bg);color:var(--txt);margin-bottom:10px;}
.inp:focus{border-color:var(--g3);background:var(--surf);}.inp::placeholder{color:var(--txt4);}
.empty{text-align:center;padding:28px 18px;color:var(--txt4);}
.empty-ico{font-size:2.4rem;margin-bottom:8px;}.empty-txt{font-size:.82rem;}
.hero-banner{background:linear-gradient(135deg,#071c10 0%,#0d6e3a 55%,#14a050 100%);border-radius:18px;padding:20px 16px;margin-bottom:13px;position:relative;overflow:hidden;}
.hero-greet{color:rgba(255,255,255,.55);font-size:.74rem;margin-bottom:2px;}
.hero-name{color:#fff;font-family:"Playfair Display",serif;font-size:1.4rem;font-weight:700;margin-bottom:13px;}.hero-name span{color:#fad369;}
.hero-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;}
.hero-stat{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.14);border-radius:11px;padding:9px;text-align:center;}
.hero-stat-v{font-family:"Playfair Display",serif;font-size:1.2rem;font-weight:700;color:#fad369;}
.hero-stat-l{font-size:.54rem;color:rgba(255,255,255,.45);margin-top:2px;}
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:9px;margin-bottom:12px;}
.stat-card{background:var(--surf);border:1.5px solid var(--bdr);border-radius:var(--r);padding:13px;position:relative;overflow:hidden;}
.stat-card::before{content:"";position:absolute;top:0;left:0;right:0;height:3px;border-radius:3px 3px 0 0;}
.sc-walk::before{background:linear-gradient(90deg,#f0b429,#fad369);}.sc-earn::before{background:linear-gradient(90deg,#0d9e4a,#1ab358);}
.sc-ref::before{background:linear-gradient(90deg,#6820d0,#a050f8);}.sc-wallet::before{background:linear-gradient(90deg,#1448b8,#38a0f8);}
.stat-v{font-family:"Playfair Display",serif;font-size:1.6rem;font-weight:700;color:var(--txt);line-height:1;}
.stat-l{font-size:.62rem;color:var(--txt4);margin-top:2px;letter-spacing:.5px;text-transform:uppercase;}
.stat-sub{font-size:.68rem;color:var(--txt3);margin-top:4px;}
.progress-bar{height:5px;background:var(--bg2);border-radius:3px;overflow:hidden;margin-top:7px;}
.pb-fill{height:100%;border-radius:3px;transition:width .7s var(--ease);}
.pb-walk{background:linear-gradient(90deg,#f0b429,#fad369);}.pb-earn{background:linear-gradient(90deg,#0d9e4a,#1ab358);}
.prize-banner{background:linear-gradient(135deg,#1a0a38,#3818a0,#2a0870);border-radius:18px;padding:18px;margin-bottom:13px;}
.prize-title{font-family:"Playfair Display",serif;font-size:1rem;color:#fff;font-weight:700;margin-bottom:3px;}
.prize-sub{font-size:.7rem;color:rgba(255,255,255,.45);margin-bottom:13px;}
.prize-list{display:flex;flex-direction:column;gap:7px;}
.prize-item{display:flex;align-items:center;gap:11px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.12);border-radius:11px;padding:11px 13px;}
.prize-rank{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.1rem;font-weight:800;flex-shrink:0;}
.pr-1{background:linear-gradient(135deg,#FFD700,#FFA500);color:#fff;}.pr-2{background:linear-gradient(135deg,#C0C0C0,#A0A0A0);color:#fff;}.pr-3{background:linear-gradient(135deg,#CD7F32,#A0520A);color:#fff;}
.prize-info{flex:1;}.prize-name{font-weight:700;font-size:.88rem;color:#fff;}
.prize-amt{font-size:1.05rem;font-weight:800;color:#fad369;font-family:"Playfair Display",serif;}
.prize-who{font-size:.68rem;color:rgba(255,255,255,.45);margin-top:1px;}
.how-step{display:flex;align-items:flex-start;gap:11px;padding:11px 0;border-bottom:1px solid var(--bdr);}
.how-step:last-child{border-bottom:none;}
.how-num{width:30px;height:30px;border-radius:50%;background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;display:flex;align-items:center;justify-content:center;font-size:.76rem;font-weight:800;flex-shrink:0;}
.how-body{flex:1;}.how-title{font-size:.86rem;font-weight:700;color:var(--txt2);}
.how-desc{font-size:.74rem;color:var(--txt4);margin-top:2px;line-height:1.5;}
.how-badge{display:inline-block;background:#fad369;color:#071c10;padding:2px 7px;border-radius:18px;font-size:.63rem;font-weight:800;margin-top:3px;}
.gps-card{background:linear-gradient(135deg,#061410,#0a2a18,#0d6e3a);border-radius:18px;padding:18px;margin-bottom:13px;}
.gps-status-row{display:flex;align-items:center;gap:9px;margin-bottom:13px;}
.gps-dot{width:9px;height:9px;border-radius:50%;background:#4ade80;flex-shrink:0;}
.gps-dot.off{background:#6b7280;}.gps-dot.live{animation:blink 1.5s ease infinite;}.gps-dot.paused{background:#fad369;animation:blink 1s ease infinite;}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:.3;}}
.gps-status-txt{font-size:.82rem;color:rgba(255,255,255,.75);font-weight:600;}
.gps-metrics{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin-bottom:13px;}
.gps-metric{background:rgba(255,255,255,.09);border:1px solid rgba(255,255,255,.1);border-radius:9px;padding:9px;text-align:center;}
.gps-metric-v{font-family:"Playfair Display",serif;font-size:1.3rem;font-weight:700;color:#fad369;}
.gps-metric-l{font-size:.54rem;color:rgba(255,255,255,.4);margin-top:2px;}
.gps-prog-wrap{background:rgba(255,255,255,.08);border-radius:7px;height:7px;margin-bottom:9px;overflow:hidden;}
.gps-prog-fill{height:100%;background:linear-gradient(90deg,#f0b429,#fad369);border-radius:7px;transition:width .4s var(--ease);}
.gps-cap-txt{font-size:.64rem;color:rgba(255,255,255,.3);text-align:right;margin-bottom:11px;}
.gps-btns{display:flex;gap:7px;}
.gps-btn{flex:1;padding:11px;border:none;border-radius:9px;cursor:pointer;font-size:.82rem;font-weight:700;display:flex;align-items:center;justify-content:center;gap:5px;}
.gps-start{background:linear-gradient(135deg,#0d6e3a,#1ab358);color:#fff;}
.gps-stop{background:linear-gradient(135deg,#8a1010,#c82020);color:#fff;}
.gps-pause{background:rgba(255,255,255,.12);color:#fff;border:1px solid rgba(255,255,255,.18);}
.gps-locked{background:rgba(255,255,255,.05);border:1.5px solid rgba(240,180,41,.25);border-radius:12px;padding:15px;text-align:center;margin-bottom:13px;}
.ref-box{background:linear-gradient(135deg,#071c10,#0f3820,#0d6e3a);border-radius:18px;padding:20px;margin-bottom:13px;}
.ref-reward{display:flex;align-items:center;gap:13px;background:rgba(240,180,41,.15);border:1px solid rgba(240,180,41,.3);border-radius:11px;padding:11px 13px;margin-bottom:13px;}
.ref-reward-amt{font-family:"Playfair Display",serif;font-size:1.9rem;font-weight:700;color:#fad369;line-height:1;}
.ref-reward-info{flex:1;}.ref-reward-title{font-weight:700;font-size:.86rem;color:#fff;}
.ref-reward-sub{font-size:.7rem;color:rgba(255,255,255,.5);margin-top:2px;line-height:1.4;}
.ref-code-box{background:rgba(0,0,0,.3);border:1px solid rgba(255,255,255,.1);border-radius:11px;padding:13px;margin-bottom:11px;}
.ref-code-lbl{font-size:.63rem;color:rgba(255,255,255,.35);letter-spacing:2px;text-transform:uppercase;margin-bottom:5px;}
.ref-code-val{font-family:"Playfair Display",serif;font-size:1.7rem;font-weight:700;color:#fad369;letter-spacing:3px;}
.ref-url{font-size:.66rem;color:rgba(255,255,255,.3);margin-top:3px;word-break:break-all;}
.ref-btns{display:flex;gap:7px;flex-wrap:wrap;}
.ref-btn{flex:1;min-width:78px;padding:8px 11px;border:none;border-radius:8px;cursor:pointer;font-size:.72rem;font-weight:700;display:flex;align-items:center;justify-content:center;gap:4px;}
.rb-copy{background:rgba(255,255,255,.12);color:#fff;border:1px solid rgba(255,255,255,.18);}
.rb-wa{background:#25d366;color:#fff;}.rb-tg{background:#0088cc;color:#fff;}
.recruit-item{display:flex;align-items:center;gap:11px;padding:10px 0;border-bottom:1px solid var(--bdr);}
.recruit-item:last-child{border-bottom:none;}
.recruit-av{width:36px;height:36px;border-radius:50%;background:linear-gradient(135deg,#071c10,#0d6e3a);display:flex;align-items:center;justify-content:center;color:#fad369;font-weight:700;font-size:.82rem;flex-shrink:0;}
.rb-paid{background:var(--green2);color:var(--green);padding:2px 7px;border-radius:5px;font-size:.62rem;font-weight:800;}
.rb-pending{background:var(--amber2);color:var(--amber);padding:2px 7px;border-radius:5px;font-size:.62rem;font-weight:800;}
.km-cycle-card{background:var(--surf);border:1.5px solid var(--bdr);border-radius:15px;padding:15px;margin-bottom:12px;position:relative;overflow:hidden;}
.km-cycle-card::before{content:"";position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,#f0b429,var(--g4));}
.km-nums{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin-bottom:9px;}
.km-num{background:var(--bg2);border-radius:9px;padding:9px 7px;text-align:center;}
.km-num-v{font-family:"Playfair Display",serif;font-size:1.3rem;font-weight:700;color:var(--txt);}
.km-num-l{font-size:.54rem;color:var(--txt4);margin-top:2px;}
.wallet-hero{background:linear-gradient(135deg,#040c08,#071c10,#0d6e3a);border-radius:18px;padding:24px 18px;text-align:center;margin-bottom:13px;}
.wallet-lbl{font-size:.66rem;color:rgba(255,255,255,.35);letter-spacing:3px;text-transform:uppercase;}
.wallet-amt{font-family:"Playfair Display",serif;font-size:2.8rem;font-weight:700;color:#fff;margin:5px 0 2px;}.wallet-amt span{color:#fad369;}
.wallet-sub{font-size:.72rem;color:rgba(255,255,255,.4);}
.txn-item{display:flex;align-items:center;gap:11px;padding:10px 0;border-bottom:1px solid var(--bdr);}
.txn-item:last-child{border-bottom:none;}
.txn-ico{width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.95rem;flex-shrink:0;}
.txn-ico-in{background:var(--green2);}.txn-ico-out{background:var(--red2);}
.txn-desc{flex:1;font-size:.82rem;font-weight:600;color:var(--txt2);}
.txn-status{font-size:.64rem;font-weight:800;text-transform:uppercase;margin-top:1px;}
.txn-in{color:var(--green);font-weight:800;}.txn-out{color:var(--red);font-weight:800;}
.wd-method-btn{flex:1;padding:8px;border:1.5px solid var(--bdr);border-radius:9px;cursor:pointer;font-size:.72rem;font-weight:700;background:var(--bg);color:var(--txt2);transition:.2s;}
.wd-method-btn.on{background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;border-color:transparent;}
.profile-avatar{width:68px;height:68px;border-radius:50%;background:linear-gradient(135deg,#071c10,#0d6e3a);display:flex;align-items:center;justify-content:center;font-size:1.9rem;margin:0 auto 11px;border:3px solid #fad369;}
.profile-badge{display:inline-block;padding:3px 11px;border-radius:18px;font-size:.7rem;font-weight:700;margin-top:3px;}
.badge-paid{background:var(--green2);color:var(--green);}.badge-free{background:var(--amber2);color:var(--amber);}
/* QR SCANNER */
#qrOverlay{position:fixed;inset:0;z-index:1000;background:rgba(0,0,0,.9);display:none;flex-direction:column;align-items:center;justify-content:center;padding:20px;}
#qrOverlay.on{display:flex;}
#qrVideo{width:100%;max-width:320px;border-radius:16px;border:3px solid #fad369;}
.qr-frame{position:relative;width:100%;max-width:320px;margin-bottom:16px;}
.qr-frame::after{content:"";position:absolute;inset:10px;border:2px solid #fad369;border-radius:10px;pointer-events:none;}
#qrResult{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.2);border-radius:10px;padding:12px;color:#fff;font-size:.84rem;text-align:center;margin-bottom:12px;width:100%;max-width:320px;word-break:break-all;}
/* PAYMENT SHEET */
.upi-sheet{position:fixed;inset:0;z-index:800;background:rgba(0,0,0,.65);backdrop-filter:blur(6px);display:flex;align-items:flex-end;justify-content:center;opacity:0;visibility:hidden;transition:.3s;}
.upi-sheet.on{opacity:1;visibility:visible;}
.upi-content{background:var(--surf);border-radius:22px 22px 0 0;padding:22px 18px 38px;width:100%;max-width:480px;transform:translateY(100%);transition:.35s var(--spring);max-height:92vh;overflow-y:auto;}
.upi-sheet.on .upi-content{transform:translateY(0);}
.upi-handle{width:38px;height:4px;background:var(--bdr2);border-radius:2px;margin:0 auto 18px;}
.upi-amount{background:linear-gradient(135deg,#071c10,#0d6e3a);border-radius:13px;padding:15px;text-align:center;margin-bottom:15px;}
.upi-step{background:var(--bg);border:1.5px solid var(--bdr);border-radius:11px;padding:13px;margin-bottom:11px;display:flex;align-items:flex-start;gap:11px;}
.upi-step-num{width:24px;height:24px;background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.7rem;font-weight:800;flex-shrink:0;margin-top:1px;}
.upi-id-box{background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;padding:9px 15px;border-radius:9px;font-size:.95rem;font-weight:800;margin:7px 0;text-align:center;}
.upi-app-btn{width:100%;padding:12px;border:none;border-radius:11px;cursor:pointer;font-size:.88rem;font-weight:700;margin-bottom:9px;display:flex;align-items:center;justify-content:center;gap:7px;}
.upi-gpay{background:linear-gradient(135deg,#4285f4,#1967d2);color:#fff;}
.upi-phone{background:linear-gradient(135deg,#7b2ff7,#5e12d4);color:#fff;}
.upi-bhim{background:linear-gradient(135deg,#0052a3,#003880);color:#fff;}
.upi-other{background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;}
.upi-inp{width:100%;padding:11px 13px;border:2px solid var(--bdr);border-radius:9px;font-size:.88rem;outline:none;background:var(--bg);color:var(--txt);}
.upi-inp:focus{border-color:var(--g3);}
/* MODAL */
.modal-bg{position:fixed;inset:0;z-index:900;background:rgba(0,0,0,.7);backdrop-filter:blur(8px);display:flex;align-items:center;justify-content:center;padding:18px;opacity:0;visibility:hidden;transition:.3s;}
.modal-bg.on{opacity:1;visibility:visible;}
.modal-box{background:var(--surf);border-radius:22px;padding:30px 22px;width:100%;max-width:340px;text-align:center;animation:mi .4s var(--spring) both;}
@keyframes mi{from{opacity:0;transform:scale(.85);}to{opacity:1;transform:none;}}
.modal-ico{font-size:3.2rem;margin-bottom:11px;}
/* ADMIN */
#adminApp{display:none;min-height:100vh;background:#f0faf5;}
.admin-hd{background:linear-gradient(135deg,#071c10,#0d6e3a);padding:13px 18px;display:flex;align-items:center;justify-content:space-between;}
.admin-hd h1{color:#fff;font-size:1rem;font-weight:800;}.admin-hd h1 span{color:#fad369;}
.admin-tabs{background:#fff;border-bottom:2px solid #b0d8c0;display:flex;overflow-x:auto;padding:0 6px;}
.admin-tab{padding:11px 14px;border:none;background:transparent;font-size:.78rem;font-weight:700;cursor:pointer;color:#5a9070;border-bottom:3px solid transparent;margin-bottom:-2px;white-space:nowrap;transition:.2s;}
.admin-tab.on{color:#071c10;border-bottom-color:#f0b429;}
.admin-content{max-width:1100px;margin:0 auto;padding:14px;}
.admin-stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:9px;margin-bottom:14px;}
.admin-stat{background:linear-gradient(135deg,#fff,#edf8f2);border:1.5px solid #b0d8c0;border-radius:13px;padding:14px;text-align:center;position:relative;overflow:hidden;}
.admin-stat::before{content:"";position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,#0d9e4a,#f0b429);}
.admin-stat-v{font-family:"Playfair Display",serif;font-size:1.9rem;font-weight:700;color:#071c10;}
.admin-stat-l{font-size:.6rem;color:#5a9070;margin-top:3px;text-transform:uppercase;letter-spacing:.5px;font-weight:600;}
.admin-section{background:#fff;border:1.5px solid #b0d8c0;border-radius:14px;overflow:hidden;margin-bottom:14px;}
.admin-section-hd{padding:13px 16px;border-bottom:1.5px solid #daf0e4;display:flex;align-items:center;justify-content:space-between;background:linear-gradient(135deg,#fff,#f0faf5);}
.admin-section-hd h3{font-size:.88rem;font-weight:800;color:#071c10;}
.tbl{width:100%;border-collapse:collapse;}
.tbl th{background:linear-gradient(135deg,#d8f0e4,#c0e8d0);padding:9px 12px;font-size:.66rem;font-weight:800;color:#1a6a3a;text-align:left;text-transform:uppercase;letter-spacing:.5px;}
.tbl td{padding:10px 12px;border-bottom:1px solid #daf0e4;font-size:.8rem;color:#1a3828;vertical-align:middle;}
.tbl tr:last-child td{border-bottom:none;}.tbl tr:hover td{background:#f0faf5;}
.pill{display:inline-block;padding:2px 8px;border-radius:18px;font-size:.62rem;font-weight:800;text-transform:uppercase;}
.pill-p{background:#fff0cc;color:#b86a00;border:1px solid #f0b429;}
.pill-a{background:#c8f0dc;color:#0d7a3a;border:1px solid #5ac888;}
.pill-r{background:#ffe0e0;color:#b01818;border:1px solid #f09090;}
.btn-a{background:linear-gradient(135deg,#0d6e3a,#14a050);color:#fff;border:none;padding:5px 11px;border-radius:7px;cursor:pointer;font-size:.72rem;font-weight:700;}
.btn-r{background:linear-gradient(135deg,#8a1010,#c82020);color:#fff;border:none;padding:5px 11px;border-radius:7px;cursor:pointer;font-size:.72rem;font-weight:700;}
.btn-danger{background:linear-gradient(135deg,#5a0a0a,#a01010);color:#fff;border:none;padding:4px 8px;border-radius:6px;cursor:pointer;font-size:.68rem;font-weight:700;}
.refresh-btn{background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fad369;border:none;padding:7px 13px;border-radius:8px;cursor:pointer;font-size:.74rem;font-weight:800;}
.admin-inp{width:100%;padding:9px 11px;border:1.5px solid #b0d8c0;border-radius:8px;font-size:.84rem;outline:none;background:#fff;color:#071c10;margin-bottom:8px;}
.admin-free-ref{background:linear-gradient(135deg,#071c10,#0d6e3a);border-radius:13px;padding:15px;margin-bottom:13px;color:#fff;}
.admin-free-ref h4{font-size:.88rem;color:#fad369;margin-bottom:7px;}
.admin-ref-code{font-family:"Playfair Display",serif;font-size:1.5rem;color:#fad369;letter-spacing:3px;font-weight:700;}
.wd-detail-box{background:#f0faf5;border:1px solid #b0d8c0;border-radius:7px;padding:7px 9px;font-size:.72rem;color:#1a3828;line-height:1.7;}
.wd-detail-box strong{color:#071c10;}
@media(max-width:600px){.tbl{font-size:.72rem;}.tbl td,.tbl th{padding:7px 9px;}}
#toast{position:fixed;bottom:82px;left:50%;transform:translateX(-50%) translateY(12px);background:linear-gradient(135deg,#071c10,#0d6e3a);color:#fff;padding:9px 20px;border-radius:20px;font-size:.78rem;font-weight:600;z-index:9999;opacity:0;transition:.3s;pointer-events:none;white-space:nowrap;max-width:90vw;}
#toast.on{opacity:1;transform:translateX(-50%) translateY(0);}
</style>
</head>
<body>
<div id="splash"><div class="sp-logo">🌿</div><div class="sp-title">Health is <span>Wealth</span></div><div class="sp-sub">Walk · Earn · Win</div><div class="sp-bar"><div class="sp-fill"></div></div></div>

<div id="authScreen" style="display:none">
  <div class="auth-box">
    <div class="auth-logo"><div class="auth-ico">🌿</div><h1>Health is <span>Wealth</span></h1><p>Walk · Earn · Win</p></div>
    <div class="auth-tabs">
      <button class="auth-tab on" id="tabLogin" onclick="switchTab('login')">Sign In</button>
      <button class="auth-tab" id="tabSignup" onclick="switchTab('signup')">Register</button>
    </div>
    <div id="formLogin">
      <input class="ai" type="email" id="loginEmail" placeholder="Email address" autocomplete="email"/>
      <div class="pw-row"><input class="ai" type="password" id="loginPass" placeholder="Password" autocomplete="current-password"/><button type="button" class="pw-eye" onclick="togglePw('loginPass',this)">👁</button></div>
      <div class="auth-forgot"><button onclick="forgotPw()">Forgot password?</button></div>
      <button class="btn-gold" id="btnLogin" onclick="doLogin()">Sign In →</button>
      <div class="auth-err" id="loginErr"></div>
    </div>
    <div id="formSignup" style="display:none">
      <input class="ai" type="text" id="signupName" placeholder="Full Name" autocomplete="name"/>
      <input class="ai" type="email" id="signupEmail" placeholder="Email address" autocomplete="email"/>
      <div class="pw-row"><input class="ai" type="password" id="signupPass" placeholder="Password (8+ chars)" autocomplete="new-password"/><button type="button" class="pw-eye" onclick="togglePw('signupPass',this)">👁</button></div>
      <input class="ai" type="text" id="signupRef" placeholder="Referral code (optional)" oninput="this.value=this.value.toUpperCase()"/>
      <button class="btn-gold" id="btnSignup" onclick="doSignup()">Create Account →</button>
      <div class="auth-err" id="signupErr"></div><div class="auth-ok" id="signupOk"></div>
    </div>
    <div class="auth-admin-link"><button onclick="goAdmin()">🔐 Admin Panel</button></div>
  </div>
</div>

<div id="userApp" style="display:none">
  <div class="topbar">
    <div class="tb-brand"><span class="tb-ico">🌿</span><span class="tb-name">Health is <span>Wealth</span></span></div>
    <div class="tb-right"><span class="tb-pill" onclick="goPage('wallet')" id="tbWallet">₹0</span><button class="tb-btn" onclick="toggleTheme()">🌙</button><button class="tb-logout" onclick="doLogout()">Exit</button></div>
  </div>
  <div id="pgHome" class="pg on">
    <div class="wrap">
      <div class="hero-banner">
        <div class="hero-greet">Good day 👋</div>
        <div class="hero-name" id="heroName">Welcome, <span>Friend</span></div>
        <div class="hero-stats">
          <div class="hero-stat"><div class="hero-stat-v" id="hKm">0.00</div><div class="hero-stat-l">KM Today</div></div>
          <div class="hero-stat"><div class="hero-stat-v" id="hEarned">₹0</div><div class="hero-stat-l">Earned</div></div>
          <div class="hero-stat"><div class="hero-stat-v" id="hRefs">0</div><div class="hero-stat-l">Referrals</div></div>
        </div>
      </div>
      <div class="stat-grid">
        <div class="stat-card sc-walk"><div class="stat-v" id="statKm">0.00</div><div class="stat-l">KM Today</div><div class="stat-sub" id="statKmSub">Cap: 300 KM</div><div class="progress-bar"><div class="pb-fill pb-walk" id="pbKm" style="width:0%"></div></div></div>
        <div class="stat-card sc-wallet"><div class="stat-v" id="statWallet">₹0</div><div class="stat-l">Wallet</div><div class="progress-bar"><div class="pb-fill pb-earn" id="pbWallet" style="width:0%"></div></div></div>
        <div class="stat-card sc-ref"><div class="stat-v" id="statRefs">0</div><div class="stat-l">Referrals</div><div class="stat-sub">₹300 each</div></div>
        <div class="stat-card sc-earn"><div class="stat-v" id="statTotalEarn">₹0</div><div class="stat-l">Total Earned</div></div>
      </div>
      <div id="homePayStatus"></div>
      <div class="sect-hd">🏆 Prizes</div>
      <div class="prize-banner">
        <div class="prize-title">🎁 All-Time Referral Champions</div>
        <div class="prize-sub">Top referrers win massive prizes — no time limit!</div>
        <div class="prize-list">
          <div class="prize-item"><div class="prize-rank pr-1">🥇</div><div class="prize-info"><div class="prize-name">Top Referrer</div><div class="prize-who">Most paid referrals</div></div><div><div class="prize-amt">₹1 Cr</div></div></div>
          <div class="prize-item"><div class="prize-rank pr-2">🥈</div><div class="prize-info"><div class="prize-name">2nd Place</div></div><div><div class="prize-amt">₹75 L</div></div></div>
          <div class="prize-item"><div class="prize-rank pr-3">🥉</div><div class="prize-info"><div class="prize-name">3rd Place</div></div><div><div class="prize-amt">₹50 L</div></div></div>
        </div>
      </div>
      <div class="sect-hd">📋 How It Works</div>
      <div class="card">
        <div class="how-step"><div class="how-num">1</div><div class="how-body"><div class="how-title">Pay ₹1,999 to Unlock</div><div class="how-desc">One-time payment. Referral link activates immediately after payment.</div><div class="how-badge">₹1,999 one-time</div></div></div>
        <div class="how-step"><div class="how-num">2</div><div class="how-body"><div class="how-title">Walk & Earn ₹1/KM</div><div class="how-desc">GPS tracks your walk. Earn ₹1 per KM. Cap: 300 KM per cycle.</div><div class="how-badge">₹1/KM</div></div></div>
        <div class="how-step"><div class="how-num">3</div><div class="how-body"><div class="how-title">Refer & Earn ₹300</div><div class="how-desc">When your friend pays ₹1,999 — you get ₹300 + 300 KM cap reset.</div><div class="how-badge">₹300 + KM reset</div></div></div>
        <div class="how-step"><div class="how-num">4</div><div class="how-body"><div class="how-title">Withdraw via UPI / Bank</div><div class="how-desc">Request payout via GPay, PhonePe, UPI or Bank Transfer. Processed in 1–3 days.</div></div></div>
      </div>
    </div>
  </div>
  <div id="pgEarn" class="pg">
    <div class="wrap">
      <div class="sect-hd">🛰️ GPS Walk & Earn</div>
      <div id="gpsLockedContent">
        <div class="gps-locked">
          <div style="font-size:2.2rem;margin-bottom:7px">🔒</div>
          <div style="font-weight:700;color:var(--txt2);margin-bottom:4px">GPS Earn Locked</div>
          <div style="font-size:.76rem;color:var(--txt4);margin-bottom:13px">Pay ₹1,999 once to unlock GPS walking income.</div>
          <button class="btn btn-primary btn-full" onclick="openPayment()">💳 Unlock Now — ₹1,999</button>
        </div>
      </div>
      <div id="gpsPaidContent" style="display:none">
        <div class="gps-card">
          <div class="gps-status-row"><div class="gps-dot off" id="gpsDot"></div><span class="gps-status-txt" id="gpsStatusTxt">Tap Start to begin tracking</span></div>
          <div class="gps-metrics">
            <div class="gps-metric"><div class="gps-metric-v" id="gpsKm">0.00</div><div class="gps-metric-l">KM Today</div></div>
            <div class="gps-metric"><div class="gps-metric-v" id="gpsSpeed">0.0</div><div class="gps-metric-l">km/h</div></div>
            <div class="gps-metric"><div class="gps-metric-v" id="gpsEarned">₹0</div><div class="gps-metric-l">Session Earn</div></div>
          </div>
          <div class="gps-prog-wrap"><div class="gps-prog-fill" id="gpsProgFill" style="width:0%"></div></div>
          <div class="gps-cap-txt" id="gpsCapTxt">Cap: 300 KM · Walked: 0 KM</div>
          <div class="gps-btns">
            <button class="gps-btn gps-start" id="gpsBtnStart" onclick="startGPS()">📍 Start Walk</button>
            <button class="gps-btn gps-pause" id="gpsBtnPause" onclick="pauseGPS()" style="display:none">⏸ Pause</button>
            <button class="gps-btn gps-stop" id="gpsBtnStop" onclick="stopGPS()" style="display:none">⏹ Stop</button>
          </div>
        </div>
        <div class="km-cycle-card">
          <div style="font-size:.68rem;color:var(--txt4);text-transform:uppercase;letter-spacing:1px;margin-bottom:9px">Walking Cycle</div>
          <div class="km-nums">
            <div class="km-num"><div class="km-num-v" id="cycleWalked">0</div><div class="km-num-l">KM Walked</div></div>
            <div class="km-num"><div class="km-num-v" id="cycleRemain">300</div><div class="km-num-l">KM Left</div></div>
            <div class="km-num"><div class="km-num-v" id="cycleEarned">₹0</div><div class="km-num-l">Earned</div></div>
          </div>
          <div class="progress-bar"><div class="pb-fill pb-walk" id="cycleProg" style="width:0%"></div></div>
          <div style="font-size:.66rem;color:var(--txt4);margin-top:5px;text-align:center" id="cycleCapLbl">Cap: 300 KM — refer friends to reset!</div>
        </div>
      </div>
      <div class="sect-hd">👥 Refer & Earn ₹300</div>
      <div id="refLockedContent"><div class="gps-locked"><div style="font-size:1.9rem;margin-bottom:7px">🔒</div><div style="font-weight:700;color:var(--txt2);margin-bottom:4px">Referral Locked</div><div style="font-size:.76rem;color:var(--txt4)">Pay ₹1,999 to unlock.</div></div></div>
      <div id="refPaidContent" style="display:none">
        <div class="ref-box">
          <div class="ref-reward"><div class="ref-reward-amt">₹300</div><div class="ref-reward-info"><div class="ref-reward-title">Per Paid Referral</div><div class="ref-reward-sub">+300 KM cap reset every referral!</div></div></div>
          <div class="ref-code-box"><div class="ref-code-lbl">Your Referral Code</div><div class="ref-code-val" id="refCode">——</div><div class="ref-url" id="refUrl"></div></div>
          <div class="ref-btns"><button class="ref-btn rb-copy" onclick="copyRef()">📋 Copy</button><button class="ref-btn rb-wa" onclick="shareWA()">💬 WhatsApp</button><button class="ref-btn rb-tg" onclick="shareTG()">✈️ Telegram</button></div>
        </div>
        <div class="card"><div class="card-hd">Your Referrals</div><div id="recruitList"><div class="empty"><div class="empty-ico">👥</div><div class="empty-txt">No paid referrals yet.</div></div></div></div>
      </div>
    </div>
  </div>
  <div id="pgWallet" class="pg">
    <div class="wrap">
      <div class="wallet-hero"><div class="wallet-lbl">Available Balance</div><div class="wallet-amt"><span>₹</span><span id="walletAmt">0</span></div><div class="wallet-sub" id="walletSub">Walk more to earn more</div></div>
      <div id="payStatus"></div>
      <div class="card">
        <div class="card-hd">💸 Request Withdrawal</div>
        <div id="wdPendingBlock" style="display:none">
          <div style="background:var(--amber2);border:1.5px solid rgba(184,106,0,.25);border-radius:11px;padding:13px;margin-bottom:8px">
            <div style="font-size:.86rem;font-weight:700;color:var(--amber);margin-bottom:3px">⏳ Withdrawal Pending</div>
            <div style="font-size:.74rem;color:var(--txt3);margin-bottom:9px;line-height:1.5" id="wdPendingInfo">Your request is under admin review.</div>
            <button class="btn btn-red btn-full" onclick="cancelWithdrawal()">❌ Cancel This Request</button>
          </div>
        </div>
        <div id="wdNewBlock">
          <div style="font-size:.76rem;color:var(--txt4);margin-bottom:11px">⚠️ Min ₹50. One request at a time. Processed in 1–3 days.</div>
          <input class="inp" type="number" id="withdrawAmt" placeholder="Amount in ₹ (min ₹50)" min="50"/>
          <div style="display:flex;gap:6px;margin-bottom:11px">
            <button class="wd-method-btn on" id="wdTabUpi" onclick="switchWDMethod('upi')">📱 UPI / GPay</button>
            <button class="wd-method-btn" id="wdTabBank" onclick="switchWDMethod('bank')">🏦 Bank Account</button>
          </div>
          <div id="wdUpiFields"><input class="inp" type="text" id="withdrawUPI" placeholder="UPI ID / GPay / PhonePe (e.g. 9876543210@ybl)"/></div>
          <div id="wdBankFields" style="display:none">
            <input class="inp" type="text" id="withdrawAccName" placeholder="Account Holder Full Name"/>
            <input class="inp" type="text" id="withdrawAccNo" placeholder="Account Number"/>
            <input class="inp" type="text" id="withdrawAccNo2" placeholder="Re-enter Account Number"/>
            <input class="inp" type="text" id="withdrawIFSC" placeholder="IFSC Code (e.g. SBIN0001234)" oninput="this.value=this.value.toUpperCase()"/>
            <input class="inp" type="text" id="withdrawBankName" placeholder="Bank Name (e.g. SBI, HDFC)"/>
          </div>
          <button class="btn btn-primary btn-full" onclick="requestWithdraw()">💸 Submit Withdrawal Request</button>
        </div>
      </div>
      <div class="card"><div class="card-hd">Transaction History</div><div id="txnList"><div class="empty"><div class="empty-ico">📭</div><div class="empty-txt">No transactions yet</div></div></div></div>
    </div>
  </div>
  <div id="pgProfile" class="pg">
    <div class="wrap">
      <div class="card" style="text-align:center;padding:22px">
        <div class="profile-avatar">👤</div>
        <div style="font-family:'Playfair Display',serif;font-size:1.15rem;font-weight:700" id="profileName">—</div>
        <div style="font-size:.76rem;color:var(--txt4);margin-top:2px" id="profileEmail">—</div>
        <div id="profileBadge" style="margin-top:7px"></div>
      </div>
      <div class="card">
        <div class="card-hd">Account Details</div>
        <div style="display:flex;justify-content:space-between;padding:7px 0;border-bottom:1px solid var(--bdr);font-size:.82rem"><span style="color:var(--txt4)">Referral Code</span><strong id="profRefCode" style="font-family:monospace">—</strong></div>
        <div style="display:flex;justify-content:space-between;padding:7px 0;border-bottom:1px solid var(--bdr);font-size:.82rem"><span style="color:var(--txt4)">Total KM Walked</span><strong id="profTotalKm">0 km</strong></div>
        <div style="display:flex;justify-content:space-between;padding:7px 0;border-bottom:1px solid var(--bdr);font-size:.82rem"><span style="color:var(--txt4)">Paid Referrals</span><strong id="profRefs">0</strong></div>
        <div style="display:flex;justify-content:space-between;padding:7px 0;font-size:.82rem"><span style="color:var(--txt4)">KM Cap Remaining</span><strong id="profCapLeft" style="color:var(--green)">300 km</strong></div>
      </div>
      <div class="card">
        <div class="card-hd">Payment</div>
        <div id="profilePayStatus" style="margin-bottom:11px"></div>
        <button class="btn btn-primary btn-full" onclick="openPayment()" id="profilePayBtn" style="display:none">💳 Pay ₹1,999 to Unlock Earning</button>
      </div>
      <button class="btn btn-red btn-full" onclick="doLogout()" style="margin-top:4px">Sign Out</button>
    </div>
  </div>
</div>

<div class="bnav" id="bnav" style="display:none">
  <button class="bn-item on" onclick="goPage('home')" id="bn-home"><span class="bn-ico">🏠</span><span class="bn-lbl">Home</span></button>
  <button class="bn-item" onclick="goPage('earn')" id="bn-earn"><span class="bn-ico">🏃</span><span class="bn-lbl">Earn</span></button>
  <button class="bn-item" onclick="goPage('wallet')" id="bn-wallet"><span class="bn-ico">💳</span><span class="bn-lbl">Wallet</span></button>
  <button class="bn-item" onclick="goPage('profile')" id="bn-profile"><span class="bn-ico">👤</span><span class="bn-lbl">Profile</span></button>
</div>

<!-- QR SCANNER OVERLAY -->
<div id="qrOverlay">
  <h3 style="color:#fff;font-size:1rem;margin-bottom:12px">📷 Scan UPI QR Code</h3>
  <div class="qr-frame"><video id="qrVideo" autoplay playsinline muted></video></div>
  <div id="qrResult">Point camera at a UPI QR code...</div>
  <div style="display:flex;gap:10px;width:100%;max-width:320px">
    <button onclick="stopQR()" style="flex:1;padding:12px;background:var(--red);color:#fff;border:none;border-radius:10px;cursor:pointer;font-weight:700">❌ Close</button>
    <button onclick="useQRResult()" id="btnUseQR" style="flex:1;padding:12px;background:linear-gradient(135deg,#0d6e3a,#1ab358);color:#fff;border:none;border-radius:10px;cursor:pointer;font-weight:700;display:none">✅ Use This</button>
  </div>
</div>

<!-- UPI PAYMENT SHEET -->
<div class="upi-sheet" id="upiSheet" onclick="closePaymentBg(event)">
  <div class="upi-content">
    <div class="upi-handle"></div>
    <h3 style="font-family:'Playfair Display',serif;font-size:1.25rem;font-weight:700;margin-bottom:15px">💳 Unlock Walking Income</h3>
    <div class="upi-amount">
      <div style="font-size:.64rem;color:rgba(255,255,255,.4);letter-spacing:2px;text-transform:uppercase">One-Time Payment</div>
      <div style="font-family:'Playfair Display',serif;font-size:2.1rem;font-weight:700;color:#fad369">₹1,999</div>
      <div style="font-size:.68rem;color:rgba(255,255,255,.35);margin-top:3px">✅ Referral link activates instantly after payment</div>
    </div>
    <div class="upi-step">
      <div class="upi-step-num">1</div>
      <div style="flex:1">
        <div style="font-size:.82rem;font-weight:700;color:var(--txt2);margin-bottom:5px">Pay ₹1,999 to UPI ID</div>
        <div class="upi-id-box" id="upiIdDisplay">bonagirispinoj-1@oksbi</div>
        <div style="display:flex;gap:7px;flex-wrap:wrap;margin-top:6px">
          <button class="btn btn-outline" style="font-size:.7rem;padding:5px 9px" onclick="copyUPI()">📋 Copy UPI</button>
          <button class="btn btn-outline" style="font-size:.7rem;padding:5px 9px;background:rgba(240,180,41,.1);border-color:var(--gold)" onclick="startQR()">📷 Scan QR</button>
        </div>
      </div>
    </div>
    <div class="upi-step"><div class="upi-step-num">2</div><div style="font-size:.82rem;color:var(--txt3)">Pay via your UPI app:</div></div>
    <button class="upi-app-btn upi-gpay" onclick="openUPI('gpay')">🔵 Google Pay</button>
    <button class="upi-app-btn upi-phone" onclick="openUPI('phonepe')">💜 PhonePe</button>
    <button class="upi-app-btn upi-bhim" onclick="openUPI('bhim')">🔷 BHIM UPI</button>
    <button class="upi-app-btn upi-other" onclick="openUPI('other')">📲 Any UPI App</button>
    <div class="upi-step" style="margin-top:11px">
      <div class="upi-step-num">3</div>
      <div style="width:100%">
        <div style="font-size:.82rem;font-weight:700;color:var(--txt2);margin-bottom:3px">Enter UTR / Transaction Number</div>
        <div style="font-size:.7rem;color:var(--txt4);margin-bottom:7px">Find the 12-digit UTR in your UPI app payment history after paying.</div>
        <input class="upi-inp" id="txnId" placeholder="e.g. 426819234567" maxlength="30"/>
        <div id="txnErr" style="color:var(--red);font-size:.72rem;margin-top:3px;display:none"></div>
      </div>
    </div>
    <div style="background:var(--amber2);border:1px solid rgba(184,106,0,.3);border-radius:10px;padding:11px;margin:11px 0;font-size:.76rem;color:var(--amber)">
      <strong>📲 After submitting:</strong> Your payment details will be sent to admin WhatsApp for verification. Admin will approve within a few hours and GPS Earn will be unlocked.
    </div>
    <button class="btn btn-primary btn-full" style="margin-top:7px" id="submitPayBtn" onclick="submitPayment()">✅ Submit Payment & Notify Admin</button>
    <button class="btn btn-outline btn-full" style="margin-top:7px" onclick="closePayment()">Cancel</button>
  </div>
</div>

<div class="modal-bg" id="successModal">
  <div class="modal-box">
    <div class="modal-ico" id="modalIco">✅</div>
    <h3 style="font-size:1.2rem;margin-bottom:7px" id="modalTitle">Done!</h3>
    <p style="font-size:.82rem;color:var(--txt3);line-height:1.6;margin-bottom:18px;white-space:pre-wrap" id="modalMsg"></p>
    <button class="btn btn-primary btn-full" onclick="closeModal()">Continue</button>
  </div>
</div>
<div id="toast"></div>

<!-- ADMIN PANEL -->
<div id="adminApp" style="display:none">
  <div class="admin-hd">
    <h1>🌿 Health is <span>Wealth</span> — Admin</h1>
    <div style="display:flex;gap:7px;align-items:center">
      <span style="background:rgba(240,180,41,.2);border:1px solid rgba(240,180,41,.3);color:#fad369;padding:3px 9px;border-radius:11px;font-size:.68rem;font-weight:700" id="adminBadge">Admin</span>
      <button onclick="adminLogout()" style="background:none;border:1px solid rgba(255,255,255,.2);color:rgba(255,255,255,.6);padding:4px 9px;border-radius:6px;cursor:pointer;font-size:.7rem">Sign Out</button>
    </div>
  </div>
  <div id="adminLoginBox" style="min-height:85vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(160deg,#040e08,#071c10,#0a3018);padding:18px">
    <div style="background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.14);border-radius:22px;padding:30px 24px;width:100%;max-width:360px;backdrop-filter:blur(20px)">
      <div style="text-align:center;margin-bottom:22px"><div style="font-size:2.8rem;margin-bottom:8px">🌿</div><h2 style="font-family:'Playfair Display',serif;font-size:1.4rem;font-weight:700;color:#fff;margin-bottom:3px">Admin Panel</h2><p style="font-size:.68rem;color:rgba(255,255,255,.3);letter-spacing:2px;text-transform:uppercase">Health is Wealth Management</p></div>
      <input style="width:100%;padding:12px 13px;border:1px solid rgba(255,255,255,.15);border-radius:10px;font-size:.88rem;margin-bottom:9px;outline:none;background:rgba(255,255,255,.08);color:#fff" type="email" id="adminEmail" placeholder="Admin Email"/>
      <div style="position:relative;margin-bottom:13px"><input style="width:100%;padding:12px 42px 12px 13px;border:1px solid rgba(255,255,255,.15);border-radius:10px;font-size:.88rem;outline:none;background:rgba(255,255,255,.08);color:#fff" type="password" id="adminPass" placeholder="Admin Password"/><button type="button" onclick="togglePw('adminPass',this)" style="position:absolute;right:12px;top:50%;transform:translateY(-50%);background:none;border:none;color:rgba(255,255,255,.4);cursor:pointer;font-size:.95rem">👁</button></div>
      <button onclick="adminLogin()" id="adminLoginBtn" style="width:100%;padding:13px;border:none;border-radius:10px;background:linear-gradient(135deg,#8a6210,#f0b429,#fad369);color:#071c10;font-weight:800;font-size:.9rem;cursor:pointer">Sign In to Admin</button>
      <div style="color:#ff9090;font-size:.72rem;text-align:center;margin-top:7px;min-height:16px" id="adminErr"></div>
      <div style="margin-top:14px;text-align:center"><button onclick="showAuth()" style="background:none;border:none;color:rgba(255,255,255,.28);font-size:.74rem;cursor:pointer">← Back to App</button></div>
    </div>
  </div>
  <div id="adminDash" style="display:none">
    <div class="admin-tabs">
      <button class="admin-tab on" onclick="adminTab(this,'aDash')">📊 Dashboard</button>
      <button class="admin-tab" onclick="adminTab(this,'aUsers')">👥 Users</button>
      <button class="admin-tab" onclick="adminTab(this,'aPay')">💳 Payments</button>
      <button class="admin-tab" onclick="adminTab(this,'aWD')">💸 Withdrawals</button>
      <button class="admin-tab" onclick="adminTab(this,'aLeaderboard')">🏆 Leaderboard</button>
      <button class="admin-tab" onclick="adminTab(this,'aSettings')">⚙️ Settings</button>
    </div>
    <div class="admin-content">
      <div id="aDash">
        <div class="admin-stats">
          <div class="admin-stat"><div class="admin-stat-v" id="sTotalUsers">—</div><div class="admin-stat-l">Total Users</div></div>
          <div class="admin-stat"><div class="admin-stat-v" id="sPaidUsers">—</div><div class="admin-stat-l">Active Users</div></div>
          <div class="admin-stat"><div class="admin-stat-v" id="sPendingPay">—</div><div class="admin-stat-l">Pending Pay</div></div>
          <div class="admin-stat"><div class="admin-stat-v" id="sPendingWD">—</div><div class="admin-stat-l">Pending WD</div></div>
          <div class="admin-stat"><div class="admin-stat-v" id="sTotalKm">—</div><div class="admin-stat-l">Total KM</div></div>
          <div class="admin-stat"><div class="admin-stat-v" id="sTotalBal">—</div><div class="admin-stat-l">₹ Owed</div></div>
        </div>
        <div class="admin-section">
          <div class="admin-section-hd"><h3>🔗 Admin Free Referral Link</h3><button class="refresh-btn" onclick="loadAdminStats()">🔄 Refresh</button></div>
          <div style="padding:14px">
            <div class="admin-free-ref"><h4>Admin Free-Access Code</h4><div class="admin-ref-code" id="adminRefCodeDisplay">—</div><div style="font-size:.7rem;color:rgba(255,255,255,.5);margin-top:3px;word-break:break-all" id="adminRefUrlDisplay"></div><div style="display:flex;gap:7px;margin-top:11px;flex-wrap:wrap"><button class="btn-a" onclick="copyAdminRef()">📋 Copy Link</button><button style="background:#25d366;color:#fff;border:none;padding:5px 11px;border-radius:7px;cursor:pointer;font-size:.72rem;font-weight:700" onclick="shareAdminRefWA()">💬 WhatsApp</button><button class="btn-r" onclick="generateNewAdminRef()">🔄 New Code</button></div></div>
            <div style="background:#fff0cc;border:1px solid #f0b429;border-radius:9px;padding:11px;font-size:.76rem;color:#8a6210">People joining via admin code get FREE access without paying ₹1,999.</div>
          </div>
        </div>
        <div class="admin-section">
          <div class="admin-section-hd"><h3>🔥 Deploy These Firestore Rules</h3></div>
          <div style="padding:13px">
            <div style="font-size:.76rem;color:#c82020;font-weight:700;margin-bottom:8px">⚠️ IMPORTANT: Deploy these rules to fix "missing permissions" error!</div>
            <div style="font-size:.74rem;color:#2a6040;margin-bottom:8px">Firebase Console → Firestore Database → Rules → Replace all → Publish</div>
            <pre style="background:#071c10;color:#4ade80;border-radius:9px;padding:12px;font-size:.66rem;overflow-x:auto;white-space:pre;line-height:1.6">rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    function isAdmin() {
      return request.auth != null &&
        request.auth.token.email == 'bonagirispinoj@gmail.com';
    }
    match /users/{uid} {
      allow read, write: if request.auth != null &&
        (request.auth.uid == uid || isAdmin());
    }
    match /payments/{id} {
      allow read: if request.auth != null;
      allow create: if request.auth != null;
      allow update, delete: if isAdmin();
    }
    match /withdrawals/{id} {
      allow read: if request.auth != null;
      allow create: if request.auth != null;
      allow update: if request.auth != null &&
        (isAdmin() || (resource.data.uid == request.auth.uid &&
         resource.data.status == 'pending' &&
         request.resource.data.status == 'cancelled'));
      allow delete: if isAdmin();
    }
    match /referrals/{id} { allow read, write: if request.auth != null; }
    match /km_logs/{id} { allow read, write: if request.auth != null; }
    match /free_referrals/{id} { allow read, write: if request.auth != null; }
    match /app_settings/{id} {
      allow read: if request.auth != null;
      allow write: if isAdmin();
    }
  }
}</pre>
            <button onclick="copyFirestoreRules()" class="btn-a" style="margin-top:10px;width:100%;padding:10px">📋 Copy Rules to Clipboard</button>
          </div>
        </div>
      </div>

      <div id="aUsers" style="display:none">
        <div class="admin-section">
          <div class="admin-section-hd"><h3>👥 All Users</h3><button class="refresh-btn" onclick="loadAdminUsers()">🔄 Refresh</button></div>
          <div style="padding:13px;border-bottom:1px solid #daf0e4;background:#f8fff8">
            <div style="font-size:.76rem;font-weight:700;color:#071c10;margin-bottom:7px">⚡ Grant Free Access by Email</div>
            <div style="display:flex;gap:7px;flex-wrap:wrap"><input class="admin-inp" style="flex:1;min-width:180px;margin-bottom:0" type="email" id="grantEmail" placeholder="user@email.com"/><button class="btn-a" onclick="grantFreeAccess()">✅ Grant Free</button></div>
          </div>
          <div style="overflow-x:auto">
            <table class="tbl">
              <thead><tr><th>#</th><th>Name / Email</th><th>Ref Code</th><th>Balance</th><th>KM</th><th>Status</th><th>Refs</th><th>Joined</th><th>Actions</th></tr></thead>
              <tbody id="usersBody"><tr><td colspan="9" style="text-align:center;padding:22px;color:#5a9070">Click Refresh to load</td></tr></tbody>
            </table>
          </div>
        </div>
      </div>

      <div id="aPay" style="display:none">
        <div class="admin-section">
          <div class="admin-section-hd"><h3>💳 Payment Verifications</h3><button class="refresh-btn" onclick="loadAdminPay()">🔄 Refresh</button></div>
          <div style="padding:9px 14px;background:#e8f8ff;border-bottom:1px solid #90c8f0;font-size:.76rem;color:#1448b8">
            <strong>ℹ️ Approve</strong> = activates GPS Earn + credits referrer. <strong>Reject</strong> = marks rejected. Check UTR in your UPI app / bank statement before approving.
          </div>
          <div style="overflow-x:auto">
            <table class="tbl">
              <thead><tr><th>User</th><th>Email</th><th>Amount</th><th>UTR / Txn ID</th><th>Status</th><th>Date</th><th>Action</th></tr></thead>
              <tbody id="payBody"><tr><td colspan="7" style="text-align:center;padding:22px;color:#5a9070">Loading...</td></tr></tbody>
            </table>
          </div>
        </div>
      </div>

      <div id="aWD" style="display:none">
        <div class="admin-section">
          <div class="admin-section-hd"><h3>💸 Withdrawal Requests</h3><button class="refresh-btn" onclick="loadAdminWD()">🔄 Refresh</button></div>
          <div style="padding:9px 14px;background:#fffbe6;border-bottom:1px solid #f0d060;font-size:.76rem;color:#7a5800"><strong>Workflow:</strong> Transfer money manually → Click ✅ Approve. ❌ Reject = auto refund.</div>
          <div style="overflow-x:auto">
            <table class="tbl">
              <thead><tr><th>User</th><th>Amount</th><th>Payment Details</th><th>Status</th><th>Date</th><th>Action</th></tr></thead>
              <tbody id="wdBody"><tr><td colspan="6" style="text-align:center;padding:22px;color:#5a9070">Switch to this tab to load</td></tr></tbody>
            </table>
          </div>
        </div>
      </div>

      <div id="aLeaderboard" style="display:none">
        <div class="admin-section">
          <div class="admin-section-hd"><h3>🏆 Leaderboard</h3><button class="refresh-btn" onclick="loadLeaderboard()">🔄 Refresh</button></div>
          <div style="padding:13px"><div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:9px;margin-bottom:14px">
            <div style="background:linear-gradient(135deg,#FFD700,#FFA500);border-radius:13px;padding:14px;text-align:center"><div style="font-size:2rem">🥇</div><div style="font-weight:800;color:#fff;font-size:1rem;margin-top:3px">₹1 CRORE</div><div id="prize1Name" style="font-size:.74rem;color:rgba(255,255,255,.9);margin-top:3px;font-weight:700">—</div><div id="prize1refs" style="font-size:.66rem;color:rgba(255,255,255,.7)">—</div></div>
            <div style="background:linear-gradient(135deg,#C0C0C0,#A0A0A0);border-radius:13px;padding:14px;text-align:center"><div style="font-size:2rem">🥈</div><div style="font-weight:800;color:#fff;font-size:1rem;margin-top:3px">₹75 LAKHS</div><div id="prize2Name" style="font-size:.74rem;color:rgba(255,255,255,.9);margin-top:3px;font-weight:700">—</div><div id="prize2refs" style="font-size:.66rem;color:rgba(255,255,255,.7)">—</div></div>
            <div style="background:linear-gradient(135deg,#CD7F32,#A0520A);border-radius:13px;padding:14px;text-align:center"><div style="font-size:2rem">🥉</div><div style="font-weight:800;color:#fff;font-size:1rem;margin-top:3px">₹50 LAKHS</div><div id="prize3Name" style="font-size:.74rem;color:rgba(255,255,255,.9);margin-top:3px;font-weight:700">—</div><div id="prize3refs" style="font-size:.66rem;color:rgba(255,255,255,.7)">—</div></div>
          </div></div>
          <div style="overflow-x:auto"><table class="tbl"><thead><tr><th>Rank</th><th>Name</th><th>Email</th><th>Referrals</th><th>KM</th><th>Balance</th><th>Prize</th></tr></thead><tbody id="lbBody"><tr><td colspan="7" style="text-align:center;padding:22px;color:#5a9070">Click Refresh</td></tr></tbody></table></div>
        </div>
      </div>

      <div id="aSettings" style="display:none">
        <div class="admin-section">
          <div class="admin-section-hd"><h3>⚙️ App Settings</h3><button class="refresh-btn" onclick="loadSettings()">🔄 Load</button></div>
          <div style="padding:14px">
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:11px;margin-bottom:14px">
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">Entry Price (₹)</label><input class="admin-inp" type="number" id="setPrice" placeholder="1999"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">Referral Reward (₹)</label><input class="admin-inp" type="number" id="setRefReward" placeholder="300"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">KM Rate (₹/km)</label><input class="admin-inp" type="number" id="setKmRate" placeholder="1" step="0.1"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">KM Cap per Cycle</label><input class="admin-inp" type="number" id="setKmCap" placeholder="300"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">Min Withdrawal (₹)</label><input class="admin-inp" type="number" id="setMinWD" placeholder="50"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">1st Prize (₹)</label><input class="admin-inp" type="number" id="setPrize1" placeholder="10000000"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">2nd Prize (₹)</label><input class="admin-inp" type="number" id="setPrize2" placeholder="7500000"/></div>
              <div><label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">3rd Prize (₹)</label><input class="admin-inp" type="number" id="setPrize3" placeholder="5000000"/></div>
            </div>
            <label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">UPI ID</label>
            <input class="admin-inp" type="text" id="setUpiId" placeholder="bonagirispinoj-1@oksbi"/>
            <label style="font-size:.74rem;font-weight:700;color:#2a6040;display:block;margin-bottom:3px">Announcement</label>
            <textarea class="admin-inp" id="setAnnouncement" rows="2" placeholder="Optional message for users..." style="resize:vertical"></textarea>
            <button class="btn-a" style="width:100%;padding:12px;font-size:.86rem;border-radius:9px" onclick="saveSettings()">💾 Save Settings</button>
          </div>
        </div>
        <div class="admin-section">
          <div class="admin-section-hd"><h3>📢 Broadcast to WhatsApp</h3></div>
          <div style="padding:14px"><textarea class="admin-inp" id="broadcastMsg" rows="3" placeholder="Type message..." style="resize:vertical"></textarea><button class="btn-a" onclick="sendBroadcast()">💬 Send to WhatsApp</button></div>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
// ═══════════════════════════════════════════
// HEALTH IS WEALTH v4 — Fixed Permissions
// Admin: bonagirispinoj@gmail.com | WA: 9110563921
// ═══════════════════════════════════════════
const FB={apiKey:"AIzaSyBIebPXVjzVBZl380ZCELg2LUSCLr-6QrE",authDomain:"neurocoin-ntc.firebaseapp.com",projectId:"neurocoin-ntc",storageBucket:"neurocoin-ntc.firebasestorage.app",messagingSenderId:"1040732555800",appId:"1:1040732555800:web:55e63b5ff81781c6b1916d"};
const ADMIN_EMAIL="bonagirispinoj@gmail.com",ADMIN_WA="919110563921";
let UPI_ID="bonagirispinoj-1@oksbi",BOOK_PRICE=1999,REF_REWARD=300,KM_RATE=1,KM_CAP=300,MIN_WD=50,PRIZE_1=10000000,PRIZE_2=7500000,PRIZE_3=5000000;
let db,auth,currentUser=null;
try{if(!firebase.apps.length)firebase.initializeApp(FB);auth=firebase.auth();db=firebase.firestore();db.enablePersistence({synchronizeTabs:true}).catch(()=>{});}catch(e){console.error("FB:",e);}
let S={wallet:0,totalKm:0,todayKm:0,kmLimit:300,referralCount:0,bookPurchased:false,bookStatus:"none",refCode:"",pendingWDId:null};
const AUTH_MAX=5,AUTH_LOCK=900000;let aa;
try{aa=JSON.parse(sessionStorage.getItem("__aa")||'{"c":0,"t":0}');}catch(e){aa={c:0,t:0};}
function checkRL(){if(aa.c>=AUTH_MAX){const e=Date.now()-aa.t;if(e<AUTH_LOCK)return`Too many attempts. Wait ${Math.ceil((AUTH_LOCK-e)/60000)} min.`;aa={c:0,t:0};}return null;}
function recAtt(ok){if(ok){aa={c:0,t:0};}else{aa.c++;aa.t=Date.now();}try{sessionStorage.setItem("__aa",JSON.stringify(aa));}catch(e){}}
function esc(s){if(typeof s!=="string")return"";return s.replace(/[<>&'"]/g,c=>({"<":"&lt;",">":"&gt;","&":"&amp;","'":"&#39;",'"':'&quot;'}[c]));}
function san(s){if(typeof s!=="string")return"";return s.replace(/[<>'"&]/g,"").trim().slice(0,300);}
function isEmail(e){return/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(e);}
function genRef(n,uid){return n.replace(/[^a-zA-Z]/g,"").toUpperCase().slice(0,4).padEnd(4,"X")+uid.slice(-4).toUpperCase();}
function fmtL(n){if(n>=10000000)return"₹"+(n/10000000).toFixed(0)+" Cr";if(n>=100000)return"₹"+(n/100000).toFixed(0)+" L";return"₹"+n.toLocaleString("en-IN");}
let toastT=null;
function showToast(msg,dur){dur=dur||2800;const t=document.getElementById("toast");if(!t)return;t.textContent=msg;t.classList.add("on");if(toastT)clearTimeout(toastT);toastT=setTimeout(()=>t.classList.remove("on"),dur);}
function authErr(c){return{"auth/user-not-found":"No account with this email.","auth/wrong-password":"Incorrect password.","auth/invalid-credential":"Invalid email or password.","auth/email-already-in-use":"Email already registered.","auth/weak-password":"Password must be 8+ characters.","auth/invalid-email":"Enter a valid email.","auth/too-many-requests":"Too many attempts. Wait a while.","auth/network-request-failed":"No internet connection."}[c]||"Something went wrong. Try again.";}

// ── SCREENS ──────────────────────────────────
function showAuth(){document.getElementById("authScreen").style.display="flex";document.getElementById("userApp").style.display="none";document.getElementById("bnav").style.display="none";document.getElementById("adminApp").style.display="none";}
function showUserApp(){document.getElementById("authScreen").style.display="none";document.getElementById("userApp").style.display="block";document.getElementById("bnav").style.display="flex";document.getElementById("adminApp").style.display="none";}
function showAdminPanel(){document.getElementById("authScreen").style.display="none";document.getElementById("userApp").style.display="none";document.getElementById("bnav").style.display="none";document.getElementById("adminApp").style.display="block";document.getElementById("adminLoginBox").style.display="flex";document.getElementById("adminDash").style.display="none";}
function goAdmin(){window.location.hash="#admin";showAdminPanel();}
function togglePw(id,btn){const el=document.getElementById(id);if(!el)return;const s=el.type==="password";el.type=s?"text":"password";if(btn)btn.textContent=s?"🙈":"👁";}
function toggleTheme(){const t=document.documentElement.getAttribute("data-theme")==="dark"?"light":"dark";document.documentElement.setAttribute("data-theme",t);document.querySelector(".tb-btn").textContent=t==="dark"?"☀️":"🌙";try{localStorage.setItem("__theme",t);}catch(e){}}
function goPage(p){document.querySelectorAll(".pg").forEach(x=>x.classList.remove("on"));document.querySelectorAll(".bn-item").forEach(x=>x.classList.remove("on"));const pg=document.getElementById("pg"+p.charAt(0).toUpperCase()+p.slice(1)),bn=document.getElementById("bn-"+p);if(pg)pg.classList.add("on");if(bn)bn.classList.add("on");window.scrollTo({top:0,behavior:"smooth"});if(p==="wallet"){loadTxns();checkPendingWD();}if(p==="earn")loadReferrals();}
function switchTab(t){["login","signup"].forEach(x=>{document.getElementById("tab"+x.charAt(0).toUpperCase()+x.slice(1)).classList.toggle("on",x===t);document.getElementById("form"+x.charAt(0).toUpperCase()+x.slice(1)).style.display=x===t?"block":"none";});["loginErr","signupErr","signupOk"].forEach(id=>{const el=document.getElementById(id);if(el)el.textContent="";});}

// ── APP SETTINGS ─────────────────────────────
async function loadAppSettings(){try{const doc=await db.collection("app_settings").doc("config").get();if(doc.exists){const d=doc.data();if(d.bookPrice)BOOK_PRICE=d.bookPrice;if(d.refReward)REF_REWARD=d.refReward;if(d.kmRate)KM_RATE=d.kmRate;if(d.kmCap)KM_CAP=d.kmCap;if(d.minWD)MIN_WD=d.minWD;if(d.upiId){UPI_ID=d.upiId;const el=document.getElementById("upiIdDisplay");if(el)el.textContent=d.upiId;}if(d.prize1)PRIZE_1=d.prize1;if(d.prize2)PRIZE_2=d.prize2;if(d.prize3)PRIZE_3=d.prize3;}}catch(e){}}

// ── AUTH ──────────────────────────────────────
async function doLogin(){
  const btn=document.getElementById("btnLogin"),errEl=document.getElementById("loginErr");errEl.textContent="";errEl.style.color="#ff9090";
  const rl=checkRL();if(rl){errEl.textContent=rl;return;}
  const email=document.getElementById("loginEmail").value.trim().toLowerCase(),pass=document.getElementById("loginPass").value;
  if(!isEmail(email)){errEl.textContent="Enter a valid email.";return;}if(!pass){errEl.textContent="Password is required.";return;}
  btn.disabled=true;btn.textContent="Signing in...";
  try{await auth.signInWithEmailAndPassword(email,pass);recAtt(true);}
  catch(e){recAtt(false);errEl.textContent=authErr(e.code);}
  finally{btn.disabled=false;btn.textContent="Sign In →";}
}
async function doSignup(){
  const btn=document.getElementById("btnSignup"),errEl=document.getElementById("signupErr"),okEl=document.getElementById("signupOk");errEl.textContent="";okEl.textContent="";
  const name=san(document.getElementById("signupName").value).trim(),email=document.getElementById("signupEmail").value.trim().toLowerCase(),pass=document.getElementById("signupPass").value,ref=san(document.getElementById("signupRef").value).toUpperCase().trim();
  if(!name||name.length<2){errEl.textContent="Enter your full name.";return;}if(!isEmail(email)){errEl.textContent="Enter a valid email.";return;}if(!pass||pass.length<8){errEl.textContent="Password must be 8+ characters.";return;}
  let isFreeRef=false;if(ref){try{const fs=await db.collection("free_referrals").where("code","==",ref).where("active","==",true).limit(1).get();if(!fs.empty)isFreeRef=true;}catch(e){}}
  btn.disabled=true;btn.textContent="Creating account...";
  try{const cred=await auth.createUserWithEmailAndPassword(email,pass);await cred.user.updateProfile({displayName:name});const myRef=genRef(name,cred.user.uid);
    await db.collection("users").doc(cred.user.uid).set({name,email,refCode:myRef,referredBy:ref||null,joinedAt:firebase.firestore.FieldValue.serverTimestamp(),wallet:0,balance:0,bookPurchased:isFreeRef,bookStatus:isFreeRef?"approved":"none",totalKm:0,todayKm:0,kmLimit:KM_CAP,referralCount:0,isAdminGranted:isFreeRef});
    if(ref&&!isFreeRef)await creditRef(ref,cred.user.uid);okEl.textContent=isFreeRef?"✅ Account created with FREE access!":"✅ Account created! Welcome!";recAtt(true);
  }catch(e){recAtt(false);errEl.textContent=authErr(e.code);}
  finally{btn.disabled=false;btn.textContent="Create Account →";}
}
async function creditRef(refCode,newUid){try{const s=await db.collection("users").where("refCode","==",refCode).limit(1).get();if(s.empty)return;const rd=s.docs[0];if(rd.id===newUid||!rd.data().bookPurchased)return;await db.collection("referrals").add({referrerId:rd.id,referredId:newUid,status:"pending",amount:0,createdAt:firebase.firestore.FieldValue.serverTimestamp()});}catch(e){}}
async function forgotPw(){const email=document.getElementById("loginEmail").value.trim();if(!isEmail(email)){document.getElementById("loginErr").textContent="Enter your email first.";return;}try{await auth.sendPasswordResetEmail(email);const el=document.getElementById("loginErr");el.style.color="#6ee7b7";el.textContent="✅ Reset link sent!";}catch(e){document.getElementById("loginErr").textContent=authErr(e.code);}}
async function doLogout(){if(!confirm("Sign out?"))return;if(gpsRunning)await stopGPS();await auth.signOut();currentUser=null;S={wallet:0,totalKm:0,todayKm:0,kmLimit:300,referralCount:0,bookPurchased:false,bookStatus:"none",refCode:"",pendingWDId:null};}

// ── LOAD USER ─────────────────────────────────
async function loadUser(user){
  showUserApp();currentUser=user;await loadAppSettings();
  try{const doc=await db.collection("users").doc(user.uid).get();
    if(doc.exists){const d=doc.data();S.wallet=d.wallet||d.balance||0;S.refCode=d.refCode||genRef(user.displayName||"USER",user.uid);S.bookPurchased=d.bookPurchased||false;S.bookStatus=d.bookStatus||"none";S.totalKm=d.totalKm||0;S.todayKm=d.todayKm||0;S.kmLimit=d.kmLimit||KM_CAP;S.referralCount=d.referralCount||0;}
    else{const mr=genRef(user.displayName||"USER",user.uid);await db.collection("users").doc(user.uid).set({name:user.displayName||"User",email:user.email||"",refCode:mr,referredBy:null,joinedAt:firebase.firestore.FieldValue.serverTimestamp(),wallet:0,balance:0,bookPurchased:false,bookStatus:"none",totalKm:0,todayKm:0,kmLimit:KM_CAP,referralCount:0});S.refCode=mr;}
  }catch(e){console.error("loadUser:",e);}
  db.collection("users").doc(user.uid).onSnapshot(snap=>{if(!snap||!snap.exists)return;const d=snap.data();S.wallet=d.wallet||d.balance||0;S.totalKm=d.totalKm||0;S.todayKm=d.todayKm||0;S.kmLimit=d.kmLimit||KM_CAP;S.bookPurchased=d.bookPurchased||false;S.bookStatus=d.bookStatus||"none";S.referralCount=d.referralCount||0;renderUI(user);});
  renderUI(user);
}
function renderUI(user){
  const name=san(user.displayName||"Friend");
  document.getElementById("heroName").innerHTML=`Welcome, <span>${name}</span> 👋`;
  document.getElementById("hKm").textContent=S.todayKm.toFixed(2);document.getElementById("hEarned").textContent="₹"+S.wallet.toFixed(0);document.getElementById("hRefs").textContent=S.referralCount;
  document.getElementById("statKm").textContent=S.todayKm.toFixed(2);document.getElementById("statKmSub").textContent=`Cap: ${S.kmLimit} KM`;document.getElementById("pbKm").style.width=Math.min(100,(S.totalKm/Math.max(1,S.kmLimit))*100)+"%";
  document.getElementById("statWallet").textContent="₹"+S.wallet.toFixed(0);document.getElementById("pbWallet").style.width=Math.min(100,(S.wallet/Math.max(1,REF_REWARD))*100)+"%";
  document.getElementById("statRefs").textContent=S.referralCount;document.getElementById("statTotalEarn").textContent="₹"+S.wallet.toFixed(0);
  document.getElementById("walletAmt").textContent=S.wallet.toFixed(0);document.getElementById("tbWallet").textContent="₹"+S.wallet.toFixed(0);
  document.getElementById("walletSub").textContent=S.bookPurchased?`${S.totalKm.toFixed(1)} km · ${S.referralCount} referrals`:`Pay ₹${BOOK_PRICE} to start earning`;
  document.getElementById("profileName").textContent=name;document.getElementById("profileEmail").textContent=san(user.email||"");document.getElementById("profRefCode").textContent=S.refCode;
  document.getElementById("profTotalKm").textContent=S.totalKm.toFixed(1)+" km";document.getElementById("profRefs").textContent=S.referralCount;document.getElementById("profCapLeft").textContent=Math.max(0,S.kmLimit-S.totalKm).toFixed(1)+" km";
  document.getElementById("profileBadge").innerHTML=S.bookPurchased?'<span class="profile-badge badge-paid">✅ GPS Earn Active</span>':`<span class="profile-badge badge-free">🔒 Pay ₹${BOOK_PRICE} to Unlock</span>`;
  const pb=document.getElementById("profilePayBtn");if(pb)pb.style.display=S.bookPurchased?"none":"flex";
  const rc=document.getElementById("refCode"),ru=document.getElementById("refUrl");if(rc)rc.textContent=S.refCode;if(ru)ru.textContent=location.origin+location.pathname+"?ref="+S.refCode;
  document.getElementById("gpsPaidContent").style.display=S.bookPurchased?"block":"none";document.getElementById("gpsLockedContent").style.display=S.bookPurchased?"none":"block";
  document.getElementById("refPaidContent").style.display=S.bookPurchased?"block":"none";document.getElementById("refLockedContent").style.display=S.bookPurchased?"none":"block";
  updateCycleUI();updatePayStatus();
}
function updatePayStatus(){
  const el=document.getElementById("payStatus"),pEl=document.getElementById("profilePayStatus"),hEl=document.getElementById("homePayStatus");let html="";
  if(S.bookPurchased){html=`<div style="background:var(--green2);border:1.5px solid rgba(13,158,74,.25);border-radius:10px;padding:11px;text-align:center;margin-bottom:11px"><div style="font-size:1.1rem;margin-bottom:3px">✅</div><div style="font-weight:700;color:var(--green);font-size:.86rem">GPS Earn Activated!</div><div style="font-size:.72rem;color:var(--txt3);margin-top:2px">Walk ₹${KM_RATE}/KM + ₹${REF_REWARD}/referral</div></div>`;}
  else if(S.bookStatus==="pending"){html=`<div style="background:var(--amber2);border:1.5px solid rgba(184,106,0,.2);border-radius:10px;padding:11px;text-align:center;margin-bottom:11px"><div style="font-size:1.1rem;margin-bottom:3px">⏳</div><div style="font-weight:700;color:var(--amber);font-size:.86rem">Payment Under Review</div><div style="font-size:.72rem;color:var(--txt3);margin-top:2px">Referral link is active! GPS Earn activates after admin verifies.</div></div>`;}
  if(el)el.innerHTML=html;if(pEl)pEl.innerHTML=html;if(hEl)hEl.innerHTML=html;
}
function updateCycleUI(){const w=S.totalKm||0,cap=S.kmLimit||KM_CAP,rem=Math.max(0,cap-w),pct=Math.min(100,(w/Math.max(1,cap))*100);const cw=document.getElementById("cycleWalked"),cr=document.getElementById("cycleRemain"),ce=document.getElementById("cycleEarned"),cp=document.getElementById("cycleProg"),cl=document.getElementById("cycleCapLbl"),gpt=document.getElementById("gpsCapTxt");if(cw)cw.textContent=w.toFixed(1);if(cr)cr.textContent=rem.toFixed(1);if(ce)ce.textContent="₹"+Math.floor(w*KM_RATE);if(cp)cp.style.width=pct+"%";if(cl)cl.textContent=`Cap: ${cap} KM — refer to reset!`;if(gpt)gpt.textContent=`Cap: ${cap} KM · Walked: ${w.toFixed(1)} KM`;}

// ── GPS ───────────────────────────────────────
let gpsWId=null,gpsLP=null,gpsSKm=0,gpsPKm=0,gpsRunning=false,gpsPaused=false;
function haversineKm(la1,lo1,la2,lo2){const R=6371,dLa=(la2-la1)*Math.PI/180,dLo=(lo2-lo1)*Math.PI/180,a=Math.sin(dLa/2)**2+Math.cos(la1*Math.PI/180)*Math.cos(la2*Math.PI/180)*Math.sin(dLo/2)**2;return R*2*Math.atan2(Math.sqrt(a),Math.sqrt(1-a));}
function startGPS(){if(!S.bookPurchased){showToast("⚠ Pay ₹"+BOOK_PRICE+" first to unlock GPS Earn");return;}if(!navigator.geolocation){showToast("⚠ GPS not supported");return;}if((S.kmLimit-S.totalKm)<=0){showToast("⚠ KM cap reached! Refer friends to reset.");return;}gpsRunning=true;gpsPaused=false;gpsSKm=0;gpsPKm=0;gpsLP=null;setGPSUI("tracking");showToast("📍 GPS started! Earn ₹"+KM_RATE+"/KM",3000);gpsWId=navigator.geolocation.watchPosition(pos=>{if(!gpsRunning||gpsPaused)return;const{latitude:lat,longitude:lon,speed,accuracy}=pos.coords;if(accuracy>30)return;const spd=speed!=null?speed*3.6:0;const se=document.getElementById("gpsSpeed");if(se)se.textContent=spd.toFixed(1);if(speed!==null&&(speed<0.14||speed>2.2)){gpsLP=null;return;}if(gpsLP){const d=haversineKm(gpsLP.lat,gpsLP.lon,lat,lon);if(d>0.003&&d<0.2){gpsSKm+=d;gpsPKm+=d;updateGPSDisplay();if(gpsPKm>=0.1){saveGPSChunk(gpsPKm);gpsPKm=0;}}}gpsLP={lat,lon};},err=>{if(err.code===1)showToast("⚠ Location denied.");else showToast("⚠ GPS error. Try again.");stopGPS();},{enableHighAccuracy:true,maximumAge:3000,timeout:15000});}
function pauseGPS(){gpsPaused=!gpsPaused;const b=document.getElementById("gpsBtnPause"),d=document.getElementById("gpsDot"),t=document.getElementById("gpsStatusTxt");if(b)b.textContent=gpsPaused?"▶ Resume":"⏸ Pause";if(d)d.className="gps-dot "+(gpsPaused?"paused":"live");if(t)t.textContent=gpsPaused?"Walk paused":"Tracking your walk...";}
async function stopGPS(){if(gpsWId!==null){navigator.geolocation.clearWatch(gpsWId);gpsWId=null;}gpsRunning=false;gpsPaused=false;if(gpsPKm>0.01){await saveGPSChunk(gpsPKm);gpsPKm=0;}setGPSUI("idle");showToast(`✅ ${gpsSKm.toFixed(2)} KM · ₹${(gpsSKm*KM_RATE).toFixed(0)} earned`);gpsSKm=0;gpsLP=null;}
function setGPSUI(m){const d=document.getElementById("gpsDot"),t=document.getElementById("gpsStatusTxt"),s=document.getElementById("gpsBtnStart"),p=document.getElementById("gpsBtnPause"),x=document.getElementById("gpsBtnStop");if(m==="tracking"){if(d)d.className="gps-dot live";if(t)t.textContent="Tracking your walk...";if(s)s.style.display="none";if(p)p.style.display="flex";if(x)x.style.display="flex";}else{if(d)d.className="gps-dot off";if(t)t.textContent="Tap Start to begin tracking";if(s)s.style.display="flex";if(p)p.style.display="none";if(x)x.style.display="none";}}
function updateGPSDisplay(){const tot=S.todayKm+gpsSKm;const ke=document.getElementById("gpsKm"),ee=document.getElementById("gpsEarned"),pe=document.getElementById("gpsProgFill");if(ke)ke.textContent=tot.toFixed(2);if(ee)ee.textContent="₹"+(gpsSKm*KM_RATE).toFixed(2);if(pe)pe.style.width=Math.min(100,((S.totalKm+gpsSKm)/Math.max(1,S.kmLimit))*100)+"%";}
async function saveGPSChunk(km){if(!currentUser||km<0.001)return;const ref=db.collection("users").doc(currentUser.uid);try{const doc=await ref.get();if(!doc||!doc.exists)return;const d=doc.data(),rem=(d.kmLimit||KM_CAP)-(d.totalKm||0);if(rem<=0){stopGPS();showToast("⚠ KM cap reached!");return;}const al=Math.min(km,rem),earn=parseFloat((al*KM_RATE).toFixed(2));await ref.update({totalKm:firebase.firestore.FieldValue.increment(al),todayKm:firebase.firestore.FieldValue.increment(al),wallet:firebase.firestore.FieldValue.increment(earn),balance:firebase.firestore.FieldValue.increment(earn)});await db.collection("km_logs").add({uid:currentUser.uid,km:al,earned:earn,date:new Date().toISOString().slice(0,10),ts:firebase.firestore.FieldValue.serverTimestamp()});}catch(e){console.error("saveGPS:",e);}}

// ── QR SCANNER ────────────────────────────────
let qrStream=null,qrInterval=null,qrDetected="";
async function startQR(){
  const overlay=document.getElementById("qrOverlay");overlay.classList.add("on");
  const video=document.getElementById("qrVideo");qrDetected="";document.getElementById("qrResult").textContent="Point camera at UPI QR code...";document.getElementById("btnUseQR").style.display="none";
  try{qrStream=await navigator.mediaDevices.getUserMedia({video:{facingMode:"environment"}});video.srcObject=qrStream;
    // Use BarcodeDetector if available
    if("BarcodeDetector" in window){const bd=new BarcodeDetector({formats:["qr_code"]});qrInterval=setInterval(async()=>{try{const barcodes=await bd.detect(video);if(barcodes.length>0){const raw=barcodes[0].rawValue;handleQRResult(raw);}}catch(e){}},500);}
    else{document.getElementById("qrResult").textContent="QR scanning not supported on this browser. Please enter UTR manually.";}
  }catch(e){document.getElementById("qrResult").textContent="Camera access denied. Enter UTR manually.";setTimeout(stopQR,2000);}
}
function handleQRResult(raw){
  // Extract UPI ID or amount from QR
  const upiMatch=raw.match(/pa=([^&]+)/);
  const amtMatch=raw.match(/am=([^&]+)/);
  let info=raw;
  if(upiMatch)info=`UPI: ${decodeURIComponent(upiMatch[1])}`;
  if(amtMatch)info+=` | Amount: ₹${amtMatch[1]}`;
  qrDetected=raw;document.getElementById("qrResult").textContent="✅ QR Scanned: "+info;
  document.getElementById("btnUseQR").style.display="block";
  if(qrInterval){clearInterval(qrInterval);qrInterval=null;}
}
function useQRResult(){
  // Pre-fill UPI ID from scanned QR
  const upiMatch=qrDetected.match(/pa=([^&]+)/);
  if(upiMatch){const upiVal=decodeURIComponent(upiMatch[1]);const txnEl=document.getElementById("txnId");if(txnEl)txnEl.placeholder="Enter UTR after paying to: "+upiVal;}
  stopQR();showToast("📷 QR scanned! Now pay and enter your UTR number.");
}
function stopQR(){if(qrInterval){clearInterval(qrInterval);qrInterval=null;}if(qrStream){qrStream.getTracks().forEach(t=>t.stop());qrStream=null;}document.getElementById("qrOverlay").classList.remove("on");}

// ── REFERRAL ──────────────────────────────────
function copyRef(){const url=location.origin+location.pathname+"?ref="+S.refCode;if(navigator.clipboard)navigator.clipboard.writeText(url).then(()=>showToast("📋 Referral link copied!"));else showToast("Code: "+S.refCode);}
function shareWA(){const url=location.origin+location.pathname+"?ref="+S.refCode;window.open("https://wa.me/?text="+encodeURIComponent("🌿 Join Health is Wealth! Walk & earn real money! I earned ₹"+S.wallet.toFixed(0)+"! Join: "+url));}
function shareTG(){const url=location.origin+location.pathname+"?ref="+S.refCode;window.open("https://t.me/share/url?url="+encodeURIComponent(url)+"&text="+encodeURIComponent("🌿 Join Health is Wealth — Walk & Earn!"));}
async function loadReferrals(){if(!currentUser)return;const list=document.getElementById("recruitList");if(!list)return;try{const s=await db.collection("referrals").where("referrerId","==",currentUser.uid).orderBy("createdAt","desc").limit(20).get();if(!s||s.empty){list.innerHTML='<div class="empty"><div class="empty-ico">👥</div><div class="empty-txt">No paid referrals yet.</div></div>';return;}list.innerHTML=s.docs.map(d=>{const r=d.data();return`<div class="recruit-item"><div class="recruit-av">${esc(r.referredName||"U").slice(0,1)}</div><div style="flex:1"><div style="font-weight:600;font-size:.84rem;color:var(--txt2)">${esc(r.referredName||"User")}</div><div style="font-size:.7rem;color:var(--txt4)">+₹${REF_REWARD} + ${KM_CAP}KM reset</div></div>${r.status==="paid"?`<span class="rb-paid">✅ ₹${REF_REWARD}</span>`:'<span class="rb-pending">⏳ Pending</span>'}</div>`;}).join("");}catch(e){}}

// ── PAYMENT ───────────────────────────────────
function openPayment(){document.getElementById("upiSheet").classList.add("on");}
function closePayment(){document.getElementById("upiSheet").classList.remove("on");const t=document.getElementById("txnId");if(t)t.value="";const e=document.getElementById("txnErr");if(e){e.textContent="";e.style.display="none";}}
function closePaymentBg(e){if(e.target===document.getElementById("upiSheet"))closePayment();}
function copyUPI(){if(navigator.clipboard)navigator.clipboard.writeText(UPI_ID).then(()=>showToast("📋 Copied: "+UPI_ID));else showToast("UPI: "+UPI_ID);}
function openUPI(app){const pa=UPI_ID,pn="Health+is+Wealth",am=BOOK_PRICE,tn="Unlock+GPS+Earn",u=`upi://pay?pa=${pa}&pn=${pn}&am=${am}&cu=INR&tn=${tn}`;const pkgs={gpay:"com.google.android.apps.nbu.paisa.user",phonepe:"com.phonepe.app",bhim:"in.org.npci.upiapp"};if(pkgs[app]){window.location.href=`intent://pay?pa=${pa}&pn=${pn}&am=${am}&cu=INR&tn=${tn}#Intent;scheme=upi;package=${pkgs[app]};end`;setTimeout(()=>window.open(u,"_blank"),600);}else{window.location.href=u;setTimeout(()=>{if(navigator.clipboard)navigator.clipboard.writeText(UPI_ID).then(()=>showToast("📋 UPI copied"));},1000);}}

// ── SUBMIT PAYMENT — Fixed permissions + WhatsApp fallback ──
async function submitPayment(){
  const ti=document.getElementById("txnId"),txn=san(ti.value).trim(),ee=document.getElementById("txnErr"),btn=document.getElementById("submitPayBtn");
  ee.textContent="";ee.style.display="none";
  if(!txn){ee.textContent="⚠️ Enter your UTR / Transaction ID.";ee.style.display="block";ti.focus();return;}
  if(txn.length<6){ee.textContent="⚠️ UTR must be at least 6 characters.";ee.style.display="block";ti.focus();return;}
  if(!currentUser){showToast("⚠ Please login again.");return;}
  if(S.bookPurchased){showToast("✅ Already activated!");closePayment();return;}
  if(S.bookStatus==="pending"){showToast("⏳ Payment already under review. Please wait.");return;}
  btn.disabled=true;btn.textContent="Submitting...";

  // Build WhatsApp approval message with direct approve link
  const approveUrl=location.origin+location.pathname+"#admin";
  const waMsg=encodeURIComponent(
    `🌿 *Health is Wealth — Payment Received*\n\n`+
    `👤 *Name:* ${currentUser.displayName||"User"}\n`+
    `📧 *Email:* ${currentUser.email||"N/A"}\n`+
    `🆔 *User ID:* ${currentUser.uid}\n`+
    `💳 *UTR / Txn ID:* ${txn}\n`+
    `💰 *Amount:* ₹${BOOK_PRICE}\n`+
    `📅 *Time:* ${new Date().toLocaleString("en-IN")}\n\n`+
    `✅ To approve, open Admin Panel:\n${approveUrl}\n\n`+
    `📋 Go to Payments tab → find this UTR → Click Approve`
  );
  const waUrl=`https://wa.me/${ADMIN_WA}?text=${waMsg}`;

  try{
    // Try saving to Firestore first
    let payId="";
    try{
      // Check duplicate UTR
      const dup=await db.collection("payments").where("txnId","==",txn).limit(1).get();
      if(!dup.empty){ee.textContent="❌ This UTR was already submitted. Enter a different UTR.";ee.style.display="block";btn.disabled=false;btn.textContent="✅ Submit Payment";return;}
      const pr=await db.collection("payments").add({userId:currentUser.uid,name:currentUser.displayName||"User",email:currentUser.email||"",txnId:txn,amount:BOOK_PRICE,status:"pending",submittedAt:firebase.firestore.FieldValue.serverTimestamp()});
      await db.collection("users").doc(currentUser.uid).update({bookStatus:"pending"});
      payId=pr.id;
    }catch(dbErr){
      // Firestore failed (rules not deployed yet) — still proceed with WhatsApp notification
      console.warn("Firestore write failed, proceeding with WA only:", dbErr.message);
    }

    // Always open WhatsApp to notify admin — this works even without Firestore rules
    closePayment();
    S.bookStatus="pending";updatePayStatus();
    document.getElementById("modalIco").textContent="🎉";
    document.getElementById("modalTitle").textContent="Payment Submitted!";
    document.getElementById("modalMsg").textContent=`UTR: ${txn}\n\n✅ Your referral link is now ACTIVE! Start sharing immediately.\n\nAdmin will verify your payment and unlock GPS Earn within a few hours.`;
    document.getElementById("successModal").classList.add("on");
    // Open WhatsApp with payment details
    setTimeout(()=>window.open(waUrl,"_blank"),800);
    showToast("📲 Opening WhatsApp to notify admin...",3000);

  }catch(e){ee.textContent="⚠️ Error: "+e.message;ee.style.display="block";}
  finally{btn.disabled=false;btn.textContent="✅ Submit Payment & Notify Admin";}
}
function closeModal(){document.getElementById("successModal").classList.remove("on");}

// ── WITHDRAWAL ────────────────────────────────
let wdMethod="upi";
function switchWDMethod(m){wdMethod=m;document.getElementById("wdUpiFields").style.display=m==="upi"?"block":"none";document.getElementById("wdBankFields").style.display=m==="bank"?"block":"none";document.getElementById("wdTabUpi").classList.toggle("on",m==="upi");document.getElementById("wdTabBank").classList.toggle("on",m==="bank");}
async function checkPendingWD(){if(!currentUser)return;try{const s=await db.collection("withdrawals").where("uid","==",currentUser.uid).where("status","==","pending").limit(1).get();const nb=document.getElementById("wdNewBlock"),pb=document.getElementById("wdPendingBlock"),pi=document.getElementById("wdPendingInfo");if(!s.empty){const d=s.docs[0].data();S.pendingWDId=s.docs[0].id;if(pb)pb.style.display="block";if(nb)nb.style.display="none";if(pi)pi.textContent=`₹${d.amount} withdrawal pending admin approval. Cancel to re-submit.`;}else{S.pendingWDId=null;if(pb)pb.style.display="none";if(nb)nb.style.display="block";}}catch(e){}}
async function cancelWithdrawal(){if(!S.pendingWDId||!currentUser)return;if(!confirm("Cancel this withdrawal? Balance will be refunded."))return;try{const doc=await db.collection("withdrawals").doc(S.pendingWDId).get();if(!doc.exists||doc.data().status!=="pending"){showToast("⚠ Not found or already processed.");return;}const amt=doc.data().amount||0;await db.collection("withdrawals").doc(S.pendingWDId).update({status:"cancelled",cancelledAt:firebase.firestore.FieldValue.serverTimestamp()});await db.collection("users").doc(currentUser.uid).update({wallet:firebase.firestore.FieldValue.increment(amt),balance:firebase.firestore.FieldValue.increment(amt)});S.pendingWDId=null;showToast("✅ Cancelled. ₹"+amt+" refunded.");checkPendingWD();loadTxns();}catch(e){showToast("⚠ Cancel failed: "+e.message);}}
async function requestWithdraw(){
  if(!currentUser)return;if(!S.bookPurchased){showToast("⚠ Activate account first.");return;}
  const pend=await db.collection("withdrawals").where("uid","==",currentUser.uid).where("status","==","pending").limit(1).get().catch(()=>({empty:true}));
  if(!pend.empty){showToast("⚠ You have a pending request. Cancel it first.");return;}
  const amt=parseFloat(document.getElementById("withdrawAmt").value);
  if(!amt||amt<MIN_WD){showToast(`⚠ Minimum withdrawal is ₹${MIN_WD}`);return;}
  if(S.wallet<amt){showToast(`⚠ Insufficient balance. Have: ₹${S.wallet.toFixed(0)}`);return;}
  let pd={};
  if(wdMethod==="upi"){const upi=san(document.getElementById("withdrawUPI").value).trim();if(!upi||upi.length<5){showToast("⚠ Enter a valid UPI ID / GPay number");return;}pd={method:"upi",upiId:upi};}
  else{const an=san(document.getElementById("withdrawAccName").value).trim(),ac=san(document.getElementById("withdrawAccNo").value).trim(),ac2=san(document.getElementById("withdrawAccNo2").value).trim(),ifs=san(document.getElementById("withdrawIFSC").value).trim().toUpperCase(),bn=san(document.getElementById("withdrawBankName").value).trim();if(!an){showToast("⚠ Enter account holder name");return;}if(!ac||ac.length<8){showToast("⚠ Enter valid account number");return;}if(ac!==ac2){showToast("⚠ Account numbers don't match");return;}if(!ifs||ifs.length!==11){showToast("⚠ Enter valid 11-char IFSC code");return;}if(!bn){showToast("⚠ Enter bank name");return;}pd={method:"bank",accName:an,accNo:ac,ifsc:ifs,bankName:bn,upiId:"Bank:"+ifs};}
  if(!confirm(`Withdraw ₹${amt}?\nBalance deducted immediately.`))return;
  const btn=document.getElementById("btnRequestWD");if(btn){btn.disabled=true;btn.textContent="Submitting...";}
  try{await db.collection("withdrawals").add({uid:currentUser.uid,name:currentUser.displayName||"User",email:currentUser.email||"",amount:amt,...pd,status:"pending",time:firebase.firestore.FieldValue.serverTimestamp()});await db.collection("users").doc(currentUser.uid).update({wallet:firebase.firestore.FieldValue.increment(-amt),balance:firebase.firestore.FieldValue.increment(-amt)});document.getElementById("withdrawAmt").value="";if(wdMethod==="upi")document.getElementById("withdrawUPI").value="";else["withdrawAccName","withdrawAccNo","withdrawAccNo2","withdrawIFSC","withdrawBankName"].forEach(id=>{const el=document.getElementById(id);if(el)el.value="";});showToast(`✅ ₹${amt} withdrawal requested!`);checkPendingWD();loadTxns();}catch(e){showToast("⚠ Failed: "+e.message);}
  finally{if(btn){btn.disabled=false;btn.textContent="💸 Submit Withdrawal Request";}}
}
async function loadTxns(){if(!currentUser)return;const list=document.getElementById("txnList");if(!list)return;try{const[p,w]=await Promise.all([db.collection("payments").where("userId","==",currentUser.uid).orderBy("submittedAt","desc").limit(10).get().catch(()=>({docs:[]})),db.collection("withdrawals").where("uid","==",currentUser.uid).orderBy("time","desc").limit(10).get().catch(()=>({docs:[]}))]);const items=[];p.docs.forEach(d=>{const t=d.data();items.push({type:"pay",desc:`Payment — Unlock (UTR: ${t.txnId||"—"})`,amt:t.amount||BOOK_PRICE,status:t.status,date:t.submittedAt?.toDate()});});w.docs.forEach(d=>{const t=d.data();items.push({type:"wd",desc:`Withdrawal → ${t.method==="bank"?`Bank (${t.ifsc||""})`:t.upiId||"UPI"}`,amt:t.amount||0,status:t.status,date:t.time?.toDate()});});if(!items.length){list.innerHTML='<div class="empty"><div class="empty-ico">📭</div><div class="empty-txt">No transactions yet</div></div>';return;}items.sort((a,b)=>(b.date||0)-(a.date||0));const sc=s=>s==="approved"||s==="paid"?"var(--green)":s==="rejected"||s==="cancelled"?"var(--red)":"var(--amber)";list.innerHTML=items.map(t=>`<div class="txn-item"><div class="txn-ico ${t.type==="wd"?"txn-ico-out":"txn-ico-in"}">${t.type==="wd"?"💸":"💰"}</div><div class="txn-desc">${esc(t.desc)}<div class="txn-status" style="color:${sc(t.status)}">${t.status}</div></div><span class="${t.type==="wd"?"txn-out":"txn-in"}">${t.type==="wd"?"-":""}₹${t.amt}</span></div>`).join("");}catch(e){}}

// ── APP INIT ──────────────────────────────────
(function(){try{const r=new URLSearchParams(location.search).get("ref");if(r)sessionStorage.setItem("__pendingRef",r.toUpperCase());}catch(e){}})();
window.addEventListener("load",()=>{
  try{const t=localStorage.getItem("__theme");if(t){document.documentElement.setAttribute("data-theme",t);if(t==="dark"){const b=document.querySelector(".tb-btn");if(b)b.textContent="☀️";}}}catch(e){}
  setTimeout(()=>{const s=document.getElementById("splash");if(s)s.classList.add("gone");},2000);
  try{const pr=sessionStorage.getItem("__pendingRef");if(pr){const ri=document.getElementById("signupRef");if(ri){ri.value=pr;switchTab("signup");}sessionStorage.removeItem("__pendingRef");}}catch(e){}
  if(location.hash==="#admin"){showAdminPanel();return;}
  // Show auth immediately — no waiting
  showAuth();
  if(!auth)return;
  let resolved=false;const fallback=setTimeout(()=>{if(!resolved){resolved=true;showAuth();}},8000);
  auth.onAuthStateChanged(user=>{if(!resolved){resolved=true;clearTimeout(fallback);}if(user){currentUser=user;loadUser(user);}else{showAuth();}});
});
window.addEventListener("hashchange",()=>{if(location.hash==="#admin")showAdminPanel();else if(currentUser)showUserApp();else showAuth();});

// ═══════════════════════════════════════════
// ADMIN PANEL
// ═══════════════════════════════════════════
let adminRefCode=null;
function copyFirestoreRules(){const rules=document.querySelector("pre").textContent;if(navigator.clipboard)navigator.clipboard.writeText(rules).then(()=>showToast("📋 Rules copied! Paste in Firebase Console."));else showToast("Select and copy the rules text manually.");}
async function adminLogin(){
  const email=document.getElementById("adminEmail").value.trim().toLowerCase(),pass=document.getElementById("adminPass").value,err=document.getElementById("adminErr"),btn=document.getElementById("adminLoginBtn");
  err.textContent="";if(!email||!pass){err.textContent="Enter email and password.";return;}
  if(email!==ADMIN_EMAIL.toLowerCase()){err.textContent="Access denied. Not admin account.";return;}
  if(btn){btn.disabled=true;btn.textContent="Signing in...";}
  try{const cred=await auth.signInWithEmailAndPassword(email,pass);if(cred.user.email.toLowerCase()!==ADMIN_EMAIL.toLowerCase()){await auth.signOut();err.textContent="Access denied.";return;}document.getElementById("adminBadge").textContent=cred.user.email.split("@")[0];document.getElementById("adminLoginBox").style.display="none";document.getElementById("adminDash").style.display="block";loadAdminStats();loadAdminPay();loadAdminRefCode();}
  catch(e){err.textContent=authErr(e.code);}finally{if(btn){btn.disabled=false;btn.textContent="Sign In to Admin";}}
}
function adminLogout(){auth.signOut().then(()=>{document.getElementById("adminLoginBox").style.display="flex";document.getElementById("adminDash").style.display="none";document.getElementById("adminEmail").value="";document.getElementById("adminPass").value="";location.hash="";showAuth();}).catch(()=>{location.hash="";showAuth();});}
function adminTab(btn,tabId){document.querySelectorAll(".admin-tab").forEach(t=>t.classList.remove("on"));btn.classList.add("on");["aDash","aUsers","aPay","aWD","aLeaderboard","aSettings"].forEach(id=>{const e=document.getElementById(id);if(e)e.style.display="none";});const el=document.getElementById(tabId);if(el)el.style.display="block";if(tabId==="aWD")loadAdminWD();else if(tabId==="aPay")loadAdminPay();else if(tabId==="aUsers")loadAdminUsers();else if(tabId==="aLeaderboard")loadLeaderboard();else if(tabId==="aSettings")loadSettings();else loadAdminStats();}
async function loadAdminStats(){try{const[users,wd,pay]=await Promise.all([db.collection("users").get().catch(()=>({size:0,docs:[]})),db.collection("withdrawals").where("status","==","pending").get().catch(()=>({size:0,docs:[]})),db.collection("payments").where("status","==","pending").get().catch(()=>({size:0,docs:[]}))]);document.getElementById("sTotalUsers").textContent=users.size||0;const pc=(users.docs||[]).filter(d=>d.data().bookPurchased).length;document.getElementById("sPaidUsers").textContent=pc;document.getElementById("sPendingWD").textContent=wd.size||0;document.getElementById("sPendingPay").textContent=pay.size||0;let tk=0,tb=0;(users.docs||[]).forEach(d=>{const dd=d.data();tk+=dd.totalKm||0;tb+=dd.wallet||dd.balance||0;});document.getElementById("sTotalKm").textContent=tk.toFixed(1);document.getElementById("sTotalBal").textContent="₹"+tb.toFixed(0);}catch(e){}}
async function loadAdminUsers(){
  const tb=document.getElementById("usersBody");tb.innerHTML='<tr><td colspan="9" style="text-align:center;padding:18px;color:#5a9070">Loading...</td></tr>';
  try{const snap=await db.collection("users").orderBy("joinedAt","desc").limit(200).get();if(snap.empty){tb.innerHTML='<tr><td colspan="9" style="text-align:center;padding:18px;color:#5a9070">No users yet.</td></tr>';return;}const ws=await db.collection("withdrawals").where("status","==","pending").get().catch(()=>({docs:[]}));const wm={};ws.docs.forEach(d=>{const dd=d.data();wm[dd.uid]=(wm[dd.uid]||0)+(dd.amount||0);});
  tb.innerHTML=snap.docs.map((doc,i)=>{const d=doc.data(),j=d.joinedAt?.toDate()?.toLocaleDateString("en-IN",{day:"2-digit",month:"short",year:"2-digit"})||"—",pw=wm[doc.id]||0;
  return`<tr><td style="font-weight:800;color:#5a9070;font-size:.78rem">#${i+1}</td><td><strong>${esc(d.name||"—")}</strong><div style="font-size:.66rem;color:#5a9070">${esc(d.email||"—")}</div></td><td style="font-family:monospace;font-size:.78rem">${esc(d.refCode||"—")}</td><td><strong style="color:var(--green)">₹${(d.wallet||d.balance||0).toFixed(0)}</strong>${pw>0?`<div style="font-size:.62rem;color:var(--amber)">⏳₹${pw} WD</div>`:""}</td><td style="font-size:.8rem">${(d.totalKm||0).toFixed(1)}km</td><td><span class="pill ${d.bookPurchased?"pill-a":"pill-p"}">${d.bookPurchased?(d.isAdminGranted?"🎁Free":"✅Active"):"🔒Locked"}</span></td><td style="text-align:center">${d.referralCount||0}</td><td style="font-size:.7rem">${j}</td><td><div style="display:flex;gap:3px;flex-wrap:wrap"><button class="btn-a" style="font-size:.62rem;padding:4px 7px" onclick="adminGrantCap('${doc.id}',${d.totalKm||0})">+KM</button>${!d.bookPurchased?`<button class="btn-a" style="font-size:.62rem;padding:4px 7px;background:linear-gradient(135deg,#6820d0,#a050f8)" onclick="adminGrantFreeById('${doc.id}','${esc(d.name||"")}')">🎁</button>`:""}<button class="btn-r" style="font-size:.62rem;padding:4px 7px" onclick="adminEditBalance('${doc.id}','${esc(d.name||"")}',${d.wallet||d.balance||0})">₹Edit</button><button class="btn-danger" onclick="adminRemoveUser('${doc.id}','${esc(d.name||"")}','${esc(d.email||"")}')">🗑</button></div></td></tr>`;}).join("");}catch(e){tb.innerHTML=`<tr><td colspan="9" style="text-align:center;padding:18px;color:var(--red)">Error: ${esc(e.message)}</td></tr>`;}
}
async function adminRemoveUser(uid,name,email){if(!confirm(`⚠️ REMOVE USER?\n\nName: ${name}\nEmail: ${email}\n\nThis deletes all their data permanently.`))return;const c2=prompt(`Type REMOVE to confirm:`);if(c2!=="REMOVE"){showToast("❌ Cancelled.");return;}try{await db.collection("users").doc(uid).delete();const[w,p,r,k]=await Promise.all([db.collection("withdrawals").where("uid","==",uid).get().catch(()=>({docs:[]})),db.collection("payments").where("userId","==",uid).get().catch(()=>({docs:[]})),db.collection("referrals").where("referrerId","==",uid).get().catch(()=>({docs:[]})),db.collection("km_logs").where("uid","==",uid).limit(50).get().catch(()=>({docs:[]}))]);const batch=db.batch();[...w.docs,...p.docs,...r.docs,...k.docs].forEach(d=>batch.delete(d.ref));await batch.commit();showToast(`✅ ${name} removed.`);loadAdminUsers();}catch(e){showToast("⚠ Remove failed: "+e.message);}}
async function adminGrantCap(uid,ktm){if(!confirm(`Grant +${KM_CAP} KM cap?`))return;try{await db.collection("users").doc(uid).update({kmLimit:(ktm||0)+KM_CAP});showToast(`✅ +${KM_CAP} KM granted!`);loadAdminUsers();}catch(e){showToast("⚠ Failed: "+e.message);}}
async function adminGrantFreeById(uid,name){if(!confirm(`Grant FREE access to ${name}?`))return;try{await db.collection("users").doc(uid).update({bookPurchased:true,bookStatus:"approved",isAdminGranted:true,grantedAt:firebase.firestore.FieldValue.serverTimestamp()});showToast("✅ Free access granted to "+name);loadAdminUsers();}catch(e){showToast("⚠ Failed: "+e.message);}}
async function adminEditBalance(uid,name,cur){const nb=prompt(`Edit balance for ${name}\nCurrent: ₹${cur}\nNew balance:`,cur);if(nb===null)return;const n=parseFloat(nb);if(isNaN(n)||n<0){showToast("⚠ Invalid amount");return;}if(!confirm(`Set ₹${n} for ${name}?`))return;try{await db.collection("users").doc(uid).update({wallet:n,balance:n});showToast(`✅ Balance set to ₹${n}`);loadAdminUsers();}catch(e){showToast("⚠ Failed: "+e.message);}}
async function grantFreeAccess(){const ei=document.getElementById("grantEmail"),email=san(ei.value).trim().toLowerCase();if(!isEmail(email)){showToast("⚠ Enter valid email");return;}try{const s=await db.collection("users").where("email","==",email).limit(1).get();if(s.empty){showToast("⚠ User not found");return;}await db.collection("users").doc(s.docs[0].id).update({bookPurchased:true,bookStatus:"approved",isAdminGranted:true,grantedAt:firebase.firestore.FieldValue.serverTimestamp()});showToast("✅ Free access granted to "+email);ei.value="";loadAdminUsers();}catch(e){showToast("⚠ Failed: "+e.message);}}

// ── ADMIN PAYMENTS (FULLY WORKING) ────────────
let payUnsub=null;
function loadAdminPay(){
  if(payUnsub)payUnsub();const tb=document.getElementById("payBody");tb.innerHTML='<tr><td colspan="7" style="text-align:center;padding:18px;color:#5a9070">Loading...</td></tr>';
  payUnsub=db.collection("payments").orderBy("submittedAt","desc").limit(100).onSnapshot(snap=>{
    if(!snap||snap.empty){tb.innerHTML='<tr><td colspan="7" style="text-align:center;padding:18px;color:#5a9070">No payments yet. Payments appear here when users submit UTR.</td></tr>';return;}
    tb.innerHTML=snap.docs.map(doc=>{const d=doc.data(),date=d.submittedAt?.toDate()?.toLocaleDateString("en-IN",{day:"2-digit",month:"short",year:"numeric",hour:"2-digit",minute:"2-digit"})||"—",pc=d.status==="approved"||d.status==="paid"?"pill-a":d.status==="rejected"?"pill-r":"pill-p";
    const btns=d.status==="pending"
      ?`<div style="display:flex;gap:5px;flex-wrap:wrap">
          <button class="btn-a" onclick="aApprovePay('${doc.id}','${d.userId||""}','${esc(d.name||"")}','${esc(d.email||"")}')">✅ Approve</button>
          <button class="btn-r" onclick="aRejectPay('${doc.id}','${d.userId||""}')">❌ Reject</button>
          <button style="background:#25d366;color:#fff;border:none;padding:5px 9px;border-radius:7px;cursor:pointer;font-size:.7rem;font-weight:700" onclick="notifyUserWA('${esc(d.name||"")}','${esc(d.email||"")}','${esc(d.txnId||"")}','approved')">📲 WA</button>
        </div>`
      :`<span style="font-size:.7rem;color:#5a9070">${d.status}</span>`;
    return`<tr>
      <td><strong>${esc(d.name||"—")}</strong><br><small style="color:#5a9070;font-size:.7rem">${esc(d.userId||"").slice(0,10)}...</small></td>
      <td style="font-size:.76rem;word-break:break-all"><a href="mailto:${esc(d.email||"")}" style="color:#0d6e3a;text-decoration:none">${esc(d.email||"—")}</a></td>
      <td><strong style="color:var(--green)">₹${d.amount||BOOK_PRICE}</strong></td>
      <td style="font-family:monospace;font-weight:700;font-size:.78rem;color:#071c10">${esc(d.txnId||"—")}</td>
      <td><span class="pill ${pc}">${d.status}</span></td>
      <td style="font-size:.7rem">${date}</td>
      <td>${btns}</td>
    </tr>`;}).join("");
  },err=>{tb.innerHTML=`<tr><td colspan="7" style="text-align:center;padding:18px;color:var(--red)">⚠️ Error loading. Deploy Firestore rules first!<br><small>${esc(err.message)}</small></td></tr>`;});
}
function notifyUserWA(name,email,txn,action){const msg=action==="approved"?`✅ *Health is Wealth*\n\nDear ${name},\n\nYour payment (UTR: ${txn}) has been APPROVED!\n\nYour GPS Walk Earn is now active. Open the app and start walking to earn ₹1/KM!\n\n🌿 Walk · Earn · Win`:`❌ *Health is Wealth*\n\nDear ${name},\n\nYour payment (UTR: ${txn}) could not be verified.\n\nPlease contact support or resubmit with a valid UTR.`;window.open(`https://wa.me/${ADMIN_WA}?text=${encodeURIComponent(msg)}`,"_blank");}
async function aApprovePay(id,userId,name,email){
  if(!confirm(`Approve payment for:\nName: ${name}\nEmail: ${email}\n\nThis will activate GPS Earn + credit their referrer.`))return;
  try{await db.collection("payments").doc(id).update({status:"approved",approvedAt:firebase.firestore.FieldValue.serverTimestamp()});await db.collection("users").doc(userId).update({bookPurchased:true,bookStatus:"approved"});
    const ud=await db.collection("users").doc(userId).get();const ud2=ud.data();
    if(ud2?.referredBy){const rs=await db.collection("users").where("refCode","==",ud2.referredBy).limit(1).get();if(!rs.empty){const rd=rs.docs[0],rdd=rd.data();if(rdd.bookPurchased&&rd.id!==userId){await db.collection("users").doc(rd.id).update({referralCount:firebase.firestore.FieldValue.increment(1),wallet:firebase.firestore.FieldValue.increment(REF_REWARD),balance:firebase.firestore.FieldValue.increment(REF_REWARD),kmLimit:(rdd.totalKm||0)+KM_CAP});const rr=await db.collection("referrals").where("referrerId","==",rd.id).where("referredId","==",userId).limit(1).get();if(!rr.empty)await rr.docs[0].ref.update({status:"paid",amount:REF_REWARD,paidAt:firebase.firestore.FieldValue.serverTimestamp(),referredName:ud2.name||"User"});await db.collection("km_logs").add({uid:rd.id,km:0,earned:REF_REWARD,type:"referral_bonus",referredUserId:userId,date:new Date().toISOString().slice(0,10),ts:firebase.firestore.FieldValue.serverTimestamp()});}}}
    showToast("✅ Approved! GPS Earn activated for "+name);
  }catch(e){showToast("⚠ Error: "+e.message);}
}
async function aRejectPay(id,userId){if(!confirm("Reject this payment?"))return;try{await db.collection("payments").doc(id).update({status:"rejected",rejectedAt:firebase.firestore.FieldValue.serverTimestamp()});if(userId)await db.collection("users").doc(userId).update({bookStatus:"rejected"});showToast("❌ Payment rejected.");}catch(e){showToast("⚠ Error: "+e.message);}}

// ── ADMIN WITHDRAWALS ─────────────────────────
let wdUnsub=null;
function loadAdminWD(){
  if(wdUnsub)wdUnsub();const tb=document.getElementById("wdBody");tb.innerHTML='<tr><td colspan="6" style="text-align:center;padding:18px;color:#5a9070">Loading...</td></tr>';
  wdUnsub=db.collection("withdrawals").orderBy("time","desc").limit(100).onSnapshot(snap=>{
    if(!snap||snap.empty){tb.innerHTML='<tr><td colspan="6" style="text-align:center;padding:18px;color:#5a9070">No withdrawal requests yet.</td></tr>';return;}
    tb.innerHTML=snap.docs.map(doc=>{const d=doc.data(),date=d.time?.toDate()?.toLocaleDateString("en-IN",{day:"2-digit",month:"short",year:"numeric"})||"—",pc=d.status==="approved"?"pill-a":d.status==="rejected"||d.status==="cancelled"?"pill-r":"pill-p";
    const det=d.method==="bank"?`<div class="wd-detail-box">🏦 <strong>Bank</strong><br>Name: <strong>${esc(d.accName||"—")}</strong><br>A/c: <strong>${esc(d.accNo||"—")}</strong><br>IFSC: <strong>${esc(d.ifsc||"—")}</strong><br>Bank: ${esc(d.bankName||"—")}</div>`:`<div class="wd-detail-box">📱 <strong>UPI/GPay</strong><br>ID: <strong style="color:#0d6e3a">${esc(d.upiId||"—")}</strong></div>`;
    const btns=d.status==="pending"?`<div style="display:flex;gap:5px;flex-wrap:wrap"><button class="btn-a" onclick="aApproveWD('${doc.id}','${d.uid||""}','${esc(d.upiId||"")}',${d.amount||0},'${esc(d.name||"")}')">✅</button><button class="btn-r" onclick="aRejectWD('${doc.id}','${d.uid||""}',${d.amount||0})">❌</button></div>`:`<span style="font-size:.7rem;color:#5a9070">${d.status}</span>`;
    return`<tr><td><strong>${esc(d.name||"—")}</strong><br><small style="color:#5a9070">${esc(d.email||"")}</small></td><td><strong style="color:var(--green)">₹${d.amount||0}</strong></td><td>${det}</td><td><span class="pill ${pc}">${d.status}</span></td><td style="font-size:.7rem">${date}</td><td>${btns}</td></tr>`;}).join("");
  });
}
async function aApproveWD(id,uid,upiId,amount,name){if(!confirm(`Confirm you have transferred ₹${amount} to:\n${upiId}\n\nMark as approved?`))return;try{await db.collection("withdrawals").doc(id).update({status:"approved",approvedAt:firebase.firestore.FieldValue.serverTimestamp()});showToast("✅ Withdrawal approved!");window.open(`https://wa.me/${ADMIN_WA}?text=${encodeURIComponent(`✅ Health is Wealth\n\nWithdrawal APPROVED!\n👤 ${name}\n💰 ₹${amount}\n📲 ${upiId}`)}`,"_blank");}catch(e){showToast("⚠ Error: "+e.message);}}
async function aRejectWD(id,uid,amt){if(!confirm(`Reject & refund ₹${amt} to user?`))return;try{if(uid)await db.collection("users").doc(uid).update({wallet:firebase.firestore.FieldValue.increment(amt),balance:firebase.firestore.FieldValue.increment(amt)});await db.collection("withdrawals").doc(id).update({status:"rejected",rejectedAt:firebase.firestore.FieldValue.serverTimestamp()});showToast(`❌ Rejected. ₹${amt} refunded.`);}catch(e){showToast("⚠ Error: "+e.message);}}

// ── LEADERBOARD ───────────────────────────────
async function loadLeaderboard(){const tb=document.getElementById("lbBody");tb.innerHTML='<tr><td colspan="7" style="text-align:center;padding:18px;color:#5a9070">Loading...</td></tr>';try{const s=await db.collection("users").where("bookPurchased","==",true).orderBy("referralCount","desc").limit(50).get();if(s.empty){tb.innerHTML='<tr><td colspan="7" style="text-align:center;padding:18px;color:#5a9070">No active users yet.</td></tr>';return;}const m=["🥇","🥈","🥉"],p=[PRIZE_1,PRIZE_2,PRIZE_3],top=s.docs.slice(0,3).map(d=>d.data());["prize1","prize2","prize3"].forEach((id,i)=>{const ne=document.getElementById(id+"Name"),re=document.getElementById(id+"refs");if(top[i]){if(ne)ne.textContent=esc(top[i].name||"—");if(re)re.textContent=(top[i].referralCount||0)+" referrals";}});tb.innerHTML=s.docs.map((doc,i)=>{const d=doc.data();return`<tr style="${i<3?"background:linear-gradient(90deg,rgba(240,180,41,.06),transparent)":""}"><td style="font-size:1rem;font-weight:800;text-align:center">${m[i]||"#"+(i+1)}</td><td><strong>${esc(d.name||"—")}</strong></td><td style="font-size:.74rem;color:#5a9070">${esc(d.email||"—")}</td><td><strong style="color:var(--green)">${d.referralCount||0}</strong></td><td>${(d.totalKm||0).toFixed(1)} km</td><td><strong style="color:var(--green)">₹${(d.wallet||d.balance||0).toFixed(0)}</strong></td><td><strong style="color:#6820d0">${i<3?fmtL(p[i]):"—"}</strong></td></tr>`;}).join("");}catch(e){tb.innerHTML=`<tr><td colspan="7" style="text-align:center;padding:18px;color:var(--red)">Error: ${esc(e.message)}</td></tr>`;}}

// ── ADMIN FREE REF ────────────────────────────
async function loadAdminRefCode(){try{const s=await db.collection("free_referrals").where("isAdmin","==",true).where("active","==",true).limit(1).get();if(!s.empty){adminRefCode=s.docs[0].data().code;}else{adminRefCode="ADMIN"+Math.random().toString(36).slice(-5).toUpperCase();await db.collection("free_referrals").add({code:adminRefCode,isAdmin:true,active:true,createdAt:firebase.firestore.FieldValue.serverTimestamp()});}const dd=document.getElementById("adminRefCodeDisplay"),du=document.getElementById("adminRefUrlDisplay");if(dd)dd.textContent=adminRefCode;if(du)du.textContent=`${location.origin}${location.pathname}?ref=${adminRefCode}`;}catch(e){}}
function copyAdminRef(){if(!adminRefCode)return;const url=`${location.origin}${location.pathname}?ref=${adminRefCode}`;if(navigator.clipboard)navigator.clipboard.writeText(url).then(()=>showToast("📋 Admin link copied!"));else showToast("Code: "+adminRefCode);}
function shareAdminRefWA(){if(!adminRefCode)return;const url=`${location.origin}${location.pathname}?ref=${adminRefCode}`;window.open("https://wa.me/?text="+encodeURIComponent("🌿 Join Health is Wealth FREE!\n🔗 "+url+"\n\nFREE access — no payment needed!"),"_blank");}
async function generateNewAdminRef(){if(!confirm("Generate new admin code? Old code stops working."))return;try{const s=await db.collection("free_referrals").where("isAdmin","==",true).where("active","==",true).get();const b=db.batch();s.docs.forEach(d=>b.update(d.ref,{active:false}));await b.commit();adminRefCode="ADMIN"+Math.random().toString(36).slice(-5).toUpperCase();await db.collection("free_referrals").add({code:adminRefCode,isAdmin:true,active:true,createdAt:firebase.firestore.FieldValue.serverTimestamp()});document.getElementById("adminRefCodeDisplay").textContent=adminRefCode;document.getElementById("adminRefUrlDisplay").textContent=`${location.origin}${location.pathname}?ref=${adminRefCode}`;showToast("✅ New code generated!");}catch(e){showToast("⚠ Failed: "+e.message);}}

// ── SETTINGS ──────────────────────────────────
async function loadSettings(){try{const doc=await db.collection("app_settings").doc("config").get();if(doc.exists){const d=doc.data();if(d.bookPrice)document.getElementById("setPrice").value=d.bookPrice;if(d.refReward)document.getElementById("setRefReward").value=d.refReward;if(d.kmRate)document.getElementById("setKmRate").value=d.kmRate;if(d.kmCap)document.getElementById("setKmCap").value=d.kmCap;if(d.minWD)document.getElementById("setMinWD").value=d.minWD;if(d.upiId)document.getElementById("setUpiId").value=d.upiId;if(d.prize1)document.getElementById("setPrize1").value=d.prize1;if(d.prize2)document.getElementById("setPrize2").value=d.prize2;if(d.prize3)document.getElementById("setPrize3").value=d.prize3;if(d.announcement)document.getElementById("setAnnouncement").value=d.announcement;}showToast("✅ Settings loaded.");}catch(e){showToast("⚠ Failed: "+e.message);}}
async function saveSettings(){const price=parseFloat(document.getElementById("setPrice").value)||BOOK_PRICE,refR=parseFloat(document.getElementById("setRefReward").value)||REF_REWARD,kmR=parseFloat(document.getElementById("setKmRate").value)||KM_RATE,kmC=parseInt(document.getElementById("setKmCap").value)||KM_CAP,minW=parseFloat(document.getElementById("setMinWD").value)||MIN_WD,upi=document.getElementById("setUpiId").value.trim()||UPI_ID,p1=parseFloat(document.getElementById("setPrize1").value)||PRIZE_1,p2=parseFloat(document.getElementById("setPrize2").value)||PRIZE_2,p3=parseFloat(document.getElementById("setPrize3").value)||PRIZE_3,ann=document.getElementById("setAnnouncement").value.trim();try{await db.collection("app_settings").doc("config").set({bookPrice:price,refReward:refR,kmRate:kmR,kmCap:kmC,minWD:minW,upiId:upi,prize1:p1,prize2:p2,prize3:p3,announcement:ann,updatedAt:firebase.firestore.FieldValue.serverTimestamp()},{merge:true});BOOK_PRICE=price;REF_REWARD=refR;KM_RATE=kmR;KM_CAP=kmC;MIN_WD=minW;UPI_ID=upi;PRIZE_1=p1;PRIZE_2=p2;PRIZE_3=p3;showToast("✅ Settings saved!");}catch(e){showToast("⚠ Save failed: "+e.message);}}
function sendBroadcast(){const m=document.getElementById("broadcastMsg").value.trim();if(!m){showToast("⚠ Enter a message first");return;}window.open(`https://wa.me/${ADMIN_WA}?text=${encodeURIComponent(m)}`,"_blank");}
</script>
</body>
</html>
