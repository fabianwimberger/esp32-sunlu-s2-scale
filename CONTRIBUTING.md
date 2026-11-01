# Contributing

## Quick start

- **Bugs:** Open an issue using the bug-report template.
- **Features:** Open an issue using the feature-request template.
- **PRs:** Fork, branch from `develop`, keep the change focused, open against `develop`.

```bash
python -m venv .venv
.venv/bin/pip install esphome
make check
make firmware
```

## Conventions

- Prefix commits semantically (`feat:`, `fix:`, `docs:`, `ci:`, `deps:`).
- One logical change per PR.
- Make sure CI is green before requesting review.
- Every release body ends with a `## Source` section: which firmware file it was built
  from, the ESPHome version, and that ESPHome is GPLv3. The firmware ships as a binary
  built from GPLv3 code, so the release has to say where that code is.

## License

By contributing, you agree that your contributions will be licensed under the project's MIT license.
