# AGENTS.md - Developer & AI Agent Guide for machinelearning 🤖

## 🎯 Repository Overview
**machinelearning**: Core repository for machinelearning.

---

## 🏗️ Repository Architecture
Key directories and entrypoints: `LICENSE, MobilePrice/, winequality/`.

### Tech Stack & Runtime
- **Category:** Machine Learning / Data Science Notebooks & Datasets
- **Runtime:** Python 3, Pandas, NumPy, Scikit-Learn

## ⚙️ Executable Verification Commands

### 1. Data Integrity & Python Scripts Verification
```bash
python3 -m py_compile $(find . -maxdepth 3 -name '*.py' -not -path '*/.*')
```

---

## 🛡️ Coding & Safety Guidelines for Autonomous Agents

1. **Documentation Integrity:** Preserve all existing docstrings, header comments, and licensing banners. Never delete context unless specifically instructed.
2. **Zero Hardcoded Secrets:** Never embed API keys, OAuth tokens, personal access tokens, or sensitive credentials in committed files. Read credentials exclusively from environment variables or secure credential paths.
3. **Git Hygiene:**
   - Do not force-push (`git push --force`) or execute destructive resets.
   - Never modify root git configurations or harness infrastructure outside task scope.
   - Keep git diffs atomic, focused, and verified before committing.
4. **Agent Workflow Protocol:**
   - **Plan:** Inspect codebase architecture and dependencies before editing.
   - **Act:** Make minimal, clean, high-precision changes.
   - **Verify:** Run the appropriate verification commands listed above.
   - **Reflect:** Confirm zero regressions and review `git diff`.

---
*Maintained by Ayyappa Pravin • Built for Antigravity, Claude, Cursor & Autonomous AI Agents.*
