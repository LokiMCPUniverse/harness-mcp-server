# Harness MCP Server

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
