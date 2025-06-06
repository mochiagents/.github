# Hello, Mochi

**Building open source AI agents for everyday life**

Welcome to Mochi Agents, an open source initiative dedicated to creating intelligent, practical AI agents that seamlessly integrate into daily workflows. Our mission is to democratize AI automation by providing powerful, accessible tools that anyone can use, modify, and extend.

## 🌟 Our Vision

We believe AI agents should be:
- **Open & Transparent**: Fully open source with clear, understandable implementations
- **Practical & Useful**: Solving real-world problems that people face every day
- **Modular & Extensible**: Built with composable components that can be mixed and matched
- **Community-Driven**: Developed collaboratively with input from users and contributors

## 🌸 About Mochi

**Mochi** is our flagship project - a sophisticated AI agent framework that transforms complex queries into actionable task execution plans. Unlike traditional chatbots, Mochi understands your intent, breaks down complex requests into manageable steps, and executes them using a rich ecosystem of tools and integrations.

### Key Capabilities
- **Intelligent Task Planning**: Automatically decomposes user queries into executable workflows
- **Tool Integration**: Seamlessly connects to external services via the Model Context Protocol (MCP)
- **Parallel Execution**: Runs multiple tasks concurrently with smart dependency management
- **Error Recovery**: Automatically adapts and repairs execution plans when things go wrong
- **Multi-Interface Support**: CLI, REST API, and programmatic interfaces for any use case

## 📦 Mochi Components

| Component | Status | Description | Repository |
|-----------|--------|-------------|------------|
| **Worker** | ✅ Active | Core agent framework with intelligent task planning and execution | [`link`](https://github.com/mochiagents/worker) |
| **Toolkit** | ✅ Active | Collection of MCP-compatible tools for extending agent capabilities | [`link`](https://github.com/mochiagents/toolkit) |

More coming soon...

## 🏗 Architecture Philosophy

Mochi is built on several key principles:

### Composability
Components are designed to work together seamlessly while remaining independent and reusable.

### Extensibility
The Model Context Protocol (MCP) provides a standardized way to add new capabilities without modifying core components.

### Reliability
Built-in error handling, retry logic, and circuit breakers ensure robust operation in production environments.

### Transparency
Every decision, execution step, and tool call is logged and can be inspected for debugging and optimization.

## 🤝 Contributing

We welcome contributions from developers, researchers, and users at all levels! Here's how you can get involved:

### Code Contributions
- **Bug Fixes**: Help us identify and fix issues
- **New Features**: Implement new capabilities in the core framework
- **Tool Development**: Create new tools for the toolkit
- **Documentation**: Improve guides, tutorials, and API documentation

See the contributing guide (`CONTRIBUTING.md`) for the repository you would like to contribute to for more details.

## 📚 Documentation

- **[Worker Documentation](./worker/README.md)**: Complete guide to the core agent framework
- **[Toolkit Documentation](./toolkit/README.md)**: Tool development and MCP integration
  
## 💬 Community & Support

- **Discord**: [Join our community](https://discord.gg/bY62AWfKuA) for real-time discussions
- **GitHub Issues**: [Report bugs](https://github.com/mochiagents/mochi/issues) and request features
- **GitHub Discussions**: [Ask questions](https://github.com/mochiagents/mochi/discussions) and share ideas

## 📄 License

All Mochi Agents projects are released under the [MIT License](LICENSE). We believe in keeping AI tools open and accessible to everyone.

## 🙏 Acknowledgments

Special thanks to:
- The [LangChain](https://github.com/langchain-ai/langchain) and [LangGraph](https://github.com/langchain-ai/langgraph) teams for foundational frameworks
- The [Model Context Protocol](https://modelcontextprotocol.io/) initiative for standardizing tool integration
- Our community of contributors, users, and feedback providers
- The broader open source AI community for inspiration and collaboration

---

*Making AI agents accessible, practical, and open for everyone.* 🌸
