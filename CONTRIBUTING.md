# Contributing to Mru

Thank you for your interest. Pull requests are welcome in every public
repository. For questions or bug reports, email
[contact@mru.space](mailto:contact@mru.space).

This file applies to every repository in the mruspace organization that has no
CONTRIBUTING.md of its own. Mru Flight and Mru Field have one with their own
check commands.

## Before you open a pull request

Run the repository's check command. It runs the same checks as CI.

| Repository | Command |
| --- | --- |
| website, docs, 2049 | `npm run check` |
| flight, field, dusk | see the repository's CONTRIBUTING.md or README |
| whitepaper, brand | see the README |

## Rules for changes

- `main` is protected. Make every change through a branch and a pull request.
- State what exists. State plans as "planned". Every number has a source and
  a scope.
- Every command output on a page comes from a real run. If a change moves a
  number, run the command again and paste what it printed.
- Straight apostrophes, no em dashes, US spelling. Short sentences.
- Keep README, LICENSE and TRADEMARK current.

## License

By contributing, you agree that your contributions are licensed under the
[Apache License 2.0](LICENSE).
