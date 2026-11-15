<div align="center">

# Hi, I'm Jacob 👋

**I build things across the whole stack — co-op game mods, Minecraft rendering engines,
circuit boards, AI tools and web apps.**

![Projects](https://img.shields.io/badge/projects-34-8A2BE2?style=for-the-badge) ![Mods](https://img.shields.io/badge/game_mods-C%23_%7C_Java-blue?style=for-the-badge) ![Hardware](https://img.shields.io/badge/hardware-ESP32_%7C_KiCad-orange?style=for-the-badge) ![Web](https://img.shields.io/badge/web-Next.js_%7C_Python-black?style=for-the-badge)

</div>

Here's everything I've made. Projects with a link are open to browse;
🔒 ones are private, but described here so you can see what they do.

## 🎮 Games & Mods

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🏎️ | **BetterCar** 🔒 | A rally game mod with handling sliders and a self-driving autopilot that races and drifts the car | Racing-line planner with a lap-time simulator and optimiser, autopilot that drifts sideways ~97% of a lap, automatic overnight car tuning |
| 💣 | **[Cheaty Explody](https://github.com/Jacobalicious/KeepTalkingAndNobodyExplodesBot)** · [🔗 Try it](https://jacobalicious.github.io/KeepTalkingAndNobodyExplodesBot/) | A web helper that solves Keep Talking and Nobody Explodes bomb modules for you | 10 module solvers, maze pathfinding, Morse decoder |
| 🧵 | **Tagalong** 🔒 · [⬇️ Download](https://github.com/Jacobalicious/silksong-tagalong-releases/releases/latest) | Co-op mod for Hollow Knight: Silksong - a friend joins your game as a second Hornet | GPU-encoded video streaming of the second Hornet's view over Steam, independent rooms for each player, up to 4 players with self-updating builds |
| 🦋 | **Silksong Besties** 🔒 · [⬇️ Download](https://github.com/Jacobalicious/silksongbesties-releases/releases/latest) | Full co-op mod for Hollow Knight: Silksong built on SSMP | synced enemies and bosses with co-op targeting, cocoon revives and boss tether, shared loot plus a custom-shader Hornet wardrobe |

## ⛏️ Minecraft

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🐱 | **[A Kitty More](https://github.com/Jacobalicious/akittymore)** · [🔗 Try it](https://jacobalicious.github.io/akittymore/) | A Minecraft datapack of 179 co-op, prank and revenge advancements, plus a live tracker website | co-op advancements with no mod, weird custom items and trophy heads, live advancement tracker site |
| 🏔️ | **Better Render** 🔒 | An infinite-view-distance Minecraft mod built for computers with a small graphics card | Distant world kept in RAM with a capped VRAM window, quadtree block tiles with real textures, background horizon generation |
| 🧪 | **BetterMC Renderer** 🔒 | An early scaffold for a from-scratch Minecraft chunk renderer | Unobfuscated Fabric toolchain for Minecraft 26.2, proof-of-life mixin into the game loop |
| 🎰 | **Gamblerrr Hub** 🔒 | Global live feed and luckiest-player leaderboard server for the Gamblerrr Minecraft mod | rarity-based leaderboard weighted by tries, anti-cheat and verified servers, auto-deploy with rollback |
| 🐛 | **Glitch Hunt** 🔒 | Hunting new bugs and exploits in Minecraft Java 26.3 by reading the code and fuzzing a test server | permanently invulnerable sulfur cube, update suppression via a nether-portal tree, RCON-driven fuzzers |
| 🏡 | **mcbuilding** 🔒 | Python tools for designing a cosy Minecraft house in code | Real-texture software renderer, procedural valley-aware roof, schematic read/write with leak test |
| 🔭 | **Professional MC** 🔒 | A Minecraft mod that draws the world out to 12,000 blocks without eating your graphics card | Terrain to 12,000 blocks in fixed memory, world remembered on disk between sessions, multiplayer land streaming |
| 🐱 | **Purrformance** 🔒 | A Minecraft mod that makes your player dance, including emotes made from your own videos | In-game video-to-emote with local AI pose estimation, player rig with elbows knees and spine, multiplayer relay |

## 🔌 Hardware & Electronics

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🏍️ | **BikeMic** 🔒 | Helmet audio and a live rider map for guided motorcycle tours, one cheap board does both. | One PCB for guide and pods, ESP-NOW digital audio, no-app offline rider map over Wi-Fi |
| 🎛️ | **ESB (Buttonbox)** 🔒 | A pocket synth you power on and play — twelve touch pads, a screen, and its own speaker. | Always-in-key touch keyboard, live chord editing, full on-chip synthesis with drums and reverb |
| 🚪 | **Garage** 🔒 | A cheap ESP8266 + radio kit for security-testing old fixed-code garage openers on your own door. | De Bruijn brute force, phone-controlled web tool, faithful Linear/CAME/NICE receiver sketches |
| 🔇 | **Hidden Speaker** 🔒 | An invisible speaker — a disc behind your ear you hear through your own skull by bone conduction. | Bone-conduction audio, type-on-phone speech over Wi-Fi, browser test rigs and a generated PCB |
| 🎹 | **PocketChord PCB** 🔒 | The circuit board for PocketChord, a handheld chord synth held like a game controller. | Code-generated KiCad design, custom A* grid autorouter, copper touch pads with clean ERC/DRC |
| 🌡️ | **[Matter + Thread Environmental Sensor](https://github.com/Jacobalicious/Temperature-Sensor-over-Matter-Thread)** | A rechargeable temp/humidity/pressure sensor that joins any smart home over Matter, 1.5+ year battery. | Matter over Thread, deep-sleep 99% of the time, adaptive change-based reporting |
| 🧮 | **TI-32** 🔒 | An ESP32 hidden in a TI-84 Plus that answers typed questions on the calculator screen. | Direct AI-over-HTTPS with no PC, self-installing launcher, runs off the calculator's batteries |

## 🧠 AI & Tools

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🔁 | **backtrack** 🔒 | Experiments in how much of an AI model you can copy just by querying its API | NumPy-from-scratch distillation, seven API defence policies tested, GPT-2 teacher experiment |
| 🪰 | **A Fly Brain You Can Poke** 🔒 | A spiking simulation of a real fruit fly brain wired by 14.3 million real synapses, with nothing trained | Escape reflex emerges from real wiring, simulated fly forages and dodges in a virtual arena, live 3D browser sandbox of 4,186 neurons |
| 📉 | **Optamize** 🔒 | A data-driven investigation into what an AI coding assistant costs, and a plugin that fixes it | 11,430 requests measured and priced, ranked fix plan projecting a ~54% cut, smart model routing plugin |
| ✏️ | **[paper-editor](https://github.com/Jacobalicious/paper-editor)** · [🔗 Try it](https://jacobalicious.github.io/paper-editor/) | Fixes wrong answers in a photo of handwritten work, in the writer's own handwriting | AI grading checked with SymPy, invisible erase and inpaint, handwriting-matched pen strokes |
| 🚁 | **[PetDrone](https://github.com/Jacobalicious/PetDrone)** | Make a DJI Tello drone follow you around, tracking your face or hand with its camera. | Real-time face and hand tracking, smooth proportional flight control, safety speed limits |
| 🖍️ | **Red Pen** 🔒 · [🔗 Try it](https://red-pen-beta.vercel.app) | Snap a photo of handwritten math work and get it marked line by line like a teacher would | Red-pen corrections drawn on the exact wrong character, grades whole multi-problem worksheets, animated step-by-step explainers |
| 🥗 | **[token-diet](https://github.com/Jacobalicious/token-diet)** | A plugin that keeps AI coding assistant sessions cheap by trimming the context they re-read | auto-clears on a new task, compacts big or idle sessions, half-size screenshots |

## 🌐 Web Apps

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🦅 | **DealHawk** 🔒 · [🔗 Try it](https://deal-hawk-kohl.vercel.app) | Watches used car and motorcycle listings and emails you when one matches your search | Four listing sources incl. eBay and Craigslist, price-drop history graphs, twice-daily automatic poller with email alerts |
| 📺 | **[Brain Damage Jeopardy](https://github.com/Jacobalicious/jeopardy)** · [🔗 Try it](https://jacobalicious.github.io/jeopardy/) | A deliberately terrible trivia game show you host from your phone and play on the TV | Chromecast and room-code TV connection via a hand-written MQTT client, 10 themes, synthesized sound effects |
| 🌊 | **[SailKind Global Voices](https://github.com/Jacobalicious/sailkind-global-voices)** · [🔗 Try it](https://sailkind.com) | An interactive world map of ocean conservation stories from communities around the globe | Clickable story map with photo slideshows, Google Form submissions with a password-protected review dashboard, stories go live within seconds |
| 📺 | **[StreamSheet](https://github.com/Jacobalicious/StreamSheet)** | Watch YouTube from Google Sheets via a service that turns a video ID into a Drive link | YouTube safety checks, 720p download with yt-dlp, auto-shared Google Drive upload |

## ⚙️ Data & Automation

| | Project | What it does | Highlights |
|:-:|---|---|---|
| 🧾 | **Chandler Receipts** 🔒 | Turns a folder of receipt photos into a filed expense report without claiming anything twice | rotation-proof image fingerprint duplicate check, polished PDF reports, one-command Expensify upload |
| 🗺️ | **[K-Mapper](https://github.com/Jacobalicious/K-Mapper)** | Turns a spreadsheet of addresses into colour-coded saved pins on KakaoMap automatically | Headless-browser Kakao sign-in with self-healing sessions, colour-coded pins by status, batched uploads of hundreds of locations |
| 💬 | **LinkedIn Message Helper** 🔒 | Walks you through sending a personalised LinkedIn message to a list of people, one at a time, safely | Personalised message templates from a CSV, connection check against LinkedIn's own export, built-in safe pacing with daily limits |
| 🎬 | **RanchVideos** 🔒 | A Hawaii ranch climb video edited entirely in code with Python and FFmpeg | beat-synced shot list, automatic stabilisation and colour grading, Real-ESRGAN AI upscaling |

---

<sub>Plus helper repos that keep the big ones running: one-click installers for the Silksong
mods, update noticeboards for the Minecraft mods, and the video-to-dance converter for Purrformance.</sub>
