<svg xmlns="http://www.w3.org/2000/svg" width="600" height="200">
  <!-- Animated background (a moving gradient here, could also be a GIF pattern) -->
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#ff00cc">
        <animate attributeName="stop-color" values="#ff00cc;#3333ff;#ff00cc" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#3333ff">
        <animate attributeName="stop-color" values="#3333ff;#ff00cc;#3333ff" dur="5s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#grad)" />

  <!-- Selectable text -->
  <a href="https://example.com" target="_blank">
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-size="30" fill="white" font-family="sans-serif">
      Click Me!
    </text>
  </a>
</svg>