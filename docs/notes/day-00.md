# Day 0: Environment setup

| Tool | Version |
|---|---|
| .NET SDK | 10.0.403 |
| Node.js | v26.12.1 |
| Git | git version 2.56.0 |
| Docker | Docker version 29.9.2, build a82e528 |
| Azure CLI | azure-cli                         2.91.0 |
| GitHub CLI | gh version 2.103.2 (2026-10-23) |

## Problems I hit and how I fixed them
- Docker: command not found. Fixed by adding the Docker bin folder to PATH in ~/.zshrc.
- Git: a keychain password prompt blocked the push. Fixed by entering the keychain password.
- Branch protection: confirmed that a direct push to main is rejected.
