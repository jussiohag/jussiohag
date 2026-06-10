# jussiohag

## Project
TODO: add project description

## Commands
- Build: N/A
- Test: N/A
- Lint: N/A

## Conventions
- Task stamping: [ ] → [-] 🏗️ YYYY-MM-DD HH:MM → [x] ✅ YYYY-MM-DD HH:MM
- Branch workflow: feature branches, no direct commits to main
- PII: never in tracked files, use private/ (gitignored)
- Commits: conventional format (feat:, fix:, docs:, chore:), no Co-Authored-By

## Hooks
- Pre-commit: PII + secrets + QA (auto-detect)
- Pre-push: build + tests + gitleaks
- Config: .hooks-config, .hooks-allowlist

## System reference
- Full PM system docs: ~/Desktop/coding/pm/docs/PM-SYSTEM.md
- Decisions: ~/Desktop/coding/pm/decisions/
