# AgentPing

Sound alerts and desktop notifications when your AI finishes generating.

## The Problem

You send a prompt, switch to another tab, and forget to check back. Minutes pass. The AI finished ages ago.

AgentPing watches your AI tabs and pings you the moment they're done.

## Install

Get it from the [Chrome Web Store](#) (link coming soon).

Built for supported Chromium-based browsers.

## Features

**Alerts**
- 5 notification sounds (Gentle Chime, Three-Note, Warm Bell, Soft Hum, Sharp Ping)
- Desktop notifications with platform name and tab title
- Sound escalation if you don't respond
- Phone push notifications via [ntfy.sh](https://ntfy.sh) (free, no account needed)

**Detection**
- Knows when AI starts and finishes generating
- Works across multiple tabs at once
- Draggable floating bell button on each AI tab
- Click the bell or press Escape to dismiss

**Privacy**
- No analytics, no tracking, no developer servers.
- All settings stored locally on your device.
- Processes only the local page signals needed to detect when a response finishes.
- [Privacy Policy](privacy-policy.html)

## How to Use

1. Install the extension
2. Refresh any open AI tabs (or open new ones)
3. The red bell button appears in the corner of each AI tab
4. Send a prompt and switch away — AgentPing alerts you when the AI finishes

**Customize in the popup:**
- Toggle platforms on/off
- Pick your notification sound and volume
- Enable phone alerts for when your screen is off

## Phone Alerts

For notifications when your screen is off or computer is asleep:

1. Install the [ntfy app](https://ntfy.sh) on your phone
2. Subscribe to a topic name (e.g., `my-agentping-alerts`)
3. Enter the same topic name in AgentPing's popup
4. Test it with the "Test Phone Alert" button

Free, no account needed. The notification contains only the platform name and a generic completion notice.

## Report a Bug

Something not working? [Open an issue](https://github.com/AkashiGhost/agentping/issues).

Include:
- Which AI platform
- What happened vs. what you expected
- Your browser and version

## License

Copyright 2026. All rights reserved.
Source code is not included in this repository.
