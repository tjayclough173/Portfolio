# Tjay Clough

Welcome to my portfolio! I am a hands-on technologist with a strong foundation in Linux administration, infrastructure, game server architecture, and software tinkering. Passionate about self-hosting, hardware modifications, and building technical systems from the ground up.

---

### About Me
I enjoy tinkering with infrastructure, managing self-hosted services, and exploring the intersection of systems engineering and creative tech. Whether it's upgrading laptop hardware, configuring Docker containers, building custom multi-API apps, or pushing resource-constrained hardware to its absolute limits, I love solving technical puzzles.

---

### Skills & Technologies
* **Systems & OS:** Windows 11, Linux (Ubuntu, headless servers, Chromebook Crostini, Kali Linux), Package Management (`apt`), Command-Line Navigation, File Permissions
* **Infrastructure & Networking:** Docker, Docker Compose, LogMeIn Hamachi (Virtual LAN / P2P VPNs, Ad-Hoc Gaming Networks), Virtualization (VirtualBox)
* **Services & Game Hosting:** Jellyfin, Minecraft (PaperMC, MultiMC, Java runtimes), Team Fortress 2 (Dedicated servers, Source Engine, custom maps & bots)
* **Web & Programming:** JavaScript, Node.js, Discord.js, Python, HTML, CSS, REST APIs, JSON Parsing
* **Creative Tech & Hardware:** Blender (3D modeling, texturing, rendering), Adobe Photoshop, DaVinci Resolve, CapCut, Laptop Hardware Upgrades (RAM installation)

---

### Featured Projects & Experience

#### 1. Multi-API Music Player Development
* **What I did:** Designed and built a custom music player application capable of querying and streaming tracks dynamically by integrating multiple external media storage and streaming APIs (including YouTube Music).
* **Why I did it:** Out of a desire to build a custom, all-in-one music utility that combined multiple backend sources into a single unified interface.
* **What went badly:** Handling asynchronous API rate limits, parsing complex nested JSON payloads from different media services, and managing state across playback controls.
* **How I fixed it:** Implemented robust error handling for API responses, structured modular API client wrappers, and managed state hooks to ensure seamless track searching and playback queuing.
* **Tech Stack:** JavaScript/Python, REST APIs, JSON Parsing, External Media APIs (YouTube Music)

#### 2. Portable Virtualization: Kali Linux on USB
* **What I did:** Configured a portable Kali Linux environment using VirtualBox running entirely out of a high-capacity USB drive.
* **Why I did it:** To create an isolated, portable penetration-testing and cybersecurity toolkit that could run on any compatible host machine.
* **What went badly:** Attempted to also build a portable Windows XP environment, but hit a dead end due to broken/unavailable legacy download links and driver incompatibility. 
* **How I fixed it:** Pivoted away from the dead Windows XP project, focused efforts entirely on the VirtualBox USB persistence setup, and configured USB controller pass-through rules to ensure stable drive performance.
* **Tech Stack:** VirtualBox, Kali Linux, USB Mass Storage, Virtualization

#### 3. Laptop Hardware Upgrade: RAM Installation
* **What I did:** Physically upgraded a Windows 11 laptop by opening the chassis and installing an 8GB DDR4 RAM stick into the secondary open slot, doubling system memory from 8GB to 16GB.
* **Why I did it:** To eliminate hardware bottlenecks when multitasking heavy workloads like virtualization, video editing, and game servers.
* **What went badly:** Working with tight laptop casing clips and ensuring electrostatic discharge (ESD) safety while handling bare hardware components.
* **How I fixed it:** Used proper non-conductive opening tools, carefully mapped screw placements, and verified memory recognition in BIOS post-installation.
* **Tech Stack:** Hardware Engineering, DDR4 RAM, Windows 11 Laptop Architecture

#### 4. Self-Hosted Home Media Server (Windows 11)
* **What I did:** Deployed and managed a personal local media streaming server using Jellyfin on a Windows 11 host machine.
* **Why I did it:** To build a centralized, self-hosted alternative to commercial streaming services for personal media consumption.
* **What went badly:** File path permission errors, metadata scraping timeouts, and occasional transcoding bottlenecks when streaming high-bitrate video to external devices.
* **How I fixed it:** Adjusted local user folder permissions, optimized Jellyfin hardware acceleration settings, and organized local media directory structures for clean metadata indexing.
* **Tech Stack:** Windows 11, Jellyfin, Local Storage Infrastructure

#### 5. Dedicated Multiplayer Game Server Architecture & Virtual LAN Networking
* **What I did:** Hosted custom Minecraft Java servers from scratch using official binaries, built standalone Team Fortress 2 dedicated servers running custom workshop maps, and utilized **LogMeIn Hamachi** to establish secure peer-to-peer virtual LAN (VLAN) ad-hoc networks for friends to connect seamlessly.
* **Why I did it:** To bypass restrictive router firewalls and lack of native multiplayer hosting, allowing friends to connect securely for local-play games and Minecraft sessions.
* **What went badly:** Network port-forwarding blocks, firewall rules dropping incoming packets, and high memory leaks causing server crashes during heavy loads.
* **How I fixed it:** Configured Hamachi virtual tunneling to bypass complex NAT/router configurations when direct port-forwarding failed, optimized JVM garbage collection flags for Minecraft, and streamlined TF2 configuration files.
* **Tech Stack:** Minecraft Java Server, Source Engine / Team Fortress 2, LogMeIn Hamachi (VLAN), Linux/Windows CLI, Networking

