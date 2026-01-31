<!doctype html>

<html lang="en" class="h-full">  
 <head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Nikah Invitation</title>  
  <script src="https://cdn.tailwindcss.com"></script>  
  <script src="/_sdk/element_sdk.js"></script>  
  <link rel="preconnect" href="https://fonts.googleapis.com">  
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400&amp;family=Noto+Nastaliq+Urdu:wght@400;700&amp;display=swap" rel="stylesheet">  
  <style>  
    body {  
      box-sizing: border-box;  
    }  .font-elegant {  
  font-family: 'Cormorant Garamond', serif;  
}  
  
.font-arabic {  
  font-family: 'Noto Nastaliq Urdu', serif;  
}  
  
.confetti {  
  position: fixed;  
  width: 12px;  
  height: 12px;  
  pointer-events: none;  
  z-index: 1000;  
  animation: confetti-fall linear forwards;  
}  
  
@keyframes confetti-fall {  
  0% {  
    transform: translateY(0) rotate(0deg) scale(1);  
    opacity: 1;  
  }  
  100% {  
    transform: translateY(100%) rotate(720deg) scale(0.5);  
    opacity: 0;  
  }  
}  
  
.card-reveal {  
  animation: card-reveal 1.2s ease-out forwards;  
}  
  
@keyframes card-reveal {  
  0% {  
    opacity: 0;  
    transform: scale(0.8) translateY(30px);  
  }  
  100% {  
    opacity: 1;  
    transform: scale(1) translateY(0);  
  }  
}  
  
.fade-in {  
  animation: fade-in 0.8s ease-out forwards;  
}  
  
@keyframes fade-in {  
  0% {  
    opacity: 0;  
    transform: translateY(20px);  
  }  
  100% {  
    opacity: 1;  
    transform: translateY(0);  
  }  
}  
  
.shimmer {  
  background: linear-gradient(  
    110deg,  
    transparent 20%,  
    rgba(255, 215, 150, 0.3) 40%,  
    rgba(255, 215, 150, 0.3) 60%,  
    transparent 80%  
  );  
  background-size: 200% 100%;  
  animation: shimmer 3s infinite;  
}  
  
@keyframes shimmer {  
  0% { background-position: 200% 0; }  
  100% { background-position: -200% 0; }  
}  
  
.float-gentle {  
  animation: float-gentle 4s ease-in-out infinite;  
}  
  
@keyframes float-gentle {  
  0%, 100% { transform: translateY(0); }  
  50% { transform: translateY(-8px); }  
}  
  
.geometric-pattern {  
  background-image:   
    repeating-linear-gradient(  
      45deg,  
      transparent,  
      transparent 10px,  
      rgba(180, 140, 100, 0.05) 10px,  
      rgba(180, 140, 100, 0.05) 20px  
    );  
}  
  
