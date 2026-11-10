# Luci for Mac

**A personal assistant that learns how you work and live, then suggests what would make your day better.**

Luci runs quietly in your menu bar. Over the days it learns your patterns: what you work on, when you focus best,
what you enjoy. Each morning it offers a few suggestions made for you. You decide which ones to take, and Claude
can do the ones that need doing.

Luci is invite-only for now. You'll need the code from your invitation.

## What Luci does

- **Today:** when you first sit down at your Mac, Luci shows a few suggestions for your day: moving a project
  forward, a real break, something you'd enjoy, an evening out. Each one says why it fits you. Put it in your
  calendar, hand it to Claude, tell Luci what you'd change, or set it aside.
- **Patterns:** what Luci has learned about you, in plain words. Tap *That's me* or *Not me*, and every suggestion
  after that takes your answer into account.
- **Skills:** when one of your habits keeps coming round, Luci offers to help with it each time (for example,
  collecting ideas from the videos you watch into a doc). You edit or turn down each skill, and it never runs
  without your yes.
- **Days:** a timeline of each day, with your work blocks, which Luci notices by itself and adds to your calendar.

Luci never sends anything or changes your files itself. When you hand something to Claude, it opens in your own
Claude app on your Mac, and you see the work there.

## What Luci sees, and where it goes

Luci only works if it can see what you do, so please read this before you install.

- **On your Mac:** the app, window title and website in front of you, and your calendar. With *screen
  understanding* on, it also takes a snapshot of the window in front now and then.
- **It never records what you type.** It skips the apps and sites on your *Never read* list. Passwords and other
  secrets are blacked out on your Mac before a snapshot leaves it, and banking pages aren't sent at all.
- **Sent to the Luci server:** what Luci sees, so it can learn your patterns and draft your suggestions. Snapshots
  are turned into a short description and then thrown away. The descriptions and your answers are kept to improve
  Luci.
- **AI models:** the server uses Google's Gemini to describe snapshots and to look up things to do near you, and
  an open model hosted by DeepInfra in the US to find patterns and write suggestions.
- **You stay in control:** *Pause Luci* in the menu bar stops all screen capture. You can turn screen understanding
  off, and you can ask the Luci team to delete your data.

When you first open Luci, it shows the full terms, and you accept them before anything is sent.

## Install

1. Download **Luci-x.y.z.dmg** from the [latest release](https://github.com/adrienschoi/luci-releases/releases/latest)
   (under *Assets*).
2. Drag **Luci** to **Applications**, open it, and enter your invite code.
3. Allow the permissions it asks for.

Requires macOS 13 Ventura or later. Works on Intel and Apple silicon Macs.

## Updates

Luci checks for updates by itself and asks before installing one. You can also download the newest DMG at any time
and replace the copy in Applications. Your history and settings stay.
