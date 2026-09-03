<div align="center">
  <img src="./assets/banner.svg" alt="Arav Madan — infrastructure for AI agents" width="100%" />
</div>

<div align="center">
  <code>third year @ TU/e</code> &nbsp;·&nbsp;
  <code>eindhoven</code> &nbsp;·&nbsp;
  <code>agent infrastructure</code>
</div>

---

I build the infrastructure around AI agents — the parts that measure whether they work,
and contain them when they don't.

### Building

**[Parkbench](https://github.com/aravmdn/parkbench)** — a benchmark arena for AI agents, built as
a theme park: each ride is a self-contained, scored test of one capability. Seven rides across four
axes — social, economic, coding, safety. The negotiation and exchange rides grade against a provable
optimum rather than a rubric, so a score means something outside its own scale.

Ships an HTTP/JSON server so external agents can be scored over the wire, a static replay viewer, and
an LLM reference agent. Every score is seed-reproducible and byte-identical across runs, processes and
operating systems — enforced by determinism and fixture-provenance tests, not by convention.

`Python, zero runtime dependencies` &nbsp;·&nbsp; `440 tests` &nbsp;·&nbsp; `75 decision records` &nbsp;·&nbsp; `in active development`

### In production

**[Pitchr](https://pitchr.live)** — AI pitch coaching for founders. Live recording and transcription,
async analysis runs, structured scoring and rewrites. Built at HackEurope 2026 and kept going
afterwards, through billing and launch hardening.

Second-largest of four contributors, on the analysis pipeline and model routing.

`Next.js` &nbsp;·&nbsp; `Supabase` &nbsp;·&nbsp; `MIT` &nbsp;·&nbsp; `live`

### Also built

**[Rampart](https://github.com/aravmdn/rampart)** — AI coding agents run under enforced least
privilege: Windows Job Objects for process containment, Low-Integrity filesystem restriction, and
per-app-ID WFP outbound filters. Blocks fire at the OS level, and every blocked action comes back with
an explanation instead of a silent failure.
`Rust + Tauri` &nbsp;·&nbsp; `Apache-2.0`

**[CollabBoards](https://github.com/aravmdn/CollabBoards)** — real-time boards over Socket.IO with
JWT access/refresh auth and a DB-backed integration suite. Shipped and deployed.
`TypeScript` &nbsp;·&nbsp; `Prisma + PostgreSQL` &nbsp;·&nbsp; `MIT`

**[CBL](https://github.com/aravmdn/CBL)** — a live installation where a singing bowl's pitch and a
person's heartbeat drive the visuals. GPU-side in TouchDesigner and GLSL, running standalone on one
laptop.
`TouchDesigner` &nbsp;·&nbsp; `GLSL` &nbsp;·&nbsp; `Arduino`

### Stack

`Python` &nbsp;·&nbsp; `TypeScript` &nbsp;·&nbsp; `Rust` &nbsp;·&nbsp; `Next.js` &nbsp;·&nbsp; `React`
&nbsp;·&nbsp; `Supabase` &nbsp;·&nbsp; `PostgreSQL` &nbsp;·&nbsp; `Tauri` &nbsp;·&nbsp; `TouchDesigner`

### Elsewhere

Zed Campus Ambassador, first cohort · [LinkedIn](https://www.linkedin.com/in/aravmadan/)