.hidden {  
  display: none;  
}

  </style>  
  <style>@view-transition { navigation: auto; }</style>  
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>  
 </head>  
 <body class="h-full">  
  <div id="app-wrapper" class="h-full w-full overflow-auto" style="background: linear-gradient(135deg, #0a0e27 0%, #16213e 50%, #0a0e27 100%);"><!-- Confetti Container -->  
   <div id="confetti-container"></div><!-- Floating Decorative Stickers -->  
   <div style="position: fixed; top: 5%; left: 5%; font-size: 3rem; opacity: 0.15; animation: float-gentle 6s ease-in-out infinite; z-index: 1;">  
    💍  
   </div>  
   <div style="position: fixed; top: 15%; right: 8%; font-size: 2.5rem; opacity: 0.15; animation: float-gentle 5s ease-in-out infinite 1s; z-index: 1;">  
    🌙  
   </div>  
   <div style="position: fixed; bottom: 20%; left: 10%; font-size: 2rem; opacity: 0.15; animation: float-gentle 7s ease-in-out infinite 2s; z-index: 1;">  
    ✨  
   </div>  
   <div style="position: fixed; bottom: 10%; right: 5%; font-size: 3rem; opacity: 0.15; animation: float-gentle 6s ease-in-out infinite 0.5s; z-index: 1;">  
    🕌  
   </div>  
   <div style="position: fixed; top: 40%; left: 3%; font-size: 2rem; opacity: 0.12; animation: float-gentle 8s ease-in-out infinite 1.5s; z-index: 1;">  
    🌟  
   </div>  
   <div style="position: fixed; top: 60%; right: 4%; font-size: 2.5rem; opacity: 0.12; animation: float-gentle 7s ease-in-out infinite 3s; z-index: 1;">  
    💝  
   </div><!-- Welcome Screen -->  
   <div id="welcome-screen" class="min-h-full flex items-center justify-center p-4 sm:p-8">  
    <div class="fade-in relative w-full max-w-md rounded-lg overflow-hidden shadow-2xl" style="background: linear-gradient(180deg, #faf6f0 0%, #f5ede3 100%);"><!-- Top Border -->  
     <div class="h-3 shimmer" style="background: linear-gradient(90deg, #d4af37, #f4e5c3, #d4af37, #c9a236, #d4af37);"></div><!-- Content -->  
     <div class="p-8 sm:p-12 text-center"><!-- Bismillah -->  
      <div class="float-gentle mb-8">  
       <p class="font-arabic text-2xl mb-2" style="color: #d4af37;">بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ</p>  
      </div><!-- Decorative Star -->  
      <div class="flex justify-center mb-6">  
       <svg class="w-12 h-12" viewbox="0 0 24 24" fill="none" style="color: #d4af37;"><path d="M12 2L14.5 9H22L16 14L18.5 22L12 17L5.5 22L8 14L2 9H9.5L12 2Z" fill="currentColor" />  
       </svg>  
      </div><!-- Welcome Message -->  
      <h1 class="font-elegant text-3xl sm:text-4xl font-bold mb-4" id="welcome-title" style="color: #1a1a2e;">You're Invited!</h1>  
      <p class="font-elegant text-lg mb-8" id="welcome-text" style="color: #6b5b7a;">Please enter your name to view your personalized invitation</p><!-- Name Input Form -->  
      <form id="name-form" class="space-y-6">  
       <div><label for="guest-name-input" class="font-elegant text-sm uppercase tracking-wider block mb-2" style="color: #d4af37;">Your Name</label> <input type="text" id="guest-name-input" name="guest-name" class="w-full px-4 py-3 rounded-lg font-elegant text-lg text-center border-2 focus:outline-none focus:border-opacity-100 transition-all" style="border-color: #e8d5a8; background: rgba(255, 255, 255, 0.8); color: #1a1a2e;" placeholder="Enter your name" required>  
       </div><button type="submit" class="w-full px-8 py-4 font-elegant text-base uppercase tracking-widest rounded-full transition-all duration-500 hover:scale-105 hover:shadow-2xl relative overflow-hidden group" style="background: linear-gradient(135deg, #d4af37, #f4e5c3, #d4af37); color: #1a1a2e; font-weight: 600; box-shadow: 0 8px 30px rgba(212, 175, 55, 0.4);"> <span class="relative z-10">View Invitation ✨</span>  
        <div class="absolute inset-0 bg-gradient-to-r from-transparent via-white to-transparent opacity-0 group-hover:opacity-30 transform -skew-x-12 group-hover:translate-x-full transition-all duration-700"></div></button>  
      </form><!-- Decorative Ornament -->  
      <div class="flex justify-center mt-8">  
       <svg class="w-32 h-8" viewbox="0 0 120 30" fill="none"><path d="M0 15 Q30 0 60 15 Q90 30 120 15" stroke="#d4af37" stroke-width="1" fill="none" /> <path d="M0 15 Q30 30 60 15 Q90 0 120 15" stroke="#e8d5a8" stroke-width="1" fill="none" /> <circle cx="60" cy="15" r="4" fill="#d4af37" /> <circle cx="30" cy="15" r="2" fill="#c9a236" /> <circle cx="90" cy="15" r="2" fill="#c9a236" />  
       </svg>  
      </div>  
     </div><!-- Bottom Border -->  
     <div class="h-3 shimmer" style="background: linear-gradient(90deg, #d4af37, #f4e5c3, #d4af37, #c9a236, #d4af37);"></div>  
    </div>  
   </div><!-- Main Nikah Card (Initially Hidden) -->  
   <div id="nikah-card" class="hidden min-h-full items-center justify-center p-4 sm:p-8">  
    <div id="card" class="card-reveal relative w-full max-w-lg geometric-pattern rounded-lg overflow-hidden shadow-2xl" style="background: linear-gradient(180deg, #faf6f0 0%, #f5ede3 100%);"><!-- Top Ornamental Border -->  
     <div class="h-3 shimmer" style="background: linear-gradient(90deg, #d4af37, #f4e5c3, #d4af37, #c9a236, #d4af37);"></div><!-- Inner Frame -->  
     <div class="m-3 sm:m-5 border-4 rounded" style="border-color: #d4af37;">  
      <div class="border-2 m-1" style="border-color: #e8d5a8;">  
       <div class="p-6 sm:p-10 text-center"><!-- Personalized Greeting -->  
        <div class="mb-6 p-4 rounded-lg" style="background: rgba(212, 175, 55, 0.08);">  
         <p class="font-elegant text-xl sm:text-2xl font-semibold" style="color: #d4af37;">Dear <span id="display-guest-name">Guest</span>,</p>  
        </div><!-- Bismillah -->  
        <div class="float-gentle mb-6">  
         <p class="font-arabic text-2xl sm:text-3xl mb-2" id="bismillah" style="color: #d4af37;">بِسْمِ اللهِ الرَّحْمٰنِ الرَّحِيْمِ</p>  
         <p class="font-elegant text-xs tracking-widest uppercase" style="color: #6b5b7a;">In the name of Allah, the Most Gracious, the Most Merciful</p>  
        </div><!-- Decorative Divider -->  
        <div class="flex items-center justify-center gap-3 mb-6">  
         <div class="h-px w-16 sm:w-24" style="background: linear-gradient(90deg, transparent, #d4af37);"></div>  
         <svg class="w-6 h-6" viewbox="0 0 24 24" fill="none" style="color: #d4af37;"><path d="M12 2L14.5 9H22L16 14L18.5 22L12 17L5.5 22L8 14L2 9H9.5L12 2Z" fill="currentColor" />  
         </svg>  
         <div class="h-px w-16 sm:w-24" style="background: linear-gradient(90deg, #d4af37, transparent);"></div>  
        </div><!-- Nikah Title -->  
        <h1 class="font-elegant text-3xl sm:text-4xl font-bold tracking-wide mb-2" id="title" style="color: #1a1a2e;">Nikah Ceremony</h1>  
        <p class="font-elegant italic text-sm mb-8" id="invitation-text" style="color: #6b5b7a;">Together with their families, request the honor of your presence</p><!-- Couple Names with Photos -->  
        <div class="mb-8"><!-- Couple Photos -->  
         <div class="flex items-center justify-center gap-6 mb-6" id="couple-photos"><!-- Groom Photo -->  
          <div class="flex flex-col items-center">  
           <div id="groom-photo-container" class="w-28 h-28 sm:w-32 sm:h-32 rounded-full overflow-hidden border-4 mb-3 shadow-lg" style="border-color: #d4af37; background: linear-gradient(135deg, #e8d5a8 0%, #f4e5c3 100%);">  
            <div class="w-full h-full flex items-center justify-center text-4xl sm:text-5xl" id="groom-photo-placeholder">  
             👨  
            </div><img id="groom-photo" class="w-full h-full object-cover hidden" loading="lazy" alt="Groom" onerror="console.error('Image failed to load:', this.src); this.style.display='none'; document.getElementById('groom-photo-placeholder').style.display='flex';">  
           </div>  
           <p class="font-elegant text-2xl sm:text-3xl font-semibold" id="groom-name" style="color: #1a1a2e;">Zohaib Aslam</p>  
          </div><!-- Divider -->  
          <div class="flex flex-col items-center justify-center" style="margin-top: -20px;"><span class="font-arabic text-2xl sm:text-3xl" style="color: #d4af37;">&amp;</span>  
          </div><!-- Bride Photo -->  
          <div class="flex flex-col items-center">  
           <div id="bride-photo-container" class="w-28 h-28 sm:w-32 sm:h-32 rounded-full overflow-hidden border-4 mb-3 shadow-lg" style="border-color: #d4af37; background: linear-gradient(135deg, #e8d5a8 0%, #f4e5c3 100%);">  
            <div class="w-full h-full flex items-center justify-center text-4xl sm:text-5xl" id="bride-photo-placeholder">  
             👰  
            </div><img id="bride-photo" class="w-full h-full object-cover hidden" loading="lazy" alt="Bride" onerror="console.error('Image failed to load:', this.src); this.style.display='none'; document.getElementById('bride-photo-placeholder').style.display='flex';">  
           </div>  
           <p class="font-elegant text-2xl sm:text-3xl font-semibold" id="bride-name" style="color: #1a1a2e;">Mubashra</p>  
          </div>  
         </div>  
        </div><!-- Event Details -->  
        <div class="space-y-4 mb-8 p-4 sm:p-6 rounded-lg" style="background: rgba(212, 175, 55, 0.08);">  
         <div>  
          <p class="font-elegant text-xs uppercase tracking-widest mb-1" style="color: #d4af37;">Day</p>  
          <p class="font-elegant text-lg sm:text-xl font-semibold" id="event-day" style="color: #1a1a2e;">Friday</p>  
         </div>  
         <div>  
          <p class="font-elegant text-xs uppercase tracking-widest mb-1" style="color: #d4af37;">Date</p>  
          <p class="font-elegant text-lg sm:text-xl font-semibold" id="event-date" style="color: #1a1a2e;">9 February 2026</p>  
         </div>  
         <div>  
          <p class="font-elegant text-xs uppercase tracking-widest mb-1" style="color: #d4af37;">Time</p>  
          <p class="font-elegant text-lg sm:text-xl" id="event-time" style="color: #1a1a2e;">4:00 PM onwards</p>  
         </div>  
         <div>  
          <p class="font-elegant text-xs uppercase tracking-widest mb-1" style="color: #d4af37;">Venue</p>  
          <p class="font-elegant text-lg sm:text-xl font-semibold" id="venue-name" style="color: #1a1a2e;">Home</p>  
          <p class="font-elegant text-sm" id="venue-address" style="color: #6b5b7a;"></p>  
         </div>  
        </div><!-- Decorative Ornament -->  
        <div class="flex justify-center mb-6">  
         <svg class="w-32 h-8" viewbox="0 0 120 30" fill="none"><path d="M0 15 Q30 0 60 15 Q90 30 120 15" stroke="#d4af37" stroke-width="1" fill="none" /> <path d="M0 15 Q30 30 60 15 Q90 0 120 15" stroke="#e8d5a8" stroke-width="1" fill="none" /> <circle cx="60" cy="15" r="4" fill="#d4af37" /> <circle cx="30" cy="15" r="2" fill="#c9a236" /> <circle cx="90" cy="15" r="2" fill="#c9a236" />  
         </svg>  
        </div><!-- Quranic Verse -->  
        <div class="pt-4 border-t" style="border-color: #e5ddd3;">  
         <p class="font-arabic text-lg mb-2" style="color: #8b6914;">وَمِنْ آيَاتِهِ أَنْ خَلَقَ لَكُم مِّنْ أَنفُسِكُمْ أَزْوَاجًا</p>  
         <p class="font-elegant text-xs italic" style="color: #6b5b4f;">"And among His signs is that He created for you mates from among yourselves"</p>  
         <p class="font-elegant text-xs mt-1" style="color: #8b6914;">— Surah Ar-Rum 30:21</p>  
        </div><!-- Celebrate Button --> <button id="celebrate-btn" class="mt-8 px-10 py-4 font-elegant text-base uppercase tracking-widest rounded-full transition-all duration-500 hover:scale-110 hover:shadow-2xl relative overflow-hidden group" style="background: linear-gradient(135deg, #d4af37, #f4e5c3, #d4af37); color: #1a1a2e; font-weight: 600; box-shadow: 0 8px 30px rgba(212, 175, 55, 0.4);"> <span class="relative z-10">🎉 Celebrate 🎊</span>  
         <div class="absolute inset-0 bg-gradient-to-r from-transparent via-white to-transparent opacity-0 group-hover:opacity-30 transform -skew-x-12 group-hover:translate-x-full transition-all duration-700"></div></button> <!-- Congratulations Message -->  
        <div class="mt-10 pt-6 border-t" style="border-color: #e8d5a8;">  
         <p class="font-elegant text-sm italic mb-1" style="color: #6b5b7a;">Warmest Congratulations &amp; Best Wishes</p>  
         <p class="font-elegant text-lg font-semibold" id="regards-from" style="color: #d4af37;">— Basit</p>  
        </div>  
       </div>  
      </div>  
     </div><!-- Bottom Ornamental Border -->  
     <div class="h-3 shimmer" style="background: linear-gradient(90deg, #d4af37, #f4e5c3, #d4af37, #c9a236, #d4af37);"></div>  
    </div>  
   </div>  
  </div>  
  <script>  
    const defaultConfig = {  
      welcome_message: 'Please enter your name to view your personalized invitation',  
      guest_name: '',  
      groom_name: 'Zohaib Aslam',  
      bride_name: 'Mubashra',  
      groom_image: '',  
      bride_image: '',  
      event_day: 'Friday',  
      event_date: '9 February 2026',  
      event_time: '4:00 PM onwards',  
      venue_name: 'Home',  
      venue_address: '',  
      invitation_message: 'Together with their families, request the honor of your presence',  
      regards_from: 'Basit',  
      primary_color: '#0a0e27',  
      secondary_color: '#fff8f0',  
      accent_color: '#d4af37',  
      text_color: '#1a1a2e',  
      muted_color: '#6b5b7a',  
      font_family: 'Cormorant Garamond',  
      font_size: 16  
    };  let currentGuestName = '';  

