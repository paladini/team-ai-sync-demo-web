# team-ai-sync demo Web

This public repository is a target in the public
[`team-ai-sync`](https://github.com/paladini/team-ai-sync) demonstration.

It represents a web repository that started with partial AI guidance and then
received synchronized files from
[team-ai-sync-demo-source](https://github.com/paladini/team-ai-sync-demo-source).

## Demo context

- [team-ai-sync](https://github.com/paladini/team-ai-sync) provides the GitHub
  Action.
- [team-ai-sync-demo-source](https://github.com/paladini/team-ai-sync-demo-source)
  stores the shared `AGENTS.md`, `CLAUDE.md`, `.editorconfig`, instructions,
  prompts, and `sync-config.json`.
- [team-ai-sync-demo-api](https://github.com/paladini/team-ai-sync-demo-api)
  is the other target repository in the same demo.

## Sync result

The Action opened and updated
[Web pull request #1](https://github.com/paladini/team-ai-sync-demo-web/pull/1),
which synchronized the shared team guidance into this repository.

The final verification run in the source repository reported no remaining
changes:
[final dry run](https://github.com/paladini/team-ai-sync-demo-source/actions/runs/27316035674).
