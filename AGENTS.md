# AGENTS.md — .github

Organization profile for FunTech Factory on GitHub. `profile/README.md` is the welcome page shown on https://github.com/FunTechFactory; `profile/mark.svg` is the logo it displays, copied from `funtechfactory.com/assets/img/mark.svg`.

## Conventions

- The repo must stay public: GitHub only shows `profile/README.md` from a public `.github` repo.
- Link only to public pages (app websites, funtechfactory.com). The other org repos are private, so never link to them.
- Keep the apps table in sync with the apps catalog, `data/apps.json` in the funtechfactory.com repo. Same names, summaries and statuses.
- GitHub strips CSS and scripts from profile READMEs: plain Markdown plus the basic HTML attributes (`align`, `width`) only.

## Backlog

Work is tracked in GitHub Issues: **[FunTechFactory/.github](https://github.com/FunTechFactory/.github/issues)**. This repo has no TODO or roadmap file, and none should be added - anything that needs doing is a GitHub issue.

- **Pick work** from the repo's open issues, highest priority first (`priority: urgent` → `high` → `medium` → `low`). Skip issues labelled `blocked`: they wait on something only the owner can do, described in the issue.
- **Start**: add the `in progress` label (`gh issue edit <n> --add-label "in progress"`). Work directly on `main` - no feature branches.
- **Commits** cite the issue number: `fix(#7): add rollback to the deploy script`. GitHub then links the commit to the issue. The commit that finishes the issue also says `Closes #7` in its body.
- **Finish**: the issue closes when that commit lands on `main` (otherwise `gh issue close <n>`). Git history is the record of what happened - no "done" lists in files.
- **Found something new?** Open an issue in this repo (`gh issue create`) with a label (`bug`, `feature`, `improvement`, plus a `priority:` label; add `blocked` plus what's needed if it depends on the owner) instead of a TODO in a file.
- **Old Linear IDs** (`DLO-123`) in commits and docs come from the retired Linear workspace. Open issues were moved here with their old ID in the body: `gh issue list --search DLO-123 --state all`.
- **No GitHub access** in this session (`gh` not signed in)? Say so and ask - don't recreate a backlog file.
