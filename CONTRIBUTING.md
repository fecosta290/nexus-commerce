# Contributing to Nexus Commerce

## Educational constraint

The developer manually authors all application source code. AI may assist only with documentation, organization, technical guidance, and learning. Contributions containing AI-generated business logic, services, tests, executable infrastructure, or application source code do not meet this project’s learning policy.

## Branches and commits

Create focused branches from the agreed base using `feature/<issue>-<slug>`, `fix/<issue>-<slug>`, `docs/<issue>-<slug>`, `chore/<issue>-<slug>`, or `spike/<issue>-<slug>`. Use Conventional Commits such as `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, and `chore:`. Branch and commit conventions remain subject to developer approval.

## Pull Request workflow

1. Link a GitHub Issue and state the intended outcome.
2. Keep the change focused and rebase or synchronize as agreed.
3. Complete the Pull Request template with validation evidence.
4. Review the diff for secrets, generated files, contract impact, and documentation.
5. Resolve review findings before merge.
6. Update the operational backlog in GitHub Projects.

## Review expectations

Review correctness, clarity, boundary ownership, security, compatibility, failure behavior, observability, and learning value. Architectural changes require a linked ADR or an explicit statement that no ADR is needed.

## Documentation

Write professional English, use relative links, distinguish proposals from implemented behavior, and update relevant requirements and decisions. Do not claim unverified progress or results.

## Testing and Done

Application changes require appropriate developer-authored tests and recorded local evidence. Apply the [Definition of Done](docs/scrum/definition-of-done.md); keep exceptions explicit and approved.
