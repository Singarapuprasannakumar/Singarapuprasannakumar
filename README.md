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
