# Contributing to NewGenesis repositories

These rules are the same in every repository. A repository's own `CLAUDE.md` or
`CONTRIBUTING.md` may add rules for its scope, never remove these.

## Language and style

- Everything is written in English: code, identifiers, comments, commit messages, branches,
  issues, pull requests and documentation. The only exception is the text shown on a client's
  website, written in the language of its audience.
- Every source file opens with a header block (`@file`, `@brief`, `@author`) and every
  function, component and exported constant has an English Doxygen comment (`@brief`,
  `@param`, `@returns`, `@throws`). Explain why, not what.
- Use a full sentence or a plain hyphen. No em dash and no en dash anywhere.
- Files and folders use lowercase `snake_case`, ASCII only. Repositories use `kebab-case`.

## Workflow

1. One branch per person and subject, named `feat/`, `fix/`, `docs/`, `chore/` or `mockup/`.
2. Small commits in the imperative mood. A teammate's client commits carry a
   `Time-Spent: 1h30` trailer.
3. Rebase on `origin/main`, then run `npm run check` before every push.
4. Open a draft pull request at the first push. Mark it ready when the checklist is true.
5. Another person reviews. Comments that are optional start with `Nit:`.
6. Never force push a shared branch, never use `--no-verify`, never commit a secret.

## Definition of done

`npm run check` passes, the result was looked at in a browser at 1440 x 900 and 390 x 844,
and the pull request says what was checked and what was not.
