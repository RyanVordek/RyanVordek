<div align="center">

<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#89b4fa;stop-opacity:1" /> <stop offset="100%" style="stop-color:#cba6f7;stop-opacity:1" /> </linearGradient>
  </defs>
  <rect width="1200" height="220" rx="12" fill="#1e1e2e"/> <line x1="0" y1="180" x2="1200" y2="180" stroke="#313244" stroke-width="2"/> <text x="60" y="105" font-family="monospace" font-weight="bold" font-size="52" fill="#cdd6f4"> RYAN VORDEK
  </text>
  <text x="60" y="145" font-family="monospace" font-size="18" fill="#a6adc8"> > laboratório pessoal de engenharia de software_
  </text>
  <rect x="60" y="180" width="180" height="4" fill="url(#grad)" />
</svg>

<br/>

<a href="#">
  <img src="https://img.shields.io/badge/STRUCTURE-1e1e2e?style=for-the-badge&logoColor=89b4fa&labelColor=11111b&color=1e1e2e" alt="Structure"/>
</a>
<a href="#">
  <img src="https://img.shields.io/badge/SYSTEMS-1e1e2e?style=for-the-badge&logoColor=cba6f7&labelColor=11111b&color=1e1e2e" alt="Systems"/>
</a>
<a href="#">
  <img src="https://img.shields.io/badge/CONTROL-1e1e2e?style=for-the-badge&logoColor=f38ba8&labelColor=11111b&color=1e1e2e" alt="Control"/>
</a>

</div>

<br/>

> *"Eu não gosto de usar tecnologia apenas como usuário. Eu preciso entender como funciona. Preciso saber onde começa, onde termina e onde pode falhar."*

## ⌖ IDENTIDADE & MANIFESTO

Software é engenharia aplicada. É decisão de responsabilidade, fronteira bem definida e camada respeitada. Gosto de desmontar sistemas — não para quebrar, mas para compreender a base. 

Escrevo código com intenção. Organizo a arquitetura com disciplina. Customizo meu ambiente porque **controle importa**. Minimalismo na aparência, complexidade dominada na base. Antes de escrever uma linha de código, eu questiono:

* *Quem deve saber disso?*
* *Quem não deveria saber?*
* *O que acontece sob pressão?*
* *Isso pode ser automatizado?*

Se pode ser estruturado melhor, será.

---

## 🏗️ ARQUITETURA EM CAMADAS

Cada camada tem um papel. Misturar responsabilidades é criar dívida técnica.

```text
┌────────────────────────────────────────────────────────┐
│  [ INTERFACE ]           Comportamento Consistente     │
├────────────────────────────────────────────────────────┤
│  [ LÓGICA DE APLICAÇÃO ] Regras e Domínio              │
├────────────────────────────────────────────────────────┤
│  [ INTEGRAÇÕES ]         Firebase, APIs, Serviços      │
├────────────────────────────────────────────────────────┤
│  [ AUTOMAÇÃO ]           Scripts, Pipelines, Lotes     │
├────────────────────────────────────────────────────────┤
│  [ SISTEMA ]             SO, Hardware, Redes           │
└────────────────────────────────────────────────────────┘
