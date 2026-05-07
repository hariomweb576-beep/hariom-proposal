<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hariom ❤️ Proposal</title>

<style>
body{
  margin:0;
  font-family:Arial;
  background:#ff5f8a;
  color:white;
  text-align:center;
  overflow:hidden;
}

.page{display:none;padding:20px;}
.active{display:block}

.box{
  background:white;
  color:black;
  padding:20px;
  border-radius:15px;
  margin-top:20px;
}

.creator{
  margin-top:10px;
  font-size:14px;
  opacity:0.8;
}

.btn{
  padding:10px 20px;
  margin:8px;
  border:none;
  border-radius:10px;
  cursor:pointer;
}

.yes{background:#ff4081;color:white;}
.no{background:gray;color:white;position:relative;}
.share{background:#25D366;color:white;}
.insta{background:#E1306C;color:white;}
.snap{background:#FFFC00;color:black;}

input{
  padding:10px;
  width:80%;
  margin:10px;
  border-radius:10px;
  border:1px solid #ccc;
}

/* HEART */
.heart{
  position:fixed;
  bottom:0;
  animation:fly 4s linear;
}
@keyframes fly{
  0%{transform:translateY(0);}
  100%{transform:translateY(-100vh);}
}

/* FIREWORK */
.fire{
  position:fixed;
  width:6px;
  height:6px;
  border-radius:50%;
  background:yellow;
  animation:boom 1s forwards;
}
@keyframes boom{
  0%{transform:scale(1);}
  100%{transform:scale(15);opacity:0;}
}

#type{white-space:pre-line;margin-top:10px;}
</style>
</head>

<body onclick="startMusic()">

<!-- PAGE 1 -->
<div id="p1" class="page active">
<h2>💖 Romantic Proposal 💖</h2>
<div class="creator">✨ Created by HARIOM ✨</div>

<div class="box">
<p>
💌 Tum meri life ka sabse special part ho ❤️  
Kya tum meri banogi / banoge?
</p>

<button class="btn yes" onclick="yes()">YES 💍</button>
<button class="btn no" id="noBtn" onclick="moveNo()">NO 😅</button>
</div>
</div>

<!-- PAGE 2 -->
<div id="p2" class="page">
<h2>💑 Your Love 💑</h2>
<div class="creator">✨ Created by HARIOM ✨</div>

<div id="type"></div>

<input id="boy" placeholder="Boy Name">
<input id="girl" placeholder="Girl Name">

<button class="btn yes" onclick="create()">Create ❤️</button>

<div id="result"></div>

<button class="btn share" onclick="shareWhatsApp()">📲 WhatsApp</button>
<button class="btn insta" onclick="shareInstagram()">📸 Instagram</button>
<button class="btn snap" onclick="shareSnap()">👻 Snapchat</button>

</div>

<!-- 🔥 WORKING MUSIC -->
<audio id="music" loop>
<source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_115b9b1f3d.mp3">
</audio>

<script>

let musicStarted=false;

/* 🎵 MOBILE FIX MUSIC */
function startMusic(){
  if(!musicStarted){
    let m=document.getElementById("music");
    m.play().catch(()=>{});
    musicStarted=true;
  }
}

/* YES CLICK */
function yes(){

  for(let i=0;i<40;i++){
    let f=document.createElement("div");
    f.className="fire";
    f.style.left=Math.random()*100+"vw";
    f.style.top=Math.random()*100+"vh";
    document.body.appendChild(f);
    setTimeout(()=>f.remove(),1000);
  }

  setTimeout(()=>{
    p1.classList.remove("active");
    p2.classList.add("active");
    startTyping();
  },800);
}

/* NO MOVE */
function moveNo(){
  noBtn.style.position="absolute";
  noBtn.style.top=Math.random()*80+"%";
  noBtn.style.left=Math.random()*80+"%";
}

/* 💌 MULTI LEVEL SHAYARI */
let shayariLevels=[
`💖 Shayad main perfect nahi hoon...
lekin tumhare saath perfect banna chahta hoon ❤️`,

`🌙 Teri muskaan meri jaan hai...
tu haan bol de bas, meri pehchaan hai ❤️`,

`💍 Aaj se nahi... hamesha ke liye,
main sirf tumhara banna chahta hoon ❤️`
];

let current=0;
function startTyping(){
  type.innerHTML="";
  typeText();
}

function typeText(){
  let msg=shayariLevels[current];
  let i=0;
  type.innerHTML="";

  function typing(){
    if(i<msg.length){
      type.innerHTML+=msg.charAt(i);
      i++;
      setTimeout(typing,40);
    }else{
      if(current<shayariLevels.length-1){
        current++;
        setTimeout(typeText,1500);
      }
    }
  }
  typing();
}

/* CREATE + SAVE */
function create(){
  let b=boy.value;
  let g=girl.value;

  if(!b||!g){alert("Naam daalo 😄");return;}

  let data=`${b} ❤️ ${g}`;

  result.innerHTML=
  `<h3>${data}</h3>
  <p>${g} tum meri duniya ho ❤️<br>${b} tumhare bina kuch nahi 💖</p>`;
}

/* 🔗 SHARE LINK WITH DATA */
function getLink(){
  let b=boy.value;
  let g=girl.value;

  if(!b||!g){alert("Naam daalo 😄");return null;}

  return location.origin+location.pathname+
  `?boy=${encodeURIComponent(b)}&girl=${encodeURIComponent(g)}&love=1`;
}

/* SHARE */
function shareWhatsApp(){
  let url=getLink(); if(!url)return;
  window.open("https://wa.me/?text="+encodeURIComponent("💖 Just for you 💖\n"+url));
}

function shareInstagram(){
  let url=getLink(); if(!url)return;
  navigator.clipboard.writeText(url);
  alert("Link copied 📋 Insta pe paste karo");
  window.open("https://www.instagram.com/");
}

function shareSnap(){
  let url=getLink(); if(!url)return;
  navigator.clipboard.writeText(url);
  alert("Link copied 📋 Snap pe paste karo");
  window.open("https://www.snapchat.com/");
}

/* 🔥 AUTO LOAD SAME RESULT */
window.onload=function(){
  let p=new URLSearchParams(location.search);
  let b=p.get("boy");
  let g=p.get("girl");
  let love=p.get("love");

  if(b&&g&&love){
    p1.classList.remove("active");
    p2.classList.add("active");

    startTyping();

    result.innerHTML=
    `<h3>${b} ❤️ ${g}</h3>
    <p>${g} tum meri duniya ho ❤️<br>${b} tumhare bina kuch nahi 💖</p>`;
  }
}

/* HEART */
setInterval(()=>{
  let h=document.createElement("div");
  h.className="heart";
  h.innerHTML="❤️";
  h.style.left=Math.random()*100+"vw";
  document.body.appendChild(h);
  setTimeout(()=>h.remove(),4000);
},800);

</script>

</body>
</html>