#### 6. Creative Suite & 3D Pipeline Mastery
* **What I did:** Mastered advanced media production, photo editing, video editing, and 3D asset pipelines using Adobe Photoshop, CapCut, DaVinci Resolve, and Blender.
* **Why I did it:** To push personal creative projects, video production, and 3D design capabilities to a professional standard.
* **What went badly:** Heavy render pipelines, large video bitrates, and complex 3D scenes constantly choked hardware resources, causing long render times and software crashes.
* **How I fixed it:** Optimized Blender render settings (balancing GPU/CPU workloads), managed proxy workflows in DaVinci Resolve, and tuned hardware resource allocation.
* **Tech Stack:** Blender, Adobe Photoshop, DaVinci Resolve, CapCut

#### 7. A-Level Computer Science Unity Mini-Game (Age 16)
* **What I did:** Developed a playable mini-game from scratch using the Unity engine and C# as part of my coursework.
* **Why I did it:** Completed as a mandatory, graded core component of my Computer Science A-Level curriculum.
* **What went badly:** Encountered typical game development bugs, collision logic issues, and state-management glitches during coding.
* **How I fixed it:** Systematically isolated bugs via console debugging, refactored C# scripts, and leaned heavily on structured design paperwork to document the build process. Finished with a strong **B grade** on the project.
* **Tech Stack:** Unity, C#, Visual Studio, Formal Development Documentation

#### 8. Early Web Development & Python Tinkering (Before Age 16)
* **What I did:** Experimented with foundational web layouts using HTML, CSS, and JavaScript, alongside writing beginner Python scripts.
* **Why I did it:** Early exploration and foundational self-teaching into how software and the web actually work under the hood.
* **What went badly:** Typical beginner syntax errors, unstructured code, and figuring out how logic flows without a formal guide.
* **How I fixed it:** Used trial-and-error debugging, online documentation, and small isolated script tests to build core programming logic.
* **Tech Stack:** HTML, CSS, JavaScript, Python

#### 9. Node.js & Discord.js Bot Development (Ages 13–15)
* **What I did:** Built a semi-functional Discord bot from scratch using Node.js and Discord.js inside VS Code on a heavily constrained Chromebook.
* **Why I did it:** Out of raw curiosity to bridge coding with interactive applications.
* **What went badly:** Hit a major compatibility wall—the constrained environment couldn't install the latest Java runtime required for the version of Node.js, breaking core dependencies.
* **How I fixed it:** Scaled back to a compatible older version of Node/Java that the system could handle to get the bot logic running, and diagnosed hardware/OS architectural limits.
* **Tech Stack:** JavaScript, Node.js, Discord.js, VS Code, Linux CLI

#### 10. Chromebook Linux Environment & Resource Benchmarking (Ages 13–15)
* **What I did:** Configured Linux (Crostini) on an ultra-constrained Chromebook to run advanced desktop applications like Steam, MultiMC, Blender, and VS Code. 
* **Why I did it:** Driven purely by curiosity to test the absolute hardware and software limits of a 2GB RAM system.
* **What went badly:** Severe memory constraints (2GB RAM) and architecture limits made running heavy desktop software sluggish, frequently crashing the container.
* **How I fixed it:** Optimized package management (`apt`), managed storage allocation tightly, and learned how to leverage lightweight configurations to keep the environment stable.
* **Tech Stack:** ChromeOS Linux (Crostini), Steam, MultiMC, Blender, VS Code

---

### Hardware & Environment Specs

#### Primary Workstation (Age 17–Present)
#### Primary Workstation (Age 17–Present)
* **Model:** ASUS Vivobook 15
* **Processor:** Intel Core i3
* **Memory:** 16GB DDR4 RAM *(Upgraded from 8GB via secondary internal SODIMM slot)*
* **Storage:** 500GB SSD
* **Operating System:** Windows 11 (with VirtualBox for isolated Linux environments)

#### Early Development Machine (Ages 13–17)
* **Model:** Lenovo IdeaPad 3 Chromebook (11")
* **Processor:** Intel Celeron N4020 / AMD A-Series (x86-64 architecture)
* **Graphics:** Integrated Intel UHD Graphics 600 / AMD Radeon R4/R5
* **Memory:** 2GB LPDDR4 RAM
* **Storage:** 64GB eMMC Flash Storage
* **Display:** 11.6" HD (1366 x 768) TN Display
* **Operating System:** ChromeOS + Linux Development Environment (Crostini)

---

### Get in Touch
* **Email:** tjayclough173@hotmail.com
* **LinkedIn:** https://www.linkedin.com/in/tjay-clough-8130bb403/
* **GitHub:** https://github.com/tjayclough173
