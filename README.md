# AgentDock releases

Builds and the update feed for **AgentDock**, a macOS menu-bar companion for the coding agents
you run in [cmux](https://cmux.com):

- A status strip on the edge of your screen: blue is working, amber needs you, green is done.
- An Inbox (⌃⌥I) to answer questions and reply to finished agents from the keyboard.
- A router (⌥⌥) to send a request to the right agent.

Download the latest DMG from [Releases](https://github.com/tvidenov/AgentDock-releases/releases),
open it and drag AgentDock to Applications. Builds are signed with Developer ID and notarized by
Apple. AgentDock then keeps itself up to date through `appcast.xml` in this repo (Sparkle).

Requires macOS 26 and cmux, with Settings › Automation › Socket Control Mode set to **Password**.
The source code is private.
