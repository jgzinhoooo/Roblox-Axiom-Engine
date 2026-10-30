# Roblox Axiom Engine

> **Development & Update Notice:** Axiom Engine is an independent project maintained in my free time alongside work, school, and other responsibilities. Development time is limited, so updates may be irregular and no fixed release schedule is guaranteed. I will keep improving the project whenever possible, prioritizing stability and quality over rushed releases. Thank you for your patience and support.

**Precision Builder — AI-Powered Development for Roblox Studio**

🌐 **Official Website:** https://jgzinhoooo.github.io/Roblox-Axiom-Engine/

Roblox Axiom Engine is an AI-assisted development project designed to bring precision, automation, and multi-agent collaboration to Roblox Studio.

Its core component, **Precision Builder**, enables AI agents to build, modify, inspect, and optimize 3D environments, scripts, and user interfaces through a shared development infrastructure.

## AI Integration

The project is designed to support two AI development agents:

- **Google Antigravity** — AI-powered development, automation, building, and testing.
- **OpenAI Codex** — AI-powered programming, code analysis, debugging, and development.

Both agents are intended to communicate with Roblox Studio through a shared bridge, allowing them to collaborate on the same project without conflicting modifications.

## Planned Features

- **Multi-Agent Collaboration:** Shared tasks, project state, and conflict prevention.
- **Precision 3D Building:** Procedural geometry, structured models, and spatial alignment.
- **Shared Spatial Memory:** Persistent tracking of objects, coordinates, and dependencies.
- **Script Management:** Search, inspect, edit, and debug Luau scripts.
- **UI Development:** Build responsive Roblox interfaces.
- **Automated Validation:** Detect errors, geometry issues, and potential conflicts.
- **Version Control & Rollback:** Track changes and recover previous states.
- **Optimized Execution:** Batch operations to reduce unnecessary tool calls.

## Architecture

```text
Google Antigravity     OpenAI Codex
        \                  /
         \                /
          Precision Hub
                |
           StudioBridge
                |
         Precision Builder
                |
           Roblox Studio
```

The architecture is designed to allow both agents to work independently or collaboratively using shared tools and project information.

## Project Goals

Our goal is to make AI-assisted Roblox development more accurate, efficient, organized, and accessible.

Instead of generating disconnected objects or scripts, Precision Builder aims to provide a structured development workflow where AI agents can understand existing projects and build upon previous work.

## Development Status

**Work in Progress (WIP)**

The project is under active development. Features and integrations described here represent the intended architecture and may not yet be fully implemented.

## Technology

- Roblox Studio
- Luau
- Model Context Protocol (MCP), where supported
- Google Antigravity
- OpenAI Codex

---

**Roblox Axiom Engine — Building smarter, together.**
