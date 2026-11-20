# Aegis 2 for Hermes: Leaner and Meaner

Aegis helps Hermes turn an idea into bounded work, tested changes, and reviewable
decisions. It scales ceremony to risk while keeping humans accountable for
consequential choices, rather than treating an agent's completion claim as proof.

## What you get

- One master specification, dependency-aware work packages, and inspectable evidence.
- A non-implementing PM coordinating bounded delivery and independent review.
- Risk-scaled gates covering scope, execution, acceptance, commit, deployment,
  and closeout; explicit owner authority remains required for runtime promotion
  and public release.
- Contract-first work, unchanged-check verification, SecOps privacy stops, and
  source-bound grounding controls.

This is a source-faithful Hermes port of [upstream Aegis](https://github.com/dotnetdavid/aegis).
It is guidance, not a sandbox, automated enforcement engine, model router, or
permission system. See [PORT-NOTES.md](PORT-NOTES.md) for provenance and exact changes.

## Install and invoke

Copy the **complete** `skill/aegis` folder to
`<active HERMES_HOME>/skills/software-development/aegis`, including every file
under `references/` and its full license. Resolve the active profile's Hermes
home first; do not assume another profile or host shares it. Deactivate any
superseded active Aegis copies only under explicit owner authorization, preserving
project records and source history outside discovery. This checkout does not
perform installation or replacement.

Windows and WSL are separate hosts. Start a fresh Hermes session after installing
or replacing the skill, in the intended project directory. Confirm the loaded
`aegis` source, actual working directory, and writable scope before writes.

```text
/aegis Help scope this project and choose the appropriate risk path.
```

Natural-language `Use Aegis` and `$aegis` also trigger the same skill. Upstream
`aegis2` and `$aegis2` are compatibility text triggers only: do not install a
second skill for them. Native skill commands and progressive reference loading
are described in the [Hermes skills documentation](https://hermes-agent.nousresearch.com/docs/user-guide/features/skills).

## Try the bounded calculator example

In an empty isolated project, use the [baseline prompt](examples/calculator/calculator-create.md).
After accepting it, use the [percent enhancement](examples/calculator/calculator-percent.md)
in that same project. The prompts retain the upstream offline calculator scope
and prohibit commit, deployment, and publication. They are examples, not executed
test reports. Review the [runtime mapping](skill/aegis/references/hermes-runtime.md)
for delegation, model-route limitations, and host safety boundaries.

## Verification and limits

Independent engineering and bounded SecOps/privacy reviews accepted the port.
Source-fidelity checks passed, and a fresh native Windows process exercised Hermes
skill discovery, all six reference loads, `/aegis` resolution, and invocation-payload
construction. The default-profile installation matches all seven reviewed skill
files byte-for-byte; only one Aegis skill remains in the configured discovery roots.
See [VERIFICATION.md](VERIFICATION.md) for evidence scope and limitations.

These checks do not establish a complete governed LLM conversation, calculator
execution, actual per-role model routing, Windows/WSL compatibility matrix,
accessibility certification, hard containment, or performance guarantees. Start a
fresh chat after replacement to discard earlier loaded instructions. Check actual
available tools and model routes before governed work.

## Creator and license

Created by David A. Frey. Copyright (c) 2026 David A. Frey.
[MIT License](LICENSE); the same full legal text travels with the distributed
skill in [references/LICENSE.md](skill/aegis/references/LICENSE.md).
