<!-- README.md -->

<p align="center">
  <img src="PROFILE_PIC_URL" alt="profile" width="140" style="border-radius:50%;"/>
</p>

<p align="center">
  <!-- Inline SVG: animated name (typing + shine) -->
  <svg xmlns="http://www.w3.org/2000/svg" width="100%" height="70" viewBox="0 0 800 70" preserveAspectRatio="xMidYMid meet">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0%" stop-color="#7ee8fa"/>
        <stop offset="50%" stop-color="#6576ff"/>
        <stop offset="100%" stop-color="#9b59ff"/>
      </linearGradient>
      <mask id="m">
        <rect width="100%" height="100%" fill="white"/>
        <!-- "typing" mask -->
        <rect id="caret" x="0" y="0" width="6" height="70" fill="black">
          <animate attributeName="x" from="0" to="100%" dur="2.6s" begin="0s" repeatCount="indefinite" />
        </rect>
      </mask>
    </defs>

    <!-- Background rounded bar -->
    <rect x="0" y="8" rx="14" ry="14" width="100%" height="54" fill="#0b1020" opacity="0.06"/>

    <!-- Name text with gradient fill -->
    <text id="name" x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-family="Segoe UI, Roboto, Arial, sans-serif" font-size="36" fill="url(#g)" >
      YOUR NAME
    </text>

    <!-- shine overlay that moves -->
    <rect x="-40%" y="0" width="40%" height="100%" fill="white" opacity="0.12">
      <animate attributeName="x" from="-40%" to="140%" dur="3.2s" repeatCount="indefinite" />
    </rect>

    <!-- small "typing" reveal effect (clip-path) -->
    <g mask="url(#m)">
      <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
            font-family="Segoe UI, Roboto, Arial, sans-serif" font-size="36" fill="#ffffff" opacity="0.03">
        YOUR NAME
      </text>
    </g>
  </svg>
</p>

<p align="center">
  <sub>Hi! I make stuff. — <b>YOUR ROLE / TAGLINE</b></sub>
</p>

