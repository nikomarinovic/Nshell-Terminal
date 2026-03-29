<h1 align="center">
  <img src="public/logo.svg" alt="NShell Logo" width="96" />
  <br />
  NShell
</h1>

<p align="center">
  A custom terminal shell built in C# using .NET — Unix-like experience, extensible by design.
</p>

<p align="center">
  <a href="https://github.com/Nmarino8/Nshell-Terminal">https://github.com/Nmarino8/Nshell-Terminal</a>
</p>

---

## What is NShell?

**NShell is a Unix-like shell for .NET that gives you:**

- Unix-style command-line experience on Windows and cross-platform .NET runtimes
- File and directory management (`ls`, `cd`, `pwd`, `touch`, `rm`, `mkdir`, and more)
- Network utilities (`ping`, `nslookup`, `ipconfig`)
- Command aliases and input history with arrow-key navigation
- Extensible architecture for adding custom commands at runtime

**`No external dependencies. Runs entirely on .NET — clone, build, and go.`**

---

## How It Works

Getting started with NShell is fast:

1. **Clone the repo** — `git clone https://github.com/Nmarino8/Nshell-Terminal.git`
2. **Open in Visual Studio** — load the `.sln` solution file
3. **Build the project** — use Debug or Release configuration
4. **Navigate to the output** — `cd NShell/bin/Debug/net7.0`
5. **Launch the shell** — run `./NShell` and start typing commands

> [!TIP]
> Type `help` or `-h` inside NShell to see the full list of available commands and their usage.

---

## Installation

### Windows
```bash
git clone https://github.com/Nmarino8/Nshell-Terminal.git
# Open NShell.sln in Visual Studio, then Build → Run
```

### macOS / Linux
```bash
git clone https://github.com/Nmarino8/Nshell-Terminal.git
cd NShell
dotnet build
cd bin/Debug/net7.0
./NShell
```

---

## Usage

Run NShell from the built executable:
```bash
cd NShell/bin/Debug/net7.0
./NShell
```

Use built-in commands:
```bash
ls, cd, pwd, touch, rm, mkdir, clear, ping, ipconfig, nslookup
```

Get help at any time:
```bash
help    # or -h
```

---

## Features

- **Unix-like Shell** — familiar command-line experience built entirely on .NET
- **File Management** — `ls`, `cd`, `pwd`, `touch`, `rm`, `mkdir` and more
- **Network Tools** — `ping`, `nslookup`, and `ipconfig` for network diagnostics
- **Command Aliases** — define shorthand for any command
- **Input History** — navigate previous commands with arrow keys
- **External App Support** — run external executables within the same terminal session
- **Extensible Design** — built to make adding new custom commands straightforward

---

## Screenshots

> [!NOTE]
> Visual examples of NShell in action, demonstrating key commands and functionality.

**Help Command**
The `help` or `-h` command lists all available commands and their usage.

<p align="center">
  <img src="Screenshots/Screenshot_1.png" alt="NShell Help Command" width="700" />
</p>

**IP Configuration and NSLookup**
The `ipconfig` and `nslookup` commands display network information including IP addresses, gateways, and DNS resolution.

<p align="center">
  <img src="Screenshots/Screenshot_2.png" alt="NShell IPConfig & NSLookup" width="700" />
</p>

---

## Data & Privacy

NShell stores no user data. All commands run locally — nothing leaves your machine.

> [!NOTE]
> NShell is a learning project and experimental platform for exploring shell architecture, command parsing, and runtime extensibility in .NET.

> [!WARNING]
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

---

<h3 align="center">
NShell does not accept feature implementations via pull requests.<br />
Feature requests and bug reports are welcome through GitHub Issues.
</h3>

---

<p align="center">
  © 2026 Niko Marinović. All rights reserved.
</p>
