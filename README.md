`index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>pothula.nikhileswar reddy</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom styles for dropdown and scroll */
    .dropdown:hover .dropdown-menu {
      display: block;
    }
    .scrolling-notice {
      animation: marquee 20s linear infinite;
      white-space: nowrap;
    }
    @keyframes marquee {
      0% { transform: translateX(100%) }
      100% { transform: translateX(-100%) }
    }
    /* Sticky Enquire button on right */
    #enquireNow {
      writing-mode: vertical-rl;
      text-orientation: mixed;
      transform: rotate(180deg);
    }
    /* WhatsApp floating button */
    #whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      cursor: pointer;
      width: 50px;
      height: 50px;
      z-index: 1000;
    }
  </style>
</head>
<body class="bg-white font-sans">

  <!-- Header Top -->
  <header class="bg-[#b21c28] text-white select-none">
    <div class="max-w-7xl mx-auto flex items-center py-2 md:py-4 px-4 md:px-8">
      <div class="flex items-center gap-4">
        <div class="flex items-center gap-1 pr-4 border-r border-white/60">
          <img src="https://placehold.co/60x60?text=Seal" alt="Official seal badge of Koneru Lakshmaiah Education Foundation" class="h-14 w-auto"/>
          <div class="ml-2">
            <div class="text-xl font-extrabold leading-tight uppercase">KL</div>
            <div class="text-xs tracking-widest">UNIVERSITY</div>
          </div>
        </div>
        <div class="flex flex-col text-center flex-grow">
          <h1 class="font-extrabold text-2xl md:text-3xl leading-none uppercase">pothula.nikhileswar reddy</h1>
          <div class="text-xs font-light">
            (Deemed to be <span class="tracking-widest font-semibold">U N I V E R S I T Y</span>)
          </div>
        </div>
      </div>

      <div class="flex-shrink-0 flex items-center space-x-6 ml-8 text-xs md:text-sm font-semibold">
        <div><span class="text-yellow-300 text-lg font-extrabold">45</span> YEARS OF EDUCATIONAL EXCELLENCE</div>
        <div><span class="font-bold text-white">22</span> <br/>RANKED AMONG ALL UNIVERSITIES</div>
        <div><span class="font-bold text-white text-lg">1</span> <br/>CATEGORY UNIVERSITY BY MHRD, GOVT. OF INDIA</div>
        <img src="https://placehold.co/80x30?text=NAAC+A+Grade" alt="Accreditation logo NAAC with A+ grade" />
        <img src="https://placehold.co/85x30?text=NIRF" alt="National Institutional Ranking Framework logo" />
        <img src="https://placehold.co/110x30?text=QS%20World%20University" alt="QS World University Rankings logo" />
        <img src="https://placehold.co/110x30?text=THE%20World%20University" alt="THE World University Rankings logo" />
      </div>
    </div>
  </header>

  <!-- Navigation -->
  <nav class="bg-white shadow sticky top-0 z-40">
    <div class="max-w-7xl mx-auto px-4">
      <ul class="flex space-x-4 font-semibold text-gray-700 py-3 md:py-4 items-center">
        <li><a href="#" class="hover:text-red-700">Home</a></li>
        <li><a href="#" class="hover:text-red-700">About</a></li>
        <li class="relative dropdown group">
          <a href="#" class="hover:text-red-700 flex items-center gap-1 cursor-pointer">Admissions 
            <svg class="w-3 h-3 mt-1 text-gray-600 group-hover:text-red-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M19 9l-7 7-7-7" /></svg>
          </a>
          <ul class="dropdown-menu absolute hidden bg-[#b21c28] rounded-b-md mt-1 right-0 shadow-lg min-w-[140px]">
            <li><a href="#" class="block px-5 py-2 text-white hover:bg-red-700 font-semibold">National</a></li>
            <li><a href="#" class="block px-5 py-2 text-white hover:bg-red-700 font-semibold">International</a></li>
          </ul>
        </li>
        <li><a href="#" class="hover:text-red-700">Academics</a></li>
        <li><a href="#" class="hover:text-red-700">Colleges</a></li>
        <li><a href="#" class="hover:text-red-700">Skill &amp; Progression</a></li>
        <li><a href="#" class="hover:text-red-700">Placements</a></li>
        <li><a href="#" class="hover:text-red-700">R&amp;D</a></li>
        <li><a href="#" class="hover:text-red-700">Global Connect</a></li>
        <li><a href="#" class="hover:text-red-700">Facilities (P&amp;D)</a></li>
        <li><a href="#" class="hover:text-red-700">IQAC</a></li>
        <li>
          <a href="#" class="focus:outline-none" aria-label="Accessibility">
            <img src="https://placehold.co/24x24?text=&#x267F;" alt="Accessibility wheelchair icon in black" onerror="this.style.display='none'"/>
          </a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Notifications Banner -->
  <div class="bg-[#7e161f] text-white py-1 text-center text-sm overflow-hidden relative">
    <div class="max-w-7xl mx-auto flex items-center justify-center">
      <span class="bg-yellow-500 px-4 py-1 mr-4 font-semibold rounded-sm select-none">Notifications</span>
      <div class="overflow-hidden flex w-full">
        <p class="scrolling-notice">
          <strong><a href="#" class="underline text-yellow-300">KL Education Foundation</a>, based on various activities conducted as per prescribed standards and norms by MoE IIC, for 2021-22 has given a score of 85.7217...</strong>
        </p>
      </div>
    </div>
  </div>

  <!-- Main Slider Image -->
  <section class="relative max-w-full overflow-hidden">
    <div class="relative max-w-7xl mx-auto">
      <div class="relative aspect-[16/7] w-full bg-gray-100">
        <img src="https://placehold.co/1600x700?text=XIV+Convocation+Photo+of+Officials+in+Academic+Uniform+with+Backdrop+India+Flag+and+University+Branding"
          alt="XIV Convocation stage photo with Koneru Lakshmaiah Education Foundation officials in academic uniforms standing, Indian flag waving in background, university convocation banner behind them"
          class="object-cover w-full h-full"
          onerror="this.style.display='none'"
        />
      </div>
      <!-- Previous/Next arrows placeholder as subtle overlays with white transparent background -->
      <button aria-label="Previous Slide" class="absolute left-2 top-1/2 -translate-y-1/2 bg-white/70 rounded-full p-2 hover:bg-white focus:outline-none" style="user-select:none;">
        <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M15 18l-6-6 6-6" /></svg>
      </button>
      <button aria-label="Next Slide" class="absolute right-2 top-1/2 -translate-y-1/2 bg-white/70 rounded-full p-2 hover:bg-white focus:outline-none" style="user-select:none;">
        <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M9 18l6-6-6-6" /></svg>
      </button>
    </div>
  </section>

  <!-- Enquire Now side tab -->
  <div id="enquireNow"
       class="fixed top-1/3 right-0 bg-[#b21c28] text-white font-semibold px-3 py-2 rounded-l cursor-pointer z-50 hover:bg-red-700 select-none"
       role="button"
       tabindex="0"
       aria-label="Enquire Now">
    Enquire Now
  </div>

  <!-- WhatsApp floating button -->
  <a href="https://wa.me/919999999999" target="_blank" rel="noopener noreferrer" aria-label="Chat with us on WhatsApp" id="whatsapp-button" title="Chat with us on WhatsApp">
    <img 
      src="https://placehold.co/50x50?text=WA" 
      alt="WhatsApp icon button in green circle for contacting university support" 
      onerror="this.style.display='none'"
      class="rounded-full shadow-md"
    /> 
  </a>

</body>
</html>
`index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Koneru Lakshmaiah Education Foundation - KL University</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom styles for dropdown and scroll */
    .dropdown:hover .dropdown-menu {
      display: block;
    }
    .scrolling-notice {
      animation: marquee 20s linear infinite;
      white-space: nowrap;
    }
    @keyframes marquee {
      0% { transform: translateX(100%) }
      100% { transform: translateX(-100%) }
    }
    /* Sticky Enquire button on right */
    #enquireNow {
      writing-mode: vertical-rl;
      text-orientation: mixed;
      transform: rotate(180deg);
    }
    /* WhatsApp floating button */
    #whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      cursor: pointer;
      width: 50px;
      height: 50px;
      z-index: 1000;
    }
  </style>
