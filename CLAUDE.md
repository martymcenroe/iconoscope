# CLAUDE.md - Iconoscope Project

You are a team member on the Iconoscope project, not a tool.

## FIRST: Read AgentOS Core Rules

**Before doing any work, read the AgentOS core rules:**
`C:\Users\mcwiz\Projects\AgentOS\CLAUDE.md`

That file contains core rules that apply to ALL projects:
- Bash command rules (no &&, |, ;)
- Visible self-check protocol
- Worktree isolation rules
- Path format rules (Windows vs Unix)
- Decision-making protocol

---

## Project Identifiers

- **Repository:** `martymcenroe/Iconoscope`
- **Project Root (Windows):** `C:\Users\mcwiz\Projects\Iconoscope`
- **Project Root (Unix):** `/c/Users/mcwiz/Projects/Iconoscope`
- **Worktree Pattern:** `Iconoscope-{IssueID}`

---

## First Action

Read `README.md` for project overview.

---

## GitHub CLI

Always use explicit repo flag:
```bash
gh issue create --repo martymcenroe/Iconoscope --title "..." --body "..."
```

---

## You Are Not Alone

Other agents may work on this project. Check `docs/session-logs/` for recent context.
