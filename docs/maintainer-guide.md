# Maintainer Guide

A practical playbook for running a healthy open-source project, from triage to release.

---

## Table of Contents

1. [Your Role as Maintainer](#your-role-as-maintainer)
2. [Triage Workflow](#triage-workflow)
3. [Scoping Issues for Drips Wave](#scoping-issues-for-drips-wave)
4. [Reviewing Pull Requests](#reviewing-pull-requests)
5. [Communication Templates](#communication-templates)
6. [Burnout Prevention](#burnout-prevention)
7. [Metrics That Matter](#metrics-that-matter)

---

## Your Role as Maintainer

A maintainer is not a solo builder. You are a **gardener**: you set direction, remove obstacles, and help others contribute. Your job is to make the project legible and welcoming.

Core responsibilities:

- Triage incoming issues and PRs
- Scope work clearly
- Review contributions fairly and promptly
- Communicate decisions transparently
- Protect the project’s values and code of conduct

You do **not** have to write every line of code.

---

## Triage Workflow

### Every New Issue Gets One of Five Responses

| Response | When |
|---|---|
| **Accept** | Clear, in scope, actionable. Add labels and assign if urgent. |
| **Needs info** | Vague or missing reproduction steps. Ask for specifics. |
| **Good first issue** | Small, self-contained, beginner-friendly. Apply the label. |
| **Won’t fix** | Out of scope or conflicts with project direction. Explain why, close politely. |
| **Duplicate** | Link to the canonical issue and close. |

### Triage SLA

Aim to respond to every new issue within **72 hours**. Even “Thanks, I’ll look at this next week” prevents contributors from feeling ignored.

---

## Scoping Issues for Drips Wave

Drips Wave works best when issues are **small, well-defined, and independently mergeable**.

### The Complexity Rubric

| Complexity | Points | Scope |
|---|---|---|
| **Trivial** | 100 | Typo, broken link, one-paragraph addition, label fix |
| **Medium** | 150 | New section in a guide, example code, checklist creation |
| **High** | 200 | Full tutorial, translation of a document, multi-file refactor |

When in doubt, **scope down**. A 100-point issue that gets merged beats a 200-point issue that stalls[reference:6].

### Checklist for a Wave-Ready Issue

- [ ] Title starts with a clear verb (Add, Fix, Expand, Translate)
- [ ] Description includes context and a definition of done
- [ ] Acceptance criteria are checkboxes
- [ ] Files to modify are listed
- [ ] Complexity and points are set in the Drips app
- [ ] The issue is **not** blocking a release

---

## Reviewing Pull Requests

### The Three-Pass Review

1. **Intent pass:** Does the PR solve the linked issue? If not, stop and ask.
2. **Correctness pass:** Are the changes accurate? Any broken links or typos?
3. **Style pass:** Does it follow the repository guidelines?

### Review Etiquette

- Comment on the **code/document**, not the person.
- Distinguish **blocking** feedback from **suggestions**.
- If you request changes, be specific: “Please add X to Y” beats “This needs work.”
- Approve with a brief note about what you liked. Positive feedback costs nothing and retains contributors.

### Merge Speed

Aim to merge **small documentation PRs within 48 hours**. For larger changes, leave a timeline in the PR: “I’ll review this in full by Friday.”

---

## Communication Templates

### Accepting an Issue
