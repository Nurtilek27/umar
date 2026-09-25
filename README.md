
<html lang="ky">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>Умардын бешик тою</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Great+Vibes&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
<style>
:root{--green:#607b50;--light:#fbfaf5;--ink:#171914}
*{box-sizing:border-box} html{scroll-behavior:smooth}
body{margin:0;background:#e9ebe4;color:var(--ink);font-family:"Cormorant Garamond",serif;overflow:hidden}

.wrap{width:min(100%,520px);margin:auto;background:var(--light);overflow:hidden;box-shadow:0 0 35px #0001;display:none}
section{position:relative;padding:50px 25px;text-align:center}
.leaf{position:absolute;color:#84966f;font-size:28px;opacity:.35;animation:fall 7s linear infinite}
.leaf:nth-child(1){left:8%;top:10%}.leaf:nth-child(2){right:9%;top:28%;animation-delay:1.5s}.leaf:nth-child(3){left:15%;top:62%;animation-delay:3s}.leaf:nth-child(4){right:12%;top:78%;animation-delay:4.5s}
@keyframes fall{0%,100%{transform:translateY(0) rotate(0)}50%{transform:translateY(18px) rotate(25deg)}}

/* Hero Background Section */
.hero{min-height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(#fbfaf5d0,#fbfaf5d0),url("WhatsApp Image 2026-08-28 at 14.27.18.jpeg") center/cover no-repeat}
.kicker{font-size:18px;letter-spacing:4px;color:var(--green);text-transform:uppercase;font-weight:600}
.script{font-family:"Great Vibes",cursive;color:var(--green);font-weight:400}
.hero h1{font-size:78px;line-height:.9;margin:18px 0 8px}
.hero h2{font-size:26px;font-weight:400;margin:0}
.date{display:inline-block;margin-top:25px;padding:11px 25px;border-top:1px solid #839175;border-bottom:1px solid #839175;font-size:22px;letter-spacing:3px}
.btn{display:inline-block;background:var(--green);color:white;border:0;border-radius:9px;padding:13px 28px;font:400 18px "Montserrat",sans-serif;text-decoration:none;cursor:pointer}

.intro{background:var(--light)}
.intro .orn{font-size:26px;color:#84966f;letter-spacing:10px}
.intro p{font-size:23px;line-height:1.45;margin:15px auto;max-width:420px}

/* Custom Image Cards Frame Style */
.img-card{width:100%;max-width:400px;margin:20px auto;border-radius:16px;overflow:hidden;box-shadow:0 8px 25px rgba(0,0,0,0.1);border:4px solid #fff}
.img-card img{width:100%;height:auto;display:block}

.photo-banner{padding:0;min-height:430px;background:center/cover no-repeat url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRSnRpzs3ZJT71yhYOAGX3661iQJ-a3ytjH27H8ashIf7O_vNLJUKqUQp0X&s=10")}
.photo-banner .overlay{min-height:430px;background:linear-gradient(transparent 40%,#0008);display:flex;align-items:flex-end;justify-content:center;padding:45px 20px}
.photo-banner .overlay .script{color:#fff;font-size:58px}

.details{background:var(--light)}
.details h2,.rsvp h2{font-size:52px;margin:0 0 15px}
.details p{font-size:22px;line-height:1.45;margin:8px 0}
.calendar{margin:25px auto 5px;max-width:370px}
.month{font-size:33px;color:var(--green);margin-bottom:10px}
.grid{display:grid;grid-template-columns:repeat(7,1fr);gap:7px;font-size:18px}
.grid b{font-weight:500;color:#777}
.grid span{padding:7px 0}
.grid .selected{background:var(--green);color:#fff;border-radius:50%}

.count{padding:60px 25px;min-height:400px;background:linear-gradient(#5e624cbb,#5e624cbb),url("https://avatars.mds.yandex.net/i?id=b5b98f8a58be74008fe3f0d31215439083333fcb-3751999-images-thumbs&n=13") center/cover no-repeat}
.count h2{color:white;font-size:55px;margin:0 0 30px}
.timer{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;color:white}
.timer strong{display:block;font:300 34px "Montserrat",sans-serif}
.timer small{font:300 12px "Montserrat",sans-serif;letter-spacing:1px}

.place{background:var(--light)}
.place h2{font-size:55px;margin:0 0 15px}
.place .venue{font-size:31px;color:var(--green);margin:20px 0 5px}
.place .address{font-size:21px;line-height:1.45}
.map{margin-top:22px;border-radius:10px;overflow:hidden;height:180px;background:linear-gradient(135deg,#dce6d6,#f4efe4);display:flex;align-items:center;justify-content:center;color:#637455;font-size:22px}

.rsvp{text-align:left;background:var(--light)}
.rsvp h2{text-align:center}
label{display:block;font:400 17px "Montserrat",sans-serif;margin:16px 0 8px}
.choice{display:flex;flex-direction:column;gap:9px;font:400 18px "Montserrat",sans-serif}
.choice label{margin:0;padding:11px 12px;border:1px solid #ddd;border-radius:9px}
input[type=text],textarea{width:100%;border:1px solid #cfd4c8;border-radius:8px;padding:13px;background:white;font:400 17px "Montserrat",sans-serif}
textarea{min-height:90px;resize:vertical}
.people{display:flex;align-items:center;gap:14px;justify-content:center;margin:12px 0 20px}
.people button{width:48px;height:42px;border:1px solid #999;border-radius:22px;background:white;font-size:24px}
.people span{font:400 21px "Montserrat",sans-serif;min-width:30px;text-align:center}
.rsvp .btn{width:100%;margin-top:15px}

.footer{padding:38px 20px 55px;text-align:center;background:var(--light)}
.footer .script{font-size:48px}.footer p{font-size:17px;color:#777}
.hosts{font-size:20px;line-height:1.5;margin-bottom:15px;color:var(--ink)}

/* Envelope Overlay */
.envelope-wrapper{position:fixed;inset:0;background:#e9ebe4;display:flex;justify-content:center;align-items:center;z-index:1000;transition:opacity .6s ease,visibility .6s ease}
.envelope{position:relative;width:320px;height:240px;background:var(--light);border-radius:12px;box-shadow:0 10px 30px #0002;cursor:pointer;display:flex;justify-content:center;align-items:center;text-align:center;padding:20px;border:2px solid #607b50}
.envelope-btn{background:var(--green);color:#fff;border:0;padding:12px 24px;border-radius:8px;font:500 18px "Montserrat",sans-serif;margin-top:15px;cursor:pointer;box-shadow:0 4px 10px rgba(96,123,80,0.3)}
</style>
</head>
<body>

<!-- Envelope Overlay -->
<div class="envelope-wrapper" id="envelopeWrapper">
  <div class="envelope" onclick="openEnvelope()">
    <div>
      <div class="script" style="font-size:50px;color:var(--green)">Умар</div>
      <p style="font-size:20px;margin:5px 0 15px">Бешик тойго чакыруу</p>
      <button class="envelope-btn">✉ Чакырууну ачыныз</button>
    </div>
  </div>
</div>

<!-- Audio Background -->
<audio id="bgMusic" loop preload="auto">
  <source src="C:\Users\Nurtilek\Desktop\у\умар.mp3" type="audio/mpeg">
</audio>

<div class="wrap" id="mainWrap">
<section class="hero">
<div class="leaf">❧</div><div class="leaf">❧</div><div class="leaf">❧</div><div class="leaf">❧</div>
<div>
  <div class="kicker">Бешик той</div>
  <h1 class="script">Умар</h1>
  <h2>Сиздерди урматтоо менен<br>Бешик тоюбузга чакырабыз!</h2>
  <div class="date">03 • ОКТЯБРЬ • 2026</div>
  <div style="margin-top:28px"><a class="btn" href="#invite">Чакыруу</a></div>
</div>
</section>

<section class="intro" id="invite">
<div class="leaf">❧</div><div class="leaf">❧</div>
<div class="img-card">
  <img src="C:\Users\Nurtilek\Desktop\у\семья.jpeg" alt="Умар үй-бүлөсү менен">
</div>
<div class="orn">• ❦ •</div>
<p>Сүйүнүчтү сиздер менен бөлүшөлү,<br>
   Кубанычтан бакыт болуп төгүлөлү.<br>
   Дасторкондон даам сызып, бата берип,<br>
   Кудай буйруп Жентек тойдон көрүшөлү.
</p>
<div class="orn">• ❦ •</div>

<!-- Illustrative Image Card 1 -->

</section>

<section class="photo-banner">
<div class="overlay"><div><div class="script">Биздин кичинекей<br>бактылуубуз</div></div></div>
</section>

<section class="details">
<div class="leaf">❧</div>
<h2 class="script">Күнү жана убактысы</h2>
<p>2026-жылдын <b>3-октябры</b></p>
<div class="calendar">
<div class="month script">Октябрь 2026</div>
<div class="grid">
<b>Жк</b><b>Дш</b><b>Шш</b><b>Шр</b><b>Бш</b><b>Жм</b><b>Иш</b>
<span></span><span></span><span></span><span></span><span>1</span><span>2</span><span class="selected">3</span>
<span>4</span><span>5</span><span>6</span><span>7</span><span>8</span><span>9</span><span>10</span>
<span>11</span><span>12</span><span>13</span><span>14</span><span>15</span><span>16</span><span>17</span>
<span>18</span><span>19</span><span>20</span><span>21</span><span>22</span><span>23</span><span>24</span>
<span>25</span><span>26</span><span>27</span><span>28</span><span>29</span><span>30</span><span>31</span>
</div></div>
<p style="font-size:29px;color:var(--green);margin-top:20px"><span class="script">саат</span> 12:00</p>

<!-- Illustrative Image Card 2 -->
<div class="img-card">
  <img src="C:\Users\Nurtilek\Desktop\у\умар.jpeg" alt="Умар">
</div>
</section>

<section class="count">
<h2 class="script">Тойго чейин:</h2>
<div class="timer">
<div><strong id="d">0</strong><small>КҮН</small></div>
<div><strong id="h">0</strong><small>СААТ</small></div>
<div><strong id="m">0</strong><small>МҮНӨТ</small></div>
<div><strong id="s">0</strong><small>СЕКУНД</small></div>
</div>
</section>

<section class="place">
<div class="leaf">❧</div><div class="leaf">❧</div>
<h2 class="script">Дарегибиз</h2>
<p class="venue">Жентек той өтүүчү жай</p>
<p class="address">г.Баткен кв. Базар-Башы ул.Н.Боркошов дом 13</p>
<div class="map-container">
  <iframe 
    src="https://www.google.com/maps?q=Batken+Bazar+Bashi+Borkoshov+13&output=embed" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>
<a href="https://www.google.com/maps/search/?api=1&query=Баткен+Базар-Башы+Боркошов+13" target="_blank" class="map-btn">📍 Google Картадан ачуу</a>
</section>

<section class="rsvp">
<h2 class="script">Келесизби?</h2>
<form onsubmit="sendRSVP(event)">
<label>Жообуңузду тандаңыз</label>
<div class="choice">
<label><input type="radio" name="go" value="Өзүм барам" required> Өзүм барам</label>
<label><input type="radio" name="go" value="Үй-бүлөм менен барам"> Үй-бүлөм менен барам</label>
<label><input type="radio" name="go" value="Бара албайм"> Бара албайм</label>
</div>
<label>Канча адам менен келесиз?</label>
<div class="people"><button type="button" onclick="change(-1)">−</button><span id="num">1</span><button type="button" onclick="change(1)">+</button></div>
<label>Атыңыз</label>
<input id="name" type="text" placeholder="Атыңызды жазыңыз" required>
<label>Каалоо-тилек</label>
<textarea id="msg" placeholder="Каалоо-тилегиңиз..."></textarea>
<button class="btn" type="submit">Жөнөтүү</button>
</form>
</section>

<div class="footer">
  <div class="hosts">
  Терең урматтоо менен:<br>
  <strong>Сапарбай & Сайдагүл</strong><br>
  <strong>Мирланбек & Угулай</strong>
</div>
<div class="script">Умар</div>
<p>Келип, кубанычыбызды тең бөлүшүп, ак батаңыздарды бериңиздер!</p>
</div>
</div>

<script>
function openEnvelope(){
  const music = document.getElementById("bgMusic");
  music.play().catch(e => console.log("Music play blocked", e));
  
  const env = document.getElementById("envelopeWrapper");
  env.style.opacity = "0";
  setTimeout(() => {
    env.style.visibility = "hidden";
    document.getElementById("mainWrap").style.display = "block";
    document.body.style.overflow = "auto";
  }, 600);
}

let n=1;
function change(x){n=Math.max(1,Math.min(20,n+x));document.getElementById('num').textContent=n}
function sendRSVP(e){
 e.preventDefault();
 const go=document.querySelector('input[name=go]:checked').value;
 const name=document.getElementById('name').value;
 alert(name+", жообуңуз кабыл алынды: "+go+" • "+n+" адам.");
}
const target=new Date("2026-10-03T12:00:00+06:00").getTime();
function tick(){
 let x=Math.max(0,target-Date.now());
 let d=Math.floor(x/86400000);x%=86400000;
 let h=Math.floor(x/3600000);x%=3600000;
 let m=Math.floor(x/60000);x%=60000;
 let s=Math.floor(x/1000);
 document.getElementById("d").textContent=d;
 document.getElementById("h").textContent=String(h).padStart(2,"0");
 document.getElementById("m").textContent=String(m).padStart(2,"0");
 document.getElementById("s").textContent=String(s).padStart(2,"0");
}
tick();setInterval(tick,1000);
</script>
</body>
</html>
