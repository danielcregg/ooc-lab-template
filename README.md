# OOC Lab Template

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A ready-to-use Java lab template for Object-Oriented Computing (OOC) coursework at ATU. Pre-configured with a GitHub Codespaces dev container for a seamless cloud-based development experience.

## Overview

This repository provides a starter template for OOC lab assignments. It includes a basic Java project structure with a `Main.java` entry point, a pre-configured VS Code dev container running a full Java environment, and sensible editor defaults so students can begin coding immediately.

## Features

- Pre-configured Java dev container for GitHub Codespaces
- VS Code settings with Java extension support and IntelliCode
- Standard Java package structure (`ie.atu.testpackage`)
- One-click open of `Main.java` on workspace launch
- GitHub Copilot integration included

## Prerequisites

- A GitHub account with access to [GitHub Codespaces](https://github.com/features/codespaces), **or**
- [Java JDK](https://adoptium.net/) 17+ installed locally
- [Visual Studio Code](https://code.visualstudio.com/) with the Java Extension Pack (optional, for local development)

## Getting Started

### Installation

1. **Use as a template** — click the **Use this template** button on GitHub to create your own copy, or clone directly:
   ```bash
   git clone https://github.com/danielcregg/ooc-lab-template.git
   cd ooc-lab-template
   ```
2. **Open in Codespaces** (recommended) — click **Code > Codespaces > Create codespace on main** from the GitHub repo page.

### Usage

Compile and run the project from the repository root:

```bash
javac -d out src/ie/atu/testpackage/Main.java
java -cp out ie.atu.testpackage.Main
```

You should see:

```
Hello, world!
```

Edit `src/ie/atu/testpackage/Main.java` to begin your lab work.

## Tech Stack

- **Language:** Java
- **Dev Environment:** VS Code Dev Containers / GitHub Codespaces
- **Container Image:** `mcr.microsoft.com/devcontainers/java:latest`

## License

This project is licensed under the [MIT License](LICENSE).
