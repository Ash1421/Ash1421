---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ash1421</title>
  <meta property="og:title" content="Ash1421's Github Profile" />
  <meta property="og:description" content="Tech enthusiast passionate about gaming, open-source, DevOps, FOSS, and cloud computing." />
  <meta name="theme-color" content="#7c50a8" />
  <link rel="icon" type="image/x-icon" href="assets/img/favicon.ico" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;600&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg-deep:       #0f0c29;
      --bg-mid:        #1a1338;
      --bg-card:       rgba(139, 92, 246, 0.08);
      --border:        rgba(167, 139, 250, 0.18);
      --border-hover:  rgba(167, 139, 250, 0.45);
      --purple-bright: #a78bfa;
      --purple-mid:    #8b5cf6;
      --purple-soft:   #c084fc;
      --text-primary:  #e0e0ff;
      --text-muted:    #b4b4d4;
      --text-faint:    #7b7b9e;
      --shadow-glow:   0 8px 32px rgba(139, 92, 246, 0.25);
      --font-display:  'Syne', sans-serif;
      --font-mono:     'JetBrains Mono', monospace;
    }

    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    body {
      background:
        radial-gradient(ellipse 80% 50% at 20% 10%, rgba(139,92,246,0.12) 0%, transparent 60%),
        radial-gradient(ellipse 60% 40% at 80% 80%, rgba(192,132,252,0.08) 0%, transparent 55%),
        linear-gradient(160deg, #0f0c29 0%, #1a1338 45%, #24183c 100%);
      background-attachment: fixed;
      min-height: 100vh;
      font-family: var(--font-display);
      color: var(--text-primary);
      line-height: 1.7;
      padding: 40px 20px 80px;
    }

    .page-wrapper { display: flex; justify-content: center; }
    .content-container { width: 100%; max-width: 960px; }

    h1 {
      font-size: clamp(1.8rem, 4vw, 2.6rem);
      font-weight: 800;
      background: linear-gradient(135deg, #a78bfa 0%, #c084fc 60%, #e879f9 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 0.3em;
    }

    h2 {
      font-size: clamp(1.3rem, 3vw, 1.8rem);
      color: var(--purple-bright);
      margin-top: 2.5rem;
      margin-bottom: 1rem;
      padding-bottom: 0.4rem;
      border-bottom: 1px solid var(--border);
    }

    h3 {
      font-size: 1rem;
      font-weight: 400;
      color: var(--text-faint);
      line-height: 1.6;
      margin: 0;
      padding: 4px 0;
    }

    p { color: var(--text-muted); margin-bottom: 0.6em; font-size: 0.97rem; }
    strong { color: var(--text-primary); font-weight: 600; }
    a { color: var(--purple-bright); text-decoration: none; transition: color 0.2s ease; }
    a:hover { color: var(--purple-soft); }

    table {
      width: 100%;
      border-collapse: collapse;
      background: var(--bg-card);
      border-radius: 16px;
      overflow: hidden;
      border: 1px solid var(--border) !important;
      margin: 1.2rem 0;
      font-size: 0.9rem;
    }

    table:first-of-type {
      background: transparent;
      border: none !important;
      box-shadow: none;
      margin-bottom: 0;
    }
    table:first-of-type td { border: none !important; background: transparent; padding: 12px 0; }

    thead tr, tr:has(th) { background: rgba(139, 92, 246, 0.15); }

    th {
      padding: 13px 18px;
      text-align: left;
      font-family: var(--font-display);
      font-weight: 700;
      font-size: 0.8rem;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      color: var(--purple-bright);
      border-bottom: 1px solid var(--border) !important;
      border-right: 1px solid var(--border) !important;
    }

    td {
      padding: 13px 18px;
      vertical-align: top;
      border: 1px solid var(--border) !important;
      color: var(--text-muted);
      line-height: 1.6;
    }

    td p { margin-bottom: 0.3em; }
    tr:hover > td { background: rgba(167, 139, 250, 0.03); }

    td > p > strong[style*="color"] {
      display: inline-block;
      padding: 4px 12px;
      border-radius: 20px;
      background: rgba(139, 92, 246, 0.15);
      border: 1px solid var(--border);
      font-size: 0.78rem;
      letter-spacing: 0.05em;
      text-transform: uppercase;
      color: var(--purple-bright) !important;
      -webkit-text-fill-color: var(--purple-bright);
    }

    img[src*="github-readme-stats"],
    img[src*="readme-stats"],
    img[src*="lanyard"],
    img[src*="readme-typing-svg"],
    img[src*="wakatime.com/badge"] {
      border-radius: 10px;
      max-width: 100%;
      margin: 4px;
      box-shadow: var(--shadow-glow);
      vertical-align: middle;
    }

    [align="center"], div[align="center"], p[align="center"] { text-align: center; }

    ::-webkit-scrollbar { width: 6px; height: 6px; }
    ::-webkit-scrollbar-track { background: var(--bg-deep); }
    ::-webkit-scrollbar-thumb { background: var(--purple-mid); border-radius: 3px; }
    ::-webkit-scrollbar-thumb:hover { background: var(--purple-bright); }

    @media (max-width: 680px) {
      body { padding: 20px 12px 60px; }
      h1 { font-size: 1.6rem; }
      h2 { font-size: 1.2rem; }
      th, td { padding: 10px 12px; }
      div[align="center"] { overflow-x: auto; -webkit-overflow-scrolling: touch; }
    }
  </style>
</head>
<body>
<div class="page-wrapper">
<div class="content-container">

<table width="100%">
  <tr>
    <td>
      <h1>Hi there! 👋 I'm Ash</h1>
      <p>
        Welcome to my GitHub profile! <br>
        I'm a <strong>tech enthusiast</strong> passionate about <strong>gaming</strong>, <strong>open-source projects</strong>, <strong>automation/devops</strong>, <strong>foss software</strong>, and <strong>cloud computing</strong>.<br>
        I'm also interested in <strong>machine learning</strong>, <strong>front-end development</strong>, and <strong>backend development</strong>.
      </p>
    </td>
    <td align="right" style="vertical-align: top;">
        <!-- <a href="https://github.com/Ash1421/Ash1421"/>
      <img src="https://komarev.com/ghpvc/?username=Ash1421&color=blueviolet&style=for-the-badge&abbreviated=true" alt="Profile Views" /> -->
      </a>
      <img src="https://img.shields.io/github/followers/Ash1421?style=for-the-badge&color=purple&labelColor=1c1917&logo=github" alt="GitHub Followers" />
      </a>
        <a href="https://github.com/Ash1421?tab=stars">
      <img src="https://img.shields.io/github/stars/Ash1421?style=for-the-badge&color=purple&labelColor=1c1917&logo=github" alt="GitHub Stars" />
      </a>
        <a href="https://wakatime.com/@dfdffe14-322b-4a5b-aea8-bfecd3434d3f">
      <img src="https://wakatime.com/badge/user/dfdffe14-322b-4a5b-aea8-bfecd3434d3f.svg?style=for-the-badge&color=9B59B6&labelColor=1c1917" alt="WakaTime Code Time" />
      </a>
        <a href="https://discord.com/users/730744444134433994">
      <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.lanyard.rest%2Fv1%2Fusers%2F616485235982467085&query=%24.data.discord_status&style=for-the-badge&logo=discord&logoColor=white&label=Discord%20User&suffix=%20|%20@%20Ash1421&color=9B59B6&labelColor=1c1917" alt="Discord User @ash1421" />
      </a>
      <img src="https://img.shields.io/badge/Built%20with-%E2%9D%A4%EF%B8%8F-ff69b4?style=for-the-badge&labelColor=1c1917" alt="Built with love" />
      </a>
       <a href="https://en.wikipedia.org/wiki/Free_and_open-source_software">
      <img src="https://img.shields.io/badge/FOSS-Fan-9B59B6?style=for-the-badge&logo=foss&logoColor=white&labelColor=1c1917" alt="FOSS" />
      </a>
       <a href="https://opensource.org/about">
      <img src="https://img.shields.io/badge/Open%20Source-Fan-9B59B6?style=for-the-badge&logo=open-source-initiative&logoColor=white&labelColor=1c1917" alt="Open Source" />
      </a>
      <a href="https://ash1421.com">
        <img src="https://img.shields.io/website?style=for-the-badge&url=https%3A%2F%2Fash1421.com&up_message=UP&down_message=DOWN&logo=firefox&logoColor=white&up_color=9B59B6&down_color=red&label=My%20Website&labelColor=1c1917" alt="My Website" />
      </a>
      <a href="https://theme.ash1421.com">
        <img src="https://img.shields.io/website?style=for-the-badge&url=https%3A%2F%2Ftheme.ash1421.com&up_message=UP&down_message=DOWN&logo=firefox&logoColor=white&up_color=9B59B6&down_color=red&label=Theme%20Website&labelColor=1c1917" alt="Theme Website" />
      </a>
       <a href="https://www.twitch.tv/ash1421_" target="_blank" rel="noreferrer">
      <img src="https://img.shields.io/twitch/status/ash1421_?logo=twitch&style=for-the-badge&label=TWITCH+STATUS&color=9B59B6&logoColor=white&labelColor=1c1917" alt="TWITCH STATUS" />
      </a>
       <a href="https://x.com/_Ashttv">
      <img src="https://img.shields.io/badge/X%20/%20Twitter-7D39D6?style=for-the-badge&logo=x&logoColor=white&labelColor=1c1917" alt="X / Twitter" />
      </a>
       <a href="https://discord.gg/xc4D33wBmA">
      <img src="https://img.shields.io/discord/1086533721726922793?style=for-the-badge&logo=discord&logoColor=white&label=Discord%20Server%20Invite&color=7D39D6&labelColor=1c1917" alt="Discord Server" />
      </a>
       <a href="https://bsky.app/profile/ash1421.bsky.social">
      <img src="https://img.shields.io/badge/Bluesky-6829B1?style=for-the-badge&logo=bluesky&logoColor=white&labelColor=1c1917" alt="Bluesky" />
      </a>
        <a href="https://www.reddit.com/user/Ash1421_/">
      <img src="https://img.shields.io/badge/Reddit-6829B1?style=for-the-badge&logo=reddit&logoColor=white&labelColor=1c1917" alt="Reddit" />
      </a>
        <a href="https://youtube.com/@Ash1421_?sub_confirmation=1">
      <img src="https://img.shields.io/badge/YouTube-7D39D6?style=for-the-badge&logo=youtube&logoColor=white&labelColor=1c1917" alt="YouTube" />
      </a>
       <a href="https://steamcommunity.com/id/Ash1421/">
      <img src="https://img.shields.io/badge/Steam-6829B1?style=for-the-badge&logo=steam&logoColor=white&labelColor=1c1917" alt="Steam" />
      </a>
    </td>
  </tr>
</table>

<table width="100%" style="border-collapse: collapse; border: 1px solid #ddd;">
  <tr>
    <td align="center" style="border: 1px solid #ddd; padding: 15px; vertical-align: top;">
      <h3>💜 Donations and support / funding are appreciated very much!</h3>
      <p><strong>Minimum donation:</strong> $5 (NZD)</p>
      <p><strong>Payment methods:</strong> Credit/Debit Card, PayPal, Apple Pay, Google Pay</p>
      <p><strong>Supported Cards:</strong> Visa, Mastercard, Amex / American Express</p>
      <p>Membership options are <strong>available</strong> for recurring support.</p>
      <p><strong>You can donate via:</strong></p>
      <a href="https://kofi.ash1421.com">
        <img src="https://img.shields.io/badge/Ko--fi-Donate-FF69B4?style=for-the-badge&logo=kofi&logoColor=white&labelColor=1c1917" alt="Ko-fi">
      </a>
    </td>

<td align="center" style="border: 1px solid #ddd; padding: 15px; vertical-align: top;">

  <h3 style="color:#553BBB;">💜 Supported Payment Methods:</h3>

  <div style="margin-bottom:8px;">
    <div>
    <a href="https://www.visa.co.nz/">
      <img src="https://img.shields.io/badge/Visa%20Credit%2FDebit_Card-9C51E3?style=for-the-badge&logo=visa&logoColor=white&labelColor=1c1917" alt="Visa Credit/Debit Card">
    </a>
    <a href="https://www.mastercard.co.nz/">
      <img src="https://img.shields.io/badge/Mastercard%20Credit%2FDebit_Card-8F40E0?style=for-the-badge&logo=mastercard&logoColor=white&labelColor=1c1917" alt="Mastercard Credit/Debit Card">
    </a>
    <a href="https://www.americanexpress.com/newzealand/">
      <img src="https://img.shields.io/badge/Amex%2FAmerican%20Express%20Credit%2FDebit_Card-8433DD?style=for-the-badge&logo=american-express&logoColor=white&labelColor=1c1917" alt="Amex / American Express Credit/Debit Card">
    </a>
  </div>

  <div>
    <a href="https://www.paypal.com/nz/">
      <img src="https://img.shields.io/badge/PayPal-Supported-7930DA?style=for-the-badge&logo=paypal&logoColor=white&labelColor=1c1917" alt="PayPal">
    </a>
    <a href="https://www.apple.com/nz/apple-pay/">
      <img src="https://img.shields.io/badge/Apple_Pay-Supported-6F28D7?style=for-the-badge&logo=apple&logoColor=white&labelColor=1c1917" alt="Apple Pay">
    </a>
    <a href="https://pay.google.com/intl/en_nz/about/">
      <img src="https://img.shields.io/badge/Google_Pay-Supported-6320D3?style=for-the-badge&logo=google-pay&logoColor=white&labelColor=1c1917" alt="Google Pay">
    </a>
  </div>

</td>
  </tr>
</table>

<table width="100%" style="border-collapse: collapse; border: 1px solid #ddd;">
  <tr>
    <td align="center" style="border: 1px solid #ddd; padding: 10px;">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=4500&color=9B59B6&center=true&lines=Hi+there!+I'm+Ash+;Tech+enthusiast+and+gamer;Always+learning+new+things!" alt="Typing SVG">
    </td>
    <td align="center" style="border: 1px solid #ddd; padding: 10px;">
      <p><strong style="color:#551A8B; font-size:1.1em;">The badges on my profile are clickable.</strong> <br>Some of the stats or status are clickable too!</p>
    </td>
  </tr>
</table>

<div align="center">
  <table width="100%" style="border-collapse: collapse; border: 1px solid #ddd;">
    <tr>
      <th style="border: 1px solid #ddd; padding: 10px;">Category</th>
      <th style="border: 1px solid #ddd; padding: 10px;">Tech Stack & Interests</th>
    </tr>
    <tr>
      <td colspan="2" style="padding: 10px;">
        <h3 style="padding: 10px;">
          I don't claim expertise in all of the technologies listed below. Some I use regularly, some I've experimented with, and others are tools, platforms, or hardware I'm interested in or have worked with.
          <br>
          <br>
          For the companys and products such as the hardware they make I either own it, have used it, or favorite the company or product. Brands like Nintendo could include the games that are on it, or some of the hardware they make as a product such as the Nintendo Switch.
        </h3>
      </td>
    </tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#3D0066; font-size:1.1em;">Programming Languages</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/Python-3D0066?style=for-the-badge&logo=python&logoColor=white&labelColor=1c1917" alt="Python" />
        <img src="https://img.shields.io/badge/Swift-47007C?style=for-the-badge&logo=swift&logoColor=white&labelColor=1c1917" alt="Swift" />
        <img src="https://img.shields.io/badge/C-380059?style=for-the-badge&logo=C&logoColor=white&labelColor=1c1917" alt="C" />
        <img src="https://img.shields.io/badge/C++-2E004B?style=for-the-badge&logo=c-plus-plus%2B%2B%2B%2B&logoColor=white&labelColor=1c1917" alt="C++" />
        <img src="https://img.shields.io/badge/JavaScript-400066?style=for-the-badge&logo=javascript&logoColor=white&labelColor=1c1917" alt="JavaScript" />
        <img src="https://img.shields.io/badge/Kotlin-420073?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=1c1917" alt="Kotlin" />
        <img src="https://img.shields.io/badge/Go-36005A?style=for-the-badge&logo=go&logoColor=white&labelColor=1c1917" alt="Go" />
        <img src="https://img.shields.io/badge/Rust-2E004B?style=for-the-badge&logo=rust&logoColor=white&labelColor=1c1917" alt="Rust" />
        <img src="https://img.shields.io/badge/PHP-400066?style=for-the-badge&logo=php&logoColor=white&labelColor=1c1917" alt="PHP" />
        <img src="https://img.shields.io/badge/Lua-430073?style=for-the-badge&logo=lua&logoColor=white&labelColor=1c1917" alt="Lua" />
        <img src="https://img.shields.io/badge/TypeScript-42006B?style=for-the-badge&logo=typescript&logoColor=white&labelColor=1c1917" alt="TypeScript" />
        <img src="https://img.shields.io/badge/HTML-3D0066?style=for-the-badge&logo=html5&logoColor=white&labelColor=1c1917" alt="HTML" />
        <img src="https://img.shields.io/badge/Dockerfile-4D1478?style=for-the-badge&logo=docker&logoColor=white&labelColor=1c1917" alt="Dockerfile" />
        <img src="https://img.shields.io/badge/SCSS-380059?style=for-the-badge&logo=sass&logoColor=white&labelColor=1c1917" alt="SCSS" />
        <img src="https://img.shields.io/badge/CSS-380059?style=for-the-badge&logo=css&logoColor=white&labelColor=1c1917" alt="CSS" />
        <img src="https://img.shields.io/badge/Eclipse%20Adoptium-551A8B?style=for-the-badge&logo=eclipse-adoptium&logoColor=white&labelColor=1c1917" alt="Eclipse Adoptium" />
        <img src="https://img.shields.io/badge/C%23-430073?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
        <img src="https://img.shields.io/badge/Java-42006B?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
        <img src="https://img.shields.io/badge/INI-4D1478?style=for-the-badge&logo=ini&logoColor=white" alt="INI" />
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#551A8B; font-size:1.1em;">DevOps & Containers</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/Kubernetes-551A8B?style=for-the-badge&logo=kubernetes&logoColor=white&labelColor=1c1917" alt="Kubernetes" />
        <img src="https://img.shields.io/badge/Docker-4D1478?style=for-the-badge&logo=docker&logoColor=white&labelColor=1c1917" alt="Docker" />
        <img src="https://img.shields.io/badge/Docker%20Swarm-4D1478?style=for-the-badge&logo=docker&logoColor=white&labelColor=1c1917" alt="Docker Swarm" />
        <img src="https://img.shields.io/badge/VMware-4D1478?style=for-the-badge&logo=vmware&logoColor=white&labelColor=1c1917" alt="VMware" />
        <img src="https://img.shields.io/badge/VirtualBox-400066?style=for-the-badge&logo=virtualbox&logoColor=white&labelColor=1c1917" alt="VirtualBox" />
        <img src="https://img.shields.io/badge/Proxmox-4D1478?style=for-the-badge&logo=proxmox&logoColor=white&labelColor=1c1917" alt="Proxmox" />
        <img src="https://img.shields.io/badge/QEMU-4D1478?style=for-the-badge&logo=qemu&logoColor=white&labelColor=1c1917" alt="QEMU" />
        <img src="https://img.shields.io/badge/LXC-4D1478?style=for-the-badge&logo=lxc&logoColor=white" alt="LXC" />
        <img src="https://img.shields.io/badge/Hyper--V-4D1478?style=for-the-badge&logo=hyper-v&logoColor=white" alt="Hyper-V" />
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#6829B1; font-size:1.1em;">Protocols & Networking</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/RDP-6829B1?style=for-the-badge&logo=routing-information-protocol&logoColor=white" alt="RDP" />
        <img src="https://img.shields.io/badge/NTP-5E22A1?style=for-the-badge&logo=network-time-protocol&logoColor=white" alt="NTP" />
        <img src="https://img.shields.io/badge/SMTP/POP3/IMAP-531E8F?style=for-the-badge&logo=simple-mail-transfer-protocol&logoColor=white" alt="SMTP/POP3/IMAP" />
        <img src="https://img.shields.io/badge/SFTP/SCP-4B1B81?style=for-the-badge&logo=windows-server-message-block&logoColor=white" alt="SFTP/SCP" />
        <img src="https://img.shields.io/badge/DNS-6829B1?style=for-the-badge&logo=dns&logoColor=white" alt="DNS" />
        <img src="https://img.shields.io/badge/DHCP-5E22A1?style=for-the-badge&logo=dhcp&logoColor=white" alt="DHCP" />
        <img src="https://img.shields.io/badge/SMTP-531E8F?style=for-the-badge&logo=smtp&logoColor=white" alt="SMTP" />
        <img src="https://img.shields.io/badge/SNMP-4B1B81?style=for-the-badge&logo=snmp&logoColor=white" alt="SNMP" />
        <img src="https://img.shields.io/badge/ARP-591E96?style=for-the-badge&logo=arp&logoColor=white" alt="ARP" />
        <img src="https://img.shields.io/badge/ICMP-6829B1?style=for-the-badge&logo=icmp&logoColor=white" alt="ICMP" />
        <img src="https://img.shields.io/badge/HTTP/HTTPS-6829B1?style=for-the-badge&logo=http&logoColor=white" alt="HTTP/HTTPS" />
        <img src="https://img.shields.io/badge/FTP/FTPS-5E22A1?style=for-the-badge&logo=ftp&logoColor=white" alt="FTP/FTPS" />
        <img src="https://img.shields.io/badge/TCP-531E8F?style=for-the-badge&logo=tcp&logoColor=white" alt="TCP" />
        <img src="https://img.shields.io/badge/UDP-4B1B81?style=for-the-badge&logo=udp&logoColor=white" alt="UDP" />
        <img src="https://img.shields.io/badge/SSH-591E96?style=for-the-badge&logo=ssh&logoColor=white" alt="SSH" />
        <img src="https://img.shields.io/badge/SMB-6829B1?style=for-the-badge&logo=smb&logoColor=white" alt="SMB" />
        <img src="https://img.shields.io/badge/NTP-5E22A1?style=for-the-badge&logo=network-time-protocol&logoColor=white" alt="NTP" />
        <img src="https://img.shields.io/badge/ZFS-7634D3?style=for-the-badge&logo=zfs&logoColor=white" alt="ZFS" />
        <img src="https://img.shields.io/badge/NFS-7634D3?style=for-the-badge&logo=nfs&logoColor=white" alt="NFS" />
        <img src="https://img.shields.io/badge/Btrfs-7634D3?style=for-the-badge&logo=btrfs&logoColor=white" alt="Btrfs" />
        <img src="https://img.shields.io/badge/TMPFS-7634D3?style=for-the-badge&logo=tmpfs&logoColor=white" alt="TMPFS" />
        <img src="https://img.shields.io/badge/EXT4-7634D3?style=for-the-badge&logo=ext4&logoColor=white" alt="EXT4" />
        <img src="https://img.shields.io/badge/NTFS-8645EA?style=for-the-badge&logo=ntfs&logoColor=white" alt="NTFS" />
        <img src="https://img.shields.io/badge/FAT-7634D3?style=for-the-badge&logo=fat&logoColor=white" alt="FAT" />
        <img src="https://img.shields.io/badge/FAT--32-7634D3?style=for-the-badge&logo=fat&logoColor=white" alt="FAT 32" />
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#7D39D6; font-size:1.1em;">Scripting & Shells</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/Bash-7D39D6?style=for-the-badge&logo=gnu-bash&logoColor=white&labelColor=1c1917" alt="Bash" />
        <img src="https://img.shields.io/badge/Zsh-7634D3?style=for-the-badge&logo=zsh&logoColor=white&labelColor=1c1917" alt="Zsh" />
        <img src="https://img.shields.io/badge/PowerShell-6F29CC?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell" />
        <img src="https://img.shields.io/badge/Batch-5D1BC0?style=for-the-badge&logo=windows-terminal&logoColor=white" alt="Batch" />
        <img src="https://img.shields.io/badge/VBS-6020B8?style=for-the-badge&logo=visual-basic&logoColor=white" alt="VBS" />
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#8E4DF2; font-size:1.1em;">Markup & Data Formats</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/JSON-8E4DF2?style=for-the-badge&logo=json&logoColor=white&labelColor=1c1917" alt="JSON" />
        <img src="https://img.shields.io/badge/JSON%20with%20comments-8E4DF2?style=for-the-badge&logo=json&logoColor=white&labelColor=1c1917" alt="JSON with comments" />
        <img src="https://img.shields.io/badge/XML-8645EA?style=for-the-badge&logo=xml&logoColor=white&labelColor=1c1917" alt="XML" />
        <img src="https://img.shields.io/badge/YAML-7B3DD9?style=for-the-badge&logo=yaml&logoColor=white&labelColor=1c1917" alt="YAML" />
        <img src="https://img.shields.io/badge/TOML-7B3DD9?style=for-the-badge&logo=toml&logoColor=white&labelColor=1c1917" alt="TOML" />
        <img src="https://img.shields.io/badge/SQL-7839D5?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=1c1917" alt="SQL" />
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <p><strong style="color:#8B3D6E; font-size:1.1em;">Hardware & Companies</strong></p>
      </td>
      <td style="border: 1px solid #ddd; padding: 10px;">
        <img src="https://img.shields.io/badge/NVIDIA-8B3D6E?style=for-the-badge&logo=nvidia&logoColor=white&labelColor=1c1917" alt="NVIDIA" />
        <img src="https://img.shields.io/badge/Ryzen-8B3D6E?style=for-the-badge&logo=amd&logoColor=white&labelColor=1c1917" alt="Ryzen" />
        <img src="https://img.shields.io/badge/Intel-8B3D6E?style=for-the-badge&logo=intel&logoColor=white&labelColor=1c1917" alt="Intel" />
        <img src="https://img.shields.io/badge/Cisco-8B3D6E?style=for-the-badge&logo=cisco&logoColor=white&labelColor=1c1917" alt="Cisco" />
        <img src="https://img.shields.io/badge/Fortinet-8B3D6E?style=for-the-badge&logo=fortinet&logoColor=white&labelColor=1c1917" alt="Fortinet" />
        <img src="https://img.shields.io/badge/Ubiqiti-8B3D6E?style=for-the-badge&logo=ubiquiti&logoColor=white&labelColor=1c1917" alt="Ubiqiti" />
        <img src="https://img.shields.io/badge/Raspberry%20Pi-8B3D6E?style=for-the-badge&logo=raspberry-pi&logoColor=white&labelColor=1c1917" alt="Raspberry Pi" />
        <img src="https://img.shields.io/badge/ASUS-8B3D6E?style=for-the-badge&logo=asus&logoColor=white&labelColor=1c1917" alt="ASUS" />
        <img src="https://img.shields.io/badge/Samsung-8B3D6E?style=for-the-badge&logo=samsung&logoColor=white&labelColor=1c1917" alt="Samsung" />
        <img src="https://img.shields.io/badge/Lenovo-8B3D6E?style=for-the-badge&logo=lenovo&logoColor=white&labelColor=1c1917" alt="Lenovo" />
        <img src="https://img.shields.io/badge/Logitech-8B3D6E?style=for-the-badge&logo=logitech&logoColor=white&labelColor=1c1917" alt="Logitech" />
        <img src="https://img.shields.io/badge/HP-8B3D6E?style=for-the-badge&logo=hp&logoColor=white&labelColor=1c1917" alt="HP" />
        <img src="https://img.shields.io/badge/SteelSeries-8B3D6E?style=for-the-badge&logo=steelseries&logoColor=white&labelColor=1c1917" alt="SteelSeries" />
        <img src="https://img.shields.io/badge/PlayStation-8B3D6E?style=for-the-badge&logo=playstation&logoColor=white&labelColor=1c1917" alt="PlayStation" />
        <img src="https://img.shields.io/badge/Google-8B3D6E?style=for-the-badge&logo=google&logoColor=white&labelColor=1c1917" alt="Google" />
        <img src="https://img.shields.io/badge/Sony-8B3D6E?style=for-the-badge&logo=sony&logoColor=white&labelColor=1c1917" alt="Sony" />
        <img src="https://img.shields.io/badge/LG-8B3D6E?style=for-the-badge&logo=lg&logoColor=white&labelColor=1c1917" alt="LG" />
        <img src="https://img.shields.io/badge/Elgato-8B3D6E?style=for-the-badge&logo=elgato&logoColor=white&labelColor=1c1917" alt="Elgato" />
        <img src="https://img.shields.io/badge/NZXT-8B3D6E?style=for-the-badge&logo=nzxt&logoColor=white&labelColor=1c1917" alt="NZXT" />
        <img src="https://img.shields.io/badge/Epic%20Games-8B3D6E?style=for-the-badge&logo=epic-games&logoColor=white&labelColor=1c1917" alt="Epic Games" />
        <img src="https://img.shields.io/badge/Steam-8B3D6E?style=for-the-badge&logo=steam&logoColor=white&labelColor=1c1917" alt="Steam" />
        <img src="https://img.shields.io/badge/Rockstar%20Games-8B3D6E?style=for-the-badge&logo=rockstar-games&logoColor=white&labelColor=1c1917" alt="Rockstar Games" />
        <img src="https://img.shields.io/badge/Electronic%20Arts-8B3D6E?style=for-the-badge&logo=ea&logoColor=white&labelColor=1c1917" alt="Electronic Arts" />
        <img src="https://img.shields.io/badge/Nintendo-8B3D6E?style=for-the-badge&logo=nintendo&logoColor=white" alt="Nintendo" />
        <img src="https://img.shields.io/badge/Xbox-8B3D6E?style=for-the-badge&logo=xbox&logoColor=white" alt="Xbox" />
        <img src="https://img.shields.io/badge/EVGA-8B3D6E?style=for-the-badge&logo=evga&logoColor=white" alt="EVGA" />
        <img src="https://img.shields.io/badge/GSkill-8B3D6E?style=for-the-badge&logo=gskill&logoColor=white" alt="GSkill" />
        <img src="https://img.shields.io/badge/Kingston-8B3D6E?style=for-the-badge&logo=kingston&logoColor=white" alt="Kingston" />
        <img src="https://img.shields.io/badge/Realtek-8B3D6E?style=for-the-badge&logo=realtek&logoColor=white" alt="Realtek" />
  </table>
</div>

<h2>📊 GitHub Stats &amp; Discord Status</h2>

<p align="center">
  <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api?username=Ash1421&show_icons=true&theme=dark&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&hide_border=true&count_private=true" alt="GitHub Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api/top-langs/?username=Ash1421&theme=dark&show_icons=true&hide_border=true&langs_count=10&layout=compact&count_private=true&custom_title=Top%20Languages" alt="Top Languages"/>
  <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api/top-langs/?username=Ash1421&theme=dark&stats_format=bytes&show_icons=true&hide_border=true&langs_count=10&layout=compact&count_private=true&custom_title=Top%20Languages%20in%20Bytes" alt="Top Languages in Bytes"/>
  <a href="https://wakatime.com/@dfdffe14-322b-4a5b-aea8-bfecd3434d3f">
    <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api/wakatime?username=Ash1421&theme=dark&layout=compact&card_width=650" alt="Compact Waka Time"/>
  </a>
  <a href="https://github.com/Ash1421/Midnight-Ash">
    <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api/pin/?username=Ash1421&repo=Midnight-Ash&theme=dark" alt="Midnight-Ash Pin"/>
  </a>
  <a href="https://github.com/Ash1421/QuickA-Cleanup">
    <img src="https://github-readme-stats-ash1421s-projects.vercel.app/api/pin/?username=Ash1421&repo=QuickA-Cleanup&theme=dark" alt="QuickA-Cleanup Pin"/>
  </a>
  <img src="https://lanyard.cnrad.dev/api/616485235982467085?theme=dark&bg=1c1917&borderRadius=10px&hideDiscrim=false&idleMessage=Currently%20Offline,%20or%20Busy" alt="Discord Presence"/>
</p>

</div>
</div>
</body>
</html>