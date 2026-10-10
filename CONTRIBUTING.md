# Contributing to Omniverso Digital

Thank you for your interest in contributing to **Omniverso Digital**. We welcome high-agency contributions, optimizations, and security hardening across our open-source repositories.

---

## 🏛️ Engineering Standard & Philosophy

We hold all software components to principal engineering standards:
1. **Clarity & Determinism:** Favor deterministic behavior, explicit error handling, and legible control flow over obscure magic.
2. **Minimal Blast Radius:** Keep changes surgical, well-tested, and easy to review.
3. **No Unaudited Dependencies:** Every third-party library must be scrutinized for security, weight, and longevity.
4. **Zero-Flake Automated Testing:** Every PR must introduce or maintain regression testing with 100% pass rate.

---

## 🛠️ Contribution Workflow

### 1. Branching Strategy
- Branch from `main` (or default upstream branch).
- Use descriptive branch naming conventions:
  - `feat/autonomous-vector-engine`
  - `fix/websocket-reconnect-backoff`
  - `perf/simd-matrix-optimization`
  - `docs/api-gateway-specification`

### 2. Commit Message Standards (Conventional Commits)
All commit messages must adhere to the [Conventional Commits](https://www.conventionalcommits.org/) specification:
```
<type>(<scope>): <short description>

[optional body]

[optional footer(s)]
```
*Types:* `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.

### 3. Testing & Verification
Before submitting a Pull Request:
- Ensure all automated unit tests pass locally (`pytest`, `npm test`, `forge test`).
- Ensure linters and type checkers report zero errors (`ruff`, `oxlint`, `mypy`, `tsc`).
- Verify documentation is updated to match interface changes.

---

## 🚀 Submitting a Pull Request
1. Fork the target repository and create your feature branch.
2. Push your changes and open a PR with the template filled in completely.
3. Link any related issues or discussions.
4. Pass all CI checks.
5. All PRs require review and approval from core maintainers before merging.

---

<sub>Built with precision by Omniverso Digital.</sub>
