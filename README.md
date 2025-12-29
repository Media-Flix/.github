# Media Flix

Media Flix is a **self-hosted personal media platform** designed for people who want full control over their media servers, accounts, and data — without cloud lock-in, social noise, or opaque behavior.

It is inspired by platforms like Plex, Emby, and Jellyfin, but built with a **server-first**, **account-centric**, and **restore-friendly** architecture from the ground up.

This project is currently **early stage** and under active development.

---

## What Media Flix Is

Media Flix aims to provide:

- A **central account system** for managing one or more personal media servers
- A **local-first media server** that runs entirely on your hardware
- A clean, modern **web UI and apps** for browsing and watching content
- A setup and restore process that respects your time and configuration
- A long-term focus on **stability, transparency, and ownership**

Media Flix is **not a streaming service**, **not a social network**, and **not a content host**.

---

## What Media Flix Is Not

To avoid confusion:

- Media Flix does **not** host media files
- Media Flix does **not** provide or distribute content
- Media Flix does **not** include social feeds, discovery networks, or friend timelines
- Media Flix does **not** back up your media itself

You bring your own media. You control your servers.  
Media Flix is just the software.

---

## Core Design Principles

### Self-Hosted First
Your Media Flix server runs on **your hardware** (Docker, Linux, NAS, etc.).  
No mandatory cloud dependencies for playback or library access.

### Account-Centric
Accounts are used to:
- Link servers
- Manage access
- Restore configurations
- Handle permissions and roles

Accounts are **not** used for social features or content sharing networks.

### Reinstall & Recovery Friendly
Media Flix is designed so that if you:
- Reinstall the server
- Migrate to new hardware
- Reclaim a lost system

You can restore **settings, configuration, and relationships** without re-doing everything manually.

> Media files themselves are never backed up by Media Flix.

### No Forced Discovery
There is no server discovery feed, global server list, or social graph.
If someone has access to your server, it is because **you gave it to them**.

---

## Project Structure

The Media Flix ecosystem is split into several parts:

- **Media Flix Server**
  - Runs locally on your machine
  - Handles libraries, scanning, playback, and users
  - Distributed via Docker

- **Web UI**
  - React / Next.js (TypeScript)
  - Used for accounts, dashboards, and server management
  - Also accessible locally on the server

- **API**
  - Shared API for accounts, servers, and metadata
  - Used by web, desktop, and future native clients

- **Clients**
  - Web
  - Desktop (planned)
  - Mobile (planned)

---

## Current Status

Media Flix is currently in **active development**.

Focus areas right now:
- UI/UX foundations
- Account system architecture
- Server setup & linking
- Dockerized server base
- Configuration and restore flows

This repository reflects **real development**, not a polished product.

Expect:
- Breaking changes
- Incomplete features
- Rough edges

---

## Roadmap (High Level)

Planned milestones include:

- Initial Media Flix Server container
- Guided setup UI (new install vs restore)
- Account + server linking
- Library management
- Playback foundations
- Permissions & roles
- Desktop and mobile clients

A more detailed roadmap will live in `/roadmap`.

---

## Transparency & Philosophy

Media Flix is built as a **hobby project in the open**.

- No hidden tracking
- No analytics by default
- No selling user data
- No dark patterns

Decisions are made with long-term maintainability in mind, not growth metrics.

---

## Contributing

Contributions are welcome once the core architecture stabilizes.

Until then:
- Issues may be closed quickly if they conflict with project direction
- Feature requests should align with the stated goals
- Social or discovery features are out of scope

More contribution guidelines will be added later.

---

## License

License information will be added once the core project structure stabilizes.

---

## Disclaimer

Media Flix is provided **as-is**, without warranty.

You are responsible for:
- Your media
- Your server
- Your usage

Media Flix does not condone or facilitate piracy or copyright infringement.

---

## Final Notes

Media Flix exists because existing solutions either:
- Hide too much behind the cloud
- Make recovery painful
- Add unnecessary social features
- Or stop evolving in meaningful ways

This project is about **ownership**, **clarity**, and **control**.

Nothing more.
Nothing less.
