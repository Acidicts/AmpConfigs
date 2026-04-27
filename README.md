# AmpConfigs

Community AMP Panel configuration templates for game servers.

## Available Configurations

### WaterdogPE

AMP Panel configuration for [WaterdogPE](https://waterdog.dev) — a Minecraft: Bedrock Edition proxy server.

**Files:**
- `waterdog.kvp` — Main AMP configuration
- `waterdogconfig.json` — AMP settings UI (Java version, memory)
- `waterdogports.json` — Port definitions (UDP 19132 default)
- `waterdogupdates.json` — Update sources (downloads from GitHub releases + Eclipse Temurin Java)

**Requirements:**
- Java 17 or newer (automatically downloaded during update)
- AMP version 2.4.3.2 or newer

**After installation:**
1. Run **Update** in AMP to download WaterdogPE and Java.
2. Edit `config.yml` in the instance directory to configure servers, MOTD, and ensure `listener.host` uses the port assigned by AMP (default: `0.0.0.0:19132`).
3. Start the server.

**Default port:** UDP 19132
