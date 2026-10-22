# AgentDock releases

Builds and the update feed for **AgentDock**, a macOS menu-bar app for the coding agents you run:
Claude Code, Codex, Grok and more, in any terminal or in their apps.

- A status strip on the edge of your screen: blue is working, amber needs you, green is done.
- An Inbox (⌃⌥I) to answer questions and reply to finished agents from the keyboard.
- A router (⌥⌥) to send a message to the right agent from any app.
- History, Activity and desktop widgets for what they did.

Download the latest DMG from [Releases](https://github.com/tvidenov/AgentDock-releases/releases),
open it and drag AgentDock to Applications, or `brew install --cask tvidenov/tap/agentdock`. Builds are
signed with Developer ID and notarized by Apple. AgentDock then keeps itself up to date through
`appcast.xml` in this repo (Sparkle).

Requires macOS 15 or later. $19 once after a 7-day free trial; the status dots stay free afterwards.
Nothing to set up for Claude Code and Codex; cmux is optional. Site: https://www.agentdockapp.com.
The source code is private.
