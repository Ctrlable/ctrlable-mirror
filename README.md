# Ctrlable Mirror

**Link fixtures together so they follow each other.** Ctrlable Mirror keeps two
or more entities in sync — brightness, color, color temperature, position,
volume, on/off and more — with a friendly point-and-click panel. Built for
**Ctrlable Pro**.

> This is the distribution repository consumed by HACS. Sources are maintained
> privately; the published build ships the licensing/engine modules as native
> `abi3` extensions.

## What it does

- **Bidirectional links** — change either fixture and the other follows.
- **One-way mirror** — a target follows a source, but not the reverse.
- **One-to-many** — one source drives many targets at once.
- **Pick exactly what to mirror** — tick only Brightness + Color, or just Color
  Temperature, or On/Off, per link. Works across lights, fans, covers, climate,
  media players and more.
- **Guided picker** — browse entities by area, **grouped and filterable by
  integration** (find your Lutron phantom loads in a couple of clicks), with a
  search box and inline help.
- **Loop-safe** — bidirectional links won't ping-pong.

## Requirements

- Ctrlable Pro / Home Assistant `2024.12.0` or newer.
- A **Ctrlable Mirror license** (issued from the Ctrlable portal or the Ctrlable
  Store). Paste it into the Mirror panel to activate.

## Install

1. Install via HACS (this repository) or the **Ctrlable Store**.
2. Add the **Ctrlable Mirror** integration.
3. Open **Mirror** in the sidebar, paste your license key, and create your first
   link.

## Support

Issues: https://github.com/Ctrlable/ctrlable-mirror/issues
