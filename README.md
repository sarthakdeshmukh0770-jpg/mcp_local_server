# MCP Local Server

A local **Model Context Protocol (MCP)** server built with [FastMCP](https://github.com/jlowin/fastmcp), designed to run and serve MCP-compatible tools locally.

## 📋 Overview

This project provides a lightweight, local MCP server implementation that allows you to expose custom tools and resources to MCP-compatible clients (such as Claude Desktop) for local development and testing.

## ✨ Features

- 🚀 Fast and lightweight local MCP server
- 🔌 Easy integration with MCP-compatible clients
- 🛠️ Built on top of FastMCP for rapid tool development
- 📦 Simple dependency management with `uv`

## 🧰 Requirements

- Python >= 3.14
- [uv](https://docs.astral.sh/uv/) (recommended for dependency management)

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/sarthakdeshmukh0770-jpg/mcp_local_server.git
cd mcp_local_server
```

Install dependencies using `uv`:

```bash
uv sync
```

## 🚀 Usage

Run the server locally:

```bash
uv run main.py
```

## 🗂️ Project Structure