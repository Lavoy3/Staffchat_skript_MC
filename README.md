# Staff Chat — Skript Edition

A tiny, dependency-free **/sc** staff-chat channel for servers running the **Skript** plugin.  
Messages sent with `/sc` are visible only to players with the configurable permission node.

---

## ✨ Features

| Feature                     | Description                                               |
|-----------------------------|-----------------------------------------------------------|
| **/sc &lt;message&gt;**     | Sends a coloured message to all online staff members      |
| **Prefix & colouring**      | Customisable prefix and colour codes                      |
| **Permission-gated**        | Only players with the permission node send/receive staff chat |
| **Legacy-safe colours**     | Manually replaces `&` with `§` so it works on any Skript version |
| **Zero addons**             | Works on vanilla Skript — no extras required              |

---

## 📂 Installation

1. **Install Skript** (≥ 2.6) on your Spigot/Paper server.  
2. Drop `staffchat.sk` into `plugins/Skript/scripts/`.  
3. Run `/skript reload staffchat` from console or in-game.

---

## ⚙️ Configuration

Edit the **`options`** block at the top of the script:

```skript
options:
    staff-prefix: "&8[&bStaff&8]&r "  # Shown before every staff message
    staff-permission: "staffchat.use" # Node required to send/receive
