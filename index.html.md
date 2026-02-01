index.html  
  
<!DOCTYPE html>  
<html lang="de">  
<head>  
<meta charset="UTF-8">  
<title>Der Schlagerkönig & die Euratsfelder Spatzen</title>  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
<style>  
body {  
  margin: 0;  
  font-family: "Trebuchet MS", Arial, sans-serif;  
  background: linear-gradient(180deg, #ff4d6d, #ff9ecb);  
  color: #fff;  
  overflow-x: hidden;  
}  
  
/* ❤️ Herz-Animation */  
.heart {  
  position: fixed;  
  color: rgba(255,255,255,0.4);  
  animation: float 10s linear infinite;  
  font-size: 20px;  
}  
  
@keyframes float {  
  from { transform: translateY(100vh); }  
  to { transform: translateY(-10vh); }  
}  
  
header {  
  padding: 80px 20px;  
  text-align: center;  
  background: radial-gradient(circle, #ffb6c1, #ff2f6f);  
}  
  
h1 {  
  font-size: 3.5rem;  
  color: gold;  
  text-shadow: 3px 3px 12px #000;  
}  
  
.subtitle {  
  font-size: 1.5rem;  
}  
  
section {  
  max-width: 1100px;  
  margin: auto;  
  padding: 50px 20px;  
}  
  
.card {  
  background: rgba(255,255,255,0.15);  
  border-radius: 25px;  
  padding: 35px;  
  margin-bottom: 40px;  
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);  
}  
  
.bandfoto img {  
  width: 100%;  
  max-width: 700px;  
  border-radius: 25px;  
  box-shadow: 0 15px 40px rgba(0,0,0,0.4);  
}  
  
.tour-date {  
  display: flex;  
  justify-content: space-between;  
  padding: 15px;  
  border-bottom: 1px solid rgba(255,255,255,0.3);  
}  
  
.city {  
  font-weight: bold;  
  color: gold;  
}  
  
footer {  
  background: #b3003b;  
  padding: 30px;  
  text-align: center;  
}  
  
@media(max-width:600px){  
  h1 { font-size: 2.5rem; }  
  .tour-date { flex-direction: column; }  
}  
</style>  
</head>  
  
<body>  
  
<!-- Herzen -->  
<div class="heart" style="left:10%">❤️</div>  
<div class="heart" style="left:30%;animation-delay:2s">❤️</div>  
<div class="heart" style="left:60%;animation-delay:4s">❤️</div>  
<div class="heart" style="left:80%;animation-delay:1s">❤️</div>  
  
<header>  
  <h1>Der Schlagerkönig</h1>  
  <p class="subtitle">und die Euratsfelder Spatzen</p>  
  <p>❤️ Herz zua – Tour 2026 ❤️</p>  
</header>  
  
<section>  
  <div class="card bandfoto">  
    <h2>Die Band</h2>  
    <img src="band.jpg" alt="Der Schlagerkönig und die Euratsfelder Spatzen">  
    <p>  
      Echte Gefühle, starke Stimmen und Schlager mit Herz.  
      Stimmung garantiert!  
    </p>  
  </div>  
  
  <div class="card">  
    <h2>Tour 2026</h2>  
  
    <div class="tour-date"><span>10. April 2026</span><span class="city">Wien – Wiener Stadthalle</span></div>  
    <div class="tour-date"><span>11. April 2026</span><span class="city">Linz – TipsArena</span></div>  
    <div class="tour-date"><span>12. April 2026</span><span class="city">Klagenfurt – Messearena</span></div>  
    <div class="tour-date"><span>17. April 2026</span><span class="city">Salzburg – Salzburgarena</span></div>  
    <div class="tour-date"><span>18. April 2026</span><span class="city">Graz – Stadthalle</span></div>  
    <div class="tour-date"><span>19. April 2026</span><span class="city">Innsbruck – Olympiahalle</span></div>  
    <div class="tour-date"><span>24. April 2026</span><span class="city">St. Pölten – VAZ St. Pölten</span></div>  
    <div class="tour-date"><span>25. April 2026</span><span class="city">Wels – Messehalle</span></div>  
  
    <p style="margin-top:20px;color:#fffacd;">  
      🎟 Tickets: ÖTicket · Eventim · www.schlagerkoenig-tour.at  
    </p>  
  </div>  
</section>  
  
<footer>  
  © 2026 – Der Schlagerkönig & die Euratsfelder Spatzen  
</footer>  
  
</body>  
</html>  
