# AGENTS.md — .github

Organization profile for FunTech Factory on GitHub. `profile/README.md` is the welcome page shown on https://github.com/FunTechFactory; `profile/mark.svg` is the logo it displays, copied from `funtechfactory.com/assets/img/mark.svg`.

## Conventions

- The repo must stay public: GitHub only shows `profile/README.md` from a public `.github` repo.
- Link only to public pages (app websites, funtechfactory.com). The other org repos are private, so never link to them.
- Keep the apps table in sync with the apps catalog, `data/apps.json` in the funtechfactory.com repo. Same names, summaries and statuses.
- GitHub strips CSS and scripts from profile READMEs: plain Markdown plus the basic HTML attributes (`align`, `width`) only.

## Backlog

Work is tracked in Linear: project **[funtechfactory.com](https://linear.app/dlopezcuadrado/project/funtechfactorycom-a322a8723754)**, team `DLO`. This repo has no TODO or roadmap file, and none should be added - anything that needs doing is a Linear issue.

- **Pick work** from the project's open issues, highest priority first (Urgent → High → Medium → Low). Skip issues labelled `Blocked`: they wait on something only the owner can do, described in the issue.
- **Start**: move the issue to *In Progress*. Work directly on `main` - no feature branches.
- **Commits** cite the Linear issue they belong to. Every issue has an ID made of the team key `DLO` plus a number, shown in Linear next to the title (e.g. `DLO-7`). Put it in the commit message: `fix(DLO-7): add rollback to the deploy script`. Linear then links the commit to the issue.
- **Finish**: move it to *Done* once the commit is on `main`. Git history is the record of what happened - no "done" lists in files.
- **Found something new?** Open an issue in the same project with a label (`Bug`, `Feature`, `Improvement`; add `Blocked` plus what's needed if it depends on the owner) instead of a TODO in a file.
- **No Linear access** in this session? Say so and ask - don't recreate a backlog file.
