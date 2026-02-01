# rulesets

Reusable GitHub repository ruleset JSON templates for branch and tag protection.

📋 **Overview**

`rulesets` provides reusable JSON templates you can use to configure repository-level protection rules for branches and tags. Use these templates as a starting point and customize them to match your organization's policies.

---

## Included files ✅

- `default-branch-protection.json` — Recommended protection for the default branch (e.g., `main`), including required status checks, required reviewers, and merge restrictions.
- `release-branch-protection.json` — Rules for long-lived or release branches (e.g., `release/*`).
- `tag-protection.json` — Policies for protecting tags (e.g., signed or restricted tag creation).

---

## Quick start ✨

1. Review and customize the JSON files to match your organization's policies.
2. Test changes in a non-production repository.
3. Apply the rules via the GitHub UI (Repository Settings → Code and automation → Rules) or automate deployment using the GitHub REST API.

---

## License 🔒

This project is licensed under the **Apache License 2.0**. See the repository `LICENSE` file for the full license text and terms.
