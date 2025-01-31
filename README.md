# polyglot-code-server

![Docker](https://github.com/jpwhite3/polyglot-code-server/workflows/Docker/badge.svg)

![Code Server](https://img.shields.io/badge/Powered%20By-coder%2Fcode--server-blue)

A web-based IDE, built using [Codeserver](https://github.com/coder/code-server) on top of a custom-made, multi programming language container, built for interactive development environments.

![Screen shot](https://github.com/jpwhite3/polyglot-code-server/raw/main/images/screenshot.png)

_NOTE:_ The container image is quite large, and can be very resource intensive. Please plan accordingly.

## Included Tools

| Ecosystem             | Tools                                                |
| --------------------- | ---------------------------------------------------- |
| Node == 18.18.0       | nvm == 0.39.5, npm == 9.8.1                          |
| code-server == 4.17.1 | _various vscode plugins_                             |
| Python == 3.11.5      | Poetry == 1.1.13                                     |
| Java == 20.0.2        |                                                      |
| GO == 1.21.1          |                                                      |
| Dotnet == 6.0.122     | livingdoc                                            |
| Linux Utilities       | wget, curl, gpg, git, make, p7zip, vim, jq, xz-utils |

# Installations instructions

## Prerequisites

- Unix based OS (Linux/MacOS)
- Docker Desktop, Docker Engine, or compatible container management system

## Build

```bash
make build
```

## Run

```bash
make run
```
