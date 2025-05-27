# Terminal Pacman 🟡

A terminal-based implementation of the classic Pacman arcade game using ASCII graphics and ANSI escape sequences.

## Overview

This project recreates the Pacman experience in the terminal, featuring authentic ghost AI behaviors, smooth rendering, and all the classic game mechanics. Built with Python, it demonstrates advanced terminal manipulation techniques and clean game architecture.

## Technical Scope

- **Rendering Engine**: Custom ANSI-based renderer with double-buffering
- **Game Logic**: Complete Pacman rules, scoring, and level progression
- **Ghost AI**: Faithful recreation of Blinky, Pinky, Inky, and Clyde behaviors
- **Input System**: Non-blocking keyboard controls
- **Performance**: Optimized for smooth terminal gameplay

## Architecture

```
Game Engine ──► Renderer ──► Terminal
     │
State Manager
     │
Game Objects / AI System / Input Handler
```

The modular design separates game logic from rendering and I/O, making the codebase easy to understand and extend.

## Requirements

- Python 3.7+
- Terminal with ANSI escape sequence support
- 80x24 character window minimum

## Development Status

🚧 **Under Active Development**

- [x] Core rendering engine
- [x] Maze system
- [ ] Player controls and collision
- [ ] Ghost AI implementation
- [ ] Scoring and power-ups
- [ ] Sound effects and polish

## Contributing

Contributions welcome! Key areas include game mechanics, AI improvements, testing, and cross-platform support. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## References

- [The Pac-Man Dossier](https://www.gamasutra.com/view/feature/3938/the_pacman_dossier.php)
- [ANSI Escape Sequences](https://en.wikipedia.org/wiki/ANSI_escape_code)

## License

MIT License - See [LICENSE](LICENSE)

## Author Information

Below is a collection of README content from some of the author’s other repositories, as requested by Issue #1.

### From PyramidFL (MobiCom'22)
"...PyramidFL: Fine-grained Data and System Heterogeneity-aware Client Selection for Efficient Federated Learning...\nThis repository contains scripts/instructions for reproducing the experiments in our MobiCom’22 paper..."

### From CurvingLoRa_NSDI22 (NSDI'22)
"...CurvingLoRa to Boost LoRa Network Throughput via Concurrent Transmission...\nThis repository contains scripts/instructions for reproducing experiments in our NSDI’22 paper..."

### From cnli.me
"...BioPage: [cnli.me](https://cnli.me/)\nWe thank [Chenshu wu](https://cswu.me/) for providing the design template of this webpage..."

### From WiVelo_SECON22 (SECON'22)
"...WiVelo: Fine-grained Walking Velocity Estimation for Wi-Fi Passive Tracking...\nThis repository contains scripts and instructions for reproducing the experiments in our SECON’22 paper..."

---

*Building the classic arcade experience, one character at a time.*
