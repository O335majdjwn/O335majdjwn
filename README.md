<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="styles.css">
<title> nikoh to'yida faxriy mehmon bo'ling!</title>
</head>
<body>
<div class="invitation">
    <header>
        <h1>Hurmatli mehmonlar!</h1>
        <p>Sizni Omonullo va Azizaning nikoh to'yining faxriy mehmoni bo'lishga taklif qilamiz.</p>
        <p>Qalblar ezguliklarga to‘la bo‘lgan ushbu qutlug‘ kunda do‘stlar yonida bo‘ling!</p>
    </header>
    <section class="details">
        <p><strong>Bayramni boshlash vaqti:</strong> 31.08.2024 / soat 6:43</p>
        <p><strong>To'y manzili:</strong> Azizim to`yhonasi</p>
        <a href="https://maps.app.goo.gl/rPXa7z5auwNqRykY9" target="_blank" class="map-button">Karta orqali ochish</a>
    </section>
    <div class="countdown">
        <div id="days" class="time">03 <span>kun</span></div>
        <div id="hours" class="time">00 <span>soat</span></div>
        <div id="minutes" class="time">00 <span>daqiqalar</span></div>
        <div id="seconds" class="time">00 <span>soniyalar</span></div>
    </div>
    <audio id="audioPlayer" loop>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    
    <button id="playPauseBtn" onclick="togglePlayPause()">▶️ Play Music</button>

</div>
<script src="script.js"></script>
</body>
</html>
