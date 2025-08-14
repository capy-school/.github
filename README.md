## Capy School .github

Centralized GitHub configuration for the Capy School organization.

### What’s included
- Issue templates (under `.github/ISSUE_TEMPLATE/`)
  - 🐛 Bug report, ✨ Feature request, 📝 Documentation, 💬 Question, 🎨 Design, 🗺️ Epic, 🔬 Research, 🛠️ Technical Task
  - PM-friendly optional fields: Acceptance Criteria, Stakeholders, Dependencies, Risks & Assumptions, PM Notes
- Labels (managed via `.github/labels.yml` and synced by CI)
  - Type/Status/Severity/Priority/Impact/Complexity/Agent
- Workflows (under `.github/workflows/`)
  - `sync-labels.yml`: Keeps repository labels in sync with `.github/labels.yml`
  - `apply-form-labels.yml`: Applies labels based on Issue Form content
  - `auto-type-label.yml`: Ensures Type label on issues based on title

### How to use
- Creating issues: pick the appropriate template and fill only what’s relevant. PM fields are optional but help the dev team.
- Labels: do not create labels manually. Edit `.github/labels.yml` and let CI sync them.
- Sync labels manually: edit and push `.github/labels.yml` (or run the "Sync labels" workflow from the Actions tab).

### Security
- Report vulnerabilities privately via: `mailto:xcapyschoolx@gmail.com`

### Contributing
- See `CONTRIBUTING.md` for guidelines on issue types, labels, and PR expectations.