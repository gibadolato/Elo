<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover, interactive-widget=resizes-content">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Elo">
<meta name="format-detection" content="telephone=no">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='16' fill='%2308B8C8'/%3E%3Crect x='9' y='21' width='28' height='22' rx='11' fill='none' stroke='white' stroke-width='5'/%3E%3Crect x='27' y='21' width='28' height='22' rx='11' fill='none' stroke='%23FF9F43' stroke-width='5'/%3E%3C/svg%3E">
<meta name="theme-color" content="#08B8C8">
<title>Elo | Protótipo navegável</title>
<style>
:root{
  --c:#08B8C8; --cd:#087F8C; --cm:#38C9D4; --cl:#E8FAFC; --w:#fff;
  --t:#263238; --t2:#566A72; --bg:#F5F8F9; --line:#E1EBED;
  --o:#FF9F43; --ol:#FFF0DC; --g:#B8E986; --gs:#EAF8D9; --gd:#3F7A12;
  --sh:0 8px 24px -12px rgba(8,127,140,.28);
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html,body{height:100%}
body{font-family:"Segoe UI",Inter,system-ui,-apple-system,Roboto,Helvetica,Arial,sans-serif;color:var(--t);line-height:1.4;background:radial-gradient(1200px 700px at 15% 0%,#d7f4f7 0%,transparent 60%),radial-gradient(900px 600px at 100% 100%,#ffe9cc 0%,transparent 55%),#e9f6f8;-webkit-font-smoothing:antialiased}
button{font-family:inherit;cursor:pointer;color:inherit}
input,select,textarea{font-family:inherit;font-size:15px;color:var(--t)}
h1,h2,h3{line-height:1.15}
:focus-visible{outline:3px solid var(--o);outline-offset:2px;border-radius:10px}
.ic{flex:none;vertical-align:middle}

/* ---------- palco e moldura ---------- */
.stage{position:fixed;inset:0;display:block}
.side{display:none;width:310px;flex:none}
.side-logo{display:flex;align-items:center;gap:10px;font-size:26px;font-weight:800;color:var(--cd);margin-bottom:22px}
.side h2{font-size:26px;font-weight:800;letter-spacing:-.01em;margin-bottom:8px}
.side>p{color:var(--t2);font-size:14.5px;margin-bottom:22px}
.side-h{font-weight:700;font-size:13px;color:var(--t2);margin-bottom:8px}
.st{display:flex;align-items:center;gap:12px;width:100%;text-align:left;border:0;background:transparent;padding:9px 10px;border-radius:12px;font-size:14.5px;font-weight:600;color:var(--t2);transition:background .2s,color .2s}
.st span{display:grid;place-items:center;width:26px;height:26px;border-radius:50%;background:#fff;color:var(--cd);font-size:12.5px;font-weight:800;box-shadow:0 2px 6px rgba(8,127,140,.15)}
.st:hover{background:rgba(255,255,255,.7)}
.st.on{background:#fff;color:var(--cd);box-shadow:var(--sh)}
.st.on span{background:var(--cd);color:#fff}
.side-f{margin-top:22px;font-size:12.5px;color:var(--t2)}
.phone{position:fixed;top:0;left:0;width:100%;height:var(--app-h,100dvh);background:var(--bg);overflow:hidden;overflow:clip}
.app{position:absolute;inset:0;display:flex;flex-direction:column;overflow:hidden;overflow:clip}
.viewport{position:relative;flex:1;min-height:0;overflow:hidden;overflow:clip}
.screen{position:absolute;inset:0;overflow-y:auto;overflow-x:hidden;opacity:0;visibility:hidden;transform:translateX(26px);transition:opacity .28s ease,transform .28s ease,visibility 0s .28s;padding-bottom:30px;scrollbar-width:none;overscroll-behavior:contain}
.screen::-webkit-scrollbar{display:none}
.screen.active{opacity:1;visibility:visible;transform:none;transition:opacity .28s ease,transform .28s ease,visibility 0s}
.screen.from-left:not(.active){transform:translateX(-26px)}
.pad{padding:12px 18px 8px}
.pull{margin-top:-38px;position:relative}
.pull2{margin-top:-64px;position:relative}
.pull3{margin-top:-30px;position:relative}

/* ---------- barra inferior ---------- */
.tabbar{position:relative;z-index:5;display:flex;flex:none;background:#fff;border-top:1px solid var(--line);padding:6px 6px calc(8px + env(safe-area-inset-bottom));box-shadow:0 -8px 22px -16px rgba(8,127,140,.4)}
.tabbar.hide{display:none}
.tab{flex:1;border:0;background:none;display:flex;flex-direction:column;align-items:center;gap:2px;font-size:11.5px;font-weight:600;color:#7C8E95;padding:4px 0;border-radius:14px}
.tab .ti{display:grid;place-items:center;width:52px;height:30px;border-radius:15px;transition:background .25s,color .25s}
.tab.on{color:var(--cd)}
.tab.on .ti{background:var(--cl);color:var(--c)}

/* ---------- cabeçalhos ---------- */
.top{display:flex;align-items:center;gap:12px;padding:calc(18px + env(safe-area-inset-top)) 18px 6px}
.top-t{flex:1;min-width:0}
.top h1{font-size:19px;font-weight:800;letter-spacing:-.01em}
.top.big h1{font-size:26px}
.top p{font-size:13px;color:var(--t2);margin-top:2px}
.iconbtn{position:relative;flex:none;width:42px;height:42px;border:0;border-radius:14px;background:#fff;color:var(--cd);display:grid;place-items:center;box-shadow:var(--sh);transition:transform .12s}
.iconbtn:active{transform:scale(.94)}
.iconbtn.glass{background:rgba(255,255,255,.2);color:#fff;box-shadow:none;backdrop-filter:blur(6px)}
.iconbtn .dot{position:absolute;top:9px;right:10px;width:9px;height:9px;border-radius:50%;background:var(--o);border:2px solid #0a98a7}
.hero{background:linear-gradient(150deg,var(--cd) 0%,var(--c) 68%,var(--cm) 100%);color:#fff;border-radius:0 0 34px 34px;padding:calc(16px + env(safe-area-inset-top)) 22px 56px}
.hh-top{display:flex;align-items:center;gap:10px}
.hh-sp{flex:1}
.home-hero h1{font-size:29px;font-weight:800;letter-spacing:-.02em;margin-top:16px}
.hh-school{display:flex;align-items:center;gap:6px;margin-top:18px;font-size:13.5px;font-weight:600;opacity:.92}
.hh-sub{font-size:14.5px;opacity:.92;margin-top:5px}
.sec{font-size:16px;font-weight:800;margin:22px 2px 10px}

/* ---------- cartões, avatares e chips ---------- */
.card{background:#fff;border-radius:20px;padding:16px;box-shadow:var(--sh);margin-bottom:14px}
.card h3{font-size:15px;font-weight:800;margin-bottom:8px}
.card h3:not(:first-child){margin-top:14px}
.hov{cursor:pointer;transition:transform .2s,box-shadow .2s}
@media(hover:hover){.hov:hover{transform:translateY(-2px);box-shadow:0 14px 28px -14px rgba(8,127,140,.45)}}
.txt{font-size:14.5px;color:var(--t2);line-height:1.5}
.avatar{display:grid;place-items:center;border-radius:50%;font-weight:800;color:#fff;flex:none;border:0;width:44px;height:44px;font-size:15px}
.avatar.sm{width:40px;height:40px;font-size:14px}
.avatar.md{width:52px;height:52px;font-size:17px}
.avatar.lg{width:64px;height:64px;font-size:21px}
.avatar.xl{width:92px;height:92px;font-size:32px;border:4px solid #fff;box-shadow:0 8px 20px -8px rgba(8,127,140,.55)}
.a1{background:var(--cd)}.a2{background:var(--o);color:#3a2300}.a3{background:var(--g);color:#2d5a0a}.a4{background:var(--cm);color:#05393f}.a5{background:#37505a}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:8px}
.tags.center{justify-content:center}
.tag{display:inline-flex;align-items:center;gap:5px;background:var(--cl);color:var(--cd);font-size:12.5px;font-weight:700;padding:4px 10px;border-radius:999px}
.tag.ok{background:var(--gs);color:var(--gd)}
.tag.warn{background:var(--ol);color:#9a5300}
.tag.light{background:rgba(255,255,255,.22);color:#fff}
.dotg{display:inline-block;width:7px;height:7px;border-radius:50%;background:#5DB521}
.chips{display:flex;gap:8px;margin:12px 0 4px}
.chips.scroll{overflow-x:auto;scrollbar-width:none;margin-left:-18px;margin-right:-18px;padding:2px 18px 6px}
.chips.scroll::-webkit-scrollbar{display:none}
.chip{flex:none;display:inline-flex;align-items:center;gap:6px;border:1.5px solid var(--line);background:#fff;color:var(--t);border-radius:999px;padding:8px 13px;font-size:13.5px;font-weight:600;transition:all .18s}
.chip.on{background:var(--cd);border-color:var(--cd);color:#fff}
.chip.on .dotg{background:var(--g)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;border:0;border-radius:14px;padding:13px 18px;min-height:48px;font-size:15px;font-weight:700;line-height:1.2;transition:transform .12s,box-shadow .2s,background .2s}
.btn.block{display:flex;width:100%;margin-top:10px}
.btn.primary{background:var(--cd);color:#fff;box-shadow:0 10px 20px -10px rgba(8,127,140,.8)}
.btn.orange{background:var(--o);color:#3a2300;box-shadow:0 10px 20px -12px rgba(255,159,67,.9)}
.btn.soft{background:var(--cl);color:var(--cd)}
.btn.ghost{background:transparent;color:var(--cd);border:1.5px solid #BDE7EC}
.btn.done{background:var(--gs);color:var(--gd);box-shadow:none}
.btn.mini{min-height:38px;padding:8px 13px;font-size:13.5px;border-radius:12px}
.btn:active{transform:scale(.97)}
.btn:disabled{opacity:.55;cursor:not-allowed}
.btn.done:disabled{opacity:1;cursor:default}
.link{background:none;border:0;color:var(--cd);font-weight:700;font-size:14px;padding:8px 2px;text-decoration:underline;text-underline-offset:3px}
.spin{width:18px;height:18px;border-radius:50%;border:3px solid rgba(255,255,255,.4);border-top-color:#fff;animation:rot .8s linear infinite;display:inline-block}
.spin.big{width:54px;height:54px;border-width:5px;border-color:var(--cl);border-top-color:var(--c)}
@keyframes rot{to{transform:rotate(360deg)}}

/* ---------- barras e linhas do tempo ---------- */
.bar{height:9px;border-radius:9px;background:var(--cl);overflow:hidden}
.bar i{display:block;height:100%;width:0;border-radius:9px;background:linear-gradient(90deg,var(--c),var(--g));transition:width 1s cubic-bezier(.2,.8,.2,1)}
.bar.big{height:7px;margin:4px 0 14px}
.mbar{margin-bottom:12px}
.mb-h{display:flex;justify-content:space-between;font-size:14px;font-weight:600;margin-bottom:6px}
.mb-h b{color:var(--cd)}
.mbar.warn .bar i{background:linear-gradient(90deg,var(--o),#ffc27d)}
.mbar.warn .mb-h b{color:#b86300}
.tl{list-style:none;position:relative}
.tl li{position:relative;display:flex;gap:12px;padding:0 0 16px}
.tl li:last-child{padding-bottom:0}
.tl li:not(:last-child)::before{content:"";position:absolute;left:10px;top:22px;bottom:0;width:2px;background:var(--line)}
.tl li.done:not(:last-child)::before{background:var(--g)}
.tl-dot{flex:none;width:22px;height:22px;border-radius:50%;border:2px solid #C9D8DB;background:#fff;display:grid;place-items:center;color:var(--gd)}
.tl li.done .tl-dot{background:var(--g);border-color:var(--g)}
.tl li.doing .tl-dot{border-color:var(--c);box-shadow:0 0 0 5px rgba(8,184,200,.18)}
.tl b{font-size:14.5px;display:block}
.tl small{font-size:12.5px;color:var(--t2)}

/* ---------- formulários, busca e abas ---------- */
.field{margin-bottom:14px}
.field label,.lbl{display:block;font-size:13.5px;font-weight:700;margin-bottom:6px}
.field input,.inp,.selw select,.ta{width:100%;border:1.5px solid var(--line);background:#fff;border-radius:14px;padding:13px 14px;outline:none;transition:border-color .2s,box-shadow .2s}
.field input:focus,.inp:focus,.selw select:focus,.ta:focus{border-color:var(--c);box-shadow:0 0 0 4px rgba(8,184,200,.15)}
.field input.bad{border-color:#E4572E}
.err{display:block;color:#C23B15;font-size:12.5px;font-weight:600;margin-top:5px;min-height:0}
.selw{position:relative}
.selw select{appearance:none;-webkit-appearance:none;padding-right:40px}
.selw .ic{position:absolute;right:13px;top:50%;transform:translateY(-50%);pointer-events:none;color:var(--t2)}
.ta{resize:none;line-height:1.5;margin-bottom:6px}
.seg{display:flex;background:#E4EEF0;border-radius:14px;padding:4px;margin-bottom:14px}
.seg button{flex:1;border:0;background:transparent;border-radius:11px;padding:9px;font-weight:700;font-size:14px;color:var(--t2);transition:all .2s}
.seg button.on{background:#fff;color:var(--cd);box-shadow:0 4px 10px -4px rgba(8,127,140,.35)}
.tabs2{display:flex;gap:6px;margin-bottom:14px;border-bottom:1.5px solid var(--line)}
.tabs2 button{border:0;background:none;padding:10px 6px;margin-right:12px;font-weight:700;font-size:14.5px;color:var(--t2);border-bottom:3px solid transparent;margin-bottom:-1.5px}
.tabs2 button.on{color:var(--cd);border-color:var(--c)}
.tabs2 i{font-style:normal;display:inline-grid;place-items:center;min-width:20px;height:20px;border-radius:10px;background:var(--o);color:#3a2300;font-size:12px;padding:0 5px;margin-left:4px}
.search{display:flex;align-items:center;gap:10px;background:#fff;border:1.5px solid var(--line);border-radius:16px;padding:0 14px;color:var(--t2);margin-top:12px}
.search:focus-within{border-color:var(--c);box-shadow:0 0 0 4px rgba(8,184,200,.15)}
.search input{flex:1;border:0;outline:0;padding:13px 0;background:transparent;min-width:0}
.count{font-size:13px;color:var(--t2);margin:6px 2px 10px}
.empty{display:flex;flex-direction:column;align-items:center;text-align:center;gap:6px;padding:34px 18px;color:var(--t2)}
.empty b{color:var(--t);font-size:16px}
.empty .btn{margin-top:8px}
.note{display:flex;gap:10px;align-items:flex-start;background:#fff;border:1.5px dashed #BFDDE2;border-radius:16px;padding:12px 14px;font-size:13.5px;color:var(--t2);margin-top:6px}
.note .ic{color:var(--c);margin-top:1px}
.banner{display:flex;gap:10px;align-items:flex-start;background:var(--ol);color:#7a4300;border-radius:16px;padding:12px 14px;font-size:14px;font-weight:600;margin-bottom:14px}
.fine{text-align:center;font-size:12.5px;color:var(--t2);margin-top:12px}

/* ---------- splash e onboarding ---------- */
.splash{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;color:#fff;background:linear-gradient(160deg,var(--cd) 0%,var(--c) 62%,var(--cm) 100%);padding:30px}
.splash h1{font-size:54px;font-weight:800;letter-spacing:-.03em;margin-top:6px;animation:fadein .8s .9s both}
.splash p{font-size:17px;font-weight:600;opacity:.95;animation:fadein .8s 1.2s both}
.logo-wrap svg rect{transform-box:fill-box}
.logo-wrap svg rect:first-child{animation:linkA 1s cubic-bezier(.2,.8,.2,1) both}
.logo-wrap svg rect:last-child{animation:linkB 1s cubic-bezier(.2,.8,.2,1) both}
@keyframes linkA{from{transform:translateX(-30px);opacity:0}to{transform:none;opacity:1}}
@keyframes linkB{from{transform:translateX(30px);opacity:0}to{transform:none;opacity:1}}
@keyframes fadein{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.loadbar{width:120px;height:5px;border-radius:5px;background:rgba(255,255,255,.3);margin-top:34px;overflow:hidden;animation:fadein .6s 1.4s both}
.loadbar i{display:block;height:100%;background:#fff;border-radius:5px;animation:load 2.4s ease-out .4s both}
@keyframes load{from{width:0}to{width:100%}}
.splash-skip{position:absolute;bottom:calc(26px + env(safe-area-inset-bottom));background:none;border:0;color:#fff;opacity:.85;font-size:13.5px;font-weight:600}
.ob{position:absolute;inset:0;display:flex;flex-direction:column;padding:calc(20px + env(safe-area-inset-top)) 24px calc(24px + env(safe-area-inset-bottom));background:var(--bg)}
.ob-top{display:flex;justify-content:space-between;align-items:center}
.ob-count{font-size:13.5px;font-weight:700;color:var(--t2)}
.ob-art{flex:1;min-height:0;display:grid;place-items:center;margin:12px -8px;border-radius:30px;background:linear-gradient(150deg,var(--c),var(--cm));padding:16px}
.ob-art svg{width:100%;max-height:100%}
.ob-art .n{animation:floaty 3s ease-in-out infinite;transform-box:fill-box;transform-origin:center}
.ob-art .n2{animation-delay:.5s}.ob-art .n3{animation-delay:1s}.ob-art .n4{animation-delay:1.5s}.ob-art .n5{animation-delay:.8s}
@keyframes floaty{50%{transform:translateY(-6px)}}
.ob-art .w{transform-box:fill-box;transform-origin:center bottom;animation:wv 1.2s ease-in-out infinite;animation-delay:calc(var(--i)*.09s)}
@keyframes wv{50%{transform:scaleY(.45)}}
.ob-body h1{font-size:27px;font-weight:800;letter-spacing:-.02em;margin-bottom:8px}
.ob-body p{font-size:15.5px;color:var(--t2);line-height:1.5}
.ob-foot{display:flex;align-items:center;justify-content:space-between;margin-top:20px}
.dots{display:flex;gap:7px}
.dots i{width:8px;height:8px;border-radius:8px;background:#C9DADE;transition:all .3s}
.dots i.on{width:26px;background:var(--c)}
.ob-foot .btn{min-width:140px}
.cad{padding:calc(16px + env(safe-area-inset-top)) 22px 26px}
.cad-h{margin:16px 0 20px}
.cad-logo{width:56px;height:56px;border-radius:18px;background:var(--cl);display:grid;place-items:center;margin-bottom:14px}
.cad-h h1{font-size:27px;font-weight:800;letter-spacing:-.02em;margin-bottom:6px}
.cad-h p{color:var(--t2);font-size:14.5px}
.shake{animation:shake .4s}
@keyframes shake{25%{transform:translateX(-6px)}75%{transform:translateX(6px)}}

/* ---------- início ---------- */
.jcard{padding:18px}
.jhead{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:12px}
.jhead h2{font-size:19px;font-weight:800}
.jhead p{font-size:13px;color:var(--t2);margin-top:3px}
.jpct{font-size:34px;font-weight:800;letter-spacing:-.03em;color:var(--cd)}
.chain{width:100%;height:auto;display:block;margin:2px 0 12px}
.chain .pulse{animation:pls 1.8s ease-in-out infinite}
@keyframes pls{50%{opacity:.55}}
.jlist{display:flex;flex-direction:column;gap:6px}
.jrow{display:flex;align-items:center;gap:12px;width:100%;border:0;background:var(--bg);border-radius:14px;padding:11px 12px;text-align:left;transition:background .2s,transform .12s}
.jrow:active{transform:scale(.98)}
.jn{display:grid;place-items:center;width:26px;height:26px;border-radius:50%;background:#fff;font-size:13px;font-weight:800;color:var(--cd)}
.jl{flex:1;font-size:14.5px;font-weight:700}
.jst{font-size:12px;color:var(--t2);font-weight:600}
.jrow.done .jst{color:var(--gd)}
.sti{display:grid;place-items:center;width:22px;height:22px;border-radius:50%;background:var(--g);color:#2d5a0a}
.sti.doing{background:var(--cl);border:2px solid var(--c)}
.sti.doing i{width:8px;height:8px;border-radius:50%;background:var(--c);animation:pls 1.4s infinite}
.sti.todo{background:#fff;border:2px solid #CBDADD}
.next{display:grid;grid-template-columns:auto 1fr;gap:12px 14px;align-items:center;background:var(--ol);border-radius:20px;padding:16px}
.next .btn{grid-column:1/-1}
.next-ic{width:44px;height:44px;border-radius:14px;background:var(--o);color:#3a2300;display:grid;place-items:center}
.next-b b{font-size:15.5px;display:block;margin-bottom:3px}
.next-b p{font-size:13.5px;color:#7a5320}
.next.ok{background:var(--gs)}
.next.ok .next-ic{background:var(--g);color:#2d5a0a}
.next.ok .next-b p{color:#4c6b2c}
.scs{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.sc{display:flex;flex-direction:column;align-items:flex-start;gap:12px;background:#fff;border:0;border-radius:20px;padding:15px;text-align:left;box-shadow:var(--sh);transition:transform .15s}
.sc:active{transform:scale(.97)}
.sc b{font-size:14.5px;line-height:1.25}
.scb{display:grid;place-items:center;width:44px;height:44px;border-radius:14px;flex:none}
.scb.c{background:var(--cl);color:var(--cd)}.scb.o{background:var(--ol);color:#b86300}.scb.g{background:var(--gs);color:var(--gd)}
.evmini{display:flex;align-items:center;gap:14px;width:100%;background:#fff;border:0;border-radius:20px;padding:14px;text-align:left;box-shadow:var(--sh);margin-bottom:14px}
.evmini>div:nth-child(2){flex:1;min-width:0}
.evmini b{font-size:14.5px}
.evmini p{font-size:13px;color:var(--t2);margin-top:2px}
.datebox{flex:none;width:52px;height:56px;border-radius:15px;background:var(--cd);color:#fff;display:flex;flex-direction:column;align-items:center;justify-content:center}
.datebox b{font-size:20px;line-height:1}
.datebox span{font-size:12px;font-weight:600;opacity:.9;margin-top:2px}
.datebox.alt{background:var(--cl);color:var(--cd)}

/* ---------- rede e perfis ---------- */
.netcount{display:flex;align-items:center;gap:14px;background:linear-gradient(140deg,var(--cd),var(--c));color:#fff;border-radius:20px;padding:14px 16px}
.nc-ic{width:46px;height:46px;border-radius:15px;background:rgba(255,255,255,.2);display:grid;place-items:center;flex:none}
.netcount b{display:block;font-size:16.5px}
.netcount span{font-size:13px;opacity:.92}
.pro{display:flex;align-items:center;gap:12px;padding:14px}
.pro-b{flex:1;min-width:0}
.pro-b h3{font-size:15.5px;margin:0 !important}
.pro-b p{font-size:13.5px;color:var(--t2)}
.pro-b .co{display:flex;align-items:center;gap:5px;font-size:13px;margin-top:1px}
.pro-b .tags{margin-top:6px}
.pro-b .tag{font-size:12px;padding:3px 8px}
.pro-hero{padding-bottom:84px}
.pro-main{display:flex;flex-direction:column;align-items:center;text-align:center;padding-top:0}
.pro-main .avatar{margin-top:-46px}
.pro-main h1{font-size:23px;font-weight:800;margin-top:10px}
.role{color:var(--t2);font-size:14.5px;margin-top:3px}
.schoollink{display:flex;gap:12px;align-items:flex-start;background:var(--cl);color:var(--cd);border-radius:18px;padding:13px 14px;margin-bottom:14px}
.schoollink p{font-size:13.5px;color:#0b5560;line-height:1.45}
.traj{display:grid;grid-template-rows:0fr;transition:grid-template-rows .4s ease}
.traj.open{grid-template-rows:1fr}
.traj-in{overflow:hidden}
.acts{margin-top:4px}

/* ---------- networking ---------- */
.ev{display:flex;gap:13px;align-items:flex-start;padding:14px}
.ev-b{flex:1;min-width:0}
.ev-b h3{font-size:16px;margin:7px 0 2px !important}
.ev-b p{font-size:13.5px;color:var(--t2)}
.ev-m{display:flex;flex-wrap:wrap;gap:6px 14px;font-size:12.5px;color:var(--t2);margin-top:9px}
.ev-m span{display:inline-flex;align-items:center;gap:5px}
.ev-m.big{font-size:14px;margin:12px 0}
.ev .btn{align-self:flex-end;position:absolute;right:14px;bottom:14px}
.ev{position:relative;padding-bottom:64px}

/* ---------- padrinho ---------- */
.padc-h{display:flex;gap:14px;align-items:center;margin-bottom:14px}
.padc-h h2{font-size:19px;font-weight:800}
.padc-h p{font-size:13.5px;color:var(--t2);margin:2px 0 4px}
.stats3{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:6px}
.stats3>div{background:var(--bg);border-radius:14px;padding:11px 8px;text-align:center}
.stats3 b{display:block;font-size:21px;font-weight:800;color:var(--cd);letter-spacing:-.02em}
.stats3 b.gr{color:var(--gd)}
.stats3 span{font-size:11.5px;color:var(--t2);line-height:1.25;display:block;margin-top:3px}
.stats3.p3{margin-bottom:14px}
.pfs{display:flex;flex-direction:column;gap:10px;margin-bottom:14px}
.pf{display:flex;gap:12px;background:#fff;border-radius:18px;padding:13px 14px;box-shadow:var(--sh)}
.pf-ic{flex:none;width:32px;height:32px;border-radius:11px;display:grid;place-items:center}
.pf.ok .pf-ic{background:var(--gs);color:var(--gd)}
.pf.warn .pf-ic{background:var(--ol);color:#b86300}
.pf b{font-size:14.5px}
.pf p{font-size:13.5px;color:var(--t2);margin-top:2px}

/* ---------- simulação ---------- */
.sim-hero{border-radius:24px;padding:20px;margin:6px 0 14px;position:relative;overflow:hidden}
.sim-hero h2{font-size:24px;font-weight:800;letter-spacing:-.02em;margin:12px 0 5px}
.sim-hero p{font-size:14.5px;opacity:.95}
.aitag{display:inline-flex;align-items:center;gap:6px;background:rgba(255,255,255,.2);color:#fff;font-size:12.5px;font-weight:700;padding:5px 11px;border-radius:999px}
.aitag.sm{background:var(--cl);color:var(--cd);padding:5px 9px;font-size:12px;flex:none}
.wave{display:flex;align-items:center;gap:4px;height:40px;margin-top:16px}
.wave i{flex:1;height:100%;border-radius:4px;background:rgba(255,255,255,.55);transform-origin:center;animation:wv2 1.3s ease-in-out infinite;animation-delay:calc(var(--i)*.07s)}
@keyframes wv2{0%,100%{transform:scaleY(.18)}50%{transform:scaleY(1)}}
.mut{display:flex;align-items:center;gap:12px;padding:13px 14px}
.mut-ic{width:42px;height:42px;border-radius:14px;background:var(--ol);color:#b86300;display:grid;place-items:center;flex:none}
.mut-b{flex:1;min-width:0}
.mut-b b{font-size:14.5px}
.mut-b p{font-size:13px;color:var(--t2)}
.sess h3{font-size:17px !important;margin-bottom:10px}
.metas{display:flex;flex-wrap:wrap;gap:8px 14px;font-size:13px;color:var(--t2);margin-bottom:6px}
.metas span{display:inline-flex;align-items:center;gap:5px}
.qcard{background:linear-gradient(150deg,var(--cd),var(--c));color:#fff;border-radius:22px;padding:18px;margin:6px 0 16px}
.qcard small{font-size:13px;font-weight:600;opacity:.9}
.qcard h2{font-size:20px;font-weight:800;line-height:1.3;margin-top:6px;letter-spacing:-.01em}
.micro{display:flex;align-items:center;gap:8px;background:var(--gs);color:var(--gd);font-size:13.5px;font-weight:700;border-radius:12px;padding:9px 12px;margin-bottom:12px}
.ta-meta{display:flex;justify-content:space-between;align-items:center;font-size:12.5px;color:var(--t2)}
.tip{display:flex;gap:7px;align-items:center;font-size:13px;color:var(--t2);margin:6px 0 4px}
.tip .ic{color:var(--o)}
.score{display:flex;flex-direction:column;gap:14px;margin:6px 0 14px;border-radius:24px;padding:22px 20px}
.score-n b{font-size:56px;font-weight:800;letter-spacing:-.04em;line-height:1;display:block}
.score-n span{font-size:14px;opacity:.92}
.up{display:flex;gap:10px;align-items:center;background:var(--g);color:#244a07;border-radius:14px;padding:11px 13px;font-size:14.5px}
.qn{display:flex;gap:10px;align-items:flex-start;margin-top:12px}
.qn p{font-size:13.5px;color:var(--t2)}
.qn p b{color:var(--t)}
.qn span{flex:none;width:26px;height:26px;border-radius:9px;display:grid;place-items:center}
.qn .ok{background:var(--gs);color:var(--gd)}.qn .wn{background:var(--ol);color:#b86300}
.loading-full{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;gap:10px;padding:30px;background:var(--bg)}
.loading-full h2{font-size:21px;font-weight:800}
.loading-full p{color:var(--t2);font-size:14.5px;max-width:260px}
.orb{width:74px;height:74px;border-radius:50%;background:radial-gradient(circle at 30% 30%,var(--cm),var(--cd));animation:orb 1.6s ease-in-out infinite;margin-bottom:8px}
@keyframes orb{50%{transform:scale(1.12);box-shadow:0 0 0 18px rgba(8,184,200,.15)}}
.typing{display:flex;gap:6px;margin-top:6px}
.typing i{width:9px;height:9px;border-radius:50%;background:var(--c);animation:bnc 1s infinite}
.typing i:nth-child(2){animation-delay:.15s}.typing i:nth-child(3){animation-delay:.3s}
@keyframes bnc{50%{transform:translateY(-6px);opacity:.5}}

/* ---------- evolução ---------- */
.tiles{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px}
.tile{background:#fff;border-radius:18px;padding:13px 14px;box-shadow:var(--sh)}
.tile b{display:block;font-size:24px;font-weight:800;color:var(--cd);letter-spacing:-.02em}
.tile span{font-size:12.5px;color:var(--t2)}
.chart{width:100%;height:auto;display:block;margin-top:6px}
.chart .gl{stroke:var(--line);stroke-width:1}
.chart .gt{fill:#7C8E95;font-size:10px}
.chart .ar{fill:rgba(8,184,200,.12)}
.chart .ln{fill:none;stroke:var(--c);stroke-width:3;stroke-linecap:round;stroke-linejoin:round;stroke-dasharray:1;stroke-dashoffset:1;transition:stroke-dashoffset 1.3s ease}
.chart .ln.go{stroke-dashoffset:0}
.chart .pt{fill:#fff;stroke:var(--c);stroke-width:3}
.chart .pt.last{fill:var(--g);stroke:var(--gd)}
.chart .cv{fill:var(--t);font-size:11px;font-weight:700}
.msg{display:flex;gap:12px;align-items:center;background:var(--gs);color:#244a07;border-radius:18px;padding:14px 16px;margin-bottom:14px;font-size:15px}

/* ---------- carta e verificação ---------- */
.paper{position:relative;background:#fff;border-radius:20px;padding:20px 18px 18px;box-shadow:0 18px 40px -22px rgba(8,127,140,.55);border:1px solid var(--line);overflow:hidden}
.paper.draft{background:repeating-linear-gradient(135deg,#fff 0 12px,#F5F8F9 12px 24px);border-style:dashed}
.paper-h{display:flex;justify-content:space-between;align-items:center;font-size:12px;color:var(--t2);padding-bottom:12px;border-bottom:1px solid var(--line)}
.plogo{display:inline-flex;align-items:center;gap:6px;font-size:18px;color:var(--cd)}
.paper h2{font-size:21px;font-weight:800;margin:16px 0 12px;letter-spacing:-.01em}
.meta{display:grid;grid-template-columns:1fr 1fr;gap:12px 14px;margin-bottom:14px}
.meta dt{font-size:12px;color:var(--t2);font-weight:600}
.meta dd{font-size:14.5px;font-weight:700}
.meta dd small{display:block;font-size:12px;font-weight:500;color:var(--t2)}
.paper .body{font-size:14px;line-height:1.55;color:#3a4a50}
.paper-f{display:flex;justify-content:space-between;align-items:flex-end;gap:12px;margin-top:18px}
.sig i{font-family:"Segoe Script","Brush Script MT",cursive;font-size:21px;color:var(--cd);display:block}
.sig small{font-size:12px;color:var(--t2)}
.qrbox{display:flex;flex-direction:column;align-items:center;gap:5px;background:#fff;border:1.5px solid var(--line);border-radius:14px;padding:7px;transition:transform .15s}
.qrbox:not(.off):hover{transform:scale(1.03)}
.qrbox small{font-size:10.5px;color:var(--t2);font-weight:600}
.qrbox.off{width:104px;height:122px;justify-content:center;color:#9bb0b6;cursor:not-allowed}
.stamp{display:inline-flex;align-items:center;gap:6px;border:2.5px solid var(--gd);color:var(--gd);background:rgba(234,248,217,.85);border-radius:12px;padding:5px 11px;margin:-2px 0 14px;font-weight:800;font-size:13px;letter-spacing:.04em;transform:rotate(-3deg);animation:stamp .5s .2s cubic-bezier(.3,1.6,.5,1) both}
@keyframes stamp{from{transform:rotate(-3deg) scale(2.2);opacity:0}to{transform:rotate(-3deg) scale(1);opacity:1}}
.hint{display:flex;gap:8px;align-items:center;justify-content:center;text-align:center;font-size:13.5px;color:var(--t2);margin:14px 0 4px}
.hint .ic{color:var(--gd);flex:none}
.trio{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:10px}
.trio .btn{flex-direction:column;gap:4px;font-size:12.5px;padding:10px 4px;min-height:60px}
.vbar{display:flex;align-items:center;gap:10px;padding:calc(14px + env(safe-area-inset-top)) 16px 8px}
.url{flex:1;display:flex;align-items:center;gap:7px;background:#fff;border-radius:12px;padding:11px 12px;font-size:12.5px;color:var(--t2);font-weight:600;box-shadow:var(--sh);min-width:0;overflow:hidden;white-space:nowrap}
.url .ic{color:var(--gd);flex:none}
.vok,.success{display:flex;flex-direction:column;align-items:center;text-align:center;padding:22px 0 20px}
.vok h1,.success h1{font-size:25px;font-weight:800;margin-top:14px}
.vok p,.success p{color:var(--t2);font-size:15px;margin-top:3px}
.vcheck{width:82px;height:82px;border-radius:50%;background:var(--g);color:#2d5a0a;display:grid;place-items:center;animation:pop .6s cubic-bezier(.3,1.6,.5,1) both;box-shadow:0 0 0 12px rgba(184,233,134,.35)}
@keyframes pop{from{transform:scale(.3);opacity:0}to{transform:none;opacity:1}}
.vrow{display:flex;justify-content:space-between;gap:14px;padding:12px 2px;border-bottom:1px solid var(--line);font-size:14.5px}
.vrow:last-child{border:0}
.vrow span{color:var(--t2)}
.vrow b{text-align:right}
.okt{display:inline-flex;align-items:center;gap:5px;color:var(--gd)}

/* ---------- candidatura e perfil ---------- */
.vaga{display:flex;gap:12px;width:100%;text-align:left;background:#fff;border:2px solid transparent;border-radius:18px;padding:14px;margin-bottom:10px;box-shadow:var(--sh);transition:border-color .2s}
.vaga.on{border-color:var(--c);background:#F2FCFD}
.vaga b{font-size:15px}
.vaga p{font-size:13px;color:var(--t2);margin:2px 0 6px}
.radio{flex:none;width:22px;height:22px;border-radius:50%;border:2px solid #BCCDD1;margin-top:2px;display:grid;place-items:center}
.vaga.on .radio{border-color:var(--c)}
.vaga.on .radio::after{content:"";width:11px;height:11px;border-radius:50%;background:var(--c)}
.sws{padding:6px 16px}
.swrow{display:flex;align-items:center;justify-content:space-between;gap:12px;width:100%;border:0;background:none;padding:12px 0;text-align:left}
.swrow+.swrow{border-top:1px solid var(--line)}
.swrow b{font-size:14.5px;display:block}
.swrow small{font-size:12.5px;color:var(--t2)}
.swrow:disabled{opacity:.55;cursor:not-allowed}
.sw{flex:none;width:46px;height:28px;border-radius:14px;background:#CBDADD;position:relative;transition:background .2s}
.sw i{position:absolute;left:3px;top:3px;width:22px;height:22px;border-radius:50%;background:#fff;transition:transform .2s;box-shadow:0 2px 5px rgba(0,0,0,.2)}
.sw.on{background:var(--c)}
.sw.on i{transform:translateX(18px)}
.prof-hero{text-align:center;padding-bottom:50px}
.prof-hero .hh-top{margin-bottom:6px}
.prof-hero .avatar{margin:0 auto}
.prof-hero h1{font-size:25px;font-weight:800;margin-top:12px}
.prof-hero .btn{margin-top:14px}
.rowl{display:flex;align-items:center;gap:12px;width:100%;border:0;background:none;text-align:left;padding:8px 0}
.rowl>div{flex:1;min-width:0}
.rowl b{font-size:14.5px}
.rowl p{font-size:13px;color:var(--t2)}
.card .link{display:block;margin-top:6px}

/* ---------- camadas: folha, modal, menu, toast ---------- */
.ov{position:absolute;inset:0;z-index:30;display:flex;align-items:flex-end;visibility:hidden}
.ov.open{visibility:visible}
.ov-bg{position:absolute;inset:0;background:rgba(18,40,46,.5);opacity:0;transition:opacity .25s}
.ov.open .ov-bg{opacity:1}
.sheet{position:relative;width:100%;max-height:86%;overflow-y:auto;background:#fff;border-radius:28px 28px 0 0;padding:10px 20px calc(22px + env(safe-area-inset-bottom));transform:translateY(100%);transition:transform .32s cubic-bezier(.2,.8,.2,1);scrollbar-width:none}
.ov.open .sheet{transform:none}
.sheet h2{font-size:21px;font-weight:800;margin:6px 0 8px;letter-spacing:-.01em}
.sheet h3{font-size:15px;margin:14px 0 8px}
.sheet .btn.block{margin-top:14px}
.grab{width:42px;height:5px;border-radius:5px;background:#D5E1E4;margin:4px auto 10px}
.sheet.modal{margin:auto 20px;width:calc(100% - 40px);border-radius:26px;text-align:center;padding-top:24px;transform:scale(.9);opacity:0;transition:transform .25s,opacity .25s}
.ov.open .sheet.modal{transform:none;opacity:1}
.ov:has(.sheet.modal){align-items:center}
.sheet.modal .grab{display:none}
.mdl-i{width:56px;height:56px;border-radius:18px;background:var(--cl);color:var(--cd);display:grid;place-items:center;margin:0 auto 12px}
.mdl-a{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:18px}
.opts{display:flex;flex-direction:column;gap:8px;margin:12px 0 4px}
.opt{display:flex;align-items:center;justify-content:space-between;gap:12px;width:100%;text-align:left;border:1.5px solid var(--line);background:#fff;border-radius:14px;padding:13px 14px;font-size:15px;font-weight:600;transition:all .15s}
.opt span{flex:1}
.opt small{display:block;font-size:12.5px;color:var(--t2);font-weight:500}
.opt.on{border-color:var(--c);background:#F2FCFD;color:var(--cd)}
.slots{display:flex;flex-direction:column;gap:8px;margin:12px 0}
.slot{border:1.5px solid var(--line);background:#fff;border-radius:14px;padding:12px 14px;font-size:15px;font-weight:700;text-align:left}
.slot.on{border-color:var(--c);background:#F2FCFD;color:var(--cd)}
.nlist{display:flex;flex-direction:column;gap:14px;margin-top:12px}
.nitem{display:flex;gap:12px}
.nitem b{font-size:14.5px}
.nitem p{font-size:13px;color:var(--t2)}
.attach{display:flex;flex-direction:column;gap:8px;background:var(--gs);border-radius:14px;padding:12px 14px;margin:12px 0;font-size:14px;color:#2d5a0a}
.attach div{display:flex;gap:8px;align-items:center}
.guests{display:flex;flex-direction:column;gap:8px}
.guests div{display:flex;align-items:center;gap:10px;font-size:14.5px;font-weight:600}
.drawer{position:absolute;inset:0;z-index:40;visibility:hidden}
.drawer.open{visibility:visible}
.dr-bg{position:absolute;inset:0;background:rgba(18,40,46,.5);opacity:0;transition:opacity .25s}
.drawer.open .dr-bg{opacity:1}
#dr{position:absolute;top:0;right:0;bottom:0;width:78%;background:#fff;border-radius:28px 0 0 28px;transform:translateX(100%);transition:transform .32s cubic-bezier(.2,.8,.2,1);display:flex;flex-direction:column;padding-bottom:calc(16px + env(safe-area-inset-bottom));overflow-y:auto}
.drawer.open #dr{transform:none}
.dr-h{display:flex;align-items:center;gap:10px;padding:calc(18px + env(safe-area-inset-top)) 18px 16px;background:linear-gradient(150deg,var(--cd),var(--c));color:#fff;border-radius:0 0 0 28px;font-size:22px;font-weight:800}
.dr-h b{flex:1}
#dr nav{padding:10px;display:flex;flex-direction:column;gap:2px;flex:1}
#dr nav button{display:flex;align-items:center;gap:13px;border:0;background:none;padding:12px;border-radius:14px;font-size:15px;font-weight:600;text-align:left}
#dr nav button:hover,#dr nav button:active{background:var(--cl);color:var(--cd)}
.dr-reset{margin:0 14px;display:flex;align-items:center;gap:10px;border:1.5px solid var(--line);background:#fff;border-radius:14px;padding:12px;font-weight:700;color:var(--t2)}
.toast{position:absolute;left:16px;right:16px;bottom:calc(86px + env(safe-area-inset-bottom));z-index:60;display:flex;align-items:center;gap:10px;background:#16262b;color:#fff;border-radius:16px;padding:13px 15px;font-size:14px;font-weight:600;box-shadow:0 14px 30px -10px rgba(0,0,0,.5);opacity:0;transform:translateY(16px);pointer-events:none;transition:all .3s}
.toast.show{opacity:1;transform:none}
.toast .ic{color:var(--g);flex:none}
.toast.err .ic{color:var(--o)}
.busy{position:absolute;inset:0;z-index:50;display:flex;align-items:center;justify-content:center;background:rgba(245,248,249,.88);backdrop-filter:blur(4px);visibility:hidden;opacity:0;transition:opacity .2s}
.busy.show{visibility:visible;opacity:1}
.busy>div{display:flex;flex-direction:column;align-items:center;gap:12px;background:#fff;border-radius:22px;padding:24px 28px;box-shadow:var(--sh);text-align:center;max-width:78%}
.busy p{font-weight:700;font-size:14.5px}


/* ================= MOBILE-FIRST: ajustes de app nativo ================= */
html,body{height:100%;overflow:hidden;overscroll-behavior:none;-webkit-text-size-adjust:100%;text-size-adjust:100%}
body{-webkit-user-select:none;user-select:none;-webkit-touch-callout:none}
input,textarea,select,.paper,.txt,.vrow{-webkit-user-select:text;user-select:text}
button,[role=button],[data-go],[data-act],.tab,.chip,.slot,.opt,input,select,textarea{touch-action:manipulation}
.app{padding-left:env(safe-area-inset-left);padding-right:env(safe-area-inset-right)}
.field input,.inp,.selw select,.ta,.search input{font-size:16px}
.search input::placeholder{font-size:14.5px}
.iconbtn{width:44px;height:44px}
.avatar.sm{width:44px;height:44px}
.chip{min-height:44px}
.btn.mini{min-height:44px}
.seg button{min-height:44px}
.tabs2 button{min-height:44px}
.link{min-height:44px;display:inline-flex;align-items:center}
.splash-skip{min-height:44px;padding:0 20px}
.opt,.slot{min-height:48px}
.chips,.chips.scroll{flex-wrap:wrap;overflow:visible;margin-left:0;margin-right:0;padding:2px 0 6px}
.sheet{max-height:min(90%,calc(var(--app-h,100dvh) - 24px))}
.sheet .field,.sheet .lbl{scroll-margin-top:12px}
.grab{position:relative}
.grab::after{content:"";position:absolute;left:-60px;right:-60px;top:-16px;bottom:-16px}
.loading-full{padding-top:calc(30px + env(safe-area-inset-top))}
body.kb .tabbar{display:none}
.mgrid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px;margin:12px 0 4px}
.mitem{display:flex;flex-direction:column;align-items:flex-start;justify-content:center;gap:8px;min-height:84px;border:1.5px solid var(--line);background:#fff;border-radius:16px;padding:12px;text-align:left;font-weight:700;font-size:14.5px;line-height:1.2}
.mitem .scb{width:38px;height:38px;border-radius:12px;flex:none}
.mitem:active{background:var(--cl)}
.mitem>span:last-child{min-width:0;overflow-wrap:break-word}
.mitem{min-width:0;width:100%}
@media(max-width:380px){
  .pad{padding-left:14px;padding-right:14px}
  .top{padding-left:14px;padding-right:14px}
  .top.big h1{font-size:23px}
  .home-hero h1{font-size:26px}
  .stats3 b{font-size:19px}
  .meta{gap:10px}
  .trio .btn{font-size:12px}
  .pro{gap:10px;padding:12px}
  .pro .btn.mini{padding:8px 10px}
  .jrow{gap:10px}
  .jpct{font-size:30px}
}
@media(max-height:700px){
  .hero{padding-bottom:44px}
  .pull{margin-top:-30px}
  .home-hero h1{margin-top:10px}
  .hh-school{margin-top:10px}
  .ob-art{margin:6px -8px}
  .ob-body h1{font-size:23px}
  .splash h1{font-size:46px}
  .cad-h{margin:8px 0 14px}
  .field{margin-bottom:10px}
}
/* telas maiores: pré-visualização com moldura de celular */
@media(min-width:521px){
  html,body{overflow:auto}
  .stage{position:static;min-height:100vh;display:flex;align-items:center;justify-content:center;gap:64px;padding:16px}
  .phone{position:relative;top:auto;left:auto;flex:none;width:392px;height:min(844px,calc(100vh - 32px));border-radius:46px;box-shadow:0 0 0 9px #16262b,0 40px 90px -24px rgba(8,127,140,.55)}
}
@media(min-width:1040px){.side{display:block}}
@media (prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms !important;animation-iteration-count:1 !important;transition-duration:.01ms !important}.screen{transform:none}}
</style>
</head>
<body>
<div class="stage">
  <aside class="side" id="side" aria-label="Jornada do protótipo"></aside>
  <main class="phone" id="phone">
    <div class="app">
      <div class="viewport" id="viewport"></div>
      <nav class="tabbar" id="tabbar" aria-label="Navegação principal"></nav>
      <div class="ov" id="ov" aria-hidden="true"><div class="ov-bg" data-act="closeOv"></div><div class="sheet" id="sheet" role="dialog" aria-modal="true"></div></div>
      <div class="drawer" id="drawer"><div class="dr-bg" data-act="closeDrawer"></div><aside id="dr" aria-label="Menu"></aside></div>
      <div class="busy" id="busy" role="status" aria-live="polite"><div><div class="spin big"></div><p>Carregando…</p></div></div>
      <div class="toast" id="toast" role="status" aria-live="polite"></div>
    </div>
  </main>
</div>
<script>
(function () {
'use strict';

/* ===== utilidades ===== */
const $ = (s, r = document) => r.querySelector(s);
const $$ = (s, r = document) => Array.prototype.slice.call(r.querySelectorAll(s));
const esc = s => String(s).replace(/[&<>"']/g, c => ({ '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#39;' }[c]));
const hash = s => { let h = 0; for (const c of String(s)) h = (h * 31 + c.charCodeAt(0)) >>> 0; return h; };
const initials = n => n.trim().split(/\s+/).filter(Boolean).slice(0, 2).map(w => w[0].toUpperCase()).join('');
const firstName = n => (n.trim().split(/\s+/)[0] || '');
const TODAY = '08/10/2026';

/* ===== ícones (traço, sem biblioteca externa) ===== */
const IC = {
  home: '<path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/>',
  users: '<path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/>',
  user: '<path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/>',
  search: '<circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/>',
  bell: '<path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/>',
  menu: '<line x1="3" y1="6" x2="21" y2="6"/><line x1="3" y1="12" x2="21" y2="12"/><line x1="3" y1="18" x2="21" y2="18"/>',
  back: '<line x1="19" y1="12" x2="5" y2="12"/><polyline points="12 19 5 12 12 5"/>',
  next: '<line x1="5" y1="12" x2="19" y2="12"/><polyline points="12 5 19 12 12 19"/>',
  check: '<polyline points="20 6 9 17 4 12"/>',
  calendar: '<rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/>',
  clock: '<circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/>',
  send: '<line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/>',
  share: '<circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><line x1="8.59" y1="13.51" x2="15.42" y2="17.49"/><line x1="15.41" y1="6.51" x2="8.59" y2="10.49"/>',
  link: '<path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/>',
  download: '<path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/>',
  shield: '<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>',
  briefcase: '<rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/>',
  chat: '<path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/>',
  chevron: '<polyline points="9 18 15 12 9 6"/>',
  x: '<line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/>',
  trend: '<polyline points="23 6 13.5 15.5 8.5 10.5 1 18"/><polyline points="17 6 23 6 23 12"/>',
  award: '<circle cx="12" cy="8" r="7"/><polyline points="8.21 13.89 7 23 12 20 17 23 15.79 13.88"/>',
  bolt: '<polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/>',
  mic: '<path d="M12 1a3 3 0 0 0-3 3v8a3 3 0 0 0 6 0V4a3 3 0 0 0-3-3z"/><path d="M19 10v2a7 7 0 0 1-14 0v-2"/><line x1="12" y1="19" x2="12" y2="23"/>',
  pin: '<path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/>',
  lock: '<rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/>',
  play: '<polygon points="6 3 20 12 6 21 6 3"/>',
  refresh: '<polyline points="23 4 23 10 17 10"/><path d="M20.49 15a9 9 0 1 1-2.12-9.36L23 10"/>',
  copy: '<rect x="9" y="9" width="13" height="13" rx="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/>',
  mail: '<path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/>',
  edit: '<path d="M12 20h9"/><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"/>',
  heart: '<path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/>',
  file: '<path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="8" y1="13" x2="16" y2="13"/><line x1="8" y1="17" x2="14" y2="17"/>',
  school: '<path d="M22 10L12 5 2 10l10 5 10-5z"/><path d="M6 12v5c3 3 9 3 12 0v-5"/>',
  qr: '<rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/><path d="M14 14h3v3h-3zM20 14v.01M14 20h3M20 17v4"/>',
  sparkle: '<path d="M12 3l1.9 5.1L19 10l-5.1 1.9L12 17l-1.9-5.1L5 10l5.1-1.9z"/><path d="M19 15l.7 1.8 1.8.7-1.8.7L19 20l-.7-1.8-1.8-.7 1.8-.7z"/>',
  flame: '<path d="M12 22a7 7 0 0 0 7-7c0-4-3-6-4-10-3 2-5 5-5 8-1-1-2-2-2-4-2 2-3 4-3 6a7 7 0 0 0 7 7z"/>',
  filter: '<polygon points="22 3 2 3 10 12.46 10 19 14 21 14 12.46 22 3"/>',
  chevdown: '<polyline points="6 9 12 15 18 9"/>',
  plus: '<line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/>',
  logout: '<path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/>',
  info: '<circle cx="12" cy="12" r="10"/><line x1="12" y1="16" x2="12" y2="12"/><line x1="12" y1="8" x2="12.01" y2="8"/>'
};
const icon = (n, s = 20, cls = '') => `<svg class="ic ${cls}" width="${s}" height="${s}" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">${IC[n] || ''}</svg>`;

/* marca: dois elos entrelaçados */
const logoMark = (s = 64, a = '#FFFFFF', b = '#FF9F43') =>
  `<svg width="${s}" height="${s}" viewBox="0 0 64 64" fill="none" aria-hidden="true"><rect x="5" y="19" width="32" height="26" rx="13" stroke="${a}" stroke-width="6"/><rect x="27" y="19" width="32" height="26" rx="13" stroke="${b}" stroke-width="6"/></svg>`;

const av = (name, cls = '') => `<div class="avatar a${hash(name) % 5 + 1} ${cls}" aria-hidden="true">${esc(initials(name))}</div>`;

/* QR Code fictício, gerado a partir de uma semente */
function qrSVG(seed, size = 132) {
  const N = 25; let s = hash(seed) % 233280 || 7;
  const rnd = () => (s = (s * 9301 + 49297) % 233280) / 233280;
  const inF = (x, y) => (x < 8 && y < 8) || (x >= N - 8 && y < 8) || (x < 8 && y >= N - 8);
  let cells = '';
  for (let y = 0; y < N; y++) for (let x = 0; x < N; x++) if (!inF(x, y) && rnd() > 0.5) cells += `<rect x="${x}" y="${y}" width="1" height="1"/>`;
  const finder = (ox, oy) => `<path d="M${ox} ${oy}h7v7h-7z M${ox + 1} ${oy + 1}v5h5v-5z" fill-rule="evenodd"/><rect x="${ox + 2}" y="${oy + 2}" width="3" height="3"/>`;
  return `<svg width="${size}" height="${size}" viewBox="-1 -1 ${N + 2} ${N + 2}" shape-rendering="crispEdges" fill="#263238" role="img" aria-label="QR Code da carta"><rect x="-1" y="-1" width="${N + 2}" height="${N + 2}" fill="#fff"/>${cells}${finder(0, 0)}${finder(N - 7, 0)}${finder(0, N - 7)}</svg>`;
}

/* ===== dados fictícios ===== */
const SCHOOL = 'Escola Técnica Horizonte';
const P = [
  { id: 'p1', n: 'Mariana Costa', r: 'Analista de Marketing', c: 'Sabor Express', a: 'Marketing', y: 2019, g: 'f', d: true, cu: 'Administração', bio: 'Começou como estagiária e hoje lidera campanhas de lançamento.', sk: ['Campanhas', 'Redes sociais', 'Métricas', 'Comunicação'], p1: 'Estágio em Marketing', p2: 'Assistente de Marketing' },
  { id: 'p2', n: 'Rafael Almeida', r: 'Gerente de Marketing', c: 'Nuvem Bank', a: 'Marketing', y: 2012, g: 'm', d: true, cu: 'Administração', bio: 'Mais de dez anos em marketing de produtos digitais. Apadrinha jovens da sua antiga escola.', sk: ['Estratégia de marca', 'Liderança', 'Mentoria', 'Entrevistas'], p1: 'Auxiliar de Marketing', p2: 'Analista de Marketing' },
  { id: 'p3', n: 'Camila Duarte', r: 'Designer de Produto', c: 'Pixel Studio', a: 'Design', y: 2018, g: 'f', d: true, cu: 'Design Gráfico', bio: 'Transformou o curso técnico em uma carreira em design de interfaces.', sk: ['Prototipação', 'Pesquisa com usuários', 'Identidade visual'], p1: 'Estágio em Design', p2: 'Designer Júnior' },
  { id: 'p4', n: 'Lucas Pereira', r: 'Desenvolvedor Júnior', c: 'Vértice Tech', a: 'Tecnologia', y: 2021, g: 'm', d: false, cu: 'Informática', bio: 'Entrou em tecnologia logo após o curso e aprende algo novo toda semana.', sk: ['JavaScript', 'Banco de dados', 'Trabalho em equipe'], p1: 'Jovem Aprendiz em TI', p2: 'Desenvolvedor Assistente' },
  { id: 'p5', n: 'Beatriz Nogueira', r: 'Analista de RH', c: 'Grupo Lumina', a: 'RH', y: 2017, g: 'f', d: true, cu: 'Administração', bio: 'Conduz processos seletivos de estágio e aprendizagem todos os anos.', sk: ['Recrutamento', 'Entrevistas', 'Desenvolvimento de pessoas'], p1: 'Estágio em RH', p2: 'Assistente de RH' },
  { id: 'p6', n: 'Thiago Santos', r: 'Analista Financeiro', c: 'Nuvem Bank', a: 'Finanças', y: 2016, g: 'm', d: true, cu: 'Administração', bio: 'Cuida de planejamento financeiro e gosta de explicar números de um jeito simples.', sk: ['Planilhas', 'Orçamento', 'Análise de dados'], p1: 'Estágio em Finanças', p2: 'Assistente Financeiro' },
  { id: 'p7', n: 'Aline Ferreira', r: 'Coordenadora de Logística', c: 'Rota Log', a: 'Logística', y: 2014, g: 'f', d: false, cu: 'Logística', bio: 'Começou no armazém e hoje coordena uma equipe de quinze pessoas.', sk: ['Gestão de equipe', 'Processos', 'Planejamento'], p1: 'Auxiliar de Logística', p2: 'Analista de Logística' },
  { id: 'p8', n: 'Diego Martins', r: 'Analista de Dados', c: 'Vértice Tech', a: 'Tecnologia', y: 2020, g: 'm', d: true, cu: 'Informática', bio: 'Une curiosidade e planilhas para ajudar times a decidir melhor.', sk: ['SQL', 'Visualização de dados', 'Comunicação'], p1: 'Jovem Aprendiz em TI', p2: 'Assistente de Dados' },
  { id: 'p9', n: 'Juliana Rocha', r: 'Assistente Administrativa', c: 'Pulso Saúde', a: 'Administração', y: 2022, g: 'f', d: true, cu: 'Administração', bio: 'Primeira da família em um emprego formal. Hoje ajuda novos aprendizes a se adaptar.', sk: ['Organização', 'Atendimento', 'Rotinas administrativas'], p1: 'Jovem Aprendiz Administrativa', p2: 'Auxiliar Administrativa' },
  { id: 'p10', n: 'Paulo Henrique Lima', r: 'Analista de Mídia Social', c: 'Sabor Express', a: 'Marketing', y: 2020, g: 'm', d: true, cu: 'Marketing', bio: 'Cuida da presença digital da marca e adora trocar ideias com quem está começando.', sk: ['Conteúdo', 'Redes sociais', 'Criatividade'], p1: 'Estágio em Mídias', p2: 'Assistente de Conteúdo' }
];
const PRO = id => P.find(p => p.id === id);
const PADRINHO = P[1];
const AREAS = ['Todas', 'Marketing', 'Tecnologia', 'Design', 'Finanças', 'RH', 'Logística', 'Administração'];
const CARGOS = ['Todos', 'Analista', 'Gerente', 'Coordenador', 'Designer', 'Desenvolvedor', 'Assistente'];
const EMPRESAS = ['Todas', 'Sabor Express', 'Nuvem Bank', 'Pixel Studio', 'Vértice Tech', 'Grupo Lumina', 'Rota Log', 'Pulso Saúde'];

const EV = [
  { id: 'e1', d: '15', m: 'out', t: 'Roda de Marketing', s: 'Empreendedores e profissionais convidados', h: '19h às 20h30', n: 38, k: 'Roda', ic: 'users', g: ['Rafael Almeida', 'Mariana Costa', 'Paulo Henrique Lima'], desc: 'Conversa em roda sobre como começar em marketing, com empreendedores locais e ex-alunos da escola.' },
  { id: 'e2', d: '22', m: 'out', t: 'Encontro com Recrutadores', s: 'Como se destacar em processos seletivos', h: '18h30 às 20h', n: 54, k: 'Recrutadores', ic: 'briefcase', g: ['Beatriz Nogueira', 'Thiago Santos'], desc: 'Recrutadores contam o que observam em currículos, entrevistas e dinâmicas, e respondem às suas dúvidas.' },
  { id: 'e3', d: '29', m: 'out', t: 'Networking entre ex-alunos', s: 'Conexões que podem abrir portas', h: '19h às 21h', n: 71, k: 'Ex-alunos', ic: 'link', g: ['Camila Duarte', 'Diego Martins', 'Juliana Rocha'], desc: 'Encontro mensal de ex-alunos de todas as turmas, com apresentações rápidas e conversas guiadas.' }
];

const SIMS = [
  { short: 'Estágio em Marketing', title: 'Entrevista para Estágio em Marketing',
    qs: ['Conte um pouco sobre você e por que deseja essa oportunidade.', 'Descreva uma situação em que você trabalhou em equipe. Qual foi o seu papel?', 'Fale sobre um erro que você cometeu e o que aprendeu com ele.'],
    ex: ['Sou estudante do curso técnico de Administração e gosto de criar conteúdo. Quero esta vaga para aplicar o que aprendi na escola em campanhas reais e crescer na área de marketing.', 'No projeto final do curso, organizei a divulgação de uma feira da escola. Dividi tarefas com mais quatro colegas, criei as artes e acompanhei os resultados nas redes.', 'Uma vez entreguei um trabalho sem revisar e havia erros de dados. Pedi desculpas, refiz no mesmo dia e passei a usar uma lista de conferência antes de entregar.'] },
  { short: 'Jovem Aprendiz Administrativo', title: 'Entrevista para Jovem Aprendiz Administrativo',
    qs: ['Por que você quer ser Jovem Aprendiz nesta empresa?', 'Como você organiza seu tempo entre escola e trabalho?', 'O que você faria se não soubesse resolver uma tarefa?'],
    ex: ['Quero ter minha primeira experiência formal e aprender como uma empresa funciona por dentro. Sou organizado e gosto de aprender com quem tem mais experiência.', 'Uso uma agenda semanal com os horários de aula, tarefas e descanso. Deixo o que tem prazo mais próximo em destaque e peço ajuda cedo quando algo aperta.', 'Primeiro tentaria resolver pesquisando. Se não desse certo, pediria orientação a um colega, explicando o que já tentei, e anotaria a solução para a próxima vez.'] },
  { short: 'Assistente de Logística', title: 'Entrevista para Assistente de Logística',
    qs: ['Fale sobre você e o que despertou seu interesse por logística.', 'Conte uma situação em que você precisou cumprir um prazo apertado.', 'Como você lida com uma crítica do seu líder?'],
    ex: ['Fiz o curso técnico de Logística e sempre gostei de entender como as coisas chegam até as pessoas. Quero praticar o que estudei em uma operação de verdade.', 'Na escola, precisei montar um plano de entregas em dois dias. Listei prioridades, dividi o trabalho com a equipe e entregamos um dia antes do prazo.', 'Escuto até o fim, peço exemplos do que posso melhorar e aplico na próxima tarefa. Depois volto para saber se a mudança ajudou.'] }
];

const EMISSORES = {
  padrinho: { name: 'Rafael Almeida', role: 'Gerente de Marketing, Nuvem Bank', label: 'Padrinho de Currículo' },
  coord: { name: 'Profª. Helena Prado', role: 'Coordenadora do curso, ' + SCHOOL, label: 'Coordenação do curso' },
  prof: { name: 'Prof. Marcos Teles', role: 'Professor orientador, ' + SCHOOL, label: 'Professor orientador' }
};

const VAGAS = [
  { t: 'Estágio em Marketing', e: 'Sabor Express', l: 'São Paulo, híbrido', tag: 'Rede da sua escola' },
  { t: 'Jovem Aprendiz Administrativo', e: 'Pulso Saúde', l: 'São Paulo, presencial', tag: 'Rede da sua escola' },
  { t: 'Assistente de Mídia Social', e: 'Pixel Studio', l: 'Remoto', tag: 'Vaga aberta' }
];

const PF = [
  { k: 'ok', ic: 'check', t: 'Você conta bem a sua história', d: 'Sua apresentação ficou clara e natural nos dois últimos encontros.' },
  { k: 'warn', ic: 'bolt', t: 'Seja mais direto nas respostas', d: 'Comece pelo resultado e só depois explique o caminho.' },
  { k: 'ok', ic: 'trend', t: 'Seu currículo evoluiu bastante', d: 'Incluímos os projetos do curso e a clareza do perfil subiu 28%.' }
];

const OB = [
  { t: 'Conheça quem já chegou lá.', d: 'Entre na rede de ex-alunos da sua escola técnica e converse com profissionais que começaram onde você está.', art: 'net' },
  { t: 'Tenha alguém ao seu lado.', d: 'O Padrinho de Currículo acompanha o seu trabalho, vê sua evolução de perto e pode indicar você com confiança.', art: 'duo' },
  { t: 'Esteja pronto antes da oportunidade chegar.', d: 'Simule entrevistas com IA, receba feedback na hora e acompanhe sua evolução a cada simulação.', art: 'ai' }
];

/* ===== estado ===== */
const defaults = () => ({
  user: { name: 'Giovanna Souza', email: 'giovanna.souza@email.com', school: SCHOOL, course: 'Administração', area: 'Marketing' },
  sims: [55, 62, 69],
  comp: { 'Comunicação': 70, 'Clareza': 65, 'Objetividade': 78, 'Segurança': 63 },
  feedbacks: 6, simDone: false, runs: 0,
  carta: { emitida: false, emissor: 'padrinho', code: 'EL-2026-8F3K' },
  candidatura: null, nextMeeting: '18/10', nextTime: '18h30',
  events: {}, requests: {}, proId: 'p1',
  filters: { q: '', area: 'Todas', cargo: 'Todos', empresa: 'Todas', disp: false },
  netTab: 'proximos', simRole: 0, sim: null, lastResult: null, fbLoading: false, ob: 0,
  vaga: 0, attach: { carta: true, evolucao: true }, trajOpen: false, pick: null, emitPick: 'padrinho'
});
let S = defaults();
/* ===== componentes de tela ===== */
const V = {};
const menuBtn = () => `<button class="iconbtn" data-act="menu" aria-label="Abrir menu">${icon('menu')}</button>`;
const topbar = ({ title, sub = '', back = true, right = '', big = false }) =>
  `<header class="top ${big ? 'big' : ''}">${back ? `<button class="iconbtn" data-act="back" aria-label="Voltar">${icon('back')}</button>` : ''}<div class="top-t"><h1>${title}</h1>${sub ? `<p>${sub}</p>` : ''}</div>${right}</header>`;
const seg = a => `<div class="seg" role="tablist"><button role="tab" aria-selected="${a === 'rede'}" class="${a === 'rede' ? 'on' : ''}" data-go="rede">Ex-alunos</button><button role="tab" aria-selected="${a === 'net'}" class="${a === 'net' ? 'on' : ''}" data-go="networking">Networking</button></div>`;
const bar = (label, v, cls = '') => `<div class="mbar ${cls}"><div class="mb-h"><span>${label}</span><b>${v}%</b></div><div class="bar"><i data-w="${v}"></i></div></div>`;
const timeline = items => `<ol class="tl">${items.map(i => `<li class="${i.st || ''}"><span class="tl-dot">${i.st === 'done' ? icon('check', 12) : ''}</span><div><b>${i.t}</b>${i.d ? `<small>${i.d}</small>` : ''}</div></li>`).join('')}</ol>`;

/* jornada */
function journey() {
  const steps = [
    { label: 'Rede de ex-alunos', st: 'done', go: 'rede' },
    { label: 'Padrinho de Currículo', st: 'done', go: 'padrinho' },
    { label: 'Simulação de entrevista', st: S.simDone ? 'done' : 'doing', go: 'sim' },
    { label: 'Recomendação', st: S.carta.emitida ? 'done' : (S.simDone ? 'doing' : 'todo'), go: 'carta' }
  ];
  const pct = Math.round(steps.reduce((a, s) => a + (s.st === 'done' ? 25 : s.st === 'doing' ? 12.5 : 0), 0));
  return { steps, pct };
}
const ST_LABEL = { done: 'Concluída', doing: 'Em andamento', todo: 'A seguir' };
function chainSVG(steps) {
  const w = 80, step = 62, h = 44, W = step * 3 + w;
  const col = { done: '#B8E986', doing: '#08B8C8', todo: '#D5E1E4' };
  const links = steps.map((s, i) => {
    const x = 3 + i * step, cx = x + w / 2, cy = 25;
    const inner = s.st === 'done'
      ? `<path d="M${cx - 7} ${cy} l5 5 l9 -10" stroke="#3F7A12" stroke-width="3" fill="none" stroke-linecap="round" stroke-linejoin="round"/>`
      : `<text x="${cx}" y="${cy + 5}" text-anchor="middle" font-size="14" font-weight="700" fill="${s.st === 'doing' ? '#087F8C' : '#8A9AA0'}">${i + 1}</text>`;
    return `<g class="${s.st === 'doing' ? 'pulse' : ''}"><rect x="${x}" y="3" width="${w}" height="${h}" rx="22" fill="none" stroke="${col[s.st]}" stroke-width="6"/>${inner}</g>`;
  }).join('');
  return `<svg class="chain" viewBox="0 0 ${W + 6} 50" role="img" aria-label="Corrente de confiança: ${steps.filter(s => s.st === 'done').length} de 4 elos completos">${links}</svg>`;
}
function nextStep() {
  if (S.candidatura) return { cls: 'ok', t: 'Candidatura enviada!', d: `${S.candidatura.vaga} na ${S.candidatura.empresa}, com a carta verificada anexada.`, btn: 'Ver minha carta', go: 'carta' };
  if (S.carta.emitida) return { cls: '', t: 'Sua carta está pronta.', d: 'Anexe a recomendação verificável a uma candidatura real.', btn: 'Candidatar-me', go: 'candidatura' };
  if (S.simDone) return { cls: '', t: 'Peça sua carta de recomendação.', d: 'Você concluiu a simulação. Agora seu padrinho já pode emitir a carta.', btn: 'Pedir carta', go: 'carta' };
  return { cls: '', t: 'Você tem uma simulação marcada para amanhã.', d: 'Mutirão de Simulação para Estágio em Marketing, dia 09/10 às 14h.', btn: 'Preparar agora', go: 'sim' };
}

/* ---------- splash ---------- */
V.splash = () => `
<div class="splash">
  <div class="logo-wrap">${logoMark(88)}</div>
  <h1>Elo</h1>
  <p>Conexões que abrem portas.</p>
  <div class="loadbar"><i></i></div>
  <button class="splash-skip" data-go="onboarding">Toque para começar</button>
</div>`;

/* ---------- onboarding ---------- */
const ART = {
  net: `<svg viewBox="0 0 280 210" aria-hidden="true"><g stroke="#38C9D4" stroke-width="2" opacity=".8"><line x1="140" y1="105" x2="50" y2="45"/><line x1="140" y1="105" x2="236" y2="52"/><line x1="140" y1="105" x2="40" y2="150"/><line x1="140" y1="105" x2="238" y2="158"/><line x1="140" y1="105" x2="140" y2="26"/></g><circle cx="140" cy="105" r="36" fill="#087F8C"/><g transform="translate(122 87)" stroke="#fff" stroke-width="2.4" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8L9 3 0 8l9 5 9-5z" transform="translate(9 6)"/><path d="M6 21v4c2.6 2.6 8.4 2.6 12 0v-4" transform="translate(6 3)"/></g><circle class="n n1" cx="50" cy="45" r="16" fill="#FF9F43"/><circle class="n n2" cx="236" cy="52" r="14" fill="#B8E986"/><circle class="n n3" cx="40" cy="150" r="14" fill="#B8E986"/><circle class="n n4" cx="238" cy="158" r="17" fill="#FF9F43"/><circle class="n n5" cx="140" cy="26" r="13" fill="#fff" stroke="#08B8C8" stroke-width="3"/></svg>`,
  duo: `<svg viewBox="0 0 280 210" aria-hidden="true"><rect x="40" y="46" width="200" height="124" rx="22" fill="#fff" opacity=".9"/><circle cx="92" cy="96" r="22" fill="#087F8C"/><path d="M62 150c0-17 13-28 30-28s30 11 30 28z" fill="#087F8C"/><circle cx="188" cy="96" r="22" fill="#FF9F43"/><path d="M158 150c0-17 13-28 30-28s30 11 30 28z" fill="#FF9F43"/><path d="M118 84c14-14 30-14 44 0" stroke="#08B8C8" stroke-width="4" fill="none" stroke-linecap="round" stroke-dasharray="2 8"/><circle cx="140" cy="62" r="16" fill="#B8E986"/><path d="M133 62l5 5 9-10" stroke="#3F7A12" stroke-width="3.4" fill="none" stroke-linecap="round" stroke-linejoin="round"/></svg>`,
  ai: `<svg viewBox="0 0 280 210" aria-hidden="true"><rect x="36" y="38" width="208" height="134" rx="24" fill="#fff" opacity=".92"/><g fill="#08B8C8">${[0, 1, 2, 3, 4, 5, 6, 7, 8, 9].map(i => `<rect class="w" style="--i:${i}" x="${62 + i * 16}" y="${95 - (i % 3 + 1) * 6}" width="8" height="${(i % 3 + 1) * 12 + 6}" rx="4"/>`).join('')}</g><rect x="62" y="140" width="156" height="10" rx="5" fill="#E8FAFC"/><rect x="62" y="140" width="112" height="10" rx="5" fill="#B8E986"/><g transform="translate(196 44)" fill="#FF9F43"><path d="M12 0l2.6 7.4L22 10l-7.4 2.6L12 20l-2.6-7.4L2 10l7.4-2.6z"/></g></svg>`
};
V.onboarding = () => {
  const o = OB[S.ob], last = S.ob === OB.length - 1;
  return `
<div class="ob">
  <div class="ob-top"><span class="ob-count">${S.ob + 1} de ${OB.length}</span><button class="link" data-go="cadastro">Pular</button></div>
  <div class="ob-art">${ART[o.art]}</div>
  <div class="ob-body"><h1>${o.t}</h1><p>${o.d}</p></div>
  <div class="ob-foot">
    <div class="dots" aria-hidden="true">${OB.map((_, i) => `<i class="${i === S.ob ? 'on' : ''}"></i>`).join('')}</div>
    <button class="btn primary" data-act="obNext">${last ? 'Começar' : 'Próximo'}</button>
  </div>
</div>`;
};

/* ---------- cadastro ---------- */
const sel = (id, label, opts, val) => `<div class="field"><label for="${id}">${label}</label><div class="selw"><select id="${id}">${opts.map(o => `<option ${o === val ? 'selected' : ''}>${o}</option>`).join('')}</select>${icon('chevdown', 18)}</div></div>`;
V.cadastro = () => `
<div class="cad">
  <button class="iconbtn" data-act="back" aria-label="Voltar">${icon('back')}</button>
  <div class="cad-h"><div class="cad-logo">${logoMark(34, '#087F8C', '#FF9F43')}</div><h1>Entre pela sua escola</h1><p>Sua escola técnica é a porta de entrada. Ela confirma quem você é e conecta você aos ex-alunos.</p></div>
  <div class="field"><label for="f-nome">Nome</label><input id="f-nome" type="text" value="${esc(S.user.name)}" autocomplete="off"><small class="err" id="e-nome"></small></div>
  <div class="field"><label for="f-email">E-mail</label><input id="f-email" type="email" value="${esc(S.user.email)}" autocomplete="off"><small class="err" id="e-email"></small></div>
  ${sel('f-escola', 'Escola', [SCHOOL, 'Instituto Técnico Novo Caminho', 'Centro de Formação Aurora'], S.user.school)}
  ${sel('f-curso', 'Curso', ['Administração', 'Marketing', 'Informática', 'Logística', 'Design Gráfico'], S.user.course)}
  ${sel('f-area', 'Área de interesse', ['Marketing', 'Tecnologia', 'Design', 'Finanças', 'RH', 'Logística', 'Administração'], S.user.area)}
  <button class="btn primary block" id="btnCad" data-act="cadSubmit">Entrar na rede</button>
  <p class="fine">Dados fictícios, só para demonstração.</p>
</div>`;

/* ---------- home ---------- */
V.home = () => {
  const J = journey(), n = J.steps.filter(s => s.st === 'done').length, ns = nextStep(), ev = EV[0];
  return `
<div class="hero home-hero">
  <div class="hh-top">
    <button class="avatar a1 sm" data-go="perfil" aria-label="Abrir perfil">${esc(initials(S.user.name))}</button>
    <span class="hh-sp"></span>
    <button class="iconbtn glass" data-act="notifs" aria-label="Notificações">${icon('bell')}<i class="dot"></i></button>
    <button class="iconbtn glass" data-act="menu" aria-label="Abrir menu">${icon('menu')}</button>
  </div>
  <p class="hh-school">${icon('school', 15)} ${esc(S.user.school)}</p>
  <h1>Olá, ${esc(firstName(S.user.name))} 👋</h1>
  <p class="hh-sub">Vamos aproximar você da próxima oportunidade.</p>
</div>
<div class="pad pull">
  <section class="card jcard" aria-label="Sua jornada">
    <div class="jhead"><div><h2>Sua jornada</h2><p>${n} de 4 etapas concluídas</p></div><div class="jpct" data-count="${J.pct}" data-suffix="%">0%</div></div>
    ${chainSVG(J.steps)}
    <div class="jlist">${J.steps.map((s, i) => `<button class="jrow ${s.st}" data-go="${s.go}"><span class="jn">${i + 1}</span><span class="jl">${s.label}</span><span class="jst">${ST_LABEL[s.st]}</span>${s.st === 'done' ? `<span class="sti">${icon('check', 14)}</span>` : s.st === 'doing' ? '<span class="sti doing"><i></i></span>' : '<span class="sti todo"></span>'}</button>`).join('')}</div>
  </section>

  <h3 class="sec">Próximo passo</h3>
  <section class="next ${ns.cls}">
    <div class="next-ic">${icon(ns.cls === 'ok' ? 'check' : 'bolt', 22)}</div>
    <div class="next-b"><b>${ns.t}</b><p>${ns.d}</p></div>
    <button class="btn ${ns.cls === 'ok' ? 'soft' : 'orange'}" data-go="${ns.go}">${ns.btn}</button>
  </section>

  <h3 class="sec">Atalhos</h3>
  <div class="scs">
    <button class="sc" data-go="rede"><span class="scb c">${icon('users', 22)}</span><b>Encontrar profissionais</b></button>
    <button class="sc" data-go="padrinho"><span class="scb o">${icon('heart', 22)}</span><b>Meu padrinho</b></button>
    <button class="sc" data-go="sim"><span class="scb c">${icon('mic', 22)}</span><b>Simular entrevista</b></button>
    <button class="sc" data-go="carta"><span class="scb g">${icon('award', 22)}</span><b>Minha recomendação</b></button>
  </div>

  <h3 class="sec">Agenda da rede</h3>
  <button class="evmini" data-go="networking"><div class="datebox"><b>${ev.d}</b><span>${ev.m}</span></div><div><b>${ev.t}</b><p>${ev.s}</p></div>${icon('chevron', 18)}</button>
</div>`;
};

/* ---------- rede de ex-alunos ---------- */
function filtered() {
  const f = S.filters, q = f.q.trim().toLowerCase();
  return P.filter(p => (!q || [p.n, p.r, p.c, p.a].join(' ').toLowerCase().includes(q)) && (f.area === 'Todas' || p.a === f.area) && (f.cargo === 'Todos' || p.r.toLowerCase().includes(f.cargo.toLowerCase())) && (f.empresa === 'Todas' || p.c === f.empresa) && (!f.disp || p.d));
}
const filterChip = (k, label) => { const v = S.filters[k], def = (k === 'area' || k === 'empresa') ? 'Todas' : 'Todos', on = v !== def; return `<button class="chip ${on ? 'on' : ''}" data-act="openFilter:${k}">${on ? esc(v) : label}${icon('chevdown', 14)}</button>`; };
const filtersHTML = () => filterChip('area', 'Área') + filterChip('cargo', 'Cargo') + filterChip('empresa', 'Empresa') + `<button class="chip ${S.filters.disp ? 'on' : ''}" data-act="toggleDisp" aria-pressed="${S.filters.disp}"><i class="dotg"></i>Disponível para conversar</button>`;
const proCard = p => `
<article class="card pro hov" data-act="openPro:${p.id}" tabindex="0" role="link" aria-label="Ver perfil de ${esc(p.n)}">
  ${av(p.n, 'md')}
  <div class="pro-b"><h3>${esc(p.n)}</h3><p>${esc(p.r)}</p><p class="co">${icon('briefcase', 13)} ${esc(p.c)}</p>
    <div class="tags"><span class="tag">${p.g === 'f' ? 'Ex-aluna' : 'Ex-aluno'} ${p.y}</span>${p.d ? '<span class="tag ok"><i class="dotg"></i>Disponível</span>' : ''}</div></div>
  <button class="btn mini soft" data-act="openPro:${p.id}">Ver perfil</button>
</article>`;
const listHTML = () => { const r = filtered(); return r.length ? r.map(proCard).join('') : `<div class="empty">${icon('search', 28)}<b>Nenhum profissional encontrado</b><p>Tente outro termo ou remova algum filtro.</p><button class="btn soft" data-act="clearFilters">Limpar filtros</button></div>`; };
const countText = () => `Mostrando ${filtered().length} de 1.248 profissionais`;
V.rede = () => `
${topbar({ title: 'Rede de Ex-Alunos', sub: esc(S.user.school), back: false, big: true, right: menuBtn() })}
<div class="pad">
  ${seg('rede')}
  <div class="netcount"><div class="nc-ic">${icon('users', 22)}</div><div><b>1.248 profissionais conectados</b><span>Ex-alunos da sua escola, em empresas da cidade</span></div></div>
  <label class="search">${icon('search', 18)}<input id="q" type="search" placeholder="Buscar por área, empresa ou cargo" value="${esc(S.filters.q)}" autocomplete="off" aria-label="Buscar por área, empresa ou cargo"></label>
  <div class="chips scroll" id="filters">${filtersHTML()}</div>
  <p class="count" id="rcount">${countText()}</p>
  <div class="plist" id="rlist">${listHTML()}</div>
</div>`;

/* ---------- perfil do ex-aluno ---------- */
V.pro = () => {
  const p = PRO(S.proId), rq = S.requests[p.id] || {};
  const path = [{ d: String(p.y), t: `Formou-se em ${p.cu} na ${SCHOOL}`, st: 'done' }, { d: String(p.y), t: p.p1, st: 'done' }, { d: String(p.y + 2), t: p.p2, st: 'done' }, { d: 'Hoje', t: `${p.r}, ${p.c}`, st: 'doing' }];
  return `
<div class="hero pro-hero"><div class="hh-top"><button class="iconbtn glass" data-act="back" aria-label="Voltar">${icon('back')}</button><span class="hh-sp"></span>${'<button class="iconbtn glass" data-act="menu" aria-label="Abrir menu">' + icon('menu') + '</button>'}</div></div>
<div class="pad pull2">
  <section class="card pro-main">
    ${av(p.n, 'xl')}
    <h1>${esc(p.n)}</h1>
    <p class="role">${esc(p.r)} na ${esc(p.c)}</p>
    <div class="tags center"><span class="tag">${p.g === 'f' ? 'Ex-aluna' : 'Ex-aluno'} ${p.y}</span>${p.d ? '<span class="tag ok"><i class="dotg"></i>Disponível para networking</span>' : '<span class="tag">Sem agenda no momento</span>'}</div>
  </section>
  <div class="schoollink">${icon('link', 20)}<p><b>Conexão pela sua escola.</b> Vocês estudaram na ${SCHOOL}. Não é um contato aleatório: é a sua rede.</p></div>
  <section class="card"><h3>Formação</h3><p class="txt">Curso técnico em ${p.cu}, ${SCHOOL}, turma de ${p.y}.</p><h3>Resumo da trajetória</h3><p class="txt">${esc(p.bio)}</p></section>
  <section class="traj ${S.trajOpen ? 'open' : ''}" id="traj"><div class="traj-in"><div class="card"><h3>Trajetória completa</h3>${timeline(path)}</div></div></section>
  <section class="card"><h3>Áreas de conhecimento</h3><div class="tags">${p.sk.map(s => `<span class="tag">${esc(s)}</span>`).join('')}</div></section>
  <div class="acts">
    ${p.d ? `
      <button class="btn ${rq.conversa ? 'done' : 'primary'} block" ${rq.conversa ? 'disabled' : ''} data-act="reqConversa:${p.id}">${rq.conversa ? icon('check', 18) + ' Conversa solicitada' : icon('chat', 18) + ' Pedir conversa'}</button>
      <button class="btn ${rq.indic ? 'done' : 'orange'} block" ${rq.indic ? 'disabled' : ''} data-act="reqIndic:${p.id}">${rq.indic ? icon('check', 18) + ' Indicação solicitada' : icon('send', 18) + ' Pedir indicação'}</button>`
      : `<button class="btn soft block" data-act="notifyMe:${p.id}">${icon('bell', 18)} Avisar quando estiver disponível</button>`}
    <button class="btn ghost block" data-act="toggleTraj" id="btnTraj">${S.trajOpen ? 'Ocultar trajetória' : 'Conhecer trajetória'}</button>
  </div>
</div>`;
};

/* ---------- networking ---------- */
const evN = e => e.n + (S.events[e.id] ? 1 : 0);
const evCard = e => `
<article class="card ev hov" data-act="evDetail:${e.id}" tabindex="0" role="link" aria-label="Detalhes: ${e.t}">
  <div class="datebox"><b>${e.d}</b><span>${e.m}</span></div>
  <div class="ev-b"><span class="tag">${icon(e.ic, 12)} ${e.k}</span><h3>${e.t}</h3><p>${e.s}</p>
    <div class="ev-m"><span>${icon('clock', 14)} ${e.h}</span><span>${icon('users', 14)} <b id="n-${e.id}">${evN(e)}</b> participantes</span></div></div>
  <button class="btn mini ${S.events[e.id] ? 'done' : 'primary'}" data-act="joinEv:${e.id}" id="j-${e.id}">${S.events[e.id] ? icon('check', 14) + ' Inscrito' : 'Participar'}</button>
</article>`;
const evListHTML = () => { const l = S.netTab === 'meus' ? EV.filter(e => S.events[e.id]) : EV; return l.length ? l.map(evCard).join('') : `<div class="empty">${icon('calendar', 28)}<b>Você ainda não está inscrito</b><p>Escolha um encontro em Próximos e toque em Participar.</p><button class="btn soft" data-act="netTab:proximos">Ver próximos encontros</button></div>`; };
V.networking = () => `
${topbar({ title: 'Networking guiado', sub: 'Encontros mensais da sua rede', back: false, big: true, right: menuBtn() })}
<div class="pad">
  ${seg('net')}
  <div class="tabs2" role="tablist"><button role="tab" class="${S.netTab === 'proximos' ? 'on' : ''}" data-act="netTab:proximos">Próximos</button><button role="tab" class="${S.netTab === 'meus' ? 'on' : ''}" data-act="netTab:meus">Meus encontros <i id="mcount">${Object.keys(S.events).filter(k => S.events[k]).length}</i></button></div>
  <div id="evlist">${evListHTML()}</div>
  <div class="note">${icon('info', 16)} Os encontros reúnem profissionais, empresários e recrutadores. Sempre com mediação, para ninguém ficar perdido na conversa.</div>
</div>`;

/* ---------- padrinho ---------- */
V.padrinho = () => {
  const p = PADRINHO;
  const items = [
    { t: 'Encontro 1: conhecendo seu objetivo', d: '12/08', st: 'done' },
    { t: 'Encontro 2: currículo e posicionamento', d: '09/09', st: 'done' },
    { t: 'Encontro 3: simulação de entrevista', d: '23/09', st: 'done' },
    { t: 'Encontro 4: preparação para candidatura', d: `Em andamento, próximo em ${S.nextMeeting}`, st: 'doing' }
  ];
  return `
${topbar({ title: 'Seu Padrinho de Currículo', sub: 'Quem conhece o seu trabalho e pode indicar você', back: false, big: true, right: menuBtn() })}
<div class="pad">
  <section class="card padc">
    <div class="padc-h">${av(p.n, 'lg')}<div><h2>${esc(p.n)}</h2><p>Gerente de Marketing | Nuvem Bank</p><span class="tag ok"><i class="dotg"></i>Acompanha você desde agosto</span></div></div>
    <div class="stats3">
      <div><b>4</b><span>encontros, 3 concluídos</span></div>
      <div><b id="nm">${S.nextMeeting}</b><span>próximo encontro, ${S.nextTime}</span></div>
      <div><b class="gr" data-count="28" data-prefix="+" data-suffix="%">+0%</b><span>evolução do perfil</span></div>
    </div>
    <button class="btn primary block" data-act="agendar">${icon('calendar', 18)} Agendar próximo encontro</button>
    <button class="btn soft block" data-act="msgPad">${icon('chat', 18)} Enviar mensagem</button>
  </section>
  <h3 class="sec">Seus encontros</h3>
  <section class="card">${timeline(items)}</section>
  <h3 class="sec">O que seu padrinho percebeu</h3>
  <div class="pfs">${PF.map(f => `<div class="pf ${f.k}"><span class="pf-ic">${icon(f.ic, 16)}</span><div><b>${f.t}</b><p>${f.d}</p></div></div>`).join('')}</div>
  <button class="evmini" data-go="networking"><div class="datebox alt">${icon('users', 20)}</div><div><b>Encontros mensais de networking</b><p>Rodas com profissionais, empresários e recrutadores</p></div>${icon('chevron', 18)}</button>
</div>`;
};

/* ---------- simulação (mutirão com IA) ---------- */
V.sim = () => {
  const sc = SIMS[S.simRole], last = S.sims.slice(-3);
  return `
${topbar({ title: 'Simulação', sub: 'Mutirão de Simulação de Entrevistas', back: false, big: true, right: menuBtn() })}
<div class="pad">
  <section class="hero sim-hero">
    <span class="aitag">${icon('sparkle', 14)} Simulação por IA</span>
    <h2>Prepare-se para a entrevista.</h2>
    <p>Simule situações reais e descubra onde pode melhorar.</p>
    <div class="wave" aria-hidden="true">${Array.from({ length: 22 }, (_, i) => `<i style="--i:${i}"></i>`).join('')}</div>
  </section>
  <div class="card mut"><div class="mut-ic">${icon('calendar', 20)}</div><div class="mut-b"><b>Mutirão de amanhã</b><p>09/10, 14h, conduzido por IA. 32 jovens inscritos.</p></div><span class="tag warn">Amanhã</span></div>
  <h3 class="sec">Escolha a vaga para treinar</h3>
  <div class="chips scroll">${SIMS.map((s, i) => `<button class="chip ${i === S.simRole ? 'on' : ''}" data-act="pickRole:${i}">${s.short}</button>`).join('')}</div>
  <section class="card sess">
    <h3>${sc.title}</h3>
    <div class="metas"><span>${icon('clock', 14)} cerca de 6 min</span><span>${icon('chat', 14)} ${sc.qs.length} perguntas</span><span>${icon('sparkle', 14)} feedback imediato</span></div>
    <button class="btn primary block" data-act="startSim">${icon('play', 18)} Começar simulação</button>
  </section>
  <h3 class="sec">Suas últimas simulações</h3>
  <section class="card">${last.map((v, i) => bar(`Simulação ${S.sims.length - last.length + i + 1}`, v)).join('')}<button class="link" data-go="evolucao">Ver minha evolução completa</button></section>
  <div class="note">${icon('shield', 16)} A IA é uma ferramenta de apoio ao seu desenvolvimento. Ela avalia a resposta, não a pessoa.</div>
</div>`;
};
V.simRun = () => {
  const sc = SIMS[S.simRole], q = S.sim.q, tot = sc.qs.length;
  return `
<header class="top"><button class="iconbtn" data-act="exitSim" aria-label="Sair da simulação">${icon('x')}</button><div class="top-t"><h1>${sc.short}</h1><p>Pergunta ${q + 1} de ${tot}</p></div><span class="aitag sm">${icon('sparkle', 13)} IA</span></header>
<div class="pad">
  <div class="bar big"><i data-w="${Math.round(q / tot * 100)}"></i></div>
  ${S.sim.note ? `<div class="micro">${icon('check', 14)} ${esc(S.sim.note)}</div>` : ''}
  <section class="qcard"><small>Pergunta</small><h2>${esc(sc.qs[q])}</h2></section>
  <label class="lbl" for="ans">Sua resposta</label>
  <textarea id="ans" class="ta" rows="6" placeholder="Responda como se estivesse na entrevista…"></textarea>
  <div class="ta-meta"><span id="cnt">0 caracteres</span><button class="link" data-act="useSample">Usar resposta de exemplo</button></div>
  <p class="tip">${icon('bolt', 14)} Dica: conte a situação, o que você fez e qual foi o resultado.</p>
  <button class="btn primary block" id="btnAns" data-act="submitAnswer" disabled>${q + 1 === tot ? 'Enviar e ver feedback' : 'Responder'} ${icon('send', 18)}</button>
</div>`;
};
const SUMMARY = low => ({
  'Comunicação': 'Você apresentou boas ideias, mas pode tornar sua resposta mais objetiva: comece pelo ponto principal e só depois conte os detalhes.',
  'Clareza': 'Suas ideias são boas. Organize em três partes (situação, ação e resultado) para ficarem ainda mais claras.',
  'Objetividade': 'Você foi direto. Falta só incluir um exemplo concreto para tornar a resposta memorável.',
  'Segurança': 'Você apresentou boas ideias, mas pode tornar sua resposta mais objetiva e firme. Evite abrir com "acho que" e fale de suas conquistas com mais segurança.'
}[low]);
V.simFeedback = () => {
  if (S.fbLoading) return `<div class="loading-full"><div class="orb"></div><h2>Gerando seu feedback…</h2><p>A IA está comparando suas respostas com as simulações anteriores.</p><div class="typing"><i></i><i></i><i></i></div></div>`;
  const R = S.lastResult, low = Object.keys(R.ind).sort((a, b) => R.ind[a] - R.ind[b])[0];
  return `
${topbar({ title: 'Feedback da simulação', sub: esc(R.title), back: false, right: `<span class="aitag sm">${icon('sparkle', 13)} Análise por IA</span>` })}
<div class="pad">
  <section class="hero score">
    <div class="score-n"><b data-count="${R.overall}" data-suffix="%">0%</b><span>pontuação geral</span></div>
    <div class="up">${icon('trend', 18)}<b>${R.delta > 0 ? `Você evoluiu ${R.delta}% desde sua última simulação.` : 'Sua pontuação se manteve estável. Continue treinando.'}</b></div>
  </section>
  <section class="card"><h3>Indicadores</h3>${Object.keys(R.ind).map(k => bar(k, R.ind[k], k === low ? 'warn' : '')).join('')}</section>
  <section class="card"><h3>O que a IA observou</h3><p class="txt">${SUMMARY(low)}</p>
    <div class="qn"><span class="ok">${icon('check', 14)}</span><p><b>Pergunta 1.</b> Boa abertura. Mencione um resultado concreto.</p></div>
    <div class="qn"><span class="ok">${icon('check', 14)}</span><p><b>Pergunta 2.</b> Papel bem explicado. Descreva o que mudou depois da sua ação.</p></div>
    <div class="qn"><span class="wn">${icon('bolt', 14)}</span><p><b>Pergunta 3.</b> Você aprendeu com o erro. Fale mais firme sobre como evita repetir.</p></div></section>
  <button class="btn primary block" data-act="newSim">${icon('refresh', 18)} Nova simulação</button>
  <button class="btn soft block" data-go="evolucao">${icon('trend', 18)} Ver minha evolução</button>
  <button class="btn orange block" data-go="carta">${icon('award', 18)} Pedir recomendação ao padrinho</button>
</div>`;
};

/* ---------- evolução ---------- */
function chart(vals) {
  const W = 320, H = 176, L = 34, R = 16, T = 24, B = 32, lo = 40, hi = 100, n = vals.length;
  const x = i => L + (n === 1 ? (W - L - R) / 2 : i * (W - L - R) / (n - 1)), y = v => T + (1 - (v - lo) / (hi - lo)) * (H - T - B);
  let grid = ''; [40, 60, 80, 100].forEach(g => { grid += `<line x1="${L}" x2="${W - R}" y1="${y(g)}" y2="${y(g)}" class="gl"/><text x="${L - 8}" y="${y(g) + 4}" class="gt" text-anchor="end">${g}</text>`; });
  const pts = vals.map((v, i) => `${x(i)},${y(v)}`).join(' ');
  const area = `M${x(0)},${H - B} L${pts.replace(/ /g, ' L')} L${x(n - 1)},${H - B} Z`;
  const dots = vals.map((v, i) => `<circle cx="${x(i)}" cy="${y(v)}" r="${i === n - 1 ? 6 : 4.5}" class="${i === n - 1 ? 'pt last' : 'pt'}"/><text x="${x(i)}" y="${y(v) - 12}" class="cv" text-anchor="middle">${v}%</text><text x="${x(i)}" y="${H - 10}" class="gt" text-anchor="middle">Sim. ${i + 1}</text>`).join('');
  return `<svg viewBox="0 0 ${W} ${H}" class="chart" role="img" aria-label="Pontuação em cada simulação: ${vals.join('%, ')}%">${grid}<path d="${area}" class="ar"/><polyline class="ln draw" pathLength="1" points="${pts}"/>${dots}</svg>`;
}
V.evolucao = () => {
  const v = S.sims, f = v[0], l = v[v.length - 1], gain = Math.round((l - f) / f * 100), avg = v.length > 1 ? Math.round((l - f) / (v.length - 1)) : 0;
  const tile = (n, s) => `<div class="tile"><b>${n}</b><span>${s}</span></div>`;
  return `
${topbar({ title: 'Minha evolução', sub: 'Progresso medido a cada simulação' })}
<div class="pad">
  <div class="tiles">${tile(v.length, 'simulações feitas')}${tile('+' + gain + '%', 'desde a primeira')}${tile('+' + avg + ' pts', 'por simulação, em média')}${tile(4, 'competências desenvolvidas')}${tile(S.feedbacks, 'feedbacks recebidos')}${tile(4, 'encontros com o padrinho')}</div>
  <section class="card"><h3>Pontuação por simulação</h3>${chart(v)}</section>
  <div class="msg">${icon('trend', 22)}<b>Você está mais preparado do que quando começou.</b></div>
  <section class="card"><h3>Competências desenvolvidas</h3>${Object.keys(S.comp).map(k => bar(k, S.comp[k])).join('')}</section>
  <button class="btn primary block" data-go="sim">${icon('mic', 18)} Nova simulação</button>
</div>`;
};

/* ---------- carta de recomendação ---------- */
V.carta = () => {
  const C = S.carta, em = EMISSORES[C.emissor], ok = C.emitida, nome = firstName(S.user.name);
  return `
${topbar({ title: 'Carta de Recomendação', sub: 'Documento digital verificável' })}
<div class="pad">
  ${ok ? '' : `<div class="banner">${icon('clock', 18)}<span>Sua carta ainda não foi emitida. Solicite a emissão para liberar o link e o QR Code.</span></div>`}
  <article class="paper ${ok ? '' : 'draft'}">
    <div class="paper-h"><span class="plogo">${logoMark(26, '#087F8C', '#FF9F43')}<b>Elo</b></span><small>${esc(S.user.school)}</small></div>
    <h2>Carta de Recomendação</h2>
    ${ok ? `<div class="stamp">${icon('shield', 16)} VERIFICADA</div>` : ''}
    <dl class="meta">
      <div><dt>Recomendado por</dt><dd>${ok ? em.name : 'A definir'}${ok ? `<small>${em.role}</small>` : ''}</dd></div>
      <div><dt>Para</dt><dd>${esc(S.user.name)}</dd></div>
      <div><dt>Área</dt><dd>${esc(S.user.area)}</dd></div>
      <div><dt>Data</dt><dd>${TODAY}</dd></div>
    </dl>
    <p class="body">Acompanhei ${esc(nome)} em quatro encontros de mentoria e em ${S.sims.length} simulações de entrevista. Nesse período, a evolução em comunicação, clareza e organização foi consistente. Recomendo com confiança para oportunidades de estágio e aprendizagem em ${esc(S.user.area)}.</p>
    <div class="paper-f">
      <div class="sig"><i>${ok ? esc(em.name) : '—'}</i><small>${ok ? em.label : 'Aguardando emissão'}</small></div>
      <button class="qrbox ${ok ? '' : 'off'}" ${ok ? 'data-act="verify"' : 'disabled'} aria-label="Verificar autenticidade da carta">${ok ? qrSVG(C.code, 104) : icon('lock', 34)}<small>${ok ? C.code : 'QR Code bloqueado'}</small></button>
    </div>
  </article>
  ${ok ? `
    <p class="hint">${icon('shield', 16)} Esta recomendação pode ser verificada por qualquer recrutador.</p>
    <div class="trio"><button class="btn soft" data-act="share">${icon('share', 18)} Compartilhar</button><button class="btn soft" data-act="copyLink">${icon('copy', 18)} Copiar link</button><button class="btn soft" data-act="download">${icon('download', 18)} Baixar</button></div>
    <button class="btn ghost block" data-act="verify">${icon('qr', 18)} Verificar como recrutador</button>
    <button class="btn orange block" data-go="candidatura">${icon('briefcase', 18)} Anexar à candidatura</button>`
    : `<button class="btn primary block" data-act="askCarta">${icon('send', 18)} Solicitar emissão da carta</button>`}
</div>`;
};
V.verificar = () => {
  const em = EMISSORES[S.carta.emissor];
  if (S.vLoading) return `<div class="loading-full"><div class="spin big"></div><h2>Verificando documento…</h2><p>Consultando o registro de autenticidade</p></div>`;
  const row = (k, v) => `<div class="vrow"><span>${k}</span><b>${v}</b></div>`;
  return `
<header class="vbar"><button class="iconbtn" data-act="back" aria-label="Fechar">${icon('x')}</button><div class="url">${icon('lock', 14)} elo.app/verificar/${S.carta.code}</div></header>
<div class="pad">
  <section class="vok"><div class="vcheck">${icon('check', 44)}</div><h1>Recomendação válida</h1><p>Documento verificado</p></section>
  <section class="card">
    ${row('Recomendado por', esc(em.name))}${row('Empresa', S.carta.emissor === 'padrinho' ? 'Nuvem Bank' : esc(S.user.school))}${row('Estudante', esc(S.user.name))}${row('Data de emissão', TODAY)}
    <div class="vrow"><span>Status</span><b class="okt">${icon('check', 14)} Autenticidade confirmada</b></div>
  </section>
  <p class="note">${icon('info', 16)} Esta é a página que o recrutador vê ao ler o QR Code ou abrir o link da carta. Nenhum login é necessário.</p>
  <button class="btn soft block" data-act="back">Voltar à carta</button>
</div>`;
};

/* ---------- candidatura ---------- */
V.candidatura = () => {
  if (S.candidatura) {
    const c = S.candidatura;
    return `
${topbar({ title: 'Candidatura', back: true })}
<div class="pad"><section class="success"><div class="vcheck">${icon('check', 44)}</div><h1>Candidatura enviada</h1><p>${esc(c.vaga)}, ${esc(c.empresa)}</p></section>
<section class="card"><h3>O que foi enviado</h3>${timeline([{ t: 'Perfil e área de interesse', st: 'done' }, ...(c.carta ? [{ t: 'Carta de recomendação verificada (QR Code)', st: 'done' }] : []), ...(c.evolucao ? [{ t: 'Resumo da evolução nas simulações', st: 'done' }] : []), { t: 'Recrutador recebe a carta com selo de verificação', st: 'doing' }])}</section>
<button class="btn primary block" data-go="home">Voltar ao início</button></div>`;
  }
  const sw = (k, label, sub, dis) => `<button class="swrow" ${dis ? 'disabled' : ''} data-act="toggleAttach:${k}"><div><b>${label}</b><small>${sub}</small></div><span class="sw ${S.attach[k] && !dis ? 'on' : ''}"><i></i></span></button>`;
  return `
${topbar({ title: 'Candidatura', sub: 'Anexe sua recomendação verificável' })}
<div class="pad">
  <h3 class="sec">Escolha a vaga</h3>
  ${VAGAS.map((v, i) => `<button class="vaga ${S.vaga === i ? 'on' : ''}" data-act="pickVaga:${i}" role="radio" aria-checked="${S.vaga === i}"><span class="radio"></span><div><b>${v.t}</b><p>${v.e}, ${v.l}</p><span class="tag">${v.tag}</span></div></button>`).join('')}
  <h3 class="sec">O que enviar junto</h3>
  <section class="card sws">${sw('carta', 'Carta de recomendação verificada', S.carta.emitida ? 'Link e QR Code seguem na candidatura' : 'Emita a carta primeiro', !S.carta.emitida)}${sw('evolucao', 'Resumo da minha evolução', 'Pontuação das simulações e competências', false)}</section>
  ${S.carta.emitida ? '' : `<button class="btn soft block" data-go="carta">Emitir minha carta</button>`}
  <button class="btn primary block" id="btnCand" data-act="sendCand">${icon('send', 18)} Enviar candidatura</button>
</div>`;
};

/* ---------- perfil ---------- */
V.perfil = () => {
  const J = journey(), u = S.user;
  return `
<div class="hero prof-hero">
  <div class="hh-top"><span class="hh-sp"></span>${'<button class="iconbtn glass" data-act="menu" aria-label="Abrir menu">' + icon('menu') + '</button>'}</div>
  ${av(u.name, 'xl')}
  <h1>${esc(u.name)}</h1>
  <p class="hh-sub">${esc(u.school)}</p>
  <p class="hh-sub">Curso técnico em ${esc(u.course)}</p>
  <div class="tags center"><span class="tag light">Interesse em ${esc(u.area)}</span></div>
  <button class="btn soft mini" data-act="editProfile">${icon('edit', 14)} Editar perfil</button>
</div>
<div class="pad pull3">
  <section class="card stats3 p3"><div><b>${J.pct}%</b><span>da jornada</span></div><div><b>${S.sims.length}</b><span>simulações</span></div><div><b>${S.carta.emitida ? 1 : 0}</b><span>recomendação</span></div></section>
  <section class="card"><h3>Competências</h3>${Object.keys(S.comp).map(k => bar(k, S.comp[k])).join('')}<button class="link" data-go="evolucao">Ver minha evolução</button></section>
  <section class="card"><h3>Meu padrinho</h3><button class="rowl" data-go="padrinho">${av(PADRINHO.n, 'md')}<div><b>${PADRINHO.n}</b><p>Gerente de Marketing, Nuvem Bank</p></div>${icon('chevron', 18)}</button></section>
  <section class="card"><h3>Recomendações</h3><button class="rowl" data-go="carta"><span class="scb ${S.carta.emitida ? 'g' : 'o'}">${icon(S.carta.emitida ? 'award' : 'clock', 20)}</span><div><b>${S.carta.emitida ? 'Carta verificada' : 'Carta em preparação'}</b><p>${S.carta.emitida ? 'Emitida por ' + EMISSORES[S.carta.emissor].name : 'Solicite a emissão'}</p></div>${icon('chevron', 18)}</button>
  ${S.candidatura ? `<button class="rowl" data-go="candidatura"><span class="scb c">${icon('briefcase', 20)}</span><div><b>${S.candidatura.vaga}</b><p>Candidatura enviada</p></div>${icon('chevron', 18)}</button>` : ''}</section>
</div>`;
};
/* ===== roteador ===== */
const ROOTS = ['home', 'rede', 'networking', 'padrinho', 'sim', 'perfil'];
const TAB = { home: 'home', rede: 'rede', networking: 'rede', pro: 'rede', padrinho: 'padrinho', sim: 'sim', simRun: 'sim', simFeedback: 'sim', evolucao: 'sim', carta: 'perfil', verificar: 'perfil', candidatura: 'perfil', perfil: 'perfil' };
const NONAV = ['splash', 'onboarding', 'cadastro', 'simRun', 'verificar'];
const STAGES = [
  ['Cadastro pela escola', 'cadastro'], ['Rede de ex-alunos', 'rede'], ['Networking guiado', 'networking'], ['Padrinho de Currículo', 'padrinho'],
  ['Simulação com IA', 'sim'], ['Minha evolução', 'evolucao'], ['Carta de recomendação', 'carta'], ['Candidatura', 'candidatura']
];
const STAGE_OF = { cadastro: 0, rede: 1, pro: 1, networking: 2, padrinho: 3, sim: 4, simRun: 4, simFeedback: 4, evolucao: 5, carta: 6, verificar: 6, candidatura: 7 };
let cur = null, stack = [], timer = null;

function go(id, o = {}) {
  if (!V[id]) return;
  closeOv(); closeDrawer();
  if (o.id) S.proId = o.id;
  if (o.reset || ROOTS.includes(id)) stack = [id];
  else if (o.replace) { stack.pop(); stack.push(id); }
  else if (stack[stack.length - 1] !== id) stack.push(id);
  show(id, o.dir);
}
function back() {
  if (stack.length > 1) { stack.pop(); show(stack[stack.length - 1], 'back'); } else go('home');
}
function show(id, dir) {
  clearTimeout(timer);
  const el = $('#s-' + id);
  if (cur && cur !== id) $('#s-' + cur).classList.remove('active');
  el.innerHTML = V[id]();
  el.classList.toggle('from-left', dir === 'back');
  el.scrollTop = 0; $('#viewport').scrollLeft = 0; el.scrollLeft = 0;
  el.classList.add('active');
  cur = id;
  chrome(); animate(el);
  if (AFTER[id]) AFTER[id](el);
}
function refresh() {
  const el = $('#s-' + cur), top = el.scrollTop;
  el.innerHTML = V[cur](); el.scrollTop = top;
  chrome(); animate(el);
  if (AFTER[cur]) AFTER[cur](el);
}
function chrome() {
  $('#tabbar').classList.toggle('hide', NONAV.includes(cur));
  $$('#tabbar .tab').forEach(t => { const on = t.dataset.go === TAB[cur]; t.classList.toggle('on', on); on ? t.setAttribute('aria-current', 'page') : t.removeAttribute('aria-current'); });
  $$('#side .st').forEach((b, i) => b.classList.toggle('on', STAGE_OF[cur] === i));
}
function animate(root) {
  requestAnimationFrame(() => requestAnimationFrame(() => {
    $$('[data-w]', root).forEach(e => { e.style.width = e.dataset.w + '%'; });
    $$('[data-count]', root).forEach(countUp);
    $$('.draw', root).forEach(e => e.classList.add('go'));
  }));
}
function countUp(el) {
  const to = +el.dataset.count, pre = el.dataset.prefix || '', suf = el.dataset.suffix || '', t0 = performance.now(), d = 900;
  (function f(t) { const k = Math.min(1, (t - t0) / d); el.textContent = pre + Math.round(to * (1 - Math.pow(1 - k, 3))) + suf; if (k < 1) requestAnimationFrame(f); })(t0);
}

const AFTER = {
  splash() { timer = setTimeout(() => { if (cur === 'splash') go('onboarding'); }, 2600); },
  simRun(el) { const a = $('#ans', el); if (a) { a.value = S.sim.draft || ''; syncAns(); a.focus({ preventScroll: true }); } },
  simFeedback() { if (S.fbLoading) timer = setTimeout(() => { S.fbLoading = false; if (cur === 'simFeedback') refresh(); }, 1700); },
  verificar() { if (S.vLoading) timer = setTimeout(() => { S.vLoading = false; if (cur === 'verificar') refresh(); }, 1300); }
};

/* ===== toast, carregando, folhas e modais ===== */
let toastT;
function toast(msg, kind = '') {
  const t = $('#toast'); t.className = 'toast show ' + kind;
  t.innerHTML = `${icon(kind === 'err' ? 'info' : 'check', 18)}<span>${esc(msg)}</span>`;
  clearTimeout(toastT); toastT = setTimeout(() => t.classList.remove('show'), 2600);
}
function busy(msg, ms, cb) {
  const b = $('#busy'); b.querySelector('p').textContent = msg; b.classList.add('show');
  setTimeout(() => { b.classList.remove('show'); cb && cb(); }, ms);
}
function openSheet(html, cls = '') {
  const ov = $('#ov'), sh = $('#sheet');
  sh.className = 'sheet ' + cls; sh.innerHTML = `<div class="grab" aria-hidden="true"></div>${html}`;
  ov.classList.add('open'); ov.setAttribute('aria-hidden', 'false');
}
function closeOv() { const ov = $('#ov'); ov.classList.remove('open'); ov.setAttribute('aria-hidden', 'true'); }
function modal(o) {
  openSheet(`<div class="mdl-i">${icon(o.icon || 'info', 26)}</div><h2>${o.title}</h2><p class="txt">${o.text}</p><div class="mdl-a"><button class="btn soft" data-act="closeOv">${o.cancel || 'Cancelar'}</button><button class="btn ${o.kind || 'primary'}" data-act="modalOk">${o.ok}</button></div>`, 'modal');
  modalCb = o.onOk;
}
let modalCb = null;

/* ===== menu lateral ===== */
function openDrawer() {
  const items = [['home', 'home', 'Início'], ['users', 'rede', 'Rede de ex-alunos'], ['calendar', 'networking', 'Encontros'], ['heart', 'padrinho', 'Meu padrinho'], ['mic', 'sim', 'Simulação com IA'], ['trend', 'evolucao', 'Minha evolução'], ['award', 'carta', 'Recomendação'], ['briefcase', 'candidatura', 'Candidatura'], ['user', 'perfil', 'Meu perfil']];
  openSheet(`<h2>Menu</h2><div class="mgrid">${items.map(i => `<button class="mitem" data-go="${i[1]}"><span class="scb c">${icon(i[0], 22)}</span><span>${i[2]}</span></button>`).join('')}</div><button class="btn ghost block" data-act="resetAsk">${icon('refresh', 18)} Reiniciar demonstração</button>`, 'menu');
}
function closeDrawer() { $('#drawer').classList.remove('open'); }

/* ===== simulação ===== */
function syncAns() {
  const a = $('#ans'); if (!a) return;
  const n = a.value.trim().length; S.sim.draft = a.value;
  $('#cnt').textContent = n + (n === 1 ? ' caractere' : ' caracteres');
  $('#btnAns').disabled = n < 10;
}
function finishSim() {
  const base = { 'Comunicação': 82, 'Clareza': 76, 'Objetividade': 88, 'Segurança': 71 }, add = Math.min(S.runs * 3, 15), ind = {};
  Object.keys(base).forEach(k => { ind[k] = Math.min(97, base[k] + add); });
  const overall = Math.round(Object.values(ind).reduce((a, b) => a + b, 0) / 4), prev = S.sims[S.sims.length - 1];
  S.lastResult = { ind, overall, prev, delta: Math.round((overall - prev) / prev * 100), title: SIMS[S.simRole].title };
  S.sims.push(overall); S.comp = Object.assign({}, ind); S.feedbacks += 1; S.simDone = true; S.runs += 1;
}
const NOTES = ['Boa abertura. Seu objetivo ficou claro.', 'Papel bem explicado na equipe.'];

/* ===== ações (data-act) ===== */
const ACT = {
  back, closeOv, closeDrawer,
  menu: openDrawer,
  modalOk() { const f = modalCb; closeOv(); modalCb = null; f && f(); },
  notifs() {
    openSheet(`<h2>Notificações</h2><div class="nlist">
      <div class="nitem"><span class="scb o">${icon('calendar', 18)}</span><div><b>Mutirão de Simulação amanhã, 14h</b><p>Sessão de Estágio em Marketing conduzida por IA.</p></div></div>
      <div class="nitem"><span class="scb c">${icon('heart', 18)}</span><div><b>Rafael confirmou o encontro de ${S.nextMeeting}</b><p>Prepare seu currículo atualizado.</p></div></div>
      <div class="nitem"><span class="scb g">${icon('users', 18)}</span><div><b>Roda de Marketing em 15/10</b><p>38 jovens e profissionais já estão inscritos.</p></div></div></div>`);
  },
  obNext() { if (S.ob < OB.length - 1) { S.ob++; refresh(); } else go('cadastro'); },
  cadSubmit(btn) {
    const nome = $('#f-nome').value.trim(), email = $('#f-email').value.trim();
    const e1 = nome.length < 2 ? 'Informe seu nome completo.' : '', e2 = /^\S+@\S+\.\S+$/.test(email) ? '' : 'Digite um e-mail válido, como nome@email.com.';
    $('#e-nome').textContent = e1; $('#e-email').textContent = e2;
    $('#f-nome').classList.toggle('bad', !!e1); $('#f-email').classList.toggle('bad', !!e2);
    if (e1 || e2) { btn.classList.remove('shake'); void btn.offsetWidth; btn.classList.add('shake'); return; }
    S.user = { name: nome, email, school: $('#f-escola').value, course: $('#f-curso').value, area: $('#f-area').value };
    btn.disabled = true; btn.innerHTML = '<span class="spin"></span> Entrando na rede…';
    setTimeout(() => { go('home', { reset: true }); toast('Você entrou na rede da ' + S.user.school); }, 1000);
  },
  /* rede */
  openFilter(k) {
    const map = { area: ['Área', AREAS], cargo: ['Cargo', CARGOS], empresa: ['Empresa', EMPRESAS] }, [t, l] = map[k];
    openSheet(`<h2>${t}</h2><div class="opts">${l.map(o => `<button class="opt ${S.filters[k] === o ? 'on' : ''}" data-act="setFilter:${k}:${o}"><span>${o}</span>${S.filters[k] === o ? icon('check', 18) : ''}</button>`).join('')}</div>`);
  },
  setFilter(k, v) { S.filters[k] = v; closeOv(); redoList(); },
  toggleDisp() { S.filters.disp = !S.filters.disp; redoList(); },
  clearFilters() { S.filters = { q: '', area: 'Todas', cargo: 'Todos', empresa: 'Todas', disp: false }; const q = $('#q'); if (q) q.value = ''; redoList(); },
  openPro(id) { S.trajOpen = false; go('pro', { id }); },
  toggleTraj() {
    S.trajOpen = !S.trajOpen; const t = $('#traj'); t.classList.toggle('open', S.trajOpen);
    $('#btnTraj').textContent = S.trajOpen ? 'Ocultar trajetória' : 'Conhecer trajetória';
    if (S.trajOpen) setTimeout(() => { const sc = $('#s-pro'); sc.scrollTo({ top: Math.max(0, t.offsetTop - 90), behavior: 'smooth' }); }, 120);
  },
  notifyMe(id) { toast('Avisaremos quando ' + firstName(PRO(id).n) + ' estiver disponível'); },
  reqConversa(id) {
    const p = PRO(id);
    openSheet(`<h2>Pedir conversa com ${esc(firstName(p.n))}</h2><p class="txt">Uma conversa rápida de 15 minutos, por chat ou vídeo.</p>
      <div class="slots" role="radiogroup">${['Qui, 09/10 às 18h', 'Sex, 10/10 às 12h30', 'Seg, 13/10 às 19h'].map((s, i) => `<button class="slot ${i === 0 ? 'on' : ''}" role="radio" aria-checked="${i === 0}" data-act="slot">${s}</button>`).join('')}</div>
      <label class="lbl" for="msg">Mensagem</label><textarea id="msg" class="ta" rows="4">Olá, ${esc(firstName(p.n))}! Sou aluna da ${SCHOOL} e gostaria de conhecer sua trajetória em ${esc(p.a)}. Posso te fazer algumas perguntas?</textarea>
      <button class="btn primary block" data-act="sendConversa:${id}">${icon('send', 18)} Enviar pedido</button>`);
  },
  slot(el) { $$('.slot').forEach(s => { s.classList.remove('on'); s.setAttribute('aria-checked', 'false'); }); el.classList.add('on'); el.setAttribute('aria-checked', 'true'); },
  sendConversa(id) { (S.requests[id] = S.requests[id] || {}).conversa = true; closeOv(); refresh(); toast('Pedido enviado para ' + firstName(PRO(id).n)); },
  reqIndic(id) {
    const p = PRO(id);
    openSheet(`<h2>Pedir indicação a ${esc(firstName(p.n))}</h2><p class="txt">${esc(firstName(p.n))} vai receber seu perfil, sua evolução nas simulações e o aval do seu padrinho.</p>
      <div class="attach">${['Perfil e área de interesse', 'Evolução nas simulações', 'Parecer do padrinho'].map(t => `<div>${icon('check', 16)}<span>${t}</span></div>`).join('')}</div>
      <label class="lbl" for="msg">Vaga ou área de interesse</label><input id="msg" class="inp" value="Estágio em ${esc(S.user.area)} na ${esc(p.c)}">
      <button class="btn orange block" data-act="sendIndic:${id}">${icon('send', 18)} Enviar pedido</button>`);
  },
  sendIndic(id) { (S.requests[id] = S.requests[id] || {}).indic = true; closeOv(); refresh(); toast('Pedido de indicação enviado'); },
  /* networking */
  netTab(t) { S.netTab = t; $$('.tabs2 button').forEach(b => b.classList.remove('on')); refresh(); },
  joinEv(id, el, ev) {
    ev && ev.stopPropagation();
    const e = EV.find(x => x.id === id);
    if (S.events[id]) { modal({ icon: 'calendar', title: 'Cancelar inscrição?', text: `Você deixará de participar de “${e.t}”.`, ok: 'Cancelar inscrição', cancel: 'Manter', kind: 'orange', onOk() { S.events[id] = false; refreshEv(); toast('Inscrição cancelada'); } }); return; }
    S.events[id] = true; closeOv(); refreshEv(); toast('Inscrição confirmada em ' + e.t);
  },
  evDetail(id) {
    const e = EV.find(x => x.id === id);
    openSheet(`<span class="tag">${icon(e.ic, 12)} ${e.k}</span><h2>${e.t}</h2><p class="txt">${e.desc}</p>
      <div class="ev-m big"><span>${icon('calendar', 16)} ${e.d} de ${e.m}</span><span>${icon('clock', 16)} ${e.h}</span><span>${icon('users', 16)} ${evN(e)} participantes</span></div>
      <h3>Convidados</h3><div class="guests">${e.g.map(n => `<div>${av(n, 'sm')}<span>${n}</span></div>`).join('')}</div>
      <button class="btn ${S.events[id] ? 'done' : 'primary'} block" data-act="joinEv:${id}" ${S.events[id] ? 'disabled' : ''}>${S.events[id] ? 'Você está inscrito' : 'Participar'}</button>`);
  },
  /* padrinho */
  agendar() {
    openSheet(`<h2>Agendar próximo encontro</h2><p class="txt">Escolha um horário com ${esc(firstName(PADRINHO.n))}. O encontro 4 prepara sua candidatura.</p>
      <div class="slots" role="radiogroup">${[['18/10', '18h30'], ['19/10', '19h'], ['21/10', '12h30']].map((s, i) => `<button class="slot ${s[0] === S.nextMeeting ? 'on' : ''}" role="radio" aria-checked="${s[0] === S.nextMeeting}" data-act="pickSlot:${s[0]}:${s[1]}">${s[0]} às ${s[1]}</button>`).join('')}</div>
      <button class="btn primary block" data-act="confirmAgenda">Confirmar horário</button>`);
    S.pick = [S.nextMeeting, S.nextTime];
  },
  pickSlot(d, h, el) { S.pick = [d, h]; $$('.slot').forEach(s => { s.classList.remove('on'); s.setAttribute('aria-checked', 'false'); }); el.classList.add('on'); el.setAttribute('aria-checked', 'true'); },
  confirmAgenda() { S.nextMeeting = S.pick[0]; S.nextTime = S.pick[1]; closeOv(); refresh(); toast('Encontro marcado para ' + S.nextMeeting + ' às ' + S.nextTime); },
  msgPad() { openSheet(`<h2>Mensagem para ${esc(firstName(PADRINHO.n))}</h2><label class="lbl" for="msg">Sua mensagem</label><textarea id="msg" class="ta" rows="4">Oi, Rafael! Atualizei meu currículo com os projetos do curso. Podemos revisar no próximo encontro?</textarea><button class="btn primary block" data-act="sendMsg">${icon('send', 18)} Enviar</button>`); },
  sendMsg() { closeOv(); toast('Mensagem enviada ao seu padrinho'); },
  /* simulação */
  pickRole(i) { S.simRole = +i; refresh(); },
  startSim() { S.sim = { q: 0, answers: [], draft: '', note: '' }; go('simRun'); },
  useSample() { const a = $('#ans'); a.value = SIMS[S.simRole].ex[S.sim.q]; syncAns(); },
  submitAnswer() {
    const a = $('#ans'); if (a.value.trim().length < 10) { toast('Escreva um pouco mais para a IA analisar.', 'err'); return; }
    S.sim.answers.push(a.value.trim());
    busy('A IA está analisando sua resposta…', 1200, () => {
      S.sim.q += 1; S.sim.draft = ''; S.sim.note = NOTES[S.sim.q - 1] || '';
      if (S.sim.q < SIMS[S.simRole].qs.length) go('simRun', { replace: true });
      else { finishSim(); S.fbLoading = true; go('simFeedback', { replace: true }); }
    });
  },
  exitSim() { modal({ icon: 'x', title: 'Sair da simulação?', text: 'Suas respostas desta sessão não serão salvas.', ok: 'Sair', cancel: 'Continuar', kind: 'orange', onOk() { go('sim'); } }); },
  newSim() { ACT.startSim(); },
  /* carta */
  askCarta() {
    openSheet(`<h2>Quem emite sua carta?</h2><p class="txt">Padrinhos, professores e coordenadores podem emitir. A carta nasce com selo e QR Code de verificação.</p>
      <div class="opts">${Object.keys(EMISSORES).map(k => `<button class="opt ${S.emitPick === k ? 'on' : ''}" data-act="pickEmissor:${k}"><span><b>${EMISSORES[k].name}</b><small>${EMISSORES[k].label}</small></span>${S.emitPick === k ? icon('check', 18) : ''}</button>`).join('')}</div>
      <button class="btn primary block" data-act="confirmCarta">${icon('send', 18)} Solicitar emissão</button>`);
  },
  pickEmissor(k) { S.emitPick = k; ACT.askCarta(); },
  confirmCarta() {
    const k = S.emitPick; closeOv();
    busy('Aguardando emissão da carta…', 1400, () => { S.carta.emitida = true; S.carta.emissor = k; refresh(); toast(EMISSORES[k].name + ' emitiu sua carta'); });
  },
  verify() { S.vLoading = true; go('verificar'); },
  share() {
    openSheet(`<h2>Compartilhar carta</h2><div class="opts">${[['mail', 'Enviar por e-mail'], ['chat', 'Enviar por mensagem'], ['link', 'Copiar link']].map(o => `<button class="opt" data-act="shareDo:${o[1]}">${icon(o[0], 20)}<span>${o[1]}</span></button>`).join('')}</div>`);
  },
  shareDo(what) { closeOv(); if (what === 'Copiar link') ACT.copyLink(); else toast('Carta compartilhada (demonstração)'); },
  copyLink() { copyText('https://elo.app/verificar/' + S.carta.code); toast('Recomendação copiada'); },
  download() {
    const em = EMISSORES[S.carta.emissor], txt = `CARTA DE RECOMENDAÇÃO\n\nRecomendado por: ${em.name} (${em.role})\nPara: ${S.user.name}\nÁrea: ${S.user.area}\nData: ${TODAY}\n\nVerifique em: https://elo.app/verificar/${S.carta.code}\n(Documento fictício, gerado em protótipo.)\n`;
    const a = document.createElement('a'); a.href = URL.createObjectURL(new Blob([txt], { type: 'text/plain;charset=utf-8' })); a.download = 'carta-de-recomendacao.txt';
    document.body.appendChild(a); a.click(); a.remove(); toast('Download iniciado');
  },
  /* candidatura */
  pickVaga(i) { S.vaga = +i; refresh(); },
  toggleAttach(k) { if (k === 'carta' && !S.carta.emitida) return; S.attach[k] = !S.attach[k]; refresh(); },
  sendCand(btn) {
    const v = VAGAS[S.vaga]; btn.disabled = true; btn.innerHTML = '<span class="spin"></span> Enviando…';
    setTimeout(() => { S.candidatura = { vaga: v.t, empresa: v.e, carta: S.carta.emitida && S.attach.carta, evolucao: S.attach.evolucao }; go('candidatura', { replace: true }); toast('Candidatura enviada com a carta anexada'); }, 1100);
  },
  /* perfil */
  editProfile() {
    openSheet(`<h2>Editar perfil</h2><div class="field"><label for="p-nome">Nome</label><input id="p-nome" class="inp" value="${esc(S.user.name)}"></div>
      ${sel('p-area', 'Área de interesse', ['Marketing', 'Tecnologia', 'Design', 'Finanças', 'RH', 'Logística', 'Administração'], S.user.area)}
      <button class="btn primary block" data-act="saveProfile">Salvar alterações</button>`);
  },
  saveProfile() { const n = $('#p-nome').value.trim(); if (n.length < 2) { toast('Informe seu nome.', 'err'); return; } S.user.name = n; S.user.area = $('#p-area').value; closeOv(); refresh(); toast('Perfil atualizado'); },
  resetAsk() { closeDrawer(); modal({ icon: 'refresh', title: 'Reiniciar demonstração?', text: 'Todo o progresso volta ao início, com os dados de exemplo.', ok: 'Reiniciar', onOk() { S = defaults(); go('splash', { reset: true }); } }); }
};
function redoList() { if (cur !== 'rede') return; $('#filters').innerHTML = filtersHTML(); $('#rlist').innerHTML = listHTML(); $('#rcount').textContent = countText(); }
function refreshEv() {
  if (cur === 'networking') { $('#evlist').innerHTML = evListHTML(); $('#mcount').textContent = Object.keys(S.events).filter(k => S.events[k]).length; }
}
function copyText(t) {
  const fb = () => { const a = document.createElement('textarea'); a.value = t; a.style.position = 'fixed'; a.style.opacity = '0'; document.body.appendChild(a); a.select(); try { document.execCommand('copy'); } catch (e) { } a.remove(); };
  if (navigator.clipboard && window.isSecureContext) navigator.clipboard.writeText(t).catch(fb); else fb();
}

/* ===== eventos globais ===== */
document.addEventListener('click', e => {
  const a = e.target.closest('[data-act]');
  if (a && !a.disabled) {
    const [name, ...args] = a.dataset.act.split(':');
    if (ACT[name]) { ACT[name](...args, a, e); return; }
  }
  const g = e.target.closest('[data-go]');
  if (g && !g.disabled) go(g.dataset.go);
});
document.addEventListener('input', e => {
  if (e.target.id === 'ans') syncAns();
  if (e.target.id === 'q') { S.filters.q = e.target.value; redoList(); }
});
document.addEventListener('keydown', e => {
  if (e.key === 'Escape') { closeOv(); closeDrawer(); }
  if (e.key === 'Enter' && cur === 'cadastro' && e.target.tagName === 'INPUT') { e.preventDefault(); $('#btnCad').click(); }
  if ((e.key === 'Enter' || e.key === ' ') && e.target.matches && e.target.matches('article[data-act]')) { e.preventDefault(); e.target.click(); }
});

/* ===== comportamento de app no celular ===== */
const vv = window.visualViewport; let maxH = 0;
function fitViewport() {
  if (window.matchMedia('(min-width:521px)').matches) { document.documentElement.style.removeProperty('--app-h'); document.body.classList.remove('kb'); return; }
  const h = vv ? vv.height : window.innerHeight; maxH = Math.max(maxH, h, window.innerHeight);
  document.documentElement.style.setProperty('--app-h', Math.round(h) + 'px');
  document.body.classList.toggle('kb', maxH - h > 140);
  window.scrollTo(0, 0);
}
function ensureVisible(el) {
  const sc = el.closest('.sheet') || el.closest('.screen'); if (!sc) return;
  const r = el.getBoundingClientRect(), s = sc.getBoundingClientRect(), vh = vv ? vv.height : window.innerHeight;
  const limit = Math.min(s.bottom, vh) - 16;
  if (r.bottom > limit || r.top < s.top + 8) sc.scrollTo({ top: sc.scrollTop + (r.top - s.top) - Math.min(120, s.height * 0.25), behavior: 'smooth' });
}
if (vv) { vv.addEventListener('resize', () => { fitViewport(); const f = document.activeElement; if (f && f.matches && f.matches('input,textarea,select')) setTimeout(() => ensureVisible(f), 60); }); vv.addEventListener('scroll', () => window.scrollTo(0, 0)); }
window.addEventListener('resize', fitViewport);
window.addEventListener('orientationchange', () => { maxH = 0; setTimeout(fitViewport, 250); });
document.addEventListener('focusin', e => { if (e.target.matches && e.target.matches('input,textarea,select')) setTimeout(() => ensureVisible(e.target), 350); });
fitViewport();

/* gesto: deslizar da borda esquerda para voltar */
let sw = null;
document.addEventListener('touchstart', e => { const t = e.touches[0]; sw = (t.clientX < 26 && stack.length > 1 && !$('#ov').classList.contains('open') && !NONAV.includes(cur)) ? { x: t.clientX, y: t.clientY } : null; }, { passive: true });
document.addEventListener('touchend', e => { if (!sw) return; const t = e.changedTouches[0]; if (t.clientX - sw.x > 80 && Math.abs(t.clientY - sw.y) < 60) back(); sw = null; }, { passive: true });

/* gesto: arrastar a folha para baixo para fechar */
let dg = null;
document.addEventListener('touchstart', e => { const g = e.target.closest && e.target.closest('.grab'); if (g) dg = { y: e.touches[0].clientY, dy: 0 }; }, { passive: true });
document.addEventListener('touchmove', e => { if (!dg) return; dg.dy = Math.max(0, e.touches[0].clientY - dg.y); $('#sheet').style.transition = 'none'; $('#sheet').style.transform = `translateY(${dg.dy}px)`; }, { passive: true });
document.addEventListener('touchend', () => { if (!dg) return; const sh = $('#sheet'); sh.style.transition = ''; sh.style.transform = ''; if (dg.dy > 90) closeOv(); dg = null; }, { passive: true });

/* ===== inicialização ===== */
function init() {
  const vp = $('#viewport');
  Object.keys(V).forEach(id => { const s = document.createElement('section'); s.className = 'screen'; s.id = 's-' + id; vp.appendChild(s); });
  $('#tabbar').innerHTML = [['home', 'Início', 'home'], ['rede', 'Rede', 'users'], ['padrinho', 'Padrinho', 'heart'], ['sim', 'Simulação', 'mic'], ['perfil', 'Perfil', 'user']]
    .map(t => `<button class="tab" data-go="${t[0]}"><span class="ti">${icon(t[2], 22)}</span>${t[1]}</button>`).join('');
  $('#side').innerHTML = `<div class="side-logo">${logoMark(40, '#087F8C', '#FF9F43')}<b>Elo</b></div>
    <h2>Protótipo navegável</h2><p>Rede de ex-alunos, Padrinho de Currículo e Mutirão de Simulação com IA, até a carta de recomendação verificável.</p>
    <p class="side-h">Jornada do jovem</p>${STAGES.map((s, i) => `<button class="st" data-go="${s[1]}"><span>${i + 1}</span>${s[0]}</button>`).join('')}
    <p class="side-f">Todos os nomes, empresas e dados são fictícios.</p>`;
  $$('.tab,.st').forEach(b => b.setAttribute('type', 'button'));
  go('splash', { reset: true });
}
window.__elo = { go, get state() { return S; } };
init();
})();
</script>
</body>
</html>
