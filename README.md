[![Golang](https://img.shields.io/static/v1?label=Made%20with&message=Go&logo=go&color=007ACC)](https://go.dev/)
[![Go version](https://img.shields.io/github/go-mod/go-version/knuspii/notigo)](https://github.com/knuspii/notigo)
[![Go Report Card](https://goreportcard.com/badge/github.com/Knuspii/notigo)](https://goreportcard.com/report/github.com/Knuspii/notigo)
[![Build](https://github.com/Knuspii/notigo/actions/workflows/go.yml/badge.svg)](https://github.com/Knuspii/notigo/actions/workflows/go.yml)
[![GitHub Issues](https://img.shields.io/github/issues/knuspii/notigo)](https://github.com/knuspii/notigo/issues)
[![GitHub Stars](https://img.shields.io/github/stars/knuspii/notigo?style=social)](https://github.com/knuspii/notigo/stargazers)

<h1>NotiGo 🚨</h1>

### A lightweight, crossplatform download notifier tool. 
NotiGo is made to be simple and easy!\
You want to be notified when your download is finished?\
You want to be notified when your command is finished?\
-Then this tool is for you!

## 📥 [[Download here]](https://github.com/Knuspii/crunchycleaner/releases) <- Click here to download NotiGo!

## 🔑 Key features:

- 💻 **Cross-Platform**: Works on both **Windows** and **Linux**
- ⚡ **Lightweight**: Single binary, no dependencies (just download and run it)
- 🎨 **TUI (Text-UI)**: Simple, minimalist interface, no confusing menus

## ⚙️ Start options:
```
Usage:
  NotiGo [option]

Options:
  -b  manual beep
  -v  show version
  -r  refresh rate in seconds
  -t  threshold in bytes
  -h  help
```

## External Dependencies
This project uses the following external dependencies:
- **[github.com/eiannone/keyboard](https://github.com/eiannone/keyboard)** – used for cross-platform keyboard input (MIT License)
- **[github.com/gen2brain/beeep](https://github.com/gen2brain/beeep)** - used for notifications (BSD-2-Clause license)
- **[github.com/shirou/gopsutil/](https://github.com/shirou/gopsutil)** - used for fetching network usage (BSD license)
