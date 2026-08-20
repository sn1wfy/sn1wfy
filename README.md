<h1 align="center">Martin Nikolov</h1>

<p align="center">
  <b>Backend &amp; systems developer from Bulgaria.</b><br>
  <sub>ASP.NET Core on the web · C++ close to the kernel · Linux, Postgres and Docker underneath both.</sub>
</p>

<p align="center">
  <a href="https://omnexis.net"><img src="https://img.shields.io/badge/omnexis.net-0e75b6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <img src="https://img.shields.io/badge/Bulgaria-00966E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bulgaria">
  <img src="https://img.shields.io/badge/Focus-Backend%20%2F%20Systems-6E4AFF?style=for-the-badge" alt="Focus">
  <img src="https://komarev.com/ghpvc/?username=sn1wfy&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="Profile views">
</p>

---

<!-- ═══════════════ EDIT THIS SECTION ═══════════════ -->
## 👋 About me

I build things that have to keep running when nobody is watching — dispatch loops
that reconcile themselves after a restart, marketplaces that take real money, and
daemons that watch a Linux host for things it should not be doing. Plus the boring
infrastructure that keeps all of it alive: restorable backups, migrations that
apply on boot, and deploy scripts that refuse to run when the server is not ready.

- 🔭 Currently building **OmniTaxi** — fully automated taxi dispatch (ASP.NET Core 8 · PostgreSQL · SignalR · self-hosted OSRM)
- 🛒 Built **TrufflePoint** — a bilingual marketplace with Stripe payments, S3 media, PDF contracts and Bulgarian tax export
- 🛡️ And **BackMaster** — a C++ host-security daemon for Linux: process, socket, DNS and kernel-log monitoring with nftables enforcement
- 🌱 Going deeper on distributed state, GDPR-grade data handling, and self-hosted infrastructure
- 🗣️ Bulgarian (native) · English · German(Current Level at early A2)
- ⚡ I self-host almost everything I run

<!-- ═════════════ END EDITABLE SECTION ══════════════ -->

---

## 🧰 Tech I actually use

