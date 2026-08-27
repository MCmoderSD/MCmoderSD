<!-- **MCmoderSD/MCmoderSD** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->

# Seraphin Berger

Software engineering student and full stack developer based in Germany, currently building internal web applications at ODDO BHF SE. I work primarily with Angular, .NET and Java, and self-host and automate most of what I run.

## About Me
- **Name:** Seraphin Berger
- **Age:** 22
- **Location:** Germany
- **Education:** Pursuing [B.Eng. Software Engineering and Media Computing](https://www.hs-esslingen.de/en/softwaretechnik-und-medieninformatik) at [Hochschule Esslingen](https://www.hs-esslingen.de/)

## Experience
- **Current Position:** Full Stack Developer at [ODDO BHF SE](https://www.oddo-bhf.com/en/) in Frankfurt am Main, Germany
- **Employment Type:** Working Student (Werkstudent) since November 2025
- **Responsibilities:** Developing and maintaining an internal web application
- **Technologies:** Angular, TypeScript, C# .NET 8, Oracle SQL

## Technologies
- **Languages:** Java, C#, TypeScript, HTML, CSS, SQL
- **Infrastructure:** Debian Linux, TrueNAS Scale, [Hetzner](https://www.hetzner.com/)
- **Containerization:** Docker, Docker Compose
- **Services:** [Cloudflare](https://www.cloudflare.com/), [OpenAI API](https://openai.com/en-US/api/), GitHub Actions

## Contact
- **Website:** [mcmodersd.de](https://www.mcmodersd.de/)
- **LinkedIn:** [Seraphin Berger](https://www.linkedin.com/in/seraphin-berger/)
- **Email:** [business@mcmodersd.de](mailto:business@mcmodersd.de)

## Projects

### [YEPPBot](https://github.com/MCmoderSD/YEPPBot) | Java Twitch Bot
This repository hosts the source code for YEPPBot, a comprehensive Twitch bot featuring numerous tools to entertain and manage your Twitch channel.

#### Tech Stack
- **Java**: The primary programming language used for developing the bot.
- **Docker**: Used for containerizing the application, including a published Docker image and Docker Compose setup for easy self-hosting.
- **GitHub Actions**: Used for continuous integration and deployment automation through YAML configuration.

#### Key Features
- **Automated Build and Deployment**: Utilizes GitHub Actions for CI/CD and multi-architecture support releases.
- **Easy Self-Hosting**: Comes with a ready-to-use Docker image and Docker Compose configuration for straightforward deployment.
- **Multi-API Integration**: Integrates with various third-party APIs to provide a wide range of functionalities:
  - **[OpenAI-Wrapper](https://github.com/MCmoderSD/OpenAI-Wrapper/)**: A custom wrapper to interact with OpenAI APIs for advanced functionalities.
  - **[OpenWeatherMap](https://github.com/MCmoderSD/OpenWeatherMap/)**: Fetches weather information to provide real-time weather updates in the chat.
  - **[HTTPS-Server](https://github.com/MCmoderSD/HTTPS-Server/)**: A lightweight HTTPS server with automatic TLS certificate management via ACME.

This repository serves as a demonstration of my skills in developing, integrating, and managing a complex Java application with practical applications in the real world.  
It is my biggest project yet, highlighting my proficiency in building scalable, maintainable, and feature-rich software solutions.

---

### [MCmoderSD.de](https://github.com/MCmoderSD/MCmoderSD.de) | Personal Portfolio & Homepage
This repository hosts the source code for my personal portfolio and homepage. It's an Angular application that presents who I am, the projects I've built, the open-source packages I maintain, and the self-hosted services running on my home server.

#### Tech Stack
- **Angular 22**: Standalone-first, signal-based components, native control flow, and `input()`/`output()`/`computed()` for state.
- **TypeScript**: Strict mode throughout.
- **Angular Material**: Layered with a custom, hand-built design system, CSS custom properties, OKLCh colors, wide-gamut/P3 support, and a dark/light color-scheme switch.
- **SSR & Pre-rendering**: Server-side rendering and static pre-rendering via `@angular/ssr`, served through a minimal **Express** server.
- **Vitest**: Unit testing.
- **Docker**: Multi-stage, multi-architecture (`amd64` + `arm64`) image, built with Buildx on native per-arch GitHub Actions runners with registry-backed layer caching.

#### Key Features
- **Accessible by design**: Built to pass AXE checks and WCAG AA minimums — focus management, color contrast, and ARIA attributes are treated as requirements, not afterthoughts.
- **Custom design system**: A cursor-following spotlight, a floating custom scrollbar, and a wide-gamut color palette that degrades gracefully on unsupported displays.
- **Automated CI/CD**: GitHub Actions builds and publishes the multi-arch Docker image to Docker Hub on every push, with Dependabot keeping GitHub Actions and the base image up to date automatically.
- **Production hosting**: Runs behind a **Caddy** reverse proxy that provisions and renews its own TLS certificates via the **Cloudflare** DNS challenge, with custom static error pages (404, 500, 502, 503, 504, ...) styled to match the site.
- **Security-conscious server**: Strict host allowlisting, security headers (HSTS, X-Frame-Options, Referrer-Policy, ...), and Brotli/gzip compression on the Express layer.

This repository demonstrates my ability to design and ship a production web application end-to-end: a polished, accessible frontend, a hardened SSR backend, and a fully automated build, security-update, and deployment pipeline.

---

### [Tab Scraper](https://github.com/MCmoderSD/TabScraper) | TypeScript Chrome Extension
A lightweight, privacy-first Chrome extension that collects the URLs of all your open tabs and saves them as a text file, in a single click.

#### Tech Stack
- **TypeScript**: The primary language used for all extension logic, compiled to ESNext via `tsc`.
- **Chrome Extension APIs**: Leverages the `tabs`, `downloads`, `storage`, `scripting`, and `activeTab` permissions for full browser integration.
- **Manifest V3**: Built on the latest Chrome extension standard using a service worker background script.

#### Key Features
- **One-Click Export**: Gather all open tab URLs instantly and save them as a `.txt` file.
- **Advanced Filtering**: Include or exclude tabs by URL prefix, suffix, or custom regular expressions.
- **Invert Selection**: Flip any filter to exclude matching patterns instead.
- **Persistent Settings**: Filter preferences sync across your Chrome profile via `chrome.storage.sync`.
- **Privacy-First**: All data stays local — no external servers, no tracking, no telemetry.
- **Modern UI**: Dark mode, responsive layout, and polished styling out of the box.

Available on the [Chrome Web Store](https://chromewebstore.google.com/detail/tab-scraper/ahdhhonppgdiglmppkcjckijelfdalho) or as a self-hosted build via the [GitHub releases page](https://github.com/MCmoderSD/TabScraper/releases/latest).

---

## Hardware

### [Main Rig](https://pcpartpicker.com/list/x272mL)
- Mainboard: [Asus ROG Strix B550-F Gaming WiFi 2](https://rog.asus.com/de/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/)
- CPU: [AMD Ryzen 7 5800X](https://www.amd.com/de/products/cpu/amd-ryzen-7-5800x)
- AIO Liquid Cooler: [NZXT Kraken X63 RGB](https://nzxt.com/product/kraken-x63-rgb)
- RAM: [Corsair Vengeance RGB Pro 2x32GB 3600MHz CL18](https://www.corsair.com/de/de/p/memory/cmw64gx4m2d3600c18/vengeance-rgb-pro-64gb-2-x-32gb-ddr4-dram-3600mhz-c18-memory-kit-black-cmw64gx4m2d3600c18)
- GPU: [Zotac Gaming GeForce RTX 5070 TI SOLID SFF](https://www.zotac.com/at/product/graphics_card/zotac-gaming-geforce-rtx-5070-ti-solid-sff-0)
- PSU: [BeQuiet! Pure Power 12 M 750W](https://www.bequiet.com/de/powersupply/4073)
- NVMe M.2 SSD:
  - C: Drive: [WD Black SN850X 2TB](https://shop.sandisk.com/de-de/products/ssd/internal-ssd/wd-black-sn850x-nvme-ssd?sku=WDS100T2X0E-00BCA0)
  - D: Drive: [WD Black SN850 1TB](https://www.westerndigital.com/de-de/products/internal-drives/wd-black-sn850-nvme-ssd)
- HDD: [Seagate Desktop SSHD 2TB](https://www.amazon.de/Seagate-Desktop-interne-Hybrid-Festplatte-7200rpm/dp/B00EIQTKAS)
- NIC: [Intel X540-AT2 Dual 10GBit/s](https://www.intel.de/content/www/de/de/products/sku/60020/intel-ethernet-controller-x540at2/specifications.html)
- Case: [Kolink Balance](https://kolink.eu/Home/case-1/midi-tower-2/others/balance-1.html)
- OS: [Windows 11 Pro](https://www.microsoft.com/de-de/windows/windows-11-pro)

---

- Monitors:
  - 1st: [ASUS TUF Gaming VG249QM1A 270hz](https://www.asus.com/de/displays-desktops/monitors/tuf-gaming/tuf-gaming-vg249qm1a/)
  - 2nd: [Samsung LF24T350FHR](https://www.samsung.com/de/monitors/flat/t35f-24-inch-ips-fhd-1080p-freesync-lf24t350fhrxen/)
- Monitor Mount: [BONTEC Monitor Bracket](https://www.amazon.de/gp/product/B01MR397OH/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1)
- WebCam: [Logitech StreamCam](https://www.logitech.com/de-de/products/webcams/streamcam.960-001281.html#buy-streamcam)
- Microphone: [RØDE NT-USB](https://rode.com/de/microphones/usb/nt-usb)
- Headset: [HyperX Cloud 2](https://www.hyperxgaming.com/germany/de/headsets/cloud-gaming-headset?partnum=khx-hscp-rd)
- Keyboard: [Wooting Two HE](https://wooting.io/wooting-two-he)
- Keycaps: [Wooting Double Shot Backlit PBT Keycaps](https://wooting.io/product/wooting-double-shot-pbt-backlit-keycap-set-just-black?Language=ISO+German&Color=Just+Black)
- Mouse: [Logitech Pro X Superlight 2](https://www.logitechg.com/de-de/products/gaming-mice/pro-x2-superlight-wireless-mouse.910-006630.html)
- Mousepad:[Glorious 3XL Extended Mousepad](https://www.pcgamingrace.com/products/glorious-3xl-extended-24x48-stealth-edition)
- Controller: [Xbox Wireless Controller Custom Design](https://xboxdesignlab.xbox.com/)
- VR Headset: [Meta Quest 3S](https://www.meta.com/de/quest/quest-3s/)
- VR Head-Strap: [KIWI Design H4 Boost](https://www.kiwidesign.com/de-eu/products/h4-boost-halo-battery-strap)

---

### Mobile
- Notebook: [Samsung Galaxy Book6 Pro 16" (NP960XJG-KG6DE)](https://www.samsung.com/de/computers/galaxy-book/galaxy-book6-pro-ultra-x7-32gb-1tb-np960xjg-kg6de/)
- CPU: [Intel Core Ultra X7 358H](https://www.intel.com/content/www/us/en/products/sku/245527/intel-core-ultra-x7-processor-358h-18m-cache-up-to-4-80-ghz/specifications.html)
- GPU: Intel Arc B390 (integrated)
- RAM: 32GB LPDDR5X 9600 MT/s (on board)
- NVMe: 1TB NVMe SSD
- Display: 16" Dynamic AMOLED 2X, 2880x1800 (WQXGA+), 30-120Hz
- OS: [Windows 11 Pro](https://www.microsoft.com/de-de/windows/windows-11)
- Mouse: [SteelSeries Rival 3](https://de.steelseries.com/gaming-mice/rival-3-wireless)

---

### [Home Server](https://pcpartpicker.com/list/ZYTv3R)
- Mainboard: [Asus Prime B550-Plus](https://www.asus.com/de/motherboards-components/motherboards/prime/prime-b550-plus/)
- CPU: [AMD Ryzen 5 3400G](https://www.mindfactory.de/product_info.php/AMD-Ryzen-5-3400G-4x-3-70GHz-So-AM4-BOX_1313642.html)
- RAM: [4x 8GB 2400MHz](https://www.amazon.de/Ballistix-BLS8G4D240FSC-Speicher-PC4-19200-288-Pin/dp/B0198QDLXO/ref=sr_1_7?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Crucial+Ballistix+Sport+LT+BLS4K8G4D240FSC&qid=1630305516&sr=8-7)
- iGPU [AMD Radeon RX Vega 11](https://www.notebookcheck.com/AMD-Radeon-RX-Vega-11-GPU-Ryzen-APU.278618.0.html)
- GPU: [ASRock Intel Arc A380 6GB OC](https://www.asrock.com/Graphics-Card/Intel/Intel%20Arc%20A380%20Challenger%20ITX%206GB%20OC/)
- PSU: [BeQuiet! Pure Power 13 M 550W](https://www.bequiet.com/de/powersupply/5976)
- NIC: [Intel X540-AT2 Dual 10GBit/s](https://www.intel.de/content/www/de/de/products/sku/60020/intel-ethernet-controller-x540at2/specifications.html)
- Case: [Inter-Tech 4U-40248](https://www.inter-tech.de/produktdetails-17/4U-40248.html)
- OS: [TrueNAS Scale](https://www.truenas.com/truenas-scale/)
- Drives:
  - 3x 500GB HHD's
  - 5x 4000GB HHD's
  - 1x 240GB SSD

---

### Other Hardware
- Smartphone: [Samsung Galaxy S26 Ultra 1TB](https://www.samsung.com/de/smartphones/galaxy-s26-ultra/buy/)
- Tablet: [Samsung Galaxy Tab S8+](https://www.samsung.com/de/tablets/galaxy-tab-s8/buy/)
- EarBuds: [Samsung Galaxy Buds 4 Pro](https://www.samsung.com/de/audio-sound/galaxy-buds4-pro/buy/)
- Watch: [Samsung Galaxy Watch 4 44mm](https://www.samsung.com/de/watches/galaxy-watch/galaxy-watch4-black-bluetooth-sm-r870nzkadbt/)
- Internet ISP: [Vodafone 250mbit/s ↓ 40mbit/s ↑](https://www.vodafone.de/)
- Modem: [AMV FRITZ!Box 7530](https://avm.de/produkte/fritzbox/fritzbox-7530/)
- Router: [Ubiquiti UniFi Dream Router 7](https://eu.store.ui.com/eu/en/category/cloud-gateways-wifi-integrated/products/udr7)
- Access Point: [Ubiquiti UniFi U7 Lite](https://eu.store.ui.com/eu/en/category/wifi-flagship/products/u7-lite)

---

### Smart Home
- Smart Home Hub: [Home Assistant](https://www.home-assistant.io/)
- Zigbee Antenna: [Sonoff Zigbee 3.0 USB Dongle Plus](https://sonoff.tech/de-de/products/sonoff-zigbee-3-0-usb-dongle-plus-zbdongle-p)
- Smart Plugs: [TP-Link Tapo P110](https://www.tp-link.com/de/home-networking/smart-plug/tapo-p110/)
- Smoke Detector: [Aqara Smoke Detector](https://www.aqara.com/eu/product/smoke-detector/)
