<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Teacher's Day</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&family=Caveat:wght@500;600;700&display=swap');

  :root{
    --pink: #ff9ecb;
    --pink-deep: #f472b6;
    --violet: #a78bfa;
    --violet-deep: #8b5cf6;
    --cream: #fff5fa;
    --ink: #4a2a5a;
  }

  *{ box-sizing:border-box; -webkit-tap-highlight-color:transparent; }
  html,body{ margin:0; padding:0; height:100%; overflow:hidden; font-family:'Quicksand',sans-serif; color:var(--ink); }

  #app{ position:relative; width:100%; height:100vh; }

  .page{
    position:absolute; inset:0;
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    opacity:0; pointer-events:none;
    transition:opacity .6s ease;
    padding:24px;
    text-align:center;
  }
  .page.active{ opacity:1; pointer-events:auto; }

  /* ---------- shared bg for pages 1 & 2 ---------- */
  .bg-pv{
    background:
      radial-gradient(circle at 20% 15%, rgba(255,255,255,.35), transparent 45%),
      linear-gradient(160deg, var(--pink) 0%, #d199f0 50%, var(--violet-deep) 100%);
  }

  .next-btn{
    margin-top:28px;
    border:none; cursor:pointer;
    padding:12px 30px;
    border-radius:999px;
    font-family:'Quicksand',sans-serif;
    font-weight:700;
    font-size:15px;
    letter-spacing:.3px;
    color:#fff;
    background:linear-gradient(120deg,var(--pink-deep),var(--violet-deep));
    box-shadow:0 6px 18px rgba(139,92,246,.35);
    transition:transform .15s ease, box-shadow .15s ease;
  }
  .next-btn:hover{ transform:translateY(-2px); box-shadow:0 10px 22px rgba(139,92,246,.45); }
  .next-btn:active{ transform:translateY(0px) scale(.97); }
  .next-btn::after{ content:" →"; }

  /* =========================================================
     PAGE 1 — calculator password lock
     ========================================================= */
  .calc{
    width:280px;
    background:rgba(255,255,255,.16);
    border:1px solid rgba(255,255,255,.35);
    border-radius:28px;
    padding:22px;
    backdrop-filter:blur(6px);
    box-shadow:0 20px 45px rgba(80,20,90,.25);
  }
  .calc-title{
    color:#fff; font-family:'Caveat',cursive; font-size:28px; margin:0 0 12px;
    text-shadow:0 2px 6px rgba(0,0,0,.15);
  }
  .calc-screen{
    background:rgba(255,255,255,.85);
    border-radius:16px;
    height:56px;
    display:flex; align-items:center; justify-content:flex-end;
    padding:0 18px;
    font-size:26px; letter-spacing:8px;
    color:var(--ink);
    margin-bottom:14px;
    font-weight:600;
    box-shadow:inset 0 2px 6px rgba(0,0,0,.15);
  }
  .calc-hint{ font-size:12px; color:rgba(255,255,255,.85); margin:-6px 0 14px; }
  .calc-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:10px;
  }
  .calc-key{
    border:none; cursor:pointer;
    height:52px; border-radius:14px;
    font-size:19px; font-weight:700;
    background:rgba(255,255,255,.9);
    color:var(--ink);
    box-shadow:0 4px 10px rgba(80,20,90,.18);
    transition:transform .1s ease, background .15s ease;
  }
  .calc-key:active{ transform:scale(.93); background:#fff; }
  .calc-key.wide{ grid-column:span 2; background:rgba(255,255,255,.55); color:#fff; }
  .calc-key.eq{ background:linear-gradient(120deg,var(--pink-deep),var(--violet-deep)); color:#fff; }
  .calc.shake{ animation:shake .45s; }
  @keyframes shake{
    10%,90%{ transform:translateX(-6px); }
    20%,80%{ transform:translateX(8px); }
    30%,50%,70%{ transform:translateX(-10px); }
    40%,60%{ transform:translateX(10px); }
  }
  .calc-error{ color:#fff; font-size:13px; height:16px; margin-top:8px; opacity:0; transition:opacity .2s; }
  .calc-error.show{ opacity:1; }

  /* =========================================================
     PAGE 2 — greeting / letter
     ========================================================= */
  .greet-title{
    font-family:'Caveat',cursive;
    font-weight:700;
    color:#fff;
    font-size:44px;
    text-shadow:0 3px 10px rgba(80,20,90,.35);
    min-height:60px;
    margin-bottom:6px;
  }
  .caret{ display:inline-block; width:3px; background:#fff; margin-left:2px; animation:blink 1s step-end infinite; }
  @keyframes blink{ 50%{ opacity:0; } }

  .envelope-wrap{
    margin-top:18px;
    display:flex; flex-direction:column; align-items:center;
    opacity:0; transform:translateY(10px);
    transition:opacity .6s ease, transform .6s ease;
  }
  .envelope-wrap.show{ opacity:1; transform:translateY(0); }
  .envelope-label{ color:#fff; font-size:13px; margin-bottom:8px; opacity:.9; }
  .heart-btn{
    font-size:54px; background:none; border:none; cursor:pointer;
    filter:drop-shadow(0 6px 10px rgba(80,20,90,.35));
    animation:pulse 1.6s ease-in-out infinite;
  }
  @keyframes pulse{ 0%,100%{ transform:scale(1);} 50%{ transform:scale(1.12);} }

  .letter-overlay{
    position:fixed; inset:0;
    background:rgba(60,20,70,.55);
    backdrop-filter:blur(3px);
    display:flex; align-items:center; justify-content:center;
    opacity:0; pointer-events:none;
    transition:opacity .35s ease;
    z-index:50;
    padding:20px;
  }
  .letter-overlay.show{ opacity:1; pointer-events:auto; }
  .letter-paper{
    background:linear-gradient(180deg,#fffafc,#fdf1f8);
    max-width:480px; width:100%;
    max-height:82vh;
    overflow-y:auto;
    border-radius:18px;
    padding:28px 26px 24px;
    box-shadow:0 25px 60px rgba(50,10,60,.4);
    position:relative;
    text-align:left;
    transform:scale(.9) translateY(10px);
    transition:transform .35s ease;
  }
  .letter-overlay.show .letter-paper{ transform:scale(1) translateY(0); }
  .letter-close{
    position:absolute; top:12px; right:14px;
    border:none; background:none; cursor:pointer;
    font-size:20px; color:var(--violet-deep);
  }
  .letter-body{
    font-size:15.5px; line-height:1.75;
    white-space:pre-wrap;
    color:#5b3466;
    min-height:220px;
  }
  .letter-body .type-caret{ background:var(--violet-deep); }

  /* =========================================================
     PAGE 3 — photo page
     ========================================================= */
  .page3{ background:#0b0b0f; color:#fff; }
  .p3-title{
    font-family:'Caveat',cursive;
    font-size:34px;
    font-weight:700;
    margin-bottom:20px;
    background:linear-gradient(120deg,#ff9ecb,#c084fc,#f472b6);
    -webkit-background-clip:text; background-clip:text; color:transparent;
    text-shadow:none;
  }
  .photo-frame{
    width:min(78vw,320px);
    aspect-ratio:5/4;
    border-radius:20px;
    background:linear-gradient(160deg,#2a2a35,#141418);
    border:3px solid rgba(255,255,255,.15);
    display:flex; align-items:center; justify-content:center;
    overflow:hidden;
    box-shadow:0 25px 60px rgba(0,0,0,.6);
    position:relative;
    z-index:2;
  }
  .photo-frame img{ width:100%; height:100%; object-fit:cover; display:none; }
  .photo-frame .placeholder{ font-size:13px; color:rgba(255,255,255,.5); padding:20px; line-height:1.6; }
  .heart-rain{ position:absolute; inset:0; overflow:hidden; pointer-events:none; z-index:1; }
  .heart-rain span{
    position:absolute; top:-10%;
    animation-name:fall; animation-timing-function:linear; animation-iteration-count:infinite;
    opacity:.85;
  }
  @keyframes fall{
    0%{ transform:translateY(-10vh) translateX(0) rotate(0deg); }
    100%{ transform:translateY(110vh) translateX(var(--drift,0px)) rotate(360deg); }
  }

  /* =========================================================
     PAGE 4 — firecrackers
     ========================================================= */
  .page4{ background:linear-gradient(180deg,#f3e6ff,#ecd9ff); }
  .p4-btn{
    border:none; cursor:pointer;
    padding:16px 34px;
    border-radius:999px;
    font-family:'Quicksand',sans-serif;
    font-weight:700; font-size:16px;
    color:#fff;
    background:linear-gradient(120deg,#f472b6,#a855f7);
    box-shadow:0 10px 26px rgba(168,85,247,.4);
    animation:float 2.2s ease-in-out infinite;
    z-index:3;
  }
  @keyframes float{ 0%,100%{ transform:translateY(0);} 50%{ transform:translateY(-8px);} }
  #fireCanvas{ position:absolute; inset:0; z-index:2; pointer-events:none; }
  .p4-text{
    position:relative; z-index:3;
    font-family:'Caveat',cursive;
    font-weight:700;
    font-size:30px;
    line-height:1.35;
    color:#7a2b8c;
    white-space:pre;
    opacity:0; transform:scale(.85);
    transition:opacity .5s ease, transform .5s ease;
    text-shadow:0 2px 10px rgba(255,255,255,.6);
  }
  .p4-text.show{ opacity:1; transform:scale(1); }
  .p4-hearts{ position:absolute; inset:0; overflow:hidden; pointer-events:none; z-index:1; }

  @media (prefers-reduced-motion: reduce){
    .heart-rain span, .p4-hearts span, .p4-btn, .heart-btn{ animation:none !important; }
  }
</style>
</head>
<body>

<div id="app">

  <!-- PAGE 1: calculator password -->
  <section class="page bg-pv active" id="page1">
    <div class="calc" id="calc">
      <p class="calc-title">Enter the secret code 💗</p>
      <div class="calc-screen" id="calcScreen">••••</div>
      <p class="calc-hint">hint: it's your favourite 4 digits</p>
      <div class="calc-grid" id="calcGrid">
        <button class="calc-key" data-k="1">1</button>
        <button class="calc-key" data-k="2">2</button>
        <button class="calc-key" data-k="3">3</button>
        <button class="calc-key" data-k="4">4</button>
        <button class="calc-key" data-k="5">5</button>
        <button class="calc-key" data-k="6">6</button>
        <button class="calc-key" data-k="7">7</button>
        <button class="calc-key" data-k="8">8</button>
        <button class="calc-key" data-k="9">9</button>
        <button class="calc-key wide" data-k="clear">Clear</button>
        <button class="calc-key" data-k="0">0</button>
        <button class="calc-key eq" data-k="enter">↵</button>
      </div>
      <p class="calc-error" id="calcError">Not quite — try again 🌸</p>
    </div>
  </section>

  <!-- PAGE 2: greeting + letter -->
  <section class="page bg-pv" id="page2">
    <h1 class="greet-title" id="typeTitle"></h1>
    <div class="envelope-wrap" id="envelopeWrap">
      <p class="envelope-label">tap the letter to open it</p>
      <button class="heart-btn" id="openLetterBtn">💌</button>
    </div>
    <button class="next-btn" id="next2">Next Page</button>
  </section>

  <div class="letter-overlay" id="letterOverlay">
    <div class="letter-paper">
      <button class="letter-close" id="closeLetterBtn">✕</button>
      <div class="letter-body" id="letterBody"></div>
    </div>
  </div>

  <!-- PAGE 3: photo -->
  <section class="page page3" id="page3">
    <div class="heart-rain" id="heartRain3"></div>
    <p class="p3-title">HAPPY💝 TEACHER'S ♥️DAY🌹</p>
    <div class="photo-frame" id="photoFrame">
      <img id="teacherPhoto" src="data:image/jpeg;base64,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" alt="Teacher photo" style="display:block;">
      
    </div>
    <button class="next-btn" id="next3">Next Page</button>
  </section>

  <!-- PAGE 4: firecrackers -->
  <section class="page page4" id="page4">
    <canvas id="fireCanvas"></canvas>
    <div class="p4-hearts" id="heartRain4"></div>
    <button class="p4-btn" id="fireBtn">Click me ✨</button>
    <p class="p4-text" id="p4Text">HAPPY 💝
                  TEACHERS 🌹
                                            DAY🫂
           JOHTI MAM💖</p>
  </section>

</div>

<script>
(function(){
  const pages = ['page1','page2','page3','page4'];
  function goTo(id){
    pages.forEach(p=>document.getElementById(p).classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }

  /* ---------------- PAGE 1: calculator password ---------------- */
  const PASSWORD = "1234";
  let entered = "";
  const calc = document.getElementById('calc');
  const screen = document.getElementById('calcScreen');
  const errEl = document.getElementById('calcError');

  function renderScreen(){
    screen.textContent = entered.length ? '•'.repeat(entered.length) : '••••';
  }

  document.getElementById('calcGrid').addEventListener('click', (e)=>{
    const btn = e.target.closest('.calc-key');
    if(!btn) return;
    const k = btn.dataset.k;
    errEl.classList.remove('show');
    if(k === 'clear'){
      entered = "";
      renderScreen();
      return;
    }
    if(k === 'enter'){
      if(entered === PASSWORD){
        startTypewriterTitle();
        goTo('page2');
      } else {
        calc.classList.remove('shake'); void calc.offsetWidth;
        calc.classList.add('shake');
        errEl.classList.add('show');
        entered = "";
        renderScreen();
      }
      return;
    }
    if(entered.length < 4){
      entered += k;
      renderScreen();
    }
  });
  renderScreen();

  /* ---------------- PAGE 2: typewriter greeting ---------------- */
  const titleText = "Happy Teacher's Day! 🌸✨🎉";
  const titleEl = document.getElementById('typeTitle');
  const envelopeWrap = document.getElementById('envelopeWrap');
  let titleStarted = false;

  function startTypewriterTitle(){
    if(titleStarted) return;
    titleStarted = true;
    titleEl.innerHTML = '<span class="caret">&nbsp;</span>';
    let i = 0;
    const speed = 55;
    function step(){
      if(i <= titleText.length){
        titleEl.innerHTML = titleText.slice(0,i) + '<span class="caret">&nbsp;</span>';
        i++;
        setTimeout(step, speed);
      } else {
        envelopeWrap.classList.add('show');
      }
    }
    step();
  }

  const letterLines = [
"Happy Teacher's Day! 🌸✨🎉",
"",
"Even though I've only been coming to your tuition for the past three weeks, I wanted to take a moment to tell you how truly grateful I am. 📚💛🙌",
"",
"I see how hard you work every single day and how early you wake up just to help build a better future for us. ⏰💪🌱",
"",
"Your dedication and passion for teaching are so inspiring to witness. 💡🔥🎓",
"",
"What I appreciate the most is your wonderful, kind nature and the incredible patience you always show us. 💖😊🛡️",
"",
"You never scold us, and you always create such a calm and positive space to learn. 🌿🕊️📖",
"",
"Most importantly, thank you for treating and respecting all of us equally like adults, which makes us feel so valued and trusted in your class. 🤝👑🌟",
"",
"You are an amazing mentor, a truly hardworking teacher, and a wonderful guide. 🧭🏆💼",
"",
"Wishing you a joyful, relaxing, and wonderful Teacher's Day! 🍰💐🎈"
  ].join("\n");

  const letterOverlay = document.getElementById('letterOverlay');
  const letterBody = document.getElementById('letterBody');
  let letterTyped = false;

  function openLetter(){
    letterOverlay.classList.add('show');
    if(letterTyped){ letterBody.textContent = letterLines; return; }
    letterTyped = true;
    letterBody.innerHTML = '<span class="caret type-caret">&nbsp;</span>';
    let i = 0;
    const speed = 12;
    function step(){
      if(i <= letterLines.length){
        letterBody.innerHTML = letterLines.slice(0,i).replace(/\n/g,'<br>') + '<span class="caret type-caret">&nbsp;</span>';
        i += 2;
        setTimeout(step, speed);
      }
    }
    step();
  }

  document.getElementById('openLetterBtn').addEventListener('click', openLetter);
  document.getElementById('closeLetterBtn').addEventListener('click', ()=>{
    letterOverlay.classList.remove('show');
  });
  letterOverlay.addEventListener('click', (e)=>{
    if(e.target === letterOverlay) letterOverlay.classList.remove('show');
  });

  document.getElementById('next2').addEventListener('click', ()=> goTo('page3'));
  document.getElementById('next3').addEventListener('click', ()=> goTo('page4'));

  /* ---------------- PAGE 3: heart rain ---------------- */
  function buildHeartRain(container, count, opts){
    opts = opts || {};
    const emojis = opts.emojis || ['💗','💖','💕','💓'];
    const minSize = opts.minSize || 12;
    const maxSize = opts.maxSize || 22;
    const color = opts.color;
    for(let i=0;i<count;i++){
      const s = document.createElement('span');
      s.textContent = emojis[Math.floor(Math.random()*emojis.length)];
      const left = Math.random()*100;
      const size = minSize + Math.random()*(maxSize-minSize);
      const dur = 5 + Math.random()*6;
      const delay = Math.random()*8;
      const drift = (Math.random()*80 - 40) + 'px';
      s.style.left = left + '%';
      s.style.fontSize = size + 'px';
      s.style.setProperty('--drift', drift);
      s.style.animationDuration = dur + 's';
      s.style.animationDelay = '-' + delay + 's';
      if(color) s.style.filter = 'none';
      container.appendChild(s);
    }
  }
  buildHeartRain(document.getElementById('heartRain3'), 26, {emojis:['💗','💖','💕'], minSize:10, maxSize:20});

  /* page 4 heart rain — small red hearts */
  buildHeartRain(document.getElementById('heartRain4'), 40, {emojis:['❤️','♥️'], minSize:8, maxSize:14});

  /* ---------------- PAGE 4: firecrackers ---------------- */
  const canvas = document.getElementById('fireCanvas');
  const ctx = canvas.getContext('2d');
  let particles = [];
  let animId = null;

  function resizeCanvas(){
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  }
  window.addEventListener('resize', resizeCanvas);
  resizeCanvas();

  const fireColors = ['#ff5da2','#ffd166','#8b5cf6','#4cc9f0','#ff9f1c','#f72585','#7bdff2','#c77dff'];

  function spawnBurst(x,y){
    const count = 45;
    const color = fireColors[Math.floor(Math.random()*fireColors.length)];
    for(let i=0;i<count;i++){
      const angle = (Math.PI*2*i)/count + Math.random()*0.2;
      const speed = 2 + Math.random()*4;
      particles.push({
        x, y,
        vx: Math.cos(angle)*speed,
        vy: Math.sin(angle)*speed,
        life: 60 + Math.random()*20,
        age: 0,
        color: Math.random() < 0.3 ? fireColors[Math.floor(Math.random()*fireColors.length)] : color,
        size: 2 + Math.random()*2
      });
    }
  }

  function animate(){
    ctx.clearRect(0,0,canvas.width,canvas.height);
    particles.forEach(p=>{
      p.x += p.vx;
      p.y += p.vy;
      p.vy += 0.045; // gravity
      p.age++;
      const alpha = Math.max(0, 1 - p.age/p.life);
      ctx.globalAlpha = alpha;
      ctx.fillStyle = p.color;
      ctx.beginPath();
      ctx.arc(p.x, p.y, p.size, 0, Math.PI*2);
      ctx.fill();
    });
    ctx.globalAlpha = 1;
    particles = particles.filter(p => p.age < p.life);
    animId = requestAnimationFrame(animate);
  }
  animate();

  function randomBurstsSequence(){
    const spots = 6;
    for(let i=0;i<spots;i++){
      setTimeout(()=>{
        const x = canvas.width * (0.15 + Math.random()*0.7);
        const y = canvas.height * (0.15 + Math.random()*0.45);
        spawnBurst(x,y);
      }, i*260);
    }
  }

  const fireBtn = document.getElementById('fireBtn');
  const p4Text = document.getElementById('p4Text');
  let fired = false;
  fireBtn.addEventListener('click', ()=>{
    randomBurstsSequence();
    if(!fired){
      fired = true;
      setTimeout(()=> p4Text.classList.add('show'), 350);
      // keep celebrating gently
      let bursts = 0;
      const keepGoing = setInterval(()=>{
        randomBurstsSequence();
        bursts++;
        if(bursts > 4) clearInterval(keepGoing);
      }, 1700);
    }
  });

})();
</script>

</body>
</html>
