# Luci (beta)

**Luci learns how you work and live from your days, and you talk it through with Claude or ChatGPT.**

Luci sits quietly in your menu bar (Mac) or system tray (Windows). Over the days it learns your patterns: what you
work on, when you focus best, what you enjoy, what restores you. You ask it things in Claude or ChatGPT: where you
left off, what it has noticed about your days, how you work best.

Luci is invite-only for now. You need the invite code from your invitation.

## Download

| | |
|---|---|
| **Mac** (macOS 13 or later, Intel or Apple silicon) | [Download Luci.dmg](https://github.com/adrienschoi/luci-releases/releases/latest/download/Luci.dmg) |
| **Windows** (Windows 10 version 2004 or later, 64-bit) | [Download Luci-Windows-Setup.exe](https://github.com/adrienschoi/luci-releases/releases/download/windows/Luci-Windows-Setup.exe) |

## Get started

1. **Install it.**
   - Mac: open `Luci.dmg` and drag Luci to Applications, then open Luci.
   - Windows: open `Luci-Windows-Setup.exe`. The beta isn't signed yet, so Windows may say it protected your PC:
     choose **More info**, then **Run anyway**.
2. **Enter your invite code.** Then read what Luci collects and accept it, and allow the access it asks for.
   Use the **same code** on every computer you add: the code is your account, so a second computer or a reinstall
   joins the same Luci. Please don't share it.
3. **Talk with Luci in Claude or ChatGPT.** Add Luci as a custom connector, with this address:

   ```
   https://luci-hub.fly.dev/patterns/mcp
   ```

   - **Claude** (claude.ai or the Claude app): Settings → Connectors → Add custom connector.
   - **ChatGPT** (on the web, Plus or Pro): Settings → Apps & Connectors → Advanced settings → turn on
     Developer mode, then Create, with OAuth sign-in.

   When it asks you to sign in, enter the same invite code. Then write **@luci** in a chat.
   On a Mac with Claude Code, Luci also connects to Claude Code by itself.
4. **Optional, iPhone:** if your invitation has a TestFlight link, install Luci Sensor and scan the QR code Luci shows.

Luci needs a few days of your days before it has much to say.

## What Luci sees, and where it goes

Please read this before you install. Luci shows the full terms when you first open it.

- **On your computer:** the app, window title and website in front of you, when you are idle or typing (never what
  you type), and on a Mac, your calendar. With **Read the window in front** on, it also takes a snapshot of the
  window in front now and then.
- **Private things stay out.** It skips banking, password, health and messaging apps, private windows, and the apps
  and sites you tell it not to read. Passwords and other secrets are blacked out on your computer before a snapshot
  leaves it, and banking pages aren't sent at all.
- **Sent to the Luci server:** what Luci sees, so it can learn your patterns. Snapshots are turned into a short
  description and then thrown away. The descriptions and your answers are kept to improve Luci.
- **AI models:** the server uses Google's Gemini to describe snapshots and to look up things to do near you, and
  an open model hosted by DeepInfra in the US to find patterns.
- **Claude and ChatGPT** read only what you share with them: at first, what Luci counted in your days and the
  patterns you confirmed, with names replaced by what kind of thing they are, and no health details.
- **You stay in control:** **Pause Luci** stops all screen capture. You can turn reading the window off, and you can
  ask the Luci team to delete your data.

## Updates

Luci updates itself. On a Mac it asks before installing an update; on Windows it installs it the next time Luci
restarts. You can also download the newest version above at any time. Your account and settings stay.
