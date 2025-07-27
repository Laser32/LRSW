# 🎮 Long Range Server Watcher (LRSW)

*Professional Server Monitoring and Management Tool*

---

## 🌍 Languages / Sprachen

- [🇺🇸 English](#english)
- [🇩🇪 Deutsch](#deutsch)

---

# English

## 📋 Overview

Long Range Server Watcher (LRSW) is a powerful application for monitoring and managing game servers that support the Source Query Protocol. With this application you can:

### 🚀 Core Features
- 🔍 **Server Browser**: Search and discover servers from Steam's master server list
- ⭐ **Favorites Management**: Save and organize your favorite servers
- 📊 **Real-time Monitoring**: Live server information updates
- 👥 **Player Lists**: View current players with detailed information
- ⚙️ **Server Rules**: Display and analyze server configuration
- 🎛️ **RCON Console**: Remote server administration
- 🌐 **FTP Client**: Integrated file management for server files
- 📝 **Config Generator**: Create server configuration files
- 🔧 **Plugin Management**: Update Metamod and SourceMod plugins
- 🌐 **Network Diagnostics**: Advanced network troubleshooting tools

### 🎯 Supported Games
- Counter-Strike: Global Offensive (CS:GO)
- Counter-Strike 2 (CS2)
- Counter-Strike: Source (CSS)
- Team Fortress 2 (TF2)
- Day of Defeat: Source (DoD:S)
- Half-Life 2: Deathmatch
- Garry's Mod
- Left 4 Dead 2
- And many more Source Engine games

## 🛠️ Installation

### Method 1: Installer (Recommended)
1. Download `LRSW-Setup-v2.0.0.exe`
2. Run the installer as administrator
3. Follow the installation wizard
4. Launch LRSW from Start Menu or Desktop

### Method 2: Portable
1. Extract all files to a folder of your choice
2. Run `LRSW.exe` directly
3. No installation required

### 📋 System Requirements
- Windows 10 (1809) or later
- .NET 9.0 Runtime (included in installer)
- 100 MB free disk space
- Internet connection for server browsing

## 🖥️ Main Window

### 📊 Server List
Displays your saved favorite servers with:
- **Server Name**: Custom or official server name
- **Map**: Currently running map
- **Players**: Current/Maximum player count
- **Ping**: Response time in milliseconds
- **Tags**: Server tags and game mode information

**Selection**: Click on any server to select it (highlighted with blue border)

### 👥 Player List
Shows all current players on the selected server:
- **Player Name**: In-game username
- **Score**: Current player score/frags
- **Duration**: Time connected to server

**Auto-Update**: Refreshes automatically when selecting a server

### ⚙️ Rules List
Displays server configuration rules:
- **Rule Name**: Configuration variable name
- **Value**: Current setting value
- **Description**: Explanation of the rule's purpose

## 🔍 Server Browser

### 🌐 Global Games Window
Access via: **Tools → Global Games**

**Features:**
- Browse thousands of servers from Steam's master list
- Filter by game, map, player count
- Real-time server information
- Add servers directly to favorites
- Ping measurement and sorting

**Tabs:**
- **Global**: All available servers
- **Favorites**: Your saved servers
- **Recent**: Recently visited servers

### 🔧 Server Management
- **Add to Favorites**: Click the star icon or "Add to Favorites" button
- **Remove from Favorites**: Uncheck the star icon
- **Server Details**: Double-click for detailed information
- **Direct Connect**: Right-click for game launch options

## 🎛️ RCON Console

### 🔐 Connection Setup
1. Select a server from your favorites
2. Click **"RCON"** button
3. Enter RCON password
4. Click **"Connect"**

### 💻 Command Interface
- **Command Input**: Type commands in the bottom text field
- **Execute**: Press Enter or click "Send"
- **Command History**: Use Up/Down arrows for previous commands
- **Auto-Complete**: Tab completion for common commands

### 📋 Common Commands
```
status              - Show server status
users               - List connected players
changelevel <map>   - Change current map
kick <player>       - Kick a player
ban <player>        - Ban a player
say <message>       - Send message to all players
```

## 🌐 FTP Client

### 📁 File Management
Access via: **Tools → FTP Client**

**Features:**
- **Secure Connection**: SFTP and FTP support
- **File Browser**: Navigate server directories
- **Upload/Download**: Transfer files and folders
- **Permissions**: Modify file permissions
- **Synchronization**: Keep local and remote files in sync

### 🔧 Connection Setup
1. Enter server hostname/IP
2. Provide username and password
3. Select connection type (FTP/SFTP)
4. Click **"Connect"**

## 📝 Config Generator

### ⚙️ Server Configuration
Access via: **Tools → Config Generator**

**Tabs:**
- **Basic**: Server name, passwords, player limits
- **Network**: Network settings and rates
- **Gameplay**: Game rules and mechanics
- **Map**: Map rotation and game modes
- **Bots**: AI player configuration
- **Game Specific**: Game-specific settings

### 🎮 Supported Games
- **CS:GO**: Competitive settings, economy, rounds
- **CS2**: Modern Counter-Strike configuration
- **TF2**: Team balance, respawn times, tournament mode
- **CSS**: Classic Counter-Strike settings
- **DoD:S**: Class limits, round settings

### 💾 Export Options
- **Copy to Clipboard**: Quick copying
- **Save to File**: Export as .cfg file
- **Direct Upload**: Upload via FTP to server

## 🔧 Plugin Management

### 🔌 Metamod Updates
Access via: **Tools → Update Metamod**

**Features:**
- **Automatic Detection**: Detect current Metamod version
- **Version Selection**: Choose specific version to install
- **Backup Creation**: Automatic backup before update
- **FTP Integration**: Direct upload to server

### 📦 SourceMod Updates
Access via: **Tools → Update SourceMod**

**Features:**
- **Latest Builds**: Download latest stable/dev builds
- **Extension Management**: Handle SourceMod extensions
- **Plugin Compatibility**: Check plugin compatibility
- **Automated Installation**: One-click installation process

## 🌐 Network Diagnostics

### 🔍 Connection Analysis
Access via: **Tools → Network Diagnostics**

**Tools:**
- **Ping Test**: Measure server response time
- **Traceroute**: Trace network path to server
- **Port Scanner**: Check open ports
- **Bandwidth Test**: Measure connection speed
- **DNS Lookup**: Resolve hostnames

### 📊 Performance Monitoring
- **Real-time Graphs**: Visual network performance
- **Historical Data**: Track performance over time
- **Alert System**: Notifications for connection issues
- **Export Reports**: Generate diagnostic reports

## ⚙️ Settings & Configuration

### 🎨 Appearance
- **Themes**: Multiple color schemes
- **Font Size**: Adjustable text size
- **Window Layout**: Customizable interface
- **Transparency**: Window opacity settings

### 🔔 Notifications
- **Server Status**: Alerts for server changes
- **Player Alerts**: Notifications for specific players
- **Update Notifications**: Software update alerts
- **Sound Effects**: Audio notifications

### 📁 Data Management
- **Backup/Restore**: Save and restore settings
- **Import/Export**: Share server lists
- **Auto-Save**: Automatic configuration saving
- **Data Location**: `%LocalAppData%\LRSW\`

## 🆘 Troubleshooting

### ❌ Common Issues

**Server Not Responding:**
- Check server IP and port
- Verify firewall settings
- Test with Network Diagnostics

**RCON Connection Failed:**
- Verify RCON password
- Check if RCON is enabled on server
- Ensure correct port (usually 27015)

**FTP Connection Issues:**
- Verify credentials
- Check FTP server status
- Try different connection modes

### 📋 Log Files
- **Location**: `%LocalAppData%\LRSW\`
- **Main Log**: `LRSW.log`
- **Debug Log**: `debug.log`
- **FTP Log**: `ftp.log`

### 🔧 Reset Settings
1. Close LRSW completely
2. Delete folder: `%LocalAppData%\LRSW\`
3. Restart application

## 📞 Support

- **GitHub**: [Report Issues](https://github.com/lrsw/lrsw/issues)
- **Documentation**: [Wiki](https://github.com/lrsw/lrsw/wiki)
- **Community**: [Discord Server](https://discord.gg/aU9kCFKzH2)

---

# Deutsch

## 📋 Übersicht

Long Range Server Watcher (LRSW) ist eine leistungsstarke Anwendung zur Überwachung und Verwaltung von Spieleservern, die das Source Query Protocol unterstützen. Mit dieser Anwendung können Sie:

### 🚀 Hauptfunktionen
- 🔍 **Server-Browser**: Server aus Steams Master-Server-Liste suchen und entdecken
- ⭐ **Favoriten-Verwaltung**: Lieblings-Server speichern und organisieren
- 📊 **Echtzeit-Überwachung**: Live-Serverinformationen
- 👥 **Spielerlisten**: Aktuelle Spieler mit detaillierten Informationen anzeigen
- ⚙️ **Server-Regeln**: Server-Konfiguration anzeigen und analysieren
- 🎛️ **RCON-Konsole**: Remote-Server-Administration
- 🌐 **FTP-Client**: Integrierte Dateiverwaltung für Server-Dateien
- 📝 **Config-Generator**: Server-Konfigurationsdateien erstellen
- 🔧 **Plugin-Verwaltung**: Metamod und SourceMod Plugins aktualisieren
- 🌐 **Netzwerk-Diagnose**: Erweiterte Netzwerk-Fehlerbehebungstools

### 🎯 Unterstützte Spiele
- Counter-Strike: Global Offensive (CS:GO)
- Counter-Strike 2 (CS2)
- Counter-Strike: Source (CSS)
- Team Fortress 2 (TF2)
- Day of Defeat: Source (DoD:S)
- Half-Life 2: Deathmatch
- Garry's Mod
- Left 4 Dead 2
- Und viele weitere Source Engine Spiele

## 🛠️ Installation

### Methode 1: Installer (Empfohlen)
1. `LRSW-Setup-v2.0.0.exe` herunterladen
2. Installer als Administrator ausführen
3. Installationsassistent folgen
4. LRSW vom Startmenü oder Desktop starten

### Methode 2: Portabel
1. Alle Dateien in einen Ordner Ihrer Wahl extrahieren
2. `LRSW.exe` direkt ausführen
3. Keine Installation erforderlich

### 📋 Systemanforderungen
- Windows 10 (1809) oder neuer
- .NET 9.0 Runtime (im Installer enthalten)
- 100 MB freier Festplattenspeicher
- Internetverbindung für Server-Browsing

## 🖥️ Hauptfenster

### 📊 Serverliste
Zeigt Ihre gespeicherten Favoriten-Server mit:
- **Servername**: Benutzerdefinierter oder offizieller Servername
- **Karte**: Aktuell laufende Map
- **Spieler**: Aktuelle/Maximale Spieleranzahl
- **Ping**: Antwortzeit in Millisekunden
- **Tags**: Server-Tags und Spielmodus-Informationen

**Auswahl**: Klicken Sie auf einen Server, um ihn auszuwählen (blauer Rahmen)

### 👥 Spielerliste
Zeigt alle aktuellen Spieler auf dem ausgewählten Server:
- **Spielername**: In-Game Benutzername
- **Punkte**: Aktuelle Spielerpunkte/Frags
- **Dauer**: Verbindungszeit zum Server

**Auto-Update**: Aktualisiert sich automatisch bei Serverauswahl

### ⚙️ Regelliste
Zeigt Server-Konfigurationsregeln:
- **Regelname**: Name der Konfigurationsvariable
- **Wert**: Aktuelle Einstellung
- **Beschreibung**: Erklärung des Zwecks der Regel

## 🔍 Server-Browser

### 🌐 Global Games Fenster
Zugriff über: **Tools → Global Games**

**Funktionen:**
- Tausende von Servern aus Steams Master-Liste durchsuchen
- Nach Spiel, Map, Spieleranzahl filtern
- Echtzeit-Serverinformationen
- Server direkt zu Favoriten hinzufügen
- Ping-Messung und Sortierung

**Tabs:**
- **Global**: Alle verfügbaren Server
- **Favoriten**: Ihre gespeicherten Server
- **Kürzlich**: Kürzlich besuchte Server

### 🔧 Server-Verwaltung
- **Zu Favoriten hinzufügen**: Stern-Symbol oder "Zu Favoriten hinzufügen" Button klicken
- **Aus Favoriten entfernen**: Stern-Symbol deaktivieren
- **Server-Details**: Doppelklick für detaillierte Informationen
- **Direkt verbinden**: Rechtsklick für Spiel-Start-Optionen

## 🎛️ RCON-Konsole

### 🔐 Verbindungseinrichtung
1. Server aus Favoriten auswählen
2. **"RCON"** Button klicken
3. RCON-Passwort eingeben
4. **"Verbinden"** klicken

### 💻 Befehlsschnittstelle
- **Befehlseingabe**: Befehle in das untere Textfeld eingeben
- **Ausführen**: Enter drücken oder "Senden" klicken
- **Befehlshistorie**: Pfeiltasten für vorherige Befehle
- **Auto-Vervollständigung**: Tab-Vervollständigung für häufige Befehle

### 📋 Häufige Befehle
```
status              - Server-Status anzeigen
users               - Verbundene Spieler auflisten
changelevel <map>   - Aktuelle Map wechseln
kick <spieler>      - Spieler kicken
ban <spieler>       - Spieler bannen
say <nachricht>     - Nachricht an alle Spieler senden
```

## 🌐 FTP-Client

### 📁 Dateiverwaltung
Zugriff über: **Tools → FTP Client**

**Funktionen:**
- **Sichere Verbindung**: SFTP und FTP Unterstützung
- **Datei-Browser**: Server-Verzeichnisse navigieren
- **Upload/Download**: Dateien und Ordner übertragen
- **Berechtigungen**: Dateiberechtigungen ändern
- **Synchronisation**: Lokale und Remote-Dateien synchron halten

### 🔧 Verbindungseinrichtung
1. Server-Hostname/IP eingeben
2. Benutzername und Passwort angeben
3. Verbindungstyp auswählen (FTP/SFTP)
4. **"Verbinden"** klicken

## 📝 Config-Generator

### ⚙️ Server-Konfiguration
Zugriff über: **Tools → Config Generator**

**Tabs:**
- **Basic**: Servername, Passwörter, Spielerlimits
- **Network**: Netzwerkeinstellungen und Raten
- **Gameplay**: Spielregeln und Mechaniken
- **Map**: Map-Rotation und Spielmodi
- **Bots**: KI-Spieler-Konfiguration
- **Game Specific**: Spielspezifische Einstellungen

### 🎮 Unterstützte Spiele
- **CS:GO**: Competitive-Einstellungen, Wirtschaft, Runden
- **CS2**: Moderne Counter-Strike-Konfiguration
- **TF2**: Team-Balance, Respawn-Zeiten, Turnier-Modus
- **CSS**: Klassische Counter-Strike-Einstellungen
- **DoD:S**: Klassenlimits, Runden-Einstellungen

### 💾 Export-Optionen
- **In Zwischenablage kopieren**: Schnelles Kopieren
- **In Datei speichern**: Als .cfg-Datei exportieren
- **Direkter Upload**: Via FTP auf Server hochladen

## 🔧 Plugin-Verwaltung

### 🔌 Metamod-Updates
Zugriff über: **Tools → Update Metamod**

**Funktionen:**
- **Automatische Erkennung**: Aktuelle Metamod-Version erkennen
- **Versionsauswahl**: Spezifische Version zum Installieren wählen
- **Backup-Erstellung**: Automatisches Backup vor Update
- **FTP-Integration**: Direkter Upload auf Server

### 📦 SourceMod-Updates
Zugriff über: **Tools → Update SourceMod**

**Funktionen:**
- **Neueste Builds**: Neueste stabile/dev Builds herunterladen
- **Extension-Verwaltung**: SourceMod-Extensions verwalten
- **Plugin-Kompatibilität**: Plugin-Kompatibilität prüfen
- **Automatisierte Installation**: Ein-Klick-Installationsprozess

## 🌐 Netzwerk-Diagnose

### 🔍 Verbindungsanalyse
Zugriff über: **Tools → Network Diagnostics**

**Tools:**
- **Ping-Test**: Server-Antwortzeit messen
- **Traceroute**: Netzwerkpfad zum Server verfolgen
- **Port-Scanner**: Offene Ports prüfen
- **Bandbreiten-Test**: Verbindungsgeschwindigkeit messen
- **DNS-Lookup**: Hostnamen auflösen

### 📊 Performance-Überwachung
- **Echtzeit-Diagramme**: Visuelle Netzwerk-Performance
- **Historische Daten**: Performance über Zeit verfolgen
- **Alarm-System**: Benachrichtigungen bei Verbindungsproblemen
- **Export-Berichte**: Diagnose-Berichte generieren

## ⚙️ Einstellungen & Konfiguration

### 🎨 Erscheinungsbild
- **Themes**: Mehrere Farbschemata
- **Schriftgröße**: Anpassbare Textgröße
- **Fenster-Layout**: Anpassbare Benutzeroberfläche
- **Transparenz**: Fenster-Deckkraft-Einstellungen

### 🔔 Benachrichtigungen
- **Server-Status**: Alarme für Server-Änderungen
- **Spieler-Alarme**: Benachrichtigungen für bestimmte Spieler
- **Update-Benachrichtigungen**: Software-Update-Alarme
- **Soundeffekte**: Audio-Benachrichtigungen

### 📁 Datenverwaltung
- **Backup/Wiederherstellen**: Einstellungen sichern und wiederherstellen
- **Import/Export**: Serverlisten teilen
- **Auto-Speichern**: Automatisches Konfigurationsspeichern
- **Daten-Speicherort**: `%LocalAppData%\LRSW\`

## 🆘 Fehlerbehebung

### ❌ Häufige Probleme

**Server antwortet nicht:**
- Server-IP und Port prüfen
- Firewall-Einstellungen überprüfen
- Mit Netzwerk-Diagnose testen

**RCON-Verbindung fehlgeschlagen:**
- RCON-Passwort überprüfen
- Prüfen, ob RCON auf Server aktiviert ist
- Korrekten Port sicherstellen (meist 27015)

**FTP-Verbindungsprobleme:**
- Anmeldedaten überprüfen
- FTP-Server-Status prüfen
- Verschiedene Verbindungsmodi versuchen

### 📋 Log-Dateien
- **Speicherort**: `%LocalAppData%\LRSW\`
- **Haupt-Log**: `LRSW.log`
- **Debug-Log**: `debug.log`
- **FTP-Log**: `ftp.log`

### 🔧 Einstellungen zurücksetzen
1. LRSW vollständig schließen
2. Ordner löschen: `%LocalAppData%\LRSW\`
3. Anwendung neu starten

## 📞 Support

- **GitHub**: [Probleme melden](https://github.com/lrsw/lrsw/issues)
- **Dokumentation**: [Wiki](https://github.com/lrsw/lrsw/wiki)
- **Community**: [Discord Server](https://discord.gg/aU9kCFKzH2)

---

## 📄 License / Lizenz

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe die [LICENSE](LICENSE) Datei für Details.

## 🤝 Contributing / Mitwirken

Contributions are welcome! Please feel free to submit a Pull Request.

Beiträge sind willkommen! Bitte zögern Sie nicht, einen Pull Request zu erstellen.

## 📊 Version History / Versionshistorie

### v2.0.0 (Current/Aktuell)
- Complete UI redesign / Komplette UI-Neugestaltung
- Enhanced server browser / Verbesserter Server-Browser
- Integrated FTP client / Integrierter FTP-Client
- Config generator / Config-Generator
- Plugin management / Plugin-Verwaltung
- Network diagnostics / Netzwerk-Diagnose
- Improved stability / Verbesserte Stabilität

---

*© 2025 LRSW Development Team. All rights reserved.*

