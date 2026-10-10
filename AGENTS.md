# AGENTS.md

## Repository status and evidence

- Repository: Farzam13/Bariatric-AfterCare-App.
- Baseline verified on 2026-10-10 UTC: main at commit
  2e52f7c3b2304da0eb040df266af09bf976cfe2f contains only README.md.
  AGENTS.md is introduced by the documentation pull request.
- This is currently a documentation-only repository. No application source,
  dependency manifests, build configuration, test suite, or CI workflows are
  present in the verified baseline.
- The repository name suggests a bariatric aftercare product; its implemented
  features, platform, architecture, and deployment are not established here.
- README.md documents the current scope and an AI Studio reference. An
  external app link does not establish the implementation, technology stack,
  or deployment of this repository.
- Reinspect the current branch before every task. If files have been added,
  update this status from the actual tree rather than preserving stale claims.
- Do not infer this repository's implementation from other projects, previous
  conversations, or an external app link.

## Working principles

- Read the relevant files and any scoped AGENTS.md before editing. Separate
  verified facts, proposals, and missing information.
- Make focused, reversible changes within the requested scope. Preserve
  unrelated files and work; avoid unjustified rewrites or new dependencies.
- For documentation tasks, correct inaccurate claims and broken references.
  Do not scaffold an application or choose a technology stack solely to make
  outdated documentation appear true.
- Keep planned features and architecture explicitly labeled as planned.
- Do not publish credentials, signing material, or identifiable patient data.
  Use placeholders and synthetic examples.
- For future clinical content or rules, provide primary sources and identify
  assumptions requiring clinician review; do not invent patient guidance.
- Do not modify production systems, deploy, or merge a pull request unless
  the user's task authorizes that action.

## Validation appropriate to the repository

- For documentation changes, check accuracy against the tracked tree,
  Markdown structure, referenced paths, and links where accessible.
- In a Git checkout, inspect git diff and run git diff --check. Confirm that
  only intended files changed.
- No application build, unit tests, type checks, or Gradle commands are
  currently available. Report them as not applicable because the required
  source and configuration are absent; never report them as passed.
- Do not install a framework or add a test suite for a documentation-only task.
- If application code is explicitly introduced, derive setup and validation
  commands from its real manifests and configuration. Update README.md and
  AGENTS.md together, documenting commands actually run and their results.
- Apply platform-specific checks only when the corresponding implementation
  exists, including RTL, data handling, and signing checks where relevant.

## Task workflow and reporting

1. Inspect the current branch and relevant PR changes; establish the facts.
2. Define the smallest change that satisfies the request.
3. Make the change and perform the applicable validation above.
4. Report changed or proposed files, actual checks and results, unavailable
   checks with reasons, remaining issues, and one concrete next action.
5. For PR reviews, distinguish Git mergeability from review readiness. Give
   a clear merge or needs-changes recommendation tied to the reviewed commit.

Communicate with the user in Persian, keeping file paths, commands, and code
identifiers in English. Keep repository documentation consistent with its
existing language unless a translation is requested.
