<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a1a"/>
      <stop offset="50%" style="stop-color:#0d1b2a"/>
      <stop offset="100%" style="stop-color:#0a0a1a"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0"/>
      <stop offset="40%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="60%" style="stop-color:#7b2fff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#7b2fff;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff"/>
      <stop offset="100%" style="stop-color:#7b2fff"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="860" height="200" fill="url(#bg)" rx="12"/>

  <!-- Grid lines subtle -->
  <g opacity="0.06" stroke="#00d4ff" stroke-width="0.5">
    <line x1="0" y1="40" x2="860" y2="40"/>
    <line x1="0" y1="80" x2="860" y2="80"/>
    <line x1="0" y1="120" x2="860" y2="120"/>
    <line x1="0" y1="160" x2="860" y2="160"/>
    <line x1="100" y1="0" x2="100" y2="200"/>
    <line x1="200" y1="0" x2="200" y2="200"/>
    <line x1="300" y1="0" x2="300" y2="200"/>
    <line x1="400" y1="0" x2="400" y2="200"/>
    <line x1="500" y1="0" x2="500" y2="200"/>
    <line x1="600" y1="0" x2="600" y2="200"/>
    <line x1="700" y1="0" x2="700" y2="200"/>
    <line x1="800" y1="0" x2="800" y2="200"/>
  </g>

  <!-- Floating particles -->
  <circle cx="60" cy="40" r="2" fill="#00d4ff" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="800" cy="160" r="1.5" fill="#7b2fff" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="35" r="2.5" fill="#00d4ff" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.9;0.4" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="140" cy="165" r="1.5" fill="#7b2fff" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="430" cy="20" r="2" fill="#00d4ff" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.9;0.5" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Decorative tooth icon left side (simplified geometric) -->
  <g transform="translate(60, 75)" opacity="0.25" fill="none" stroke="#00d4ff" stroke-width="1.2">
    <path d="M0,0 C-8,-12 -20,-12 -20,0 C-20,15 -12,30 -8,45 C-6,52 -2,52 0,45 C2,52 6,52 8,45 C12,30 20,15 20,0 C20,-12 8,-12 0,0Z"/>
  </g>

  <!-- Decorative circuit lines right -->
  <g opacity="0.12" stroke="#7b2fff" stroke-width="1" fill="none">
    <path d="M780,30 L820,30 L820,60"/>
    <circle cx="780" cy="30" r="3" fill="#7b2fff"/>
    <path d="M800,80 L840,80 L840,50"/>
    <circle cx="840" cy="50" r="3" fill="#7b2fff"/>
  </g>

  <!-- Top accent line animated -->
  <rect x="0" y="0" width="860" height="2" rx="1" fill="url(#lineGrad)" opacity="0.9"/>

  <!-- Bottom accent line -->
  <rect x="0" y="198" width="860" height="2" rx="1" fill="url(#lineGrad)" opacity="0.9"/>

  <!-- Side accent -->
  <rect x="0" y="0" width="3" height="200" fill="#00d4ff" opacity="0.4"/>
  <rect x="857" y="0" width="3" height="200" fill="#7b2fff" opacity="0.4"/>

  <!-- Main name -->
  <text x="430" y="105" font-family="'Segoe UI', Arial, sans-serif" font-size="64" font-weight="900"
        fill="url(#textGrad)" text-anchor="middle" filter="url(#softglow)" letter-spacing="4">
    Herlan Mistas
  </text>

  <!-- Subtitle -->
  <text x="430" y="140" font-family="'Segoe UI', Arial, sans-serif" font-size="15"
        fill="#a0b4c8" text-anchor="middle" letter-spacing="6" opacity="0.85">
    DEVELOPER  ·  ENGINEER  ·  INNOVATOR
  </text>

  <!-- Username tag -->
  <rect x="345" y="152" width="170" height="26" rx="13" fill="#00d4ff" opacity="0.08"/>
  <rect x="345" y="152" width="170" height="26" rx="13" fill="none" stroke="#00d4ff" stroke-width="0.8" opacity="0.4"/>
  <text x="430" y="169" font-family="'Segoe UI', Arial, sans-serif" font-size="13"
        fill="#00d4ff" text-anchor="middle" letter-spacing="2" opacity="0.9">
    @MiStAs27
  </text>

  <!-- Animated scan line -->
  <rect x="0" y="0" width="860" height="3" fill="url(#lineGrad)" opacity="0.15">
    <animateTransform attributeName="transform" type="translate" values="0,0;0,197;0,0" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.15;0.35;0.15" dur="6s" repeatCount="indefinite"/>
  </rect>
