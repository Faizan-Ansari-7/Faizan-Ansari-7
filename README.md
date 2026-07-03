<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 300" width="100%">
  <defs>
    <!-- Highly Saturated Dark Moving Gradient Background -->
    <linearGradient id="dark-bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%">
        <animate attributeName="stop-color" values="#052538;#0a4a61;#11708f;#052538" dur="10s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%">
        <animate attributeName="stop-color" values="#11708f;#052538;#0a4a61;#11708f" dur="10s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <!-- Light Black Drop Shadow Filter -->
    <filter id="light-shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="1.5" dy="2.5" stdDeviation="2" flood-color="#000000" flood-opacity="0.6"/>
    </filter>

    <!-- TYPEWRITER ANIMATION MASK -->
    <clipPath id="typing-mask">
      <rect x="-170" y="-30" width="0" height="60">
        <animate attributeName="width" values="0; 340; 340" dur="5s" repeatCount="indefinite" />
      </rect>
    </clipPath>

    <!-- ICON DEFINITIONS -->
    <g id="html"><polygon points="-12,-15 12,-15 10,10 0,15 -10,10" fill="#E34F26"/><polygon points="0,-12 10,-12 8,8 0,12" fill="#F06529"/><text y="3" font-family="Arial" font-weight="bold" font-size="10" fill="#fff" text-anchor="middle">5</text></g>
    <g id="css"><polygon points="-12,-15 12,-15 10,10 0,15 -10,10" fill="#1572B6"/><polygon points="0,-12 10,-12 8,8 0,12" fill="#33A9DC"/><text y="3" font-family="Arial" font-weight="bold" font-size="10" fill="#fff" text-anchor="middle">3</text></g>
    <g id="js"><rect x="-12" y="-12" width="24" height="24" fill="#F7DF1E" rx="3"/><text y="4" font-family="Arial" font-weight="bold" font-size="12" fill="#000" text-anchor="middle">JS</text></g>
    <g id="py"><rect x="-12" y="-12" width="24" height="24" fill="#3776AB" rx="4"/><text y="4" font-family="Arial" font-weight="bold" font-size="12" fill="#FFD43B" text-anchor="middle">Py</text></g>
    <g id="react"><g fill="none" stroke="#61DAFB" stroke-width="2"><ellipse rx="12" ry="4" transform="rotate(30)"/><ellipse rx="12" ry="4" transform="rotate(90)"/><ellipse rx="12" ry="4" transform="rotate(150)"/></g><circle r="2.5" fill="#61DAFB"/></g>
    <g id="node"><polygon points="0,-12 10,-6 10,6 0,12 -10,6 -10,-6" fill="#339933"/><text y="3" font-family="Arial" font-weight="bold" font-size="8" fill="#fff" text-anchor="middle">N</text></g>
    <g id="mongo"><path d="M0 -14 C-8 0 -8 8 0 14 C8 8 8 0 0 -14" fill="#47A248"/><path d="M0 -14 C8 0 8 8 0 14" fill="#3E863D"/></g>
    <g id="tail"><path d="M-8 0 C-4 -8 0 -8 4 0 C8 8 12 8 8 0 C4 -8 0 -8 -4 0" fill="none" stroke="#06B6D4" stroke-width="4" stroke-linecap="round"/></g>
    <g id="boot"><rect x="-12" y="-12" width="24" height="24" fill="#7952B3" rx="4"/><text y="5" font-family="Arial" font-weight="bold" font-size="14" fill="#fff" text-anchor="middle">B</text></g>
    <g id="dj"><rect x="-14" y="-12" width="28" height="24" fill="#092E20" rx="3"/><text y="4" font-family="Arial" font-weight="bold" font-size="11" fill="#fff" text-anchor="middle">dj</text></g>
  </defs>

  <rect width="100%" height="100%" fill="url(#dark-bg)" rx="15" />

  <!-- FALLING ICONS BACKGROUND -->
  <g opacity="0.15">
    <g><animateTransform attributeName="transform" type="translate" values="15,-50; 15,350" dur="24s" begin="-10s" repeatCount="indefinite"/><use href="#html" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="70,-50; 70,350" dur="21s" begin="-2s" repeatCount="indefinite"/><use href="#js" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="130,-50; 130,350" dur="27s" begin="-15s" repeatCount="indefinite"/><use href="#tail" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="190,-50; 190,350" dur="20s" begin="-5s" repeatCount="indefinite"/><use href="#mongo" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="260,-50; 260,350" dur="25s" begin="-18s" repeatCount="indefinite"/><use href="#py" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="320,-50; 320,350" dur="22s" begin="-7s" repeatCount="indefinite"/><use href="#node" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="380,-50; 380,350" dur="28s" begin="-12s" repeatCount="indefinite"/><use href="#tail" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="440,-50; 440,350" dur="23s" begin="-1s" repeatCount="indefinite"/><use href="#css" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="510,-50; 510,350" dur="26s" begin="-20s" repeatCount="indefinite"/><use href="#boot" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="570,-50; 570,350" dur="21s" begin="-9s" repeatCount="indefinite"/><use href="#dj" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="640,-50; 640,350" dur="24s" begin="-4s" repeatCount="indefinite"/><use href="#react" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="710,-50; 710,350" dur="29s" begin="-11s" repeatCount="indefinite"/><use href="#js" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="760,-50; 760,350" dur="23s" begin="-6s" repeatCount="indefinite"/><use href="#tail" transform="scale(0.5)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="790,-50; 790,350" dur="25s" begin="-16s" repeatCount="indefinite"/><use href="#py" transform="scale(0.5)"/></g>
  </g>

  <g opacity="0.25">
    <g><animateTransform attributeName="transform" type="translate" values="30,-50; 30,350" dur="16s" begin="-5s" repeatCount="indefinite"/><use href="#py" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="100,-50; 100,350" dur="14s" begin="-1s" repeatCount="indefinite"/><use href="#node" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="170,-50; 170,350" dur="18s" begin="-9s" repeatCount="indefinite"/><use href="#mongo" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="240,-50; 240,350" dur="13s" begin="-4s" repeatCount="indefinite"/><use href="#react" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="300,-50; 300,350" dur="17s" begin="-12s" repeatCount="indefinite"/><use href="#tail" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="370,-50; 370,350" dur="15s" begin="-6s" repeatCount="indefinite"/><use href="#css" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="450,-50; 450,350" dur="19s" begin="-2s" repeatCount="indefinite"/><use href="#js" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="520,-50; 520,350" dur="14s" begin="-10s" repeatCount="indefinite"/><use href="#boot" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="590,-50; 590,350" dur="18s" begin="-14s" repeatCount="indefinite"/><use href="#html" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="660,-50; 660,350" dur="16s" begin="-3s" repeatCount="indefinite"/><use href="#tail" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="730,-50; 730,350" dur="15s" begin="-8s" repeatCount="indefinite"/><use href="#node" transform="scale(0.8)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="785,-50; 785,350" dur="17s" begin="-12s" repeatCount="indefinite"/><use href="#react" transform="scale(0.8)"/></g>
  </g>

  <g opacity="0.45">
    <g><animateTransform attributeName="transform" type="translate" values="50,-50; 50,350" dur="10s" begin="-2s" repeatCount="indefinite"/><use href="#react" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="140,-50; 140,350" dur="8s" begin="-5s" repeatCount="indefinite"/><use href="#js" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="220,-50; 220,350" dur="11s" begin="-1s" repeatCount="indefinite"/><use href="#dj" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="310,-50; 310,350" dur="9s" begin="-7s" repeatCount="indefinite"/><use href="#py" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="410,-50; 410,350" dur="10s" begin="-4s" repeatCount="indefinite"/><use href="#tail" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="500,-50; 500,350" dur="12s" begin="-9s" repeatCount="indefinite"/><use href="#mongo" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="580,-50; 580,350" dur="8s" begin="-3s" repeatCount="indefinite"/><use href="#node" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="670,-50; 670,350" dur="11s" begin="-8s" repeatCount="indefinite"/><use href="#css" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="740,-50; 740,350" dur="9s" begin="-2s" repeatCount="indefinite"/><use href="#html" transform="scale(1.2)"/></g>
    <g><animateTransform attributeName="transform" type="translate" values="795,-50; 795,350" dur="10s" begin="-6s" repeatCount="indefinite"/><use href="#js" transform="scale(1.2)"/></g>
  </g>

  <!-- ========================================== -->
  <!-- FOREGROUND TEXT                            -->
  <!-- ========================================== -->
  
  <!-- Animated Typewriter Effect -->
  <g transform="translate(400, 120)">
    <!-- The Text that gets revealed -->
    <text x="0" y="0" font-family="monospace" font-weight="bold" font-size="36" fill="#00ffff" filter="url(#light-shadow)" text-anchor="middle" dominant-baseline="middle" clip-path="url(#typing-mask)">
      &lt;Hello World /&gt;
    </text>
    
    <!-- The Blinking, Moving Cursor -->
    <text x="-160" y="-3" font-family="monospace" font-weight="bold" font-size="38" fill="#ffffff" text-anchor="middle" dominant-baseline="middle">
      |
      <animate attributeName="x" values="-160; 175; 175" dur="5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="1;0;1" dur="0.7s" repeatCount="indefinite" />
    </text>
  </g>

  <text x="50%" y="60%" font-family="Arial, sans-serif" font-weight="bold" font-size="32" fill="#ffffff" filter="url(#light-shadow)" text-anchor="middle" dominant-baseline="middle">
    👋🏻Yoo, I'm Faizanalam Ansari !
  </text>
  <text x="50%" y="78%" font-family="Arial, sans-serif" font-size="20" fill="#eeeeee" filter="url(#light-shadow)" text-anchor="middle" dominant-baseline="middle">
    MERN Stack | Python Developer
  </text>
</svg>
