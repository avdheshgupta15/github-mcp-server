# GitHub MCP Server & Client

This project demonstrates how to use the Model Context Protocol (MCP) with n8n by creating an MCP Server and an MCP Client workflow.

## Project Overview

The project contains two n8n workflows:

### 1. MCP Server
**File:** `MCP Server.json`

The MCP Server workflow exposes tools and functionality that can be accessed by an MCP-compatible client.

### 2. MCP Client
**File:** `MCP Client.json`

The MCP Client workflow connects to the MCP Server and uses the tools made available by the server.

## Technologies Used

- n8n
- Model Context Protocol (MCP)
- GitHub
- JSON-based n8n workflows

## Repository Structure

```text
github-mcp-server/
├── MCP Client.json
├── MCP Server.json
└── README.md
