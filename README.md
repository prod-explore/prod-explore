I'm Mikołaj, a backend developer from Katowice, Poland, working in Node.js and TypeScript.

Most of what I build starts as a problem of my own. I write the tool, then run it myself on a Raspberry Pi 5 at home, behind my own reverse proxy. The one thing here built for someone else is the booking system of my family's climbing school, in production from April to October 2026, the whole run of an EU-funded programme of free classes.

I started as a kid with Scratch, Minecraft redstone and an after-school web class, then spent a few years producing music. I came back to programming in September 2025 to build a store for my own beats, and have been building since.

**Stack:** Node.js, TypeScript, Express, Fastify, React, SQLite, Docker, GitHub Actions, nginx, Linux.

## Projects

Every repository has CI on every push and a README that says how to run it.

- [**climbing-booking**](https://github.com/prod-explore/climbing-booking): class sign-up for my family's climbing school. 670 registered accounts and 750+ bookings. Waiting list with automatic promotion, passwordless login, instructor and admin panels. Express, SQLite, 270+ tests. [Live demo](https://cb-demo.futumore.pl/calendar).
- [**mindgate**](https://github.com/prod-explore/mindgate): I wanted to use the models on my desktop PC from anywhere. It became one OpenAI-compatible API in front of that PC, which it wakes with Wake-on-LAN and lets sleep when idle, and the cloud models I use. Per-app keys, budgets and a local-only flag. Fastify, SQLite, 500+ tests.
- [**everything-app**](https://github.com/prod-explore/everything-app): the AI workspace I wanted and could not buy. Any model through one API, a code agent in a Docker sandbox per project, a browser it drives, Git through a proxy that keeps credentials out of the sandbox, and an approval gate on every shell command. 1,300+ tests.
- [**OBSIDIAN-LIVESYNC**](https://github.com/prod-explore/OBSIDIAN-LIVESYNC): my Obsidian vault is where I plan everything, so AI agents read and edit it through MCP and it stays in sync with Google Calendar and Tasks. Paths are checked against traversal and symlinks; nothing is ever permanently deleted. In daily use.
- [**nginx-reverse-proxy**](https://github.com/prod-explore/nginx-reverse-proxy): the nginx in front of all of the above since September 2025. HTTPS, per-client rate limits, each app on its own Docker network with no published ports.

## Contact

[LinkedIn](https://www.linkedin.com/in/mikolaj-kajdan)
