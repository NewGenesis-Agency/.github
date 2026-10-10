# .github

Public defaults of the NewGenesis organisation. Nothing internal lives here: this repository
must stay public for GitHub to apply the defaults to our private repositories.

| Path | What it does |
| --- | --- |
| `profile/README.md` | The public organisation profile. |
| `SECURITY.md`, `CONTRIBUTING.md` | Default community files for every repository without its own. |
| `pull_request_template.md`, `ISSUE_TEMPLATE/` | Default pull request template and issue forms. A repository with its own `ISSUE_TEMPLATE` folder ignores these. |
| `.github/workflows/quality_gate.yml` | Reusable workflow that runs `npm run check`. |
| `workflow-templates/` | Starter workflow that calls the reusable gate. |

Internal documentation, prompts and training live in the private `agents` repository.