// Confetti colors  
const confettiColors = ['#d4af37', '#f4e5c3', '#c9a236', '#ffd700', '#ffe4b3', '#e8d5a8', '#b8860b'];  

function createConfetti() {  
  const container = document.getElementById('confetti-container');  
  const confettiCount = 200;  
    
  for (let i = 0; i < confettiCount; i++) {  
    setTimeout(() => {  
      const confetti = document.createElement('div');  
      confetti.className = 'confetti';  
        
      // Random properties  
      const startX = Math.random() * window.innerWidth;  
      const startY = -20;  
      const color = confettiColors[Math.floor(Math.random() * confettiColors.length)];  
      const size = Math.random() * 12 + 8;  
      const duration = Math.random() * 3 + 2.5;  
      const drift = (Math.random() - 0.5) * 300;  
      const shapes = ['50%', '0%', '20%'];  
      const shape = shapes[Math.floor(Math.random() * shapes.length)];  
        
      confetti.style.cssText = `  
        left: ${startX}px;  
        top: ${startY}px;  
        width: ${size}px;  
        height: ${size}px;  
        background: ${color};  
        border-radius: ${shape};  
        animation-duration: ${duration}s;  
        transform: rotate(${Math.random() * 360}deg);  
        box-shadow: 0 0 8px ${color};  
      `;  
        
      // Add drift effect with more rotation  
      confetti.animate([  
        { transform: `translateX(0) translateY(0) rotate(0deg) scale(1)`, opacity: 1 },  
        { transform: `translateX(${drift}px) translateY(${window.innerHeight + 100}px) rotate(1080deg) scale(0.3)`, opacity: 0 }  
      ], {  
        duration: duration * 1000,  
        easing: 'cubic-bezier(0.25, 0.46, 0.45, 0.94)'  
      });  
        
      container.appendChild(confetti);  
        
      // Remove after animation  
      setTimeout(() => confetti.remove(), duration * 1000);  
    }, i * 15);  
  }  
}  

