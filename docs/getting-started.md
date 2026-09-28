# Getting Started as an Open-Source Maintainer

You have an idea, a repository, and the will to build in public. This guide walks you through the first 30 days of maintainership — from repository hygiene to your first merged contribution.

---

## Table of Contents

1. [Day 1–3: Repository Hygiene](#day-13-repository-hygiene)
2. [Day 4–7: Community Health Files](#day-47-community-health-files)
3. [Week 2: Your First Issues](#week-2-your-first-issues)
4. [Week 3: Onboarding Drips Wave](#week-3-onboarding-drips-wave)
5. [Week 4: Sustain and Iterate](#week-4-sustain-and-iterate)

---

## Day 1–3: Repository Hygiene

### Add a README

Your README is the front door. It should answer:

- What does this project do?
- Who is it for?
- How do I install / use it?
- How do I contribute?

Use the [`README.md`](../README.md) in this toolkit as a starting point.

### Add a LICENSE

Without a license, your project is **not open source** in the legal sense. Use the [MIT License](../LICENSE) for maximum adoption, or choose from [choosealicense.com](https://choosealicense.com/).

### Add a `.gitignore`

Prevent accidental commits of OS files, editor configs, and secrets. See [`.gitignore`](../.gitignore).

---

## Day 4–7: Community Health Files

### CODE_OF_CONDUCT.md

A code of conduct sets expectations for behaviour and gives you a process to handle violations. Copy the [Contributor Covenant](../CODE_OF_CONDUCT.md).

### CONTRIBUTING.md

Tell contributors exactly how to help. Include:

- How to claim an issue
- Development setup
- PR process
- Style guidelines

See [`CONTRIBUTING.md`](../CONTRIBUTING.md).

### Issue and PR Templates

GitHub will automatically offer templates if you place them in `.github/ISSUE_TEMPLATE/` and `.github/`. Copy the templates from this repository.

---

## Week 2: Your First Issues

### Create 5–10 Good First Issues

New contributors need low-risk entry points. Good first issues should be:

- Small in scope (under 2 hours of work)
- Clearly described with acceptance criteria
- Located in a single file or directory
- Not blocking any critical path

Use the [`good_first_issue.md`](../.github/ISSUE_TEMPLATE/good_first_issue.md) template.

### Label Your Issues

Suggested labels:

| Label | When to Use |
|---|---|
| `good first issue` | Suitable for first-time contributors |
| `documentation` | Changes to docs only |
| `help wanted` | Maintainer welcomes external help |
| `bug` | Something is broken |
| `enhancement` | New feature or improvement |

---

## Week 3: Onboarding Drips Wave

Drips Wave turns your issue backlog into a recurring funding sprint. Contributors apply to solve issues, and a Wave Program reward pool pays them based on the points they earn[reference:3].

### Prerequisites

- A GitHub **organisation** (not just a personal account) hosting the repositories you want to onboard
- At least 5–10 issues ready to be scoped
- A rough idea of which Wave Program matches your ecosystem (e.g., Stellar Wave)

### Steps

1. Sign in to the [Drips Wave app](https://www.drips.network/wave) with GitHub.
2. Go to **Maintainers → Orgs and Repos**.
3. Install the **Drips Wave GitHub App** on your organisation.
4. Sync your public repositories.
5. Apply each repository to the relevant Wave Program.
6. Wait for organiser approval.
7. Add issues to the Wave and assign complexity levels[reference:4].

See [`drips-wave-points.md`](./drips-wave-points.md) for complexity and points details.

---

## Week 4: Sustain and Iterate

- **Respond to contributors within 48 hours.** Speed is the strongest retention tool.
- **Merge small PRs quickly.** Do not let perfect be the enemy of merged.
- **Say thank you.** A Compliment in Drips Wave awards bonus points and builds loyalty[reference:5].
- **Review your backlog monthly.** Close stale issues. Re-scope vague ones.
- **Write a monthly maintainer log.** Even three bullet points build trust and transparency.

---

## Recommended Reading

- [Open Source Guides by GitHub](https://opensource.guide/)
- [The Maintainer’s Guide to Happy Contributors](https://opensource.guide/maintaining-balance-for-open-source-maintainers/)
- [Drips Wave Documentation](https://docs.drips.network/wave/)
