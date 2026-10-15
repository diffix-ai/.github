## Diffix

**Autonomous Red Teaming, Enterprise Scale.**

An orchestrator deploys its specialists against your target, chains what they
find, and hands every candidate to a validator with no prior context. What
survives reaches you as a submission-ready report.

Diffix is built for live commercial penetration testing, red-team engagements
and bounty work on hardened targets.

### How it runs

One orchestrator holds engagement state and re-plans as findings land, rather
than running a fixed script. Seven squads sit under it, each agent narrow on
purpose with its own prompt, toolset and golden image:

| Squad | Covers |
|---|---|
| **Recon** | Attack surface, routes, auth boundaries, browser-native operation |
| **Analysis** | Dependencies, SCA/CVE, minified JS, secrets, prior disclosures |
| **Exploit** | Primitive construction, XSS, RCE, SSRF, API and business-logic abuse |
| **Coverage** | OWASP Top 10, WSTG conformance, mobile targets |
| **Chain** | ATT&CK mapping, kill chain, pivot graph, severity escalation |
| **Verify** | A validator with zero prior context |
| **Report** | Submission drafts in the programme's own field spine |

### The validator boundary

A system that validates its own findings will confirm its own hallucinations,
because the reasoning that produced a candidate is exactly the reasoning that
will rationalise it.

So the connection is severed. The validator receives the claim and the target.
It does not receive the transcript, the agent's reasoning, or the path that
produced the finding. It reproduces the bug cold, or the finding never ships.

### Controls

- **Authorization before autonomy.** No agent acts outside a signed engagement.
  Scope lives in the control plane and is checked at the tool boundary.
- **Tool output is data, never instruction.** Agents read attacker-controlled
  content all day. Nothing reaches a reasoning prompt without crossing a trust
  boundary.
- **Nothing asserted without evidence.** The reporter may only state what the
  evidence store holds, with a citation.
- **The last call is human.** Nothing is submitted to a programme without a
  person reading it first.

### Status

Diffix is an early research system. We are working with a small number of
researchers and security teams before general access.

No claim we cannot demonstrate. No finding we have not reproduced. No
engagement without signed scope.

---

**[diffix.ai](https://diffix.ai)** · briefings
[founders@diffix.ai](mailto:founders@diffix.ai) · responsible disclosure
[security@diffix.ai](mailto:security@diffix.ai)
