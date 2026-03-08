# Hardware MCP

> Open-source MCP servers bridging AI to physical hardware.

AI can control Jira, GitHub, Slack — but what about your oscilloscope, Arduino, or PLC?  
**hardware-mcp** is building the protocol layer that connects AI agents to the physical world.

---

## Servers

| Server | Hardware | Status |
|--------|----------|--------|
| [arduino-mcp-server](https://github.com/hardware-mcp/arduino-mcp-server) | Arduino / arduino-cli | ✅ Stable |
| rpi-mcp-server | Raspberry Pi GPIO, I2C, SPI | 🚧 Coming soon |
| oscilloscope-mcp | Keysight, Rigol, Tektronix (SCPI/VISA) | 🚧 Coming soon |
| plc-mcp-server | Industrial PLCs / Ladder Logic | 🚧 Coming soon |
| power-supply-mcp | Programmable bench PSUs | 🚧 Coming soon |

---

## What is MCP?

[Model Context Protocol (MCP)](https://modelcontextprotocol.io) is an open standard by Anthropic that lets AI models interact with external tools and services through a structured interface.

hardware-mcp extends this to the **physical world** — giving AI agents the ability to read sensors, control actuators, compile and upload firmware, monitor serial output, and run safety checks before touching real hardware.

---

## Philosophy

- **Safety first** — every server includes electrical safety preflight checks
- **Open source** — MIT licensed, community driven
- **Protocol-level thinking** — we're building a standard, not just wrappers
- **Research-backed** — we publish benchmarks and papers on AI-hardware control

---

## Get Involved

- ⭐ Star a server repo
- 🐛 File issues or feature requests
- 🔧 Contribute a new hardware server
- 📄 Read our research (coming soon)

---

*Built by engineers who work with hardware every day.*
