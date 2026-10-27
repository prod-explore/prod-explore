Hi, I'm a backend and platform engineer from Katowice, Poland (Node.js, TypeScript), freelancing as Futumore since 2025.

I build AI infrastructure and run it myself: a gateway for local and cloud models, a sandboxed agent workspace and an Obsidian-to-MCP bridge, all on a Raspberry Pi homelab, next to a commercial booking app with 200+ users. So I look after the whole path, from `git push` to the container that serves it: Docker images built in CI for amd64 and arm64, nginx and HTTPS, rollbacks, backups.

Started coding at 9 (Scratch), then C++, then web stuff around 12. Got into security basics at 14 — Kali, HTB.

**Stack:** Node.js, TypeScript, Express, Fastify, React, SQLite, Docker, GitHub Actions, nginx.

## Public projects

All of them have CI on every push, and the READMEs say how to run them.

- 🧠 [**mindgate**](https://github.com/prod-explore/mindgate) — one OpenAI-compatible API in front of my own GPU machine (woken with Wake-on-LAN when a request needs it) and the cloud models I use. A key can be local-only, and a model is never swapped behind your back. Fastify + SQLite on a Raspberry Pi, 500+ tests.
- 🤖 [**everything-app**](https://github.com/prod-explore/everything-app) — self-hosted, bring-your-own-key AI workspace: multi-provider chat, a sandboxed code agent that can browse the web and work with Git, multi-agent delegation behind a cost guard. Over a thousand tests across six packages.
- 📓 [**OBSIDIAN-LIVESYNC**](https://github.com/prod-explore/OBSIDIAN-LIVESYNC) — an Obsidian vault that AI agents read and edit through MCP, kept in sync with Google Calendar and Tasks. Strict TypeScript; every path is checked against traversal and symlinks.
- 🧗 [**climbing-booking**](https://github.com/prod-explore/climbing-booking) — registration system for a climbing school, in production with 200+ users: class schedule, waiting list, instructor roles, passwordless login. Express + SQLite; the operator's and the venue's details are edited in the admin panel, not in the code.
- 🔀 [**nginx-reverse-proxy**](https://github.com/prod-explore/nginx-reverse-proxy) — one nginx with automatic HTTPS in front of any number of containers, each on its own network. The whole configuration is validated in CI.

Also built, in private repositories (happy to walk through them): **NEXTOUCH**, a remote desktop control app (Electron + React Native, C# for input injection, Stripe licensing with hardware ID binding), and **studio.hypnagogia**, an online shop for my own audio that syncs its catalog from YouTube.
