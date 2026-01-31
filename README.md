!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nikah Invitation</title>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Noto+Nastaliq+Urdu:wght@400;700&display=swap" rel="stylesheet">

  <style>
    body { font-family: 'Cormorant Garamond', serif; }

    .font-arabic {
      font-family: 'Noto Nastaliq Urdu', serif;
    }

    .confetti {
      position: fixed;
      width: 10px;
      height: 10px;
      pointer-events: none;
      z-index: 999;
    }
  </style>
</head>

<body class="min-h-screen flex items-center justify-center p-4"
      style="background: linear-gradient(135deg,#0a0e27,#16213e,#0a0e27);">

  <div id="confetti-container"></div>

  <div class="bg-[#faf6f0] rounded-xl shadow-2xl p-8 max-w-lg w-full text-center">

    <p class="font-arabic text-2xl text-[#d4af37] mb-2">
      بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ
    </p>

    <h1 class="text-3xl font-bold mb-2">Nikah Ceremony</h1>
    <p class="italic mb-6">
      Together with their families, request the honor of your presence
    </p>

    <div class="flex justify-center items-center gap-6 mb-6 text-2xl font-semibold">
      <span>Zohaib Aslam</span>
      <span class="text-[#d4af37]">&amp;</span>
      <span>Mubashra</span>
    </div>

    <div class="bg-yellow-100 rounded-lg p-4 mb-6">
      <p><strong>Day:</strong> Friday</p>
      <p><strong>Date:</strong> 9 February 2026</p>
      <p><strong>Time:</strong> 4:00 PM onwards</p>
      <p><strong>Venue:</strong> Home</p>
    </div>

    <p class="font-arabic text-lg mb-2 text-[#8b6914]">
      وَمِنْ آيَاتِهِ أَنْ خَلَقَ لَكُم مِّنْ أَنفُسِكُمْ أَزْوَاجًا
    </p>
    <p class="text-sm italic mb-6">
      “And among His signs is that He created for you mates from among yourselves”
      <br>— Surah Ar-Rum 30:21
    </p>

    <button id="celebrate"
      class="px-8 py-3 rounded-full font-semibold text-lg
             bg-yellow-400 hover:scale-110 transition">
      🎉 Celebrate 🎊
    </button>

    <p class="mt-6 font-semibold text-[#d4af37]">— Basit</p>
  </div>

<script>
  const colors = ['#d4af37','#ffd700','#f4e5c3','#c9a236'];

  function confetti() {
    const container = document.getElementById('confetti-container');
    for (let i = 0; i < 120; i++) {
      const c = document.createElement('div');
      c.className = 'confetti';
      c.style.left = Math.random() * window.innerWidth + 'px';
      c.style.top = '-10px';
      c.style.background = colors[Math.floor(Math.random()*colors.length)];
      c.style.borderRadius = '50%';
      container.appendChild(c);

      c.animate([
        { transform:'translateY(0)', opacity:1 },
        { transform:`translateY(${window.innerHeight}px) rotate(720deg)`, opacity:0 }
      ], { duration:3000 + Math.random()*2000 });

      setTimeout(()=>c.remove(),5000);
    }
  }

  document.getElementById('celebrate').onclick = confetti;
  setTimeout(confetti, 800);
</script>

</body>
</html>
