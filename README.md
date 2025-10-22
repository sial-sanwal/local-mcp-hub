# 🧠 Demo MCP Server

A lightweight **Model Context Protocol (MCP)** server built with [FastMCP](https://github.com/prefix-dev/fastmcp) and managed using [uv](https://docs.astral.sh/uv/).  
This server is connected to **Claude Desktop**, enabling local experimentation with custom MCP tools and model integrations.

---

## 🚀 Features

- ⚡ Built with **FastMCP** for ultra-fast MCP development  
- 🔗 Integrates directly with **Claude Desktop**  
- 🧩 Includes a simple demo tool (`add_numbers`)  
- 🧠 Ideal for **local testing, experimentation, and learning MCP protocols**  
- 🧱 Uses **uv** for dependency management and environment isolation  

---

## 📦 Setup & Installation

Clone the repository:

```bash
git clone https://github.com/sial-sanwal/local-mcp-hub
cd mcp-server-hub
```

Install dependencies with uv:

```bash
uv sync
```

## Running the MCP Server

```bash
uv run fastmcp dev main.py
```

