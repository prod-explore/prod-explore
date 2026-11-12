# Mikołaj Kajdan

Backend & full-stack developer · Node.js, TypeScript · AI integrations · Katowice, Poland

I build backend systems and run them in production myself. A booking system I wrote served a climbing
school's EU-funded programme (670 accounts, 750+ bookings), and on the same Raspberry Pi 5 I run
a self-hosted AI agent platform and an MCP server I use every day. Each app has its own Docker network
behind my TLS reverse proxy and ships through CI with automated tests. I build with AI coding agents
and own the architecture, code review and testing.

Looking for my first full-time developer role.

## Featured

### [EverythingApp](https://github.com/prod-explore/everything-app): self-hosted AI agent platform
The AI workspace I wanted and could not buy: any OpenAI-compatible model, a code agent with a Docker
sandbox per project, a browser it drives, Git through a proxy that keeps credentials out of the sandbox,
and an approval gate on every shell command. 5 containerised services, 1,300+ tests, 21 architecture
decision records. TypeScript, Node.js, React, Docker, MCP.

### [climbing-booking](https://github.com/prod-explore/climbing-booking): booking system in production · [live demo](https://cb-demo.futumore.pl/calendar)
Class sign-up for a climbing school, in production April–October 2026: 670 registered accounts,
750+ bookings. Waiting list with automatic promotion, sign-ups that cannot overbook under concurrency,
passwordless login, instructor and admin panels. Express, SQLite, 300+ tests.

## Also here
- [mindgate](https://github.com/prod-explore/mindgate): one OpenAI-compatible API in front of cloud
  models and my home GPU PC, which it wakes over Wake-on-LAN. Fastify, SQLite, 500+ tests.
- [OBSIDIAN-LIVESYNC](https://github.com/prod-explore/OBSIDIAN-LIVESYNC): MCP server that lets AI agents
  edit my Obsidian vault safely, with two-way Google Calendar and Tasks sync. 290+ tests.
- [nginx-reverse-proxy](https://github.com/prod-explore/nginx-reverse-proxy): the nginx in front of all
  of the above since September 2025: HTTPS, rate limits, no published app ports.

Every repository runs CI on each push and pull request and has a README that says how to run it.

**Stack:** Node.js · TypeScript · Express · Fastify · React · SQLite · Docker · GitHub Actions · nginx · Linux · Python

**Contact:** [LinkedIn](https://www.linkedin.com/in/mikolaj-kajdan)
