# Contributing to Anti-Gravity Construction System (AGCS)

Thank you for contributing to **GALACTIC-UNION / anti-gravity-construction-system**.

## Code of Conduct

All contributors must adhere to the [GALACTIC-UNION Code of Conduct](https://github.com/GALACTIC-UNION/.github/blob/main/CODE_OF_CONDUCT.md).

## Getting Started

```bash
git clone https://github.com/GALACTIC-UNION/anti-gravity-construction-system.git
cd anti-gravity-construction-system
python -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
pre-commit install
```

## Branch Strategy

| Branch           | Purpose                           |
|-----------------|-----------------------------------|
| `main`          | Production-stable; protected      |
| `develop`       | Integration branch                |
| `feature/<name>`| New features                      |
| `fix/<name>`    | Bug fixes                         |
| `hotfix/<name>` | Critical fixes → `main`           |

All changes to `main` require: PR + 2 approvals + green CI.

## Commit Messages

[Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <summary>
```

**Types**: `feat`, `fix`, `docs`, `test`, `refactor`, `perf`, `ci`, `chore`

## Pull Request Process

1. Fork and branch from `develop`
2. Write tests for new functionality (minimum 85% coverage)
3. Run `pytest` and `ruff check . && mypy src/`
4. Update docs if behavior changes
5. Open PR against `develop` with 2+ reviewer approvals

## Security

Report via [GitHub Security Advisories](https://github.com/GALACTIC-UNION/anti-gravity-construction-system/security/advisories/new).

---

*Part of OMNISCIENT CIVILIZATION NEXUS (OCN) — ASTRAL-GUARDIAN Domain* 🌌
