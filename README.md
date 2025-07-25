# Orbitron Releases

This repository contains the release builds and distribution files for the Orbitron project.

## About Orbitron

Orbitron is a powerful terminal-based AI assistant that provides intelligent cloud engineering support directly from the terminal for AWS, GCP, Azure, and other cloud platforms.

## Releases

All stable releases of Orbitron are published here. You can find:

- Binary distributions for different platforms
- Release notes and changelogs
- Installation packages
- Documentation for each version

## Download

Visit the [Releases](../../releases) page to download the latest version of Orbitron for your platform.

## Installation

### Download Pre-built Binaries

Download the appropriate binary for your platform from the [releases page](https://github.com/AlphaCode-AI/orbitron/releases/tag/v0.1.0):

**macOS:**
```bash
# Apple Silicon (M1/M2/M3)
curl -L -o orbitron https://github.com/AlphaCode-AI/orbitron-release/releases/download/v0.1.0/orbitron-macos-arm64
chmod +x orbitron
sudo mv orbitron /usr/local/bin/

# Intel
curl -L -o orbitron https://github.com/AlphaCode-AI/orbitron-release/releases/download/v0.1.0/orbitron-macos-x86_64
chmod +x orbitron
sudo mv orbitron /usr/local/bin/
```

**Linux:**
```bash
# AMD64
curl -L -o orbitron https://github.com/AlphaCode-AI/orbitron-release/releases/download/v0.1.0/orbitron-linux-x86_64
chmod +x orbitron
sudo mv orbitron /usr/local/bin/

# ARM64
curl -L -o orbitron https://github.com/AlphaCode-AI/orbitron-release/releases/download/v0.1.0/orbitron-linux-arm64
chmod +x orbitron
sudo mv orbitron /usr/local/bin/
```

**Windows:**
```powershell
# Download from browser or use PowerShell
Invoke-WebRequest -Uri "https://github.com/AlphaCode-AI/orbitron-release/releases/download/v0.1.0/orbitron-windows-x86_64.exe" -OutFile "orbitron.exe"
# Add to PATH or run from current directory
```

## Support

For issues or questions, please create an issue in this repository.

## Access Requirements

Orbitron is restricted to authorized users only. Access requires proper authentication and approval. Please ensure you have the necessary permissions before attempting to download or use Orbitron.

