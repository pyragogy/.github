# Contributing to Pyragogy

## Welcome

Pyragogy is a multi-repo ecosystem of open research on AI–human co-learning, cognitive rhythm, and structured disagreement. The work spans theory, tooling, datasets, and editorial artifacts. Contributions from researchers, builders, educators, and curious outsiders are welcome.

## Ways to contribute

- **Report bugs or suggest features.** Open an issue in the relevant repo using the [bug report](.github/ISSUE_TEMPLATE/bug_report.md) or [feature request](.github/ISSUE_TEMPLATE/feature_request.md) template.
- **Improve documentation.** README clarifications, broken links, examples, translations — all welcome.
- **Propose new research questions.** Open a thread in the [organization Discussions](https://github.com/orgs/pyragogy/discussions) rather than an issue.
- **Contribute code or content** to a specific repo. Read its own README first; some repos have their own conventions.

## Repository conventions

These conventions apply across the org. Individual repos may extend them.

### Naming

Some repos use a layer prefix (`theory-`, `tools-`), others don't (`open-review`, `publications`, `legacy-peeragogy-handbook`). The prefix marks internal/structural assets; unprefixed names are public-facing destinations or stand-alone artifacts. When proposing a new repo, follow the closest analogue.

### Branching

- Default branch: `main` (`master` only on the legacy fork).
- PRs against `main`. Direct pushes are discouraged except for trivial org-meta work.
- Branch naming: `feat/<slug>`, `fix/<slug>`, `docs/<slug>`, `chore/<slug>`, `refactor/<slug>`.

### Commit messages

[Conventional Commits](https://www.conventionalcommits.org/) are recommended, not required. Common types: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `perf`. Subject under ~70 characters; body for the *why* if non-obvious.

### License files

Every repo must contain a `LICENSE` file (no extension) with the **canonical legal text** of the chosen license. Header rules:

- Maximum **one line** of attribution at the top: `Copyright (c) YYYY Pyragogy contributors`, followed by a blank line.
- No preamble, no separator lines, no human-readable summary links inside the file.

Reason: longer wrappers prevent GitHub Licensee from detecting the license, and the repo gets classified as `Other`. Keep summaries in `README.md` instead.

Default license per layer:

- `theory-*` (research code, libraries): MIT
- `tools-*` (chatbots, services with copyleft preference): AGPL-3.0
- `publications`, `theory-*` papers/datasets, `open-review`: CC-BY 4.0 or CC0
- Org meta (`.github`): CC-BY 4.0

## License of contributions

By contributing, you agree to license your contribution under the same terms as the repository you're contributing to. The `LICENSE` file in the root of each repo is authoritative.

## Code of Conduct

Participation in any Pyragogy space — issues, PRs, Discussions, off-platform threads linked from the org — is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). Reports go to `info@pyragogy.org`.

## Questions?

- General research questions and ideas → [Discussions](https://github.com/orgs/pyragogy/discussions)
- Project background → [pyragogy.org](https://pyragogy.org)
- Direct contact → `info@pyragogy.org`
