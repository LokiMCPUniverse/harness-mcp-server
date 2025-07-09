[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/lokimcpuniverse-harness-mcp-server-badge.png)](https://mseep.ai/app/lokimcpuniverse-harness-mcp-server)

# Harness MCP Server

<div align="center">

# Harness Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/harness-mcp-server?style=social)](https://github.com/LokiMCPUniverse/harness-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/harness-mcp-server?style=social)](https://github.com/LokiMCPUniverse/harness-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/harness-mcp-server?style=social)](https://github.com/LokiMCPUniverse/harness-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/harness-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/harness-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/harness-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/harness-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/harness-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/harness-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/harness-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/harness-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/harness-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/harness-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/harness-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/harness-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/harness-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/harness-mcp-server/graphs/contributors)

</div>

A Model Context Protocol (MCP) server for integrating Harness with GenAI applications.

## Overview

Continuous delivery and cloud cost management

## Features

- Comprehensive Harness API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install harness-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/harness-mcp-server.git
cd harness-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Harness API requirements.

## Quick Start

```python
from harness_mcp import HarnessMCPServer

# Initialize the server
server = HarnessMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
