# Awesome Computer Use

> A curated list of open-source projects that let AI click, type, scroll, and generally make a mess of your desktop — so you don't have to.

Your AI can write poetry, debug code, and explain quantum physics. But ask it to open Spotify and it stares at you blankly. **Not anymore.**

Computer-use agents (CUAs) are AI systems that see your screen, understand what's on it, and interact with it — just like a human would, minus the coffee breaks and existential dread.

---

## Contents

- [Desktop Agents](#desktop-agents)
- [Browser Agents](#browser-agents)
- [Mobile Agents](#mobile-agents)
- [Vision and Grounding Models](#vision-and-grounding-models)
- [Screen Capture and Recording](#screen-capture-and-recording)
- [OCR and Screen Reading](#ocr-and-screen-reading)
- [Desktop Automation Libraries](#desktop-automation-libraries)
- [RPA Tools](#rpa-tools)
- [MCP Servers for Desktop](#mcp-servers-for-desktop)
- [Sandbox and Containerization](#sandbox-and-containerization)
- [Voice-Controlled Agents](#voice-controlled-agents)
- [Agent Memory](#agent-memory)
- [Agent Orchestration](#agent-orchestration)
- [Agent Testing and Evaluation](#agent-testing-and-evaluation)
- [Game-Playing Agents](#game-playing-agents)
- [Training Data Tools](#training-data-tools)
- [Screen Understanding](#screen-understanding)
- [Browser Extension Agents](#browser-extension-agents)
- [Desktop-Native AI Assistants](#desktop-native-ai-assistants)
- [IDE-Based Agents](#ide-based-agents)
- [Research Papers](#research-papers)
- [Related Awesome Lists](#related-awesome-lists)

---

## Desktop Agents

The full package. These see your screen, click things, type things, and occasionally crash things.

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenInterpreter](https://github.com/OpenInterpreter/open-interpreter) | 55k+ | Run code locally via natural language. The OG. |
| [Self-Operating Computer](https://github.com/OthersideAI/self-operating-computer) | 10.2k | Framework for multimodal models to operate a computer |
| [Bytebot](https://github.com/bytebot-ai/bytebot) | 10.5k | Self-hosted AI desktop agent in Docker |
| [Agent S](https://github.com/simular-ai/agent-s) | 3k+ | SOTA on OSWorld 72.6%, beats OpenAI CUA |
| [GenericAgent](https://github.com/lsdefine/GenericAgent) | 740 | Minimal 3,300 LOC self-evolving agent |
| [Ghost OS](https://github.com/ghostwright/ghost-os) | Growing | macOS AX tree + local VLM, self-learning recipes |
| [TuriX](https://github.com/TurixAI/TuriX-CUA) | Growing | Desktop automation, OpenClaw integration |
| [Atlas](https://github.com/dortanes/atlas) | 7 | Electron overlay, Gemini native CUA |
| [Open Computer Use](https://github.com/coasty-ai/open-computer-use) | New | Full-stack platform, multi-provider |
| [Cua](https://github.com/trycua/cua) | Growing | Containers for computer-use agents |
| [Fara-7B](https://github.com/microsoft/fara) | 500 | Microsoft's efficient small model for CUA |
| [Cuse](https://github.com/cuse-dev/cuse) | 400 | Open framework for building CUA agents |
| [Clevrr Computer](https://github.com/Clevrr-AI/Clevrr-Computer) | 309 | Open-source Anthropic CUA with PyAutoGUI |
| [Cuse Agent](https://github.com/e2b-dev/cuse-agent) | 300 | CUA with E2B virtual desktop sandbox |
| [Agent Desktop](https://github.com/lahfir/agent-desktop) | 100 | Native Rust CLI, AX-first, no screenshots |
| [IrisGUI](https://github.com/black-yt/IrisGUI) | 50 | Lightweight with Dynamic Focus Vision |
| [Computer-Use-Agent](https://github.com/nabhpatodi10/Computer-Use-Agent) | 20 | Windows CUA with LangGraph + OmniParser |
| [VNC-Use](https://github.com/mayflower/vnc-use) | 30 | LangGraph agent via VNC, multi-model |
| [Gofer](https://github.com/jleuth/gofer) | 20 | AI agent controllable via Telegram |
| [AskUI Vision Agent](https://github.com/askui/vision-agent) | 200 | Automate desktop, mobile, and HMI devices |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 40k+ | Software dev agents that browse, code, run commands |
| [TongUI Agent](https://github.com/TongUI-agent/TongUI-agent) | 77 | VLA model learning from web tutorials |
| [Accomplish](https://github.com/accomplish-ai/accomplish) | 500 | Open-source AI desktop agent, local-first |
| [Oboto](https://github.com/sschepis/oboto) | 24 | Everything assistant with persistent cognitive architecture |
| [Magentic-UI](https://github.com/microsoft/magentic-ui) | 500 | Human-centered web agent with approval workflows |
| [Open Computer Use (E2B)](https://github.com/e2b-dev/open-computer-use) | 3k+ | Cloud sandbox + open-source LLMs |
| [Cybergod](https://github.com/james4ever0/agi_computer_control) | Small | AGI computer control framework |

---

## Browser Agents

For when your AI only needs to wreck things on the web.

| Project | Stars | Description |
|---------|-------|-------------|
| [Browser-Use](https://github.com/browser-use/browser-use) | 84k | SOTA browser automation, makes websites LLM-friendly |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | 10k+ | Vision-driven web automation, no coded selectors |
| [Nanobrowser](https://github.com/nanobrowser/nanobrowser) | 12.5k | Chrome extension, multi-agent |
| [Fuji-Web](https://github.com/normal-computing/fuji-web) | 500 | Chrome extension with step-by-step explanations |
| [UI-Act](https://github.com/TobiasNorlund/UI-Act) | Small | Grounded UI interaction |
| [WebMarker](https://github.com/reidbarber/webmarker) | Small | Web annotation for agents |
| [Notte](https://github.com/nott-ai/notte) | Growing | Reliable browser AI framework |
| [LaVague](https://github.com/lavague-ai/LaVague) | Growing | Natural language web automation |

---

## Mobile Agents

AI that taps, swipes, and scrolls on your phone so you can doom-scroll guilt-free.

| Project | Stars | Description |
|---------|-------|-------------|
| [Open-AutoGLM](https://github.com/THUDM/AutoGLM) | 23.6k | Phone agent with vision-language model for Android |
| [AppAgent](https://github.com/TencentQQGYLab/AppAgent) | 6.6k | LLM-based multimodal agent for smartphone apps |
| [Mobile-Use (madeagents)](https://github.com/madeagents/mobile-use) | 200 | Any app, any task; NeurIPS 2025 |
| [Mobile-Use (minitap)](https://github.com/minitap-ai/mobile-use) | 100 | Automate Android/iOS with natural language |
| [CoCo-Agent](https://github.com/xbmxb/CoCo-Agent) | 100 | Smartphone GUI automation, ACL 2024 |

---

## Vision and Grounding Models

The eyes of computer-use. These models see and understand what is on screen.

| Project | Stars | Description |
|---------|-------|-------------|
| [ShowUI](https://github.com/showlab/ShowUI) | 1.5k | Lightweight VLM for GUI agent and CUA |
| [OS-Atlas](https://github.com/os-copilot/os-atlas) | 442 | Foundation Action Model for Generalist GUI Agents |
| [OmniParser](https://github.com/microsoft/OmniParser) | 5k | Screen parsing for pure vision-based GUI agents |
| [UGround](https://github.com/OSU-NLP-Group/UGround) | 600 | Universal Visual Grounding, ICLR 2025 Oral |
| [UI-Venus](https://github.com/inclusionAI/UI-Venus) | 1.2k | Native UI agent, SOTA on ScreenSpot-Pro |
| [CogAgent](https://github.com/THUDM/CogAgent) | 2.5k | Open-sourced VLM-based GUI Agent, CVPR 2024 |
| [GUI-Libra](https://github.com/GUI-Libra/GUI-Libra) | 50 | Post-training framework for GUI agents |
| [GUI-G1](https://github.com/Yuqi-Zhou/GUI-G1) | 100 | R1-Zero-like training for GUI grounding |
| [ScreenSpot-Pro](https://github.com/likaixin2000/screenspot-pro-gui-grounding) | 200 | GUI Grounding benchmark for high-res |
| [Screen-Point-and-Read](https://github.com/eric-ai-lab/Screen-Point-and-Read) | 100 | Layout-aware GUI screen reading |
| [ShowUI-Aloha](https://github.com/showlab/ShowUI-Aloha) | 100 | Human-taught computer-use agent |
| [SeeClick](https://github.com/nicehuster/AITQE) | Growing | Harnessing GUI grounding for visual agents |

---

## Screen Capture and Recording

Taking screenshots for AI so it knows what is going on.

| Project | Stars | Description |
|---------|-------|-------------|
| [Peekaboo](https://github.com/steipete/Peekaboo) | 2.9k | macOS screen capture + AI analysis + MCP server |
| [Screenpipe](https://github.com/screenpipe/screenpipe) | 17.5k | Continuous screen/audio recording, searchable AI memory |
| [MacOS Visual Agent](https://github.com/peakmojo/macos-visual-agent) | 50 | On-device screen understanding via Apple AX APIs |
| [CaptiOCR](https://github.com/carlosacchi/captiocr) | 6 | Real-time OCR for video conferencing |

---

## OCR and Screen Reading

Turning pixels into text your AI can actually read.

| Project | Stars | Description |
|---------|-------|-------------|
| [NormCap](https://github.com/dynobo/normcap) | 3.5k | OCR-powered screen-capture, capture text not images |
| [OpenOCR](https://github.com/Topdu/OpenOCR) | 1.2k | General OCR toolkit from Fudan University |
| [AgentOCR](https://github.com/AgentMaker/AgentOCR) | 300 | Multi-language OCR with PaddleOCR + ONNX |
| [LOCR](https://github.com/dmzlingyin/LOCR) | 100 | Lightweight auto-extract OCR, cross-platform Go |
| [Prism AI](https://github.com/chrismannina/prism-ai-screen-reader) | 10 | AI screen reader with OCR, privacy-first |

---

## Desktop Automation Libraries

The plumbing behind the magic. Low-level tools that do the actual clicking.

| Project | Stars | Description |
|---------|-------|-------------|
| [PyAutoGUI](https://github.com/asweigart/pyautogui) | 10k+ | Cross-platform GUI automation for Python |
| [nut.js](https://github.com/nut-tree/nut.js) | 2.8k | Native UI automation for Node.js |
| [RobotJS](https://github.com/octalmage/robotjs) | 12k+ | Node.js Desktop Automation |
| [guibot](https://github.com/intra2net/guibot) | 200 | GUI automation with computer vision |
| [qontinui](https://github.com/jspinak/qontinui) | 30 | Model-based GUI automation with state management |
| [libnut-core](https://github.com/nut-tree/libnut-core) | 50 | Node-API addon for desktop automation |

---

## RPA Tools

Robotic Process Automation, but make it AI.

| Project | Stars | Description |
|---------|-------|-------------|
| [rpaframework](https://github.com/robocorp/rpaframework) | 1k+ | Open-source RPA libraries for Robot Framework |
| [TagUI-Python](https://github.com/tebelorg/RPA-Python) | 5k+ | Leading open-source Python RPA tool |
| [astron-rpa](https://github.com/iflytek/astron-rpa) | 50 | Enterprise-grade RPA with LLM integration |
| [AIVANE](https://github.com/taiyouqu/aivane) | 20 | AI+RPA cross-platform control |

---

## MCP Servers for Desktop

Model Context Protocol servers that give your AI desktop superpowers.

| Project | Stars | Description |
|---------|-------|-------------|
| [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 2k+ | Terminal control, file system, diff editing |
| [Peekaboo MCP](https://github.com/steipete/Peekaboo) | 2.9k | macOS capture + AI + MCP |
| [Computer Control MCP](https://github.com/AB498/computer-control-mcp) | 124 | Mouse, keyboard, OCR via PyAutoGUI |
| [System MCP](https://github.com/aurafriday/system_mcp) | 50 | Full desktop automation, multi-platform |
| [Desktop Automation MCP](https://github.com/tanob/mcp-desktop-automation) | 50 | RobotJS-based desktop automation |
| [Windows Desktop Automation MCP](https://github.com/mario-andreschak/mcp-windows-desktop-automation) | 20 | Windows desktop automation via AutoIt |
| [ScreenMonitor MCP](https://github.com/inkbytefo/ScreenMonitorMCP) | 71 | Real-time screen capture and vision |
| [QuickDesk](https://github.com/barry-ran/QuickDesk) | 115 | AI-native remote desktop with MCP |
| [Automation MCP](https://github.com/ashwwwin/automation-mcp) | 30 | macOS automation (mouse, keyboard, screenshots) |
| [MCP Computer Use](https://github.com/mediar-ai/MCP-server-client-computer-use-ai-sdk) | 50 | Screenpipe-based computer control |
| [VNC MCP](https://github.com/volkan-m/vnc-mcp-server) | 1 | VNC integration for remote agent control |

---

## Sandbox and Containerization

Keep your AI agent from burning down the house. Run it in a sandbox.

| Project | Stars | Description |
|---------|-------|-------------|
| [E2B Desktop](https://github.com/e2b-dev/desktop) | 1k+ | Open-source secure virtual desktop |
| [Agent Sandbox](https://github.com/agent-infra/sandbox) | 500 | Browser + Shell + File + MCP in one container |
| [Cyberdesk](https://github.com/cyberdesk-hq/cyberdesk) | 200 | Kubernetes-native virtual desktop orchestration |
| [Code Sandbox MCP](https://github.com/Automata-Labs-team/code-sandbox-mcp) | 317 | Secure code sandbox in Docker |
| [EdgeBox](https://github.com/BIGPPWONG/EdgeBox) | 197 | Local desktop sandbox with MCP support |
| [Sandbox0](https://github.com/sandbox0-ai/sandbox0) | 10 | General-purpose sandbox with hot pool |

---

## Voice-Controlled Agents

Talk to your computer and it actually does things. Revolutionary.

| Project | Stars | Description |
|---------|-------|-------------|
| [Fazm](https://github.com/m13v/fazm) | 200 | Fully local macOS AI agent via voice |
| [Voqal](https://github.com/voqal/voqal) | 200 | Voice-native AI agent, speech-to-code |
| [Voice Mirror](https://github.com/contextmirror/voice-mirror-electron) | 100 | Voice-controlled AI overlay, Tauri + Rust |
| [Colossus](https://github.com/richardanaya/colossus) | 50 | Voice-controlled multi-agent dev system |
| [Tankwork](https://github.com/agenttankos/tankwork) | 30 | Computer vision + voice commands, macOS |
| [Desktop Agent Voice](https://github.com/ruslankoroy/desktop-agent) | 15 | CV + Whisper voice input |

---

## Agent Memory

Because your AI should remember that you hate dark mode (weirdo).

| Project | Stars | Description |
|---------|-------|-------------|
| [Mem0](https://github.com/mem0ai/mem0) | 50.9k | Universal memory layer for AI agents |
| [ReMe](https://github.com/agentscope-ai/ReMe) | 200 | Memory management kit, SOTA on benchmarks |
| [A-Mem](https://github.com/agiresearch/A-mem) | 300 | Agentic Memory with knowledge networks |
| [OpenMemory](https://github.com/CaviraOSS/OpenMemory) | 500 | Cognitive memory engine with 4 memory types |
| [MemMachine](https://github.com/MemMachine/MemMachine) | 100 | Long-term episodic + profile memory |
| [SimpleMem](https://github.com/aiming-lab/SimpleMem) | 100 | Semantic lossless compression, MCP server |
| [Memori](https://github.com/GibsonAI/memori) | 150 | Memory engine with multi-provider support |
| [MemLayer](https://github.com/divagr18/memlayer) | 50 | Plug-and-play, under 100ms search |
| [Agent Memory](https://github.com/rohitg00/agentmemory) | 20 | Auto-capture via hooks, knowledge graphs |

---

## Agent Orchestration

When one agent is not enough and you need a whole crew.

| Project | Stars | Description |
|---------|-------|-------------|
| [Ruflo](https://github.com/ruvnet/ruflo) | 24.5k | Enterprise AI orchestration, 60+ agents |
| [Claude Code by Agents](https://github.com/baryhuang/claude-code-by-agents) | 812 | Multi-agent Claude Code with at-mentions |
| [AnyTool](https://github.com/HKUDS/AnyTool) | 100 | Universal tool-use layer with recording |

---

## Agent Testing and Evaluation

Prove your agent actually works (or laugh at how badly it fails).

| Project | Stars | Description |
|---------|-------|-------------|
| [ScreenSuite](https://github.com/huggingface/screensuite) | 200 | 13 benchmarks for GUI agents |
| [OSUniverse](https://github.com/agentsea/osuniverse) | 100 | 160 complex multimodal desktop tasks |
| [ScaleCUA](https://github.com/OpenGVLab/ScaleCUA) | 100 | Cross-platform dataset + training framework |
| [Agent VCR](https://github.com/ixchio/agent-vcr) | 19 | Time-travel debugging for AI agents |

---

## Game-Playing Agents

AI that plays games while you pretend to work.

| Project | Stars | Description |
|---------|-------|-------------|
| [AI-Player](https://github.com/shasankp000/AI-Player) | 104 | Minecraft mod with LLM-powered AI player |
| [Claude Minecraft Use](https://github.com/ObservedObserver/claude-minecraft-use) | Small | Claude playing Minecraft |
| [Bedrock Minecraft Agent](https://github.com/build-on-aws/amazon-bedrock-minecraft-agent) | 58 | Minecraft bot with Amazon Bedrock |
| [OSRS PVP RL](https://github.com/Naton1/osrs-pvp-reinforcement-learning) | 159 | Deep RL for Old School RuneScape PvP |
| [OSRS-CV](https://github.com/KaustubhLall/OSRS-CV) | 20 | Computer vision for OSRS automation |
| [Minecraft-RL](https://github.com/otsolappalainen/Minecraft-RL) | 2 | Deep RL training AI to play Minecraft |

---

## Training Data Tools

Collect data so your AI agent can learn from humans who actually know how to use a computer.

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenCUA](https://github.com/xlang-ai/OpenCUA) | 500 | 22.6K trajectories, annotation tools |
| [TongUI Data](https://github.com/TongUI-agent/TongUI-agent) | 77 | GUI-Net-1M dataset from web tutorials |
| [Captr](https://github.com/anaishowland/Captr_Windows) | 8 | Screen recording + interaction capture |
| [Interaction Logger](https://github.com/hemangjoshi37a/AIComputerInteractionLogger) | 11 | Capture screenshots, mouse, keyboard |
| [GUI Dataset Creator](https://github.com/harpreetsahota204/gui_dataset_creator) | 20 | Annotate GUI interactions in COCO format |
| [Data Collection](https://github.com/bobcoi03/computeruse-data-collection) | 10 | Privacy-first interaction data collection |

---

## Screen Understanding

Parse the chaos of a desktop into structured data your AI can reason about.

| Project | Stars | Description |
|---------|-------|-------------|
| [Screen2AX](https://github.com/MacPaw/Screen2AX) | 100 | Vision to macOS accessibility tree, 77 percent F1 |
| [AX Tree Parsers](https://github.com/viralmind-ai/accessibility-tree-parsers) | 50 | Cross-platform AX tree extraction scripts |
| [OmniParser](https://github.com/microsoft/OmniParser) | 5k | Screen parsing for vision-based GUI agents |

---

## Browser Extension Agents

Your browser, but smarter. And it does things for you.

| Project | Stars | Description |
|---------|-------|-------------|
| [Nanobrowser](https://github.com/nanobrowser/nanobrowser) | 12.5k | Open-source alternative to OpenAI Operator |
| [Fuji-Web](https://github.com/normal-computing/fuji-web) | 500 | Autonomous web with explanations |
| [ChromeClaw](https://github.com/algopian/chromeclaw) | 100 | OpenClaw-inspired Chrome extension |
| [Browser Agent Extension](https://github.com/KazKozDev/browser-agent-chrome-extension) | 30 | Manifest V3 with tool calling |
| [Browser Control](https://github.com/dhamaniasad/browser-control) | 8 | Gemini multimodal browser automation |
| [Izan.io](https://github.com/ekingunoncu/izan.io) | 20 | 17+ providers, no-code action recorder |
| [LLM in Chrome](https://github.com/hanzili/llm-in-chrome) | 50 | Give your AI agent your real browser via MCP |
| [Dev Browser](https://github.com/SawyerHood/dev-browser) | 50 | Claude Code browser automation plugin |

---

## Desktop-Native AI Assistants

Your always-on AI buddy that lives in your system tray.

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenClaw](https://github.com/openclaw/openclaw) | 5k+ | Multi-channel AI assistant with skills |

---

## IDE-Based Agents

Coding agents that learned to use a mouse.

| Project | Stars | Description |
|---------|-------|-------------|
| [Elves](https://github.com/mvmcode/elves) | 50 | Tauri app orchestrating Claude Code and Codex |
| [Pilos Agents](https://github.com/pilos-ai/agents) | 30 | Visual desktop for Claude Code, multi-agent |
| [Mastra Code UI](https://github.com/mastra-ai/mastra-code-ui) | 100 | Desktop coding agent with multi-model |

---

## Research Papers

The science behind the magic.

| Paper | Venue | Focus |
|-------|-------|-------|
| [Agent S](https://arxiv.org/abs/2410.08164) | - | Open agentic framework for CUA |
| [UI-TARS](https://arxiv.org/abs/2501.12326) | - | Native GUI interaction |
| [OSWorld](https://arxiv.org/abs/2404.07972) | NeurIPS 2024 | Real computer benchmark |
| [OS Agents Survey](https://openreview.net/forum?id=ed2f5ee6b84c3b118cb953b6e750486dbd700419) | - | Comprehensive CUA survey |
| [Computer Use Agents Survey](https://arxiv.org/abs/2501.16150) | - | Instruction-based computer control |
| [Cradle](https://arxiv.org/abs/2403.03186) | - | General computer control |
| [Aguvis](https://arxiv.org/abs/2412.04454) | - | Unified pure vision agents |
| [OS-Atlas](https://arxiv.org/abs/2410.23218) | ICLR 2025 | Foundation action model |
| [SeeClick](https://arxiv.org/abs/2401.10935) | ACL 2024 | GUI grounding |
| [OmniParser](https://arxiv.org/abs/2408.00203) | - | Screen parsing for agents |

---

## Related Awesome Lists

These folks are doing great work too. Go star them.

| List | Focus |
|------|-------|
| [ranpox/awesome-computer-use](https://github.com/ranpox/awesome-computer-use) | The OG CUA list (papers + projects) |
| [Awesome-GUI-Agent](https://github.com/showlab/Awesome-GUI-Agent) | GUI agent papers and projects |
| [GUI-Agents-Paper-List](https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List) | Comprehensive paper list |
| [Awesome-GUI-Agents](https://github.com/ZJU-REAL/Awesome-GUI-Agents) | GUI agents with project links |
| [ACU](https://github.com/trycua/acu) | Awesome Agents for Computer Use |
| [steel-dev/awesome-web-agents](https://github.com/steel-dev/awesome-web-agents) | Web agents |
| [awesome-local-llm](https://github.com/rafska/awesome-local-llm) | Local LLM ecosystem |

---

## The Leaderboard

Who is actually winning at computer use?

| Agent | Benchmark | Score | Open Source |
|-------|-----------|-------|-------------|
| Agent S3 | OSWorld | 72.6% | Yes |
| Anthropic CUA | OSWorld | ~68% | No |
| OpenAI Operator | OSWorld | ~65% | No |
| Browser-Use | WebVoyager | 89.1% | Yes |
| Skyvern | WebVoyager | 85.8% | Yes |
| Agent-E | WebVoyager | 73.1% | Yes |

---

## Contributing

Found something missing? Open an issue or submit a PR!

**Rules:**
1. Must be open source (or have a meaningful open-source component)
2. Must relate to computer use / desktop automation / GUI agents
3. Must be actively maintained (commit within last 6 months)
4. Add it to the correct category with stars and description

---

## License

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
