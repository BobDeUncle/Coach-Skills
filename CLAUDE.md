# Coach-Skills

Claude skills for a personal training business: weekly client check-ins, red/orange/green triage, and consistent coach replies.

## Client data

This repo is public. Real client data (names, photos, weights, health details, check-in answers) lives only in `private/`, which git ignores; the coach's returned `coach-requirements.md` goes there. Everything committed (skills, examples, tests, docs, commit messages, issues) uses anonymised or made-up clients ("Client A", invented numbers).

## Layout

- Plugin marketplace: `.claude-plugin/marketplace.json` and `.claude-plugin/plugin.json`. The coach installs the repo as a marketplace in the Claude web app, so skills reach him when changes are pushed.
- Skills: `skills/<name>/SKILL.md`, each listed in `plugin.json`'s `skills` array.
- Bump `version` in `plugin.json` with every change to a skill, so installs pick up the update.
- Skills run in the Claude web app: no local filesystem or git between chats. Anything that must persist goes to Google Drive or a file the coach downloads.

## Agent skills

### Issue tracker

Issues and specs live in GitHub Issues for BobDeUncle/Coach-Skills, via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default vocabulary: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.
