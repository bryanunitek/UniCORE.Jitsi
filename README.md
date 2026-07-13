# UniCORE.Jitsi

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 14:50 UTC.**

---

## What this repository is

`bryanunitek/UniCORE.Jitsi` is the **Jitsi** family member: On-prem-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source video conferencing platform. Multi-upstream: Jitsi Meet (application) + Jitsi Videobridge (SFU).

**Role in UniCORE:** Video conferencing substrate — UniCORE.GVB substrate-services consume Jitsi to deliver browser-based video meetings on UniCORE-deployed nodes, with NGINX-based regional load-balancing across the multi-node fleet.

---

## Upstream

- **Upstream projects:** [jitsi-meet](https://github.com/jitsi/jitsi-meet) + [jitsi-videobridge](https://github.com/jitsi/jitsi-videobridge)
- **Upstream licence:** Apache-2.0
- **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our additions sit on top under CC BY 4.0.

This repository tracks multiple upstreams via separate remotes (`upstream-meet` + `upstream-videobridge`). The merge discipline that governs how this repository absorbs upstream changes is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md).

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

UniCORE.Jitsi is published as a **four-repo family**:

- `bryanunitek/UniCORE.Jitsi` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Jitsi` — public SaaS-deployment-shape gift surface
- `bryanunitek/UniCORE.Jitsi-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Jitsi-Claw` (private) — SaaS-shape working repository

**This repository is the `UniCORE.Jitsi` member of the family.**

Sister repos:

- [`UniSaaS.UniCORE.Jitsi`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Jitsi) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Jitsi))
- `UniCORE.Jitsi-Claw (private)`
- `UniSaaS.UniCORE.Jitsi-Claw (private)`

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04 14:50 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown.

---

## Files in this scaffold commit

- [`README.md`](README.md) — this file
- [`LICENSE.md`](LICENSE.md) — CC BY 4.0 for UniCORE additions
- [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim upstream Apache-2.0 licence
- [`README.upstream.md`](README.upstream.md) — verbatim upstream README (renamed)
- [`STATUS.md`](STATUS.md) — scaffold-anchor status
- [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline
- [`AI-AUTHORSHIP.md`](AI-AUTHORSHIP.md) — AI authorship disclosure

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://git.unitek-systems.com/UniCORE/UniVERSE) (mirror: [GitHub](https://github.com/bryanunitek/UniVERSE)) — programme
- [`TrueAI`](https://git.unitek-systems.com/UniCORE/TrueAI) (mirror: [GitHub](https://github.com/bryanunitek/TrueAI)) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://git.unitek-systems.com/UniCORE/UniCORE-AI) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE-AI)) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://git.unitek-systems.com/UniCORE/UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE)) — on-prem-shape
- [`UniSaaS.UniCORE`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE)) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.GVB)) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB)) — SaaS-shape

**Forked-upstream building blocks:**
- UniCORE.Avalonia family (4 repos) — cross-platform UI
- UniCORE.DNN family (4 repos) — CMS platform
- UniCORE.Asterisk family (4 repos) — telephony
- UniCORE.Jitsi family (4 repos) — video conferencing ← **this family**
- UniCORE.Signal family (4 repos) — secure messaging
- UniCORE.XCP family (4 repos) — virtualisation

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE.Jitsi/discussions) (public repos only)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
