<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>오늘, 나에게 · Dear Me, Today</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Gowun+Batang:wght@400;700&family=Gowun+Dodum&family=Nanum+Myeongjo:wght@400;700&family=Nanum+Pen+Script&family=Hi+Melody&family=Gaegu:wght@400;700&family=Song+Myung&family=Yeon+Sung&family=Poor+Story&family=Dongle:wght@400;700&family=Playfair+Display:ital,wght@1,500&family=Cormorant+Garamond:ital,wght@1,500&family=Dancing+Script:wght@500&family=Great+Vibes&family=Caveat:wght@500&family=Parisienne&family=Sacramento&display=swap" rel="stylesheet">
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#faf6f0;--card:#fff;--ink:#3b3330;--sub:#8a7d74;--line:#e8dfd4;--accent:#c9826b;--accent-ink:#fff}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#1d1917;--card:#2a2522;--ink:#f1e9e1;--sub:#a99c91;--line:#3d3631;--accent:#d98f77;--accent-ink:#1d1917}}
:root[data-theme="dark"]{--bg:#1d1917;--card:#2a2522;--ink:#f1e9e1;--sub:#a99c91;--line:#3d3631;--accent:#d98f77;--accent-ink:#1d1917}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Gowun Batang","Noto Serif KR",serif;line-height:1.6}
.wrap{max-width:1100px;margin:0 auto;padding:20px 16px 48px}
h1{font-size:30px;margin:8px 0 0;line-height:1.25}.en{font-family:"Cormorant Garamond","Playfair Display",serif;font-style:italic;font-size:20px;color:var(--accent);margin:0 0 10px}.sub b{font-weight:400;color:var(--ink)}
.sub{color:var(--sub);margin:0 0 18px;font-size:15px}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:14px}
label.l{font-weight:700;font-size:15px}
textarea,select{width:100%;font:inherit;font-size:15px;color:var(--ink);background:var(--bg);border:1px solid var(--line);border-radius:10px;padding:8px 10px;margin-top:6px}
textarea{resize:vertical;min-height:64px}
.chips{display:flex;flex-wrap:wrap;gap:6px;margin:10px 0 12px}
button,label.btn{font:inherit;font-size:14px;cursor:pointer;border:1px solid var(--line);background:var(--card);color:var(--ink);border-radius:999px;padding:7px 14px}
button.primary{background:var(--accent);color:var(--accent-ink);border-color:var(--accent);font-weight:700;font-size:16px;padding:11px 20px;width:100%}
button:disabled{opacity:.6;cursor:wait}
.msg{font-size:13px;color:var(--accent);text-align:center;min-height:20px;margin-top:6px}
.cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(230px,1fr));gap:14px;margin:18px 0}
.item{display:flex;flex-direction:column;gap:6px}
canvas{width:100%;height:auto;display:block;border-radius:10px;border:1px solid var(--line);aspect-ratio:9/16}
.row{display:flex;gap:6px;flex-wrap:wrap}
.row select{flex:1;min-width:90px;margin:0;padding:6px 8px;font-size:13px}
.row button,.row label.btn{padding:6px 10px;font-size:13px}
.bar{display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
.opts{display:flex;gap:10px;flex-wrap:wrap;margin:0 0 12px}.opts label{flex:1;min-width:150px;font-size:14px}
.pool{margin-top:14px}.pool h3{margin:0 0 8px;font-size:15px}.pgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:8px}.pc{text-align:left;border-radius:12px;padding:10px 12px;position:relative;line-height:1.5}.pc span{display:block;padding-right:18px}.pc.on{border-color:var(--accent);background:var(--bg);box-shadow:0 0 0 1px var(--accent) inset}.pc i{position:absolute;top:6px;right:8px;font-style:normal;font-size:12px;background:var(--accent);color:var(--accent-ink);border-radius:999px;width:20px;height:20px;text-align:center;line-height:20px}
.kakao{background:#fee500;color:#191919;border-color:#fee500;font-weight:700}
.viewer{position:fixed;inset:0;z-index:20;background:rgba(20,15,12,.95);overflow:auto;padding:calc(env(safe-area-inset-top,0px) + 12px) 12px calc(env(safe-area-inset-bottom,0px) + 24px);color:#fff}.viewer[hidden]{display:none}.viewer .top{position:sticky;top:0;display:flex;gap:10px;align-items:flex-start;justify-content:space-between;background:rgba(20,15,12,.95);padding:4px 0 10px;z-index:1}.viewer p{margin:0;font-size:14px;line-height:1.6}.viewer img{width:min(100%,420px);display:block;margin:14px auto 8px;border-radius:10px}.viewer .vb{display:block;margin:0 auto 10px;background:transparent;color:#fff;border-color:rgba(255,255,255,.4)}.viewer .top button{background:#fee500;color:#191919;border-color:#fee500;font-weight:700;white-space:nowrap}
input[type=file]{display:none}
.hint{font-size:13px;color:var(--sub);text-align:center;margin:10px 0 0}
</style>
</head>
<body>
<div class="wrap">
  <h1>🌿 오늘, 나에게</h1>
  <div class="en">Dear Me, Today</div>
  <p class="sub"><b>남을 챙기느라 자신을 놓친 사람이,<br>오늘만큼은 자기 자신에게 위로를 건네는 공간</b><br>지금 받고 싶은 위로를 적어 주세요. 그 마음에 맞는 글귀와 풍경으로 인스타용 9:16 이미지 4장을 만들어 드려요.</p>
  <div class="card">
    <label class="l" for="feel">어떤 위로를 받고 싶으세요?</label>
    <textarea id="feel" placeholder="예) 요즘 너무 지쳐서 아무것도 하기 싫어요"></textarea>
        <div class="opts"><label>감정 (고르면 바로 시작) <select id="emo"><option value="">감정을 골라 보세요</option></select></label><label>문구 언어 <select id="lang"><option value="ko">한국어</option><option value="en">English</option><option value="both">한글 + English</option></select></label><label>문체 <select id="tone"><option>다정하고 따뜻한 위로</option><option>편지처럼 다정하게</option><option>시처럼 담백하고 여운 있게</option><option>유쾌하고 힘이 나는 응원</option><option>짧고 단단한 한 줄</option></select></label><label>이미지 테마 <select id="theme"><option value="">AI가 마음에 맞게 고르기</option></select></label><label>글씨체 (전체 적용) <select id="font"></select></label></div>
    <button class="primary" id="gen">🌿 위로 글귀 12개 만들기</button>
    <div class="msg" id="msg"></div>
  </div>
  <div class="card pool" id="poolBox" hidden><h3>마음에 드는 글귀 4개를 골라 주세요 <span id="pcount"></span></h3><div class="pgrid" id="pool"></div></div>
  <div class="cards" id="cards"></div>
  <div class="bar"><button id="regen">🔄 다른 12개 다시 받기</button><button id="shuf">🎨 풍경만 바꾸기</button><button id="redesign">✨ 풍경만 AI로 다시 설계</button><button id="shareAll" class="kakao">📤 4장 카톡으로 공유</button><button id="viewAll">🖼 이미지 열어 보내기</button><button id="copyAll">📋 글귀 복사</button><button id="saveAll">💾 4장 모두 저장</button></div>
  <p class="hint">📤 공유를 누르면 휴대폰의 공유 창이 열려요. 거기서 카카오톡을 고르면 돼요. 안 열리면 저장한 뒤 카톡에서 사진으로 보내 주세요. 문구와 풍경은 장마다 직접 고칠 수 있어요.</p>
</div>
<div class="viewer" id="viewer" hidden><div class="top"><p><b>휴대폰</b>: 이미지를 <b>길게 눌러서</b> 저장·공유 메뉴에서 카카오톡을 고르세요.<br><b>PC</b>: 이미지를 <b>우클릭 → 이미지 복사</b> 한 뒤 카톡 대화창에 붙여넣기(Ctrl+V)</p><button id="vclose">닫기 ✕</button></div><div id="vlist"></div></div>
<script>
const TH=["rainwarm","garden","dawnsea","pinkridge","fogpath","moonquiet","booktea","countrypath","clearsky","springtree","winterwindow","dawnlake"];
const SC=[["rainwarm","비 내리는 창가와 따뜻한 실내 조명"],["garden","햇살이 비치는 꽃과 정원"],["dawnsea","새벽 바다와 잔잔한 파도"],["pinkridge","분홍빛 노을과 산 능선"],["fogpath","안개가 내려앉은 숲길"],["moonquiet","달빛 아래 조용한 풍경"],["booktea","책과 차가 놓인 아늑한 공간"],["countrypath","들꽃이 피어 있는 시골길"],["clearsky","비 온 뒤 맑아진 하늘"],["springtree","봄날의 나무와 부드러운 햇살"],["winterwindow","겨울 창가와 포근한 담요"],["dawnlake","새벽의 고요한 호수"],["sunset","노을"],["forest","숲"],["sea","바다"],["night","별밤"],["flower","들꽃"],["mist","새벽 안개"],["rain","비 오는 창가"],["snow","눈 내리는 밤"],["autumn","가을 낙엽"],["cherry","벚꽃"],["aurora","오로라"],["lake","달빛 호수"],["cloud","구름 하늘"],["lavender","라벤더 들판"],["mountain","산 위 일출"],["lantern","소원 등불"],["starfall","별똥별"],["firefly","반딧불 숲"],["rainbow","비 갠 무지개"],["dandelion","민들레 홀씨"],["sunflower","해바라기"],["candle","촛불"],["balloon","풍선 하늘"],["paperboat","종이배"],["lighthouse","등대"],["bokeh","노을 불빛"],["ai","✨ AI 맞춤 풍경"]];
const FONTS=[
{id:"gowun",label:"고운바탕 (명조)",css:"Gowun Batang",w:700,st:"",sc:1},
{id:"dodum",label:"고운돋움 (고딕)",css:"Gowun Dodum",w:400,st:"",sc:1},
{id:"myeong",label:"나눔명조",css:"Nanum Myeongjo",w:700,st:"",sc:1},
{id:"pen",label:"나눔손글씨 펜",css:"Nanum Pen Script",w:400,st:"",sc:1.35},
{id:"melody",label:"하이멜로디",css:"Hi Melody",w:400,st:"",sc:1.15},
{id:"gaegu",label:"개구 (손글씨)",css:"Gaegu",w:700,st:"",sc:1.1},
{id:"songm",label:"송명 (붓글씨)",css:"Song Myung",w:400,st:"",sc:1},
{id:"yeon",label:"연성 (감성 손글씨)",css:"Yeon Sung",w:400,st:"",sc:1.05},
{id:"poor",label:"푸어스토리",css:"Poor Story",w:400,st:"",sc:1.1},
{id:"dongle",label:"동글",css:"Dongle",w:400,st:"",sc:1.5},
{id:"playfair",label:"Playfair Display (영문 세리프)",css:"Playfair Display",w:500,st:"italic",sc:.95},
{id:"cormorant",label:"Cormorant Garamond (영문 우아)",css:"Cormorant Garamond",w:500,st:"italic",sc:1.15},
{id:"dancing",label:"Dancing Script (영문 필기)",css:"Dancing Script",w:500,st:"",sc:1.05},
{id:"vibes",label:"Great Vibes (영문 캘리)",css:"Great Vibes",w:400,st:"",sc:1.25},
{id:"caveat",label:"Caveat (영문 손글씨)",css:"Caveat",w:500,st:"",sc:1.2},
{id:"parisienne",label:"Parisienne (영문 필기체)",css:"Parisienne",w:400,st:"",sc:1.15},
{id:"sacramento",label:"Sacramento (영문 가는 필기)",css:"Sacramento",w:400,st:"",sc:1.3}
];
const fsc=c=>(FONTS.find(x=>x.id===c.font)||FONTS[0]).sc;
const fontStr=(c,fs)=>{const F=FONTS.find(x=>x.id===c.font)||FONTS[0];return F.st+" "+F.w+" "+Math.round(fs*F.sc)+"px '"+F.css+"','Gowun Batang','Nanum Myeongjo',serif"};
const lf=c=>document.fonts.load(fontStr(c,60),(c.text||"")+"가a").catch(()=>0);
const langp=()=>{const v=$("lang").value;return v==="en"?"영어(자연스럽고 시적인 영어, 줄바꿈 포함 2줄 이내, 12단어 이내)":v==="both"?"한국어 한 줄 뒤에 줄바꿈 하고 그 영어 번역 한 줄을 붙인 형태(한 문구의 text 안에 함께 넣기, 한국어 25자 이내, 영어 10단어 이내)":"한국어"};
const SCK=SC.map(s=>s[0]).filter(k=>k!=="ai");
const FB=[
{k:/인간관계|관계에|사람들|사람.*지치/,t:["모두에게 좋은 사람이\n되지 않아도 괜찮아요","거리를 두는 것도\n나를 지키는 다정한 방법이에요","맞지 않는 사람 곁에서\n애쓰지 않아도 돼요","오늘은 내 마음 곁에\n조용히 머물러 주세요"],s:["rainwarm","booktea","fogpath","moonquiet"],e:["You don't have to be\neveryone's favorite person.","Keeping distance is also\na gentle way to protect yourself.","You don't need to strain\nbeside those who don't fit.","Tonight, stay quietly\nwith your own heart."]},
{k:/자신감|자존감|초라|못나|쓸모/,t:["당신은 생각보다\n훨씬 잘 해내고 있어요","작은 한 걸음도\n분명한 성장이에요","비교하지 않아도\n당신의 속도는 충분히 아름다워요","스스로를 믿어 주는 마음이\n가장 큰 용기예요"],s:["springtree","garden","clearsky","pinkridge"],e:["You are doing far better\nthan you think.","Even a small step\nis real growth.","You don't have to compare.\nYour own pace is beautiful.","Believing in yourself\nis the greatest courage."]},
{k:/새로운 시작|시작이|도전|낯선|두려운 날/,t:["처음은 누구에게나\n떨리는 법이에요","완벽하게 준비되지 않아도\n시작해도 괜찮아요","두려움은 당신이 앞으로\n나아가고 있다는 신호예요","한 걸음만 내디디면\n길은 따라 열려요"],s:["dawnsea","countrypath","dawnlake","clearsky"],e:["Beginnings tremble\nfor everyone.","You don't have to be\nfully ready to begin.","Fear is a sign\nthat you are moving forward.","Take one step,\nand the path will open."]},
{k:/중년|인생 ?2막|2막|나이 들|오십|쉰/,t:["지나온 시간이 당신을\n단단하고 깊게 만들었어요","지금부터가\n나를 위한 인생의 2막이에요","늦은 때란 없어요\n오늘이 가장 젊은 날이에요","애쓴 날들이\n이제 따뜻한 쉼이 되기를"],s:["pinkridge","booktea","countrypath","springtree"],e:["The years behind you\nmade you deep and strong.","From here on,\nact two is for you.","It's never too late.\nToday is your youngest day.","May all your hard-working days\nbecome a warm rest."]},
{k:/허전|이유 없|괜히|텅 빈|공허/,t:["이유 없이 허전한 날도\n있는 법이에요","비어 있는 마음에도\n고요히 머물 자리가 생겨요","아무것도 채우지 않아도\n오늘의 당신은 충분해요","이 허전함도 지나가요\n따뜻한 차 한 잔과 함께"],s:["fogpath","dawnlake","booktea","moonquiet"],e:["Some days feel empty\nfor no reason at all.","Even an empty heart\nholds a quiet place to rest.","Without filling anything,\nyou are enough today.","This emptiness will pass,\nwith a warm cup of tea."]},
{k:/행복|소소|기쁨|감사|좋은 일/,t:["오늘 마신 따뜻한 차 한 잔\n그게 작은 행복이에요","창밖의 햇살이\n나에게 건네는 인사 같아요","별일 없는 하루도\n참 고마운 하루예요","작은 기쁨을 알아보는\n당신의 눈이 참 예뻐요"],s:["booktea","garden","springtree","clearsky"],e:["A warm cup of tea today.\nThat is a small happiness.","Sunlight at the window\nis a greeting just for you.","An uneventful day\nis a day to be grateful for.","Your eyes that notice small joys\nare truly lovely."]},
{k:/스스로|사랑하고 싶|자기애|나를 사랑|나 자신/,t:["오늘의 나를\n꼭 안아 주세요","있는 그대로의 나도\n충분히 사랑받을 자격이 있어요","나에게 가장 다정한 사람이\n내가 되어 주세요","나를 아끼는 마음이\n모든 사랑의 시작이에요"],s:["garden","winterwindow","pinkridge","springtree"],e:["Hold today's you\nclose and tight.","The way you are\ndeserves love already.","Be the kindest person\nto yourself.","Caring for yourself\nis where all love begins."]},
{k:/지치|지쳐|피곤|힘들|번아웃|무기력|쉬고/,t:["오늘도 버텨 낸 당신,\n정말 수고 많았어요","지쳐도 괜찮아요\n쉬어 가는 것도 용기예요","아무것도 안 해도 되는 날\n오늘이 그날이면 좋겠어요","천천히 숨 쉬어요\n내일은 조금 가벼울 거예요"],s:["rainwarm","booktea","dawnlake","pinkridge"],e:["You made it through today.\nThat is enough.","It's okay to be tired.\nResting is also brave.","Some days you don't have to do anything.\nMay today be one.","Breathe slowly.\nTomorrow will feel a little lighter."]},
{k:/실수|실패|망했|망쳐|시험|떨어|후회|자책/,t:["실수한 나도\n여전히 괜찮은 사람이에요","넘어진 자리에서도\n꽃은 다시 피어나요","이번 일이 당신의 전부를\n말해 주지는 않아요","오늘은 나를 꼭 안아 주고\n내일 다시 걸어요"],s:["clearsky","garden","springtree","dawnsea"],e:["A mistake doesn't make you\nany less worthy.","Flowers bloom again\nwhere you once fell.","This one moment is not\nthe whole of you.","Hold yourself tonight.\nWalk again tomorrow."]},
{k:/외로|혼자|쓸쓸|공허|아무도/,t:["혼자인 것 같은 밤에도\n당신은 혼자가 아니에요","별은 늘 그 자리에서\n당신을 지켜보고 있어요","마음을 털어놓을 한 사람이\n곧 곁에 와 줄 거예요","오늘은 나 자신의 가장\n다정한 친구가 되어 주세요"],s:["moonquiet","winterwindow","fogpath","dawnlake"],e:["Even on lonely nights,\nyou are not alone.","The stars are always there,\nwatching over you.","Someone to listen\nwill come to you soon.","Be your own\nkindest friend tonight."]},
{k:/불안|걱정|무서|두렵|초조|떨려/,t:["불안한 마음도\n당신의 일부일 뿐이에요","지금 이 순간,\n깊게 숨 한 번 쉬어 봐요","아직 오지 않은 일은\n오늘의 당신 몫이 아니에요","한 걸음씩이면 충분해요\n잘 해내고 있어요"],s:["fogpath","dawnsea","countrypath","clearsky"],e:["Your anxious heart\nis only one part of you.","Right now,\ntake one deep breath.","What hasn't happened yet\nisn't tonight's burden.","One step at a time is enough.\nYou're doing well."]},
{k:/이별|헤어|그리워|보고싶|떠나|상실|슬프/,t:["아파하는 만큼\n사랑했다는 뜻이에요","눈물이 나면 울어도 괜찮아요\n그것도 마음이 쉬는 방법이에요","시간은 천천히\n마음을 어루만져 줄 거예요","언젠가 이 기억이\n따뜻하게 남을 날이 올 거예요"],s:["rainwarm","moonquiet","dawnsea","pinkridge"],e:["The ache is only\nas deep as the love.","Cry if you need to.\nIt's how the heart rests.","Time will slowly\nsoothe your heart.","One day this memory\nwill feel warm."]},
{k:/.*/,t:["오늘도 여기까지 오느라\n정말 애썼어요","잘하지 못한 날에도\n당신은 충분히 소중해요","구름이 지나가도\n하늘은 늘 그 자리에 있어요","내일의 당신에게\n좋은 일이 천천히 오고 있어요"],s:["pinkridge","garden","clearsky","springtree"],e:["You worked so hard\nto get here today.","Even on off days,\nyou are precious.","Clouds may pass,\nthe sky is always there.","Good things are slowly\non their way to you."]}
];
const CHIPS=["지치고 힘든 날","실수하고 자책하는 날","외롭고 쓸쓸한 날","불안하고 걱정되는 날","이별과 상실","인간관계에 지친 날","자신감이 없는 날","새로운 시작이 두려운 날","중년의 삶과 인생 2막","아무 이유 없이 마음이 허전한 날","작은 행복을 발견하고 싶은 날","스스로를 사랑하고 싶은 날"];
const $=id=>document.getElementById(id);
let seedBase=7,dl=null;
const cuts=[0,1,2,3].map(()=>({scene:"sunset",text:"",img:null,font:"gowun"}));
function applyFB(f){const s=FB.find(x=>x.k.test(f))||FB[FB.length-1];const L=$("lang").value;cuts.forEach((c,i)=>{c.text=L==="en"?s.e[i]:L==="both"?s.t[i]+"\n"+s.e[i]:s.t[i];c.scene=s.s[i];c.img=null})}
function rngf(s){return()=>(s=(s*1664525+1013904223)%4294967296)/4294967296}
function lin(c,w,h,stops){const g=c.createLinearGradient(0,0,0,h);stops.forEach(([p,col])=>g.addColorStop(p,col));c.fillStyle=g;c.fillRect(0,0,w,h)}
function hills(c,w,h,r,n,y0,amp,cols){for(let k=0;k<n;k++){c.fillStyle=cols[k];c.beginPath();c.moveTo(0,h);const ph=r()*6,fr=1.2+r()*1.5,by=y0+k*(h-y0)/(n+1);for(let x=0;x<=w;x+=10)c.lineTo(x,by+Math.sin(x/w*fr*Math.PI+ph)*amp);c.lineTo(w,h);c.fill()}}
function glow(c,x,y,rad,col){const g=c.createRadialGradient(x,y,0,x,y,rad);g.addColorStop(0,col);g.addColorStop(1,"rgba(255,255,255,0)");c.fillStyle=g;c.fillRect(0,0,c.canvas.width,c.canvas.height)}
function scene(c,w,h,type,seed,art){
  const r=rngf(seed*97+13),m=Math.min(w,h),pal=d=>{const a=(art&&Array.isArray(art.sky)?art.sky.filter(x=>HX.test(x)):[]);return a.length>=3?a.slice(0,3):d},gc=art&&HX.test(art.glow)?art.glow:null;
  if(type==="sunset"){lin(c,w,h,[[0,"#5b4b8a"],[.4,"#e58f9c"],[.65,"#ffc58a"],[1,"#ffe6b5"]]);glow(c,w*.5,h*.62,w*.9,"rgba(255,240,200,.9)");c.fillStyle="#fff3d0";c.beginPath();c.arc(w*.5,h*.62,m*.1,0,7);c.fill();hills(c,w,h,r,3,h*.7,40,["#c0728a","#8a5a86","#4d3d6b"])}
  else if(type==="forest"){lin(c,w,h,[[0,"#cfe8c9"],[.6,"#8fc3a0"],[1,"#2f6b57"]]);glow(c,w*.7,h*.08,w*.9,"rgba(255,255,220,.7)");for(let k=0;k<3;k++){c.fillStyle=["#6da98a","#3f8267","#21594a"][k];for(let i=0;i<8;i++){const x=r()*w,b=h*(.68+k*.1),t=h*(.14+r()*.1+k*.03),ww=w*(.1+r()*.06);c.beginPath();c.moveTo(x,b-t);c.lineTo(x-ww,b);c.lineTo(x+ww,b);c.fill();c.fillRect(x-6,b,12,h-b)}}c.fillStyle="#21594a";c.fillRect(0,h*.93,w,h)}
  else if(type==="sea"){lin(c,w,h,[[0,"#8ec5e8"],[.55,"#cfe9f2"],[.57,"#5aa4c6"],[1,"#1f5f86"]]);c.fillStyle="#fff7dc";c.beginPath();c.arc(w*.3,h*.42,m*.07,0,7);c.fill();for(let i=0;i<40;i++){const y=h*.6+i*(h*.4/40),x=r()*w;c.strokeStyle="rgba(255,255,255,"+(.15+r()*.3)+")";c.lineWidth=3;c.beginPath();c.moveTo(x-w*.15,y);c.quadraticCurveTo(x,y-12,x+w*.15,y);c.stroke()}}
  else if(type==="night"){lin(c,w,h,[[0,"#0d1b3d"],[.6,"#2c3e7a"],[1,"#5a6fae"]]);for(let i=0;i<160;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.7)+")";c.beginPath();c.arc(r()*w,r()*h*.8,r()*2.6+.6,0,7);c.fill()}glow(c,w*.72,h*.2,w*.6,"rgba(255,248,210,.6)");c.fillStyle="#fff6cf";c.beginPath();c.arc(w*.72,h*.2,m*.07,0,7);c.fill();hills(c,w,h,r,2,h*.82,30,["#1c2a56","#0e1733"])}
  else if(type==="flower"){lin(c,w,h,[[0,"#d9ecff"],[.58,"#fdf1e3"],[.59,"#a9d3a1"],[1,"#5f9d6b"]]);for(let i=0;i<80;i++){const x=r()*w,y=h*.62+r()*h*.38,s=5+(y/h-.6)*60;c.strokeStyle="#4e8a5c";c.lineWidth=2.5;c.beginPath();c.moveTo(x,y);c.lineTo(x,y+s*2.5);c.stroke();c.fillStyle=["#ffd1dc","#fff4a8","#ffffff","#e8c8ff"][i%4];for(let p=0;p<5;p++){c.beginPath();c.arc(x+Math.cos(p*1.26)*s,y+Math.sin(p*1.26)*s,s*.7,0,7);c.fill()}c.fillStyle="#f6a623";c.beginPath();c.arc(x,y,s*.5,0,7);c.fill()}}
  else if(type==="rain"){lin(c,w,h,[[0,"#3b4a5e"],[.6,"#5c7089"],[1,"#2a3544"]]);for(let i=0;i<34;i++){const x=r()*w,y=h*(.4+r()*.55),R=m*(.03+r()*.07),col=["255,214,150","255,170,140","190,220,255"][i%3],g=c.createRadialGradient(x,y,0,x,y,R);g.addColorStop(0,"rgba("+col+",.55)");g.addColorStop(1,"rgba("+col+",0)");c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}c.strokeStyle="rgba(255,255,255,.35)";c.lineWidth=2.5;for(let i=0;i<120;i++){const x=r()*w,y=r()*h,l=40+r()*80;c.beginPath();c.moveTo(x,y);c.lineTo(x-l*.15,y+l);c.stroke()}for(let i=0;i<40;i++){const R=6+r()*12;c.fillStyle="rgba(255,255,255,.28)";c.beginPath();c.ellipse(r()*w,r()*h,R*.7,R*1.3,0,0,7);c.fill()}}
  else if(type==="snow"){lin(c,w,h,[[0,"#1b2a4a"],[.7,"#4a6a94"],[1,"#c9d9ee"]]);for(let k=0;k<2;k++){c.fillStyle=k?"#1f3b4d":"#2c5266";for(let i=0;i<7;i++){const x=r()*w,b=h*(.78+k*.05),t=h*(.1+r()*.07),ww=w*.09;c.beginPath();c.moveTo(x,b-t);c.lineTo(x-ww,b);c.lineTo(x+ww,b);c.fill()}}c.fillStyle="#eef4fb";c.beginPath();c.moveTo(0,h);for(let x=0;x<=w;x+=10)c.lineTo(x,h*.85+Math.sin(x/w*3+1)*30);c.lineTo(w,h);c.fill();for(let i=0;i<180;i++){c.fillStyle="rgba(255,255,255,"+(.4+r()*.6)+")";c.beginPath();c.arc(r()*w,r()*h,r()*5+1.5,0,7);c.fill()}}
  else if(type==="autumn"){lin(c,w,h,[[0,"#ffe3b8"],[.5,"#f6b57a"],[1,"#b5543a"]]);hills(c,w,h,r,2,h*.72,35,["#d9893f","#a64a2e"]);const cl=["#c8452d","#e8892f","#f2b84b","#a8532e"];for(let i=0;i<70;i++){c.fillStyle=cl[i%4];c.save();c.translate(r()*w,r()*h);c.rotate(r()*6);c.beginPath();c.ellipse(0,0,10+r()*14,5+r()*7,0,0,7);c.fill();c.restore()}}
  else if(type==="cherry"){lin(c,w,h,[[0,"#fde6ee"],[.6,"#f9c9d8"],[1,"#fff3ee"]]);c.strokeStyle="#6b4a47";c.lineWidth=14;c.beginPath();c.moveTo(w,h*.08);c.quadraticCurveTo(w*.55,h*.14,w*.15,h*.12);c.stroke();c.lineWidth=7;c.beginPath();c.moveTo(w*.6,h*.13);c.quadraticCurveTo(w*.5,h*.22,w*.35,h*.24);c.stroke();for(let i=0;i<110;i++){const t=r(),x=w*(.1+t*.9),y=h*.1+r()*h*.12,s=10+r()*16;c.fillStyle=["#ffc2d4","#ffdbe6","#fff","#f7a9c1"][i%4];for(let p=0;p<5;p++){c.beginPath();c.arc(x+Math.cos(p*1.26)*s*.7,y+Math.sin(p*1.26)*s*.7,s*.6,0,7);c.fill()}}for(let i=0;i<90;i++){c.fillStyle="rgba(255,190,210,"+(.4+r()*.5)+")";c.beginPath();c.ellipse(r()*w,h*.3+r()*h*.7,6+r()*6,4+r()*3,r()*3,0,7);c.fill()}}
  else if(type==="aurora"){lin(c,w,h,[[0,"#061226"],[1,"#12304a"]]);for(let i=0;i<120;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.7)+")";c.beginPath();c.arc(r()*w,r()*h*.8,r()*2.4+.5,0,7);c.fill()}for(let k=0;k<4;k++){const col=["80,255,180","120,200,255","190,130,255","90,255,210"][k],ph=r()*3,g=c.createLinearGradient(0,h*.1,0,h*.6);g.addColorStop(0,"rgba("+col+",0)");g.addColorStop(.5,"rgba("+col+",.45)");g.addColorStop(1,"rgba("+col+",0)");c.fillStyle=g;c.beginPath();c.moveTo(0,h*.2);for(let x=0;x<=w;x+=20)c.lineTo(x,h*(.25+k*.04)+Math.sin(x/w*(3+k)+ph)*110);c.lineTo(w,h*.62);c.lineTo(0,h*.62);c.fill()}hills(c,w,h,r,2,h*.84,25,["#d5e3f2","#9fb7d0"])}
  else if(type==="lake"){lin(c,w,h,[[0,"#2b3a67"],[.45,"#8f86b8"],[.5,"#e9c9c0"],[.5,"#3c4a78"],[1,"#1b2347"]]);hills(c,w,h*.5,r,2,h*.36,25,["#4a4a7d","#2c2f5c"]);glow(c,w*.6,h*.22,w*.5,"rgba(255,246,216,.45)");c.fillStyle="#fff6d8";c.beginPath();c.arc(w*.6,h*.22,m*.07,0,7);c.fill();c.fillStyle="rgba(255,246,216,.35)";for(let i=0;i<20;i++){const ww=m*(.12-i*.004)*(.6+r()*.6);c.fillRect(w*.6-ww/2,h*.52+i*30,ww,5)}}
  else if(type==="cloud"){lin(c,w,h,[[0,"#7db8ec"],[.7,"#cde6fa"],[1,"#fdf0e0"]]);for(let k=0;k<7;k++){const cx=r()*w,cy=h*(.12+k*.12),sc=m*(.1+r()*.1);c.fillStyle="rgba(255,255,255,"+(.55+r()*.4)+")";for(let j=0;j<6;j++){c.beginPath();c.arc(cx+(j-2.5)*sc*.7,cy+Math.sin(j*1.7)*sc*.25,sc*(.5+r()*.4),0,7);c.fill()}}glow(c,w*.5,h*.9,w*.8,"rgba(255,225,190,.7)")}
  else if(type==="lavender"){lin(c,w,h,[[0,"#f3d9e8"],[.45,"#e6c9ee"],[.5,"#8a6bb5"],[1,"#4b3478"]]);glow(c,w*.5,h*.46,w*.8,"rgba(255,235,210,.8)");for(let i=0;i<900;i++){const t=Math.pow(r(),1.6),y=h*.5+t*h*.5,x=r()*w,s=4+t*40;c.strokeStyle=["#b79bdc","#9a78c8","#d2b8ee","#7d5bb0"][i%4];c.lineWidth=2+t*6;c.beginPath();c.moveTo(x,y);c.lineTo(x+(r()-.5)*s*.5,y-s*2.2);c.stroke()}}
  else if(type==="mountain"){lin(c,w,h,[[0,"#9ec5e6"],[.45,"#ffd9bd"],[.7,"#ffb8a1"],[1,"#7d6a8f"]]);glow(c,w*.5,h*.5,w*.8,"rgba(255,235,190,.85)");c.fillStyle="#fff2cf";c.beginPath();c.arc(w*.5,h*.5,m*.08,0,7);c.fill();const cs=["rgba(190,150,170,.7)","rgba(150,120,155,.8)","rgba(105,90,135,.9)","#4a4268"];for(let k=0;k<4;k++){c.fillStyle=cs[k];c.beginPath();c.moveTo(0,h);c.lineTo(0,h*(.55+k*.1));for(let x=0;x<=w;x+=60)c.lineTo(x,h*(.55+k*.1)-(r()*.5+.5)*h*(.12-k*.015)*Math.abs(Math.sin(x/w*(2+k)+k)));c.lineTo(w,h);c.fill()}}
  else if(type==="lantern"){lin(c,w,h,[[0,"#1a1838"],[.6,"#4a2f55"],[1,"#c46a4a"]]);for(let i=0;i<70;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.6)+")";c.beginPath();c.arc(r()*w,r()*h*.6,r()*2+.5,0,7);c.fill()}for(let i=0;i<26;i++){const x=r()*w,y=h*(.1+r()*.8),s=m*(.025+r()*.04),g=c.createRadialGradient(x,y,0,x,y,s*4);g.addColorStop(0,"rgba(255,200,110,.8)");g.addColorStop(1,"rgba(255,160,60,0)");c.fillStyle=g;c.beginPath();c.arc(x,y,s*4,0,7);c.fill();c.fillStyle="#ffd99a";c.fillRect(x-s*.5,y-s*.7,s,s*1.4)}}
  else if(type==="starfall"){lin(c,w,h,[[0,"#070d24"],[.7,"#1d2a5c"],[1,"#3a3f7a"]]);for(let i=0;i<150;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.7)+")";c.beginPath();c.arc(r()*w,r()*h*.8,r()*2.4+.5,0,7);c.fill()}for(let i=0;i<4;i++){const x=w*(.3+r()*.7),y=h*(.08+r()*.4),l=m*(.2+r()*.2),g=c.createLinearGradient(x,y,x-l,y+l*.5);g.addColorStop(0,"rgba(255,255,255,.95)");g.addColorStop(1,"rgba(255,255,255,0)");c.strokeStyle=g;c.lineWidth=5;c.beginPath();c.moveTo(x,y);c.lineTo(x-l,y+l*.5);c.stroke()}hills(c,w,h,r,2,h*.84,25,["#141b3f","#0a0f26"])}
  else if(type==="firefly"){lin(c,w,h,[[0,"#0b1f1c"],[.6,"#143a33"],[1,"#07140f"]]);for(let k=0;k<3;k++){c.fillStyle=["#10302a","#0c241f","#071712"][k];for(let i=0;i<9;i++){const x=r()*w,b=h*(.7+k*.1),t=h*(.18+r()*.12),ww=w*.1;c.beginPath();c.moveTo(x,b-t);c.lineTo(x-ww,b);c.lineTo(x+ww,b);c.fill()}}c.fillRect(0,h*.9,w,h);for(let i=0;i<60;i++){const x=r()*w,y=h*(.25+r()*.65),s=6+r()*10,g=c.createRadialGradient(x,y,0,x,y,s*3);g.addColorStop(0,"rgba(230,255,150,.95)");g.addColorStop(.3,"rgba(200,255,120,.4)");g.addColorStop(1,"rgba(200,255,120,0)");c.fillStyle=g;c.beginPath();c.arc(x,y,s*3,0,7);c.fill()}}
  else if(type==="rainbow"){lin(c,w,h,[[0,"#b9d4e8"],[.6,"#e6eef2"],[1,"#fff4de"]]);const cs=["#ff9aa2","#ffc58a","#fff1a0","#b5e8b0","#9fd3f5","#c3b1f0"];for(let k=0;k<6;k++){c.strokeStyle=cs[k];c.globalAlpha=.55;c.lineWidth=34;c.beginPath();c.arc(w*.5,h*.62,w*.62-k*32,Math.PI,0);c.stroke()}c.globalAlpha=1;hills(c,w,h,r,2,h*.74,30,["#9cd09a","#5fa86e"])}
  else if(type==="dandelion"){lin(c,w,h,[[0,"#cfe6f7"],[.7,"#f5ecd8"],[1,"#a8c98a"]]);glow(c,w*.3,h*.15,w*.8,"rgba(255,248,215,.8)");const sx=w*.5,sy=h*.55;c.strokeStyle="#7a9a5c";c.lineWidth=6;c.beginPath();c.moveTo(w*.45,h);c.quadraticCurveTo(w*.6,h*.8,sx,sy);c.stroke();for(let i=0;i<46;i++){const a=i/46*Math.PI*2,l=m*.16;c.strokeStyle="rgba(255,255,255,.85)";c.lineWidth=2;c.beginPath();c.moveTo(sx,sy);c.lineTo(sx+Math.cos(a)*l,sy+Math.sin(a)*l);c.stroke();c.fillStyle="rgba(255,255,255,.9)";c.beginPath();c.arc(sx+Math.cos(a)*l,sy+Math.sin(a)*l,6,0,7);c.fill()}for(let i=0;i<40;i++){const x=w*(.55+r()*.5),y=h*(.1+r()*.6);c.strokeStyle="rgba(255,255,255,.8)";c.lineWidth=1.5;c.beginPath();c.moveTo(x,y);c.lineTo(x-14,y+14);c.stroke();c.fillStyle="#fff";c.beginPath();c.arc(x,y,4,0,7);c.fill()}}
  else if(type==="sunflower"){lin(c,w,h,[[0,"#8fd0f5"],[.6,"#d6efff"],[1,"#fff6d6"]]);glow(c,w*.8,h*.1,w*.8,"rgba(255,244,190,.9)");hills(c,w,h,r,1,h*.8,30,["#7fb069"]);for(let i=0;i<14;i++){const x=r()*w,y=h*(.55+r()*.35),s=m*(.05+(y/h-.5)*.2);c.strokeStyle="#4f8a3d";c.lineWidth=s*.18;c.beginPath();c.moveTo(x,y);c.lineTo(x,h);c.stroke();c.fillStyle="#f6b800";for(let p=0;p<14;p++){const a=p/14*6.283;c.beginPath();c.ellipse(x+Math.cos(a)*s,y+Math.sin(a)*s,s*.55,s*.22,a,0,7);c.fill()}c.fillStyle="#6b4423";c.beginPath();c.arc(x,y,s*.6,0,7);c.fill()}}
  else if(type==="candle"){lin(c,w,h,[[0,"#1a1210"],[1,"#3a2418"]]);glow(c,w*.5,h*.5,w*.9,"rgba(255,190,100,.55)");for(let i=0;i<40;i++){const x=r()*w,y=r()*h,R=m*(.02+r()*.05),g=c.createRadialGradient(x,y,0,x,y,R);g.addColorStop(0,"rgba(255,200,120,.35)");g.addColorStop(1,"rgba(255,200,120,0)");c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}c.fillStyle="#f3e6cf";c.fillRect(w*.5-45,h*.56,90,h*.22);c.fillStyle="rgba(0,0,0,.15)";c.fillRect(w*.5+10,h*.56,35,h*.22);c.fillStyle="#2a1a10";c.fillRect(w*.5-2,h*.54,4,h*.02);const fg=c.createRadialGradient(w*.5,h*.5,0,w*.5,h*.5,70);fg.addColorStop(0,"rgba(255,235,170,1)");fg.addColorStop(1,"rgba(255,150,40,0)");c.fillStyle=fg;c.beginPath();c.ellipse(w*.5,h*.5,28,56,0,0,7);c.fill()}
  else if(type==="balloon"){lin(c,w,h,[[0,"#a9d6f5"],[.6,"#fde9d9"],[1,"#ffd1c1"]]);for(let i=0;i<9;i++){const x=w*(.1+r()*.8),y=h*(.1+r()*.6),s=m*(.05+r()*.05);c.strokeStyle="rgba(120,100,100,.5)";c.lineWidth=2;c.beginPath();c.moveTo(x,y+s*1.2);c.quadraticCurveTo(x+20,y+s*3,x,y+s*5);c.stroke();c.fillStyle=["#ff9aa2","#ffd37a","#9fd3f5","#c3b1f0","#b5e8b0"][i%5];c.beginPath();c.ellipse(x,y,s,s*1.2,0,0,7);c.fill();c.fillStyle="rgba(255,255,255,.4)";c.beginPath();c.ellipse(x-s*.3,y-s*.4,s*.2,s*.35,.5,0,7);c.fill()}}
  else if(type==="paperboat"){lin(c,w,h,[[0,"#f7d9c4"],[.5,"#fbeede"],[.5,"#8fc4d9"],[1,"#4f8fae"]]);for(let i=0;i<30;i++){const y=h*.52+i*(h*.48/30),x=r()*w;c.strokeStyle="rgba(255,255,255,"+(.15+r()*.3)+")";c.lineWidth=3;c.beginPath();c.moveTo(x-w*.12,y);c.quadraticCurveTo(x,y-10,x+w*.12,y);c.stroke()}const bx=w*.5,by=h*.55,s=m*.14;c.fillStyle="#fff";c.beginPath();c.moveTo(bx-s,by-s*.2);c.lineTo(bx+s,by-s*.2);c.lineTo(bx+s*.6,by+s*.35);c.lineTo(bx-s*.6,by+s*.35);c.fill();c.fillStyle="#f4e7da";c.beginPath();c.moveTo(bx,by-s*1.1);c.lineTo(bx+s*.55,by-s*.2);c.lineTo(bx-s*.1,by-s*.2);c.fill();glow(c,w*.5,h*.45,w*.7,"rgba(255,235,200,.5)")}
  else if(type==="lighthouse"){lin(c,w,h,[[0,"#1e2c52"],[.55,"#6c7fb0"],[.6,"#f0c9b0"],[.6,"#34486f"],[1,"#162240"]]);for(let i=0;i<70;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.6)+")";c.beginPath();c.arc(r()*w,r()*h*.4,r()*2+.5,0,7);c.fill()}c.fillStyle="#2a2f48";c.beginPath();c.moveTo(0,h*.62);c.lineTo(w*.35,h*.6);c.lineTo(w*.7,h*.64);c.lineTo(w,h*.7);c.lineTo(w,h);c.lineTo(0,h);c.fill();const lx=w*.65,ly=h*.58;c.fillStyle="#f2ede4";c.beginPath();c.moveTo(lx-28,ly);c.lineTo(lx+28,ly);c.lineTo(lx+16,ly-h*.2);c.lineTo(lx-16,ly-h*.2);c.fill();c.fillStyle="#c9524a";c.fillRect(lx-22,ly-h*.1,44,26);c.fillStyle="#ffe9a8";c.fillRect(lx-14,ly-h*.2-30,28,30);const lg=c.createLinearGradient(lx,0,0,0);lg.addColorStop(0,"rgba(255,235,170,.55)");lg.addColorStop(1,"rgba(255,235,170,0)");c.fillStyle=lg;c.beginPath();c.moveTo(lx,ly-h*.2-15);c.lineTo(0,ly-h*.2-170);c.lineTo(0,ly-h*.2+140);c.fill()}
  else if(type==="bokeh"){lin(c,w,h,[[0,"#3a2a4a"],[.5,"#a35d6a"],[1,"#f2a65a"]]);for(let i=0;i<60;i++){const x=r()*w,y=r()*h,R=m*(.03+r()*.09),col=["255,214,150","255,170,170","255,240,200","200,170,255"][i%4],g=c.createRadialGradient(x,y,R*.6,x,y,R);g.addColorStop(0,"rgba("+col+",.28)");g.addColorStop(.9,"rgba("+col+",.4)");g.addColorStop(1,"rgba("+col+",0)");c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}}
  else if(type==="rainwarm"){const k=pal(["#2e3b50","#4d607a","#6b584a"]);lin(c,w,h,[[0,k[0]],[.55,k[1]],[1,k[2]]]);for(let i=0;i<34;i++){const x=r()*w,y=h*(.25+r()*.5),R=m*(.03+r()*.07),col=["255,214,150","255,170,140","190,220,255"][i%3],g=c.createRadialGradient(x,y,0,x,y,R);g.addColorStop(0,"rgba("+col+",.5)");g.addColorStop(1,"rgba("+col+",0)");c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}c.strokeStyle="rgba(255,255,255,.3)";c.lineWidth=2.5;for(let i=0;i<110;i++){const x=r()*w,y=r()*h*.8,l=40+r()*80;c.beginPath();c.moveTo(x,y);c.lineTo(x-l*.12,y+l);c.stroke()}for(let i=0;i<36;i++){const R=6+r()*12;c.fillStyle="rgba(255,255,255,.25)";c.beginPath();c.ellipse(r()*w,r()*h*.8,R*.7,R*1.3,0,0,7);c.fill()}c.fillStyle="#2a1d16";c.fillRect(0,0,w,56);c.fillRect(0,0,46,h);c.fillRect(w-46,0,46,h);c.fillRect(w*.5-18,0,36,h*.8);c.fillRect(0,h*.4-16,w,32);c.fillRect(0,h*.8,w,h*.2);const lg=c.createRadialGradient(w*.25,h*.84,0,w*.25,h*.84,w*.95),lc=gc||"#ffc878";lg.addColorStop(0,rgb(lc,.75));lg.addColorStop(1,rgb(lc,0));c.fillStyle=lg;c.fillRect(0,0,w,h);c.fillStyle="#f2d9a8";c.beginPath();c.moveTo(w*.19,h*.8);c.lineTo(w*.31,h*.8);c.lineTo(w*.28,h*.73);c.lineTo(w*.22,h*.73);c.fill();c.fillStyle="#5a4332";c.fillRect(w*.25-4,h*.8,8,h*.04);c.fillStyle="#e8d6c0";c.fillRect(w*.62,h*.86,w*.1,w*.09);c.fillStyle="rgba(255,255,255,.45)";for(let i=0;i<3;i++){c.beginPath();c.arc(w*.67+Math.sin(i*2)*8,h*.84-i*40,14,0,7);c.fill()}}
  else if(type==="garden"){const k=pal(["#bfe3f5","#f6f1d6","#a9d49a"]);lin(c,w,h,[[0,k[0]],[.5,k[1]],[1,k[2]]]);glow(c,w*.85,h*.08,w*.9,rgb(gc||"#fff3c0",.9));for(let j=0;j<5;j++){c.fillStyle="rgba(255,255,255,.1)";c.beginPath();c.moveTo(w*.85,h*.08);c.lineTo(w*(.7-j*.22),h);c.lineTo(w*(.5-j*.22),h);c.fill()}hills(c,w,h,r,1,h*.5,25,["#6fae6a"]);hills(c,w,h,r,1,h*.62,30,["#4f9a5a"]);for(let i=0;i<150;i++){const y=h*(.62+i/150*.38),t=i/150,x=r()*w,s=6+t*30;c.strokeStyle="#3f8a4d";c.lineWidth=2+t*3;c.beginPath();c.moveTo(x,y);c.lineTo(x,y+s*3);c.stroke();c.fillStyle=["#ff9fb5","#ffd166","#ffffff","#c9a7ff","#ff7f6e"][i%5];for(let p=0;p<6;p++){c.beginPath();c.arc(x+Math.cos(p*1.047)*s*.7,y+Math.sin(p*1.047)*s*.7,s*.55,0,7);c.fill()}c.fillStyle="#f6a623";c.beginPath();c.arc(x,y,s*.45,0,7);c.fill()}}
  else if(type==="dawnsea"){const k=pal(["#7d86c4","#f4b5b0","#ffe0bd"]);lin(c,w,h,[[0,k[0]],[.35,k[1]],[.55,k[2]],[.551,"#7fa5c4"],[1,"#2f5c80"]]);glow(c,w*.5,h*.55,w*.9,rgb(gc||"#ffe9b8",.8));c.fillStyle="#fff1cf";c.beginPath();c.arc(w*.5,h*.55,m*.09,Math.PI,0);c.fill();c.fillStyle="rgba(255,235,190,.35)";for(let i=0;i<24;i++){const ww=m*(.16-i*.005);c.fillRect(w*.5-ww/2,h*.56+i*28,ww,6)}c.strokeStyle="rgba(255,255,255,.3)";c.lineWidth=3;for(let i=0;i<34;i++){const y=h*.57+i*(h*.43/34),x=r()*w;c.beginPath();c.moveTo(x-w*.14,y);c.quadraticCurveTo(x,y-8,x+w*.14,y);c.stroke()}c.fillStyle="rgba(255,255,255,.35)";for(let i=0;i<6;i++){c.beginPath();c.ellipse(r()*w,h*(.12+r()*.28),w*(.12+r()*.1),14,0,0,7);c.fill()}}
  else if(type==="pinkridge"){const k=pal(["#8e6fb0","#f29bb4","#ffd2b0"]);lin(c,w,h,[[0,k[0]],[.5,k[1]],[1,k[2]]]);glow(c,w*.5,h*.62,w*.9,rgb(gc||"#fff0d0",.75));c.fillStyle="#fff0d8";c.beginPath();c.arc(w*.5,h*.62,m*.09,0,7);c.fill();const rc=["rgba(214,140,170,.75)","rgba(176,110,160,.85)","rgba(130,86,140,.92)","#5a4575"];for(let q=0;q<4;q++){c.fillStyle=rc[q];c.beginPath();c.moveTo(0,h);c.lineTo(0,h*(.6+q*.07));for(let x=0;x<=w+50;x+=50)c.lineTo(x,h*(.6+q*.07)-(r()*.6+.4)*h*(.1-q*.012)*Math.abs(Math.sin(x/w*(2.2+q*.5)+q)));c.lineTo(w,h);c.fill()}c.strokeStyle="rgba(70,50,80,.6)";c.lineWidth=3;for(let i=0;i<4;i++){const x=w*(.2+r()*.6),y=h*(.2+r()*.2);c.beginPath();c.moveTo(x-14,y-5);c.quadraticCurveTo(x-7,y-12,x,y);c.quadraticCurveTo(x+7,y-12,x+14,y-5);c.stroke()}}
  else if(type==="fogpath"){const k=pal(["#c8d6cf","#a9c0b4","#6f8f80"]);lin(c,w,h,[[0,k[0]],[.6,k[1]],[1,k[2]]]);const vx=w*.5,vy=h*.55;c.fillStyle="rgba(240,236,220,.55)";c.beginPath();c.moveTo(vx-8,vy);c.lineTo(vx+8,vy);c.lineTo(w*.85,h);c.lineTo(w*.15,h);c.fill();for(let sd=-1;sd<=1;sd+=2)for(let i=0;i<14;i++){const t=i/13,x=vx+sd*(w*.05+t*t*w*.58)+(r()-.5)*16,wd=8+t*t*70,top=Math.max(-10,vy-(.2+t*.8)*h*.55),bot=vy+t*t*(h-vy)+30;c.fillStyle="rgba(46,66,56,"+(.15+t*.7)+")";c.fillRect(x-wd/2,top,wd,bot-top)}const fg=c.createLinearGradient(0,h*.3,0,h*.8);fg.addColorStop(0,"rgba(235,240,235,0)");fg.addColorStop(.5,"rgba(235,240,235,.6)");fg.addColorStop(1,"rgba(235,240,235,0)");c.fillStyle=fg;c.fillRect(0,h*.3,w,h*.5);glow(c,vx,vy-40,w*.7,rgb(gc||"#ffffff",.5))}
  else if(type==="moonquiet"){const k=pal(["#0f1d3d","#2b4272","#4a5f93"]);lin(c,w,h,[[0,k[0]],[.6,k[1]],[1,k[2]]]);for(let i=0;i<80;i++){c.fillStyle="rgba(255,255,255,"+(.2+r()*.6)+")";c.beginPath();c.arc(r()*w,r()*h*.5,r()*2+.4,0,7);c.fill()}glow(c,w*.62,h*.2,w*.8,rgb(gc||"#fff4cc",.5));c.fillStyle="#fff6d6";c.beginPath();c.arc(w*.62,h*.2,m*.11,0,7);c.fill();c.fillStyle="rgba(255,255,255,.12)";for(let i=0;i<4;i++){c.beginPath();c.ellipse(w*(.2+r()*.6),h*(.12+r()*.25),w*.2,18,0,0,7);c.fill()}hills(c,w,h,r,2,h*.74,40,["#1b2a4e","#0f1a35"]);c.fillStyle="#0b1429";c.fillRect(w*.28,h*.8,w*.16,h*.07);c.beginPath();c.moveTo(w*.26,h*.8);c.lineTo(w*.36,h*.75);c.lineTo(w*.46,h*.8);c.fill();c.fillStyle="#ffcf7a";c.fillRect(w*.33,h*.82,w*.04,h*.025);c.fillStyle="#0b1429";c.fillRect(w*.7,h*.78,10,h*.1);c.beginPath();c.arc(w*.7+5,h*.76,m*.07,0,7);c.fill()}
  else if(type==="booktea"){const k=pal(["#e9cfa8","#d3a678","#7b5238"]);lin(c,w,h,[[0,k[0]],[.6,k[1]],[1,k[2]]]);for(let i=0;i<30;i++){const x=r()*w,y=r()*h*.5,R=m*(.02+r()*.05),g=c.createRadialGradient(x,y,0,x,y,R);g.addColorStop(0,"rgba(255,225,160,.5)");g.addColorStop(1,"rgba(255,225,160,0)");c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}glow(c,w*.2,h*.1,w*.9,rgb(gc||"#fff1c8",.55));c.fillStyle="#6b4630";c.fillRect(0,h*.6,w,h*.4);c.fillStyle="rgba(0,0,0,.12)";c.fillRect(0,h*.6,w,12);c.fillStyle="#f4ebe0";c.fillRect(w*.64,h*.62,w*.16,h*.075);c.beginPath();c.ellipse(w*.72,h*.62,w*.08,h*.012,0,0,7);c.fill();c.fillStyle="#b9783f";c.beginPath();c.ellipse(w*.72,h*.62,w*.068,h*.009,0,0,7);c.fill();c.strokeStyle="rgba(255,255,255,.5)";c.lineWidth=5;for(let i=0;i<3;i++){c.beginPath();c.moveTo(w*(.69+i*.03),h*.6);c.quadraticCurveTo(w*(.66+i*.03),h*.57,w*(.69+i*.03),h*.54);c.stroke()}c.fillStyle="#fbf3e2";c.beginPath();c.moveTo(w*.14,h*.72);c.lineTo(w*.5,h*.75);c.lineTo(w*.5,h*.87);c.lineTo(w*.12,h*.84);c.fill();c.beginPath();c.moveTo(w*.5,h*.75);c.lineTo(w*.86,h*.72);c.lineTo(w*.88,h*.84);c.lineTo(w*.5,h*.87);c.fill();c.strokeStyle="rgba(120,90,60,.35)";c.lineWidth=2;for(let i=0;i<6;i++){const yy=h*(.76+i*.014);c.beginPath();c.moveTo(w*.18,yy-4);c.lineTo(w*.46,yy+5);c.moveTo(w*.54,yy+5);c.lineTo(w*.82,yy-4);c.stroke()}c.fillStyle="#4f7a45";for(let i=0;i<4;i++){c.beginPath();c.ellipse(w*(.06+i*.025),h*(.55-i*.02),22,60,-.6+i*.4,0,7);c.fill()}}
  else if(type==="countrypath"){const k=pal(["#9fd0ee","#ffe3c4","#9ccb7d"]);lin(c,w,h,[[0,k[0]],[.5,k[1]],[1,k[2]]]);glow(c,w*.3,h*.18,w*.8,rgb(gc||"#fff0c8",.7));hills(c,w,h,r,2,h*.52,30,["#a9cf90","#82b86f"]);c.fillStyle="#7aae62";c.fillRect(0,h*.6,w,h*.4);for(let i=0;i<130;i++){const t=i/130,y=h*(.6+t*.4),x=i%2?r()*w*.4:w-r()*w*.4,s=3+t*14;c.fillStyle=["#ffffff","#ffd166","#ff9fb5","#c9a7ff"][i%4];for(let p=0;p<5;p++){c.beginPath();c.arc(x+Math.cos(p*1.26)*s,y+Math.sin(p*1.26)*s,s*.7,0,7);c.fill()}c.fillStyle="#f6a623";c.beginPath();c.arc(x,y,s*.5,0,7);c.fill()}c.fillStyle="#e3c89a";c.beginPath();c.moveTo(w*.48,h*.6);c.quadraticCurveTo(w*.6,h*.75,w*.4,h*.85);c.quadraticCurveTo(w*.3,h*.93,w*.2,h);c.lineTo(w*.8,h);c.quadraticCurveTo(w*.6,h*.9,w*.62,h*.82);c.quadraticCurveTo(w*.66,h*.72,w*.52,h*.6);c.fill();c.fillStyle="#5f9a52";for(let i=0;i<6;i++){c.beginPath();c.arc(w*(.1+i*.15),h*.58,18+r()*20,0,7);c.fill()}}
  else if(type==="clearsky"){const k=pal(["#6fb3ec","#bfe2f7","#fff1dc"]);lin(c,w,h,[[0,k[0]],[.55,k[1]],[.72,k[2]],[.72,"#8fb08a"],[1,"#4f7a56"]]);for(let q=0;q<6;q++){const cx=r()*w,cy=h*(.1+q*.1),sc=m*(.08+r()*.08);c.fillStyle="rgba(255,255,255,"+(.5+r()*.4)+")";for(let j=0;j<6;j++){c.beginPath();c.arc(cx+(j-2.5)*sc*.7,cy+Math.sin(j*1.7)*sc*.25,sc*(.5+r()*.4),0,7);c.fill()}}glow(c,w*.5,h*.72,w*.9,rgb(gc||"#fff0c8",.6));for(let j=0;j<4;j++){c.fillStyle="rgba(255,255,255,.09)";c.beginPath();c.moveTo(w*(.2+j*.2),0);c.lineTo(w*(.1+j*.25),h*.72);c.lineTo(w*(.25+j*.25),h*.72);c.fill()}const pg=c.createLinearGradient(0,h*.8,0,h*.95);pg.addColorStop(0,k[1]);pg.addColorStop(1,k[0]);c.fillStyle=pg;c.beginPath();c.ellipse(w*.5,h*.87,w*.4,h*.05,0,0,7);c.fill();c.strokeStyle="rgba(255,255,255,.5)";c.lineWidth=3;for(let i=0;i<3;i++){c.beginPath();c.ellipse(w*.5,h*.87,w*(.1+i*.08),h*(.015+i*.01),0,0,7);c.stroke()}c.strokeStyle="#3f6a48";c.lineWidth=4;for(let i=0;i<80;i++){const x=r()*w,y=h*(.9+r()*.1);c.beginPath();c.moveTo(x,y);c.lineTo(x+(r()-.5)*16,y-20-r()*30);c.stroke()}}
  else if(type==="springtree"){const k=pal(["#cfe8f5","#f9eef0","#bfe0a6"]);lin(c,w,h,[[0,k[0]],[.55,k[1]],[1,k[2]]]);glow(c,w*.2,h*.05,w*.9,rgb(gc||"#fff6d0",.8));for(let j=0;j<5;j++){c.fillStyle="rgba(255,255,255,.1)";c.beginPath();c.moveTo(w*.2,0);c.lineTo(w*(.3+j*.2),h);c.lineTo(w*(.45+j*.2),h);c.fill()}c.fillStyle="#6b4a3a";c.beginPath();c.moveTo(w*.44,h);c.quadraticCurveTo(w*.48,h*.65,w*.46,h*.4);c.lineTo(w*.54,h*.4);c.quadraticCurveTo(w*.52,h*.65,w*.56,h);c.fill();c.strokeStyle="#6b4a3a";c.lineWidth=14;c.beginPath();c.moveTo(w*.5,h*.5);c.quadraticCurveTo(w*.3,h*.42,w*.2,h*.3);c.moveTo(w*.5,h*.46);c.quadraticCurveTo(w*.7,h*.38,w*.82,h*.26);c.stroke();c.globalAlpha=.75;for(let i=0;i<150;i++){const a=r()*6.283,d=Math.sqrt(r())*w*.42,x=w*.5+Math.cos(a)*d,y=h*.3+Math.sin(a)*d*.75,sz=14+r()*22;c.fillStyle=["#ffd6e0","#ffc2d4","#ffffff","#cfe8b0","#f9a8c0"][i%5];c.beginPath();c.arc(x,y,sz,0,7);c.fill()}c.globalAlpha=1;hills(c,w,h,r,1,h*.86,20,["#8fc27a"]);for(let i=0;i<60;i++){c.fillStyle="rgba(255,200,215,"+(.5+r()*.4)+")";c.beginPath();c.ellipse(r()*w,h*.35+r()*h*.6,8+r()*5,4+r()*3,r()*3,0,7);c.fill()}}
  else if(type==="winterwindow"){const k=pal(["#b9cfe6","#dfe9f4","#f2f6fb"]);lin(c,w,h,[[0,k[0]],[.5,k[1]],[1,k[2]]]);hills(c,w,h,r,2,h*.5,20,["#e8eff7","#cfdcec"]);for(let i=0;i<140;i++){c.fillStyle="rgba(255,255,255,"+(.5+r()*.5)+")";c.beginPath();c.arc(r()*w,r()*h*.62,r()*5+1.5,0,7);c.fill()}c.fillStyle="#3a2a22";c.fillRect(0,0,w,50);c.fillRect(0,0,44,h);c.fillRect(w-44,0,44,h);c.fillRect(w*.5-16,0,32,h*.62);c.fillRect(0,h*.62,w,h*.38);[[44,50],[w-44,50]].forEach(([x,y])=>{const g=c.createRadialGradient(x,y,0,x,y,w*.35);g.addColorStop(0,"rgba(255,255,255,.7)");g.addColorStop(1,"rgba(255,255,255,0)");c.fillStyle=g;c.fillRect(44,50,w-88,h*.56)});c.fillStyle="#b5543f";c.beginPath();c.moveTo(0,h*.72);for(let x=0;x<=w+40;x+=40)c.lineTo(x,h*.72+Math.sin(x/w*5)*28+Math.sin(x/w*11)*8);c.lineTo(w,h);c.lineTo(0,h);c.fill();c.strokeStyle="rgba(255,230,200,.35)";c.lineWidth=8;for(let i=0;i<7;i++){const y=h*(.77+i*.03);c.beginPath();c.moveTo(0,y);for(let x=0;x<=w;x+=40)c.lineTo(x,y+Math.sin(x/w*5+i*.4)*28);c.stroke()}glow(c,w*.8,h*.68,w*.7,rgb(gc||"#ffc878",.45));c.fillStyle="#f1e3d0";c.fillRect(w*.72,h*.64,w*.12,w*.1);c.fillStyle="rgba(255,255,255,.55)";for(let i=0;i<3;i++){c.beginPath();c.arc(w*.78+Math.sin(i*2)*8,h*.62-i*36,13,0,7);c.fill()}}
  else if(type==="dawnlake"){const k=pal(["#8e9fd0","#e3b8c8","#ffe0c4"]);lin(c,w,h,[[0,k[0]],[.4,k[1]],[.5,k[2]],[.5,k[2]],[.56,k[1]],[1,k[0]]]);const pts=[];for(let x=0;x<=w+60;x+=60)pts.push([x,h*.5-(r()*.5+.3)*h*.12*(1+Math.sin(x/w*3))]);c.fillStyle="rgba(95,105,150,.8)";c.beginPath();c.moveTo(0,h*.5);pts.forEach(q=>c.lineTo(q[0],q[1]));c.lineTo(w,h*.5);c.fill();c.fillStyle="rgba(95,105,150,.35)";c.beginPath();c.moveTo(0,h*.5);pts.forEach(q=>c.lineTo(q[0],h-q[1]));c.lineTo(w,h*.5);c.fill();glow(c,w*.7,h*.48,w*.8,rgb(gc||"#ffe6c8",.55));c.fillStyle="rgba(255,235,205,.85)";c.beginPath();c.arc(w*.7,h*.47,m*.04,Math.PI,0);c.fill();c.fillStyle="rgba(255,255,255,.12)";for(let i=0;i<5;i++){c.beginPath();c.ellipse(r()*w,h*(.44+i*.03),w*.35,22,0,0,7);c.fill()}c.strokeStyle="rgba(255,255,255,.18)";c.lineWidth=2;for(let i=0;i<14;i++){const y=h*(.55+i*.03),x=r()*w;c.beginPath();c.moveTo(x-w*.2,y);c.lineTo(x+w*.2,y);c.stroke()}}
  else{lin(c,w,h,[[0,"#e9eef2"],[1,"#c4d2dc"]]);glow(c,w*.5,h*.3,w*.9,"rgba(255,255,255,.9)");hills(c,w,h,r,5,h*.45,45,["rgba(160,180,198,.55)","rgba(135,160,182,.65)","rgba(110,138,162,.75)","rgba(85,115,140,.85)","rgba(60,90,115,.95)"])}
}
const rgb=(h,a)=>{const n=parseInt(h.slice(1),16);return "rgba("+(n>>16)+","+(n>>8&255)+","+(n&255)+","+a+")"};
const HX=/^#[0-9a-f]{6}$/i,hx=(s,d)=>HX.test(s)?s:d,cl=(v,a,b,d)=>{v=+v;return Math.min(b,Math.max(a,isFinite(v)?v:d))};
function artLayer(c,w,h,L,r){
  const col=hx(L.color,"#556677"),y=h*cl(L.y,.3,.97,.7),t=L.type;c.fillStyle=col;
  if(t==="mountains"){c.beginPath();c.moveTo(0,h);c.lineTo(0,y);for(let x=0;x<=w+70;x+=70)c.lineTo(x,y-r()*h*.14);c.lineTo(w,h);c.fill()}
  else if(t==="trees"){c.fillRect(0,y,w,h-y);for(let i=0;i<14;i++){const x=r()*w,tt=h*(.07+r()*.09),ww=w*.07;c.beginPath();c.moveTo(x,y-tt);c.lineTo(x-ww,y+8);c.lineTo(x+ww,y+8);c.fill()}}
  else if(t==="waves"){c.fillRect(0,y,w,h-y);c.strokeStyle="rgba(255,255,255,.28)";c.lineWidth=3;for(let i=0;i<30;i++){const yy=y+r()*(h-y),x=r()*w;c.beginPath();c.moveTo(x-w*.12,yy);c.quadraticCurveTo(x,yy-10,x+w*.12,yy);c.stroke()}}
  else if(t==="city"){c.fillRect(0,y,w,h-y);for(let x=0;x<w;x+=60+r()*50){const bh=h*(.04+r()*.14),bw=50+r()*50;c.fillRect(x,y-bh,bw,bh+2);c.fillStyle="rgba(255,225,150,.75)";for(let k=0;k<bh/34;k++)if(r()>.45)c.fillRect(x+8+r()*(bw-24),y-bh+10+k*30,8,12);c.fillStyle=col}}
  else{c.beginPath();c.moveTo(0,h);const ph=r()*6,fr=1.2+r()*1.6;for(let x=0;x<=w;x+=10)c.lineTo(x,y+Math.sin(x/w*fr*Math.PI+ph)*h*.02);c.lineTo(w,h);c.fill();
    if(t==="grass"){c.strokeStyle=col;c.lineWidth=3;for(let i=0;i<220;i++){const x=r()*w,yy=y+r()*(h-y);c.beginPath();c.moveTo(x,yy);c.lineTo(x+(r()-.5)*14,yy-14-r()*26);c.stroke()}}
    if(t==="flowers"){for(let i=0;i<70;i++){const x=r()*w,yy=y+r()*(h-y),sz=4+(yy-y)/(h-y)*14;c.fillStyle=["#ffd1dc","#fff4a8","#ffffff","#e8c8ff"][i%4];c.beginPath();c.arc(x,yy,sz,0,7);c.fill()}}}
}
function artScene(c,w,h,a,seed){
  const r=rngf(seed*131+7),m=Math.min(w,h);a=a||{};
  const sk=(Array.isArray(a.sky)?a.sky:[]).filter(x=>HX.test(x)).slice(0,4);while(sk.length<2)sk.push(sk.length?"#f5d6c0":"#8aa4d6");
  lin(c,w,h,sk.map((col,i)=>[i/(sk.length-1),col]));
  const s=a.sun||{};
  if(s.kind==="sun"||s.kind==="moon"){const x=w*cl(s.x,.05,.95,.5),y=h*cl(s.y,.05,.9,.35),col=hx(s.color,"#fff3d0"),g=c.createRadialGradient(x,y,0,x,y,w*.8);g.addColorStop(0,rgb(col,.6));g.addColorStop(1,rgb(col,0));c.fillStyle=g;c.fillRect(0,0,w,h);c.fillStyle=col;c.beginPath();c.arc(x,y,m*(s.kind==="moon"?.07:.1),0,7);c.fill()}
  if(HX.test(a.glow)){const g=c.createRadialGradient(w*.5,h*.65,0,w*.5,h*.65,w);g.addColorStop(0,rgb(a.glow,.5));g.addColorStop(1,rgb(a.glow,0));c.fillStyle=g;c.fillRect(0,0,w,h)}
  const P=a.particles||{},pk=P.kind,pc=hx(P.color,"#ffffff"),n=Math.round(cl(P.amount,0,1,.5)*120);
  if(pk==="stars")for(let i=0;i<n*1.4;i++){c.fillStyle="rgba(255,255,255,"+(.3+r()*.7)+")";c.beginPath();c.arc(r()*w,r()*h*.7,r()*2.4+.5,0,7);c.fill()}
  (Array.isArray(a.layers)?a.layers:[]).slice(0,4).forEach(L=>artLayer(c,w,h,L||{},r));
  if(pk&&pk!=="stars"&&pk!=="none")for(let i=0;i<n;i++){const x=r()*w,y=r()*h,t=r();
    if(pk==="snow"){c.fillStyle=rgb(pc,.5+t*.5);c.beginPath();c.arc(x,y,1.5+t*5,0,7);c.fill()}
    else if(pk==="rain"){c.strokeStyle=rgb(pc,.35);c.lineWidth=2.5;c.beginPath();c.moveTo(x,y);c.lineTo(x-8,y+60+t*50);c.stroke()}
    else if(pk==="petals"||pk==="leaves"){c.fillStyle=rgb(pc,.6+t*.4);c.save();c.translate(x,y);c.rotate(r()*6);c.beginPath();c.ellipse(0,0,8+t*12,4+t*6,0,0,7);c.fill();c.restore()}
    else if(pk==="fireflies"||pk==="bokeh"){const bk=pk==="bokeh",R=(bk?m*(.02+t*.07):6+t*10)*(bk?1:3),g=c.createRadialGradient(x,y,0,x,y,R);g.addColorStop(0,rgb(pc,bk?.35:.95));g.addColorStop(1,rgb(pc,0));c.fillStyle=g;c.beginPath();c.arc(x,y,R,0,7);c.fill()}
    else if(pk==="bubbles"){c.strokeStyle=rgb(pc,.6);c.lineWidth=2;c.beginPath();c.arc(x,y,5+t*26,0,7);c.stroke()}}
  const fg=cl(a.fog,0,1,0);if(fg>0){const fc=sk[sk.length-1],g=c.createLinearGradient(0,h*.35,0,h*.95);g.addColorStop(0,rgb(fc,0));g.addColorStop(.6,rgb(fc,fg*.55));g.addColorStop(1,rgb(fc,0));c.fillStyle=g;c.fillRect(0,h*.35,w,h*.6)}
}
function cover(c,img,w,h){const s=Math.max(w/img.width,h/img.height),dw=img.width*s,dh=img.height*s;c.drawImage(img,(w-dw)/2,(h-dh)/2,dw,dh)}
function wrap(c,text,maxW){const out=[];text.split("\n").forEach(par=>{let line="";for(const ch of par){if(c.measureText(line+ch).width>maxW&&line){out.push(line);line=ch.trim()?ch:""}else line+=ch}out.push(line)});return out}
function draw(i){
  const cv=$("cv"+i),c=cv.getContext("2d"),cut=cuts[i],W=1080,H=1920;
  cv.width=W;cv.height=H;
  if(cut.img)cover(c,cut.img,W,H);else if(cut.scene==="ai"&&cut.art)artScene(c,W,H,cut.art,seedBase+i*3);else scene(c,W,H,cut.scene==="ai"?"sunset":cut.scene,seedBase+i*3,cut.art);
  c.fillStyle="rgba(0,0,0,.2)";c.fillRect(0,0,W,H);const vg=c.createRadialGradient(W/2,H/2,H*.25,W/2,H/2,H*.7);vg.addColorStop(0,"rgba(0,0,0,0)");vg.addColorStop(1,"rgba(0,0,0,.38)");c.fillStyle=vg;c.fillRect(0,0,W,H);
  const txt=cut.text.trim();
  if(txt){c.textAlign="center";c.textBaseline="middle";let fs=84,lines;
    for(;fs>=44;fs-=2){c.font=fontStr(cut,fs);lines=wrap(c,txt,W*.76);if(lines.length*fs*fsc(cut)*1.5<H*.42)break}
    const lh=fs*fsc(cut)*1.5,y0=H*.46-(lines.length-1)*lh/2;
    c.save();c.shadowColor="rgba(0,0,0,.55)";c.shadowBlur=24;c.fillStyle="#fff";
    lines.forEach((l,k)=>c.fillText(l,W/2,y0+k*lh));
    c.fillRect(W/2-40,y0-lh*.9-30,80,3);c.restore();
  }
}
const tm={};const sched=i=>{clearTimeout(tm[i]);tm[i]=setTimeout(async()=>{draw(i);await lf(cuts[i]);draw(i)},150)};
function build(){
  const box=$("cards");box.innerHTML="";
  cuts.forEach((cut,i)=>{
    const d=document.createElement("div");d.className="item";
    d.innerHTML='<canvas id="cv'+i+'" width="1080" height="1920"></canvas><textarea rows="3"></textarea><div class="row"><select class="sc"></select><select class="fs"></select></div><div class="row"><label class="btn">📷 내 사진<input type="file" accept="image/*"></label><button>💾 저장</button><button class="sh">📤 공유</button></div>';
    const ta=d.querySelector("textarea"),sel=d.querySelector(".sc"),fsel=d.querySelector(".fs"),fi=d.querySelector("input"),sv=d.querySelector("button");
    ta.value=cut.text;ta.oninput=()=>{cut.text=ta.value;sched(i)};
    SC.forEach(([k,n])=>{const o=document.createElement("option");o.value=k;o.textContent=n;sel.appendChild(o)});
    sel.value=cut.scene;sel.onchange=()=>{cut.scene=sel.value;cut.img=null;draw(i)};
    FONTS.forEach(f=>{const o=document.createElement("option");o.value=f.id;o.textContent=f.label;fsel.appendChild(o)});fsel.value=cut.font;fsel.onchange=async()=>{cut.font=fsel.value;draw(i);await lf(cut);draw(i)};
    fi.onchange=()=>{const f=fi.files[0];if(!f)return;const im=new Image();im.onload=()=>{cut.img=im;draw(i)};im.src=URL.createObjectURL(f)};
    sv.onclick=()=>save(i);d.querySelector(".sh").onclick=()=>shareFiles([i]);
    box.appendChild(d);
  });
}
async function refresh(){build();cuts.forEach((_,i)=>draw(i));await Promise.all(cuts.map(lf));cuts.forEach((_,i)=>draw(i))}
function save(i){
  return new Promise(res=>{
    const m=$("msg");
    if(!dl){$("cv"+i).toBlob(b=>{const u=URL.createObjectURL(b),a=document.createElement("a");a.href=u;a.download="오늘나에게_"+(i+1)+"of4.png";document.body.appendChild(a);a.click();a.remove();setTimeout(()=>URL.revokeObjectURL(u),4000);m.textContent=(i+1)+"번째 이미지 저장을 시도했어요. 저장이 안 되면 🖼 이미지 열어 보내기에서 길게 눌러 저장해 주세요.";res(true)},"image/png");return}
    $("cv"+i).toBlob(async b=>{try{await dl.save({filename:"위로_"+(i+1)+"of4_9x16.png",data:b});m.textContent=(i+1)+"번째 이미지를 저장했어요 🌿";res(true)}catch(e){m.textContent=e&&e.code==="declined"?"저장을 취소했어요.":"저장하지 못했어요. 이미지를 길게 눌러 저장해 보세요.";res(false)}},"image/png");
  });
}
const SHARE_TXT=()=>cuts.map(c=>c.text.replace(/\n/g," ")).join("\n\n")+"\n\n— 오늘, 나에게 · Dear Me, Today";
const toBlob=i=>new Promise(r=>$("cv"+i).toBlob(r,"image/png"));
async function shareFiles(idx){
  const m=$("msg");
  try{
    const bl=await Promise.all(idx.map(toBlob)),files=bl.map((b,k)=>new File([b],"오늘나에게_"+(idx[k]+1)+"of4.png",{type:"image/png"}));
    if(navigator.canShare&&navigator.canShare({files})){
      try{await navigator.share({files,text:idx.length>1?SHARE_TXT():cuts[idx[0]].text.replace(/\n/g," ")+"\n— 오늘, 나에게"});m.textContent="공유 창에서 카카오톡을 골라 보내 주세요 💌";return}
      catch(e){if(e&&e.name==="AbortError")return}
    }
  }catch(e){}
  m.textContent="공유 창이 막혀 있어서 이미지를 따로 열었어요. 화면의 안내대로 이미지를 길게 눌러 카카오톡으로 보내 주세요.";await openViewer(idx);
}
async function copyText(){
  const t=SHARE_TXT(),m=$("msg");
  try{await navigator.clipboard.writeText(t);m.textContent="글귀를 복사했어요. 카카오톡 대화창에 붙여넣어 보내세요 📋";return}catch(e){}
  let ok=false;try{const ta=document.createElement("textarea");ta.value=t;ta.style.cssText="position:fixed;opacity:0";document.body.appendChild(ta);ta.select();ok=document.execCommand("copy");ta.remove()}catch(e){}
  m.textContent=ok?"글귀를 복사했어요. 카카오톡 대화창에 붙여넣어 보내세요 📋":"복사하지 못했어요. 카드의 글을 길게 눌러 복사해 주세요.";
}
let vurls=[];
async function openViewer(idx){const list=$("vlist");list.innerHTML="";vurls.forEach(u=>URL.revokeObjectURL(u));vurls=[];for(const i of idx){const b=await toBlob(i),u=URL.createObjectURL(b);vurls.push(u);const im=new Image();im.src=u;im.alt=(i+1)+"번째 이미지";list.appendChild(im);const sb=document.createElement("button");sb.className="vb";sb.textContent="💾 이 이미지 저장";sb.onclick=()=>save(i);list.appendChild(sb)}$("viewer").hidden=false;$("viewer").scrollTop=0}
$("vclose").onclick=()=>{$("viewer").hidden=true};$("viewAll").onclick=()=>openViewer([0,1,2,3]);
$("shareAll").onclick=()=>shareFiles([0,1,2,3]);$("copyAll").onclick=copyText;
async function saveAll(){for(let i=0;i<4;i++){if(!(await save(i)))break}}
const ARTSCHEMA='{"sky":["#위쪽색","#중간색","#아래쪽색"],"sun":{"kind":"sun|moon|none","x":0.5,"y":0.35,"color":"#색"},"glow":"#색","layers":[{"type":"hills|mountains|trees|waves|flowers|grass|city","color":"#색","y":0.7}],"particles":{"kind":"stars|snow|petals|fireflies|rain|leaves|bokeh|bubbles|none","color":"#색","amount":0.5},"fog":0.3}';
const ARTRULES='art는 풍경 설계도예요. 하늘 색 2~3개(위에서 아래), 해나 달의 위치(x,y는 0~1)와 색, 뒤에서 앞으로 겹치는 지형 층 2~4개(y는 지평선 높이 0.45~0.95, 뒤쪽일수록 밝고 흐린 색), 떠다니는 입자, 안개(0~1)로 구성해요. 모든 색은 #rrggbb 6자리로 쓰세요. 글씨가 흰색으로 얹히니 너무 밝은 색은 피하세요. 풍경마다 색감, 시간대(새벽, 낮, 노을, 밤), 구성이 확연히 달라야 해요.';
let cands=[],sel=[];
let shown=[];
const ANGLES=["자연과 계절에 빗댄 말","오늘 하루의 작은 장면","나 자신에게 건네는 말","내일과 시간에 대한 말","몸과 마음의 쉼에 대한 말","곁에 있는 사람과 나누는 온기","작은 용기와 한 걸음","잘 해 온 나에 대한 인정","비 온 뒤 맑음처럼 지나가는 마음","밤과 새벽, 별과 달"];
function remember(a){a.forEach(x=>{const t=x.text.replace(/\n/g," ");if(!shown.includes(t))shown.push(t)});if(shown.length>150)shown=shown.slice(-150)}
function varNote(){const a=ANGLES.slice().sort(()=>Math.random()-.5).slice(0,4).join(", "),ex=shown.slice(-36).map(t=>"\u201c"+t+"\u201d").join(" ");return " 이번에는 특히 이런 결을 섞어 주세요: "+a+"."+(ex?" 이미 보여 드린 문구와 같거나 비슷한 말은 절대 쓰지 마세요: "+ex:"")}
function fbPool(f){const L=$("lang").value,i0=FB.findIndex(x=>x.k.test(f)),ord=[FB[i0],...FB.filter((_,i)=>i!==i0)],all=[];ord.forEach(st=>st.t.forEach((t,i)=>all.push({text:L==="en"?st.e[i]:L==="both"?t+"\n"+st.e[i]:t,scene:st.s[i],art:null})));
  const seen=x=>shown.includes(x.text.replace(/\n/g," "));let fresh=all.filter(x=>!seen(x));if(fresh.length<12){shown=shown.filter(t=>!all.some(x=>x.text.replace(/\n/g," ")===t));fresh=all}
  if(shown.length)fresh=fresh.slice().sort(()=>Math.random()-.5);const out=fresh.slice(0,12);remember(out);return out}
