## Johan Jagalur

B.S. Computer Science (Cybersecurity) at Arizona State University, expected May 2028.
I build full-stack web applications and I break them on purpose.

Looking for **Summer 2027 software engineering internships** — full-stack, backend, or application security.

---

### What I'm working on

**Ksana** — Event operations platform (private, client-owned)
Lead developer on a cashless event platform: 9 PostgreSQL/Prisma models, 38 API routes, 16 front-end routes.
I wrote the authentication layer from scratch — stateless HttpOnly session cookies signed with HMAC-SHA256
and compared using `timingSafeEqual`, bcrypt credential hashing, hashed and rate-limited API keys, and three
roles enforced on every protected route. 94 test cases across 21 files, plus an OpenAPI contract check that
fails the build when routes drift from the spec. Deployed as an AWS Amplify front end against a venue-local
backend, exposing only the API through a Cloudflare Tunnel so PostgreSQL never touches the internet.
Validated in a supervised pilot with roughly 100 attendees. Source is private at the client's request.

**[Startup Village](https://github.com/JohanFJ101/Svwebsite)** — [startupvillage.xyz](https://startupvillage.xyz)
Sole developer of the site for a 500+ member ASU organization. React, TypeScript, Vite, with Vercel
serverless endpoints for session-based admin login and a content API that lets officers update event pages
without touching code. Also ran technical logistics for a 300+ registration hackathon.

**[DispatchIQ](https://github.com/JohanFJ101/dispatchiq)** — Fleet dispatch dashboard
React 19, TypeScript, Vite, Zustand. Live fleet synchronization through the NavPro API, plus a dispatch
copilot running on a local Ollama model so operational data stays on the machine instead of going to a
third-party API.

---

### Security

Completed **259/259 challenge points** in the web security module of ASU's CSE 365 (pwn.college): path
traversal, command injection, authentication bypass, SQL injection, XSS, and CSRF, reasoning about the
Same-Origin Policy and session handling along the way. Earlier modules covered Linux permissions, SUID
privilege escalation, and PATH hijacking. Also completed the TryHackMe Pre-Security path.

No solutions posted here — pwn.college asks that challenge writeups stay off the internet, and I agreed to that.

I also run a headless Debian server for my own projects: root SSH login disabled, systemd units, firewall
and file-permission hardening, and Tailscale-only access with no public exposure.

---

### Also here

- **[neetcode-submissions](https://github.com/JohanFJ101/neetcode-submissions)** — 139 Python solutions. Data structures and algorithms is CSE 310, where I earned an A+ with full marks on all four C++/Linux projects.
- **[CodexMCP](https://github.com/JohanFJ101/CodexMCP)** — A small MCP server exposing a `query_offload` tool, so an agent can hand mechanical work to a cheaper model and keep reasoning in context.
- **[TrueTrace](https://devpost.com/software/truetrace)** — Hackathon project: a multi-agent misinformation checker that returns a verdict with cited evidence. Repository lost; Devpost writeup survives.

---

### Stack

**Languages** TypeScript, Python, C++, Java, SQL, Bash
**Web** Next.js, React, Node.js, Vite, Tailwind CSS
**Data** PostgreSQL, Prisma ORM, REST, OpenAPI 3.1
**Systems** Debian Linux, SSH, systemd, Tailscale, Cloudflare Tunnel, AWS Amplify, Vercel, Git

---

Tempe, Arizona · [LinkedIn](https://linkedin.com/in/johan-jagalur-8907822b9) · johanjagalurf@gmail.com