// Handle name form submission  
document.getElementById('name-form').addEventListener('submit', (e) => {  
  e.preventDefault();  
    
  const nameInput = document.getElementById('guest-name-input');  
  currentGuestName = nameInput.value.trim();  
    
  if (currentGuestName) {  
    // Update the guest name display  
    document.getElementById('display-guest-name').textContent = currentGuestName;  
      
    // Hide welcome screen and show card  
    document.getElementById('welcome-screen').classList.add('hidden');  
    document.getElementById('nikah-card').classList.remove('hidden');  
    document.getElementById('nikah-card').classList.add('flex');  
      
    // Trigger confetti after a short delay  
    setTimeout(createConfetti, 800);  
  }  
});  

// Add click event for celebrate button  
document.getElementById('celebrate-btn').addEventListener('click', createConfetti);  

async function onConfigChange(config) {  
  const cfg = { ...defaultConfig, ...config };  
    
  // Update welcome screen  
  document.getElementById('welcome-text').textContent = cfg.welcome_message;  
    
  // Pre-fill guest name if provided  
  if (cfg.guest_name && cfg.guest_name.trim() !== '') {  
    document.getElementById('guest-name-input').value = cfg.guest_name;  
  }  
    
  // Update text content  
  document.getElementById('groom-name').textContent = cfg.groom_name;  
  document.getElementById('bride-name').textContent = cfg.bride_name;  
  document.getElementById('event-day').textContent = cfg.event_day;  
  document.getElementById('event-date').textContent = cfg.event_date;  
  document.getElementById('event-time').textContent = cfg.event_time;  
  document.getElementById('venue-name').textContent = cfg.venue_name;  
  document.getElementById('venue-address').textContent = cfg.venue_address;  
  document.getElementById('invitation-text').textContent = cfg.invitation_message;  
  document.getElementById('regards-from').textContent = `— ${cfg.regards_from}`;  
    
  // Update photos  
  const groomPhoto = document.getEleme