# Claude Voice MCP Fork

[![CogentEcho.ai](https://img.shields.io/badge/CogentEcho.ai-Ecosystem-blue)](https://github.com/topics/cogentecho-ai)
[![Status](https://img.shields.io/badge/Status-Pre--Alpha-orange)](https://github.com/gregmulvihill/claude-voice-mcp-fork)
[![MCP Tool](https://img.shields.io/badge/Type-MCP%20Tool-green)](https://github.com/gregmulvihill/claude-voice-mcp-fork)
[![License](https://img.shields.io/github/license/gregmulvihill/claude-voice-mcp-fork)](LICENSE)

> **⚠️ PRE-ALPHA WARNING ⚠️**  
> This project is in pre-alpha stage. The content has been created conceptually but has not been tested. Proceed with caution as significant changes may occur before the first stable release.

A development fork of the Claude Voice MCP server for testing and enhancement purposes.

## Overview

This repository is a fork of [Claude Voice MCP](https://github.com/gregmulvihill/claude-voice-mcp) designed for experimental development and testing. It allows for parallel development tracks without affecting the stability of the main MCP server implementation.

## CogentEcho.ai Ecosystem Integration

This repository is part of the [CogentEcho.ai](https://github.com/topics/cogentecho-ai) ecosystem:

- **Strategic Layer**: [Orchestrate-AI](https://github.com/gregmulvihill/orchestrate-ai) - Strategic orchestration and business logic
- **Tactical Layer**: [Automated-Dev-Agents](https://github.com/gregmulvihill/automated-dev-agents) - Tactical task execution and agent management
- **Foundation Layer**: [Multi-Tiered Memory Architecture](https://github.com/gregmulvihill/multi-tiered-memory-architecture) - Memory services for persistence
- **Tool Manager**: [MCP Manager](https://github.com/gregmulvihill/mcp-manager) - Manages Claude MCP servers, including this one

## Development Goals

1. **Experimental Features**: Test new voice capabilities without affecting the stable branch
2. **Performance Optimization**: Explore alternative TTS implementations and optimizations
3. **Integration Testing**: Test integration with new Claude Desktop features
4. **Custom Voice Models**: Experiment with customized voice styles and personalities

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- Claude Desktop application
- Web browser for testing

### Installation

```bash
# Clone the repository
git clone https://github.com/gregmulvihill/claude-voice-mcp-fork.git

# Navigate to project directory
cd claude-voice-mcp-fork

# Install dependencies
npm install

# Copy environment example and modify as needed
cp .env.example .env

# Start the server
npm start
```

## Contributing

This fork is primarily for internal development and testing. For feature contributions, please consider submitting pull requests to the main [Claude Voice MCP](https://github.com/gregmulvihill/claude-voice-mcp) repository instead.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Related Projects

- [Claude Voice MCP](https://github.com/gregmulvihill/claude-voice-mcp) - The main MCP implementation
- [MCP Manager](https://github.com/gregmulvihill/mcp-manager) - Tool for managing MCP servers in the ecosystem