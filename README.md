<p align="center">
  <img src="your-logo-url-here" alt="CloudForge Logo" width="200"/>
</p>
<h1 align="center">CloudForge</h1>
<p align="center">
    <a href="https://github.com/txrunn/cloudforge/stargazers">
        <img src="https://img.shields.io/github/stars/txrunn/cloudforge"
             alt="GitHub stars"/>
    </a>
    <a href="https://github.com/txrunn/cloudforge/issues">
        <img src="https://img.shields.io/github/issues/txrunn/cloudforge"
             alt="GitHub issues"/>
    </a>
    <a href="https://github.com/txrunn/cloudforge/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/txrunn/cloudforge"
             alt="License"/>
    </a>
    <a href="https://threads.com/@currydumpster">
    <img src="https://img.shields.io/badge/Threads-currydumpster-white" alt="Threads"/>
  </a>
</p>
<p align="center">
    <strong>Cloud Native Minecraft Server Management Bot</strong><br>
    Built with Rust, Serenity, and Shuttle for easy,scalable Minecraft server
    management in the cloud.
</p>

## Features

- **Containerized Minecraft Servers**: Leverage Shulker K8s Operator
- **Freemium Model**: Users can access basic server functionalities for free
- **Modpack Support**: Support for CurseForge and Feed the Beast modpacks.
- **Cloud-Native and Scalable**: Designed to be cost-efficient and scalable

## Prerequisites

- Rust Programming Environment
- Docker and Shulker Setup
- Access to a cloud provider (e.g., AWS, GCP, Azure)
- Discord Bot Token (from Discord Developer Portal)

## Setup

1. **Cloud Environment Setup**: Configure your cloud environment to support Docker
2. **Bot Token**: Place your Discord bot token in a `Secrets.toml` file
3. **Install Dependencies**: Run `cargo build` to install the necessary Rust dependencies

## Usage

- **Starting the Bot**: Run `cargo run` to start the bot.
- **Bot Commands**:
  - `!mc create <unique_server_name>`: Creates a new Minecraft server
  - `!mc upgrade`: Upgrades a user's server to a premium tier.
  - Additional commands for server management and user tier management.

## Configuration

- Configure the bot and server settings in `config.rs`.
- Set up modpack sources and cloud provider details.

### Reference Information

- [Discord Developer Portal](https://discord.com/developers/applications)
- [Discord API](https://discord.com/developers/docs/getting-started)
- [Serenity](https://docs.rs/poise/latest/poise/#introduction-to-serenity)
- [Shuttle](https://docs.shuttle.rs/introduction/what-is-shuttle)
- [Shulker](https://shulker.jeremylvln.fr/latest/guide/)
- [Agones](https://cloud.google.com/blog/products/containers-kubernetes/introducing-agones-open-source-multiplayer-dedicated-game-server-hosting-built-on-kubernetes)
