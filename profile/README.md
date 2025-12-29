# Media Flix

Media Flix is a **modern, self-hosted media platform** built for people who want the power of Plex, Emby, and Jellyfin without cloud lock-in, removed features, or artificial limitations.

It combines **one-click simplicity** with **deep customization**, advanced analytics, and a fully account-driven ecosystem that puts you in control of your media, your servers, and your data.

Media Flix is currently **early stage** and under active development.

---

## Why Media Flix Exists

Over time, existing media platforms have:
- Moved critical features behind the cloud
- Removed or restricted power-user functionality
- Made recovery and migration painful
- Fragmented analytics, lists, and reporting into third-party tools

Media Flix is being built to bring **everything back into one platform** - owned, hosted, and controlled by you.

---

## What Media Flix Delivers

Media Flix includes **everything you expect** from Plex, Emby, and Jellyfin, plus features that no longer exist elsewhere - and new ones that never did.

### Familiar Core Features
- Media libraries (Movies, Shows, Anime)
- Multi-user access and permissions
- Profiles and watch history
- Continue watching & progress tracking
- Client apps (web first, desktop & mobile planned)
- Hardware-accelerated playback
- Remote access support

### One-Click or Fully Custom - Your Choice
- **One-click hosting** like Plex (simple, fast, minimal setup)
- **Fully custom hosting** like Emby (advanced networking, paths, storage, access rules)
- Docker-first deployment
- Designed for NAS, home servers, and advanced setups

---

## Built-In Power Features (Not Add-Ons)

### Integrated Analytics (Tautulli-Class, Native)
- Full playback history
- Per-user and per-library stats
- Bandwidth, device, and quality reporting
- Server health and usage insights
- No external services required

### Skip Markers and Subtitles
- Automatic Intro and Credit markers
- add custom markers for things like (previously on)
- Share your markers with the community to use on their media
- Built in Subtitle service
- No external services required

### Lists & Discovery - Done Locally
- Create and manage lists directly inside Media Flix
- Import and sync lists from:
  - Trakt
  - IMDb
  - Other supported services (planned)
- Use lists for:
  - Libraries
  - Pins
  - Recommendations
  - Automated workflows

### Advanced Media Reporting
- Complete media inventory
- Missing, incomplete, and duplicate detection
- Quality and format reporting
- Watchers can create reports and will automatically attach the marker they stopped at or had issues
- Growth and usage trends over time
- Monitor content thats added and never watched with possibility to remove unused data

---

## Account-Centric by Design

Media Flix is built around **accounts**, not just servers.

Accounts allow you to:
- Link and manage multiple servers
- Restore configurations after reinstall or hardware failure
- Manage access and roles cleanly
- Keep your ecosystem intact even if the server changes

> Media files are never backed up — only configuration and platform data for easy restoration as per users choice.

---

## Self-Hosted First, Always

- Runs entirely on **your hardware**
- No required cloud dependency for playback
- No tracking
- No data resale
- No forced social features

You decide what connects out — and what doesn’t.

---

## Project Components

- **Media Flix Server**
  - Local media server
  - Library management, playback, users
  - Distributed via Docker

- **Web Interface**
  - React / Next.js (TypeScript)
  - Used for playback, dashboards, analytics, and management
  - Available locally and remotely

- **API**
  - Shared API for accounts, servers, metadata, and reporting
  - Used by web, desktop, and future mobile clients

  - **Metadata API**
  - Our own Metadata that acts like a Trakt, stores the metadata, subtitles, soundtracks, etc
  - More planned for this later

---

## Current Status

Media Flix is actively being built.

Current focus:
- Core server foundation
- Account and server linking
- UI/UX foundations
- Setup, restore, and migration flows
- Media analytics and reporting architecture

Expect rapid changes while foundations are finalized.

---

## Roadmap (High Level)

- Media Flix Server v0.0.0000189
- Guided setup (new install vs restore)
- Integrated analytics dashboard
- List creation & imports
- Permissions & roles
- Desktop and mobile clients

---

## Philosophy

Media Flix is built with a simple mindset:

- Software should not hold your data hostage
- Advanced features should not be removed over time
- Power users should not need 5 external tools
- Recovery should be painless
- Ownership matters
- No reliant on our servers. If ours is offline, yours still works.

This is software for people who run their own servers - and want them done right.

---

## Disclaimer

Media Flix does not provide content, host media, or condone piracy.

You are responsible for:
- Your media
- Your server
- Your usage

Media Flix is provided as-is while under development.

---

## Final Note

Media Flix is not trying to replace Plex, Emby, or Jellyfin overnight.

It is being built to **outgrow them** - thoughtfully, transparently, and without compromise.


## All features are available in the free version. Paid plans are optional and only required if you want our guided one-click setup (similar to Plex) and/or built-in backup tools.
