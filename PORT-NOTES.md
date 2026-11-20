# Hermes Port Notes

## Source boundary

Only governance source: https://github.com/dotnetdavid/aegis at commit
`4699791576c03d91e92af6ef3ec91a26a214f301`.
The clean local source checkout was verified at that identity before conversion.
The port uses `skill/aegis2/SKILL.md`, all four reference guides, root LICENSE,
and both calculator prompt files; upstream README, RELEASE-NOTES, and
`agents/openai.yaml` were read for packaging context. No older Hermes Aegis
content was used. The initial conversion did not change the existing skill;
verified default-profile replacement occurred afterward in the parent workflow.

## Exact host-only adaptations

1. Package directory and canonical skill name: `skill/aegis2` -> `skill/aegis`;
   frontmatter `name: aegis`. Keep upstream heading **Aegis 2: Leaner and Meaner**.
2. Replace Codex-specific introductory wording with Hermes-specific wording.
   Keep the remainder of upstream SKILL body, changing only activation wording
   and adding the concise Hermes Runtime/license routing section.
3. Activation: native `/aegis`; natural Aegis/Aegis 2 and `$aegis`;
   preserve `aegis2`/`$aegis2` as text aliases selecting the single skill.
4. Replace the long Codex description with
   `Use when Aegis is invoked. Govern risk-scaled delivery.` Add version `2.0.0`,
   author `David A. Frey`, MIT license, and `metadata.hermes.tags`
   `[aegis, governance, sdlc, security, lifecycle]`. Omit platform claims.
5. Do not carry over Codex UI file `agents/openai.yaml`: its display branding
   stays in the heading; discovery text moves to Hermes frontmatter and its
   default invocation becomes documented native `/aegis` usage. No agents file
   or model-selection UI is added.
6. Copy all four reference files byte-for-byte, preserving every substantive
   policy, gate, schema, template, and known source wording. No optional
   deployment-placeholder repair was applied; reference fidelity takes priority.
7. Add `references/hermes-runtime.md` for progressive loading, file/evidence
   tools, bounded one-requirement delegation, independent approvals, actual
   model-route limits, confirmations, and non-sandbox boundaries. It does not
   create a competing policy or relax source controls.
8. Copy full original LICENSE unchanged to root and `references/LICENSE.md`;
   SKILL routes to that distributed legal text.
9. Calculator prompts change only host/invocation wording: fresh Codex -> fresh
   Hermes; `$aegis2`/legacy-version selection -> canonical `/aegis` port selection;
   unavailable `aegis2` -> unavailable canonical `aegis`. Preserve functionality,
   acceptance, delegation bounds, timeboxes, safety, and reporting requirements.
10. Write a Hermes-specific outcome-first README, portable active-profile install
    path, fresh-session instructions, verification limits, and upstream/port links.
    Keep Windows and WSL distinct. Add only minimal editor/OS exclusions in
    `.gitignore`; add no executable code, runtime, scaffolding, or CI.

Upstream README/RELEASE-NOTES describe a stale local-candidate packaging state,
say the Hermes port is absent, and include owner-reported earlier calculator
counts. Those are not current Hermes-port evidence and are not carried into
this README. All substantive governance policy remains, including its heavier
requirements; this is not a policy simplification.

## Verification boundary

Independent engineering and bounded SecOps/privacy reviews accepted the original
13-file conversion snapshot. Parent validation passed 30 structural/source-fidelity
checks before the documentation refresh; final packaging and native loader
results are recorded in VERIFICATION.md. All four upstream references and both license
copies match source bytes. Reversing the three SKILL-body host adaptations
recovers the upstream body after newline normalization. Calculator diffs contain
only the documented host/invocation changes. SKILL.md is 21,302 characters; its
description is 55 characters. No executable product code or automated enforcement
was added.

Authored SKILL and adapted calculator prompts use LF rather than source CRLF;
the four references and both license copies retain exact source bytes. Windows
text-write newline conversion was detected by checksum verification during local
installation and corrected with exact-byte copies of the unchanged reviewed files.
The final installed seven-file manifest equals the source manifest.

A fresh native Windows process verified the actual Hermes catalog, readiness,
all six reference loads, native `/aegis` resolution and invocation-payload
construction. The superseded default-profile skill was replaced and its archived
Aegis preflight companion removed under the owner's replacement instruction.
Only one Aegis skill remains in the configured discovery roots. Other profiles,
WSL installations, unrelated skills and historical project records were not
removed or rewritten.

The parent initialized this directory as its own repository and retained the
existing private destination. Review and verification do not themselves grant
publication authority; the owner's explicit instruction names the destination.
See VERIFICATION.md for the bounded evidence and inherited template typo.
No complete governed LLM conversation, new calculator execution, actual per-role
model routing, universal compatibility or sandbox enforcement is claimed.