function applySel(){if(sel.length!==4)return;sel.forEach((ci,i)=>{const x=cands[ci],c=cuts[i];c.text=x.text;c.art=x.art;c.scene=$("theme").value||(TH.includes(x.scene)?x.scene:(x.art?"ai":x.scene));c.img=null});refresh()}
function renderPool(){
  const box=$("poolBox"),g=$("pool"),m=$("msg");box.hidden=!cands.length;g.innerHTML="";$("pcount").textContent="("+sel.length+"/4)";
  cands.forEach((x,ci)=>{const b=document.createElement("button"),k=sel.indexOf(ci);b.className="pc"+(k>=0?" on":"");b.innerHTML=(k>=0?"<i>"+(k+1)+"</i>":"")+"<span></span>";b.querySelector("span").textContent=x.text.replace(/\n/g," ");
    b.onclick=()=>{const j=sel.indexOf(ci);if(j>=0)sel.splice(j,1);else if(sel.length<4)sel.push(ci);else{m.textContent="4개까지 고를 수 있어요. 하나를 먼저 해제해 주세요.";return}renderPool();if(sel.length===4){m.textContent="";applySel()}else m.textContent="4개를 고르면 아래 4장이 바뀌어요."};g.appendChild(b)});
}
async function generate(){
  const f=$("feel").value.trim()||"오늘 하루 그냥 위로가 필요해요";
  const b=$("gen"),m=$("msg");b.disabled=true;b.textContent="글귀 12개와 풍경을 만드는 중…";seedBase=Math.floor(Math.random()*1000);
  let ok=false;
  try{
    const sample=await claude.use("sample");if(!sample)throw new Error("none");
    const p='어떤 사람이 지금 받고 싶은 위로를 이렇게 적었어요: "'+f.replace(/"/g,"'")+'"\n이 마음에 맞는 '+langp()+' 위로 문구 12개를 인스타 스토리 카드용으로 써 주세요. 문체: '+$("tone").value+'. 각 문구는 줄바꿈(\\n) 포함 2줄 이내, 공백 포함 45자 이내. 12개는 서로 다른 말이어야 하고,'+varNote()+' 공감, 인정, 작은 위안, 지금 할 수 있는 한 가지, 응원, 쉼, 희망 등 다른 관점을 고루 담아 주세요. 각 문구의 정서에 맞는 풍경 테마를 아래 12개 중에서 하나씩 고르세요(키: 이름): '+TH.map(k=>k+": "+SC.find(q=>q[0]===k)[1]).join(", ")+'. 12개 문구가 한두 테마에만 몰리지 않게 골고루 쓰되 정서에 맞게 고르세요. art에는 그 풍경의 색감만 정해 주세요: 하늘이나 배경 색 3개(위에서 아래, #rrggbb)와 빛의 색(glow). 글씨가 흰색으로 얹히니 너무 밝은 색은 피하고, 같은 테마라도 문구마다 시간대와 색감이 다르게 해 주세요. JSON만 출력: {"items":[{"text":"...","scene":"테마 키","art":{"sky":["#위","#중간","#아래"],"glow":"#빛색"}}]}';
    const r=await sample.json(p);
    const it=(r&&Array.isArray(r.items)?r.items:[]).slice(0,12).map((x,i)=>({text:String(x&&x.text||"").trim(),scene:SCK.includes(x&&x.scene)?x.scene:SCK[i%SCK.length],art:x&&x.art&&typeof x.art==="object"?x.art:null})).filter(x=>x.text);
    if(it.length<4)throw new Error("bad");
    cands=it;ok=true;remember(it);
  }catch(e){cands=fbPool(f);m.textContent="맞춤 글귀를 불러오지 못해 준비된 글귀로 채웠어요. 마음에 드는 4개를 골라 주세요."}
  if(ok)m.textContent="글귀 "+cands.length+"개를 만들었어요. 마음에 드는 4개를 골라 주세요.";
  sel=[0,1,2,3];renderPool();applySel();
  b.disabled=false;b.textContent="🌿 위로 글귀 12개 만들기";
}
async function redesign(){
  const m=$("msg"),b=$("redesign");b.disabled=true;b.textContent="풍경을 설계하는 중…";seedBase=Math.floor(Math.random()*1000);
  try{
    const sample=await claude.use("sample");if(!sample)throw new Error("none");
    const t=cuts.map((c,i)=>(i+1)+") "+c.text.replace(/\n/g," ")).join("\n");
    const r=await sample.json('아래 위로 문구 4개 각각에 어울리는 풍경을 새로 설계해 주세요.\n'+t+'\n'+ARTRULES+' 4개의 풍경은 서로 확연히 달라야 해요. JSON만 출력: {"arts":['+ARTSCHEMA+',...4개]}');
    if(!r||!Array.isArray(r.arts)||r.arts.length<4)throw new Error("bad");
    cuts.forEach((c,i)=>{c.art=r.arts[i]&&typeof r.arts[i]==="object"?r.arts[i]:null;c.scene=c.art?"ai":c.scene;c.img=null});m.textContent="AI가 풍경을 새로 설계했어요.";refresh();
  }catch(e){m.textContent="AI 풍경을 불러오지 못했어요. 잠시 뒤 다시 눌러 주세요."}
  b.disabled=false;b.textContent="✨ 풍경만 AI로 다시 설계";
}
CHIPS.forEach(t=>{const o=document.createElement("option");o.value=t;o.textContent=t;$("emo").appendChild(o)});$("emo").onchange=()=>{const v=$("emo").value;if(v){$("feel").value=v;generate()}};
$("shuf").onclick=()=>{seedBase=Math.floor(Math.random()*1000);const o=SCK.slice().sort(()=>Math.random()-.5);cuts.forEach((c,i)=>{c.scene=o[i];c.img=null});refresh()};$("gen").onclick=generate;$("redesign").onclick=redesign;if(typeof claude==="undefined"){$("redesign").hidden=true}FONTS.forEach(f=>{const o=document.createElement("option");o.value=f.id;o.textContent=f.label;$("font").appendChild(o)});$("font").onchange=()=>{cuts.forEach(c=>c.font=$("font").value);refresh()};$("lang").onchange=generate;$("regen").onclick=generate;$("saveAll").onclick=saveAll;
TH.forEach(k=>{const o=document.createElement("option");o.value=k;o.textContent=SC.find(q=>q[0]===k)[1];$("theme").appendChild(o)});
$("theme").onchange=()=>{if(sel.length===4)applySel();else{const v=$("theme").value;if(v)cuts.forEach(c=>{c.scene=v;c.img=null});refresh()}};
applyFB("");build();
(async()=>{try{await document.fonts.load("700 40px 'Gowun Batang'")}catch(e){}refresh();
try{dl=await claude.use("downloads")}catch(e){}})();
cuts.forEach((_,i)=>draw(i));
</script>
</body>
</html>
