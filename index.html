<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="robots" content="noindex,nofollow">
<meta http-equiv="Content-Security-Policy" content="default-src 'none'; script-src 'sha256-ULkHNcpdytf3OYq8js+VzfTRQQv4C1eAB/7XE8E0bpw='; style-src 'unsafe-inline'; base-uri 'none'; form-action 'none'">
<meta name="referrer" content="no-referrer">
<title>REVAD</title>
<style>
  :root{
    --ink:#0e1522; --ink-2:#17213a; --text:#eef1f6; --muted:#8f9bb3;
    --line:#2b3857; --brass:#d9b25a; --danger:#ff6b5e; --ok:#7fd6a0; --red:#d8332a; --red-dark:#8f1d17;
  }
  *{box-sizing:border-box}
  html,body{margin:0}
  body{
    min-height:100vh;color:var(--text);
    font-family:"Avenir Next","Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    background:radial-gradient(ellipse at 50% 28%,var(--ink-2) 0%,var(--ink) 62%) fixed;
  }
  [hidden]{display:none!important}
  .screen{min-height:100vh;display:flex;align-items:center;justify-content:center}
  main{width:100%;max-width:320px;padding:24px;text-align:center}

  /* ---------- lock screen ---------- */
  .lock{width:168px;height:210px;margin:0 auto 18px;display:block;overflow:visible}
  #shackle{transform-origin:116px 92px;transition:transform .7s cubic-bezier(.3,1.5,.5,1)}
  .open #shackle{transform:translateY(-12px) rotate(32deg)}
  #keyhole{transition:fill .3s}
  #glow{opacity:.55;transition:opacity .4s}
  .open #glow{opacity:1}
  .bad #keyhole{fill:var(--danger)}
  .open #keyhole{fill:var(--ok)}
  .lockwrap.shake{animation:shake .38s}
  @keyframes shake{20%{transform:translateX(-9px) rotate(-2deg)}50%{transform:translateX(8px) rotate(2deg)}80%{transform:translateX(-4px)}}
  h1{font-size:26px;font-weight:600;letter-spacing:.01em;margin:0 0 6px}
  .sub{margin:0 0 24px;color:var(--muted);font-size:15px}
  .field{position:relative;margin-bottom:12px}
  input{width:100%;padding:13px 46px 13px 16px;border-radius:10px;border:1px solid var(--line);
    background:rgba(255,255,255,.04);color:var(--text);font-size:16px;letter-spacing:.04em}
  input::placeholder{color:var(--muted);letter-spacing:0}
  input:focus{outline:2px solid var(--brass);outline-offset:1px;border-color:transparent}
  .eye{position:absolute;right:6px;top:50%;transform:translateY(-50%);width:36px;height:36px;border:0;
    background:none;color:var(--muted);cursor:pointer;border-radius:8px;padding:0}
  .eye:hover{color:var(--text)}
  .eye:focus-visible,.go:focus-visible,.relock:focus-visible{outline:2px solid var(--brass);outline-offset:2px}
  .eye svg{width:20px;height:20px;fill:none;stroke:currentColor;stroke-width:2;stroke-linecap:round;stroke-linejoin:round}
  .go{width:100%;padding:13px;border:0;border-radius:10px;font-size:16px;font-weight:700;cursor:pointer;color:#2a1d08;
    background:linear-gradient(180deg,#ecca78,var(--brass) 55%,#c39a40);
    box-shadow:0 1px 0 rgba(255,255,255,.35) inset,0 6px 18px rgba(217,178,90,.22)}
  .go:hover{filter:brightness(1.06)}.go:active{transform:translateY(1px)}
  .err{min-height:20px;margin-top:12px;font-size:14px;color:var(--danger)}
  .ok .err{color:var(--ok)}

  /* ---------- inside ---------- */
  #inside{animation:enter .8s ease both}
  @keyframes enter{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
  .wrap{max-width:880px;margin:0 auto;padding:0 24px}
  .hero{position:relative;overflow:hidden;padding:84px 0 72px;border-bottom:4px solid var(--brass)}
  .hero::before{content:"";position:absolute;top:-40%;bottom:-40%;left:-12%;width:58%;
    background:linear-gradient(180deg,var(--red),var(--red-dark));transform:rotate(14deg);transform-origin:center}
  .hero .wrap{position:relative}
  .welcome{margin:0 0 10px;font-size:18px;font-weight:600;color:#ffe9d6}
  .display{margin:0;font-family:Impact,"Haettenschweiler","Arial Narrow Bold","Arial Black",sans-serif;font-weight:400;
    font-size:clamp(46px,9.5vw,92px);line-height:.98;text-transform:uppercase;letter-spacing:.01em}
  .abbr{display:inline-block;margin-top:22px;padding:6px 18px;border:3px solid var(--brass);color:var(--brass);
    font-family:Impact,"Haettenschweiler","Arial Narrow Bold","Arial Black",sans-serif;font-size:34px;letter-spacing:.18em;
    background:rgba(14,21,34,.7);transform:rotate(-3deg)}
  .lead{max-width:520px;margin:26px 0 0;font-size:18px;line-height:1.55;color:var(--text)}

  section{padding:56px 0 0}
  h2{margin:0 0 18px;font-family:Impact,"Haettenschweiler","Arial Narrow Bold","Arial Black",sans-serif;font-weight:400;
    font-size:30px;letter-spacing:.02em}
  .manifesto{font-size:clamp(22px,3.4vw,30px);line-height:1.4;max-width:720px;margin:0}
  .manifesto b{color:var(--brass);font-weight:600}
  ol.rules{margin:0;padding:0;list-style:none;counter-reset:r}
  ol.rules li{counter-increment:r;display:flex;gap:18px;align-items:baseline;padding:16px 0;border-top:1px solid var(--line);font-size:18px}
  ol.rules li:last-child{border-bottom:1px solid var(--line)}
  ol.rules li::before{content:counter(r);flex:none;width:34px;font-family:Impact,"Arial Narrow Bold",sans-serif;font-size:26px;color:var(--red)}
  dl.ranks{margin:0;max-width:640px}
  dl.ranks div{display:flex;justify-content:space-between;gap:20px;padding:14px 0;border-top:1px solid var(--line)}
  dl.ranks div:last-child{border-bottom:1px solid var(--line)}
  dt{font-weight:600;font-size:18px;color:var(--brass)}
  dd{margin:0;color:var(--muted);text-align:right}
  footer{padding:64px 0 56px;display:flex;flex-wrap:wrap;gap:16px;align-items:center;justify-content:space-between;color:var(--muted);font-size:14px}
  .relock{padding:10px 18px;border-radius:10px;border:1px solid var(--line);background:rgba(255,255,255,.04);color:var(--text);
    font-size:15px;font-weight:600;cursor:pointer}
  .relock:hover{border-color:var(--brass)}

  ul.members{list-style:none;margin:0;padding:0;display:flex;flex-wrap:wrap;gap:0 32px;max-width:640px;border-bottom:1px solid var(--line)}
  ul.members li{flex:1 1 40%;padding:13px 0;border-top:1px solid var(--line);font-size:18px}
  .hint{display:block;margin-top:4px}
  input:disabled,.go:disabled{opacity:.5;cursor:not-allowed}
  /* weak-flashlight cursor glow */
  #torch{position:fixed;left:0;top:0;width:340px;height:340px;margin:-170px 0 0 -170px;border-radius:50%;
    pointer-events:none;z-index:99999;opacity:0;mix-blend-mode:screen;will-change:transform;
    background:radial-gradient(circle,rgba(255,196,120,.22) 0%,rgba(255,176,96,.10) 26%,rgba(255,160,80,.035) 46%,transparent 66%)}
  #torch.on{opacity:1;animation:weak 3.4s infinite}
  @keyframes weak{
    0%{filter:brightness(1)}8%{filter:brightness(.72)}11%{filter:brightness(1)}
    37%{filter:brightness(.9)}40%{filter:brightness(.55)}43%{filter:brightness(.95)}
    71%{filter:brightness(1)}74%{filter:brightness(.68)}78%{filter:brightness(1.05)}100%{filter:brightness(1)}}
  @media (hover:none){#torch{display:none}}
  .caps{margin:-2px 0 12px;font-size:13px;font-weight:600;color:#f2c14e}
  .actions{display:flex;gap:10px;flex-wrap:wrap}
  @media (max-width:560px){
    .hero::before{width:80%;left:-30%}
    ol.rules li{font-size:16px}dd{text-align:left}dl.ranks div{flex-direction:column;gap:2px}
  }
  @media (prefers-reduced-motion:reduce){
    #shackle{transition:none}.lockwrap.shake,#inside,#torch.on{animation:none}
  }
</style>
</head>
<body>

<!-- ===== LOCK SCREEN ===== -->
<div class="screen" id="lockScreen">
<main id="app">
  <div class="lockwrap" id="lockwrap">
    <svg class="lock" viewBox="0 0 160 200" role="img" aria-label="Padlock">
      <defs>
        <linearGradient id="steel" x1="0" y1="0" x2="1" y2="0">
          <stop offset="0" stop-color="#9aa6ba"/><stop offset=".35" stop-color="#eef2f8"/>
          <stop offset=".65" stop-color="#b3bdcd"/><stop offset="1" stop-color="#7d889c"/>
        </linearGradient>
        <linearGradient id="brass" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0" stop-color="#efcf82"/><stop offset=".45" stop-color="#cfa247"/><stop offset="1" stop-color="#8f6a22"/>
        </linearGradient>
        <linearGradient id="sheen" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0" stop-color="#fff" stop-opacity=".45"/><stop offset=".5" stop-color="#fff" stop-opacity="0"/>
        </linearGradient>
        <radialGradient id="halo" cx=".5" cy=".5" r=".5">
          <stop offset="0" stop-color="#d9b25a" stop-opacity=".5"/><stop offset="1" stop-color="#d9b25a" stop-opacity="0"/>
        </radialGradient>
      </defs>
      <circle id="glow" cx="80" cy="118" r="96" fill="url(#halo)"/>
      <ellipse cx="80" cy="190" rx="54" ry="7" fill="#000" opacity=".35"/>
      <g id="shackle">
        <path d="M44 100 V62 a36 36 0 0 1 72 0 V100" fill="none" stroke="#4b5568" stroke-width="18" stroke-linecap="round"/>
        <path d="M44 100 V62 a36 36 0 0 1 72 0 V100" fill="none" stroke="url(#steel)" stroke-width="13" stroke-linecap="round"/>
      </g>
      <rect x="20" y="88" width="120" height="96" rx="18" fill="url(#brass)"/>
      <rect x="20" y="88" width="120" height="96" rx="18" fill="url(#sheen)"/>
      <rect x="27" y="95" width="106" height="82" rx="12" fill="none" stroke="#fff" stroke-opacity=".28" stroke-width="1.5"/>
      <circle cx="35" cy="107" r="2.6" fill="#7a5a1c"/><circle cx="125" cy="107" r="2.6" fill="#7a5a1c"/>
      <circle cx="35" cy="165" r="2.6" fill="#7a5a1c"/><circle cx="125" cy="165" r="2.6" fill="#7a5a1c"/>
      <g id="keyhole" fill="#2a1d08"><circle cx="80" cy="128" r="12"/><path d="M73 134 H87 L91 163 H69 Z"/></g>
    </svg>
  </div>
  <h1 id="title">Site Is Locked</h1>
  <p class="sub" id="sub">Enter the password to continue</p>
  <div class="field">
    <input id="pw" type="password" placeholder="Password" aria-label="Password" autocomplete="off" autocapitalize="off" autocorrect="off" spellcheck="false" autofocus>
    <button class="eye" id="eye" type="button" aria-label="Show password">
      <svg viewBox="0 0 24 24"><path d="M2 12s4-7 10-7 10 7 10 7-4 7-10 7S2 12 2 12z"/><circle cx="12" cy="12" r="3"/></svg>
    </button>
  </div>
  <div class="caps" id="caps" role="status" hidden>Caps Lock is on</div>
  <button class="go" id="go">Unlock</button>
  <div class="err" id="err" aria-live="polite"></div>
</main>
</div>

<!-- ===== INSIDE ===== -->
<div id="inside" hidden>
</div>

<div id="torch" aria-hidden="true"></div>

<script id="vault" type="application/json">{"v":1,"it":600000,"salt":"iMcmRurnfpphRqLlpHOOrA==","iv":"G3Eik3pD4Lzm7D4d","ct":"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"}</script>
<script>
  // ===== Settings you can change =====
  var MAX_TRIES           = 3;       // wrong tries before a lockout
  var LOCK_START_MIN      = 5;       // first lockout, in minutes
  var LOCK_STEP_MIN       = 5;       // every new lockout adds this many minutes
  var IDLE_MINUTES        = 3;       // auto re-lock after this long with no activity
  var HIDDEN_LOCK_SECONDS = 60;      // re-lock if the tab stays in the background this long

  var app = document.getElementById('app');
  var pw = document.getElementById('pw');
  var go = document.getElementById('go');
  var err = document.getElementById('err');
  var wrap = document.getElementById('lockwrap');
  var caps = document.getElementById('caps');
  var busy = false, inside = false, plain = null, idleTimer = null, lockTimer = null, hideTimer = null;

  /* ---- encryption: the inside page is locked with AES-256-GCM, key made from the password ---- */
  var enc = new TextEncoder(), dec = new TextDecoder();
  function b64e(buf) { var b = new Uint8Array(buf), s = ''; for (var i = 0; i < b.length; i++) s += String.fromCharCode(b[i]); return btoa(s); }
  function b64d(str) { var s = atob(str), b = new Uint8Array(s.length); for (var i = 0; i < s.length; i++) b[i] = s.charCodeAt(i); return b; }
  async function deriveKey(password, salt, iterations) {
    var base = await crypto.subtle.importKey('raw', enc.encode(password), 'PBKDF2', false, ['deriveKey']);
    return crypto.subtle.deriveKey({ name: 'PBKDF2', salt: salt, iterations: iterations, hash: 'SHA-256' },
      base, { name: 'AES-GCM', length: 256 }, false, ['encrypt', 'decrypt']);
  }
  async function decryptVault(v, password) {
    var key = await deriveKey(password, b64d(v.salt), v.it);
    var out = await crypto.subtle.decrypt({ name: 'AES-GCM', iv: b64d(v.iv) }, key, b64d(v.ct));
    return dec.decode(out);
  }
  var vault = JSON.parse(document.getElementById('vault').textContent);

  function save(k, v) { try { if (v === null) localStorage.removeItem(k); else localStorage.setItem(k, String(v)); } catch (e) {} }
  function load(k) { try { return localStorage.getItem(k); } catch (e) { return null; } }

  /* ---- lockout after too many wrong tries (survives refresh, grows each time) ---- */
  function setDisabled(on) { pw.disabled = on; go.disabled = on; }
  function startCountdown(until) {
    setDisabled(true);
    clearInterval(lockTimer);
    function tick() {
      var left = Math.ceil((until - Date.now()) / 1000);
      if (left <= 0) {
        clearInterval(lockTimer);
        save('revad_until', null); save('revad_tries', null);
        setDisabled(false); err.textContent = ''; pw.focus();
        return;
      }
      var mm = Math.floor(left / 60), ss = left % 60;
      err.textContent = 'Too many tries. Try again in ' + mm + ':' + (ss < 10 ? '0' : '') + ss;
    }
    tick();
    lockTimer = setInterval(tick, 250);
  }
  var saved = parseInt(load('revad_until'), 10);
  if (saved && saved > Date.now()) startCountdown(saved);
  if (!window.crypto || !crypto.subtle) { err.textContent = 'This browser cannot run the lock.'; setDisabled(true); }

  /* ---- caps lock warning ---- */
  function capsCheck(e) { if (e.getModifierState) caps.hidden = !e.getModifierState('CapsLock'); }
  pw.addEventListener('keydown', capsCheck);
  pw.addEventListener('keyup', capsCheck);

  /* ---- unlocking: the right password is the only thing that can decrypt the inside ---- */
  function showInside() {
    var box = document.getElementById('inside');
    box.innerHTML = plain;
    document.getElementById('lockScreen').hidden = true;
    box.hidden = false;
    var h = document.getElementById('hint');
    if (h) h.textContent = 'Esc locks instantly. Auto-locks after ' + IDLE_MINUTES + ' minutes of no activity.';
    inside = true;
    window.scrollTo(0, 0);
    resetIdle();
  }
  async function tryUnlock() {
    if (busy || pw.disabled) return;
    var attempt = pw.value;
    if (!attempt) { err.textContent = 'Enter the password first'; return; }
    busy = true; go.disabled = true; err.textContent = '';
    document.getElementById('sub').textContent = 'Checking…';
    var html = null;
    try { html = await decryptVault(vault, attempt); } catch (e) { html = null; }
    pw.value = ''; attempt = '';
    document.getElementById('sub').textContent = 'Enter the password to continue';
    if (html !== null) {
      plain = html;
      save('revad_tries', null); save('revad_until', null); save('revad_strikes', null);
      app.classList.remove('bad'); app.classList.add('open', 'ok');
      document.getElementById('title').textContent = 'Unlocked';
      document.getElementById('sub').textContent = 'Welcome in…';
      setTimeout(showInside, 1000);
    } else {
      busy = false; go.disabled = false;
      var tries = (parseInt(load('revad_tries'), 10) || 0) + 1;
      app.classList.add('bad');
      wrap.classList.remove('shake'); void wrap.offsetWidth; wrap.classList.add('shake');
      setTimeout(function () { app.classList.remove('bad'); }, 900);
      if (tries >= MAX_TRIES) {
        var strikes = parseInt(load('revad_strikes'), 10) || 0;
        var until = Date.now() + (LOCK_START_MIN + strikes * LOCK_STEP_MIN) * 60000;
        save('revad_strikes', strikes + 1);
        save('revad_until', until); save('revad_tries', null);
        startCountdown(until);
      } else {
        save('revad_tries', tries);
        var left = MAX_TRIES - tries;
        err.textContent = 'Wrong password. ' + left + (left === 1 ? ' try' : ' tries') + ' left';
        pw.focus();
      }
    }
  }
  go.addEventListener('click', tryUnlock);
  pw.addEventListener('keydown', function (e) { if (e.key === 'Enter') tryUnlock(); });
  pw.addEventListener('input', function () { err.textContent = ''; });
  document.getElementById('eye').addEventListener('click', function () {
    pw.type = pw.type === 'password' ? 'text' : 'password'; pw.focus();
  });

  /* ---- re-locking: button, Esc key, idle timeout, background tab, back button ---- */
  function relock() { plain = null; location.reload(); }
  function resetIdle() {
    if (!inside) return;
    clearTimeout(idleTimer);
    idleTimer = setTimeout(relock, IDLE_MINUTES * 60000);
  }
  ['mousemove', 'mousedown', 'keydown', 'scroll', 'touchstart'].forEach(function (ev) {
    window.addEventListener(ev, resetIdle, { passive: true });
  });
  document.addEventListener('keydown', function (e) { if (inside && e.key === 'Escape') relock(); });
  document.addEventListener('visibilitychange', function () {
    if (!inside) return;
    if (document.hidden) hideTimer = setTimeout(relock, HIDDEN_LOCK_SECONDS * 1000);
    else clearTimeout(hideTimer);
  });
  window.addEventListener('pageshow', function (e) { if (e.persisted) location.reload(); });

  /* ---- the Lock button on the inside page ---- */
  document.addEventListener('click', function (e) {
    var t = e.target.closest ? e.target.closest('button') : null;
    if (t && t.id === 'relock') relock();
  });

  /* ---- weak flashlight glow that follows the cursor ---- */
  (function () {
    var torch = document.getElementById('torch'), x = 0, y = 0, queued = false;
    function draw() { torch.style.transform = 'translate(' + x + 'px,' + y + 'px)'; queued = false; }
    window.addEventListener('mousemove', function (e) {
      x = e.clientX; y = e.clientY;
      torch.classList.add('on');
      if (!queued) { queued = true; requestAnimationFrame(draw); }
    }, { passive: true });
    document.addEventListener('mouseleave', function () { torch.classList.remove('on'); });
  })();
</script>
</body>
</html>
