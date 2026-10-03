 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="Jump & Core">
<meta name="theme-color" content="#111">
<title>Jump & Speed Workout</title>
<style>
*{box-sizing:border-box}body{margin:0;background:#111;color:#fff;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;padding:20px 16px 40px}.app{max-width:600px;margin:auto}h1{font-size:30px;margin:10px 0 4px}.sub{color:#aaa;margin:0 0 18px}.day{background:#1b1b1b;border:1px solid #333;border-radius:18px;padding:16px;margin:14px 0}.day h2{margin:0 0 12px;font-size:21px}.exercise{display:flex;align-items:center;gap:12px;padding:11px 0;border-top:1px solid #2d2d2d}.exercise:first-of-type{border-top:0}input{width:24px;height:24px;accent-color:#32d74b;flex:none}label{font-size:16px;line-height:1.3}.done label{text-decoration:line-through;color:#777}.progress{height:10px;background:#2b2b2b;border-radius:99px;overflow:hidden;margin:12px 0}.bar{height:100%;width:0;background:#32d74b;transition:.2s}.counter{text-align:center;color:#bbb;font-size:14px}button{border:0;border-radius:12px;padding:12px 15px;font-size:15px;font-weight:700;cursor:pointer}#reset{background:#333;color:#fff;width:100%;margin-top:8px}.note{font-size:13px;color:#999;line-height:1.45;margin-top:18px}
</style>
</head>
<body><div class="app">
<h1>⚡ Jump & Speed Workout</h1>
<p class="sub">Leg power • Jump height • Speed • Core • Calisthenics</p>
<div class="progress"><div class="bar" id="bar"></div></div><div class="counter" id="counter">0 / 0 completed</div>

<section class="day"><h2>MON — Explosive Legs + Core</h2>
<div class="exercise"><input type="checkbox"><label>Squats — 4 × 12–15</label></div>
<div class="exercise"><input type="checkbox"><label>Squat jumps — 5 × 5</label></div>
<div class="exercise"><input type="checkbox"><label>Max vertical jumps — 6 × 3</label></div>
<div class="exercise"><input type="checkbox"><label>Calf raises — 4 × 20</label></div>
<div class="exercise"><input type="checkbox"><label>Pogo jumps — 3 × 20</label></div>
<div class="exercise"><input type="checkbox"><label>Hollow-body hold — 3 × 30–60 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Reverse crunches — 3 × 12–15</label></div></section>

<section class="day"><h2>TUE — Upper Body + Core</h2>
<div class="exercise"><input type="checkbox"><label>Push-ups — 4 × 10–20</label></div>
<div class="exercise"><input type="checkbox"><label>Decline push-ups — 3 × 6–12</label></div>
<div class="exercise"><input type="checkbox"><label>Chin-ups — 3 × 5–10</label></div>
<div class="exercise"><input type="checkbox"><label>Close-grip push-ups — 3 × 8–15</label></div>
<div class="exercise"><input type="checkbox"><label>Leg raises — 3 × 10–15</label></div>
<div class="exercise"><input type="checkbox"><label>Bicycle crunches — 3 × 20</label></div>
<div class="exercise"><input type="checkbox"><label>Hollow-body hold — 3 × 30–60 sec</label></div></section>

<section class="day"><h2>WED — Speed Power + Legs</h2>
<div class="exercise"><input type="checkbox"><label>Fast high-knees in place — 5 × 20 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Fast feet in place — 5 × 15 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Broad jumps — 4 × 5</label></div>
<div class="exercise"><input type="checkbox"><label>Jumping lunges — 3 × 6 each leg</label></div>
<div class="exercise"><input type="checkbox"><label>Single-leg calf raises — 3 × 15 each leg</label></div>
<div class="exercise"><input type="checkbox"><label>Wall sit — 3 × 30–60 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Plank — 3 × 30–60 sec</label></div></section>

<section class="day"><h2>THU — Jump Height + Core</h2>
<div class="exercise"><input type="checkbox"><label>Max vertical jumps — 6 × 3</label></div>
<div class="exercise"><input type="checkbox"><label>Squat jumps — 4 × 6</label></div>
<div class="exercise"><input type="checkbox"><label>Pogo jumps — 4 × 15</label></div>
<div class="exercise"><input type="checkbox"><label>Calf raises — 4 × 20</label></div>
<div class="exercise"><input type="checkbox"><label>Glute bridges — 4 × 15</label></div>
<div class="exercise"><input type="checkbox"><label>Leg raises — 3 × 10–15</label></div>
<div class="exercise"><input type="checkbox"><label>Reverse crunches — 3 × 12–15</label></div></section>

<section class="day"><h2>FRI — Legs + Full Core</h2>
<div class="exercise"><input type="checkbox"><label>Squats — 4 × 15</label></div>
<div class="exercise"><input type="checkbox"><label>Step-ups — 3 × 10 each leg</label></div>
<div class="exercise"><input type="checkbox"><label>Glute bridges — 3 × 15</label></div>
<div class="exercise"><input type="checkbox"><label>Calf raises — 4 × 20–25</label></div>
<div class="exercise"><input type="checkbox"><label>Wall sit — 3 × 45–60 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Hollow-body hold — 3 × 30–60 sec</label></div>
<div class="exercise"><input type="checkbox"><label>Mountain climbers — 3 × 20</label></div></section>

<section class="day"><h2>SAT — 💤 Recovery</h2>
<div class="exercise"><input type="checkbox"><label>Easy movement / mobility</label></div>
<div class="exercise"><input type="checkbox"><label>Gentle stretching</label></div>
<div class="exercise"><input type="checkbox"><label>Recover — no hard jumping</label></div></section>

<section class="day"><h2>SUN — 💤 Recovery</h2>
<div class="exercise"><input type="checkbox"><label>Rest and recover</label></div></section>

<button id="reset">Reset all checkmarks</button>
<p class="note">No outdoor runs needed. High knees and fast-feet drills are done in place. Focus on powerful, controlled jumps and soft landings. Stop if anything hurts.</p>
</div>
<script>
const boxes=[...document.querySelectorAll('input[type="checkbox"]')],key='jumpCoreWorkoutChecks',saved=JSON.parse(localStorage.getItem(key)||'[]');
boxes.forEach((b,i)=>{b.checked=!!saved[i];b.addEventListener('change',update)});
function update(){localStorage.setItem(key,JSON.stringify(boxes.map(b=>b.checked)));boxes.forEach(b=>b.parentElement.classList.toggle('done',b.checked));const d=boxes.filter(b=>b.checked).length;document.getElementById('counter').textContent=d+' / '+boxes.length+' completed';document.getElementById('bar').style.width=(d/boxes.length*100)+'%'}
document.getElementById('reset').onclick=()=>{boxes.forEach(b=>b.checked=false);update()};update();
</script></body></html>
