# Hermes Runtime Mapping

This is a host adapter, not a replacement policy. The source governance and
canonical schemas in SKILL.md and the four upstream references remain binding.

## Load only the reference needed

Load the installed skill with `skill_view(name="aegis")`. Progressively load a
routed guide with `skill_view(name="aegis", file_path="references/lifecycle-gates.md")`,
or the corresponding reference path. Do not substitute a summary for a required
canonical schema. Use `read_file` and `search_files` for project files and evidence;
use `terminal` for actual authorized work and verification, retaining real results.
Check the actual working directory and writable scope before writes. A requested
output destination does not change a terminal's working directory.

## Bounded delivery and independent review

When available, use `delegate_task` for explicit bounded assignments. Each delivery
agent receives exactly one approved requirement, governing spec identity, approved
contract/check identity, allowed paths, prerequisites, entry/exit criteria,
verification expectations, exclusions, and the PM escalation route. Parallelize
only independent assignments. Return questions and adjacent ideas to the PM;
do not expand scope. The PM stays non-implementing and inspects actual changed
content and evidence before acceptance; a passing check or child summary alone
is insufficient. Obtain genuinely independent PE, Tester, and SecOps judgments
where the risk path requires them. The PM cannot manufacture their approvals or
proxy an owner/HITL decision. If delegation or required independent review is
unavailable, report the blocker and ask the HITL for an authorized recovery;
do not silently waive a control or self-certify independence.

## Model routes are not per-task selectors

Children inherit the parent model under the normal delegation route;
`delegate_task` has no provider/model selector. A role label or requested model
in a task does not switch that route. Do not claim per-role routing that the host
does not expose. Record actual model and reasoning route only when exposed,
otherwise record `unknown`. If the approved project mapping is unsupported,
ask the HITL, unless verified explicit owner delegation permits the PM to map
an available alternative within its bounds. Never silently change capability
or spending, and do not alter host configuration to force a mapping without
authorization. Check the live tool schema and approved host configuration
rather than assuming tool availability from these instructions.

## Authority, isolation, and installation

Isolated agent conversations are not a security sandbox or proof of filesystem,
network, or permission containment. Use explicit workspace bounds and the host's
actual protections. Aegis is procedural guidance, with no automated gate
enforcement, runtime, installer, or permission system. Never bypass host
confirmations, transmission permissions, security controls, or approval gates.
No skill invocation, example, model mapping, or PM delegation grants promotion
or public-release authority; those remain explicit owner/HITL decisions.

## Read-only identity and version

For a plain version question, use resolved metadata from this Hermes session
when it proves the actual path and raw top-level `version` field. Otherwise,
verify the raw top-level field from that exact resolved source using a known
read-only native operation. The heading and description are not version
evidence. Do not assume that `skill_view` or another resolver is side-effect
free. If the only available route has unverified preprocessing, setup or other
effects, do not invoke it; report the unverified fields as unknown.
Do not inspect unrelated profiles, write project records, start gates, start
delegation, or treat this request as permission to run project work.

## Single-slot update

The canonical folder is `<active HERMES_HOME>/skills/software-development/aegis`
for a profile-local copy, with all references and its LICENSE.md. Native
`/aegis` invokes this single name. Resolve Windows and WSL profiles separately,
including any project-local or external directory that could shadow the package.
A `git pull` updates the active package only if that checkout is the actual
discovery source; otherwise replace the whole copied package, never merge it.

Stage and verify outside live discovery. Close affected sessions; with owner
approval for the exact locations, replace the complete selected slot without
exposing any duplicate or stale copy. Start a fresh session and verify the
actual resolved path and version. If verification fails, stop without any
restore, checkout or copy. Propose the prior release from Hermes GitLab history
by immutable commit and package digest, and name the exact destination.
A rollback is a separate active installation: obtain explicit scoped owner
approval, including G7, before any recovery action. Do not keep a local
rollback copy or substitute the Codex package.

Authoritative host documentation: https://hermes-agent.nousresearch.com/docs
Skills: https://hermes-agent.nousresearch.com/docs/user-guide/features/skills
Tools: https://hermes-agent.nousresearch.com/docs/reference/tools-reference
