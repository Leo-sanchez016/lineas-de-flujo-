<svg viewBox="0 0 400 500" xmlns="http://www.w3.org/2000/svg">
  <!-- Vaso de la licuadora -->
  <path d="M100 100 L80 400 L320 400 L300 100 Z" fill="none" stroke="black" stroke-width="2"/>
  
  <!-- Base -->
  <rect x="60" y="400" width="280" height="20" fill="gray"/>
  
  <!-- Eje central -->
  <line x1="200" y1="150" x2="200" y2="380" stroke="black" stroke-width="3"/>
  
  <!-- Cuchillas -->
  <path d="M160 360 L240 360" stroke="black" stroke-width="2"/>
  <path d="M170 340 L230 340" stroke="black" stroke-width="2"/>
  
  <!-- Flujo tangencial (azul) -->
  <path d="M180 200 A50 50 0 1 1 220 200" fill="none" stroke="blue" stroke-width="2" stroke-dasharray="5,5">
    <animateTransform
      attributeName="transform"
      type="rotate"
      from="0 200 200"
      to="360 200 200"
      dur="3s"
      repeatCount="indefinite"/>
  </path>
  
  <!-- Flujo axial (verde) -->
  <path d="M200 150 C220 200 180 250 200 300" fill="none" stroke="green" stroke-width="2" stroke-dasharray="5,5">
    <animate
      attributeName="d"
      values="M200 150 C220 200 180 250 200 300;M200 150 C180 200 220 250 200 300;M200 150 C220 200 180 250 200 300"
      dur="2s"
      repeatCount="indefinite"/>
  </path>
  
  <!-- Flujo radial (rojo) -->
  <path d="M160 250 L240 250" fill="none" stroke="red" stroke-width="2" stroke-dasharray="5,5">
    <animate
      attributeName="d"
      values="M160 250 L240 250;M170 250 L230 250;M160 250 L240 250"
      dur="1s"
      repeatCount="indefinite"/>
  </path>
  
  <!-- Leyenda -->
  <circle cx="50" cy="450" r="5" fill="blue"/>
  <text x="70" y="455" font-size="12">Flujo tangencial</text>
  
  <circle cx="170" cy="450" r="5" fill="green"/>
  <text x="190" y="455" font-size="12">Flujo axial</text>
  
  <circle cx="290" cy="450" r="5" fill="red"/>
  <text x="310" y="455" font-size="12">Flujo radial</text>
</svg>
