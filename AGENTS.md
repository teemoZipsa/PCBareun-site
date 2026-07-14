# Agent Working Rules

## GitHub Actions Cost Lock

- Do not add, enable, dispatch, rerun, or broaden GitHub Actions workflows without the user's explicit approval.
- Do not use a commit, push, or pull request merely to test remote CI. Run the repository's checks locally first.
- For private repositories, keep GitHub Actions disabled in repository settings. If it is explicitly re-enabled, workflows must remain manual-only (`workflow_dispatch`) unless the user approves otherwise.
- Existing automatic workflows in public repositories may remain only when they provide a real deployed service (for example Pages publishing or scheduled data refresh). Do not expand them without approval.
- Prefer an approved self-hosted runner when remote automation is explicitly required.
