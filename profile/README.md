<p align="center">
  <img src="https://github.com/gillisandrew/shard/blob/main/docs/attachments/shard-full-logo.png?raw=true" style="width: 256px;height: auto" alt="Shard for Obsidian logo" />
</p>

# Shard Plugin System for Obsidian

Welcome to **Shard for Obsidian** — an experimental plugin system for managing [Obsidian](https://obsidian.md) plugins distributed via GitHub Container Registry (GHCR).

## 🎯 Why Shard?

The official Obsidian plugin system has several limitations that Shard addresses:

- **📦 Distribution**: Beyond the community directory — faster updates and more control via GHCR
- **🔒 Security**: Built-in mechanisms for plugin authenticity and integrity verification
- **🔐 Privacy**: Support for private plugins with granular access control
- **✅ Granular Trust**: Move beyond all-or-nothing plugin trust

The official system forces users to either trust all community plugins or none at all. **Shard provides a more granular approach to plugin trust and verification.**

## 🏗️ Components

- **[@shard-for-obsidian/lib](https://www.npmjs.com/package/@shard-for-obsidian/lib)**: Core TypeScript library for GHCR interaction
- **[@shard-for-obsidian/cli](https://www.npmjs.com/package/@shard-for-obsidian/cli)**: CLI tool for pushing/pulling plugins to/from GHCR
- **shard-installer**: Obsidian plugin for browsing, installing, and managing plugins from GHCR

## ✨ Feature Status

### Completed ✅
- Core library for GHCR interaction
- Obsidian plugin installer
- CLI tool for plugin management (push, pull, marketplace integration)
- GitHub-hosted community marketplace with dynamic version querying
- Legacy Obsidian community plugin directory integration

### Planned 🚀
- Automated vulnerability scanning for plugin bundles
- Static analysis security tools (API usage enumeration, network call detection)
- Plugin signing and verification
- Enhanced documentation and examples
- GitHub Actions for automated plugin publishing

## 🚀 Quick Start

Install the CLI globally:

```bash
npm install -g @shard-for-obsidian/cli
```

Or use the library in your project:

```bash
npm install @shard-for-obsidian/lib
```

## 📚 Key Repositories

- **[shard](https://github.com/gillisandrew/shard)**: Main monorepo with core packages
- More repositories coming soon!

## 🤝 Contributing

We welcome contributions from the community! Whether you're a developer, security researcher, or Obsidian enthusiast:

- 🐛 Report bugs and issues
- 💡 Suggest new features and improvements
- 🔧 Submit pull requests
- 📖 Improve documentation
- 🔍 Help with security audits

## 📬 Get Involved

- **GitHub Discussions**: Join conversations in our project repositories
- **Issues**: Report bugs or request features in the relevant repository

---

<sub>⚠️ **EXPERIMENTAL**: Shard is under active development. Use with caution in production environments.</sub>

<sub>Built with ❤️ for the Obsidian community</sub>
