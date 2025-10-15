# 🔐 Secure Env Audit

Python scripts to detect exposed secrets in environment variables or `.env` files. Built for CI pipelines, pre-deploy checks, and local audits.

---

## 🔧 Tools Included

| Script | Description |
|--------|-------------|
| `audit_env.py` | Scans current environment for sensitive keys. |
| `scan_env_file.py` | Flags secrets in `.env` or config files. |

---

## 🚀 Usage

bash

python3 audit_env.py

python3 scan_env_file.py

---

🧠 Notes
• 	Extend with regex for AWS keys, JWTs, or OAuth tokens.
• 	Ideal for pre-commit hooks or CI/CD pipelines.
