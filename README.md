# 🎮 Tactical Ops Quick Join - Mod

A modern, fast server browser for Tactical Operations with advanced features and an improved user interface.

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?logo=dotnet)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)
![License](https://img.shields.io/badge/License-MIT-green)

<!-- TODO: Add main screenshot here -->
![Main Interface](screenshots/main-interface.png)

## ✨ Features

- **🌐 Real-time Server Browser** - Browse all available Tactical Ops servers instantly
- **🗺️ Fast Map Preview** - Optimized image loading with cache (256x144 thumbnails)
- **📊 Ping Display** - Shows latency to each server with color coding
- **👥 Player Details** - Detailed player information and statistics
- **⭐ Favorites System** - Mark your favorite servers for quick access
- **🎨 Dark/Light Theme** - Switchable design for your preference
- **🔄 Auto-Refresh** - Automatic server list updates
- **⌨️ Keyboard Shortcuts** - Quick actions with F5, Enter, and Escape
- **🎯 Version Filter** - Filter servers by TO version (2.2, 3.4, 3.5)

<!-- TODO: Add feature screenshots here -->
![Map Preview](screenshots/map-preview.png)
![Dark Theme](screenshots/dark-theme.png)

## 📥 Installation

### Requirements
- Windows 10/11
- .NET 10 Runtime (included in self-contained build)
- Tactical Operations installed

### Download
1. Download the latest `TacticalOpsQuickJoin.exe` from [Releases](../../releases)
2. Run the executable
3. That's it! No installation needed.

## 🎮 Usage

### Joining Servers
1. Select a server from the list
2. Click "Join Server" or double-click the server
3. The game starts automatically

### Map Preview
- Hover your mouse over a map name
- A preview window appears after a short delay
- Move away to close the preview

### Favorites
- Click the ☆ icon to add a server to favorites
- Favorite servers appear at the top of the list

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **F5** | Refresh server list |
| **Escape** | Minimize application |
| **Enter** | Join selected server |

## 🎨 Themes

Switch between light and dark mode:
- **Menu → Toggle Theme**
- Setting is saved automatically

## ⚙️ Configuration

The application saves settings automatically:
- Theme preference (Light/Dark)
- Window position and size
- "Close on join" setting
- Favorite servers
- Master server list

## 🛠️ Development

### Build from Source
```bash
dotnet build --configuration Release
```

### Create Release Build
```bash
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true
```

## 📊 Map Data

The program loads map preview images from:
1. **Online**: GitHub Repository (automatic)
2. **Local**: `maps.json` in program folder (fallback)

Map data provided by [TO-ServerStats](https://github.com/InSource/TO-ServerStats)

## 🐛 Known Issues

- Map preview requires internet connection
- Some older TO versions may not be recognized
- Firewall can block server ping

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- Tactical Operations Community
- Map data provided by [TO-ServerStats](https://github.com/InSource/TO-ServerStats)
- Original project inspiration

## 📞 Support

For issues or questions:
- Open an [Issue](../../issues)
- Contact the TO Community

---

**Made with ❤️ for the Tactical Operations Community**
