<div align="center">

<svg width="100%" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg" style="background-color:#1e1e2e; border-radius: 16px;">
  <defs>
    <linearGradient id="neonGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#89b4fa;stop-opacity:1" /> <stop offset="50%" style="stop-color:#cba6f7;stop-opacity:1" /> <stop offset="100%" style="stop-color:#f38ba8;stop-opacity:1" /> </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#313244" stroke-width="0.5" stroke-opacity="0.5"/>
    </pattern>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="5" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>

  <rect width="100%" height="100%" fill="url(#grid)" />

  <rect x="0" y="0" width="1200" height="30" fill="#11111b" />
  <circle cx="20" cy="15" r="6" fill="#f38ba8" />
  <circle cx="40" cy="15" r="6" fill="#f9e2af" />
  <circle cx="60" cy="15" r="6" fill="#a6e3a1" />
  <text x="90" y="20" font-family="monospace" font-size="12" fill="#6c7086">tty1 — vordek@mainframe:~</text>

  <rect x="50" y="70" width="4" height="180" fill="url(#neonGrad)" />
  
  <text x="80" y="110" font-family="monospace" font-weight="900" font-size="64" fill="#cdd6f4" letter-spacing="2">RYAN VORDEK</text>
  
  <text x="85" y="145" font-family="monospace" font-size="18" fill="#89b4fa">> ENG. DE SOFTWARE // LABORATÓRIO DE SISTEMAS</text>

  <rect x="85" y="170" width="420" height="70" rx="4" fill="#181825" stroke="#313244" stroke-width="1"/>
  <text x="100" y="195" font-family="monospace" font-size="12" fill="#a6adc8">SYSTEM_STATUS: <tspan fill="#a6e3a1">ONLINE</tspan></text>
  <text x="100" y="215" font-family="monospace" font-size="12" fill="#a6adc8">CORE_TEMP: <tspan fill="#fab387">42°C</tspan> | THREADS: <tspan fill="#cba6f7">ACTIVE</tspan></text>
  <text x="100" y="235" font-family="monospace" font-size="12" fill="#a6adc8">LUPINE_PROTOCOLS: <tspan fill="#89b4fa">ENGAGED</tspan></text>

  <circle cx="950" cy="160" r="60" fill="none" stroke="#313244" stroke-width="2" stroke-dasharray="4 4"/>
  <circle cx="950" cy="160" r="45" fill="none" stroke="#89b4fa" stroke-width="1" />
  <circle cx="950" cy="160" r="30" fill="none" stroke="#cba6f7" stroke-width="3" filter="url(#glow)"/>
  <circle cx="950" cy="160" r="8" fill="#f38ba8" />
  
  <line x1="1010" y1="160" x2="1100" y2="160" stroke="#313244" stroke-width="2" />
  <rect x="1100" y="150" width="50" height="20" rx="2" fill="#11111b" stroke="#313244"/>
  <text x="1110" y="164" font-family="monospace" font-size="10" fill="#a6adc8">100%</text>

  <line x1="890" y1="160" x2="800" y2="160" stroke="#313244" stroke-width="2" />
  <rect x="730" y="150" width="70" height="20" rx="2" fill="#11111b" stroke="#313244"/>
  <text x="740" y="164" font-family="monospace" font-size="10" fill="#a6adc8">COMPILE</text>
  
  <text x="890" y="270" font-family="monospace" font-size="10" fill="#45475a">/// SECURE_CONNECTION_ESTABLISHED</text>
</svg>

<br/>

<a href="#-core-dump"><img src="https://img.shields.io/badge/ARCH-STRUCTURE-1e1e2e?style=for-the-badge&logo=probot&logoColor=89b4fa&labelColor=11111b&color=1e1e2e" alt="Structure"/></a>
<a href="#-workspace-env"><img src="https://img.shields.io/badge/OS-SYSTEMS-1e1e2e?style=for-the-badge&logo=linux&logoColor=cba6f7&labelColor=11111b&color=1e1e2e" alt="Systems"/></a>
<a href="#-active-modules"><img src="https://img.shields.io/badge/ROOT-CONTROL-1e1e2e?style=for-the-badge&logo=terminal&logoColor=f38ba8&labelColor=11111b&color=1e1e2e" alt="Control"/></a>

</div>

<br/>

## <code>&gt; [ // CORE_DUMP ]</code>

**Eu não gosto de usar tecnologia apenas como usuário. Eu preciso entender como funciona, onde começa, onde termina e onde pode falhar.**

Software é engenharia aplicada. É decisão de responsabilidade, fronteira bem definida e camada respeitada. Gosto de desmontar sistemas não para quebrar, mas para compreender a base de execução. Minimalismo na aparência, complexidade dominada no backend. Antes de compilar, a regra é clara:

> *Quem deve saber disso? Quem não deveria saber? O que acontece sob pressão? Pode ser automatizado?* **Se pode ser estruturado melhor, será.**

<br/>

## <code>&gt; [ // WORKSPACE_ENV ]</code>

Meu ambiente não é padrão. A produtividade não é sorte, é construção constante e controle absoluto sobre o kernel e a interface. O sistema é uma extensão direta do raciocínio lógico.

```yaml
os: CachyOS / Arch Linux Base
window_manager: Hyprland (Wayland)
shell: Fish / Zsh
status_bar: Waybar
theme_aesthetics: Catppuccin Mocha
editor: Neovim / VSCode
hardware_labs: Lenovo ThinkPad T495 (AMD Ryzen) c/ Hackintosh (OpenCore + NootedRed)
