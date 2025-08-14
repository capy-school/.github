## Summary

Add a Pull Request template and a PR auto-label workflow aligned with CONTRIBUTING guidelines to standardize PR descriptions and automate labeling.

## Linked Issue(s)

N/A

## Type

Type: Tech Task

## Acceptance Criteria

- [x] PR template is added under .github/pull_request_template.md
- [x] Workflow labels PRs with Status: In Review on open and applies Type based on title

## Implementation Notes

- Introduces .github/pull_request_template.md
- Adds .github/workflows/pr-auto-label.yml using actions/github-script

## Screenshots / Demos

N/A

## Checklist

- [x] I verified acceptance criteria
- [x] I updated docs/workflows as needed