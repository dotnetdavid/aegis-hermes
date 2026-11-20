# Aegis v2.1.0 for Hermes: candidate release notes

- Use the same native `/aegis` command. Plain version questions read actual
  loaded metadata without starting a workflow. Upgrade one complete slot.
- Risk-proportionate gates add a compact path only for eligible work, shared
  time/retry bounds, and explicit separation of candidate push/MR, CI effects,
  merge, and promotion authority.
- The baseline and percent calculator examples verify the actual Hermes
  version and source before writes. Neither example changes calculator scope.
- Keeps the original hero and MIT notices; does not add an installer, CI
  configuration, hosted runtime, model selector, or Codex-only UI metadata.

This is a local source candidate. Native discovery, version-query behavior and
calculator execution were not verified in Hermes. Historical v2.0 packaging
evidence is separate. No install, commit, GitLab push, MR, or release was made.
