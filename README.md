<!-- **MCmoderSD/MCmoderSD** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->

## About Me

**Name:** Seraphin Berger <br>
**Age:** 21 <br>
**Location:** Germany 🇩🇪 <br>
**Occupation:** Student <br>
**Education:** Pursuing [B.Eng. Software Engineering and Media Computing](https://www.hs-esslingen.de/en/softwaretechnik-und-medieninformatik) <br>
**University:** [Hochschule Esslingen - University of Applied Sciences](https://www.hs-esslingen.de/) <br>
**Experience:** Knowledgeable in Java, Linux, and server management <br>

## Technologies & Tools

- **Languages**: Java, C#, SQL
- **IDE's**: [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Visual Studio Code](https://code.visualstudio.com/)
- **Database**: MariaDB/MySQL
- **Systems**: Debian-based servers, [TrueNAS Scale](https://www.truenas.com/truenas-scale/)

## Contact

- **Business Email**: [business@mcmodersd.de](mailto:business@mcmodersd.de)
- **Discord**: [MCmoderSD](https://mcmodersd.de/dc)

## Socials

[![Homepage](https://img.shields.io/badge/MCmoderSD.de-000?style=for-the-badge&logo=&logoColor=white&height=30)](https://www.MCmoderSD.de/)
[![Steam](https://img.shields.io/badge/Steam-000?style=for-the-badge&logo=steam&logoColor=white&height=30)](https://www.MCmoderSD.de/steam)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white&height=30)](https://www.MCmoderSD.de/twitter)
[![Twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white&height=30)](https://www.MCmoderSD.de/ttv)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white&height=30)](https://www.MCmoderSD.de/yt)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white&height=30)](https://www.MCmoderSD.de/reddit)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&height=30)](https://www.MCmoderSD.de/insta)
[![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white&height=30)](http://www.MCmoderSD.de/spotify)

## Projects

### [YEPPBot](https://github.com/MCmoderSD/YEPPBot)
This repository hosts the source code for the YEPPBot, a comprehensive Twitch bot featuring numerous tools to entertain and manage your Twitch channel.

#### Technologies Used
- **Java**: The primary programming language used for developing the Twitch bot.
- **Docker**: Used for containerizing the application, making it easy to deploy and manage.
- **GitHub Actions**: Used for continuous integration and deployment automation through YAML configuration.

#### Purpose
The main purpose of this repository is to provide a versatile and feature-rich Twitch bot that can help manage and enhance your Twitch channel. <br>
It demonstrates the ability to create, build, deploy, and maintain a complex Java-based application that interacts with the Twitch platform.

#### Key Features
- **Automated Build and Deployment**: Utilizes GitHub Actions for CI/CD and multi-architecture support releases.
- **Multi-API Integration**: Integrates with various third-party APIs to provide a wide range of functionalities:
  - **[OpenAI-Wrapper](https://www.GitHub.com/MCmoderSD/OpenAI-Wrapper/)**: A custom wrapper to interact with OpenAI APIs for advanced functionalities.
  - **[OpenWeatherMap](https://www.GitHub.com/MCmoderSD/OpenWeatherMap/)**: Fetches weather information to provide real-time weather updates in the chat.
  - **[RiotGames-API](https://www.GitHub.com/MCmoderSD/RiotGames-API/)**: Tracks and displays player ranks and stats for games like League of Legends.
- **Chat Commands**: Provides a wide range of chat commands to engage with viewers and manage the chat more effectively.
- **Customizable Features**: Offers customizable features and settings to tailor the bot's behavior to the specific needs of the channel.
- **High Availability**: Connected to a redundant MariaDB database for high availability and failover.
- **Optimized Performance**: The bot runs very efficiently on a Raspberry Pi and gets auto-updates via Docker Watchtower.

This repository serves as a demonstration of my skills in developing, integrating, and managing a complex Java application with practical applications in the real world.  <br>
It is my biggest project yet, highlighting my proficiency in building scalable, maintainable, and feature-rich software solutions.

---

### [MCmoderSD.de](https://www.GitHub.com/MCmoderSD/MCmoderSD.de/)
This repository hosts the source code for my personal website, encapsulated as an all-in-one Docker image. 
It serves as a comprehensive portfolio showcasing my skills in continuous integration and deployment automation.

#### Technologies Used
- **HTML**: The primary markup language for the website's structure.
- **CSS**: Used for styling the website, ensuring a visually appealing and responsive design.
- **Dockerfile**: Scripts for containerizing the application, making it easy to deploy and manage.
- **GitHub Actions**: Used for continuous integration and deployment automation through YAML configuration.

#### Purpose
The main purpose of this repository is to serve as my personal website. 
It demonstrates my ability to integrate various technologies and tools to build, deploy, and maintain a web application.

#### Key Features
- **Workflow Automation**: Utilizes GitHub Actions for continuous integration and continuous deployment (CI/CD). This includes building the Docker image and deploying updates seamlessly.
- **Docker Hosting**: The website is hosted within a Docker container, providing a consistent environment across different deployment platforms. The container runs behind a reverse proxy for enhanced performance and security.
- **Auto-Update with Watchtower**: Watchtower is used to monitor the Docker container for updates. Whenever an update is available, Watchtower automatically pulls the latest version and restarts the container to apply the update without downtime.
- **Multi-Arch Image**: The Docker image is a multi-architecture image, supporting amd64, arm64, and other architectures. This is essential as the Docker host is a Raspberry Pi at my home.
- **Optimized Performance**: The Docker image is very slim and performant, requiring minimal space and resources to run efficiently.

---

### [JSQL-Driver](https://www.GitHub.com/MCmoderSD/JSQL-Driver/)
This repository hosts the source code for a simple Java SQL driver designed to connect to SQL databases, compatible with MySQL, MariaDB, and PostgreSQL. 
It is built to provide a straightforward and efficient way to interact with SQL databases using Java.

#### Technologies Used
- **Java**: The primary programming language used for developing the SQL driver.
- **GitHub Actions**: Used for continuous integration and deployment automation through YAML configuration.

#### Purpose
The main purpose of this repository is to offer a minimalistic and efficient SQL driver for Java applications. 
It showcases the ability to create, build, and deploy a Java-based library that can be seamlessly integrated into other projects.

#### Key Features
- **Automated Build and Deployment**: Utilizes GitHub Actions for continuous integration and continuous deployment (CI/CD). This includes building the JAR file and deploying it to my Sonatype Nexus OSS Maven Repository, a self-hosted repository for distributing Maven dependencies.
- **Workflow Automation**: The GitHub Actions workflow compiles the Java code, packages it into a JAR file, and deploys it to the Sonatype Nexus OSS Maven Repository, ensuring that every commit is automatically built and deployed.
- **Release Management**: Automatically generates a release on GitHub with the built JAR file and its hashes, providing an added layer of security by allowing users to verify the authenticity and integrity of the downloaded files.


## Hardware

### [Main Rig](https://pcpartpicker.com/list/zttyWc)
- Mainboard: [Asus ROG Strix B550-F Gaming WiFi 2](https://rog.asus.com/de/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/)
- CPU: [AMD Ryzen 7 5800X](https://www.amd.com/de/products/cpu/amd-ryzen-7-5800x)
- AIO Liquid Cooler: [NZXT Kraken X63 RGB](https://nzxt.com/product/kraken-x63-rgb)
- RAM: [Corsair Vengeance RGB Pro 2x32GB 3600MHz CL18](https://www.corsair.com/de/de/p/memory/cmw64gx4m2d3600c18/vengeance-rgb-pro-64gb-2-x-32gb-ddr4-dram-3600mhz-c18-memory-kit-black-cmw64gx4m2d3600c18)
- GPU: [MSI Nvidia GeForce RTX 3060 12GB Gaming Z Trio](https://www.msi.com/Graphics-card/GeForce-RTX-3060-GAMING-Z-TRIO-12G)
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
  - 1st: [AOC AGON AG251FZ 240hz](https://agon.aocmonitorap.com/my/product_ag251fz.php)
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
- VR Headset: [HTC Vive Cosmos](https://www.vive.com/de/product/vive-cosmos/overview/)

--- 

### Mobile
- Notebook: [HP 255 15.6 inch G10](https://www.notebooksbilliger.de/hp+255+g10+853t0es+805699)
- CPU: [AMD Ryzen 5 7530U](https://www.amd.com/de/products/processors/laptop/ryzen/7000-series/amd-ryzen-5-7530u.html)
- RAM: [2x Crucial 16GB DDR4-3200 CL22](https://www.notebooksbilliger.de/crucial+16gb+ddr4+3200+cl22+683186)
- GPU: [AMD ATI Barcelo](https://www.techpowerup.com/gpu-specs/amd-barcelo.g1045)
- NVMe: [Samsung 970 EVO 1TB](https://www.samsung.com/de/memory-storage/solid-state-drives/ssd-970-evo-plus-nvme-m-2-1tb-mz-v7s1t0b/)
- OS [Kubuntu 24.10 with KDE Plasma 6.1.5](https://kubuntu.org/getkubuntu/)
- Mouse: [SteelSeries Rival 3](https://de.steelseries.com/gaming-mice/rival-3-wireless)

---

### [Home Server](https://pcpartpicker.com/list/W9NkGP)
- Mainboard: [Asus Prime B450M-A II](https://www.asus.com/de/motherboards-components/motherboards/prime/prime-b450m-a-ii/)
- CPU: [AMD Ryzen 5 3400G](https://www.mindfactory.de/product_info.php/AMD-Ryzen-5-3400G-4x-3-70GHz-So-AM4-BOX_1313642.html)
- RAM: [4x 8GB 2400MHz](https://www.amazon.de/Ballistix-BLS8G4D240FSC-Speicher-PC4-19200-288-Pin/dp/B0198QDLXO/ref=sr_1_7?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=Crucial+Ballistix+Sport+LT+BLS4K8G4D240FSC&qid=1630305516&sr=8-7)
- iGPU [AMD Radeon RX Vega 11](https://www.notebookcheck.com/AMD-Radeon-RX-Vega-11-GPU-Ryzen-APU.278618.0.html)
- GPU: [Nvidia GT 720 2GB](https://www.mindfactory.de/product_info.php/2GB-MSI-GeForce-GT-720-GDDR5-Passiv-PCIe-2-0-x-8--Retail-_982919.html)
- PSU: [BeQuiet! System Power 9](https://www.bequiet.com/de/powersupply/1281)
- OS: [TrueNAS Scale](https://www.truenas.com/truenas-scale/)
- Drives:
  - 3x 500GB HHD's
  - 5x 4000GB HHD's
  - 1x 240GB SSD

---

### Other Hardware

- Smartphone: [Samsung Galaxy S23+](https://www.samsung.com/de/smartphones/galaxy-s23/buy/)
- Tablet: [Samsung Galaxy Tab S6 Lite](https://www.samsung.com/de/tablets/galaxy-tab-s/galaxy-tab-s6-lite-wi-fi-2022-edition-gray-128gb-sm-p613nzaedbt/)
- EarBuds: [Samsung Galaxy Buds 3 Pro](https://www.samsung.com/de/audio-sound/galaxy-buds/galaxy-buds3-pro-silver-sm-r630nzaadbt/)
- Watch: [Samsung Galaxy Watch 4 44mm](https://www.samsung.com/de/watches/galaxy-watch/galaxy-watch4-black-bluetooth-sm-r870nzkadbt/)
- Internet ISP: [Vodafone 250mbit/s ↓ 40mbit/s ↑](https://www.vodafone.de/)
- Router/Modem: [AMV FRITZ!Box 7530](https://avm.de/produkte/fritzbox/fritzbox-7530/)
- Router Access Point: [AMV FRITZ!Box 7430](https://www.mediamarkt.de/de/product/_avm-fritzbox-7430-20002733-router-107835303.html)
- Lights: [Govee RGBIC LED Strip](https://www.amazon.de/gp/product/B093PRYW1D/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1)