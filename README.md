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

- [Clickyy](https://github.com/jayamitkatariya/clickyyy) - Shake your cursor to summon an AI agent that sees your screen and clicks, types, drags, and acts for you on macOS. Open-source, MIT.

The full package. These see your screen, click things, type things, and occasionally crash things.

- [OpenInterpreter](https://github.com/openinterpreter/openinterpreter) - Coding agent for open models like Kimi K3. The OG. `68.0k ⭐`.
- [OpenHands](https://github.com/OpenHands/OpenHands) - Software dev agents that browse, code, and run commands. `83.7k ⭐`.
- [Self-Operating Computer](https://github.com/OthersideAI/self-operating-computer) - Framework for multimodal models to operate a computer. `10.3k ⭐`.
- [Bytebot](https://github.com/bytebot-ai/bytebot) - Self-hosted AI desktop agent in Docker. `11.1k ⭐`.
- [Agent S](https://github.com/simular-ai/agent-s) - SOTA on OSWorld 72.6%, beats OpenAI CUA. `12.1k ⭐`.
- [Open Computer Use (E2B)](https://github.com/e2b-dev/open-computer-use) - Cloud sandbox plus open-source LLMs. `2.2k ⭐`.
- [GenericAgent](https://github.com/lsdefine/GenericAgent) - Minimal 3,300 LOC self-evolving agent. `13.7k ⭐`.
- [Coworker](https://github.com/accomplish-ai/coworker) - Open-source AI desktop coworker that lives on your desktop (formerly Accomplish). `10.9k ⭐`.
- [Fara](https://github.com/microsoft/fara) - Microsoft's family of frontier computer-use agent models (Fara 1.5). `6.1k ⭐`.
- [Magentic-UI](https://github.com/microsoft/magentic-ui) - Human-centered web agent with approval workflows. `10.1k ⭐`.
- [Cuse](https://github.com/cuse-dev/cuse) - Open framework for building CUA agents. `87 ⭐`.
- [Clevrr Computer](https://github.com/Clevrr-AI/Clevrr-Computer) - Open-source Anthropic CUA with PyAutoGUI. `318 ⭐`.
- [Surf](https://github.com/e2b-dev/surf) - OpenAI-powered CUA on E2B's virtual desktop (formerly Cuse Agent). `843 ⭐`.
- [AskUI Vision Agent](https://github.com/askui/python-sdk) - Automate desktop, mobile, and HMI devices. `551 ⭐`.
- [Agent Desktop](https://github.com/lahfir/agent-desktop) - Native Rust CLI, AX-first, no screenshots. `1.0k ⭐`.
- [TongUI Agent](https://github.com/TongUI-agent/TongUI-agent) - VLA model learning from web tutorials. `114 ⭐`.
- [IrisGUI](https://github.com/black-yt/IrisGUI) - Lightweight with Dynamic Focus Vision. `6 ⭐`.
- [Oboto](https://github.com/sschepis/oboto) - Everything assistant with persistent cognitive architecture. `27 ⭐`.
- [Computer-Use-Agent](https://github.com/nabhpatodi10/Computer-Use-Agent) - Windows CUA with OmniParser, GUI Actor, and OpenAI models. `0 ⭐`.
- [Gofer](https://github.com/jleuth/gofer) - AI agent that lives on your computer, controllable via Telegram. `3 ⭐`.
- [VNC-Use](https://github.com/mayflower/vnc-use) - LangGraph agent via VNC, Gemini-powered. `8 ⭐`.
- [Ghost OS](https://github.com/ghostwright/ghost-os) - macOS AX tree plus local VLM, self-learning recipes. `1.6k ⭐`.
- [TuriX](https://github.com/TurixAI/TuriX-CUA) - Desktop automation, OpenClaw integration. `3.2k ⭐`.
- [Atlas](https://github.com/dortanes/atlas) - Electron overlay, Gemini native CUA. `24 ⭐`.
- [Open Cowork](https://github.com/coasty-ai/open-cowork) - Coasty's full-stack computer-use coworker, multi-provider BYO LLM. `130 ⭐`.
- [Cua](https://github.com/trycua/cua) - Containers for computer-use agents. `21.2k ⭐`.
- [Cybergod](https://github.com/james4ever0/agi_computer_control) - AGI computer control framework. `157 ⭐`.

## Browser Agents

For when your AI only needs to wreck things on the web.

- [Browser-Use](https://github.com/browser-use/browser-use) - SOTA browser automation, makes websites LLM-friendly. `108.8k ⭐`.
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - Vision-driven web automation, no coded selectors. `22.7k ⭐`.
- [Nanobrowser](https://github.com/nanobrowser/nanobrowser) - Chrome extension, multi-agent Planner and Navigator. `13.5k ⭐`.
- [Fuji-Web](https://github.com/normal-computing/fuji-web) - Chrome extension with step-by-step explanations. `597 ⭐`.
- [Notte](https://github.com/nottelabs/notte) - Cloud browser infrastructure and web automation platform for AI agents. `2.0k ⭐`.
- [LaVague](https://github.com/lavague-ai/LaVague) - Natural language web automation. `6.4k ⭐`.
- [UI-Act](https://github.com/TobiasNorlund/UI-Act) - Grounded UI interaction. `88 ⭐`.
- [WebMarker](https://github.com/reidbarber/webmarker) - Web annotation for agents. `61 ⭐`.

## Mobile Agents

AI that taps, swipes, and scrolls on your phone so you can doom-scroll guilt-free.

- [Open-AutoGLM](https://github.com/zai-org/Open-AutoGLM) - Open phone agent model and framework for Android. `26.0k ⭐`.
- [AppAgent](https://github.com/TencentQQGYLab/AppAgent) - LLM-based multimodal agent for smartphone apps. `6.8k ⭐`.
- [Mobile-Use](https://github.com/madeagents/mobile-use) - Any app, any task. NeurIPS 2025. `179 ⭐`.
- [Mobile-Use](https://github.com/minitap-ai/mobile-use) - Automate Android and iOS with natural language. `2.8k ⭐`.
- [CoCo-Agent](https://github.com/xbmxb/CoCo-Agent) - Smartphone GUI automation, ACL 2024. `35 ⭐`.

## Vision and Grounding Models

The eyes of computer-use. These models see and understand what is on screen.

- [OmniParser](https://github.com/microsoft/OmniParser) - Screen parsing for pure vision-based GUI agents. `25.2k ⭐`.
- [CogAgent](https://github.com/zai-org/CogAgent) - Open-sourced VLM-based GUI Agent, CVPR 2024. `1.2k ⭐`.
- [ShowUI](https://github.com/showlab/ShowUI) - Lightweight VLM for GUI agent and CUA. `1.9k ⭐`.
- [UI-Venus](https://github.com/inclusionAI/UI-Venus) - Native UI agent, SOTA on ScreenSpot-Pro. `1.0k ⭐`.
- [UGround](https://github.com/OSU-NLP-Group/UGround) - Universal Visual Grounding, ICLR 2025 Oral. `316 ⭐`.
- [OS-Atlas](https://github.com/os-copilot/os-atlas) - Foundation Action Model for Generalist GUI Agents. `453 ⭐`.
- [ScreenSpot-Pro](https://github.com/likaixin2000/screenspot-pro-gui-grounding) - GUI Grounding benchmark for high-res. `387 ⭐`.
- [Screen-Point-and-Read](https://github.com/UCSB-AI/Screen-Point-and-Read) - Layout-aware GUI screen reading. `31 ⭐`.
- [ShowUI-Aloha](https://github.com/showlab/ShowUI-Aloha) - Human-taught computer-use agent. `318 ⭐`.
- [GUI-G1](https://github.com/Yuqi-Zhou/GUI-G1) - R1-Zero-like training for GUI grounding. `28 ⭐`.
- [GUI-Libra](https://github.com/GUI-Libra/GUI-Libra) - Post-training framework for GUI agents. `68 ⭐`.
- [SeeClick](https://github.com/njucckevin/SeeClick) - Harnessing GUI grounding for visual agents. `495 ⭐`.

## Screen Capture and Recording

Taking screenshots for AI so it knows what is going on.

- [Screenpipe](https://github.com/screenpipe/screenpipe) - Continuous screen and audio recording, searchable AI memory. `20.9k ⭐`.
- [Peekaboo](https://github.com/openclaw/Peekaboo) - macOS screen capture plus AI analysis plus MCP server. `5.0k ⭐`.
- [macOS Visual Agent](https://github.com/peakmojo/macos-visual-agent) - On-device screen understanding via Apple AX APIs. `6 ⭐`.
- [CaptiOCR](https://github.com/carlosacchi/captiocr) - Real-time OCR for video conferencing. `19 ⭐`.

## OCR and Screen Reading

Turning pixels into text your AI can actually read.

- [NormCap](https://github.com/dynobo/normcap) - OCR-powered screen-capture, capture text not images. `2.7k ⭐`.
- [OpenOCR](https://github.com/Topdu/OpenOCR) - General OCR toolkit from Fudan University. `1.4k ⭐`.
- [AgentOCR](https://github.com/AgentMaker/AgentOCR) - Multi-language OCR with PaddleOCR plus ONNX. `125 ⭐`.
- [LOCR](https://github.com/dmzlingyin/LOCR) - Lightweight auto-extract OCR, cross-platform Go. `11 ⭐`.
- [Prism AI](https://github.com/chrismannina/prism-ai-screen-reader) - AI screen reader with OCR, privacy-first. `2 ⭐`.

## Desktop Automation Libraries

The plumbing behind the magic. Low-level tools that do the actual clicking.

- [RobotJS](https://github.com/octalmage/robotjs) - Node.js Desktop Automation. `12.8k ⭐`.
- [PyAutoGUI](https://github.com/asweigart/pyautogui) - Cross-platform GUI automation for Python. `12.7k ⭐`.
- [nut.js](https://github.com/nut-tree/nut.js) - Native UI automation for Node.js. `2.8k ⭐`.
- [guibot](https://github.com/intra2net/guibot) - GUI automation with computer vision. `187 ⭐`.
- [libnut-core](https://github.com/nut-tree/libnut-core) - Node-API addon for desktop automation. `55 ⭐`.
- [qontinui](https://github.com/qontinui/qontinui) - Model-based GUI automation with state management. `3 ⭐`.

## RPA Tools

Robotic Process Automation, but make it AI.

- [TagUI-Python](https://github.com/tebelorg/RPA-Python) - Leading open-source Python RPA tool. `5.5k ⭐`.
- [rpaframework](https://github.com/robocorp/rpaframework) - Open-source RPA libraries for Robot Framework. `1.5k ⭐`.
- [astron-rpa](https://github.com/iflytek/astron-rpa) - Enterprise-grade RPA with LLM integration. `5.8k ⭐`.
- [AIVANE](https://github.com/taiyouqu/aivane) - AI plus RPA cross-platform control. `1 ⭐`.

## MCP Servers for Desktop

Model Context Protocol servers that give your AI desktop superpowers.

- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Terminal control, file system, diff editing. `9.3k ⭐`.
- [Computer Control MCP](https://github.com/AB498/computer-control-mcp) - Mouse, keyboard, OCR via PyAutoGUI. `158 ⭐`.
- [QuickDesk](https://github.com/barry-ran/QuickDesk) - AI-native remote desktop with MCP. `345 ⭐`.
- [System MCP](https://github.com/aurafriday/system_mcp) - Full desktop automation, multi-platform. `3 ⭐`.
- [MCP Computer Use](https://github.com/mediar-ai/MCP-server-client-computer-use-ai-sdk) - Screenpipe-based computer control. `195 ⭐`.
- [Desktop Automation MCP](https://github.com/tanob/mcp-desktop-automation) - RobotJS-based desktop automation. `34 ⭐`.
- [Automation MCP](https://github.com/ashwwwin/automation-mcp) - macOS automation, mouse, keyboard, screenshots. `415 ⭐`.
- [Windows Desktop Automation MCP](https://github.com/mario-andreschak/mcp-windows-desktop-automation) - Windows desktop automation via AutoIt. `113 ⭐`.
- [VNC MCP](https://github.com/volkan-m/vnc-mcp-server) - VNC integration for remote agent control. `1 ⭐`.

## Sandbox and Containerization

Keep your AI agent from burning down the house. Run it in a sandbox.

- [E2B Desktop](https://github.com/e2b-dev/desktop) - Open-source secure virtual desktop. `1.4k ⭐`.
- [Agent Sandbox](https://github.com/agent-infra/sandbox) - Browser plus Shell plus File plus MCP in one container. `5.7k ⭐`.
- [Code Sandbox MCP](https://github.com/Automata-Labs-team/code-sandbox-mcp) - Secure code sandbox in Docker. `326 ⭐`.
- [Cyberdesk](https://github.com/cyberdesk-hq/cyberdesk) - Kubernetes-native virtual desktop orchestration. `313 ⭐`.
- [EdgeBox](https://github.com/BIGPPWONG/EdgeBox) - Local desktop sandbox with MCP support. `213 ⭐`.
- [Sandbox0](https://github.com/sandbox0-ai/sandbox0) - General-purpose sandbox with hot pool. `76 ⭐`.

## Voice-Controlled Agents

Talk to your computer and it actually does things. Revolutionary.

- [Fazm](https://github.com/mediar-ai/fazm) - Fully local macOS AI agent via voice. `312 ⭐`.
- [Voqal](https://github.com/voqal/voqal) - Voice-native AI agent, speech-to-code. `193 ⭐`.
- [Voice Mirror](https://github.com/contextmirror/voice-mirror) - Voice-controlled AI overlay, Tauri plus Rust. `10 ⭐`.
- [Colossus](https://github.com/richardanaya/colossus) - Voice-controlled multi-agent dev system. `15 ⭐`.
- [Tankwork](https://github.com/agenttankos/tankwork) - Computer vision plus voice commands, macOS. `98 ⭐`.
- [Desktop Agent Voice](https://github.com/ruslankoroy/desktop-agent) - CV plus Whisper voice input. `34 ⭐`.

## Agent Memory

Because your AI should remember that you hate dark mode (weirdo).

- [Mem0](https://github.com/mem0ai/mem0) - Universal memory layer for AI agents. `63.0k ⭐`.
- [OpenMemory](https://github.com/CaviraOSS/OpenMemory) - Cognitive memory engine with 4 memory types. `4.4k ⭐`.
- [A-Mem](https://github.com/agiresearch/A-mem) - Agentic Memory with knowledge networks. `1.1k ⭐`.
- [ReMe](https://github.com/agentscope-ai/ReMe) - Memory management kit, SOTA on benchmarks. `3.3k ⭐`.
- [Memori](https://github.com/MemoriLabs/Memori) - Agent-native memory infrastructure, LLM-agnostic. `15.7k ⭐`.
- [MemMachine](https://github.com/MemMachine/MemMachine) - Long-term episodic plus profile memory. `3.4k ⭐`.
- [SimpleMem](https://github.com/aiming-lab/SimpleMem) - Semantic lossless compression, MCP server. `3.7k ⭐`.
- [MemLayer](https://github.com/divagr18/memlayer) - Plug-and-play, under 100ms search. `277 ⭐`.
- [Agent Memory](https://github.com/rohitg00/agentmemory) - Persistent memory for AI coding agents, auto-capture via hooks. `26.9k ⭐`.

## Agent Orchestration

When one agent is not enough and you need a whole crew.

- [Ruflo](https://github.com/ruvnet/ruflo) - Enterprise AI orchestration, 60 plus agents. `67.6k ⭐`.
- [Claude Code by Agents](https://github.com/baryhuang/claude-code-by-agents) - Multi-agent Claude Code with at-mentions. `890 ⭐`.
- [AnyTool](https://github.com/HKUDS/AnyTool) - Universal tool-use layer with recording. `685 ⭐`.

## Agent Testing and Evaluation

Prove your agent actually works (or laugh at how badly it fails).

- [ScreenSuite](https://github.com/huggingface/screensuite) - 13 benchmarks for GUI agents. `145 ⭐`.
- [OSUniverse](https://github.com/agentsea/osuniverse) - 160 complex multimodal desktop tasks. `24 ⭐`.
- [ScaleCUA](https://github.com/OpenGVLab/ScaleCUA) - Cross-platform dataset plus training framework. `1.1k ⭐`.
- [Agent VCR](https://github.com/ixchio/agent-vcr) - Time-travel debugging for AI agents. `33 ⭐`.

## Game-Playing Agents

AI that plays games while you pretend to work.

- [AI-Player](https://github.com/shasankp000/AI-Player) - Minecraft mod with LLM-powered AI player. `138 ⭐`.
- [OSRS PVP RL](https://github.com/Naton1/osrs-pvp-reinforcement-learning) - Deep RL for Old School RuneScape PvP. `170 ⭐`.
- [Bedrock Minecraft Agent](https://github.com/build-on-aws/amazon-bedrock-minecraft-agent) - Minecraft bot with Amazon Bedrock. `59 ⭐`.
- [OSRS-CV](https://github.com/KaustubhLall/OSRS-CV) - Computer vision for OSRS automation. `3 ⭐`.
- [Claude Minecraft Use](https://github.com/ObservedObserver/claude-minecraft-use) - Claude playing Minecraft. `25 ⭐`.
- [Minecraft-RL](https://github.com/otsolappalainen/Minecraft-RL) - Deep RL training AI to play Minecraft. `2 ⭐`.

## Training Data Tools

Collect data so your AI agent can learn from humans who actually know how to use a computer.

- [OpenCUA](https://github.com/xlang-ai/OpenCUA) - 22.6K trajectories, annotation tools. `816 ⭐`.
- [GUI Dataset Creator](https://github.com/harpreetsahota204/gui_dataset_creator) - Annotate GUI interactions in COCO format. `13 ⭐`.
- [Interaction Logger](https://github.com/hemangjoshi37a/AIComputerInteractionLogger) - Capture screenshots, mouse, keyboard. `13 ⭐`.
- [Data Collection](https://github.com/bobcoi03/computeruse-data-collection) - Privacy-first interaction data collection. `1 ⭐`.
- [Captr](https://github.com/anaishowland/Captr_Windows) - Screen recording plus interaction capture. `8 ⭐`.

## Screen Understanding

Parse the chaos of a desktop into structured data your AI can reason about.

- [Screen2AX](https://github.com/MacPaw/Screen2AX) - Vision to macOS accessibility tree, 77 percent F1. `32 ⭐`.

## Browser Extension Agents

Your browser, but smarter. And it does things for you.

- [ChromeClaw](https://github.com/algopian/chromeclaw) - OpenClaw-inspired Chrome extension. `192 ⭐`.
- [Hanzi Browse](https://github.com/hanzili/hanzi-browse) - Give your AI agent your real browser via MCP. `175 ⭐`.
- [Dev Browser](https://github.com/SawyerHood/dev-browser) - Claude Code browser automation plugin. `6.5k ⭐`.
- [WebOperator](https://github.com/KazKozDev/WebOperator) - A small browser agent that lives inside Chrome (formerly Browser Agent Extension). `1 ⭐`.
- [Izan.io](https://github.com/ekingunoncu/izan.io) - 17 plus providers, no-code action recorder. `29 ⭐`.
- [Browser Control](https://github.com/dhamaniasad/browser-control) - Gemini multimodal browser automation. `16 ⭐`.

## Desktop-Native AI Assistants

Your always-on AI buddy that lives in your system tray.

- [OpenClaw](https://github.com/openclaw/openclaw) - Multi-channel AI assistant with skills. `385.9k ⭐`.

## IDE-Based Agents

Coding agents that learned to use a mouse.

- [Mastra Code UI](https://github.com/mastra-ai/mastra-code-ui) - Desktop coding agent with multi-model. `53 ⭐`.
- [Elves](https://github.com/mvmcode/elves) - Tauri app orchestrating Claude Code and Codex. `11 ⭐`.
- [Pilos Agents](https://github.com/pilos-ai/agents) - Visual desktop for Claude Code, multi-agent. `39 ⭐`.

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

- [ranpox/awesome-computer-use](https://github.com/ranpox/awesome-computer-use) - The OG CUA list with papers and projects. `573 ⭐`.
- [Awesome-GUI-Agent](https://github.com/showlab/Awesome-GUI-Agent) - GUI agent papers and projects. `1.2k ⭐`.
- [GUI-Agents-Paper-List](https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List) - Comprehensive paper list. `880 ⭐`.
- [Awesome-GUI-Agents](https://github.com/ZJU-REAL/Awesome-GUI-Agents) - GUI agents with project links. `451 ⭐`.
- [ACU](https://github.com/trycua/acu) - Awesome Agents for Computer Use. `1.7k ⭐`.
- [steel-dev/awesome-web-agents](https://github.com/steel-dev/awesome-web-agents) - Web agents. `1.5k ⭐`.
- [awesome-local-llm](https://github.com/rafska/awesome-local-llm) - Local LLM ecosystem. `2.5k ⭐`.
