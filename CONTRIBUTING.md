# Contributing

Thank you for contributing! To keep our workflow consistent and predictable, please follow these guidelines when creating and managing tickets.

## Issue Types and Templates

Always create issues using the templates under New Issue:

- Emote + Type in the title, e.g. "[🐛 Type: Bug] Login fails on mobile"
- The correct "Type: …" label is auto-applied by the template and a workflow. Do not change the Type label after creation.

Available templates:
- 🐛 Type: Bug — Reproduction-first bug report with severity/priority
- ✨ Type: Feature — User story with acceptance criteria
- 🛠️ Type: Tech Task — Internal engineering work
- 🗺️ Type: Epic — Container for related work
- 🔬 Type: Research — Timeboxed spike
- ❓ Type: Question — Clarifications/discussions
- 📝 Type: Documentation — Docs updates

If you need to convert an issue to another type, close the original and open a new one with the correct template.

## Required Fields by Type

- Bugs must include: steps to reproduce, expected vs actual, environment, severity, priority, acceptance criteria.
- Features must include: user story, business value, acceptance criteria, dependencies, design links (if any).
- Tech Tasks must include: description, technical context, impact analysis, acceptance criteria, verification plan.
- Epics must include: summary, goals, deliverables, timeline (if known), stakeholders, dependencies, risks, epic DoD.
- Research must include: problem statement, scope/timebox, deliverables, acceptance criteria.
- Documentation must include: description, affected areas, audience, acceptance criteria.

Always link the parent Epic in the "Linked Epic(s)" field when applicable.

## Labels

We manage labels via `.github/labels.yml` and sync them with CI. Do not create ad-hoc labels manually.

Core label groups:
- Type: Bug/Feature/Tech Task/Research/Question/Documentation/Epic
- Status: Ready for Dev/Needs Spec/Needs QA/In Review/Blocked
- Severity: Critical/High/Medium/Low (bugs)
- Priority: P0–P4
- Impact: UX/Risk/Revenue/Growth/Cost
- Complexity: 1–10
- Agent: Developer/Background

When in doubt:
- Set Severity and Priority on Bugs.
- Set Priority on Features/Tech Tasks/Docs.
- Add Impact labels where relevant.

## Issue Lifecycle Actions

- On creation via template, the Type label is added automatically. Titles should start with the emote and "Type: …".
- Move issues through Status labels as work progresses. Only one Status label should be present at a time.
- Keep Epics updated; ensure child issues are linked using "linked issues".
- Close duplicates with the `duplicate` label and link the canonical issue.
- Use `wontfix` when intentionally closing without action and explain why.

## Pull Requests

- Reference the issue number in the PR description ("Closes #123").
- Ensure acceptance criteria are met and tested.
- Use Status: In Review once a PR is opened; set Needs QA when merged and ready for validation.

## Security

Do not file security issues publicly. Use the Security report contact link in the issue chooser.