</head>
<body class="bg-white font-sans">

  <!-- Header Top -->
  <header class="bg-[#b21c28] text-white select-none">
    <div class="max-w-7xl mx-auto flex items-center py-2 md:py-4 px-4 md:px-8">
      <div class="flex items-center gap-4">
        <div class="flex items-center gap-1 pr-4 border-r border-white/60">
          <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f576926b-1ea7-453d-b74b-47e7fc1ea85c.png" alt="Official seal badge of Koneru Lakshmaiah Education Foundation" class="h-14 w-auto"/>
          <div class="ml-2">
            <div class="text-xl font-extrabold leading-tight uppercase">KL</div>
            <div class="text-xs tracking-widest">UNIVERSITY</div>
          </div>
        </div>
        <div class="flex flex-col text-center flex-grow">
          <h1 class="font-extrabold text-2xl md:text-3xl leading-none uppercase">KONERU LAKSHMAIAH EDUCATION FOUNDATION</h1>
          <div class="text-xs font-light">
            (Deemed to be <span class="tracking-widest font-semibold">U N I V E R S I T Y</span>)
          </div>
        </div>
      </div>

      <div class="flex-shrink-0 flex items-center space-x-6 ml-8 text-xs md:text-sm font-semibold">
        <div><span class="text-yellow-300 text-lg font-extrabold">45</span> YEARS OF EDUCATIONAL EXCELLENCE</div>
        <div><span class="font-bold text-white">22</span> <br/>RANKED AMONG ALL UNIVERSITIES</div>
        <div><span class="font-bold text-white text-lg">1</span> <br/>CATEGORY UNIVERSITY BY MHRD, GOVT. OF INDIA</div>
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3da4884b-1bb7-4fbd-ba13-7c9575863a09.png" alt="Accreditation logo NAAC with A+ grade" />
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/951cbaad-06a3-4d10-a200-43c171e7538f.png" alt="National Institutional Ranking Framework logo" />
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/33bdb0d7-1650-4076-a54d-300def7c9aad.png" alt="QS World University Rankings logo" />
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3886cf38-c58a-4a01-bf3d-ba36b6bf69bd.png" alt="THE World University Rankings logo" />
      </div>
    </div>
  </header>

  <!-- Navigation -->
  <nav class="bg-white shadow sticky top-0 z-40">
    <div class="max-w-7xl mx-auto px-4">
      <ul class="flex space-x-4 font-semibold text-gray-700 py-3 md:py-4 items-center">
        <li><a href="#" class="hover:text-red-700">Home</a></li>
        <li><a href="#" class="hover:text-red-700">About</a></li>
        <li class="relative dropdown group">
          <a href="#" class="hover:text-red-700 flex items-center gap-1 cursor-pointer">Admissions 
            <svg class="w-3 h-3 mt-1 text-gray-600 group-hover:text-red-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M19 9l-7 7-7-7" /></svg>
          </a>
          <ul class="dropdown-menu absolute hidden bg-[#b21c28] rounded-b-md mt-1 right-0 shadow-lg min-w-[140px]">
            <li><a href="#" class="block px-5 py-2 text-white hover:bg-red-700 font-semibold">National</a></li>
            <li><a href="#" class="block px-5 py-2 text-white hover:bg-red-700 font-semibold">International</a></li>
          </ul>
        </li>
        <li><a href="#" class="hover:text-red-700">Academics</a></li>
        <li><a href="#" class="hover:text-red-700">Colleges</a></li>
        <li><a href="#" class="hover:text-red-700">Skill & Progression</a></li>
        <li><a href="#" class="hover:text-red-700">Placements</a></li>
        <li><a href="#" class="hover:text-red-700">R&D</a></li>
        <li><a href="#" class="hover:text-red-700">Global Connect</a></li>
        <li><a href="#" class="hover:text-red-700">Facilities (P&D)</a></li>
        <li><a href="#" class="hover:text-red-700">IQAC</a></li>
        <li>
          <a href="#" class="focus:outline-none" aria-label="Accessibility">
            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9840daa1-2527-4ea0-97ff-a428b4705a3c.png" alt="Accessibility wheelchair icon in black" onerror="this.style.display='none'"/>
          </a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Notifications Banner -->
  <div class="bg-[#7e161f] text-white py-1 text-center text-sm overflow-hidden relative">
    <div class="max-w-7xl mx-auto flex items-center justify-center">
      <span class="bg-yellow-500 px-4 py-1 mr-4 font-semibold rounded-sm select-none">Notifications</span>
      <div class="overflow-hidden flex w-full">
        <p class="scrolling-notice">
          <strong><a href="#" class="underline text-yellow-300">KL Education Foundation</a>, based on various activities conducted as per prescribed standards and norms by MoE IIC, for 2021-22 has given a score of 85.7217...</strong>
        </p>
      </div>
    </div>
  </div>

  <!-- Main Slider Image -->
  <section class="relative max-w-full overflow-hidden">
    <div class="relative max-w-7xl mx-auto">
      <div class="relative aspect-[16/7] w-full bg-gray-100">
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1bb031db-6f06-494e-bfa2-866fb15db9c1.png"
          alt="XIV Convocation stage photo with Koneru Lakshmaiah Education Foundation officials in academic uniforms standing, Indian flag waving in background, university convocation banner behind them"
          class="object-cover w-full h-full"
          onerror="this.style.display='none'"
        />
      </div>
      <!-- Previous/Next arrows placeholder as subtle overlays with white transparent background -->
      <button aria-label="Previous Slide" class="absolute left-2 top-1/2 -translate-y-1/2 bg-white/70 rounded-full p-2 hover:bg-white focus:outline-none" style="user-select:none;">
        <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M15 18l-6-6 6-6" /></svg>
      </button>
      <button aria-label="Next Slide" class="absolute right-2 top-1/2 -translate-y-1/2 bg-white/70 rounded-full p-2 hover:bg-white focus:outline-none" style="user-select:none;">
        <svg class="w-6 h-6 text-gray-700" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path d="M9 18l6-6-6-6" /></svg>
      </button>
    </div>
  </section>

  <!-- Enquire Now side tab -->
  <div id="enquireNow"
       class="fixed top-1/3 right-0 bg-[#b21c28] text-white font-semibold px-3 py-2 rounded-l cursor-pointer z-50 hover:bg-red-700 select-none"
       role="button"
       tabindex="0"
       aria-label="Enquire Now">
    Enquire Now
  </div>

  <!-- WhatsApp floating button -->
  <a href="https://wa.me/919999999999" target="_blank" rel="noopener noreferrer" aria-label="Chat with us on WhatsApp" id="whatsapp-button" title="Chat with us on WhatsApp">
    <img 
      src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f84b7bcd-e5ce-4325-92b8-315b0c16f2e1.png" 
      alt="WhatsApp icon button in green circle for contacting university support" 
      onerror="this.style.display='none'"
      class="rounded-full shadow-md"
    /> 
  </a>

</body>
</html>

```
