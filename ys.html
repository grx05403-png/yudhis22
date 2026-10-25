<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Romantic ❤️</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        min-height: 100vh;
        background: radial-gradient(circle at 50% 20%, #2b0a0a 0%, #120000 60%, #000 100%);
        color: #ff6b6b;
        font-family: "Courier New", Courier, monospace;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
        padding: 20px;
    }

    .container {
        max-width: 720px;
        width: 100%;
        text-align: center;
    }

    #text {
        font-size: 1.15rem;
        line-height: 1.7;
        color: #ffb3b3;
        min-height: 120px;
        white-space: pre-wrap;
        text-shadow: 0 0 8px rgba(255, 80, 80, 0.6);
    }

    #text .caret {
        display: inline-block;
        width: 9px;
        background-color: #ff4d4d;
        margin-left: 2px;
        animation: blink 0.8s steps(1) infinite;
    }

    @keyframes blink {
        50% { opacity: 0; }
    }

    #heart {
        font-family: monospace;
        font-size: 1.4rem;
        line-height: 1.1;
        color: #ff2d2d;
        white-space: pre;
        text-shadow: 0 0 12px rgba(255, 0, 0, 0.85),
                     0 0 25px rgba(255, 0, 0, 0.45);
        margin: 25px 0;
        opacity: 0;
        transform: scale(0.5);
        transition: opacity 0.4s ease, transform 0.4s ease;
    }

    #heart.show {
        opacity: 1;
        transform: scale(1);
    }

    #hint {
        margin-top: 35px;
        font-size: 0.85rem;
        color: #a14a4a;
        opacity: 0;
        transition: opacity 1s ease;
    }

    #hint.show {
        opacity: 1;
    }

    /* Bunga hati kecil mengambang di background */
    .petal {
        position: fixed;
        top: -20px;
        color: #ff4d4d;
        font-size: 14px;
        opacity: 0.7;
        pointer-events: none;
        animation: fall linear infinite;
        z-index: 0;
    }

    @keyframes fall {
        0%   { transform: translateY(-10vh) rotate(0deg); opacity: 0.8; }
        100% { transform: translateY(110vh) rotate(360deg); opacity: 0; }
    }
</style>
</head>
<body>

<div class="container">
    <div id="text"></div>
    <div id="heart"></div>
    <div id="hint">Tekan Enter untuk mengulang ❤️</div>
</div>

<script>
/* ================== EFEK TYPEWRITER ================== */
const textEl = document.getElementById("text");
const heartEl = document.getElementById("heart");
const hintEl = document.getElementById("hint");

function sleep(ms) {
    return new Promise(resolve => setTimeout(resolve, ms));
}

async function typewriter(text, delay = 40) {
    for (let i = 0; i < text.length; i++) {
        textEl.innerHTML = text.slice(0, i + 1) + '<span class="caret"></span>';
        await sleep(delay);
    }
    textEl.innerHTML = text + '<span class="caret"></span>';
    await sleep(300);
    // hapus caret di akhir baris
    textEl.innerHTML = text;
}

/* ================== GAMBAR HATI (ASCII) ================== */
const heartArt = `
   **     **  
 ****** ******
***************
 ************* 
  ***********  
   *********   
    *******    
     *****     
      ***      
       *       
`;

async function showHeart(times = 3) {
    for (let i = 0; i < times; i++) {
        heartEl.textContent = heartArt;
        heartEl.classList.add("show");
        await sleep(400 + i * 150);
        heartEl.classList.remove("show");
        await sleep(200);
    }
    // tampilkan hati terakhir (permanen)
    heartEl.textContent = heartArt;
    heartEl.classList.add("show");
}

/* ================== BUNGA HATI JATUH ================== */
function createPetals(count = 20) {
    for (let i = 0; i < count; i++) {
        const petal = document.createElement("div");
        petal.classList.add("petal");
        petal.textContent = "❤";
        petal.style.left = Math.random() * 100 + "vw";
        petal.style.animationDuration = (6 + Math.random() * 6) + "s";
        petal.style.animationDelay = (Math.random() * 5) + "s";
        petal.style.fontSize = (10 + Math.random() * 14) + "px";
        petal.style.opacity = 0.3 + Math.random() * 0.5;
        document.body.appendChild(petal);
    }
}

/* ================== ALUR UTAMA ================== */
async function playScene() {
    // reset tampilan
    textEl.innerHTML = "";
    heartEl.textContent = "";
    heartEl.classList.remove("show");
    hintEl.classList.remove("show");

    await typewriter("Di bawah langit yang sama, aku menulis kata-kata ini untukmu...", 35);
    await sleep(600);

    await typewriter("Setiap detik adalah bait, setiap napas adalah nada.", 35);
    await sleep(500);

    await typewriter("Izinkan aku menjadi alasan senyummu hari ini.", 35);
    await sleep(700);

    // Animasi hati berkedip 3x
    await showHeart(3);

    await typewriter("Untukmu, yang membuat hari-hariku berwarna.", 45);
    await typewriter("Tetaplah di sana, di hatiku.", 55);
    await typewriter("Dari Yudhis.", 57);

    // Hati terakhir muncul di bawah teks
    heartEl.textContent = heartArt;
    heartEl.classList.add("show");

    hintEl.classList.add("show");
}

/* ================== KONTROL ================== */
let isPlaying = false;

function start() {
    if (isPlaying) return;
    isPlaying = true;
    playScene().finally(() => { isPlaying = false; });
}

// Tekan Enter untuk mengulang
document.addEventListener("keydown", (e) => {
    if (e.key === "Enter") start();
});

// Klik di mana saja juga bisa
document.addEventListener("click", () => start());

// Jalankan
createPetals(25);
start();
</script>

</body>
</html>
