# Contributing to Spec Lint

Read `README.md`, `ABOUT.md`, and `ROADMAP.md` before contributing.

Spec Lint should produce explainable, repeatable findings for software specification documents. Rule changes must be reviewable and should avoid hidden scoring behavior.

## Contribution areas

- Rule definitions and severity levels.
- Parsing and document-structure support.
- Clear diagnostics and remediation examples.
- Configuration, ignore rules, and output formats.
- False-positive and false-negative fixtures.
- Command-line experience, tests, and documentation.

Use an Issue before changing the rule model, scoring model, configuration format, or report schema.

A rule pull request should include:

- The problem the rule detects.
- Examples that should pass and fail.
- The diagnostic message and suggested correction.
- Expected severity and scoring impact.
- Known limitations and likely edge cases.
- Automated fixtures and documentation updates.

Use focused Conventional Commit messages such as `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, and `chore:`.

Contributors are responsible for correctness, licensing, and review. Do not submit private specifications or copied proprietary documents as fixtures.