# Awesome Computer Use [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Open-source projects that let AI click, type, scroll, and generally make a mess of your desktop — so you don't have to.

Your AI can write poetry, debug code, and explain quantum physics. But ask it to open Spotify and it stares at you blankly. **Not anymore.**

Computer-use agents (CUAs) are AI systems that see your screen, understand what's on it, and interact with it — just like a human would, minus the coffee breaks and existential dread.

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
- [The Leaderboard](#the-leaderboard)
- [Related Awesome Lists](#related-awesome-lists)

## Desktop Agents

The full package. These see your screen, click things, type things, and occasionally crash things.

- [OpenInterpreter](https://github.com/OpenInterpreter/open-interpreter) - Run code locally via natural language. The OG. `55k+ ⭐`.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Software dev agents that browse, code, and run commands. `40k+ ⭐`.
- [Self-Operating Computer](https://github.com/OthersideAI/self-operating-computer) - Framework for multimodal models to operate a computer. `10.2k ⭐`.
- [Bytebot](https://github.com/bytebot-ai/bytebot) - Self-hosted AI desktop agent in Docker. `10.5k ⭐`.
- [Agent S](https://github.com/simular-ai/agent-s) - SOTA on OSWorld 72.6%, beats OpenAI CUA. `3k+ ⭐`.
- [Open Computer Use (E2B)](https://github.com/e2b-dev/open-computer-use) - Cloud sandbox plus open-source LLMs. `3k+ ⭐`.
- [GenericAgent](https://github.com/lsdefine/GenericAgent) - Minimal 3,300 LOC self-evolving agent. `740 ⭐`.
- [Accomplish](https://github.com/accomplish-ai/accomplish) - Open-source AI desktop agent, local-first. `500 ⭐`.
- [Fara-7B](https://github.com/microsoft/fara) - Microsoft's efficient small model for CUA. `500 ⭐`.
- [Magentic-UI](https://github.com/microsoft/magentic-ui) - Human-centered web agent with approval workflows. `500 ⭐`.
- [Cuse](https://github.com/cuse-dev/cuse) - Open framework for building CUA agents. `400 ⭐`.
- [Clevrr Computer](https://github.com/Clevrr-AI/Clevrr-Computer) - Open-source Anthropic CUA with PyAutoGUI. `309 ⭐`.
- [Cuse Agent](https://github.com/e2b-dev/cuse-agent) - CUA with E2B virtual desktop sandbox. `300 ⭐`.
- [AskUI Vision Agent](https://github.com/askui/vision-agent) - Automate desktop, mobile, and HMI devices. `200 ⭐`.
- [Agent Desktop](https://github.com/lahfir/agent-desktop) - Native Rust CLI, AX-first, no screenshots. `100 ⭐`.
- [TongUI Agent](https://github.com/TongUI-agent/TongUI-agent) - VLA model learning from web tutorials. `77 ⭐`.
- [IrisGUI](https://github.com/black-yt/IrisGUI) - Lightweight with Dynamic Focus Vision. `50 ⭐`.
- [Oboto](https://github.com/sschepis/oboto) - Everything assistant with persistent cognitive architecture. `24 ⭐`.
- [Computer-Use-Agent](https://github.com/nabhpatodi10/Computer-Use-Agent) - Windows CUA with LangGraph plus OmniParser. `20 ⭐`.
- [Gofer](https://github.com/jleuth/gofer) - AI agent controllable via Telegram. `20 ⭐`.
- [VNC-Use](https://github.com/mayflower/vnc-use) - LangGraph agent via VNC, multi-model. `30 ⭐`.
- [Ghost OS](https://github.com/ghostwright/ghost-os) - macOS AX tree plus local VLM, self-learning recipes.
- [TuriX](https://github.com/TurixAI/TuriX-CUA) - Desktop automation, OpenClaw integration.
- [Atlas](https://github.com/dortanes/atlas) - Electron overlay, Gemini native CUA.
- [Open Computer Use](https://github.com/coasty-ai/open-computer-use) - Full-stack platform, multi-provider.
- [Cua](https://github.com/trycua/cua) - Containers for computer-use agents.
- [Cybergod](https://github.com/james4ever0/agi_computer_control) - AGI computer control framework.

## Browser Agents

For when your AI only needs to wreck things on the web.

- [Browser-Use](https://github.com/browser-use/browser-use) - SOTA browser automation, makes websites LLM-friendly. `84k ⭐`.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Vision-driven web automation, no coded selectors. `10k+ ⭐`.
- [Nanobrowser](https://github.com/nanobrowser/nanobrowser) - Chrome extension, multi-agent Planner and Navigator. `12.5k ⭐`.
- [Fuji-Web](https://github.com/normal-computing/fuji-web) - Chrome extension with step-by-step explanations. `500 ⭐`.
- [Notte](https://github.com/nott-ai/notte) - Reliable browser AI framework.
- [LaVague](https://github.com/lavague-ai/LaVague) - Natural language web automation.
- [UI-Act](https://github.com/TobiasNorlund/UI-Act) - Grounded UI interaction.
- [WebMarker](https://github.com/reidbarber/webmarker) - Web annotation for agents.

## Mobile Agents

AI that taps, swipes, and scrolls on your phone so you can doom-scroll guilt-free.

- [Open-AutoGLM](https://github.com/THUDM/AutoGLM) - Phone agent with vision-language model for Android. `23.6k ⭐`.
- [AppAgent](https://github.com/TencentQQGYLab/AppAgent) - LLM-based multimodal agent for smartphone apps. `6.6k ⭐`.
- [Mobile-Use](https://github.com/madeagents/mobile-use) - Any app, any task. NeurIPS 2025. `200 ⭐`.
- [Mobile-Use](https://github.com/minitap-ai/mobile-use) - Automate Android and iOS with natural language. `100 ⭐`.
- [CoCo-Agent](https://github.com/xbmxb/CoCo-Agent) - Smartphone GUI automation, ACL 2024. `100 ⭐`.

## Vision and Grounding Models

The eyes of computer-use. These models see and understand what is on screen.

- [OmniParser](https://github.com/microsoft/OmniParser) - Screen parsing for pure vision-based GUI agents. `5k ⭐`.
- [CogAgent](https://github.com/THUDM/CogAgent) - Open-sourced VLM-based GUI Agent, CVPR 2024. `2.5k ⭐`.
- [ShowUI](https://github.com/showlab/ShowUI) - Lightweight VLM for GUI agent and CUA. `1.5k ⭐`.
- [UI-Venus](https://github.com/inclusionAI/UI-Venus) - Native UI agent, SOTA on ScreenSpot-Pro. `1.2k ⭐`.
- [UGround](https://github.com/OSU-NLP-Group/UGround) - Universal Visual Grounding, ICLR 2025 Oral. `600 ⭐`.
- [OS-Atlas](https://github.com/os-copilot/os-atlas) - Foundation Action Model for Generalist GUI Agents. `442 ⭐`.
- [ScreenSpot-Pro](https://github.com/likaixin2000/screenspot-pro-gui-grounding) - GUI Grounding benchmark for high-res. `200 ⭐`.
- [Screen-Point-and-Read](https://github.com/eric-ai-lab/Screen-Point-and-Read) - Layout-aware GUI screen reading. `100 ⭐`.
- [ShowUI-Aloha](https://github.com/showlab/ShowUI-Aloha) - Human-taught computer-use agent. `100 ⭐`.
- [GUI-G1](https://github.com/Yuqi-Zhou/GUI-G1) - R1-Zero-like training for GUI grounding. `100 ⭐`.
- [GUI-Libra](https://github.com/GUI-Libra/GUI-Libra) - Post-training framework for GUI agents. `50 ⭐`.
- [SeeClick](https://github.com/nicehuster/AITQE) - Harnessing GUI grounding for visual agents.

## Screen Capture and Recording

Taking screenshots for AI so it knows what is going on.

- [Screenpipe](https://github.com/screenpipe/screenpipe) - Continuous screen and audio recording, searchable AI memory. `17.5k ⭐`.
- [Peekaboo](https://github.com/steipete/Peekaboo) - macOS screen capture plus AI analysis plus MCP server. `2.9k ⭐`.
- [macOS Visual Agent](https://github.com/peakmojo/macos-visual-agent) - On-device screen understanding via Apple AX APIs. `50 ⭐`.
- [CaptiOCR](https://github.com/carlosacchi/captiocr) - Real-time OCR for video conferencing. `6 ⭐`.

## OCR and Screen Reading

Turning pixels into text your AI can actually read.

- [NormCap](https://github.com/dynobo/normcap) - OCR-powered screen-capture, capture text not images. `3.5k ⭐`.
- [OpenOCR](https://github.com/Topdu/OpenOCR) - General OCR toolkit from Fudan University. `1.2k ⭐`.
- [AgentOCR](https://github.com/AgentMaker/AgentOCR) - Multi-language OCR with PaddleOCR plus ONNX. `300 ⭐`.
- [LOCR](https://github.com/dmzlingyin/LOCR) - Lightweight auto-extract OCR, cross-platform Go. `100 ⭐`.
- [Prism AI](https://github.com/chrismannina/prism-ai-screen-reader) - AI screen reader with OCR, privacy-first. `10 ⭐`.

## Desktop Automation Libraries

The plumbing behind the magic. Low-level tools that do the actual clicking.

- [RobotJS](https://github.com/octalmage/robotjs) - Node.js Desktop Automation. `12k+ ⭐`.
- [PyAutoGUI](https://github.com/asweigart/pyautogui) - Cross-platform GUI automation for Python. `10k+ ⭐`.
- [nut.js](https://github.com/nut-tree/nut.js) - Native UI automation for Node.js. `2.8k ⭐`.
- [guibot](https://github.com/intra2net/guibot) - GUI automation with computer vision. `200 ⭐`.
- [libnut-core](https://github.com/nut-tree/libnut-core) - Node-API addon for desktop automation. `50 ⭐`.
- [qontinui](https://github.com/jspinak/qontinui) - Model-based GUI automation with state management. `30 ⭐`.

## RPA Tools

Robotic Process Automation, but make it AI.

- [TagUI-Python](https://github.com/tebelorg/RPA-Python) - Leading open-source Python RPA tool. `5k+ ⭐`.
- [rpaframework](https://github.com/robocorp/rpaframework) - Open-source RPA libraries for Robot Framework. `1k+ ⭐`.
- [astron-rpa](https://github.com/iflytek/astron-rpa) - Enterprise-grade RPA with LLM integration. `50 ⭐`.
- [AIVANE](https://github.com/taiyouqu/aivane) - AI plus RPA cross-platform control. `20 ⭐`.

## MCP Servers for Desktop

Model Context Protocol servers that give your AI desktop superpowers.

- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Terminal control, file system, diff editing. `2k+ ⭐`.
- [Computer Control MCP](https://github.com/AB498/computer-control-mcp) - Mouse, keyboard, OCR via PyAutoGUI. `124 ⭐`.
- [QuickDesk](https://github.com/barry-ran/QuickDesk) - AI-native remote desktop with MCP. `115 ⭐`.
- [ScreenMonitor MCP](https://github.com/inkbytefo/ScreenMonitorMCP) - Real-time screen capture and vision. `71 ⭐`.
- [System MCP](https://github.com/aurafriday/system_mcp) - Full desktop automation, multi-platform. `50 ⭐`.
- [MCP Computer Use](https://github.com/mediar-ai/MCP-server-client-computer-use-ai-sdk) - Screenpipe-based computer control. `50 ⭐`.
- [Desktop Automation MCP](https://github.com/tanob/mcp-desktop-automation) - RobotJS-based desktop automation. `50 ⭐`.
- [Automation MCP](https://github.com/ashwwwin/automation-mcp) - macOS automation, mouse, keyboard, screenshots. `30 ⭐`.
- [Windows Desktop Automation MCP](https://github.com/mario-andreschak/mcp-windows-desktop-automation) - Windows desktop automation via AutoIt. `20 ⭐`.
- [VNC MCP](https://github.com/volkan-m/vnc-mcp-server) - VNC integration for remote agent control. `1 ⭐`.

## Sandbox and Containerization

Keep your AI agent from burning down the house. Run it in a sandbox.

- [E2B Desktop](https://github.com/e2b-dev/desktop) - Open-source secure virtual desktop. `1k+ ⭐`.
- [Agent Sandbox](https://github.com/agent-infra/sandbox) - Browser plus Shell plus File plus MCP in one container. `500 ⭐`.
- [Code Sandbox MCP](https://github.com/Automata-Labs-team/code-sandbox-mcp) - Secure code sandbox in Docker. `317 ⭐`.
- [Cyberdesk](https://github.com/cyberdesk-hq/cyberdesk) - Kubernetes-native virtual desktop orchestration. `200 ⭐`.
- [EdgeBox](https://github.com/BIGPPWONG/EdgeBox) - Local desktop sandbox with MCP support. `197 ⭐`.
- [Sandbox0](https://github.com/sandbox0-ai/sandbox0) - General-purpose sandbox with hot pool. `10 ⭐`.

## Voice-Controlled Agents

Talk to your computer and it actually does things. Revolutionary.

- [Fazm](https://github.com/m13v/fazm) - Fully local macOS AI agent via voice. `200 ⭐`.
- [Voqal](https://github.com/voqal/voqal) - Voice-native AI agent, speech-to-code. `200 ⭐`.
- [Voice Mirror](https://github.com/contextmirror/voice-mirror-electron) - Voice-controlled AI overlay, Tauri plus Rust. `100 ⭐`.
- [Colossus](https://github.com/richardanaya/colossus) - Voice-controlled multi-agent dev system. `50 ⭐`.
- [Tankwork](https://github.com/agenttankos/tankwork) - Computer vision plus voice commands, macOS. `30 ⭐`.
- [Desktop Agent Voice](https://github.com/ruslankoroy/desktop-agent) - CV plus Whisper voice input. `15 ⭐`.

## Agent Memory

Because your AI should remember that you hate dark mode (weirdo).

- [Mem0](https://github.com/mem0ai/mem0) - Universal memory layer for AI agents. `50.9k ⭐`.
- [OpenMemory](https://github.com/CaviraOSS/OpenMemory) - Cognitive memory engine with 4 memory types. `500 ⭐`.
- [A-Mem](https://github.com/agiresearch/A-mem) - Agentic Memory with knowledge networks. `300 ⭐`.
- [ReMe](https://github.com/agentscope-ai/ReMe) - Memory management kit, SOTA on benchmarks. `200 ⭐`.
- [Memori](https://github.com/GibsonAI/memori) - Memory engine with multi-provider support. `150 ⭐`.
- [MemMachine](https://github.com/MemMachine/MemMachine) - Long-term episodic plus profile memory. `100 ⭐`.
- [SimpleMem](https://github.com/aiming-lab/SimpleMem) - Semantic lossless compression, MCP server. `100 ⭐`.
- [MemLayer](https://github.com/divagr18/memlayer) - Plug-and-play, under 100ms search. `50 ⭐`.
- [Agent Memory](https://github.com/rohitg00/agentmemory) - Auto-capture via hooks, knowledge graphs. `20 ⭐`.

## Agent Orchestration

When one agent is not enough and you need a whole crew.

- [Ruflo](https://github.com/ruvnet/ruflo) - Enterprise AI orchestration, 60 plus agents. `24.5k ⭐`.
- [Claude Code by Agents](https://github.com/baryhuang/claude-code-by-agents) - Multi-agent Claude Code with at-mentions. `812 ⭐`.
- [AnyTool](https://github.com/HKUDS/AnyTool) - Universal tool-use layer with recording. `100 ⭐`.

## Agent Testing and Evaluation

Prove your agent actually works (or laugh at how badly it fails).

- [ScreenSuite](https://github.com/huggingface/screensuite) - 13 benchmarks for GUI agents. `200 ⭐`.
- [OSUniverse](https://github.com/agentsea/osuniverse) - 160 complex multimodal desktop tasks. `100 ⭐`.
- [ScaleCUA](https://github.com/OpenGVLab/ScaleCUA) - Cross-platform dataset plus training framework. `100 ⭐`.
- [Agent VCR](https://github.com/ixchio/agent-vcr) - Time-travel debugging for AI agents. `19 ⭐`.

## Game-Playing Agents

AI that plays games while you pretend to work.

- [AI-Player](https://github.com/shasankp000/AI-Player) - Minecraft mod with LLM-powered AI player. `104 ⭐`.
- [OSRS PVP RL](https://github.com/Naton1/osrs-pvp-reinforcement-learning) - Deep RL for Old School RuneScape PvP. `159 ⭐`.
- [Bedrock Minecraft Agent](https://github.com/build-on-aws/amazon-bedrock-minecraft-agent) - Minecraft bot with Amazon Bedrock. `58 ⭐`.
- [OSRS-CV](https://github.com/KaustubhLall/OSRS-CV) - Computer vision for OSRS automation. `20 ⭐`.
- [Claude Minecraft Use](https://github.com/ObservedObserver/claude-minecraft-use) - Claude playing Minecraft.
- [Minecraft-RL](https://github.com/otsolappalainen/Minecraft-RL) - Deep RL training AI to play Minecraft. `2 ⭐`.

## Training Data Tools

Collect data so your AI agent can learn from humans who actually know how to use a computer.

- [OpenCUA](https://github.com/xlang-ai/OpenCUA) - 22.6K trajectories, annotation tools. `500 ⭐`.
- [GUI Dataset Creator](https://github.com/harpreetsahota204/gui_dataset_creator) - Annotate GUI interactions in COCO format. `20 ⭐`.
- [Interaction Logger](https://github.com/hemangjoshi37a/AIComputerInteractionLogger) - Capture screenshots, mouse, keyboard. `11 ⭐`.
- [Data Collection](https://github.com/bobcoi03/computeruse-data-collection) - Privacy-first interaction data collection. `10 ⭐`.
- [Captr](https://github.com/anaishowland/Captr_Windows) - Screen recording plus interaction capture. `8 ⭐`.

## Screen Understanding

Parse the chaos of a desktop into structured data your AI can reason about.

- [Screen2AX](https://github.com/MacPaw/Screen2AX) - Vision to macOS accessibility tree, 77 percent F1. `100 ⭐`.
- [AX Tree Parsers](https://github.com/viralmind-ai/accessibility-tree-parsers) - Cross-platform AX tree extraction scripts. `50 ⭐`.

## Browser Extension Agents

Your browser, but smarter. And it does things for you.

- [ChromeClaw](https://github.com/algopian/chromeclaw) - OpenClaw-inspired Chrome extension. `100 ⭐`.
- [LLM in Chrome](https://github.com/hanzili/llm-in-chrome) - Give your AI agent your real browser via MCP. `50 ⭐`.
- [Dev Browser](https://github.com/SawyerHood/dev-browser) - Claude Code browser automation plugin. `50 ⭐`.
- [Browser Agent Extension](https://github.com/KazKozDev/browser-agent-chrome-extension) - Manifest V3 with tool calling. `30 ⭐`.
- [Izan.io](https://github.com/ekingunoncu/izan.io) - 17 plus providers, no-code action recorder. `20 ⭐`.
- [Browser Control](https://github.com/dhamaniasad/browser-control) - Gemini multimodal browser automation. `8 ⭐`.

## Desktop-Native AI Assistants

Your always-on AI buddy that lives in your system tray.

- [OpenClaw](https://github.com/openclaw/openclaw) - Multi-channel AI assistant with skills. `5k+ ⭐`.

## IDE-Based Agents

Coding agents that learned to use a mouse.

- [Mastra Code UI](https://github.com/mastra-ai/mastra-code-ui) - Desktop coding agent with multi-model. `100 ⭐`.
- [Elves](https://github.com/mvmcode/elves) - Tauri app orchestrating Claude Code and Codex. `50 ⭐`.
- [Pilos Agents](https://github.com/pilos-ai/agents) - Visual desktop for Claude Code, multi-agent. `30 ⭐`.

## Research Papers

The science behind the magic.

- [Agent S](https://arxiv.org/abs/2410.08164) - Open agentic framework that uses computers like a human.
- [UI-TARS](https://arxiv.org/abs/2501.12326) - Pioneering automated GUI interaction with native agents.
- [OSWorld](https://arxiv.org/abs/2404.07972) - Benchmarking multimodal agents for open-ended tasks in real computer environments. `NeurIPS 2024`.
- [OS Agents Survey](https://openreview.net/forum?id=ed2f5ee6b84c3b118cb953b6e750486dbd700419) - Survey on MLLM-based agents for general computing devices use.
- [Computer Use Agents Survey](https://arxiv.org/abs/2501.16150) - A review of instruction-based computer control, GUI automation, and operator assistants.
- [Cradle](https://arxiv.org/abs/2403.03186) - Empowering foundation agents towards general computer control.
- [Aguvis](https://arxiv.org/abs/2412.04454) - Unified pure vision agents for autonomous GUI interaction.
- [OS-Atlas](https://arxiv.org/abs/2410.23218) - Foundation action model for generalist GUI agents. `ICLR 2025`.
- [SeeClick](https://arxiv.org/abs/2401.10935) - Harnessing GUI grounding for advanced visual GUI agents. `ACL 2024`.
- [OmniParser](https://arxiv.org/abs/2408.00203) - Screen parsing tool for pure vision based GUI agent.

## The Leaderboard

Who is actually winning at computer use?

- Agent S3 - OSWorld: 72.6% (Open Source)
- Anthropic CUA - OSWorld: ~68% (Closed Source)
- OpenAI Operator - OSWorld: ~65% (Closed Source)
- Browser-Use - WebVoyager: 89.1% (Open Source)
- Skyvern - WebVoyager: 85.8% (Open Source)
- Agent-E - WebVoyager: 73.1% (Open Source)

## Related Awesome Lists

These folks are doing great work too. Go star them.

- [ranpox/awesome-computer-use](https://github.com/ranpox/awesome-computer-use) - The OG CUA list with papers and projects.
- [Awesome-GUI-Agent](https://github.com/showlab/Awesome-GUI-Agent) - GUI agent papers and projects.
- [GUI-Agents-Paper-List](https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List) - Comprehensive paper list.
- [Awesome-GUI-Agents](https://github.com/ZJU-REAL/Awesome-GUI-Agents) - GUI agents with project links.
- [ACU](https://github.com/trycua/acu) - Awesome Agents for Computer Use.
- [steel-dev/awesome-web-agents](https://github.com/steel-dev/awesome-web-agents) - Web agents.
- [awesome-local-llm](https://github.com/rafska/awesome-local-llm) - Local LLM ecosystem.
