path:3/pygame-community-bot-gen-2-0

# [Pygame Community Bot Generation 2.0: A revamped server bot for Pygame Community Discord](https://github.com/orgs/pygame-community/projects/3)

This page aims to document the current plans for the future version of Pygame Community Bot (often abbreviated as "PygameBot"), a bot used for managing and enhancing the Pygame Community Discord server.

## Overview
This project will be a complete rewrite of [`PygameCommunityBot`](https://github.com/pygame-community/PygameCommunityBot) that aims to address its predecessor's known problems and limitations by starting with a modular, guild-agnostic design from the ground up, paired with many quality-of-life server management features and cool abilites. The codebase will be separated into two main repositories, with [**`pcbheart`**](https://github.com/pygame-community/pcbheart) implementing functionality for Pygame Community Discord and [**`PygameBot`**](https://github.com/pygame-community/PygameBot) implementing utilites and commands related to running `pygame` code on Discord. 

## Planned features

### Within Servers
- **Rich Message/Embed Manipulation**
- **Channel & Thread Message Archiving**
- **Documentation Command with Custom Retrieval Workflow Support**
- **Polling & Voting System**
- **Command Rate-Limiting, Concurrency Limits, Cooldowns**
- **Reminders**
- **Slash Commands**
- **Flexible Command Override System (Alongside Discord's PermsV2)**

### Backend
- **SQLite DB support**

## Deprecations and removals
## Future roadmap
- **PostgreSQL DB backend**
- **Scheduled server interactions**
- **Sandboxed `pygame` code execution**