### Backend

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square)
![.NET 8](https://img.shields.io/badge/.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core%20MVC-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core%208-512BD4?style=flat-square&logo=nuget&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-0078D4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

<sub>Repository + Unit-of-Work over EF Core · hosted background services · reconciliation loops instead of per-request jobs · typed <code>HttpClient</code> with policy-based throttling</sub>

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![AJAX](https://img.shields.io/badge/AJAX-4B8BBE?style=flat-square&logo=javascript&logoColor=white)
![DataTables](https://img.shields.io/badge/DataTables.net-1C6EA4?style=flat-square&logo=jquery&logoColor=white)
![Razor](https://img.shields.io/badge/Razor-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-A91E50?style=flat-square&logo=ejs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

<sub><b>DataTables.net</b> for every admin grid — server-side paging, responsive collapse, column visibility, export and print buttons · <b>AJAX</b> (<code>$.ajax</code> / <code>fetch</code>) for partial updates and live admin boards · <b>SignalR</b> for push · no CDN anywhere, every asset self-hosted</sub>

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL%2016-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square)
![Redis](https://img.shields.io/badge/Redis%207-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQL](https://img.shields.io/badge/T--SQL%20%2F%20PL%2FpgSQL-336791?style=flat-square)

<sub>Schema-first migrations · connection pooling · scheduled <code>pg_dump</code> with a retention policy · versioned rows instead of destructive updates · Redis as cache <i>and</i> SignalR backplane · restore-tested backups</sub>

### Infrastructure &amp; ops

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Arch](https://img.shields.io/badge/Arch%20Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-30A3DC?style=flat-square&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white)

<sub>Multi-service Compose stacks with healthchecks, resource limits and ordered startup · zero inbound ports (tunnel-only ingress) · non-root containers · TLS termination and reverse proxy on nginx · preflight-checked deploy scripts that refuse a half-ready host</sub>

### Security

![nftables](https://img.shields.io/badge/nftables-EE0000?style=flat-square&logo=linux&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![BCrypt](https://img.shields.io/badge/BCrypt-004880?style=flat-square)
![Turnstile](https://img.shields.io/badge/Turnstile-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GDPR](https://img.shields.io/badge/GDPR-003399?style=flat-square&logo=europeanunion&logoColor=white)

<sub>Rate limiting · security headers &amp; CSP · bot/scanner traps with auto-blocklists · SYN-flood and admin-IP restriction middleware · trusted-proxy IP resolution · HTML sanitisation · SSRF protection · image-upload validation · audit trails · data-retention jobs and right-to-erasure flows</sub>

### Integrations

![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square)
![QuestPDF](https://img.shields.io/badge/QuestPDF-CC0000?style=flat-square)
![ImageSharp](https://img.shields.io/badge/ImageSharp-6E4AFF?style=flat-square)
![OSRM](https://img.shields.io/badge/OSRM-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white)
![SMTP](https://img.shields.io/badge/SMTP-EA4335?style=flat-square)

---

## 📌 Featured work

| Project | What it is | Stack |
|---|---|---|
| **OmniTaxi** 🔒 | Fully automated taxi dispatch platform. A five-second reconciliation loop offers each waiting ride to the nearest free driver, ranked by real road time from a self-hosted OSRM matrix — no human dispatcher. Versioned tariffs, an enforced ride state machine, bilingual BG/EN, GDPR-documented. | `ASP.NET Core 8` `PostgreSQL` `EF Core` `SignalR` `Redis` `OSRM` `DataTables` `Docker` |
| **TrufflePoint** 🔒 | Bilingual multi-seller marketplace. Stripe checkout and webhooks, S3-backed media behind an eight-layer malicious-image validation pipeline, generated PDF contracts, seller payouts, live chat, Bulgarian tax export, and an admin suite built on DataTables. ~56k lines of C#. | `ASP.NET Core 8` `SQL Server` `EF Core` `Stripe` `AWS S3` `QuestPDF` `JWT` `Redis` `nginx` |
| **[BackMaster](https://github.com/sn1wfy/BackMaster)** | Host-security daemon for Linux, in C++. Watches processes, sockets, DNS and the kernel ring buffer, enforces blocklists through nftables, and pushes alerts to a GTK desktop agent over IPC. Ships `backmasterd`, `backmasterctl` and systemd units. | `C++17` `nftables` `systemd` `GTK` `Make` |
| **Bodpie** 🔒 | Product site on Node.js — Express + EJS with layouts, Helmet, rate limiting, validation and transactional email. | `Node.js` `Express` `EJS` `Helmet` |
| **[portfolio](https://github.com/sn1wfy/portfolio)** → [sn1wfy.net](https://sn1wfy.net) | Personal site, hand-built and fully bilingual (BG/EN), with an audio-driven boot sequence. No framework. | `HTML` `CSS` `JavaScript` |
| **[Port-Scanner](https://github.com/sn1wfy/Port-Scanner)** | Multi-threaded async TCP port scanner with `SemaphoreSlim` concurrency control. Distinguishes open, filtered and closed ports across IPv4 and IPv6. | `C#` `.NET` |

---

## 📊 Language stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sn1wfy&theme=github_dark">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sn1wfy&theme=default" alt="Most committed languages">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=sn1wfy&theme=github_dark">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=sn1wfy&theme=default" alt="Repos per language">
  </picture>
</p>

### What the public repos say

Every public repository, by bytes of source — with vendored duplicates and
committed build artifacts excluded, which GitHub's own counter does not do:

```text
C++          56.1%  ██████████████████████░░░░░░░░░░░░░░░░░░   231 KB
HTML         19.2%  ████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    79 KB
C#           10.6%  ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    44 KB
JavaScript    7.1%  ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    29 KB
CSS           6.4%  ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    26 KB
Shell         0.7%  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░     3 KB
```

### What I actually write

Nearly everything I build is private, so the chart above is close to noise.
Counted across every project I own — public and private, third-party clones and
dependencies excluded — **252,000 lines**:

```text
C#           39.3%  ████████████████░░░░░░░░░░░░░░░░░░░░░░░░   99,003
Razor        17.6%  ███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   44,286
CSS          16.3%  ███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   40,902
JavaScript    8.3%  ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   20,944
HTML          6.3%  ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   15,921
Python        6.3%  ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   15,821
C++           3.2%  █░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░    8,022
Shell · TypeScript · SQL · C · EJS              2.7%            6,835
```

> Same person, two very different charts. **C# is 10% of my public bytes and 39%
> of everything I write** — the gap is what "most of my repositories are private"
> actually looks like when you measure it.

---

## 📫 Contact

<p align="center">
  <a href="https://sn1wfy.net"><img src="https://img.shields.io/badge/Website-0e75b6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://instagram.com/sn1wfy"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://github.com/sn1wfy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>
