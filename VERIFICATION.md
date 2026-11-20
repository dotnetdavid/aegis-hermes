# Verification Record

## Scope and provenance

- Verification date: November 19, 2026, native Windows Hermes host.
- Sole governance source: `dotnetdavid/aegis` commit `4699791576c03d91e92af6ef3ec91a26a214f301`.
- Deliverable: one Hermes skill named `aegis`, with source-preserving references, a host adapter, legal notices and adapted example prompts.
- Authorization: explicit user instructions cover conversion and replacement, followed by pushing the ready Hermes version to `dotnetdavid/aegis-hermes`.
- The existing destination was verified as private, empty, and writable before publication. No visibility change, release tag, CI workflow or hosted service is part of this work.

## Observed checks

| Check | Observed result |
| --- | --- |
| Independent engineering review | Accepted source fidelity and structural Hermes operability; no blocking port-introduced contradiction. |
| Independent SecOps/privacy review | Accepted the original authored-content snapshot; no evidence-backed blocker. Full-file manual review plus bounded pattern, path, link, symlink/reparse-point and hidden-control checks. This is not a certification that no PII exists. |
| Source fidelity | Reversing only host introduction, activation and Runtime-section changes recovers the upstream SKILL body after newline normalization. All four upstream references and both full license copies match source bytes. |
| Calculator prompt differences | Only host/invocation wording changed; no calculator execution claimed. |
| Hermes metadata and packaging | Parsed YAML, canonical name, description length, references and local links checked. No executable product code, installer or Codex UI configuration added. |
| Built-in Hermes security scan | `safe`; six low informational `AGENTS.md` references, not a zero-findings claim. |
| Fresh-process native discovery | Exactly one Aegis catalog entry; readiness `available`. |
| Progressive reference loading | All six references successfully loaded through native `skill_view`. |
| Native command machinery | `/aegis` resolves and builds an invocation payload containing the new skill and requested instruction; obsolete `/aegis2` command absent. |
| Installed-file identity | All seven installed files match the reviewed source bytes and SHA-256 values below. The first post-write comparison detected Windows newline conversion; exact-byte copies corrected it before the passing comparison. |
| Previous versions | Previous default-profile Aegis body replaced; archived Aegis preflight companion removed. Only one Aegis SKILL remains in configured discovery roots. Historical project records, unrelated skills and other profiles/hosts were preserved. |

The independent reviews covered the original conversion snapshot. Final root-documentation changes report observed outcomes only; they do not change the reviewed skill, policies, references or examples.

## Reviewed source and installed-file SHA-256

| Skill-relative path | SHA-256 |
| --- | --- |
| `SKILL.md` | `666e131dde5c8ae563e0e9b7463e421f24e21f0f7d3a574d8ebd673a35bdf71c` |
| `references/artifact-templates.md` | `c6d730490df4bbccd8b79e53d3c57ab68320877c13d12162fce6e5d888acf802` |
| `references/grounding-governance.md` | `26d27f60a804c34606509805a96fba582ac8a440c56a8546b66972e78fb59903` |
| `references/hermes-runtime.md` | `15641dddcefc5a17de46195cc76b5b9378d24d2aea6758e7a526402ddb56522b` |
| `references/LICENSE.md` | `800621801de3396cd7b605c28d477f61456203b547b87b8eddfdd1e651b3c08e` |
| `references/lifecycle-gates.md` | `99acb33a06fd19611f00b1211ad531cbd982153b21906ae1b5e8caeb8a8e187f` |
| `references/project-policy.md` | `cb2f28bc8b9feb77990c09c868febefc1625e6e41b2f76b498788b71372f4591` |

## Known inherited issue

The upstream release-record template has a malformed deployment-authorization placeholder in `references/artifact-templates.md`. It is retained unchanged for exact source fidelity. The surrounding policy still expressly requires owner authorization before deployment; the typo does not grant authority or weaken that boundary.

## Limits

Native loader and command expansion were exercised in a new Python process, not a fresh end-to-end LLM conversation. No complete governed project, calculator run, Windows/WSL matrix, actual per-role model routing, accessibility assessment, performance benchmark or hard-containment test was performed. Independent review of a document package is not proof that future agents will follow it. Start a fresh Hermes chat after replacement to discard previously loaded instructions.

Remote commit identity and repository visibility are checked after pushing; this pre-publication record does not fabricate a future successful push.
