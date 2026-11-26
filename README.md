# Gabriel Parra

**I build things I use every day, then put them on GitHub.**

Software engineer (Business Systems Analyst II at UCF Global). My own projects are tools I wanted to exist: an Android app that runs my home lab, a diffusion engine in Rust, and a plugin and upstream fixes for the AI agent I work with. Python, Java and TypeScript are my daily languages.

Orlando, FL &nbsp;·&nbsp; English and Spanish &nbsp;·&nbsp; [gabrielparra.dev](https://gabrielparra.dev) &nbsp;·&nbsp; [gabpar49@gmail.com](mailto:gabpar49@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/gabeparra)

B.S. Computer Science, University of Central Florida (2026) &nbsp;·&nbsp; Ingeniería en Informática, Duoc UC, Santiago, Chile (2017)

---

### Skills

- **Languages:** Python, TypeScript, JavaScript, Java, C#, Kotlin, C++, SQL, Bash
- **Identity:** Keycloak, Entra ID, Active Directory, OAuth2 and OIDC, LDAP
- **Frameworks:** FastAPI, Flask, Node, React, Astro, Next.js, Jetpack Compose
- **Data and deployment:** PostgreSQL, MySQL, SQL Server, Docker, GitHub Actions, GHCR, nginx, systemd, Linux
- **Enterprise platforms:** PeopleSoft Campus Solutions, Slate, BPLogix, Respond.io
- **Game dev:** Unreal Engine 5 (C++), Unity 6 (C#, URP)

### Selected Projects

| Project | Description | Stack |
|---|---|---|
| [Control Center](https://github.com/gabeparra/control-center) | Android app I use to run my home lab from my phone: systemd services, Docker containers, logs, machine vitals, Wake-on-LAN, DNS and remote terminals. The public edition draws extensions that the server describes (no new app build needed) and ships with a one-command demo server using invented data. | Kotlin, Jetpack Compose, FastAPI |
| [rustyui](https://github.com/gabeparra/rustyui) | A diffusion engine I'm writing in Rust on candle. It speaks ComfyUI's API and gives ComfyUI's exact output: the same SDXL graph comes out as the same pixels. From a cold start it finishes an SDXL graph in about half to two thirds of ComfyUI's time and lets the GPU go when it's idle. Work in progress. | Rust, CUDA, candle, Vue 3 |
| [hermes-unity](https://github.com/gabeparra/hermes-unity) | Plugin that lets Hermes Agent work in the Unity 6 Editor through MCP for Unity: scenes, C# scripts, compile errors, play mode and screenshots. Runs untrusted and pinned to an exact release; the README documents an approval gap in batched tool calls. Also sent two upstream fixes to `NousResearch/hermes-agent` with tests ([PR #151953](https://github.com/NousResearch/hermes-agent/pull/151953), [PR #156635](https://github.com/NousResearch/hermes-agent/pull/156635)). | Python, MCP, Hermes Agent, Unity 6 |
| [ChessCadets](https://github.com/gabeparra/ChessCadets) | Senior design capstone: a kids' chess game in Unreal Engine 5 against an AI opponent built on the Pulse C++ chess engine. I integrated the engine, built the maps and fixed bugs (about 37% of the team's code). | Unreal Engine 5, C++ |
| [Portbook](https://github.com/gabeparra/portbook) | Local tracker for machines, the ports they serve, what connects to what, and the tickets against them. Draws its own connection map and flags port conflicts. One self-contained Python file with no dependencies: no server, no database, no login. | Python, Tailwind, http.server |
| [Rolling with the Punches](https://github.com/gabeparra/rolling-with-the-punches) | Western twin-stick shooter built by a course team in Unity 6. My parts were procedural map generation, the dash ability, bullet sound effects and the Android port (touch controls, three view modes, headless builds). | Unity 6, C#, URP, Android |

### More Projects

- **[Margot AI](https://github.com/gabeparra/Margot.AI)** (React, TypeScript, Flask, MongoDB, Docker): Bilingual word game for kids built by a team. Margot says a word in Spanish or English using ElevenLabs, and you type it in the language you're learning. I owned the MongoDB connection layer and worked across the Flask API and React client.
- **[DockerOffline](https://github.com/gabeparra/DockerOffline)** (Bash, Debian packaging): Offline install bundle for Docker Engine on Ubuntu hosts that never go online.
- **[Desktop Dancer](https://github.com/gabeparra/desktop-dancer-app)**: Puts a transparent dancer on your desktop, floating over your windows. Bring your own clip.

More at [gabrielparra.dev](https://gabrielparra.dev).
