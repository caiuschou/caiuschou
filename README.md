<div align="center">

# Hi, I'm Caius 👋

[![](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![](https://img.shields.io/badge/AI-FF6F00?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![](https://img.shields.io/badge/MCP-20232A?style=for-the-badge&logo=atom&logoColor=61DAFB)](https://modelcontextprotocol.io/)

**Systems Engineer | Rust Enthusiast | Building Tools for AI Agents**

I'm passionate about building robust tools for AI agents and developer workflows in Rust. Currently focused on the **Model Context Protocol (MCP)** ecosystem and **LangGraph-inspired agent frameworks**.

</div>

---

## 🚀 What I'm Building

### [mcp-rust](https://github.com/caiuschou/mcp-rust)
> A complete Rust implementation of the Model Context Protocol

Production-ready MCP implementation with core types, server/client libraries, and reference implementations for GitHub, GitLab, and Zoekt. Features stdio/HTTP/WebSocket transports and comprehensive examples.

```rust
// MCP server in Rust - simple and type-safe
let server = McpServer::new(ServerOptions::default())
    .register_tool(my_tool)
    .run_stdio()?;
```

### [langgraph-rust](https://github.com/caiuschou/langgraph-rust)
> Stateful agent framework with ReAct pattern

LangGraph-inspired framework bringing stateful agent graphs to Rust. Features ReAct pattern (Think → Act → Observe), LLM integration, memory/checkpointing, and MCP tool support.

### [workspace](https://github.com/caiuschou/workspace)
> MCP workspace architecture demo

Demonstrates how to structure a Rust system with shared core and dedicated server/client binaries. A practical guide to MCP architecture.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python) |
| **AI/LLM** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai) ![GLM](https://img.shields.io/badge/GLM-00A67E?style=flat-square) |
| **Protocols** | JSON-RPC • stdio • WebSocket • HTTP/SSE |
| **Databases** | ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite) ![LanceDB](https://img.shields.io/badge/LanceDB-5EA6B0?style=flat-square) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions) ![Cargo](https://img.shields.io/badge/Cargo-24455F?style=flat-square&logo=rust) |

---

## 📊 GitHub Stats

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=caiuschou&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=caiuschou&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

---

## 🌱 Current Focus

- **[MCP](https://modelcontextprotocol.io/)** - Building production-ready Rust tooling for the Model Context Protocol
- **Agent Frameworks** - Creating reusable, stateful agent systems in Rust
- **Developer Experience** - Improving workflows for AI-assisted development

---

## 📫 Connect

<div align="center">

**Feel free to reach out!**

[![](https://img.shields.io/badge/GitHub-caiuschou-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/caiuschou)

</div>

---

<div align="center">

<i>Building the future of AI agent tooling, one crate at a time. 🦀</i>

</div>