</svg>

<div align="center">

<!-- BANNER -->
<img src="./banner.svg" width="100%" alt="Herlan Mistas Banner"/>

<br/>

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=%F0%9F%A6%B7+Construyendo+soluciones+cl%C3%ADnicas+con+c%C3%B3digo;%F0%9F%9A%80+Ingeniería+de+Sistemas+%7C+Bolivia;%F0%9F%92%BB+TypeScript+%7C+C%2B%2B+%7C+React;%F0%9F%8C%B1+Explorando+Flutter+%26+React+Native)](https://git.io/typing-svg)

<br/>

<!-- CONTACT BADGES -->
<a href="mailto:tucorreo@ejemplo.com">
  <img src="https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/tuusuario">
  <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/MiStAs27">
  <img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=MiStAs27&style=flat-square&color=00d4ff&label=Visitas+al+perfil)

</div>

---

## 〔 01 〕Sobre mí

```typescript
const herlan = {
  nombre:     "Herlan Mistas",
  alias:      "@MiStAs27",
  ubicacion:  "Bolivia 🇧🇴",
  rol:        "Estudiante de Ingeniería en Sistemas",
  enfoque:    ["Soluciones clínicas", "Apps multiplataforma", "Ingeniería de software"],
  aprendiendo: ["Flutter", "React Native", "Simulación de sistemas"],
  frase:      "Convirtiendo problemas reales en software que funciona."
};
```

---

## 〔 02 〕Stack tecnológico

<div align="center">

### Lenguajes
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### Frontend & Mobile
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & Datos
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### Herramientas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 〔 03 〕Proyectos destacados

<div align="center">

| 🔷 Proyecto | 📋 Descripción | 🛠️ Stack | 🔗 |
|:------------|:---------------|:---------|:--:|
| **Dentista2** | Sistema completo de gestión para consultorios dentales | TypeScript | [→](https://github.com/MiStAs27/Dentista2) |
| **DentSync Mobile** | App móvil de sincronización clínica en tiempo real | C++ | [→](https://github.com/MiStAs27/dentsync_mobil) |
| **V_CK** *(privado)* | Herramienta interna de automatización empresarial | TypeScript | 🔒 |

</div>

---

## 〔 04 〕Estadísticas

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MiStAs27&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&title_color=00d4ff&icon_color=7b2fff&text_color=a0b4c8&bg_color=0d1117"/>
&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiStAs27&layout=compact&theme=tokyonight&hide_border=true&title_color=00d4ff&text_color=a0b4c8&bg_color=0d1117"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=MiStAs27&theme=tokyonight&hide_border=true&background=0D1117&ring=00d4ff&fire=7b2fff&currStreakLabel=00d4ff" height="160"/>

</div>

---

## 〔 05 〕Contacto

<div align="center">

¿Tienes un proyecto, idea, o propuesta? Estoy abierto a colaborar en soluciones con impacto real.

<br/>

<a href="mailto:tucorreo@ejemplo.com">
  <img src="https://img.shields.io/badge/Escríbeme_por_Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/tuusuario">
  <img src="https://img.shields.io/badge/Conectar_en_LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white"/>
</a>

<br/><br/>

---

<sub>
  Hecho con 💙 desde Bolivia · <a href="https://github.com/MiStAs27">@MiStAs27</a> · 2026
</sub>

</div>
