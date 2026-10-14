# Claude Project Backup

**Project:** airoster
**Backup date:** 2026-10-14
**Generated from:** Claude Project

> **Important note on source:** This backup was generated from a **Claude Code cloud session** (claude.ai/code), not a claude.ai "Project" with a knowledge base. There are no Project custom instructions, uploaded Project files, or prior Project conversations visible in this session. Everything below is limited to what is actually accessible in the current session context.

---

## 1. Project Name and Purpose

| Item | Value |
|---|---|
| Project name | `airoster` (taken from repository name) |
| Repository | `isaachoo/airoster` |
| Repository URL | `https://github.com/isaachoo/airoster` |
| Purpose | **Uncertain** — not stated anywhere. The name suggests an AI-assisted roster/scheduling tool, but this is an inference only. |

---

## 2. Project Instructions / Custom Instructions

- **Claude Project custom instructions:** Not available in current project context.
- **Repository `CLAUDE.md`:** Does not exist (repository is empty).
- **User preferences (account-level, apply to this project):**
  - Concise, practical style; direct answer first.
  - Don't repeat/paraphrase the question; avoid long intros, background, caveats.
  - Short paragraphs and bullets; one idea per bullet.
  - Use tables for comparisons; concrete examples over theory.
  - State a clear recommendation when there is one.
  - Default to medium-short responses; expand only when asked ("detailed", "deep dive", "comprehensive").
  - Step-by-step instructions: **one step at a time** unless all steps are explicitly requested.
  - Priority order: 1) Correctness 2) Directness 3) Practical usefulness 4) Clarity 5) Brevity.

---

## 3. Background and Context

- Work happens in a Claude Code remote (cloud) container; repo cloned to `/home/user/airoster`.
- The GitHub repository exists but contains **no commits** on any branch visible to the session.
- No background documents, specs, or requirements have been provided.

---

## 4. Technical Architecture and Configuration

### Repository state (verified 2026-10-14)

```text
$ git log
fatal: your current branch 'claude/stoic-hawking-jx3em5' does not have any commits yet

$ git remote -v
origin  https://github.com/isaachoo/airoster (fetch)
origin  https://github.com/isaachoo/airoster (push)

$ git ls-remote origin
(no output — remote has no refs)

$ ls -la /home/user/airoster
.git/  (only)
```

### Session environment

| Item | Value |
|---|---|
| Working directory | `/home/user/airoster` |
| Development branch | `claude/stoic-hawking-jx3em5` (no commits yet) |
| Platform | Linux (cloud container) |
| GitHub access scope | `isaachoo/airoster` only |
| Connected MCP servers (observed) | GitHub, Claude Docs, Microsoft 365, **Nocoly_UAT** (HAP low-code platform: apps, worksheets, workflows/processes, views, charts, chatbots, custom pages) |

- **Tech stack / language / framework:** Not available in current project context (no code exists).
- **Relationship to Nocoly_UAT (HAP):** **Uncertain.** The connector is attached to the session, which may indicate the project is intended to be built on HAP/Nocoly, but nothing confirms this.

---

## 5. Key Decisions and Reasons

- None recorded. Not available in current project context.

---

## 6. Processes and Workflows

Session-defined git workflow (from session configuration):

```bash
# Develop and push only on the designated branch
git push -u origin claude/stoic-hawking-jx3em5
# On network failure: retry up to 4 times with backoff 2s, 4s, 8s, 16s
git fetch origin <branch-name>
git pull origin <branch-name>
```

- Do not create a pull request unless explicitly requested.

---

## 7. Important Findings from Previous Conversations

- Not available in current project context. No prior conversations are accessible.

---

## 8. Requirements and Constraints

- Functional requirements: Not available in current project context.
- Constraints known: work only on branch `claude/stoic-hawking-jx3em5`; GitHub access limited to `isaachoo/airoster`.

---

## 9. Uploaded or Referenced Files

| Filename | Purpose | Status |
|---|---|---|
| — | — | No files uploaded or referenced. Repository is empty. |

---

## 10. Completed Work

- None, apart from creating this backup file (not committed).

## 11. Current Work in Progress

- None.

## 12. Known Issues and Blockers

- Repository has no initial commit; any work will start from an empty history.
- Project purpose and requirements are undefined.

## 13. Open Questions

1. What is `airoster` meant to do (e.g., staff/shift rostering)? Who are the users?
2. Should it be built as code in this repo, on the Nocoly/HAP low-code platform (Nocoly_UAT), or both?
3. Preferred tech stack, hosting, and data sources?
4. Is there an existing Claude Project (claude.ai) with instructions/files that should be merged into this backup?

## 14. Next Actions

1. Define project purpose and core requirements.
2. Decide platform (custom code vs. Nocoly/HAP).
3. Add an initial commit (README, `CLAUDE.md` with project instructions).

---

## 15. Timeline

| Date | Event |
|---|---|
| 2026-10-13 | Repository clone directory created in container (`/home/user/airoster`, empty). |
| 2026-10-14 | Session started; user greeted ("hi"). |
| 2026-10-14 | User requested a full project backup; repo verified empty; this file generated. |

---

## 16. Context to Give a New AI Assistant

```text
Project: airoster
Repo: https://github.com/isaachoo/airoster (currently EMPTY — no commits on any branch)
Working branch used so far: claude/stoic-hawking-jx3em5
Purpose: NOT YET DEFINED (name suggests an AI-assisted rostering/scheduling tool — unconfirmed).
Platform: Undecided. A Nocoly/HAP low-code MCP connector ("Nocoly_UAT") was attached to the
  previous session, possibly relevant — unconfirmed.
Prior decisions, requirements, files, conversations: none exist.
User preferences: concise, direct answers first; bullets/tables; clear recommendations;
  concrete examples; medium-short length unless asked for detail; for step-by-step tasks,
  give ONE step at a time unless all steps requested. Priorities: correctness > directness >
  practical usefulness > clarity > brevity.
First steps: clarify purpose and requirements, choose platform, create initial commit
  with README and project instructions.
```
