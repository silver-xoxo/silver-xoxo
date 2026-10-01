<div align="center">

<!-- Elegant Cursive SVG Title Banner -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 850 140" width="100%" height="140">
  <defs>
    <linearGradient id="crimsonGlow" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="45%" stop-color="#ffd5dc"/>
      <stop offset="85%" stop-color="#ff2a51"/>
      <stop offset="100%" stop-color="#b80c2e"/>
    </linearGradient>
    <filter id="neonBlur" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <style>
    .cursive-name {
      font-family: 'Brush Script MT', 'Great Vibes', 'Dancing Script', 'Segoe Script', cursive, sans-serif;
      font-size: 58px;
      font-weight: 500;
      letter-spacing: 2px;
      fill: url(#crimsonGlow);
      filter: url(#neonBlur);
    }
    .sub-cursive {
      font-family: 'Snell Roundhand', 'Brush Script MT', 'Dancing Script', 'Segoe Script', cursive, sans-serif;
      font-size: 23px;
      font-style: italic;
      fill: #a2a8ba;
      letter-spacing: 1.5px;
    }
  </style>
  <text x="50%" y="62" text-anchor="middle" class="cursive-name">Armaan Nain</text>
  <text x="50%" y="108" text-anchor="middle" class="sub-cursive">silver  •  exploit research &amp; binary elegance</text>
</svg>

<p align="center">
  <a href="https://silversec.in"><img src="https://img.shields.io/badge/Research_Garden-silversec.in-ff2a51?style=for-the-badge&logo=firefoxbrowser&logoColor=white" height="28"/></a>
  <a href="https://silversec.in"><img src="https://img.shields.io/badge/Accreditation-OSCP-0e1017?style=for-the-badge&logo=offensive-security&logoColor=ff2a51" height="28"/></a>
  <a href="https://linkedin.com/in/armaan-nain"><img src="https://img.shields.io/badge/LinkedIn-Armaan_Nain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="28"/></a>
  <a href="mailto:armaan.nain@icloud.com"><img src="https://img.shields.io/badge/Direct-armaan.nain@icloud.com-161822?style=for-the-badge&logo=icloud&logoColor=white" height="28"/></a>
</p>

<p align="center">
  <i>A quiet sanctuary dedicated to the craft of exploit development, low-level architecture, and security research.</i>
</p>

</div>

---

### *The Journey & Craft*

> *"Simplicity is about subtracting the obvious and adding the meaningful."*

I am an offensive security researcher spending my days tracing assembly routines, dissecting memory structures, and mapping system internals. This GitHub profile reflects the engine room behind [**silversec.in**](https://silversec.in)—a living digital garden where experiments, working theses, and deep technical notes coalesce into structured research.

* **Exploit Development** — Exploring the subtle mechanics of Win32/x64 userland binaries, structured exception handling (SEH), precision egg-hunters, and seamless ROP chains that flow past modern mitigations.
* **Windows Internals & Kernel Spaces** — Studying the architecture beneath the OS: driver communication dispatchers, IOCTL surfaces, pool grooming patterns, and token-stealing primitives.
* **Tooling with Purpose** — Sculpting lightweight, operator-centric automations, multi-protocol stagers, and custom debugging scripts designed for clarity and control.
* **Continuous Engineering** — Methodically preparing for advanced frontiers (including OSED & OSEE), recording the technical breakthroughs and quiet lab sessions in real time.

---

### *The Workbench*

```c
struct Operator {
    const char *name         = "Armaan Nain";
    const char *pseudonym    = "silver";
    const char *credential   = "OSCP";
    const char *digital_base = "[https://silversec.in](https://silversec.in)";
    const char *dialects[]   = { "C", "x86/x64 Assembly", "Python", "PowerShell" };
    const char *debuggers[]  = { "WinDbg", "GDB-GEF", "IDA Pro", "x64dbg" };
};
