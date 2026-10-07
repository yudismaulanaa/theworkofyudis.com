[index.html](https://github.com/user-attachments/files/33148463/index.html)
<!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1,viewport-fit=cover"><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#faf9f5;color:#141413}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body>
<title>Yudis Maulana</title>
<meta name="description" content="Videographer, video editor, AI video editor, motion graphic designer and scriptwriter from Indonesia.">
<style>
@font-face{font-family:"Plus Jakarta Sans Local";src:url("fonts/PlusJakartaSans.ttf") format("truetype");font-weight:200 800;font-style:normal;font-display:swap}
@font-face{font-family:"Plus Jakarta Sans Local";src:url("fonts/PlusJakartaSans-Italic.ttf") format("truetype");font-weight:200 800;font-style:italic;font-display:swap}
/* Layout: a clay toy studio. Candy-coloured slabs sit on a periwinkle table; every section is a "scene" on a film slate. */
:root{
  --table:#E9ECFF;      /* periwinkle ground */
  --grad-a:#E6EAFF;     /* gradient stops: periwinkle → lilac → powder blue, kept close in hue */
  --grad-b:#EDE3FF;
  --grad-c:#DDEBFF;
  --table-2:#DCE1FF;
  --ink:#241638;        /* deep grape ink */
  --ink-2:#5A4C74;
  --paper:#FFFBF4;
  --tangerine:#FF6B3D;
  --sun:#FFC93C;
  --bubble:#FF8CC0;
  --mint:#59D6A1;
  --sky:#5DB4FF;
  --grape:#9C7BFF;
  --grape-soft:#C9B8FF;
  --night:#231536;
  --night-2:#33234D;
  --f-display:"Plus Jakarta Sans Local","Plus Jakarta Sans",system-ui,-apple-system,"Segoe UI",sans-serif;
  --f-body:"Plus Jakarta Sans Local","Plus Jakarta Sans",system-ui,-apple-system,"Segoe UI",sans-serif;
  --f-mono:"Plus Jakarta Sans Local","Plus Jakarta Sans",system-ui,sans-serif;
  --clay-hi:inset 0 6px 10px rgba(255,255,255,.55);
  --clay-lo:inset 0 -10px 18px rgba(30,10,60,.16);
  --clay-drop:0 22px 40px -20px rgba(36,22,56,.55), 0 3px 0 rgba(36,22,56,.05);
  --gutter:clamp(16px,3vw,40px);
  color-scheme:light;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
html{background:var(--grad-a)}
body{margin:0;background-color:var(--table);color:var(--ink);font-family:var(--f-body);font-size:16px;line-height:1.6;overflow-x:hidden;
  background-image:radial-gradient(circle at 1px 1px, rgba(36,22,56,.06) 1px, transparent 0),linear-gradient(165deg,var(--grad-a) 0%,var(--grad-b) 38%,var(--grad-c) 70%,var(--grad-b) 100%);
  background-size:22px 22px,100% 100%;min-height:100vh}
img{max-width:100%;display:block}
a{color:inherit}
h1,h2,h3{font-family:var(--f-display);font-weight:700;line-height:1.05;margin:0;text-wrap:balance;letter-spacing:-.025em}
p{margin:0}
.wrap{max-width:1480px;margin:0 auto;padding-inline:var(--gutter)}
:focus-visible{outline:3px solid var(--grape);outline-offset:3px;border-radius:12px}

/* ---------- clay primitives ---------- */
.clay{background:var(--c,var(--paper));border-radius:var(--r,28px);box-shadow:var(--clay-hi),var(--clay-lo),var(--clay-drop)}
.eyebrow{font-family:var(--f-mono);font-size:.74rem;font-weight:700;letter-spacing:.14em;text-transform:uppercase;color:var(--ink-2);display:flex;gap:.6em;align-items:center;flex-wrap:wrap}
.eyebrow .slate{background:var(--ink);color:var(--paper);padding:.28em .7em;border-radius:8px;letter-spacing:.08em}
.sec-head{display:flex;justify-content:space-between;align-items:flex-end;gap:16px 32px;flex-wrap:wrap;margin-bottom:clamp(24px,4vw,44px)}
.sec-head h2{font-size:clamp(2.2rem,5.4vw,4rem);margin-top:.35em}
.sec-head .aside{max-width:36ch;color:var(--ink-2)}
section{position:relative;padding-block:clamp(56px,9vw,120px)}

.btn{display:inline-flex;align-items:center;gap:.55em;font-family:var(--f-display);font-weight:600;font-size:1.05rem;text-decoration:none;color:var(--ink);
  padding:.8em 1.35em;border-radius:999px;border:0;cursor:pointer;background:var(--c,var(--sun));
  box-shadow:var(--clay-hi),var(--clay-lo),0 12px 22px -10px rgba(36,22,56,.5);transition:transform .25s cubic-bezier(.3,1.6,.5,1),box-shadow .2s}
.btn:hover{transform:translateY(-3px) scale(1.03)}
.btn:active{transform:translateY(1px) scale(.97);box-shadow:inset 0 6px 12px rgba(30,10,60,.25),0 4px 8px -6px rgba(36,22,56,.4)}
.btn svg{width:1.1em;height:1.1em}
.chip{display:inline-flex;align-items:center;gap:.4em;font-weight:600;font-size:.86rem;padding:.45em .9em;border-radius:999px;background:var(--c,var(--paper));
  box-shadow:var(--clay-hi),inset 0 -5px 8px rgba(30,10,60,.12),0 8px 14px -8px rgba(36,22,56,.45);text-decoration:none;color:var(--ink);transition:transform .2s}

/* ---------- toys (cursor-reactive clay objects) ---------- */
.toy{position:absolute;left:var(--x);top:var(--y);width:var(--w);height:auto;cursor:grab;user-select:none;-webkit-user-drag:none;z-index:3;
  filter:drop-shadow(0 18px 14px rgba(36,22,56,.28));will-change:transform;touch-action:manipulation}
.toy:active{cursor:grabbing}

/* ---------- flying paper planes ---------- */
.sky{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:0}
main,.nav{position:relative;z-index:1}
.nav{position:sticky;z-index:50}


/* ---------- CSS-built clay film props (also .toy) ---------- */
div.toy{pointer-events:auto}
.filmstrip{aspect-ratio:3/1.15;border-radius:16px;background:#2E2140;padding:calc(var(--w) * .1) calc(var(--w) * .05);display:flex;column-gap:5%;align-items:stretch;
  box-shadow:inset 0 5px 8px rgba(255,255,255,.18),inset 0 -8px 12px rgba(0,0,0,.45);
  background-image:radial-gradient(circle,#E9ECFF 0 38%,transparent 42%),radial-gradient(circle,#E9ECFF 0 38%,transparent 42%);
  background-size:12% 16%;background-repeat:repeat-x;background-position:4% 18%,4% 82%}
.filmstrip i{flex:1;border-radius:7px;box-shadow:inset 0 3px 5px rgba(255,255,255,.55),inset 0 -4px 6px rgba(30,10,60,.25)}
.filmstrip i:nth-child(1){background:var(--sky)}.filmstrip i:nth-child(2){background:var(--bubble)}.filmstrip i:nth-child(3){background:var(--sun)}
.ticket{aspect-ratio:2.1/1;border-radius:14px;background:var(--sun);display:grid;place-items:center;font-family:var(--f-display);font-weight:800;color:var(--ink);font-size:clamp(.7rem,1.3vw,1rem);letter-spacing:.06em;text-align:center;line-height:1.05;
  -webkit-mask:radial-gradient(circle at 0 50%,transparent 13%,#000 14%) left/51% 100% no-repeat,radial-gradient(circle at 100% 50%,transparent 13%,#000 14%) right/51% 100% no-repeat;
          mask:radial-gradient(circle at 0 50%,transparent 13%,#000 14%) left/51% 100% no-repeat,radial-gradient(circle at 100% 50%,transparent 13%,#000 14%) right/51% 100% no-repeat;
  box-shadow:inset 0 6px 8px rgba(255,255,255,.6),inset 0 -8px 12px rgba(150,90,0,.35)}
.ticket small{display:block;font-family:var(--f-mono);font-size:.6em;font-weight:700;letter-spacing:.14em;opacity:.7;margin-top:3px}
.rec-btn{aspect-ratio:2.3/1;border-radius:999px;background:var(--tangerine);display:flex;align-items:center;justify-content:center;gap:10%;color:#fff;font-family:var(--f-display);font-weight:800;font-size:clamp(.8rem,1.4vw,1.1rem);letter-spacing:.08em;
  box-shadow:inset 0 6px 8px rgba(255,255,255,.5),inset 0 -8px 12px rgba(120,20,0,.35)}
.rec-btn::before{content:"";width:22%;aspect-ratio:1;border-radius:50%;background:#fff;box-shadow:inset 0 -3px 4px rgba(200,16,46,.5);animation:blink 1.2s steps(2) infinite}
.lens{aspect-ratio:1;border-radius:50%;background:radial-gradient(circle at 35% 30%,rgba(255,255,255,.75) 0 7%,transparent 8%),radial-gradient(circle,#5DB4FF 0 16%,#2B1E44 17% 30%,#3C2C5C 31% 44%,#1F152F 45% 58%,#6A5A86 59% 64%,#2B1E44 65%);
  box-shadow:inset 0 6px 10px rgba(255,255,255,.35),inset 0 -10px 16px rgba(0,0,0,.45)}

/* ---------- cursor follower ---------- */
.cursor{position:fixed;left:0;top:0;width:22px;height:22px;margin:-11px 0 0 -11px;border-radius:50%;pointer-events:none;z-index:999;
  background:var(--bubble);box-shadow:inset 0 3px 4px rgba(255,255,255,.6),inset 0 -4px 6px rgba(30,10,60,.25),0 6px 10px -4px rgba(36,22,56,.5);
  transition:width .25s,height .25s,margin .25s,background .25s,opacity .3s;opacity:0}
.cursor.on{opacity:1}
.cursor.big{width:54px;height:54px;margin:-27px 0 0 -27px;background:rgba(255,201,60,.55)}

/* ---------- nav ---------- */
.nav{position:sticky;top:calc(env(safe-area-inset-top,0px) + 12px);z-index:50;padding-inline:var(--gutter)}
.nav-in{max-width:1480px;margin:0 auto;display:flex;align-items:center;gap:8px;padding:8px 8px 8px 10px;--c:rgba(255,251,244,.86);--r:999px;backdrop-filter:blur(10px)}
.logo{width:44px;height:44px;border-radius:50%;padding:3px;display:block;--c:var(--sun);flex:none;transition:transform .35s cubic-bezier(.3,1.7,.5,1)}
.logo img{width:100%;height:100%;border-radius:50%;object-fit:cover}
.logo:hover{transform:rotate(-10deg) scale(1.1)}
.nav-links{position:relative;display:flex;gap:2px;margin-left:8px;flex:1;min-width:0;overflow-x:auto;scrollbar-width:none}
.nav-links::-webkit-scrollbar{display:none}
.nav-links a{position:relative;z-index:1;font-weight:600;font-size:.92rem;text-decoration:none;padding:.5em .85em;border-radius:999px;white-space:nowrap;color:var(--ink-2);transition:color .3s}
.nav-links a:hover{color:var(--ink)}
.nav-links a.active{color:var(--ink);font-weight:700}
.nav-links a{display:inline-flex;align-items:center;gap:6px}
.nav-links .ic{display:none;width:18px;height:18px;flex:none}
.nav-pill{position:absolute;z-index:0;top:50%;left:0;height:2.3em;width:0;border-radius:999px;background:var(--pill,var(--sun));opacity:0;
  transform:translate(var(--px,0),-50%);transition:transform .45s cubic-bezier(.3,1.4,.5,1),width .45s cubic-bezier(.3,1.4,.5,1),background .35s,opacity .3s;
  box-shadow:inset 0 3px 5px rgba(255,255,255,.6),inset 0 -4px 6px rgba(30,10,60,.18),0 6px 10px -6px rgba(36,22,56,.5)}
.nav-pill.on{opacity:1}
.nav-now{display:none;align-items:center;gap:6px;font-weight:700;font-size:.88rem;padding:.45em .9em;border-radius:999px;background:var(--pill,var(--sun));box-shadow:inset 0 3px 5px rgba(255,255,255,.6),inset 0 -4px 6px rgba(30,10,60,.18);transition:background .35s}
.nav-now::before{content:"";width:7px;height:7px;border-radius:50%;background:var(--ink)}
.nav-now[hidden]{display:none!important}
.nav .btn{font-size:.92rem;padding:.6em 1.05em;--c:var(--sky);flex:none}

/* ---------- hero ---------- */
.hero{padding-block:clamp(32px,6vw,72px) clamp(48px,8vw,96px)}
.hero-grid{display:grid;grid-template-columns:1.05fr 1fr;gap:clamp(24px,4vw,56px);align-items:center}
.hero-copy{min-width:0}
.roles{display:flex;flex-wrap:wrap;gap:8px;margin-top:22px}
.roles .chip:nth-child(1){--c:var(--sun)}.roles .chip:nth-child(2){--c:var(--bubble)}.roles .chip:nth-child(3){--c:var(--mint)}.roles .chip:nth-child(4){--c:var(--sky)}.roles .chip:nth-child(5){--c:#C9B8FF}
.big-hi{font-size:clamp(3.2rem,10vw,7.8rem);font-weight:800;line-height:.95;letter-spacing:-.045em}
.big-hi .line{display:block;white-space:nowrap}
.ch{display:inline-block;transform-origin:50% 90%;cursor:default}
.ch.sp{width:.28em}
.clayword .ch{color:var(--c);text-shadow:0 2px 0 rgba(255,255,255,.35),0 7px 0 color-mix(in srgb,var(--c) 72%,#241638),0 18px 22px rgba(36,22,56,.22)}
.ch.boing{animation:boing .75s cubic-bezier(.3,1.4,.5,1)}
@keyframes boing{0%{transform:none}22%{transform:translateY(6px) scale(1.22,.78)}48%{transform:translateY(-26px) scale(.86,1.16) rotate(-6deg)}70%{transform:translateY(0) scale(1.08,.93)}86%{transform:scale(.97,1.03)}100%{transform:none}}
.hero-lede{font-size:clamp(1.05rem,1.6vw,1.22rem);max-width:46ch;margin-top:26px;color:var(--ink-2)}
.hero-lede b{color:var(--ink)}
.hero-cta{display:flex;gap:12px;flex-wrap:wrap;margin-top:28px}
.trusted{margin-top:22px;display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.trusted > span{font-family:var(--f-mono);font-size:.7rem;font-weight:800;letter-spacing:.12em;text-transform:uppercase;color:var(--ink-2)}
.trusted-logos{display:flex;gap:8px;flex-wrap:wrap}
.trusted-logos span{width:78px;aspect-ratio:215/117;padding:4px;--r:14px;transition:transform .35s cubic-bezier(.3,1.7,.5,1)}
.trusted-logos span:hover{transform:translateY(-5px) rotate(-5deg) scale(1.1)}
.trusted-logos img{width:100%;height:100%;object-fit:cover;border-radius:10px}
.hint{margin-top:26px;font-family:var(--f-mono);font-size:.75rem;letter-spacing:.08em;color:var(--ink-2);display:flex;align-items:center;gap:10px}
.hint i{width:28px;height:28px;border-radius:50%;--c:var(--mint);display:inline-grid;place-items:center;font-style:normal;animation:nudge 2.4s ease-in-out infinite}
@keyframes nudge{0%,100%{transform:translate(0,0)}50%{transform:translate(6px,-4px)}}
.stage{position:relative;width:100%;max-width:660px;aspect-ratio:1/1;margin-inline:auto}
.blob{position:absolute;inset:8% 6% 6% 8%;border-radius:46% 54% 42% 58%/52% 44% 56% 48%;--c:var(--sun);animation:morph 14s ease-in-out infinite}
@keyframes morph{50%{border-radius:58% 42% 55% 45%/42% 58% 42% 58%}}
.portrait{position:absolute;left:24%;top:16%;width:52%;aspect-ratio:220/300;padding:3.2%;--c:var(--paper);--r:30px;transform:perspective(900px) rotate(-4deg) rotateX(var(--rx,0)) rotateY(var(--ry,0));transition:transform .5s cubic-bezier(.2,1.4,.4,1);z-index:2}
.portrait img{width:100%;height:100%;object-fit:cover;border-radius:20px}
.stat{position:absolute;z-index:4;padding:.6em 1em;--r:20px;font-family:var(--f-display);line-height:1.05;pointer-events:none}
.stat b{display:block;font-size:1.7rem}
.stat span{font-family:var(--f-body);font-size:.74rem;font-weight:600}

/* ---------- showreel ---------- */
.reel{background:var(--night);color:var(--paper);border-radius:clamp(28px,5vw,56px);margin-inline:var(--gutter);max-width:1600px}
@media (min-width:1680px){.reel{margin-inline:auto}}
.reel .eyebrow{color:#C9BDE6}
.reel .eyebrow .slate{background:var(--sun);color:var(--ink)}
.reel .sec-head .aside{color:#C9BDE6}
.tv{position:relative;--c:var(--tangerine);--r:clamp(28px,4vw,48px);padding:clamp(12px,2vw,22px) clamp(12px,2vw,22px) clamp(44px,5vw,64px)}
.tv-screen{position:relative;border-radius:clamp(18px,2.6vw,30px);overflow:hidden;background:#000;aspect-ratio:16/9;box-shadow:inset 0 0 0 4px rgba(0,0,0,.25)}
.tv video{width:100%;height:100%;display:block;object-fit:cover}
.tv-play{position:absolute;inset:0;display:grid;place-items:center;background:linear-gradient(transparent 40%,rgba(20,8,40,.55));border:0;cursor:pointer;color:var(--paper);font:inherit}
.tv-play span{display:grid;place-items:center;width:clamp(72px,10vw,112px);aspect-ratio:1;border-radius:50%;background:var(--sun);color:var(--ink);box-shadow:var(--clay-hi),var(--clay-lo),0 18px 30px -10px rgba(0,0,0,.6);transition:transform .3s cubic-bezier(.3,1.6,.5,1)}
.tv-play:hover span{transform:scale(1.12) rotate(-6deg)}
.tv-play svg{width:38%;margin-left:8%}
.tv-bar{position:absolute;left:clamp(16px,2.4vw,30px);right:clamp(16px,2.4vw,30px);bottom:clamp(12px,1.6vw,20px);display:flex;align-items:center;justify-content:space-between;gap:10px;font-family:var(--f-mono);font-size:.74rem;font-weight:700;color:var(--ink)}
.knobs{display:flex;gap:10px}
.knobs i{width:22px;height:22px;border-radius:50%;background:var(--sun);box-shadow:var(--clay-hi),inset 0 -4px 6px rgba(30,10,60,.25)}
.knobs i:nth-child(2){background:var(--sky)}
.rec{display:flex;align-items:center;gap:6px;min-width:0;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}.rec::before{content:"";width:9px;height:9px;border-radius:50%;background:#C8102E;animation:blink 1.2s steps(2) infinite}
@keyframes blink{50%{opacity:.2}}
.reel-grid{display:grid;grid-template-columns:1fr;gap:28px}

/* ---------- capabilities ---------- */
.caps{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:clamp(12px,2vw,22px)}
.cap{position:relative;padding:22px 22px 24px;min-height:220px;display:flex;flex-direction:column;justify-content:flex-end;--r:30px;
  transform:perspective(800px) rotateX(var(--rx,0)) rotateY(var(--ry,0)) translateY(var(--lift,0));transition:transform .45s cubic-bezier(.2,1.4,.4,1)}
.cap:hover{--lift:-6px}
.cap .num{position:absolute;top:18px;left:22px;font-family:var(--f-mono);font-size:.75rem;font-weight:700;opacity:.7}
.cap h3,.cap p{position:relative;z-index:1}
.cap img{position:absolute;right:12px;top:8px;width:38%;max-width:112px;filter:drop-shadow(0 12px 10px rgba(36,22,56,.25));transition:transform .55s cubic-bezier(.3,1.7,.5,1)}
.cap:hover img{transform:translateY(-14px) rotate(-12deg) scale(1.12)}
.cap h3{font-size:1.45rem}
.cap p{font-size:.88rem;margin-top:6px;color:color-mix(in srgb,var(--ink) 80%,transparent)}
.cap.statement{--c:var(--ink);color:var(--paper);justify-content:space-between}
.cap.statement h3{font-size:1.4rem;line-height:1.15}
.cap.statement p{color:var(--sun);font-weight:600}

/* ---------- brands marquee ---------- */
.brands{padding-block:0 clamp(40px,6vw,80px)}
.marquee{overflow:hidden;padding-block:30px 64px;margin-bottom:-34px;-webkit-mask-image:linear-gradient(90deg,transparent,#000 8%,#000 92%,transparent);mask-image:linear-gradient(90deg,transparent,#000 8%,#000 92%,transparent)}
.track{display:flex;gap:22px;width:max-content;animation:slide 38s linear infinite}
.track.rev{animation-direction:reverse;animation-duration:44s}
.tool-card{width:150px;flex:none;--r:24px;padding:16px 10px 12px;display:flex;flex-direction:column;align-items:center;gap:10px;transition:transform .35s cubic-bezier(.3,1.6,.5,1)}
.tool-card:hover{transform:translateY(-8px) rotate(3deg) scale(1.06)}
.tool-card .ic{width:64px;height:64px;border-radius:18px;display:grid;place-items:center;background:var(--tc);box-shadow:var(--clay-hi),inset 0 -6px 10px rgba(30,10,60,.22),0 10px 16px -8px rgba(36,22,56,.5)}
.tool-card .ic svg{width:34px;height:34px;fill:#fff}
.tool-card .ic b{font-family:var(--f-display);font-weight:800;font-size:1.3rem;color:#fff;letter-spacing:-.03em}
.tool-card span{font-weight:700;font-size:.8rem;text-align:center;line-height:1.2}
.tool-card small{display:block;font-family:var(--f-mono);font-size:.62rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--ink-2);margin-top:2px}
.toolkit{margin-top:clamp(48px,7vw,80px)}
.toolkit .wrap{margin-bottom:-6px}
.marquee:hover .track{animation-play-state:paused}
@keyframes slide{to{transform:translateX(-50%)}}
.logo-card{width:200px;flex:none;--r:24px;padding:8px;transition:transform .35s cubic-bezier(.3,1.6,.5,1)}
.logo-card:hover{transform:translateY(-8px) rotate(-3deg) scale(1.05)}
.logo-card img{border-radius:16px;width:100%;aspect-ratio:215/117;object-fit:cover}
.logo-card span{display:block;text-align:center;font-weight:700;font-size:.82rem;padding:8px 0 2px}

/* ---------- work ---------- */
.feature{display:block;padding:clamp(20px,3vw,36px);--c:var(--sky);--r:clamp(28px,4vw,44px)}
.feature > *{min-width:0}
.feature-top{display:grid;grid-template-columns:1fr 1fr;gap:clamp(20px,3vw,40px);align-items:center}
.feature-top > *{min-width:0}
.cats{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:clamp(14px,2vw,20px);margin-top:clamp(20px,3vw,32px)}
.cat{--c:rgba(255,255,255,.62);--r:26px;padding:14px;display:flex;flex-direction:column;gap:12px;min-width:0}
.cat-head{display:flex;align-items:center;gap:10px;flex-wrap:wrap;padding:2px 4px 0}
.cat-no{font-family:var(--f-mono);font-size:.72rem;font-weight:800;background:var(--ink);color:var(--paper);padding:.25em .55em;border-radius:8px}
.cat h4{margin:0;font-family:var(--f-display);font-weight:700;font-size:1.2rem;letter-spacing:-.02em}
.cat-head small{margin-left:auto;font-size:.74rem;font-weight:600;color:var(--ink-2)}
.cat-body{display:flex;flex-direction:column;gap:12px}
.cat-img{border-radius:18px;overflow:hidden;background:var(--paper);padding:6px;box-shadow:inset 0 3px 5px rgba(255,255,255,.7),0 10px 18px -12px rgba(36,22,56,.5)}
.cat-img img{width:100%;height:auto;border-radius:13px}
.cat-links{display:flex;gap:10px;align-items:flex-start}
.cat-links .watch{font-family:var(--f-mono);font-size:.68rem;font-weight:800;letter-spacing:.1em;text-transform:uppercase;padding-top:8px;flex:none}
.cat-links .dots{flex:1;min-width:0}
.cat-links .btn{--c:var(--paper);font-size:.88rem}
.dot.wide{background:var(--paper);padding:0 10px}
.cat.wide{grid-column:1/-1}
.cat.wide .cat-body{display:grid;grid-template-columns:1.4fr 1fr;align-items:center}
.cat.wide .cat-links .dots{flex-direction:column;align-items:flex-start;gap:10px}
.feature .tag{display:inline-flex;gap:6px;flex-wrap:wrap;margin:14px 0 18px}
.feature .tag .chip{--c:var(--paper);font-size:.78rem}
.feature h3{font-size:clamp(2.2rem,4.4vw,3.4rem)}
.co-logo{width:clamp(120px,13vw,160px);height:auto;aspect-ratio:215/117;border-radius:20px;--c:var(--paper);padding:6px;display:grid;place-items:center;margin-bottom:16px}
.co-logo img{border-radius:14px;object-fit:cover;width:100%;height:100%}
.shot{border-radius:24px;overflow:hidden;--c:var(--paper);padding:8px}
.shot img{border-radius:18px;width:100%}
.reelsets{display:grid;gap:14px;margin-top:18px}
.set{--c:rgba(255,255,255,.55);--r:22px;padding:14px 16px}
.set h4{margin:0 0 8px;font-family:var(--f-display);font-weight:600;font-size:1.08rem;display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap}
.set h4 small{font-family:var(--f-mono);font-size:.7rem;font-weight:700;opacity:.7;align-self:center}
.dots{display:flex;flex-wrap:wrap;gap:6px}
.dot{display:inline-grid;place-items:center;min-width:34px;height:30px;padding:0 6px;border-radius:12px;background:var(--sun);font-family:var(--f-mono);font-size:.72rem;font-weight:700;text-decoration:none;color:var(--ink);
  box-shadow:inset 0 3px 4px rgba(255,255,255,.55),inset 0 -4px 6px rgba(30,10,60,.18),0 5px 8px -5px rgba(36,22,56,.5);transition:transform .25s cubic-bezier(.3,1.8,.5,1)}
.dot:hover{transform:translateY(-4px) scale(1.15) rotate(-6deg);background:var(--bubble)}
details.set summary{cursor:pointer;list-style:none}
details.set summary::-webkit-details-marker{display:none}
details.set summary h4::after{content:"Show all ▾";font-family:var(--f-mono);font-size:.7rem;font-weight:700;background:var(--paper);padding:.2em .6em;border-radius:8px}
details.set[open] summary h4::after{content:"Hide ▴"}
.feature-media{display:grid;gap:14px;align-content:start}
.duo{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.social{display:flex;gap:10px;flex-wrap:wrap;margin-top:16px}
.social .btn{--c:var(--paper);font-size:.92rem}

.jobs{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:clamp(14px,2vw,24px);margin-top:clamp(18px,3vw,28px)}
.job{grid-column:span 1;display:flex;flex-direction:column;padding:16px 16px 20px;--r:32px;transform:perspective(900px) rotateX(var(--rx,0)) rotateY(var(--ry,0)) translateY(var(--lift,0));transition:transform .45s cubic-bezier(.2,1.4,.4,1)}
.job:nth-child(5){grid-column:1/-1;display:grid;grid-template-columns:1.25fr 1fr;column-gap:clamp(18px,3vw,36px);align-items:center}
.job:nth-child(5) .shot{grid-row:1/span 6;margin-bottom:48px}
.job:nth-child(5) .links{margin-top:0}
.job:hover{--lift:-6px}
.job .shot{margin-bottom:56px;padding:6px;position:relative;overflow:visible}
.job .logos{position:absolute;left:16px;bottom:-42px;display:flex;gap:10px;z-index:2}
.job .logos .co-logo{width:clamp(110px,12vw,150px);height:auto;aspect-ratio:215/117;padding:6px;margin:0;border-radius:20px;transition:transform .35s cubic-bezier(.3,1.7,.5,1)}
.job:hover .logos .co-logo{transform:rotate(-8deg) scale(1.08)}
.job .shot img{width:100%;height:auto;border-radius:18px}
.job .kind{font-family:var(--f-mono);font-size:.7rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;opacity:.75}
.job h3{font-size:1.7rem;margin:.2em 0 .35em}
.job p{font-size:.92rem}
.job .links{display:flex;flex-wrap:wrap;gap:6px;margin-top:auto;padding-top:14px}
.job .links .chip{--c:var(--paper);font-size:.78rem}
.job .links .chip:hover{transform:translateY(-3px)}

/* ---------- films ---------- */
.films{background:var(--night);color:var(--paper);border-radius:clamp(28px,5vw,56px);margin-inline:var(--gutter);max-width:1600px}
@media (min-width:1680px){.films{margin-inline:auto}}
.films .eyebrow{color:#C9BDE6}
.films .eyebrow .slate{background:var(--bubble);color:var(--ink)}
.films .sec-head .aside{color:#C9BDE6}
.feat{display:grid;grid-template-columns:.85fr 1.4fr;gap:clamp(18px,3vw,40px);align-items:center;padding:clamp(16px,2.4vw,28px);--c:var(--night-2);--r:clamp(26px,3.6vw,40px);
  box-shadow:inset 0 5px 10px rgba(255,255,255,.08),inset 0 -10px 18px rgba(0,0,0,.35),0 30px 50px -26px rgba(0,0,0,.8)}
.feat + .feat{margin-top:clamp(18px,3vw,28px)}
.feat > *{min-width:0}
.feat:nth-child(even){grid-template-columns:1.4fr .85fr}
.feat:nth-child(even) .feat-text{order:2}
.year{display:inline-block;font-family:var(--f-mono);font-weight:700;font-size:.8rem;padding:.3em .8em;border-radius:999px;background:var(--sun);color:var(--ink);box-shadow:var(--clay-hi),inset 0 -4px 6px rgba(30,10,60,.2)}
.feat h3{font-size:clamp(2rem,4vw,3.1rem);margin:.4em 0 .3em}
.feat .role{color:#C9BDE6;font-weight:500}
.feat .syn{margin-top:14px;color:#E6DEF7;font-size:.95rem;max-width:44ch}
.feat .btn{margin-top:20px;--c:var(--tangerine)}
.laurels{display:flex;flex-wrap:wrap;gap:6px;margin-top:16px}
.laurels span{font-size:.72rem;font-weight:600;padding:.35em .75em;border-radius:999px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.14)}
.stills{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.stills .main{grid-column:1/-1}
.still{border-radius:20px;overflow:hidden;background:var(--paper);padding:5px;box-shadow:inset 0 3px 5px rgba(255,255,255,.6),0 16px 26px -14px rgba(0,0,0,.8);transition:transform .45s cubic-bezier(.3,1.5,.5,1)}
.still img{width:100%;aspect-ratio:206/92;object-fit:cover;border-radius:15px}
.stills .main img{aspect-ratio:696/226}
.still:hover{transform:scale(1.04) rotate(-1deg);z-index:2}
.early{display:grid;grid-template-columns:1fr 1fr;gap:clamp(16px,2.4vw,28px);margin-top:clamp(40px,6vw,72px)}
.early > div{min-width:0}
.early h3{font-size:1.5rem;margin-bottom:12px}
.early h3 small{font-family:var(--f-body);font-weight:500;font-size:.95rem;color:#C9BDE6}
.early .stills .main img{aspect-ratio:508/172}
.early .stills{grid-template-columns:1fr 1fr}
.early .stills .still img{aspect-ratio:242/92}
.early .stills .main img{aspect-ratio:508/172}
.early a.chip{margin-top:12px;--c:var(--tangerine)}
.grid-head{display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:12px;margin:clamp(48px,7vw,84px) 0 22px}
.grid-head h3{font-size:clamp(1.8rem,3.4vw,2.6rem)}
.filters{display:flex;gap:6px;flex-wrap:wrap}
.filters button{font:600 .82rem var(--f-body);border:0;cursor:pointer;padding:.5em .95em;border-radius:999px;background:var(--night-2);color:var(--paper);box-shadow:inset 0 3px 5px rgba(255,255,255,.08),inset 0 -4px 6px rgba(0,0,0,.35)}
.filters button[aria-pressed="true"]{background:var(--sun);color:var(--ink);box-shadow:var(--clay-hi),inset 0 -4px 6px rgba(30,10,60,.2)}
.fgrid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:clamp(14px,2vw,22px)}
.film{position:relative;transform:perspective(700px) rotateX(var(--rx,0)) rotateY(var(--ry,0)) translateY(var(--lift,0));transition:transform .45s cubic-bezier(.2,1.4,.4,1)}
.film:hover{--lift:-6px}
.film .still img{aspect-ratio:236/116}
.film h4{font-family:var(--f-display);font-weight:600;font-size:1.08rem;margin:12px 0 2px;line-height:1.2}
.film .meta{font-size:.8rem;color:#C9BDE6;display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.film .meta a{color:var(--sun);font-weight:700;text-decoration:none}
.film .meta a:hover{text-decoration:underline}
.badge{position:absolute;top:-10px;right:-6px;z-index:2;font-family:var(--f-mono);font-size:.62rem;font-weight:700;line-height:1.2;max-width:62%;padding:.45em .7em;border-radius:12px;background:var(--mint);color:var(--ink);transform:rotate(5deg);box-shadow:var(--clay-hi),inset 0 -4px 6px rgba(30,10,60,.2),0 8px 12px -6px rgba(0,0,0,.6)}
.film[hidden]{display:none}

/* ---------- press ---------- */
.press-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:clamp(14px,2vw,22px)}
.press{display:flex;flex-direction:column;gap:12px;padding:22px;text-decoration:none;color:var(--ink);--r:30px;
  transform:perspective(800px) rotateX(var(--rx,0)) rotateY(var(--ry,0)) translateY(var(--lift,0));transition:transform .45s cubic-bezier(.2,1.4,.4,1)}
.press:hover{--lift:-6px}
.press.lead{grid-column:span 2;--c:var(--sun)}
.press .src{display:flex;align-items:center;justify-content:space-between;gap:8px;font-family:var(--f-mono);font-size:.72rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase}
.press .src em{font-style:normal;background:var(--ink);color:var(--paper);padding:.25em .6em;border-radius:8px}
.press h3{font-size:1.32rem;line-height:1.2}
.press.lead h3{font-size:clamp(1.6rem,3vw,2.3rem)}
.press p{font-size:.9rem;color:color-mix(in srgb,var(--ink) 82%,transparent)}
.press .go{margin-top:auto;font-weight:700;font-size:.88rem;display:flex;align-items:center;gap:6px}
.press .go svg{width:16px;height:16px;transition:transform .3s}
.press:hover .go svg{transform:translate(4px,-4px)}

.laurel-wall{margin-top:clamp(40px,6vw,72px);display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px}
.lw{--c:var(--paper);--r:24px;padding:16px 18px}
.lw .y{font-family:var(--f-mono);font-weight:700;font-size:.74rem;color:var(--tangerine)}
.lw ul{margin:6px 0 0;padding-left:1.1em;font-size:.86rem}
.lw li{margin:3px 0}

/* ---------- about ---------- */
.about-grid{display:grid;grid-template-columns:.8fr 1.2fr;gap:clamp(24px,4vw,56px);align-items:start}
.about-grid > *{min-width:0}
.about-photo{position:relative;padding:12px;--c:var(--paper);--r:34px;transform:perspective(900px) rotate(3deg) rotateX(var(--rx,0)) rotateY(var(--ry,0));transition:transform .5s cubic-bezier(.2,1.4,.4,1)}
.about-photo img{border-radius:24px;width:100%;aspect-ratio:266/350;object-fit:cover}
.about-copy h2{font-size:clamp(2rem,4.4vw,3.2rem)}
.about-copy .lead{font-size:1.12rem;margin-top:18px;max-width:58ch}
.about-copy .lead + p{margin-top:12px;color:var(--ink-2);max-width:58ch}
.skills{display:grid;grid-template-columns:1fr 1fr;gap:12px 22px;margin-top:28px}
.skill{font-size:.86rem;font-weight:600}
.skill .bar{height:16px;border-radius:999px;background:var(--table-2);box-shadow:inset 0 3px 5px rgba(30,10,60,.15);margin-top:6px;overflow:hidden}
.skill .bar i{display:block;height:100%;width:var(--v);border-radius:999px;background:var(--c);box-shadow:inset 0 3px 4px rgba(255,255,255,.55),inset 0 -3px 5px rgba(30,10,60,.2)}
.skill .lab{display:flex;justify-content:space-between}
.skill .lab span{font-family:var(--f-mono);font-size:.74rem}
.tools{margin-top:30px;display:grid;gap:14px}
.tools .row{display:flex;flex-wrap:wrap;gap:8px;align-items:center}
.tools .row b{font-family:var(--f-mono);font-size:.7rem;letter-spacing:.1em;text-transform:uppercase;width:100%;color:var(--ink-2)}
.tools .chip{cursor:default}

.journey{margin-top:clamp(56px,8vw,96px)}
.journey h3{font-size:clamp(1.8rem,3.4vw,2.6rem);margin-bottom:24px}
.tl{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:16px;position:relative}
.step{--r:26px;padding:18px;display:flex;flex-direction:column;gap:6px;transform:perspective(700px) rotateX(var(--rx,0)) rotateY(var(--ry,0));transition:transform .45s cubic-bezier(.2,1.4,.4,1)}
.step .when{font-family:var(--f-mono);font-size:.72rem;font-weight:700;background:var(--ink);color:var(--paper);align-self:flex-start;padding:.25em .65em;border-radius:8px}
.step h4{margin:4px 0 0;font-family:var(--f-display);font-weight:600;font-size:1.15rem;line-height:1.2}
.step p{font-size:.84rem;color:color-mix(in srgb,var(--ink) 80%,transparent)}
.extra{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:16px}
.extra .clay{padding:18px 20px;--r:26px}
.extra h4{margin:0 0 6px;font-family:var(--f-display);font-weight:600;font-size:1.15rem}
.extra ul{margin:0;padding-left:1.1em;font-size:.86rem}

/* ---------- contact ---------- */
.contact{padding-bottom:clamp(40px,6vw,64px)}
.contact-card{position:relative;--c:var(--tangerine);--r:clamp(32px,5vw,56px);padding:clamp(28px,5vw,64px);overflow:visible}
.contact-card h2{font-size:clamp(2.6rem,7.6vw,5.8rem);font-weight:800;letter-spacing:-.04em;line-height:.95;max-width:11ch}
.contact-card p.sub{margin-top:18px;font-size:1.1rem;max-width:44ch}
.contact-rows{display:flex;flex-wrap:wrap;gap:12px;margin-top:30px;position:relative;z-index:4}
.mail{display:flex;align-items:center;gap:8px;--c:var(--paper);--r:999px;padding:6px 6px 6px 18px;font-weight:700;max-width:100%}
.mail span{user-select:all;overflow-wrap:anywhere;font-size:clamp(.9rem,2.4vw,1.05rem)}
.mail .btn{--c:var(--sun);padding:.55em 1em;font-size:.88rem}
.contact-rows > .btn{--c:var(--paper);max-width:100%;overflow-wrap:anywhere}
.contact-rows > .btn.li{--c:var(--sky)}
footer{display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px;font-size:.82rem;color:var(--ink-2);padding-top:28px;font-family:var(--f-mono)}

/* ---------- scroll reveal (pop-up) ---------- */
html.rv .rv-item:not(.in){opacity:0}
.rv-item.in{animation:pop .85s cubic-bezier(.2,.9,.3,1) var(--d,0ms) both}
@keyframes pop{0%{opacity:0;translate:0 56px;scale:.86}55%{opacity:1;translate:0 -8px;scale:1.03}78%{translate:0 2px;scale:.99}100%{opacity:1;translate:0 0;scale:1}}

/* ---------- responsive ---------- */
@media (max-width:980px){
  .hero-grid{grid-template-columns:1fr}
  .hero-grid{gap:0}
  .hero-copy{display:contents}
  .hero-copy > *{order:2}
  .hero-copy > .big-hi{order:0}
  .stage{max-width:460px;order:1;margin:24px auto 4px}
  .caps{grid-template-columns:repeat(2,minmax(0,1fr))}
  .feature-top{grid-template-columns:1fr}
  .cats{grid-template-columns:1fr}
  .cat.wide .cat-body{grid-template-columns:1fr}
  .jobs{grid-template-columns:repeat(2,minmax(0,1fr))}
  .job:nth-child(5){grid-template-columns:1fr}
  .job:nth-child(5) .shot{grid-row:auto}
  .feat,.feat:nth-child(even){grid-template-columns:1fr}
  .feat:nth-child(even) .feat-text{order:0}
  .fgrid{grid-template-columns:repeat(3,minmax(0,1fr))}
  .press-grid{grid-template-columns:1fr 1fr}
  .about-grid{grid-template-columns:1fr}
  .about-photo{max-width:380px}
  .tl{grid-template-columns:repeat(2,minmax(0,1fr))}
  .decor{display:none}
}
@media (max-width:640px){
  .nav-now,.nav-now:not([hidden]){display:none!important}
  .big-hi{font-size:clamp(1.8rem,13.5vw,4rem);letter-spacing:-.05em;white-space:nowrap}
  .big-hi .line{display:inline}
  .big-hi .line:first-child{margin-right:.24em}
  .nav{padding-inline:10px}
  .nav-in{gap:2px;padding:5px 5px 5px 6px}
  .nav-links{margin-left:0;gap:0;-webkit-mask-image:none;mask-image:none}
  .nav-links a{padding:.55em .5em;font-size:.8rem;gap:4px}
  .nav-links .ic{width:17px;height:17px}
  .nav-links .ic{display:block}
  .nav-links a:not(.active) .t{display:none}
  .nav .btn{padding:.6em .68em}
  .nav .btn .lbl{display:none}
  .logo{width:34px;height:34px;padding:2px}
  .caps{grid-template-columns:1fr 1fr;gap:10px}
  .cap{min-height:170px;padding:16px}
  .cap h3{font-size:1.15rem}
  .cap p{display:none}
  .jobs{grid-template-columns:1fr}
  .job:nth-child(5){grid-column:auto}
  .jobs{grid-template-columns:1fr}
  .duo{grid-template-columns:1fr}
  .early{grid-template-columns:1fr}
  .fgrid{grid-template-columns:1fr 1fr;gap:14px 10px}
  .film h4{font-size:.95rem}
  .badge{font-size:.55rem}
  .press-grid{grid-template-columns:1fr}
  .press.lead{grid-column:auto}
  .skills{grid-template-columns:1fr}
  .tl{grid-template-columns:1fr}
  .extra{grid-template-columns:1fr}
  .stat b{font-size:1.25rem}
  .toy.m-hide{display:none}
}
@media (prefers-reduced-motion:reduce){
  *,*::before,*::after{animation:none!important;transition:none!important}
  html{scroll-behavior:auto}
}
</style>

<canvas class="sky" id="sky" aria-hidden="true"></canvas>
<div class="cursor" aria-hidden="true"></div>

<nav class="nav" aria-label="Main">
  <div class="nav-in clay">
    <a class="logo clay" href="#top" aria-label="Yudis Maulana, back to top"><img src="assets/avatar.jpg" alt="" width="160" height="160"></a>
    <div class="nav-links">
      <span class="nav-pill" aria-hidden="true"></span><a href="#reel" data-pill="sun" aria-label="Showreel"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="9"/><path d="M10 8.5v7l5.5-3.5z" fill="currentColor" stroke="none"/></svg><span class="t">Showreel</span></a><a href="#do" data-pill="mint" aria-label="Skills"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M12 3l2.3 5.4 5.7.5-4.3 3.8 1.3 5.6L12 15.4 7 18.3l1.3-5.6L4 8.9l5.7-.5z"/></svg><span class="t">Skills</span></a><a href="#work" data-pill="sky" aria-label="Work"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="7" width="18" height="13" rx="3"/><path d="M8.5 7V5.5A1.5 1.5 0 0 1 10 4h4a1.5 1.5 0 0 1 1.5 1.5V7M3 12.5h18"/></svg><span class="t">Work</span></a><a href="#films" data-pill="bubble" aria-label="Films"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="9" width="18" height="11" rx="2.5"/><path d="M3.5 9 19 4.5l1 3.4M8 8l2.2-3.6M13.5 6.4l2.2-3.6"/></svg><span class="t">Films</span></a><a href="#press" data-pill="sun" aria-label="Press"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M5 4h11a2 2 0 0 1 2 2v13a1 1 0 0 0 2 0V9h-2"/><path d="M5 4v14a2 2 0 0 0 2 2h12"/><path d="M8 8h6M8 12h6M8 16h4"/></svg><span class="t">Press</span></a><a href="#about" data-pill="grape-soft" aria-label="About"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="8.5" r="3.8"/><path d="M4.5 20c1.2-3.6 4-5.5 7.5-5.5s6.3 1.9 7.5 5.5"/></svg><span class="t">About</span></a><a href="#contact" data-pill="tangerine" aria-label="Contact"><svg class="ic" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><rect x="3" y="5.5" width="18" height="13" rx="3"/><path d="m4 7.5 8 6 8-6"/></svg><span class="t">Contact</span></a>
    </div>
    <span class="nav-now" id="navNow" hidden></span>
    <a class="btn" href="https://www.linkedin.com/in/yudismaulanaa/" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5a2.5 2.5 0 1 1 0 5 2.5 2.5 0 0 1 0-5ZM3 9.5h4V21H3V9.5Zm7 0h3.8v1.6h.06c.53-1 1.83-2.06 3.77-2.06 4.03 0 4.77 2.65 4.77 6.1V21h-4v-5.2c0-1.24-.02-2.84-1.73-2.84-1.74 0-2 1.35-2 2.75V21h-4V9.5Z"/></svg>
      <span class="lbl">LinkedIn</span></a>
  </div>
</nav>

<main id="top">
<!-- ================= HERO ================= -->
<header class="hero wrap">
  <div class="hero-grid">
    <div class="hero-copy">
      <h1 class="big-hi" aria-label="Hi, I'm Yudis">
        <span class="line" data-split>Hi, I'm</span>
        <span class="line clayword" data-split data-colors="tangerine,sun,mint,sky,bubble">Yudis</span>
      </h1>
      <div class="roles">
        <span class="chip">Videographer</span><span class="chip">Video Editor</span><span class="chip">AI Video Editor</span><span class="chip">Motion Graphic Designer</span><span class="chip">Scriptwriter</span>
      </div>
      <p class="hero-lede"><b>Eight years</b> making brands move. I've worked with <b>Bank Mandiri, Tempo Media Group, Kodak Pixpro and SBOX</b>. Today I'm the <b>Videographer, Video Editor, AI Video Editor &amp; Motion Graphic Designer</b> at <b>Cekat.AI</b>, making its brand films, ads, event reels and social content. My short <b>“Last Voice for Lost Light”</b> was selected for <b>JAFF 19</b> (Jogja-NETPAC Asian Film Festival) in the <b>Emerging 1</b> programme, screened at <b>Joyland Festival</b> in a line-up curated by <b>Joko Anwar</b>, and travelled to festivals in Brazil and Islamabad.</p>
      <div class="trusted"><span>Worked with</span><div class="trusted-logos">
        <span class="clay"><img src="assets/logo-mandiri.jpg" alt="Bank Mandiri"></span><span class="clay"><img src="assets/logo-tempo.jpg" alt="Tempo Media Group"></span><span class="clay"><img src="assets/logo-kodak.jpg" alt="Kodak Pixpro Indonesia"></span><span class="clay"><img src="assets/logo-sbox.jpg" alt="SBOX"></span><span class="clay"><img src="assets/logo-cekat.jpg" alt="Cekat.AI"></span>
      </div></div>
      <div class="hero-cta">
        <a class="btn" href="#reel" style="--c:var(--tangerine)">
          <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M8 5.5v13a1 1 0 0 0 1.5.86l10.5-6.5a1 1 0 0 0 0-1.72L9.5 4.64A1 1 0 0 0 8 5.5Z"/></svg>
          Play showreel</a>
        <a class="btn" href="#work" style="--c:var(--paper)">See the work</a>
      </div>
      <p class="hint"><i class="clay" aria-hidden="true">↖</i>Move your cursor over the clay toys. Click one to spin it.</p>
    </div>

    <div class="stage" id="stage">
      <div class="blob clay" aria-hidden="true"></div>
      <figure class="portrait clay" data-tilt style="margin:0"><img src="assets/portrait-hero.jpg" alt="Portrait of Yudis Maulana lit in red" width="660" height="900"></figure>
      <img class="toy" data-depth=".9" src="assets/camera.png" alt="" style="--x:-4%;--y:62%;--w:40%;--r:-8deg">
      <img class="toy" data-depth=".5" src="assets/play.png" alt="" style="--x:72%;--y:66%;--w:24%;--r:8deg">
      <img class="toy" data-depth="1.1" src="assets/reel.png" alt="" style="--x:76%;--y:34%;--w:18%;--r:0deg">
      <img class="toy" data-depth=".7" src="assets/sparkle.png" alt="" style="--x:6%;--y:4%;--w:20%;--r:-10deg">
      <img class="toy" data-depth="1.3" src="assets/star.png" alt="" style="--x:74%;--y:2%;--w:18%;--r:14deg">
      <img class="toy" data-depth=".8" src="assets/clapper.png" alt="" style="--x:38%;--y:-6%;--w:21%;--r:-8deg">
      <img class="toy m-hide" data-depth=".6" src="assets/chat.png" alt="" style="--x:0%;--y:30%;--w:20%;--r:-6deg">
      <img class="toy m-hide" data-depth="1" src="assets/shapes.png" alt="" style="--x:52%;--y:84%;--w:15%;--r:0deg">
      <div class="stat clay" style="--c:var(--mint);left:64%;top:20%"><b>8 yrs</b><span>behind the camera</span></div>
      <div class="stat clay" style="--c:var(--bubble);left:2%;top:50%"><b>29</b><span>short films</span></div>
    </div>
  </div>
</header>

<!-- ================= SHOWREEL ================= -->
<section class="reel" id="reel">
  <div class="toy decor ticket" data-depth=".7" aria-hidden="true" style="--x:85%;--y:-4%;--w:150px;--r:10deg">ADMIT ONE<small>SHOWREEL · 2026</small></div>
  <div class="toy decor filmstrip" data-depth="1" aria-hidden="true" style="--x:-3%;--y:84%;--w:190px;--r:-12deg"><i></i><i></i><i></i></div>
  <div class="wrap">
    <div class="sec-head">
      <div><p class="eyebrow"><span class="slate">SC.01</span>Showreel 2026 · 01:25</p><h2>85 seconds of work.</h2></div>
      <p class="aside">Brand films, event reels, AI-assisted spots and festival shorts, cut down to one reel. Turn the sound on.</p>
    </div>
    <div class="tv clay">
      <div class="tv-screen">
        <video id="reelVideo" preload="metadata" playsinline poster="assets/reel-poster.jpg" src="assets/showreel.mp4"></video>
        <button class="tv-play" id="reelPlay" aria-label="Play showreel"><span><svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M6 4.5v15a1 1 0 0 0 1.5.86l12.5-7.5a1 1 0 0 0 0-1.72L7.5 3.64A1 1 0 0 0 6 4.5Z"/></svg></span></button>
      </div>
      <div class="tv-bar"><span class="rec">YUDIS_MAULANA_SHOWREEL_2026.MP4</span><span class="knobs" aria-hidden="true"><i></i><i></i></span></div>
    </div>
  </div>
</section>

<!-- ================= CAPABILITIES ================= -->
<section id="do">
  <img class="toy decor" data-depth=".6" src="assets/pencil.png" alt="" style="--x:86%;--y:4%;--w:120px;--r:10deg">
  <div class="wrap">
    <div class="sec-head">
      <div><p class="eyebrow"><span class="slate">SC.02</span>Capabilities</p><h2>What I do</h2></div>
      <p class="aside">I can take a project from the first line of script to the final, delivery-ready file. These days I add AI workflows when they make the work faster or better.</p>
    </div>
    <div class="caps">
      <article class="cap clay" data-tilt style="--c:var(--sun)"><span class="num">01</span><img src="assets/star.png" alt=""><h3>Brand Identity</h3><p>Visual language for brand content and campaigns.</p></article>
      <article class="cap clay" data-tilt style="--c:var(--bubble)"><span class="num">02</span><img src="assets/camera.png" alt=""><h3>Videography</h3><p>Camera operation and DOP for ads, events and film.</p></article>
      <article class="cap clay" data-tilt style="--c:var(--sky)"><span class="num">03</span><img src="assets/bulb.png" alt=""><h3>Technical Light</h3><p>Gaffer and chief lighting on a dozen short films.</p></article>
      <article class="cap clay" data-tilt style="--c:var(--mint)"><span class="num">04</span><img src="assets/slider.png" alt=""><h3>Editing</h3><p>Cutting and colour grading, vertical and widescreen.</p></article>
      <article class="cap clay" data-tilt style="--c:#C9B8FF"><span class="num">05</span><img src="assets/shapes.png" alt=""><h3>Motion Graphic</h3><p>Bumpers, award-night packages and social motion.</p></article>
      <article class="cap clay" data-tilt style="--c:var(--paper)"><span class="num">06</span><img src="assets/pencil.png" alt=""><h3>Writing</h3><p>Scripts for my own films and for brand content.</p></article>
      <article class="cap clay" data-tilt style="--c:var(--tangerine)"><span class="num">07</span><img src="assets/sparkle.png" alt=""><h3>AI Generation</h3><p>Higgsfield, Lumina, Gemini and friends in the pipeline.</p></article>
      <article class="cap clay statement" data-tilt><h3>From the first script to final, industry-standard assets.</h3><p>Now powered by AI workflows</p></article>
    </div>
  </div>
</section>

<!-- ================= BRANDS ================= -->
<div class="brands" aria-label="Brands I've worked with">
  <div class="wrap"><p class="eyebrow"><span class="slate">CLIENTS</span>Brands I've worked with, 2017–2026</p></div>
  <div class="marquee"><div class="track" id="track"></div></div>
</div>

<!-- ================= WORK ================= -->
<section id="work" style="padding-top:clamp(24px,4vw,48px)">
  <img class="toy decor" data-depth=".8" src="assets/bulb.png" alt="" style="--x:2%;--y:2%;--w:90px;--r:-12deg">
  <div class="toy decor lens" data-depth="1" aria-hidden="true" style="--x:91%;--y:9%;--w:96px;--r:0deg"></div>
  <img class="toy decor" data-depth=".6" src="assets/clapper.png" alt="" style="--x:1%;--y:52%;--w:100px;--r:-10deg">
  <div class="wrap">
    <div class="sec-head">
      <div><p class="eyebrow"><span class="slate">SC.03</span>Work experience · 2017–2026</p><h2>Selected work</h2></div>
      <p class="aside">One full-time seat at an AI company, plus freelance work for media, consumer brands, a bank and wedding studios.</p>
    </div>

    <article class="feature clay">
      <div class="feature-top">
        <div>
          <div class="co-logo clay"><img src="assets/logo-cekat.jpg" alt="Cekat.AI logo"></div>
          <p class="eyebrow" style="color:var(--ink)">Full time · May 2025 – now</p>
          <h3>Cekat.AI</h3>
          <div class="tag"><span class="chip">Videographer</span><span class="chip">Video Editor</span><span class="chip">AI Video Editor</span><span class="chip">Motion Graphic Designer</span></div>
          <p>I run video for Cekat.AI end to end: vertical ads, the Cekat Innov 25 event package, a YouTube interview series and the daily feed on Instagram and TikTok. Each category below pairs the clips with their own watch links. Tap a number to watch that piece.</p>
        </div>
        <div class="shot clay" data-tilt><img src="assets/w-cekat.jpg" alt="Cekat.AI vertical ads on phone mockups"></div>
      </div>
      <div class="cats" id="cekatSets"></div>
    </article>

    <div class="jobs">
      <article class="job clay" data-tilt style="--c:var(--sun)">
        <div class="shot clay"><img src="assets/w-kodak.jpg" alt="Kodak Pixpro social videos"><div class="logos"><span class="co-logo clay"><img src="assets/logo-kodak.jpg" alt="Kodak Pixpro logo"></span></div></div>
        <span class="kind">Freelance editor</span><h3>Kodak Pixpro Indonesia</h3>
        <p>Social video content, including the weekend photo-walk series "Motret Akhir Pekan".</p>
        <div class="links"><a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/file/d/1hbAwwFFbJSkJGy9aTDgpVCITr5Oez4pP/view">01 · Vertical reel ↗</a><a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/file/d/17j-U1_x-FrObKp0cd8IdTwKVM75i2iHx/view">02 · Motret Akhir Pekan ↗</a></div>
      </article>
      <article class="job clay" data-tilt style="--c:var(--bubble)">
        <div class="shot clay"><img src="assets/w-sbox.jpg" alt="SBOX Pop Your Style campaign"><div class="logos"><span class="co-logo clay"><img src="assets/logo-sbox.jpg" alt="SBOX logo"></span></div></div>
        <span class="kind">Freelance editor</span><h3>SBOX</h3>
        <p>Vertical and landscape campaign videos, including "Pop Your Style, Capture the Fun".</p>
        <div class="links" id="sboxLinks"></div>
      </article>
      <article class="job clay" data-tilt style="--c:var(--tangerine)">
        <div class="shot clay"><img src="assets/w-tempo.jpg" alt="Tempo award night motion graphics"><div class="logos"><span class="co-logo clay"><img src="assets/logo-tempo.jpg" alt="Tempo Media Group logo"></span></div></div>
        <span class="kind">Freelance motion graphic</span><h3>Tempo Media Group</h3>
        <p>Motion graphics for Tempo's award nights and forums.</p>
        <div class="links">
          <a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/drive/folders/1_LiFeUNncTPHkz_jhTtpqQdO0zLfeWDK">Apresiasi Pemda Berprestasi 2026 ↗</a>
          <a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/drive/folders/1E0BeSjHqQa6--nYJbWdgIT50ltEbIa85">Apresiasi Kinerja Pemda 2025 ↗</a>
          <a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/drive/folders/13jIkay2R4qeGMCeabai5hj4hakY4y4TH">Tempo Energy Day 2025 ↗</a>
          <a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/drive/folders/1Y1ZfmUDpGjfH-yxrG5j-_sZoZ6aoXr_A">Forum &amp; Anugerah Instar 2025 ↗</a>
        </div>
      </article>
      <article class="job clay" data-tilt style="--c:var(--mint)">
        <div class="shot clay"><img src="assets/w-mandiri.jpg" alt="Bank Mandiri video productions"><div class="logos"><span class="co-logo clay"><img src="assets/logo-mandiri.jpg" alt="Bank Mandiri logo"></span></div></div>
        <span class="kind">Videographer &amp; lighting</span><h3>Bank Mandiri</h3>
        <p>Videographer and penata cahaya (lighting) on Bank Mandiri video productions.</p>
        <div class="links"><a class="chip" target="_blank" rel="noopener" href="https://youtu.be/KDjcKC1cRe8">Video 1 ↗</a><a class="chip" target="_blank" rel="noopener" href="https://drive.google.com/file/d/1sUUniSdboOHg2nVU7s3ZWy6QMHO_k6N1/view">Video 2 ↗</a></div>
      </article>
      <article class="job clay" data-tilt style="--c:#C9B8FF">
        <div class="shot clay"><img src="assets/w-daynings.jpg" alt="Wedding films on a laptop"><div class="logos"><span class="co-logo clay"><img src="assets/logo-daynings.jpg" alt="Daynings logo"></span><span class="co-logo clay"><img src="assets/logo-ruangpotret.jpg" alt="Ruangpotret logo"></span></div></div>
        <span class="kind">Videographer &amp; editor · 2020–2023</span><h3>Daynings &amp; Ruangpotret</h3>
        <p>Wedding documentation: teasers, engagement films and couple sessions. Ruang Potret from Nov 2020 to Jan 2022, Daynings from Jan 2022 to Mar 2023.</p>
        <div class="links"><a class="chip" target="_blank" rel="noopener" href="https://bit.ly/PORTOWEDDINGWORKS">See the wedding works ↗</a></div>
      </article>
    </div>
  </div>
</section>

<!-- ================= FILMS ================= -->
<section class="films" id="films">
  <div class="toy decor rec-btn" data-depth=".7" aria-hidden="true" style="--x:86%;--y:-1.2%;--w:130px;--r:8deg">REC</div>
  <div class="toy decor filmstrip" data-depth="1" aria-hidden="true" style="--x:-4%;--y:46%;--w:170px;--r:14deg"><i></i><i></i><i></i></div>
  <img class="toy decor" data-depth=".8" src="assets/reel.png" alt="" style="--x:92%;--y:62%;--w:110px;--r:0deg">
  <div class="wrap">
    <div class="sec-head">
      <div><p class="eyebrow"><span class="slate">SC.04</span>Film experience · 2017–2025</p><h2>29 short films and counting</h2></div>
      <p class="aside">As director, writer, DOP, editor, colourist and lighting crew. Three I wrote and directed lead the list.</p>
    </div>
    <div id="featured"></div>

    <div class="early">
      <div>
        <h3>Dunya <small>(2020) · Director</small></h3>
        <div class="stills"><div class="still main"><img src="assets/dunya-0.jpg" alt="Still from Dunya" loading="lazy"></div><div class="still"><img src="assets/dunya-1.jpg" alt="" loading="lazy"></div><div class="still"><img src="assets/dunya-2.jpg" alt="" loading="lazy"></div></div>
      </div>
      <div>
        <h3>Dream <small>(2017) · Director, DOP, Editor</small></h3>
        <div class="stills"><div class="still main"><img src="assets/dream-0.jpg" alt="Still from Dream" loading="lazy"></div><div class="still"><img src="assets/dream-1.jpg" alt="" loading="lazy"></div><div class="still"><img src="assets/dream-2.jpg" alt="" loading="lazy"></div></div>
        <a class="chip" href="https://youtu.be/l3Tj5UNGM4o" target="_blank" rel="noopener">▸ Watch Dream, my first film ↗</a>
      </div>
    </div>

    <div class="grid-head">
      <h3>Filmography</h3>
      <div class="filters" role="group" aria-label="Filter films by role">
        <button type="button" data-f="all" aria-pressed="true">All</button>
        <button type="button" data-f="light" aria-pressed="false">Lighting</button>
        <button type="button" data-f="cam" aria-pressed="false">DOP &amp; camera</button>
        <button type="button" data-f="watch" aria-pressed="false">Watchable</button>
      </div>
    </div>
    <div class="fgrid" id="fgrid"></div>
  </div>
</section>

<!-- ================= PRESS ================= -->
<section id="press">
  <img class="toy decor" data-depth=".7" src="assets/chat.png" alt="" style="--x:88%;--y:3%;--w:130px;--r:8deg">
  <img class="toy decor" data-depth=".9" src="assets/clapper.png" alt="" style="--x:0%;--y:38%;--w:110px;--r:-6deg">
  <div class="wrap">
    <div class="sec-head">
      <div><p class="eyebrow"><span class="slate">SC.05</span>In the news</p><h2>Press &amp; mentions</h2></div>
      <p class="aside">Coverage of "Last Voice for Lost Light", which I wrote and directed, during its 2024 festival run.</p>
    </div>
    <div class="press-grid">
      <a class="press clay lead" data-tilt href="https://www.tempo.co/teroka/joyland-festival-jakarta-2024-suguhkan-kurasi-film-pendek-joko-anwar-1168579" target="_blank" rel="noopener">
        <span class="src">Tempo · Teroka <em>News</em></span>
        <h3>Joyland Festival Jakarta 2024 Suguhkan Kurasi Film Pendek Joko Anwar</h3>
        <p>Tempo's report on the Cinerillaz short film programme at Joyland Festival 2024, curated by Joko Anwar, where "Last Voice for Lost Light" was screened.</p>
        <span class="go">Read on tempo.co <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay" data-tilt style="--c:var(--sky)" href="https://www.suara.com/entertainment/2024/11/19/122441/yuk-nonton-film-pendek-di-joyland-2024-pilihan-joko-anwar" target="_blank" rel="noopener">
        <span class="src">Suara.com · 19 Nov 2024 <em>News</em></span>
        <h3>Yuk, Nonton Film Pendek di Joyland 2024 Pilihan Joko Anwar</h3>
        <p>Lists "Last Voice for Lost Light" first among the 16 shorts Joko Anwar selected.</p>
        <span class="go">Read on suara.com <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay" data-tilt style="--c:var(--bubble)" href="https://www.instagram.com/vbiz.co.id/p/DCgw2ipPvcD/" target="_blank" rel="noopener">
        <span class="src">VBIZ · Instagram <em>Feature</em></span>
        <h3>Highlighted in VBIZ's Joyland short film line-up</h3>
        <p>VBIZ picked out the film alongside its Cinerillaz screening at Joyland Festival 2024.</p>
        <span class="go">View post <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay" data-tilt style="--c:var(--mint)" href="https://www.instagram.com/alexandermatius/p/DEG8kSWug7R/" target="_blank" rel="noopener">
        <span class="src">Alexander Matius · Instagram <em>Pick</em></span>
        <h3>Recommended Indonesian films of 2024</h3>
        <p>Named by the Program Director of Jogja-NETPAC Asian Film Festival as one of the notable films of the year.</p>
        <span class="go">View post <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay" data-tilt style="--c:#C9B8FF" href="https://www.instagram.com/movreview/p/DEREI60zzCQ/" target="_blank" rel="noopener">
        <span class="src">Movreview · Instagram <em>Recap</em></span>
        <h3>#2024RecapofMOVREVIEW: Best of the Best Experience</h3>
        <p>Listed in the top category of Movreview's recap of 200+ short films watched in 2024.</p>
        <span class="go">View post <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay" data-tilt style="--c:var(--paper)" href="https://www.instagram.com/movreview/p/C8t5TqmSY10/" target="_blank" rel="noopener">
        <span class="src">Movreview · Instagram <em>Review</em></span>
        <h3>Perspektif Jatinangor terhadap kehilangan</h3>
        <p>Movreview's write-up of Movie Event Padjadjaran (Montaj) 2024, where the film was an official selection.</p>
        <span class="go">View post <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
      <a class="press clay lead" data-tilt style="--c:var(--sky)" href="https://www.linkedin.com/feed/update/urn:li:activity:7265163329776558080/" target="_blank" rel="noopener">
        <span class="src">LinkedIn · Post <em>JAFF 2024</em></span>
        <h3>Screening at the 19th Jogja-NETPAC Asian Film Festival</h3>
        <p>A sweet close to a year on the road: after three years attending JAFF as a student, the film screened there in December 2024.</p>
        <span class="go">Read the post <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"><path d="M7 17 17 7M9 7h8v8"/></svg></span>
      </a>
    </div>

    <div class="laurel-wall" id="laurels"></div>
  </div>
</section>

<!-- ================= ABOUT ================= -->
<section id="about">
  <img class="toy decor" data-depth=".9" src="assets/sparkle.png" alt="" style="--x:90%;--y:6%;--w:110px;--r:-8deg">
  <div class="toy decor lens" data-depth=".8" aria-hidden="true" style="--x:1%;--y:62%;--w:84px;--r:0deg"></div>
  <img class="toy decor" data-depth="1" src="assets/camera.png" alt="" style="--x:88%;--y:70%;--w:150px;--r:8deg">
  <div class="wrap">
    <div class="about-grid">
      <figure class="about-photo clay" data-tilt style="margin:0"><img src="assets/portrait-about.jpg" alt="Yudis Maulana with arms crossed" loading="lazy"></figure>
      <div class="about-copy">
        <p class="eyebrow"><span class="slate">SC.06</span>About me</p>
        <h2 style="margin-top:.35em">Videographer, editor and scriptwriter, driven by visual excellence.</h2>
        <p class="lead">Eight years of expertise in delivering high-impact visuals for commercial brands and festival acclaimed films. I believe superior content bridges the gap between cinematic storytelling and dynamic motion. I collaborate from the initial script to final, industry standard assets.</p>
        <p>Now with AI-powered workflows, I bring an extra layer of speed and creativity by leveraging cutting-edge tools to push motion storytelling even further.</p>
        <div class="skills" id="skills"></div>
      </div>
    </div>

  </div>
  <div class="toolkit" aria-label="Favourite tools">
    <div class="wrap"><p class="eyebrow"><span class="slate">TOOLKIT</span>Favourite tools</p></div>
    <div class="marquee"><div class="track rev" id="toolTrack"></div></div>
  </div>
  <div class="wrap">
    <div class="journey">
      <p class="eyebrow"><span class="slate">TIMELINE</span>Journey</p>
      <h3 style="margin-top:.35em">How I got here</h3>
      <div class="tl" id="tl"></div>
      <div class="extra">
        <div class="clay" style="--c:var(--paper)">
          <h4>Education</h4>
          <ul><li>Film &amp; Television, Institut Seni Indonesia Yogyakarta</li><li>SMAN 1 Tamansari (2018–2020)</li></ul>
        </div>
        <div class="clay" style="--c:var(--paper)">
          <h4>Volunteer &amp; festival work</h4>
          <ul><li>Sewon Screening 7 (2021), video team</li><li>Sewon Screening 8 (2022), programmer for the closing and special screenings</li><li>Aputure Indonesia × ISI Yogyakarta lighting workshop (2023), documentation</li><li>Festival Film Bogor 2023, programmer</li></ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ================= CONTACT ================= -->
<section class="contact wrap" id="contact">
  <div class="contact-card clay">
    <img class="toy decor" data-depth="1" src="assets/camera.png" alt="" style="--x:68%;--y:-14%;--w:min(30%,300px);--r:-10deg">
    <img class="toy decor" data-depth=".6" src="assets/star.png" alt="" style="--x:86%;--y:52%;--w:min(13%,130px);--r:12deg">
    <div class="toy decor filmstrip" data-depth=".9" aria-hidden="true" style="--x:72%;--y:84%;--w:160px;--r:-6deg"><i></i><i></i><i></i></div>
    <img class="toy decor" data-depth=".8" src="assets/reel.png" alt="" style="--x:86%;--y:30%;--w:min(11%,110px);--r:0deg">
    <p class="eyebrow" style="color:var(--ink)"><span class="slate">SC.07</span>Contact</p>
    <h2 style="margin-top:.3em">Let's make something move.</h2>
    <p class="sub">Brand film, event reel, AI-assisted spot or a short film that needs a DOP? Send me a note.</p>
    <div class="contact-rows">
      <div class="mail clay"><span id="mail">yudismaulana77@gmail.com</span><button class="btn" id="copyMail" type="button">Copy email</button></div>
      <a class="btn li" href="https://www.linkedin.com/in/yudismaulanaa/" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5a2.5 2.5 0 1 1 0 5 2.5 2.5 0 0 1 0-5ZM3 9.5h4V21H3V9.5Zm7 0h3.8v1.6h.06c.53-1 1.83-2.06 3.77-2.06 4.03 0 4.77 2.65 4.77 6.1V21h-4v-5.2c0-1.24-.02-2.84-1.73-2.84-1.74 0-2 1.35-2 2.75V21h-4V9.5Z"/></svg>linkedin.com/in/yudismaulanaa</a>
      <a class="btn" href="https://www.instagram.com/yudismaulanaa" target="_blank" rel="noopener">Instagram · @yudismaulanaa</a>
    </div>
  </div>
  <footer><span>© 2026 Yudis Maulana</span><span>Videographer · Editor · AI Video Editor · Motion Graphic · Scriptwriter</span></footer>
</section>
</main>

<script>
const L={"ads": ["https://drive.google.com/file/d/10qGrmn6rOEAg1mhwG3uRskO-FWGp2ibp/view?usp=drivesdk", "https://drive.google.com/file/d/1dBDOBF-f8BqEund3tu0hjb21omVu6Gz7/view?usp=drivesdk", "https://drive.google.com/file/d/1xUk8kAUjcCSmMj_5_CER7xAnvOCdTaIv/view?usp=drivesdk", "https://drive.google.com/file/d/1wUk_2GLMnLjMo2M4FNov9JAFOKOUbNG0/view?usp=drivesdk", "https://drive.google.com/file/d/1A7-g0DG5NTf8_8W1uFQn2pKXIHGHl96b/view?usp=drivesdk", "https://drive.google.com/file/d/1bkFJ6rgYW39_eujKSqTbHk7whc7ZqRcs/view?usp=drivesdk", "https://drive.google.com/file/d/1EajzxWH8TRpjMdpBZIyPcm-FRQx2v9t2/view?usp=drivesdk", "https://drive.google.com/file/d/1AvDDt5axLDYf1IsUSNLonhUicT5z1JEe/view?usp=drivesdk", "https://drive.google.com/file/d/1n4nf6jRcq0snRxvkxtOa6Kuv5jALosfU/view?usp=drivesdk", "https://drive.google.com/file/d/1n_xcJaT8P3OI_3-X7H2rLzt4xa97Ox8N/view?usp=drivesdk", "https://drive.google.com/file/d/1J5zv1thLuwN8H2VMMUDZz3H1FNGn5ZFT/view?usp=drivesdk", "https://drive.google.com/file/d/106aJfEwRYllvEKoxONC4wRUI7bEHs0DY/view?usp=drivesdk", "https://drive.google.com/file/d/1YkOO5tm-ByH0eDxiGWnb05kESIvwGmv9/view?usp=drivesdk", "https://drive.google.com/file/d/1Sm0KJCA7d0mW3vcrgS7TLbaqCBP_bmKM/view?usp=drivesdk", "https://drive.google.com/file/d/1bw-pf1fi6at62522pHLvVjyB_hwCNoZO/view?usp=drivesdk", "https://drive.google.com/file/d/1vZ_m5qyqBxAKaADVtxXu9jltLm1ZHt1p/view?usp=drivesdk", "https://drive.google.com/file/d/1J16U4-NMhh3FCrpcQXkhAp6njrvaZAwi/view?usp=drivesdk", "https://drive.google.com/file/d/1W33h_sXXgsHHnpbuIBZZCvl0zgOd8Lf_/view?usp=drivesdk"], "innov": ["https://drive.google.com/file/d/1qSuMjBt7aDqp5QsDqVyPSvv0k_Qp7-BR/view?usp=drivesdk", "https://drive.google.com/file/d/1a15mvQNX3mJ2mDFhqY3TKtwDeqcM4156/view?usp=drivesdk", "https://drive.google.com/file/d/1n0Jk4z01IGU_xX0e8mOZkH_Zfb7omcoC/view?usp=drivesdk", "https://drive.google.com/file/d/1h2fTIl85-fUUQl1jvEY-BoTeP-QizRRq/view?usp=drivesdk", "https://drive.google.com/file/d/1d9b3VIkDwxIREXF46jA6SKNOsMZibLgR/view?usp=drivesdk", "https://drive.google.com/file/d/1OqLe7JD5l3OfqKoyOZ_BrXBeAqxqDkya/view?usp=drivesdk", "https://drive.google.com/file/d/1EFrSf0qoUyHe4PxwYBHprS4ZbmgUQRzZ/view?usp=drivesdk", "https://drive.google.com/file/d/1Y4PljNvVnF5nDh07GGQW03kzoGyDVy35/view?usp=drivesdk", "https://drive.google.com/file/d/1zbWAJfuEKLts_V2O4bj0g4pNA8CikRmV/view?usp=drivesdk", "https://drive.google.com/file/d/1xoihbIUqwVhTxXcvSXe27eVznW438qPJ/view?usp=drivesdk", "https://drive.google.com/file/d/1O2QyD32gzhuCtcN7dVAuvfiv8MtkAa1j/view?usp=drivesdk", "https://drive.google.com/file/d/1cLMrOmy-U89kRIdeV_O1o8JmuL9HhExq/view?usp=drivesdk", "https://drive.google.com/file/d/1AYozfQKhSn9MeTttvsk8Qk7T3uzQ-9Rj/view?usp=drivesdk", "https://drive.google.com/file/d/1TZDrgmxAzceQ108UFJQoR3Tsr0eU7GEC/view?usp=drivesdk", "https://drive.google.com/file/d/1NF20rCVuwHmNb7jkh8b88PWyWoimtZuN/view?usp=drivesdk", "https://drive.google.com/file/d/1pZwPt4BLTqzSSX5WedVDMOJvs0OUqC6C/view?usp=drivesdk", "https://drive.google.com/file/d/1Wis46ueHcEANTRbqjNn_l_L6Qa7jmZkU/view?usp=drivesdk", "https://drive.google.com/file/d/1kxZ3lUdKIPJ2jP_Tj8LALHkieUp6IwWY/view?usp=drivesdk", "https://drive.google.com/file/d/1MV86_fIIU3CPC-tq-cMwbIfpWGtghukN/view?usp=drivesdk", "https://drive.google.com/file/d/1SJqn0OE91DGTMYpgb1FJAsrRnHtfDC3D/view?usp=drivesdk", "https://drive.google.com/file/d/1NSseevsk7XMU7Q502Q5Itsp3FACyw1dn/view?usp=drivesdk", "https://drive.google.com/file/d/1vhEOVH-CKrir2O-smqkR848invMcdr6o/view?usp=drivesdk", "https://drive.google.com/file/d/1kzH8nsWOaB2RaX6842Yl90Wn6TwWt5rW/view?usp=drivesdk", "https://drive.google.com/file/d/12qGKJHopspcmVsrv9Kwid72rlJI4IIk2/view?usp=drivesdk", "https://drive.google.com/file/d/1oMJ1G3GRwhcolCbvDboLNTRTV1ipXArz/view?usp=drivesdk", "https://drive.google.com/file/d/1KanlRVMNZt5ULoL4V72qwrVf8fy-vIDv/view?usp=drivesdk", "https://drive.google.com/file/d/13PASptZCi78fxeRp_knqJdCtOUNdPOgg/view?usp=drivesdk", "https://drive.google.com/file/d/1UwYAM7nmnBZBoKsGHF6oAkCMn-sv-nDC/view?usp=drivesdk", "https://drive.google.com/file/d/1RvrlFJWLhViqMh8LYc6qVmc_zfli7i5_/view?usp=drivesdk", "https://drive.google.com/file/d/1WsCTu6I2lAM4OhItko8c25wGxvQ2tjcX/view?usp=drivesdk", "https://drive.google.com/file/d/1Xu9PjSRBpW6WE0sbJP5Zig2LXLPoqgS0/view?usp=drivesdk", "https://drive.google.com/file/d/1NqchFB4HmkgF04fvLOlWb7voC6-sCabx/view?usp=drivesdk", "https://drive.google.com/file/d/1AvSEiYkn84gl-d2XHyfeHOkQYnI-owOL/view?usp=drivesdk", "https://drive.google.com/file/d/1pZwPt4BLTqzSSX5WedVDMOJvs0OUqC6C/view?usp=drivesdk", "https://drive.google.com/file/d/1omqLrzczzwCAt6gR3dttPp5FfJQ30F1d/view?usp=drivesdk", "https://drive.google.com/file/d/1cAAVDGa1GzJZVg9gaFHH6Zxsw6x2pC8b/view?usp=drivesdk", "https://drive.google.com/file/d/1-oFoawU_9dJHBjPwI95b4d0TuWUfem09/view?usp=drive_link", "https://drive.google.com/file/d/14EwldpFtC2yYMCywr1Jz1iwTMCgR1ipe/view?usp=drivesdk", "https://drive.google.com/file/d/1Gu2XkpT_rv9dZmqDmHBBEFt53LfkDGD-/view?usp=drive_link", "https://drive.google.com/file/d/1A6kYWwnSOncbrH6N6aBDRS2ILLyxJRMa/view?usp=drivesdk", "https://drive.google.com/file/d/1IVZdFF6NLPguXdprJqe--8P6zfjulL_G/view?usp=drive_link", "https://drive.google.com/file/d/1bnITZznFH1kIzncPfta1TXB1YMPK7JPK/view?usp=drivesdk", "https://drive.google.com/file/d/1ReGxTNjPKfqp_xJ_TaiOiVqYtHiuH-dI/view?usp=drive_link", "https://drive.google.com/file/d/1jeIa1TzO8NX3Bl6u2MU44SXfE48nObHy/view?usp=drivesdk", "https://drive.google.com/file/d/1fJHX67Cu__lMbPlOFXmDMy8vIRzrPwgt/view?usp=drive_link", "https://drive.google.com/file/d/1ZyoTmMRgELC0yp34Y2xJW0q6-v5gkJIu/view?usp=drivesdk", "https://drive.google.com/file/d/1sNkjQ06rOgRUynZpOEweoHQDsNsST1s9/view?usp=drive_link", "https://drive.google.com/file/d/1VGFWcbUkQu8Taz4S_BiOrIcnocAGkGBp/view?usp=drivesdk", "https://drive.google.com/file/d/12QoFzINr0Gv2r54cEOXDyqISolBOX8XF/view?usp=drive_link", "https://drive.google.com/file/d/1JefNcezP0tb4RW0gIfL0BAKSKSYo5DTx/view?usp=drivesdk", "https://drive.google.com/file/d/1ubOARBgKpCy0tfz8XwbEKqoxD53Np-ux/view?usp=drive_link", "https://drive.google.com/file/d/1aOj85Ir2PRoCeHQnHSnZUAhKTgq4rRlD/view?usp=drivesdk", "https://drive.google.com/file/d/1Au-Mhf4-fxLIbbwTGeJ4g4FUaYIJrYzU/view?usp=drive_link", "https://drive.google.com/file/d/1ur9WX3YvWAO5xkODrkNVF8TSmG_cMqjn/view?usp=drivesdk"], "bump": ["https://drive.google.com/file/d/15kVTQEicGxSbhbkJG1_UbGgODM6gcFeb/view?usp=drive_link", "https://drive.google.com/file/d/1jDyYfxZzxd_cJzQgj0uwFt3--Q0VcuMe/view?usp=drive_link", "https://drive.google.com/file/d/1IZNknRYmlfZm7jQoLhZ4D_0s7FC86o_n/view?usp=drive_link", "https://drive.google.com/file/d/1AcL_gCxBLUlYiLE-XE8WRFpIaWTz7h9F/view?usp=drive_link", "https://drive.google.com/file/d/1MgWvmSEZAoKpHklETsJ7jdJDbOfwNy8S/view?usp=drive_link", "https://drive.google.com/file/d/14P6cSNJPTuLY5YT3CxQZl24zFCH1pxi4/view?usp=drive_link", "https://drive.google.com/file/d/1m5NUBJg7Zp9w25a7I4dHAmkksYxgYT5o/view?usp=drive_link", "https://drive.google.com/file/d/1P9zqP3X5Q5s2Q_9jhEFVOZCivd3K346S/view?usp=drive_link", "https://drive.google.com/file/d/1dCxOQ95W4ofQacplLmudub2GnHKhjQuW/view?usp=drive_link", "https://drive.google.com/file/d/1YPttgRva8pFP2UaifDW1qgJuLk0-IsKg/view?usp=drive_link", "https://drive.google.com/file/d/1El7wu8p6yhsQFt5zQ-lK7mcQWud039SB/view?usp=drive_link", "https://drive.google.com/file/d/1CQcpuvLiZ5kxpFkdNWtStjvcPC4wUuay/view?usp=drive_link"], "success": ["https://youtu.be/JTg5GsKAu_s?si=nWTSHCJsctJMBd-1", "https://youtu.be/nSQ267wtd88?si=f0QmWyrh_yAFwH_A", "https://youtu.be/uUz8sDRaxZI?si=he_y3HQXd_mDrpsB", "https://youtu.be/681luT0Aa68?si=PkLSOPlnQOdHW3yU", "https://youtu.be/A7H9MUI0zj0?si=uScSN0n5SlTAkM6R", "https://youtu.be/lF1O7sawPsQ?si=Mr74_8c77u_BqSN4", "https://youtu.be/wi2Q7Ft3WFo?si=rseZKOwHkPXG_TaK", "https://youtu.be/vmXUCHVo6k8?si=lah2dR_8ST8GfXD9", "https://youtu.be/ePdVgW7X01s?si=lKmYz_AV_qrrkLwi", "https://youtu.be/c0yJok_3Nv8?si=zJGr4_jD8loOTEAU"], "sbox": ["https://drive.google.com/file/d/1wLJ-bm811vXizW4tqpHpDQFcpBtcNajE/view", "https://drive.google.com/file/d/1_zuVlbMy7rtGHVQWn1ZUbhjuFpTW0sJf/view", "https://drive.google.com/file/d/1tIJH6qyz2Sky1VmytJniZ8_weN4KCenB/view?usp=sharing", "https://drive.google.com/file/d/1JyB8M6hzMX-V6zzSAHq27Iw_8B14t2es/view?usp=sharing", "https://drive.google.com/file/d/1yzGFUcW7ehe0bdrow2n0GgQhVzZEtQmd/view?usp=sharing"], "keynote": ["https://youtu.be/XZJXujaW0b4?si=KkSGXKYJsjm4niEy", "https://youtu.be/sBfvJn-fpnc?si=UBKmbtmxVspMRz7v"]};

(function(){
const $=(s,r=document)=>r.querySelector(s), $$=(s,r=document)=>[...r.querySelectorAll(s)];
const reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
const fine=matchMedia('(pointer: fine)').matches;
const esc=s=>String(s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const pad=n=>String(n).padStart(2,'0');
const dotsHTML=(arr)=>arr.map((u,i)=>`<a class="dot" href="${esc(u)}" target="_blank" rel="noopener" aria-label="Watch ${pad(i+1)}">${pad(i+1)}</a>`).join('');

/* --- split hero letters --- */
$$('[data-split]').forEach(el=>{
  const cols=(el.dataset.colors||'').split(',').filter(Boolean);
  const txt=el.textContent; el.textContent='';
  [...txt].forEach((c,i)=>{const s=document.createElement('span');s.className='ch'+(c===' '?' sp':'');s.textContent=c===' '?' ':c;s.setAttribute('aria-hidden','true');
    if(cols.length) s.style.setProperty('--c',`var(--${cols[i%cols.length]})`);
    el.appendChild(s);});
});
$$('.ch').forEach(s=>{const go=()=>{if(reduce)return;s.classList.remove('boing');void s.offsetWidth;s.classList.add('boing')};s.addEventListener('pointerenter',go);s.addEventListener('animationend',()=>s.classList.remove('boing'))});
if(!reduce){ $$('.clayword .ch').forEach((s,i)=>setTimeout(()=>{s.classList.add('boing')},500+i*90)); }

/* --- brands marquee --- */
const brands=[['cekat','Cekat.AI'],['kodak','Kodak Pixpro Indonesia'],['sbox','SBOX'],['tempo','Tempo Media Group'],['mandiri','Bank Mandiri'],['daynings','Daynings'],['ruangpotret','Ruangpotret']];
const bHTML=brands.map(([k,n])=>`<div class="logo-card clay"><img src="assets/logo-${k}.jpg" alt="${esc(n)} logo"><span>${esc(n)}</span></div>`).join('');
$('#track').innerHTML=bHTML+bHTML.replace(/alt="[^"]*"/g,'alt=""');

/* --- Cekat sets --- */
const cat=(n,title,meta,img,alt,links,extra='',wide='')=>`<section class="cat clay${wide}" aria-label="${title.replace('&amp;','and')}">
  <div class="cat-head"><span class="cat-no">${n}</span><h4>${title}</h4><small>${meta}</small></div>
  <div class="cat-body"><div class="cat-img"><img src="assets/${img}.jpg" alt="${esc(alt)}"></div>
  <div class="cat-links"><span class="watch">Watch</span><div class="dots">${links}${extra}</div></div></div></section>`;
$('#cekatSets').innerHTML=
 cat('01','Ads',`${L.ads.length} vertical spots`,'w-cekat-ads','Grid of 18 vertical Cekat.AI ad spots',dotsHTML(L.ads))+
 cat('02','Cekat Innov 25 reels',`${L.innov.length} event reels`,'w-innov','Vertical event reels from Cekat Innov 25',dotsHTML(L.innov))+
 cat('03','Innov 25 bumpers &amp; keynote',`${L.bump.length} bumpers + keynote`,'w-bumper','Speaker bumpers for Cekat Innov 25',dotsHTML(L.bump),`<a class="dot wide" href="${esc(L.keynote[0])}" target="_blank" rel="noopener">Keynote ↗</a><a class="dot wide" href="${esc(L.keynote[1])}" target="_blank" rel="noopener">Ideation ↗</a>`)+
 cat('04','Success Story',`YouTube · ${L.success.length} episodes`,'w-success','Success Story YouTube episode thumbnails',dotsHTML(L.success))+
 cat('05','Instagram &amp; TikTok','Daily social feed','w-social','Cekat.AI Instagram and TikTok profiles','',`<a class="btn" href="https://www.instagram.com/cekat.ai/" target="_blank" rel="noopener">Instagram · @cekat.ai ↗</a><a class="btn" href="https://www.tiktok.com/@cekatai?lang=en" target="_blank" rel="noopener">TikTok · @cekatai ↗</a>`,' wide');
$('#sboxLinks').innerHTML=L.sbox.map((u,i)=>`<a class="chip" target="_blank" rel="noopener" href="${esc(u)}">${pad(i+1)} ↗</a>`).join('');

/* --- featured films --- */
const featured=[
 {k:'ateot',t:'At the End of Time',y:2025,role:'Director · DOP · Editor · Script Writer',u:'https://youtu.be/LsoqJtd8qh4',syn:'My most recent short as director, shot, cut and written by me.'},
 {k:'sotb',t:'Sweetness of the Boi',y:2024,role:'Writer & Director',u:'https://youtu.be/HNhDwUTl57A'},
 {k:'lvfll',t:'Last Voice for Lost Light',y:2024,role:'Writer & Director · 11 min · Drama',u:'https://www.instagram.com/reel/C2fZ8vVv-xR/',
  syn:'Sarip and Susan are about to become parents. Because Sarip is absent during his wife’s labour, the couple lose their first child.',
  laurels:['19th Jogja-NETPAC Asian Film Festival 2024 · Emerging 1','Joyland Festival 2024 · Cinerillaz, curated by Joko Anwar','Islamabad International Film Festival 2024','CineMAZ Festival 2024 (Brazil)','Sewon Screening 10','Jogja Film Academy Short Film Festival 2024','Movie Event Padjadjaran 2024','Festival Film Bulanan Lokus 2','Cinecussion Movie Exhibition 2025']}
];
$('#featured').innerHTML=featured.map(f=>`
 <article class="feat clay">
  <div class="feat-text"><span class="year">${f.y}</span><h3>${esc(f.t)}</h3><p class="role">${esc(f.role)}</p>
   ${f.syn?`<p class="syn">${esc(f.syn)}</p>`:''}
   ${f.laurels?`<div class="laurels">${f.laurels.map(l=>`<span>${esc(l)}</span>`).join('')}</div>`:''}
   <a class="btn" href="${esc(f.u)}" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M8 5.5v13a1 1 0 0 0 1.5.86l10.5-6.5a1 1 0 0 0 0-1.72L9.5 4.64A1 1 0 0 0 8 5.5Z"/></svg>Watch the film</a></div>
  <div class="stills"><div class="still main"><img src="assets/${f.k}-0.jpg" alt="Still from ${esc(f.t)}" loading="lazy"></div>${[1,2,3].map(i=>`<div class="still"><img src="assets/${f.k}-${i}.jpg" alt="" loading="lazy"></div>`).join('')}</div>
 </article>`).join('');

/* --- filmography --- */
const films=[
 ['tether','Tether','Chief Lighting',2025,'https://www.instagram.com/reel/DR1s3NpAds3/','light'],
 ['insya','Insya Allah, Amanah','Chief Lighting',2023,'https://drive.google.com/file/d/1tnJkyZwx_RhNhQEdJN36bQ8x4sxEp8Ou/view','light'],
 ['katastrofi','Katastrofi Santri','Chief Lighting',2023,'https://bit.ly/TRAILER-KS','light'],
 ['pha','Pulangkeun Hayam Aing!','Chief Lighting',2023,'https://bit.ly/TRAILER-PHA','light','5 nominations · FFP TVRI Jabar 2023'],
 ['ngujang','Ngujang','Chief Lighting',2023,'','light'],
 ['wgoihbe','What’s Going On in Her Beautiful Eyes?','Chief Lighting',2023,'','light'],
 ['littleleague','Little League: From Ambition, I Learned','Lighting Crew',2022,'','light'],
 ['boykiss','The Boy Who Can’t Kiss the Ground','Lighting Crew',2022,'','light'],
 ['kompilasi','Kompilasi Komplikasi','Lighting Crew',2022,'','light'],
 ['heylookma','Hey Look Ma, I Made It!','Lighting Crew',2022,'','light'],
 ['rainyday','Rainy Day on the Last Day','Camera Operator, Colorist',2022,'http://bit.ly/TRAILER-RDOTLD','cam','Finalist · Student World Impact FF'],
 ['tellme','Tell Me It’d Be Fine','Lighting Crew · Music video',2022,'https://bit.ly/FULL-TMIBF','light'],
 ['jirapah','Jirapah Muto','DOP, Colorist · Music video',2022,'https://youtu.be/Xy9CsH-1HMg','cam'],
 ['reincarnasht','Reincarnash*t','DOP, Colorist',2021,'http://bit.ly/TRAILER-REINCARNASHT','cam','Honorable Mention · SWIFF 2022'],
 ['kencan','Kencan Tanpa Nasi','DOP, Colorist',2021,'http://bit.ly/TRAILER-KTN','cam'],
 ['ambisi','Ambisi dan Obsesi','DOP',2021,'','cam'],
 ['bersenyawa','Bersenyawa','DOP, Editor',2019,'https://youtu.be/v0XEzSjEm7U','cam','Nominee · Cirebon Film Festival'],
 ['stereotipez','Stereotipe Z','DOP, Editor',2019,'https://youtu.be/VqmM3sKxm3Y','cam','1st · ILM Kemdikbud Nasional'],
 ['figurpuan','Figur Puan','DOP, Editor',2019,'http://bit.ly/TRAILER-FP','cam'],
 ['gawang','Gawang','DOP, Editor',2019,'https://youtu.be/WB-5yCT1Roc','cam','1st · FLS2N Kab. Bogor'],
 ['lawankarsa','Lawan Karsa','DOP, Editor',2019,'https://youtu.be/jZOIESvj6_o','cam'],
 ['gaptek','Gaptek & Meletek','DOP, Editor',2018,'https://youtu.be/_szL6EUcw0w','cam'],
 ['arif','Arif','DOP, Editor',2018,'','cam'],
 ['bahasaurang','Bahasa Urang','DOP, Editor',2018,'','cam']
];
$('#fgrid').innerHTML=films.map(([k,t,r,y,u,g,b])=>`
 <article class="film" data-tilt data-g="${g}" data-w="${u?1:0}">
  ${b?`<span class="badge">${esc(b)}</span>`:''}
  <div class="still"><img src="assets/f-${k}.jpg" alt="Still from ${esc(t)}" loading="lazy"></div>
  <h4>${esc(t)}</h4>
  <div class="meta"><span>${esc(r)} · ${y}</span>${u?`<a href="${esc(u)}" target="_blank" rel="noopener">Watch ↗</a>`:''}</div>
 </article>`).join('');
$$('.filters button').forEach(b=>b.addEventListener('click',()=>{
  $$('.filters button').forEach(x=>x.setAttribute('aria-pressed',x===b?'true':'false'));
  const f=b.dataset.f;
  $$('.film').forEach(el=>{el.hidden=!(f==='all'||(f==='watch'?el.dataset.w==='1':el.dataset.g===f))});
}));

/* --- laurels wall --- */
const lw=[
 ['2019',['1st Winner, FLS2N Kabupaten Bogor (Gawang)','1st Winner, ILM Kemdikbud Nasional (Stereotipe Z)','Bersenyawa: nominee for Best Student Fiction and Best Student Cinematography, Cirebon Film Festival','Bersenyawa: Student Film Competition, Jogja Film Academy Festival']],
 ['2020–2021',['Semi-finalist, Leloun International Film Festival (Bersenyawa)','Official Selection, 9th Festival International du Court-métrage Brèves d’Images']],
 ['2022',['Honorable Mention, Student World Impact Film Festival (Reincarnash*t)','Finalist Best Short Film, Student World Impact Film Festival (Rainy Day on the Last Day)']],
 ['2023',['Pulangkeun Hayam Aing!: nominated for Best Film, Director, Screenplay, Cinematography and Editor, Festival Film Pendek TVRI Jawa Barat','Official Selection, Sewon Screening 9']],
 ['2024–2025',['Last Voice for Lost Light: JAFF 19, Joyland (Cinerillaz), Islamabad IFF, CineMAZ, Sewon Screening 10, JAFA SFF, Montaj, Lokus 2, Cinecussion Movie Exhibition 2025']]
];
$('#laurels').innerHTML=lw.map(([y,items])=>`<div class="lw clay"><span class="y">${y}</span><ul>${items.map(i=>`<li>${esc(i)}</li>`).join('')}</ul></div>`).join('');

/* --- skills & tools --- */
const skills=[['Operate Camera',95,'sky'],['Concepting Visual',95,'bubble'],['Concepting Light & Technical',95,'sun'],['Directing Film',90,'tangerine'],['Writing',90,'grape'],['Editing',90,'mint'],['Generative AI (Video & Image)',90,'sky'],['AI Video Generation',90,'bubble'],['Motion Graphic',85,'sun']];
$('#skills').innerHTML=skills.map(([n,v,c])=>`<div class="skill"><div class="lab">${esc(n)}<span>${v}%</span></div><div class="bar"><i style="--v:${v}%;--c:var(--${c})"></i></div></div>`).join('');
const IC={
 premiere:"M10.15 8.42a2.93 2.93 0 00-1.18-.2 13.9 13.9 0 00-1.09.02v3.36l.39.02h.53c.39 0 .78-.06 1.150-.18.32-.09.6-.28.82-.53.21-.25.31-.59.31-1.03a1.45 1.45 0 00-.93-1.46zM19.75.3H4.25A4.25 4.25 0 000 4.55v14.9c0 2.35 1.9 4.25 4.25 4.25h15.5c2.35 0 4.25-1.9 4.25-4.25V4.55C24 2.2 22.1.3 19.75.3zm-7.09 11.650c-.4.56-.96.98-1.61 1.22-.68.25-1.43.34-2.25.34l-.5-.01-.43-.01v3.21a.12.12 0 01-.11.14H5.82c-.08 0-.12-.04-.12-.13V6.42c0-.07.03-.11.1-.11l.56-.01.76-.02.87-.02.91-.01c.82 0 1.5.1 2.06.31.5.17.96.45 1.34.82.32.32.57.71.73 1.14.15.42.23.85.23 1.3 0 .86-.2 1.57-.6 2.13zm6.82-3.15v1.95c0 .08-.05.11-.16.11a4.35 4.35 0 00-1.92.37c-.19.09-.37.21-.51.37v5.1c0 .1-.04.14-.13.14h-1.97a.14.14 0 01-.16-.12v-5.58l-.01-.75-.02-.78c0-.23-.02-.45-.04-.68a.1.1 0 01.07-.11h1.78c.1 0 .18.07.2.16a3.03 3.03 0 01.13.92c.3-.35.67-.64 1.08-.86a3.1 3.1 0 011.52-.39c.07-.01.13.04.14.11v.04z",
 aftereffects:"M8.54 10.73c-.1-.31-.19-.61-.29-.92s-.19-.6-.27-.89c-.08-.28-.15-.54-.22-.78h-.02c-.09.43-.2.86-.34 1.29-.15.48-.3.98-.46 1.48-.13.51-.29.98-.44 1.4h2.54c-.06-.21-.14-.46-.23-.72-.09-.27-.18-.56-.27-.86zm8.58-.29c-.55-.03-1.07.26-1.33.76-.12.23-.19.47-.22.72h2.109c.26 0 .45 0 .57-.01.08-.01.16-.03.23-.08v-.1c0-.13-.021-.25-.061-.37-.178-.56-.708-.94-1.298-.92zM19.75.3H4.25C1.9.3 0 2.2 0 4.55v14.9c0 2.35 1.9 4.25 4.25 4.25h15.5c2.35 0 4.25-1.9 4.25-4.25V4.55C24 2.2 22.1.3 19.75.3zm-7.04 16.511h-2.09c-.07.01-.14-.041-.16-.11l-.82-2.4H5.92l-.76 2.36c-.02.09-.1.15-.19.14H3.09c-.11 0-.14-.06-.11-.18L6.2 7.39c.03-.1.06-.19.1-.31.04-.21.06-.43.06-.65-.01-.05.03-.1.08-.11h2.59c.07 0 .12.03.13.08l3.65 10.25c.03.11.001.161-.1.161zm7.851-3.991c-.021.189-.031.33-.041.42-.01.07-.069.13-.14.13-.06 0-.17.01-.33.021-.159.02-.35.029-.579.029-.23 0-.471-.04-.73-.04h-3.17c.039.31.14.62.31.89.181.271.431.48.729.601.4.17.841.26 1.281.25.35-.011.699-.04 1.039-.11.311-.039.61-.119.891-.23.05-.039.08-.02.08.08v1.531c0 .039-.01.08-.021.119-.021.03-.04.051-.069.07-.32.14-.65.24-1 .3-.471.09-.94.13-1.42.12-.761 0-1.4-.12-1.92-.35-.49-.211-.921-.541-1.261-.95-.319-.39-.55-.83-.69-1.31-.14-.471-.209-.961-.209-1.461 0-.539.08-1.07.25-1.59.16-.5.41-.96.75-1.37.33-.4.739-.72 1.209-.95.471-.23 1.03-.31 1.67-.31.531-.01 1.06.09 1.55.31.41.18.77.45 1.05.8.26.34.47.72.601 1.14.129.4.189.81.189 1.22 0 .24-.01.45-.019.64z",
 illustrator:"M10.53 10.73c-.1-.31-.19-.61-.29-.92-.1-.31-.19-.6-.27-.89-.08-.28-.15-.54-.22-.78h-.02c-.09.43-.2.86-.34 1.29-.15.48-.3.98-.46 1.48-.14.51-.29.98-.44 1.4h2.54c-.06-.211-.14-.46-.23-.721-.09-.269-.18-.559-.27-.859zM19.75.3H4.25C1.9.3 0 2.2 0 4.55v14.9c0 2.35 1.9 4.25 4.25 4.25h15.5c2.35 0 4.250-1.9 4.25-4.25V4.55C24 2.2 22.1.3 19.75.3zM14.7 16.83h-2.091c-.069.01-.139-.04-.159-.11l-.82-2.38H7.91l-.76 2.35c-.02.09-.1.15-.19.141H5.08c-.11 0-.14-.061-.11-.18L8.19 7.38c.03-.1.06-.21.1-.33.04-.21.06-.43.06-.65-.01-.05.03-.1.08-.11h2.59c.08 0 .12.03.13.08l3.65 10.3c.03.109 0 .16-.1.16zm3.4-.15c0 .11-.039.16-.129.16H16.01c-.1 0-.15-.061-.15-.16v-7.7c0-.1.041-.14.131-.14h1.98c.09 0 .129.05.129.14v7.7zm-.209-9.03c-.231.24-.571.37-.911.35-.33.01-.65-.12-.891-.35-.23-.25-.35-.58-.34-.92-.01-.34.12-.66.359-.89.242-.23.562-.35.892-.35.391 0 .689.12.91.35.22.24.34.56.33.89.01.34-.11.67-.349.92z",
 resolve:"M17.621 0 5.977.004c-1.37 0-2.756.345-3.762 1.11a4.925 4.925 0 0 0-1.61 2.003C.233 3.93 0 5.02 0 5.951l.012 12.2c.002 1.604.479 3.057 1.461 4.112.984 1.056 2.462 1.683 4.331 1.691L16.856 24c1.26.005 3.095-.036 4.303-.714 1.075-.605 2.025-1.556 2.497-2.984.278-.84.345-2.084.344-3.147l-.021-11.13c-.002-.888-.15-2.023-.547-2.934-.425-.976-1.181-1.815-2.322-2.425C20.353.26 19.123 0 17.622 0zm0 .93c1.378 0 2.538.295 3.04.565.977.523 1.544 1.166 1.889 1.96.315.721.47 1.793.473 2.572l.018 11.13c.002 1.013-.097 2.257-.298 2.86-.396 1.202-1.146 1.946-2.063 2.462-.814.457-2.612.593-3.820.588l-11.05-.044c-1.657-.007-2.832-.534-3.626-1.386-.792-.851-1.212-2.060-1.212-3.485L.999 5.95c0-.829.196-1.827.474-2.437.345-.757.75-1.207 1.365-1.674C3.585 1.270 4.868.97 6.080.97zm-5.66 3.423c-1.976.089-3.204 1.658-3.214 3.290.019 1.443 1.635 3.481 2.884 4.530.12.099.154.109.33.18.062.025.198-.047.327-.135.36-.245.993-.947 1.648-1.738a7.670 7.670 0 0 0 1.031-1.683c.409-.89.261-1.599.235-1.888a3.983 3.983 0 0 0-.99-1.692 3.360 3.360 0 0 0-2.251-.864zm4.172 7.922a10.185 10.185 0 0 0-3.244.610c-.15.058-.26.1-.374.17-.057.036-.11.135-.105.292.017.433.29 1.278.624 2.270.384 1.135 1.066 2.270 1.844 2.740a3.230 3.230 0 0 0 2.530.342c.832-.243 1.595-.868 1.962-1.546.986-1.818.19-3.548-1.121-4.417-.447-.296-1.133-.445-1.890-.46-.074 0-.15-.002-.226-.001zm-8.432.038a6.201 6.201 0 0 0-.752.047c-.596.078-.932.273-1.290.510a3.177 3.177 0 0 0-1.365 1.979c-.075.552-.086 1.053.033 1.507.433 1.389 1.326 2.222 2.847 2.452.636.028 1.370-.063 1.990-.450 1.269-.782 2.080-3.170 2.412-4.742.053-.176.035-.357-.013-.42-.005-.067-.044-.113-.19-.183-.398-.192-1.320-.417-2.375-.6a7.680 7.680 0 0 0-1.297-.1z",
 canva:"M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zM6.962 7.68c.754 0 1.337.549 1.405 1.2.069.583-.171 1.097-.822 1.406-.343.171-.48.172-.549.069-.034-.069 0-.137.069-.206.617-.514.617-.926.548-1.508-.034-.378-.308-.618-.583-.618-1.2 0-2.914 2.674-2.674 4.629.103.754.549 1.646 1.509 1.646.308 0 .65-.103.96-.24.5-.264.799-.47 1.097-.8-.073-.885.704-2.046 1.851-2.046.515 0 .926.205.96.583.068.514-.377.582-.514.582s-.378-.034-.378-.17c-.034-.138.309-.07.275-.378-.035-.206-.24-.274-.446-.274-.72 0-1.131.994-1.029 1.611.035.275.172.549.447.549.205 0 .514-.31.617-.755.068-.308.343-.514.583-.514.102 0 .17.034.205.171v.138c-.034.137-.137.548-.102.651 0 .069.034.171.17.171.092 0 .436-.18.777-.459.117-.59.253-1.298.253-1.357.034-.24.137-.48.617-.48.103 0 .171.034.205.171v.138l-.136.617c.445-.583 1.097-.994 1.508-.994.172 0 .309.102.309.274 0 .103 0 .274-.069.446-.137.377-.309.96-.412 1.474 0 .137.035.274.207.274.171 0 .685-.206 1.096-.754l.007-.004c-.002-.068-.007-.134-.007-.202 0-.411.035-.754.104-.994.068-.274.411-.514.617-.514.103 0 .205.069.205.171 0 .035 0 .103-.034.137-.137.446-.24.857-.24 1.269 0 .24.034.582.102.788 0 .034.035.069.07.069.068 0 .548-.445.89-1.028-.308-.206-.48-.549-.48-.96 0-.72.446-1.097.858-1.097.343 0 .617.24.617.72 0 .308-.103.65-.274.96h.102a.77.77 0 0 0 .584-.24.293.293 0 0 1 .134-.117c.335-.425.83-.74 1.41-.74.48 0 .924.205.959.582.068.515-.378.618-.515.618l-.002-.002c-.138 0-.377-.035-.377-.172 0-.137.309-.068.274-.376-.034-.206-.24-.275-.446-.275-.686 0-1.13.891-1.028 1.611.034.275.171.583.445.583.206 0 .515-.308.652-.754.068-.274.343-.514.583-.514.103 0 .17.034.205.171 0 .069 0 .206-.137.652-.17.308-.171.48-.137.617.034.274.171.48.309.583.034.034.068.102.068.102 0 .069-.034.138-.137.138-.034 0-.068 0-.103-.035-.514-.205-.72-.548-.789-.891-.205.24-.445.377-.72.377-.445 0-.89-.411-.96-.926a1.609 1.609 0 0 1 .075-.649c-.203.13-.422.203-.623.203h-.17c-.447.652-.927 1.098-1.27 1.303a.896.896 0 0 1-.377.104c-.068 0-.171-.035-.205-.104-.095-.152-.156-.392-.193-.667-.481.527-1.145.805-1.453.805-.343 0-.548-.206-.582-.55v-.376c.102-.754.377-1.2.377-1.337a.074.074 0 0 0-.069-.07c-.24 0-1.028.824-1.166 1.373l-.103.445c-.068.309-.377.515-.582.515-.103 0-.172-.035-.206-.172v-.137l.046-.233c-.435.31-.87.508-1.075.508-.308 0-.48-.172-.514-.412-.206.274-.445.412-.754.412-.352 0-.696-.24-.862-.593-.244.275-.523.553-.852.764-.48.309-1.028.549-1.68.549-.582 0-1.097-.309-1.371-.583-.412-.377-.651-.96-.686-1.509-.205-1.68.823-3.84 2.4-4.8.378-.205.755-.343 1.132-.343zm9.77 3.291c-.104 0-.172.172-.172.343 0 .274.137.583.309.755a1.74 1.74 0 0 0 .102-.583c0-.343-.137-.515-.24-.515z",
 gemini:"M11.04 19.32Q12 21.51 12 24q0-2.49.93-4.68.96-2.19 2.58-3.81t3.81-2.55Q21.51 12 24 12q-2.49 0-4.68-.93a12.3 12.3 0 0 1-3.81-2.58 12.3 12.3 0 0 1-2.58-3.81Q12 2.49 12 0q0 2.49-.96 4.68-.93 2.19-2.55 3.81a12.3 12.3 0 0 1-3.81 2.58Q2.49 12 0 12q2.49 0 4.68.96 2.19.93 3.81 2.55t2.55 3.81",
 openai:"M22.2819 9.8211a5.9847 5.9847 0 0 0-.5157-4.9108 6.0462 6.0462 0 0 0-6.5098-2.9A6.0651 6.0651 0 0 0 4.9807 4.1818a5.9847 5.9847 0 0 0-3.9977 2.9 6.0462 6.0462 0 0 0 .7427 7.0966 5.98 5.98 0 0 0 .511 4.9107 6.051 6.051 0 0 0 6.5146 2.9001A5.9847 5.9847 0 0 0 13.2599 24a6.0557 6.0557 0 0 0 5.7718-4.2058 5.9894 5.9894 0 0 0 3.9977-2.9001 6.0557 6.0557 0 0 0-.7475-7.0729zm-9.022 12.6081a4.4755 4.4755 0 0 1-2.8764-1.0408l.1419-.0804 4.7783-2.7582a.7948.7948 0 0 0 .3927-.6813v-6.7369l2.02 1.1686a.071.071 0 0 1 .038.052v5.5826a4.504 4.504 0 0 1-4.4945 4.4944zm-9.6607-4.1254a4.4708 4.4708 0 0 1-.5346-3.0137l.142.0852 4.783 2.7582a.7712.7712 0 0 0 .7806 0l5.8428-3.3685v2.3324a.0804.0804 0 0 1-.0332.0615L9.74 19.9502a4.4992 4.4992 0 0 1-6.1408-1.6464zM2.3408 7.8956a4.485 4.485 0 0 1 2.3655-1.9728V11.6a.7664.7664 0 0 0 .3879.6765l5.8144 3.3543-2.0201 1.1685a.0757.0757 0 0 1-.071 0l-4.8303-2.7865A4.504 4.504 0 0 1 2.3408 7.872zm16.5963 3.8558L13.1038 8.364 15.1192 7.2a.0757.0757 0 0 1 .071 0l4.8303 2.7913a4.4944 4.4944 0 0 1-.6765 8.1042v-5.6772a.79.79 0 0 0-.407-.667zm2.0107-3.0231l-.142-.0852-4.7735-2.7818a.7759.7759 0 0 0-.7854 0L9.409 9.2297V6.8974a.0662.0662 0 0 1 .0284-.0615l4.8303-2.7866a4.4992 4.4992 0 0 1 6.6802 4.66zM8.3065 12.863l-2.02-1.1638a.0804.0804 0 0 1-.038-.0567V6.0742a4.4992 4.4992 0 0 1 7.3757-3.4537l-.142.0805L8.704 5.459a.7948.7948 0 0 0-.3927.6813zm1.0976-2.3654l2.602-1.4998 2.6069 1.4998v2.9994l-2.5974 1.4997-2.6067-1.4997Z",
 claude:"m4.7144 15.9555 4.7174-2.6471.079-.2307-.079-.1275h-.2307l-.7893-.0486-2.6956-.0729-2.3375-.0971-2.2646-.1214-.5707-.1215-.5343-.7042.0546-.3522.4797-.3218.686.0608 1.5179.1032 2.2767.1578 1.6514.0972 2.4468.255h.3886l.0546-.1579-.1336-.0971-.1032-.0972L6.973 9.8356l-2.55-1.6879-1.3356-.9714-.7225-.4918-.3643-.4614-.1578-1.0078.6557-.7225.8803.0607.2246.0607.8925.686 1.9064 1.4754 2.4893 1.8336.3643.3035.1457-.1032.0182-.0728-.164-.2733-1.3539-2.4467-1.445-2.4893-.6435-1.032-.17-.6194c-.0607-.255-.1032-.4674-.1032-.7285L6.287.1335 6.6997 0l.9957.1336.419.3642.6192 1.4147 1.0018 2.2282 1.5543 3.0296.4553.8985.2429.8318.091.255h.1579v-.1457l.1275-1.706.2368-2.0947.2307-2.6957.0789-.7589.3764-.9107.7468-.4918.5828.2793.4797.686-.0668.4433-.2853 1.8517-.5586 2.9021-.3643 1.9429h.2125l.2429-.2429.9835-1.3053 1.6514-2.0643.7286-.8196.85-.9046.5464-.4311h1.0321l.759 1.1293-.34 1.1657-1.0625 1.3478-.8804 1.1414-1.2628 1.7-.7893 1.36.0729.1093.1882-.0183 2.8535-.607 1.5421-.2794 1.8396-.3157.8318.3886.091.3946-.3278.8075-1.967.4857-2.3072.4614-3.4364.8136-.0425.0304.0486.0607 1.5482.1457.6618.0364h1.621l3.0175.2247.7892.522.4736.6376-.079.4857-1.2142.6193-1.6393-.3886-3.825-.9107-1.3113-.3279h-.1822v.1093l1.0929 1.0686 2.0035 1.8092 2.5075 2.3314.1275.5768-.3218.4554-.34-.0486-2.2039-1.6575-.85-.7468-1.9246-1.621h-.1275v.17l.4432.6496 2.3436 3.5214.1214 1.0807-.17.3521-.6071.2125-.6679-.1214-1.3721-1.9246L14.38 17.959l-1.1414-1.9428-.1397.079-.674 7.2552-.3156.3703-.7286.2793-.6071-.4614-.3218-.7468.3218-1.4753.3886-1.9246.3157-1.53.2853-1.9004.17-.6314-.0121-.0425-.1397.0182-1.4328 1.9672-2.1796 2.9446-1.7243 1.8456-.4128.164-.7164-.3704.0667-.6618.4008-.5889 2.386-3.0357 1.4389-1.882.929-1.0868-.0062-.1579h-.0546l-6.3385 4.1164-1.1293.1457-.4857-.4554.0608-.7467.2307-.2429 1.9064-1.3114Z",
 docs:"M14.727 6.727H14V0H4.91c-.905 0-1.637.732-1.637 1.636v20.728c0 .904.732 1.636 1.636 1.636h14.182c.904 0 1.636-.732 1.636-1.636V6.727h-6zm-.545 10.455H7.09v-1.364h7.09v1.364zm2.727-3.273H7.091v-1.364h9.818v1.364zm0-3.273H7.091V9.273h9.818v1.363zM14.727 6h6l-6-6v6z",
 sheets:"M11.318 12.545H7.910v-1.909h3.410v1.910zM14.728 0v6h6l-6-6zm1.363 10.636h-3.410v1.910h3.410v-1.910zm0 3.273h-3.410v1.910h3.410v-1.910zM20.727 6.500v15.864c0 .904-.732 1.636-1.636 1.636H4.909a1.636 1.636 0 0 1-1.636-1.636V1.636C3.273.732 4.005 0 4.909 0h9.318v6.500h6.500zm-3.273 2.773H6.545v7.909h10.910v-7.910zm-6.136 4.636H7.910v1.910h3.410v-1.910z",
 office:"M21.53 4.306v15.363q0 .807-.472 1.433-.472.627-1.253.85l-6.888 1.974q-.136.037-.29.055-.156.019-.293.019-.396 0-.72-.105-.321-.106-.656-.292l-4.505-2.544q-.248-.137-.391-.366-.143-.23-.143-.515 0-.434.304-.738.304-.305.739-.305h5.831V4.964l-4.38 1.563q-.533.187-.856.658-.322.472-.322 1.03v8.078q0 .496-.248.912-.25.416-.683.651l-2.072 1.13q-.286.148-.571.148-.497 0-.844-.347-.348-.347-.348-.844V6.563q0-.62.33-1.19.328-.571.874-.881L11.07.285q.248-.136.534-.21.285-.075.57-.075.211 0 .38.031.166.031.364.093l6.888 1.899q.384.11.7.329.317.217.547.52.23.305.353.67.125.367.125.764zm-1.588 15.363V4.306q0-.273-.16-.478-.163-.204-.423-.28l-3.388-.93q-.397-.111-.794-.23-.397-.117-.794-.216v19.68l4.976-1.427q.26-.074.422-.28.161-.204.161-.477z"
};
const tools=[
 ['Adobe Premiere','Edit','premiere','#3B2B9A'],['Adobe After Effects','Motion','aftereffects','#2E1F74'],['DaVinci Resolve','Edit & colour','resolve','#233A51'],['CapCut','Edit','txt:Cc','#151515'],
 ['Adobe Illustrator','Design','illustrator','#C96B00'],['Canva','Design','canva','#00B5BD'],
 ['Higgsfield AI','AI video','txt:Hf','#3A3A3A'],['Lumina AI','AI video','txt:Lu','#6E56CF'],['Gemini','AI','gemini','#6D5BD0'],['ChatGPT','AI','openai','#10A37F'],['Claude','AI','claude','#D97757'],
 ['Final Draft 11','Screenwriting','txt:FD','#1E3A6E'],['Google Docs','Writing','docs','#4285F4'],['Google Sheets','Planning','sheets','#1E8E3E'],['Microsoft Office','Planning','office','#D83B01']
];
const tHTML=tools.map(([n,cat,k,col])=>`<div class="tool-card clay"><span class="ic" style="--tc:${col}">${k.startsWith('txt:')?`<b>${esc(k.slice(4))}</b>`:`<svg viewBox="0 0 24 24" aria-hidden="true"><path d="${IC[k]}"/></svg>`}</span><span>${esc(n)}<small>${esc(cat)}</small></span></div>`).join('');
$('#toolTrack').innerHTML=tHTML+tHTML;


/* --- timeline --- */
const tl=[
 ['2017','First film, "Dream"','Directed, shot and edited my first short in high school in Bogor.','sun'],
 ['2019','Two national-level wins','1st place at FLS2N Kab. Bogor and ILM Kemdikbud Nasional as DOP & editor.','bubble'],
 ['2020 – 2023','Wedding films','Videographer & editor at Ruang Potret, then Daynings.','mint'],
 ['2021 – 2023','Film school & set life','DOP, colourist and chief lighting on student and indie shorts in Yogyakarta.','sky'],
 ['2023 – 2025','Programmer, Bahasinema','Programming screenings, plus Festival Film Bogor 2023.','paper'],
 ['2024','Festival run','"Last Voice for Lost Light" screens at JAFF, Joyland, Islamabad and CineMAZ.','tangerine'],
 ['2025 – now','Cekat.AI','Videographer, video editor, AI video editor & motion graphic, full time.','grape'],
 ['2025 – 2026','Freelance','Motion graphics for Tempo, edits for Kodak Pixpro and SBOX.','sun']
];
$('#tl').innerHTML=tl.map(([w,h,p,c])=>`<div class="step clay" data-tilt style="--c:${c==='grape'?'#C9B8FF':`var(--${c})`}"><span class="when">${w}</span><h4>${esc(h)}</h4><p>${esc(p)}</p></div>`).join('');


/* --- scroll reveal: items pop up as they enter the viewport --- */
(()=>{
  if(reduce || !('IntersectionObserver' in window)) return;
  const sel=['.sec-head','.tv','.cap','.brands .wrap','.feature-top','.cat','.job','.feat','.early > div','.grid-head','.film','.press','.lw','.about-photo','.about-copy','.toolkit .wrap','.journey h3','.step','.extra > div','.contact-card'].join(',');
  const items=$$(sel);
  const groups=new Map();
  items.forEach(el=>{el.classList.add('rv-item');const p=el.parentElement;const i=(groups.get(p)||0);groups.set(p,i+1);el.style.setProperty('--d',Math.min(i,7)*90+'ms')});
  // anything already on screen at load shows immediately, without waiting
  const vh=innerHeight;
  items.forEach(el=>{const r=el.getBoundingClientRect(); if(r.top<vh*0.92 && r.bottom>0){el.classList.add('in');el.style.setProperty('--d','0ms')}});
  document.documentElement.classList.add('rv');
  const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add('in');io.unobserve(e.target)}}),{rootMargin:'0px 0px -8% 0px',threshold:0.08});
  items.forEach(el=>{if(!el.classList.contains('in')) io.observe(el)});
  // filters re-show hidden films: make sure they are visible
  $$('.filters button').forEach(b=>b.addEventListener('click',()=>$$('.film').forEach(f=>f.classList.add('in'))));
})();

/* --- nav: show which section you're in --- */
(()=>{
  const links=$$('.nav-links a[href^="#"]'), pill=$('.nav-pill'), now=$('#navNow'), bar=$('.nav-links');
  const secs=links.map(a=>document.querySelector(a.getAttribute('href'))).filter(Boolean);
  let cur=null;
  const place=a=>{ if(!a){pill.classList.remove('on');return}
    pill.style.width=a.offsetWidth+'px'; pill.style.setProperty('--px',a.offsetLeft+'px');
    pill.style.setProperty('--pill',`var(--${a.dataset.pill})`); pill.classList.add('on'); };
  const update=()=>{
    const line=innerHeight*.35; let idx=-1;
    secs.forEach((s,i)=>{ if(s.getBoundingClientRect().top<=line) idx=i; });
    if(innerHeight+scrollY>=document.documentElement.scrollHeight-4) idx=secs.length-1;
    const a=idx>=0?links[idx]:null;
    if(a===cur) return; cur=a;
    links.forEach(l=>{l.classList.toggle('active',l===a); if(l===a) l.setAttribute('aria-current','location'); else l.removeAttribute('aria-current')});
    place(a);
    if(a){ now.hidden=false; now.textContent=a.textContent; now.style.setProperty('--pill',`var(--${a.dataset.pill})`);
      const r=a.offsetLeft-bar.clientWidth/2+a.offsetWidth/2; bar.scrollTo({left:r,behavior:reduce?'auto':'smooth'}); }
    else now.hidden=true;
  };
  addEventListener('scroll',update,{passive:true}); addEventListener('resize',()=>{place(cur)});
  document.fonts&&document.fonts.ready.then(()=>place(cur));
  update();
})();

/* --- showreel --- */
const v=$('#reelVideo'), pb=$('#reelPlay');
pb.addEventListener('click',()=>{v.controls=true;pb.hidden=true;v.play().catch(()=>{pb.hidden=false})});
v.addEventListener('ended',()=>{pb.hidden=false;v.controls=false});

/* --- copy email --- */
$('#copyMail').addEventListener('click',e=>{
  const b=e.currentTarget, t=$('#mail').textContent;
  const done=()=>{b.textContent='Copied';setTimeout(()=>b.textContent='Copy email',1600)};
  const sel=()=>{const r=document.createRange();r.selectNodeContents($('#mail'));const s=getSelection();s.removeAllRanges();s.addRange(r);b.textContent='Selected, press Ctrl+C';setTimeout(()=>b.textContent='Copy email',2200)};
  try{navigator.clipboard.writeText(t).then(done,sel)}catch(_){sel()}
});

if(reduce) return;

/* --- tilt --- */
const bindTilt=el=>{
  el.addEventListener('pointermove',e=>{const r=el.getBoundingClientRect();const x=(e.clientX-r.left)/r.width-.5,y=(e.clientY-r.top)/r.height-.5;
    el.style.setProperty('--ry',(x*12).toFixed(2)+'deg');el.style.setProperty('--rx',(-y*12).toFixed(2)+'deg')});
  el.addEventListener('pointerleave',()=>{el.style.setProperty('--ry','0deg');el.style.setProperty('--rx','0deg')});
};
if(fine) $$('[data-tilt]').forEach(bindTilt);

/* --- magnetic chips --- */
if(fine) $$('[data-magnet]').forEach(el=>{
  el.addEventListener('pointermove',e=>{const r=el.getBoundingClientRect();el.style.transform=`translate(${(e.clientX-r.left-r.width/2)*.35}px,${(e.clientY-r.top-r.height/2)*.45}px) rotate(${(e.clientX-r.left-r.width/2)*.08}deg)`});
  el.addEventListener('pointerleave',()=>{el.style.transform=''});
});

/* --- clay toys: parallax + repel + squish + spin (spring physics) --- */
const mouse={x:innerWidth/2,y:innerHeight/2,active:false};
addEventListener('pointermove',e=>{mouse.x=e.clientX;mouse.y=e.clientY;mouse.active=true},{passive:true});
const toys=$$('.toy').map(el=>({el,x:0,y:0,vx:0,vy:0,s:1,vs:0,rot:0,vrot:0,spin:0,d:parseFloat(el.dataset.depth)||.6,base:parseFloat(el.style.getPropertyValue('--r'))||0,t:Math.random()*6}));
toys.forEach(t=>{
  t.el.addEventListener('pointerenter',()=>{t.vs-=.09;t.vrot+=(Math.random()>.5?1:-1)*3});
  t.el.addEventListener('click',()=>{t.spin+=360;t.vs-=.12});
  t.el.addEventListener('dragstart',e=>e.preventDefault());
});
let last=performance.now();
function frame(now){
  const dt=Math.min(2,(now-last)/16.67);last=now;
  const W=innerWidth,H=innerHeight;
  for(const t of toys){
    const r=t.el.getBoundingClientRect();
    if(r.bottom<-200||r.top>H+200||r.width===0) continue;
    t.t+=.016*dt;
    // idle float
    let tx=Math.sin(t.t*1.1+t.d*4)*4, ty=Math.cos(t.t*.9+t.d*3)*6;
    if(mouse.active){
      tx+=(mouse.x-W/2)*.03*t.d; ty+=(mouse.y-H/2)*.03*t.d;
      const cx=r.left+r.width/2-t.x, cy=r.top+r.height/2-t.y;
      const dx=cx-mouse.x, dy=cy-mouse.y, dist=Math.hypot(dx,dy)||1, R=Math.max(150,r.width*1.05);
      if(dist<R){const f=(1-dist/R); tx+=dx/dist*f*f*90; ty+=dy/dist*f*f*90;}
    }
    t.vx+=(tx-t.x)*.07*dt; t.vy+=(ty-t.y)*.07*dt; t.vx*=Math.pow(.84,dt); t.vy*=Math.pow(.84,dt);
    t.x+=t.vx*dt; t.y+=t.vy*dt;
    t.vs+=(1-t.s)*.18*dt; t.vs*=Math.pow(.8,dt); t.s+=t.vs*dt;
    const rt=t.base+t.spin+t.vx*1.2;
    t.vrot+=(rt-t.rot)*.08*dt; t.vrot*=Math.pow(.82,dt); t.rot+=t.vrot*dt;
    const sx=t.s, sy=2-t.s;
    t.el.style.transform=`translate3d(${t.x.toFixed(1)}px,${t.y.toFixed(1)}px,0) rotate(${t.rot.toFixed(1)}deg) scale(${sx.toFixed(3)},${sy.toFixed(3)})`;
  }
  requestAnimationFrame(frame);
}
requestAnimationFrame(frame);

/* --- paper planes & drifting lines on a fixed background canvas --- */
(()=>{
  const cv=$('#sky'); if(!cv) return; const ctx=cv.getContext('2d');
  let W=0,H=0,dpr=1;
  const resize=()=>{dpr=Math.min(2,devicePixelRatio||1);W=innerWidth;H=innerHeight;cv.width=W*dpr;cv.height=H*dpr;ctx.setTransform(dpr,0,0,dpr,0,0)};
  resize(); addEventListener('resize',resize);
  const css=getComputedStyle(document.documentElement);
  const col=n=>css.getPropertyValue('--'+n).trim();
  const palette=[['tangerine','#FFB79E'],['sky','#BFE0FF'],['bubble','#FFD0E6'],['mint','#B9EFD8'],['grape','#D9CCFF']];
  const n=W<700?2:4;
  const planes=Array.from({length:n},(_,i)=>({
    x:Math.random()*W, y:Math.random()*H, a:Math.random()*Math.PI*2, v:1.5+Math.random()*.8,
    s:W<700?.8:1+Math.random()*.35, c:col(palette[i%palette.length][0]), c2:palette[i%palette.length][1],
    seed:Math.random()*100, loop:0, trail:[]
  }));
  // slow wavy ribbons
  const ribbons=[{y:.22,amp:34,len:.006,sp:.0006,c:'rgba(156,123,255,.22)',w:2},{y:.68,amp:46,len:.004,sp:-.0004,c:'rgba(93,180,255,.22)',w:2},{y:.86,amp:24,len:.009,sp:.0008,c:'rgba(255,140,192,.2)',w:1.6}];
  function drawPlane(p){
    ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.a); ctx.scale(p.s,p.s);
    ctx.shadowColor='rgba(36,22,56,.22)'; ctx.shadowBlur=10; ctx.shadowOffsetY=8;
    // lower wing (darker)
    ctx.fillStyle=p.c; ctx.beginPath(); ctx.moveTo(18,0); ctx.lineTo(-14,12); ctx.lineTo(-7,1); ctx.closePath(); ctx.fill();
    ctx.shadowColor='transparent';
    // upper wing (light)
    ctx.fillStyle=p.c2; ctx.beginPath(); ctx.moveTo(18,0); ctx.lineTo(-14,-12); ctx.lineTo(-7,1); ctx.closePath(); ctx.fill();
    // keel fold
    ctx.fillStyle='rgba(36,22,56,.18)'; ctx.beginPath(); ctx.moveTo(18,0); ctx.lineTo(-7,1); ctx.lineTo(-10,5); ctx.closePath(); ctx.fill();
    ctx.restore();
  }
  let t=0;
  function step(){
    t++;
    ctx.clearRect(0,0,W,H);
    // ribbons
    for(const r of ribbons){
      ctx.beginPath();
      for(let x=-20;x<=W+20;x+=14){const y=r.y*H+Math.sin(x*r.len+t*r.sp*60)*r.amp+Math.sin(x*r.len*2.3-t*r.sp*40)*r.amp*.35; x<=-20?ctx.moveTo(x,y):ctx.lineTo(x,y)}
      ctx.strokeStyle=r.c; ctx.lineWidth=r.w; ctx.setLineDash([]); ctx.stroke();
    }
    for(const p of planes){
      // wander + occasional loop-de-loop
      let turn=Math.sin(t*.011+p.seed)*.018+Math.sin(t*.0037+p.seed*2)*.012;
      if(p.loop>0){turn=.075;p.loop--} else if(Math.random()<.0015){p.loop=84}
      // steer back inside the viewport
      const m=90, cx=W/2-p.x, cy=H/2-p.y;
      if(p.x<m||p.x>W-m||p.y<m||p.y>H-m){const want=Math.atan2(cy,cx);let d=want-p.a;d=Math.atan2(Math.sin(d),Math.cos(d));turn+=d*.04}
      // dodge the cursor
      if(mouse.active){const dx=p.x-mouse.x,dy=p.y-mouse.y,dist=Math.hypot(dx,dy);if(dist<160){const away=Math.atan2(dy,dx);let d=away-p.a;d=Math.atan2(Math.sin(d),Math.cos(d));turn+=d*.09*(1-dist/160);p.boost=1.8}}
      p.a+=turn; const sp=p.v*(p.boost||1); p.boost=Math.max(1,(p.boost||1)*.97);
      p.x+=Math.cos(p.a)*sp; p.y+=Math.sin(p.a)*sp;
      p.trail.push([p.x,p.y]); if(p.trail.length>90) p.trail.shift();
      // dashed trail
      if(p.trail.length>2){
        ctx.setLineDash([2,9]); ctx.lineCap='round'; ctx.lineWidth=2.2;
        for(let i=1;i<p.trail.length;i++){const a=p.trail[i-1],b=p.trail[i];ctx.globalAlpha=(i/p.trail.length)*.55;ctx.strokeStyle=p.c;ctx.beginPath();ctx.moveTo(a[0],a[1]);ctx.lineTo(b[0],b[1]);ctx.stroke()}
        ctx.globalAlpha=1; ctx.setLineDash([]);
      }
      drawPlane(p);
    }
    requestAnimationFrame(step);
  }
  requestAnimationFrame(step);
})();



/* --- cursor follower --- */
if(fine){
  const c=$('.cursor');let cx=innerWidth/2,cy=innerHeight/2;
  addEventListener('pointermove',()=>c.classList.add('on'),{once:true});
  document.addEventListener('pointerleave',()=>c.classList.remove('on'));
  document.addEventListener('pointerenter',()=>c.classList.add('on'));
  const tick=()=>{cx+=(mouse.x-cx)*.22;cy+=(mouse.y-cy)*.22;c.style.transform=`translate3d(${cx}px,${cy}px,0)`;requestAnimationFrame(tick)};tick();
  document.addEventListener('pointerover',e=>{c.classList.toggle('big',!!e.target.closest('a,button,.toy,[data-tilt],summary,.ch'))});
}
})();
</script>

</body></html>
