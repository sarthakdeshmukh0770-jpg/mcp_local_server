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

```
mcp_local_server/
├── main.py            # Entry point for the MCP server
├── test.py             # Test cases
├── expenses.db          # Local database (example use case)
├── pyproject.toml        # Project metadata and dependencies
├── uv.lock             # Locked dependency versions
└── README.md            # Project documentation
```

## 🧪 Testing

Run the test suite:

```bash
uv run pytest test.py
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/sarthakdeshmukh0770-jpg/mcp_local_server/issues).

## 📄 License

This project is currently unlicensed. Add a license file if you plan to open source this project.

## 👤 Author

**Sarthak Deshmukh**
📧 sarthakdeshmukh0770@gmail.com