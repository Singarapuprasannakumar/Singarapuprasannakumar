<svg width="900" height="1800" viewBox="0 0 900 1800" xmlns="http://www.w3.org/2000/svg" font-family="'Segoe UI', 'JetBrains Mono', monospace">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#0f1923;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1"/>
    </linearGradient>
    <!-- Header gradient -->
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#1f6feb;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#388bfd;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#a371f7;stop-opacity:1"/>
    </linearGradient>
    <!-- Section title gradient -->
    <linearGradient id="sectionGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#58a6ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#a371f7;stop-opacity:1"/>
    </linearGradient>
    <!-- Card gradient -->
    <linearGradient id="cardGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#161b22;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#1c2128;stop-opacity:1"/>
    </linearGradient>
    <!-- Gold gradient -->
    <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f0c040;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ffd700;stop-opacity:1"/>
    </linearGradient>
    <!-- Green gradient -->
    <linearGradient id="greenGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2ea043;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#3fb950;stop-opacity:1"/>
    </linearGradient>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Subtle shadow -->
    <filter id="shadow">
      <feDropShadow dx="0" dy="2" stdDeviation="4" flood-color="#58a6ff" flood-opacity="0.15"/>
    </filter>
    <!-- Clip path for rounded cards -->
    <clipPath id="roundedCard">
      <rect width="860" height="120" rx="10" ry="10"/>
    </clipPath>
    <!-- Animate pulse -->
    <style>
      .pulse { animation: pulse 2s infinite; }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.6; }
      }
      .slide-in { animation: slideIn 0.8s ease-out; }
      @keyframes slideIn {
        from { transform: translateX(-20px); opacity: 0; }
        to { transform: translateX(0); opacity: 1; }
      }
    </style>
  </defs>

  <!-- ═══ MAIN BACKGROUND ═══ -->
  <rect width="900" height="1800" fill="url(#bgGrad)" rx="16" ry="16"/>
  <!-- Outer border glow -->
  <rect width="898" height="1798" x="1" y="1" fill="none" stroke="url(#headerGrad)" stroke-width="1.5" rx="16" ry="16" opacity="0.5"/>

  <!-- ═══ HEADER SECTION ═══ -->
  <rect width="900" height="130" fill="url(#headerGrad)" rx="16" ry="16"/>
  <rect y="114" width="900" height="16" fill="url(#headerGrad)"/>
  <!-- Header diagonal accent -->
  <polygon points="0,0 900,0 900,130 750,130 600,80 0,130" fill="#0d1117" opacity="0.15"/>

  <!-- Name -->
  <text x="450" y="52" text-anchor="middle" font-size="28" font-weight="800" fill="white" filter="url(#glow)" letter-spacing="1">SINGARAPU PRASANNA KUMAR</text>
  <!-- Title -->
  <text x="450" y="80" text-anchor="middle" font-size="13.5" fill="#d2e8ff" letter-spacing="0.5">AI Engineer  •  MERN Stack Developer  •  Software Engineer</text>
  <!-- Contact row -->
  <text x="450" y="104" text-anchor="middle" font-size="11" fill="#a0c4ff">📧 prasannakumar.singarapu@sasi.ac.in  |  📞 +91 63093 77457  |  📍 Andhra Pradesh, India  |  🌐 Open to Remote</text>

  <!-- ═══ IDENTITY CARDS ROW ═══ -->
  <!-- Card 1: Education -->
  <rect x="20" y="145" width="200" height="62" rx="8" fill="url(#cardGrad)" stroke="#1f6feb" stroke-width="1" filter="url(#shadow)"/>
  <rect x="20" y="145" width="4" height="62" rx="2" fill="#1f6feb"/>
  <text x="35" y="163" font-size="9.5" fill="#58a6ff" font-weight="700" letter-spacing="0.5">🎓  EDUCATION</text>
  <text x="35" y="179" font-size="11.5" fill="white" font-weight="600">B.Tech CSE</text>
  <text x="35" y="196" font-size="10" fill="#8b949e">SASI Institute • 2023–2027</text>

  <!-- Card 2: CGPA -->
  <rect x="230" y="145" width="130" height="62" rx="8" fill="url(#cardGrad)" stroke="#2ea043" stroke-width="1" filter="url(#shadow)"/>
  <rect x="230" y="145" width="4" height="62" rx="2" fill="#2ea043"/>
  <text x="245" y="163" font-size="9.5" fill="#3fb950" font-weight="700" letter-spacing="0.5">🎯  CGPA</text>
  <text x="245" y="183" font-size="22" fill="white" font-weight="800">7.8</text>
  <text x="287" y="183" font-size="13" fill="#8b949e">/10</text>

  <!-- Card 3: Experience -->
  <rect x="370" y="145" width="160" height="62" rx="8" fill="url(#cardGrad)" stroke="#a371f7" stroke-width="1" filter="url(#shadow)"/>
  <rect x="370" y="145" width="4" height="62" rx="2" fill="#a371f7"/>
  <text x="385" y="163" font-size="9.5" fill="#a371f7" font-weight="700" letter-spacing="0.5">💼  EXPERIENCE</text>
  <text x="385" y="181" font-size="18" fill="white" font-weight="800">3 Internships</text>
  <text x="385" y="197" font-size="10" fill="#8b949e">YugaYatra • CodeAlpha • Cognifyz</text>

  <!-- Card 4: Status -->
  <rect x="540" y="145" width="160" height="62" rx="8" fill="url(#cardGrad)" stroke="#ffd700" stroke-width="1" filter="url(#shadow)"/>
  <rect x="540" y="145" width="4" height="62" rx="2" fill="#ffd700"/>
  <text x="555" y="163" font-size="9.5" fill="#ffd700" font-weight="700" letter-spacing="0.5">🚀  STATUS</text>
  <text x="555" y="181" font-size="13" fill="white" font-weight="600">Open to Internships</text>
  <text x="555" y="197" font-size="10" fill="#8b949e">Full-time Available 2027</text>

  <!-- Card 5: Location -->
  <rect x="710" y="145" width="170" height="62" rx="8" fill="url(#cardGrad)" stroke="#ff6b6b" stroke-width="1" filter="url(#shadow)"/>
  <rect x="710" y="145" width="4" height="62" rx="2" fill="#ff6b6b"/>
  <text x="725" y="163" font-size="9.5" fill="#ff6b6b" font-weight="700" letter-spacing="0.5">📍  LOCATION</text>
  <text x="725" y="181" font-size="13" fill="white" font-weight="600">Andhra Pradesh</text>
  <text x="725" y="197" font-size="10" fill="#8b949e">India • Remote OK</text>

  <!-- ═══ SECTION: WORK EXPERIENCE ═══ -->
  <text x="30" y="237" font-size="15" font-weight="700" fill="url(#sectionGrad)">💼  Work Experience</text>
  <line x1="30" y1="243" x2="870" y2="243" stroke="#21262d" stroke-width="1"/>

  <!-- Internship 1: YugaYatra -->
  <rect x="20" y="252" width="860" height="78" rx="8" fill="url(#cardGrad)" stroke="#1f6feb" stroke-width="1"/>
  <rect x="20" y="252" width="4" height="78" rx="2" fill="url(#headerGrad)"/>
  <text x="35" y="271" font-size="12.5" fill="white" font-weight="700">Software Developer Intern</text>
  <rect x="255" y="258" width="170" height="16" rx="4" fill="#1f6feb" opacity="0.25"/>
  <text x="265" y="270" font-size="10" fill="#58a6ff" font-weight="600">YugaYatra Retail (OPC) Pvt Ltd</text>
  <rect x="700" y="258" width="168" height="16" rx="4" fill="#2ea043" opacity="0.25"/>
  <text x="710" y="270" font-size="10" fill="#3fb950" font-weight="600">Jan 2026 – May 2026 • Remote</text>
  <text x="35" y="288" font-size="10" fill="#8b949e">▸ Built &amp; maintained 12+ MERN Stack business apps; optimized Freshma.io (performance + UX)</text>
  <text x="35" y="303" font-size="10" fill="#8b949e">▸ Built RESTful APIs for frontend-backend communication; collaborated on feature delivery &amp; deployments</text>
  <text x="35" y="318" font-size="10" fill="#8b949e">Stack:</text>
  <rect x="60" y="308" width="58" height="14" rx="3" fill="#1f6feb" opacity="0.3"/>
  <text x="64" y="319" font-size="9" fill="#58a6ff">React.js</text>
  <rect x="124" y="308" width="56" height="14" rx="3" fill="#2ea043" opacity="0.3"/>
  <text x="128" y="319" font-size="9" fill="#3fb950">Node.js</text>
  <rect x="186" y="308" width="64" height="14" rx="3" fill="#a371f7" opacity="0.3"/>
  <text x="190" y="319" font-size="9" fill="#a371f7">Express.js</text>
  <rect x="256" y="308" width="60" height="14" rx="3" fill="#47a248" opacity="0.3"/>
  <text x="260" y="319" font-size="9" fill="#47a248">MongoDB</text>
  <rect x="322" y="308" width="60" height="14" rx="3" fill="#ff6b6b" opacity="0.3"/>
  <text x="326" y="319" font-size="9" fill="#ff6b6b">REST APIs</text>

  <!-- Internship 2: CodeAlpha -->
  <rect x="20" y="338" width="860" height="65" rx="8" fill="url(#cardGrad)" stroke="#a371f7" stroke-width="1"/>
  <rect x="20" y="338" width="4" height="65" rx="2" fill="#a371f7"/>
  <text x="35" y="357" font-size="12.5" fill="white" font-weight="700">Frontend Development Intern</text>
  <rect x="265" y="344" width="78" height="16" rx="4" fill="#a371f7" opacity="0.25"/>
  <text x="270" y="356" font-size="10" fill="#a371f7" font-weight="600">CodeAlpha</text>
  <rect x="700" y="344" width="168" height="16" rx="4" fill="#a371f7" opacity="0.2"/>
  <text x="710" y="356" font-size="10" fill="#a371f7" font-weight="600">Jul 2025 – Aug 2025 • Remote</text>
  <text x="35" y="374" font-size="10" fill="#8b949e">▸ Built Image Gallery, Calculator, Portfolio, Music Player using HTML, CSS, JS, React.js</text>
  <text x="35" y="389" font-size="10" fill="#8b949e">▸ Applied modern UI/UX principles; optimized frontend performance &amp; prepared tech documentation</text>

  <!-- Internship 3: Cognifyz -->
  <rect x="20" y="411" width="860" height="65" rx="8" fill="url(#cardGrad)" stroke="#ff9800" stroke-width="1"/>
  <rect x="20" y="411" width="4" height="65" rx="2" fill="#ff9800"/>
  <text x="35" y="430" font-size="12.5" fill="white" font-weight="700">Web Developer Intern</text>
  <rect x="223" y="417" width="138" height="16" rx="4" fill="#ff9800" opacity="0.25"/>
  <text x="228" y="429" font-size="10" fill="#ff9800" font-weight="600">Cognifyz Technologies</text>
  <rect x="700" y="417" width="168" height="16" rx="4" fill="#ff9800" opacity="0.2"/>
  <text x="710" y="429" font-size="10" fill="#ff9800" font-weight="600">May 2025 – Jun 2025 • Remote</text>
  <text x="35" y="447" font-size="10" fill="#8b949e">▸ Designed responsive web interfaces with Bootstrap, HTML, CSS, JS</text>
  <text x="35" y="462" font-size="10" fill="#8b949e">▸ Improved cross-browser compatibility via media query optimization; created technical documentation</text>

  <!-- ═══ SECTION: TECH STACK ═══ -->
  <text x="30" y="503" font-size="15" font-weight="700" fill="url(#sectionGrad)">⚡  Tech Stack</text>
  <line x1="30" y1="509" x2="870" y2="509" stroke="#21262d" stroke-width="1"/>

  <!-- Languages row -->
  <text x="30" y="527" font-size="10" fill="#8b949e" font-weight="600">LANGUAGES</text>
  <!-- Python -->
  <rect x="110" y="514" width="64" height="18" rx="4" fill="#3776AB" opacity="0.85"/>
  <text x="142" y="527" text-anchor="middle" font-size="10" fill="white" font-weight="600">Python</text>
  <!-- JS -->
  <rect x="180" y="514" width="82" height="18" rx="4" fill="#F7DF1E" opacity="0.9"/>
  <text x="221" y="527" text-anchor="middle" font-size="10" fill="#000" font-weight="600">JavaScript</text>
  <!-- Java -->
  <rect x="268" y="514" width="48" height="18" rx="4" fill="#ED8B00" opacity="0.85"/>
  <text x="292" y="527" text-anchor="middle" font-size="10" fill="white" font-weight="600">Java</text>
  <!-- C -->
  <rect x="322" y="514" width="28" height="18" rx="4" fill="#00599C" opacity="0.85"/>
  <text x="336" y="527" text-anchor="middle" font-size="10" fill="white" font-weight="600">C</text>
  <!-- SQL -->
  <rect x="356" y="514" width="38" height="18" rx="4" fill="#4479A1" opacity="0.85"/>
  <text x="375" y="527" text-anchor="middle" font-size="10" fill="white" font-weight="600">SQL</text>

  <!-- Frontend row -->
  <text x="30" y="549" font-size="10" fill="#8b949e" font-weight="600">FRONTEND</text>
  <rect x="110" y="536" width="60" height="18" rx="4" fill="#20232A" stroke="#61DAFB" stroke-width="0.8"/>
  <text x="140" y="549" text-anchor="middle" font-size="10" fill="#61DAFB" font-weight="600">React.js</text>
  <rect x="176" y="536" width="44" height="18" rx="4" fill="#E34F26" opacity="0.85"/>
  <text x="198" y="549" text-anchor="middle" font-size="10" fill="white" font-weight="600">HTML5</text>
  <rect x="226" y="536" width="38" height="18" rx="4" fill="#1572B6" opacity="0.85"/>
  <text x="245" y="549" text-anchor="middle" font-size="10" fill="white" font-weight="600">CSS3</text>
  <rect x="270" y="536" width="72" height="18" rx="4" fill="#06B6D4" opacity="0.85"/>
  <text x="306" y="549" text-anchor="middle" font-size="10" fill="white" font-weight="600">Tailwind CSS</text>
  <rect x="348" y="536" width="70" height="18" rx="4" fill="#7952B3" opacity="0.85"/>
  <text x="383" y="549" text-anchor="middle" font-size="10" fill="white" font-weight="600">Bootstrap</text>
  <rect x="424" y="536" width="36" height="18" rx="4" fill="#646CFF" opacity="0.85"/>
  <text x="442" y="549" text-anchor="middle" font-size="10" fill="white" font-weight="600">Vite</text>

  <!-- Backend row -->
  <text x="30" y="571" font-size="10" fill="#8b949e" font-weight="600">BACKEND</text>
  <rect x="110" y="558" width="56" height="18" rx="4" fill="#339933" opacity="0.85"/>
  <text x="138" y="571" text-anchor="middle" font-size="10" fill="white" font-weight="600">Node.js</text>
  <rect x="172" y="558" width="70" height="18" rx="4" fill="#21262d" stroke="#555" stroke-width="0.8"/>
  <text x="207" y="571" text-anchor="middle" font-size="10" fill="#ccc" font-weight="600">Express.js</text>
  <rect x="248" y="558" width="72" height="18" rx="4" fill="#ff6b6b" opacity="0.8"/>
  <text x="284" y="571" text-anchor="middle" font-size="10" fill="white" font-weight="600">REST APIs</text>

  <!-- Database row -->
  <text x="30" y="594" font-size="10" fill="#8b949e" font-weight="600">DATABASE</text>
  <rect x="110" y="581" width="66" height="18" rx="4" fill="#47A248" opacity="0.85"/>
  <text x="143" y="594" text-anchor="middle" font-size="10" fill="white" font-weight="600">MongoDB</text>
  <rect x="182" y="581" width="70" height="18" rx="4" fill="#880000" opacity="0.85"/>
  <text x="217" y="594" text-anchor="middle" font-size="10" fill="white" font-weight="600">Mongoose</text>

  <!-- AI/ML row -->
  <text x="30" y="617" font-size="10" fill="#8b949e" font-weight="600">AI / ML</text>
  <rect x="110" y="604" width="76" height="18" rx="4" fill="#FF6F00" opacity="0.85"/>
  <text x="148" y="617" text-anchor="middle" font-size="10" fill="white" font-weight="600">TensorFlow</text>
  <rect x="192" y="604" width="84" height="18" rx="4" fill="#412991" opacity="0.85"/>
  <text x="234" y="617" text-anchor="middle" font-size="10" fill="white" font-weight="600">Generative AI</text>
  <rect x="282" y="604" width="110" height="18" rx="4" fill="#4285F4" opacity="0.85"/>
  <text x="337" y="617" text-anchor="middle" font-size="10" fill="white" font-weight="600">Prompt Engineering</text>

  <!-- Tools row -->
  <text x="30" y="639" font-size="10" fill="#8b949e" font-weight="600">TOOLS</text>
  <rect x="110" y="626" width="34" height="18" rx="4" fill="#F05032" opacity="0.85"/>
  <text x="127" y="639" text-anchor="middle" font-size="10" fill="white" font-weight="600">Git</text>
  <rect x="150" y="626" width="54" height="18" rx="4" fill="#181717" stroke="#555" stroke-width="0.8"/>
  <text x="177" y="639" text-anchor="middle" font-size="10" fill="white" font-weight="600">GitHub</text>
  <rect x="210" y="626" width="56" height="18" rx="4" fill="#007ACC" opacity="0.85"/>
  <text x="238" y="639" text-anchor="middle" font-size="10" fill="white" font-weight="600">VS Code</text>
  <rect x="272" y="626" width="56" height="18" rx="4" fill="#FF6C37" opacity="0.85"/>
  <text x="300" y="639" text-anchor="middle" font-size="10" fill="white" font-weight="600">Postman</text>
  <rect x="334" y="626" width="46" height="18" rx="4" fill="#00C4CC" opacity="0.85"/>
  <text x="357" y="639" text-anchor="middle" font-size="10" fill="white" font-weight="600">Canva</text>

  <!-- Core CS row -->
  <text x="30" y="661" font-size="10" fill="#8b949e" font-weight="600">CORE CS</text>
  <rect x="110" y="648" width="38" height="18" rx="4" fill="#0A66C2" opacity="0.85"/>
  <text x="129" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">DSA</text>
  <rect x="154" y="648" width="48" height="18" rx="4" fill="#4479A1" opacity="0.85"/>
  <text x="178" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">DBMS</text>
  <rect x="208" y="648" width="24" height="18" rx="4" fill="#6A1B9A" opacity="0.85"/>
  <text x="220" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">OS</text>
  <rect x="238" y="648" width="36" height="18" rx="4" fill="#FF6B6B" opacity="0.85"/>
  <text x="256" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">OOP</text>
  <rect x="280" y="648" width="34" height="18" rx="4" fill="#3fb950" opacity="0.85"/>
  <text x="297" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">CN</text>
  <rect x="320" y="648" width="24" height="18" rx="4" fill="#ff9800" opacity="0.85"/>
  <text x="332" y="661" text-anchor="middle" font-size="10" fill="white" font-weight="600">SE</text>

  <!-- ═══ SECTION: PROJECTS ═══ -->
  <text x="30" y="701" font-size="15" font-weight="700" fill="url(#sectionGrad)">🚀  Featured Projects</text>
  <line x1="30" y1="707" x2="870" y2="707" stroke="#21262d" stroke-width="1"/>

  <!-- Project 1: MeetMind -->
  <rect x="20" y="716" width="418" height="88" rx="8" fill="url(#cardGrad)" stroke="#58a6ff" stroke-width="1"/>
  <rect x="20" y="716" width="418" height="4" rx="2" fill="url(#headerGrad)"/>
  <text x="34" y="736" font-size="12" fill="white" font-weight="700">💬 MeetMind</text>
  <rect x="130" y="722" width="160" height="14" rx="3" fill="#1f6feb" opacity="0.25"/>
  <text x="210" y="733" text-anchor="middle" font-size="9" fill="#58a6ff">React.js • Node.js • Express.js • MongoDB</text>
  <text x="34" y="752" font-size="10" fill="#8b949e">▸ Collaborative discussion platform for structured</text>
  <text x="34" y="765" font-size="10" fill="#8b949e">   team communication &amp; decision workflows</text>
  <text x="34" y="778" font-size="10" fill="#8b949e">▸ Real-time sync • Role-based interactions • Scalable backend</text>
  <text x="34" y="794" font-size="9" fill="#3fb950">✓ Full-Stack  ✓ Real-Time  ✓ Role-Based</text>

  <!-- Project 2: RestaurantFlow -->
  <rect x="462" y="716" width="418" height="88" rx="8" fill="url(#cardGrad)" stroke="#a371f7" stroke-width="1"/>
  <rect x="462" y="716" width="418" height="4" rx="2" fill="#a371f7"/>
  <text x="476" y="736" font-size="12" fill="white" font-weight="700">🍽️ RestaurantFlow</text>
  <rect x="600" y="722" width="140" height="14" rx="3" fill="#a371f7" opacity="0.25"/>
  <text x="670" y="733" text-anchor="middle" font-size="9" fill="#a371f7">React.js • Vite • Context API</text>
  <text x="476" y="752" font-size="10" fill="#8b949e">▸ Restaurant workflow management system</text>
  <text x="476" y="765" font-size="10" fill="#8b949e">   with complete order lifecycle management</text>
  <text x="476" y="778" font-size="10" fill="#8b949e">▸ Real-time state sync • Multi-role operations • Kitchen WF</text>
  <text x="476" y="794" font-size="9" fill="#3fb950">✓ Multi-Role  ✓ Real-Time Sync  ✓ Full Lifecycle</text>

  <!-- Project 3: Weather App -->
  <rect x="20" y="812" width="418" height="88" rx="8" fill="url(#cardGrad)" stroke="#3fb950" stroke-width="1"/>
  <rect x="20" y="812" width="418" height="4" rx="2" fill="#2ea043"/>
  <text x="34" y="832" font-size="12" fill="white" font-weight="700">🌤️ Weather App</text>
  <rect x="140" y="818" width="220" height="14" rx="3" fill="#2ea043" opacity="0.25"/>
  <text x="250" y="829" text-anchor="middle" font-size="9" fill="#3fb950">React.js • Node.js • Express.js • MongoDB • OpenWeather</text>
  <text x="34" y="848" font-size="10" fill="#8b949e">▸ Full-stack weather app with real-time OpenWeather API</text>
  <text x="34" y="861" font-size="10" fill="#8b949e">▸ Search, validation, error handling &amp; MongoDB persistence</text>
  <text x="34" y="874" font-size="10" fill="#8b949e">▸ Responsive React UI + Node.js/Express backend</text>
  <text x="34" y="890" font-size="9" fill="#3fb950">✓ Full-Stack  ✓ API Integration  ✓ Data Persistence</text>

  <!-- Project 4: Gmail Verifier -->
  <rect x="462" y="812" width="418" height="88" rx="8" fill="url(#cardGrad)" stroke="#ff6b6b" stroke-width="1"/>
  <rect x="462" y="812" width="418" height="4" rx="2" fill="#ff6b6b"/>
  <text x="476" y="832" font-size="12" fill="white" font-weight="700">📧 Gmail Verifier</text>
  <rect x="590" y="818" width="138" height="14" rx="3" fill="#ff6b6b" opacity="0.25"/>
  <text x="659" y="829" text-anchor="middle" font-size="9" fill="#ff6b6b">Node.js • JavaScript • REST APIs</text>
  <text x="476" y="848" font-size="10" fill="#8b949e">▸ Node.js email verification tool to detect fake/invalid</text>
  <text x="476" y="861" font-size="10" fill="#8b949e">   Gmail addresses with MX record verification</text>
  <text x="476" y="874" font-size="10" fill="#8b949e">▸ Regex validation • Automated workflows • Full documentation</text>
  <text x="476" y="890" font-size="9" fill="#3fb950">✓ Backend  ✓ Validation Engine  ✓ REST API</text>

  <!-- ═══ SECTION: COMPETITIVE PROGRAMMING ═══ -->
  <text x="30" y="933" font-size="15" font-weight="700" fill="url(#sectionGrad)">🔢  Competitive Programming</text>
  <line x1="30" y1="939" x2="870" y2="939" stroke="#21262d" stroke-width="1"/>

  <!-- CodeChef card -->
  <rect x="20" y="948" width="270" height="100" rx="8" fill="url(#cardGrad)" stroke="#5B4638" stroke-width="1.5"/>
  <rect x="20" y="948" width="270" height="4" rx="2" fill="#5B4638"/>
  <text x="155" y="970" text-anchor="middle" font-size="12" fill="white" font-weight="700">CodeChef</text>
  <text x="155" y="990" text-anchor="middle" font-size="20" fill="#ffd700">⭐⭐⭐</text>
  <text x="155" y="1010" text-anchor="middle" font-size="13" fill="#ffd700" font-weight="700">3-Star Rating</text>
  <text x="155" y="1027" text-anchor="middle" font-size="10" fill="#8b949e">3800+ Problems Solved</text>
  <text x="155" y="1040" text-anchor="middle" font-size="9" fill="#8b949e">DSA • DP • Graphs • Trees</text>

  <!-- LeetCode card -->
  <rect x="310" y="948" width="270" height="100" rx="8" fill="url(#cardGrad)" stroke="#FFA116" stroke-width="1.5"/>
  <rect x="310" y="948" width="270" height="4" rx="2" fill="#FFA116"/>
  <text x="445" y="970" text-anchor="middle" font-size="12" fill="white" font-weight="700">LeetCode</text>
  <text x="445" y="990" text-anchor="middle" font-size="20" fill="#FFA116">💻</text>
  <text x="445" y="1010" text-anchor="middle" font-size="13" fill="#FFA116" font-weight="700">Active Solver</text>
  <text x="445" y="1027" text-anchor="middle" font-size="10" fill="#8b949e">150+ Problems Solved</text>
  <text x="445" y="1040" text-anchor="middle" font-size="9" fill="#8b949e">Medium / Hard Focus • DSA</text>

  <!-- HackerRank card -->
  <rect x="600" y="948" width="280" height="100" rx="8" fill="url(#cardGrad)" stroke="#2EC866" stroke-width="1.5"/>
  <rect x="600" y="948" width="280" height="4" rx="2" fill="#2EC866"/>
  <text x="740" y="970" text-anchor="middle" font-size="12" fill="white" font-weight="700">HackerRank</text>
  <text x="740" y="990" text-anchor="middle" font-size="20" fill="#2EC866">⭐⭐⭐⭐</text>
  <text x="740" y="1010" text-anchor="middle" font-size="13" fill="#2EC866" font-weight="700">4-Star Rating</text>
  <text x="740" y="1027" text-anchor="middle" font-size="10" fill="#8b949e">Consistent Performer</text>
  <text x="740" y="1040" text-anchor="middle" font-size="9" fill="#8b949e">Programming Challenges</text>

  <!-- Algo strengths -->
  <text x="30" y="1070" font-size="10" fill="#8b949e" font-weight="600">ALGORITHMIC STRENGTHS:</text>
  <rect x="230" y="1057" width="82" height="17" rx="4" fill="#0A66C2" opacity="0.85"/>
  <text x="271" y="1069" text-anchor="middle" font-size="9" fill="white" font-weight="600">DSA</text>
  <rect x="318" y="1057" width="104" height="17" rx="4" fill="#181717" stroke="#555" stroke-width="0.6"/>
  <text x="370" y="1069" text-anchor="middle" font-size="9" fill="#ccc" font-weight="600">Dynamic Prog.</text>
  <rect x="428" y="1057" width="100" height="17" rx="4" fill="#6A1B9A" opacity="0.85"/>
  <text x="478" y="1069" text-anchor="middle" font-size="9" fill="white" font-weight="600">Graph Algorithms</text>
  <rect x="534" y="1057" width="96" height="17" rx="4" fill="#FF6B6B" opacity="0.8"/>
  <text x="582" y="1069" text-anchor="middle" font-size="9" fill="white" font-weight="600">Trees &amp; Recursion</text>
  <rect x="636" y="1057" width="80" height="17" rx="4" fill="#4CAF50" opacity="0.85"/>
  <text x="676" y="1069" text-anchor="middle" font-size="9" fill="white" font-weight="600">Binary Search</text>
  <rect x="722" y="1057" width="88" height="17" rx="4" fill="#FF9800" opacity="0.85"/>
  <text x="766" y="1069" text-anchor="middle" font-size="9" fill="white" font-weight="600">Greedy Alg.</text>

  <!-- ═══ SECTION: ACHIEVEMENTS ═══ -->
  <text x="30" y="1107" font-size="15" font-weight="700" fill="url(#sectionGrad)">🏆  Achievements</text>
  <line x1="30" y1="1113" x2="870" y2="1113" stroke="#21262d" stroke-width="1"/>

  <!-- SIH 2025 -->
  <rect x="20" y="1122" width="270" height="80" rx="8" fill="url(#cardGrad)" stroke="#ffd700" stroke-width="1.5"/>
  <text x="155" y="1144" text-anchor="middle" font-size="22">🏆</text>
  <text x="155" y="1163" text-anchor="middle" font-size="11" fill="white" font-weight="700">Smart India Hackathon 2025</text>
  <text x="155" y="1178" text-anchor="middle" font-size="10" fill="#ffd700" font-weight="600">National Finalist</text>
  <text x="155" y="1193" text-anchor="middle" font-size="9" fill="#8b949e">Selected among thousands nationwide</text>

  <!-- Prayatna 2.0 -->
  <rect x="310" y="1122" width="270" height="80" rx="8" fill="url(#cardGrad)" stroke="#c0c0c0" stroke-width="1.5"/>
  <text x="445" y="1144" text-anchor="middle" font-size="22">🥈</text>
  <text x="445" y="1163" text-anchor="middle" font-size="11" fill="white" font-weight="700">Hackathon Prayatna 2.0</text>
  <text x="445" y="1178" text-anchor="middle" font-size="10" fill="#c0c0c0" font-weight="600">Runner-Up (50+ Teams)</text>
  <text x="445" y="1193" text-anchor="middle" font-size="9" fill="#8b949e">Innovative solution, 2nd place</text>

  <!-- Mentor + ACM -->
  <rect x="600" y="1122" width="280" height="80" rx="8" fill="url(#cardGrad)" stroke="#3fb950" stroke-width="1.5"/>
  <text x="740" y="1144" text-anchor="middle" font-size="22">👨‍🏫</text>
  <text x="740" y="1163" text-anchor="middle" font-size="11" fill="white" font-weight="700">Student Mentor + ACM Organizer</text>
  <text x="740" y="1178" text-anchor="middle" font-size="10" fill="#3fb950" font-weight="600">60+ Students Mentored</text>
  <text x="740" y="1193" text-anchor="middle" font-size="9" fill="#8b949e">ACM Hackathon — 100+ Participants</text>

  <!-- ═══ SECTION: EDUCATION ═══ -->
  <text x="30" y="1233" font-size="15" font-weight="700" fill="url(#sectionGrad)">🎓  Education</text>
  <line x1="30" y1="1239" x2="870" y2="1239" stroke="#21262d" stroke-width="1"/>

  <!-- B.Tech -->
  <rect x="20" y="1248" width="860" height="52" rx="8" fill="url(#cardGrad)" stroke="#58a6ff" stroke-width="1"/>
  <rect x="20" y="1248" width="4" height="52" rx="2" fill="url(#headerGrad)"/>
  <text x="35" y="1267" font-size="12" fill="white" font-weight="700">B.Tech — Computer Science &amp; Engineering</text>
  <rect x="560" y="1253" width="156" height="15" rx="4" fill="#1f6feb" opacity="0.25"/>
  <text x="638" y="1264" text-anchor="middle" font-size="9.5" fill="#58a6ff" font-weight="600">2023 – 2027 (Expected)</text>
  <rect x="726" y="1253" width="144" height="15" rx="4" fill="#2ea043" opacity="0.25"/>
  <text x="798" y="1264" text-anchor="middle" font-size="9.5" fill="#3fb950" font-weight="600">CGPA: 7.8 / 10</text>
  <text x="35" y="1283" font-size="10" fill="#8b949e">Sasi Institute of Technology &amp; Engineering, Tadepalligudem  |  Coursework: DSA • DBMS • OS • CN • OOP • SE</text>

  <!-- Intermediate -->
  <rect x="20" y="1308" width="418" height="40" rx="8" fill="url(#cardGrad)" stroke="#a371f7" stroke-width="1"/>
  <rect x="20" y="1308" width="4" height="40" rx="2" fill="#a371f7"/>
  <text x="35" y="1323" font-size="11" fill="white" font-weight="600">Intermediate (MPC)</text>
  <text x="35" y="1339" font-size="10" fill="#8b949e">Sri Chaitanya Junior College  |  2021–2023  |  Score: 634/1000</text>

  <!-- Class X -->
  <rect x="462" y="1308" width="418" height="40" rx="8" fill="url(#cardGrad)" stroke="#3fb950" stroke-width="1"/>
  <rect x="462" y="1308" width="4" height="40" rx="2" fill="#3fb950"/>
  <text x="477" y="1323" font-size="11" fill="white" font-weight="600">Secondary School (Class X)</text>
  <text x="477" y="1339" font-size="10" fill="#8b949e">Stella E.M. School  |  2020–2021  |  Score: 532/600</text>

  <!-- ═══ SECTION: CERTIFICATIONS ═══ -->
  <text x="30" y="1389" font-size="15" font-weight="700" fill="url(#sectionGrad)">📜  Certifications</text>
  <line x1="30" y1="1395" x2="870" y2="1395" stroke="#21262d" stroke-width="1"/>

  <!-- Cert 1 -->
  <rect x="20" y="1404" width="200" height="66" rx="8" fill="url(#cardGrad)" stroke="#ffd700" stroke-width="1"/>
  <text x="120" y="1424" text-anchor="middle" font-size="18">🏆</text>
  <text x="120" y="1440" text-anchor="middle" font-size="10" fill="white" font-weight="600">SIH 2025</text>
  <text x="120" y="1454" text-anchor="middle" font-size="9" fill="#ffd700">Final Participation</text>
  <text x="120" y="1465" text-anchor="middle" font-size="9" fill="#8b949e">2025</text>

  <!-- Cert 2 -->
  <rect x="230" y="1404" width="200" height="66" rx="8" fill="url(#cardGrad)" stroke="#0077B5" stroke-width="1"/>
  <text x="330" y="1424" text-anchor="middle" font-size="18">🐍</text>
  <text x="330" y="1440" text-anchor="middle" font-size="10" fill="white" font-weight="600">Data Structures in Python</text>
  <text x="330" y="1454" text-anchor="middle" font-size="9" fill="#0077B5">Infosys Springboard</text>
  <text x="330" y="1465" text-anchor="middle" font-size="9" fill="#8b949e">2025</text>

  <!-- Cert 3 -->
  <rect x="440" y="1404" width="200" height="66" rx="8" fill="url(#cardGrad)" stroke="#5B4638" stroke-width="1"/>
  <text x="540" y="1424" text-anchor="middle" font-size="18">🏗️</text>
  <text x="540" y="1440" text-anchor="middle" font-size="10" fill="white" font-weight="600">OOP in Python</text>
  <text x="540" y="1454" text-anchor="middle" font-size="9" fill="#5B4638">CodeChef</text>
  <text x="540" y="1465" text-anchor="middle" font-size="9" fill="#8b949e">2025</text>

  <!-- Cert 4 -->
  <rect x="650" y="1404" width="230" height="66" rx="8" fill="url(#cardGrad)" stroke="#054ADA" stroke-width="1"/>
  <text x="765" y="1424" text-anchor="middle" font-size="18">🗄️</text>
  <text x="765" y="1440" text-anchor="middle" font-size="10" fill="white" font-weight="600">SQL Relational DB 101</text>
  <text x="765" y="1454" text-anchor="middle" font-size="9" fill="#054ADA">IBM Cognitive Class</text>
  <text x="765" y="1465" text-anchor="middle" font-size="9" fill="#8b949e">2025</text>

  <!-- ═══ SECTION: CURRENTLY LEARNING ═══ -->
  <text x="30" y="1500" font-size="15" font-weight="700" fill="url(#sectionGrad)">📚  Currently Learning</text>
  <line x1="30" y1="1506" x2="870" y2="1506" stroke="#21262d" stroke-width="1"/>

  <!-- Progress bars -->
  <!-- MERN Stack -->
  <text x="30" y="1527" font-size="10.5" fill="#ccc">MERN Stack</text>
  <rect x="170" y="1515" width="550" height="14" rx="6" fill="#21262d"/>
  <rect x="170" y="1515" width="522" height="14" rx="6" fill="url(#headerGrad)"/>
  <text x="730" y="1527" font-size="10" fill="#58a6ff" font-weight="700">95%</text>

  <!-- DSA -->
  <text x="30" y="1547" font-size="10.5" fill="#ccc">DSA</text>
  <rect x="170" y="1535" width="550" height="14" rx="6" fill="#21262d"/>
  <rect x="170" y="1535" width="440" height="14" rx="6" fill="#a371f7" opacity="0.85"/>
  <text x="730" y="1547" font-size="10" fill="#a371f7" font-weight="700">80%</text>

  <!-- AI/ML -->
  <text x="30" y="1567" font-size="10.5" fill="#ccc">AI / ML</text>
  <rect x="170" y="1555" width="550" height="14" rx="6" fill="#21262d"/>
  <rect x="170" y="1555" width="330" height="14" rx="6" fill="#FF6F00" opacity="0.85"/>
  <text x="730" y="1567" font-size="10" fill="#FF6F00" font-weight="700">60%</text>

  <!-- System Design -->
  <text x="30" y="1587" font-size="10.5" fill="#ccc">System Design</text>
  <rect x="170" y="1575" width="550" height="14" rx="6" fill="#21262d"/>
  <rect x="170" y="1575" width="275" height="14" rx="6" fill="#2EC866" opacity="0.85"/>
  <text x="730" y="1587" font-size="10" fill="#2EC866" font-weight="700">50%</text>

  <!-- DevOps -->
  <text x="30" y="1607" font-size="10.5" fill="#ccc">DevOps / Cloud</text>
  <rect x="170" y="1595" width="550" height="14" rx="6" fill="#21262d"/>
  <rect x="170" y="1595" width="220" height="14" rx="6" fill="#58a6ff" opacity="0.6"/>
  <text x="730" y="1607" font-size="10" fill="#58a6ff" font-weight="700">40%</text>

  <!-- ═══ FOOTER ═══ -->
  <rect x="0" y="1640" width="900" height="160" rx="16" fill="url(#headerGrad)" opacity="0.12"/>
  <rect x="0" y="1636" width="900" height="164" rx="16" fill="none" stroke="url(#headerGrad)" stroke-width="0.5" opacity="0.4"/>

  <!-- Links row -->
  <text x="450" y="1665" text-anchor="middle" font-size="13" fill="#8b949e">🌐 Connect With Me</text>

  <!-- Portfolio pill -->
  <rect x="40" y="1675" width="185" height="24" rx="6" fill="#1f6feb" opacity="0.25"/>
  <rect x="40" y="1675" width="185" height="24" rx="6" fill="none" stroke="#1f6feb" stroke-width="0.8"/>
  <text x="133" y="1691" text-anchor="middle" font-size="10" fill="#58a6ff" font-weight="600">🌐 spkportfolio.netlify.app</text>

  <!-- LinkedIn pill -->
  <rect x="235" y="1675" width="190" height="24" rx="6" fill="#0077B5" opacity="0.25"/>
  <rect x="235" y="1675" width="190" height="24" rx="6" fill="none" stroke="#0077B5" stroke-width="0.8"/>
  <text x="330" y="1691" text-anchor="middle" font-size="10" fill="#0077B5" font-weight="600">💼 linkedin.com/in/prasanna-kumar-singarapu</text>

  <!-- GitHub pill -->
  <rect x="435" y="1675" width="195" height="24" rx="6" fill="#333" opacity="0.5"/>
  <rect x="435" y="1675" width="195" height="24" rx="6" fill="none" stroke="#555" stroke-width="0.8"/>
  <text x="532" y="1691" text-anchor="middle" font-size="10" fill="#ccc" font-weight="600">🐙 github.com/Singarapuprasannakumar</text>

  <!-- Email pill -->
  <rect x="640" y="1675" width="220" height="24" rx="6" fill="#EA4335" opacity="0.2"/>
  <rect x="640" y="1675" width="220" height="24" rx="6" fill="none" stroke="#EA4335" stroke-width="0.8"/>
  <text x="750" y="1691" text-anchor="middle" font-size="10" fill="#EA4335" font-weight="600">✉️ prasannakumar.singarapu@sasi.ac.in</text>

  <!-- Divider -->
  <line x1="40" y1="1712" x2="860" y2="1712" stroke="#21262d" stroke-width="1"/>

  <!-- Mindset quote -->
  <text x="450" y="1735" text-anchor="middle" font-size="12" fill="#8b949e" font-style="italic">"Every expert was once a beginner. Every pro was once an amateur."</text>
  <text x="450" y="1754" text-anchor="middle" font-size="13" fill="url(#sectionGrad)" font-weight="700">Learn. Build. Ship. Repeat. 🚀</text>

  <!-- Generated label -->
  <text x="450" y="1778" text-anchor="middle" font-size="9" fill="#30363d">Singarapu Prasanna Kumar • AI Engineer • MERN Stack Developer • Software Engineer</text>

</svg>
