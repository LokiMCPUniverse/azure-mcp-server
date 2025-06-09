# Azure MCP Server

<div align="center">

# Azure Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/azure-mcp-server?style=social)](https://github.com/LokiMCPUniverse/azure-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/azure-mcp-server?style=social)](https://github.com/LokiMCPUniverse/azure-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/azure-mcp-server?style=social)](https://github.com/LokiMCPUniverse/azure-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/azure-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/azure-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/azure-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/azure-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/azure-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/azure-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/azure-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/azure-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/azure-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/azure-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/azure-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/azure-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/azure-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/azure-mcp-server/graphs/contributors)

</div>

A Model Context Protocol (MCP) server for integrating Azure with GenAI applications.

## Overview

Microsoft Azure cloud services integration

## Features

- Comprehensive Azure API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install azure-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/azure-mcp-server.git
cd azure-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Azure API requirements.

## Quick Start

```python
from azure_mcp import AzureMCPServer

# Initialize the server
server = AzureMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
