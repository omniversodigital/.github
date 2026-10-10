# Security Policy & Vulnerability Disclosure

At **Omniverso Digital**, security, deterministic verification, and cryptographic defense are fundamental engineering invariants across our autonomous agent mesh and sovereign financial infrastructure.

---

## 🛡️ Supported Versions

We actively provide security patches, threat mitigations, and dependency updates for the following components:

| System / Subsystem | Supported Branch | Status |
| :--- | :--- | :--- |
| **Sovereign Revenue Engine** | `main` | :white_check_mark: Active & Audited |
| **Cerebro GCP Ecosystem** | `main` | :white_check_mark: Active |
| **Agent Evals Engine** | `main` | :white_check_mark: Active |
| **Omniverso Cloud Infra** | `main` | :white_check_mark: Active |
| **Interview Copilot** | `main` | :white_check_mark: Active |

---

## 🚨 Reporting a Vulnerability

If you discover a potential vulnerability, logic flaw, or threat vector in any Omniverso Digital repository, please notify us immediately through **responsible private disclosure**:

- **Email:** [security@omniverso.digital](mailto:security@omniverso.digital) / [jeancarlof@gmail.com](mailto:jeancarlof@gmail.com)
- **PGP Encryption:** Available upon request for sensitive payload submissions.
- **Direct Lead:** Jean Carlo Ferreira (`@omniversodigital`)

### Our Response SLA:
- **Initial Acknowledgment:** Within **24 hours**.
- **Triage & Reproducibility Analysis:** Within **48 hours**.
- **Fix & Patch Deployment:** Target within **7 days** (or immediate emergency hotfix for critical severity).
- **Public Advisory / CVE:** Coordinated release post-mitigation.

---

## 🔒 Security Best Practices for Contributors
1. **Never Commit Secrets:** API keys, private keys, `.env` files, and `.tfstate` must never enter git trees. All repositories enforce strict pre-commit hooks and GitHub Push Protection.
2. **Deterministic Builds:** Always verify hashes and lockfiles (`package-lock.json`, `uv.lock`, `Cargo.lock`).
3. **Least Privilege (IAM):** Always structure permissions with explicit role scopes and zero-trust perimeter boundaries.

---

<sub>© Omniverso Digital. All rights reserved.</sub>
