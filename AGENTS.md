# lab-sw-dev-2026 Repository Rules

Rules specific to this repository (`lab-sw-dev-2026`), loaded by agents working here. Universal rules live in `~/.agents/AGENTS.md`.

## I. Repository Invariants

1. **Direct Main Pushes Allowed**:
   - Committing and pushing directly to `main` is allowed in this repository (Alessio's decision, 11 Nov 2026).
   - This repo follows course exercises for Git and GitHub basics, so do not force a `testing` branch or pull requests for simple lab exercises unless explicitly instructed.
   - Enforced locally via `git config --local harness.allowMainPush true`.
2. **Authorship and Formatting**:
   - Commit authorship must always be Alessio Manera.
   - No AI trailers or Co-Authored-By tags (Rule 7).
   - No em-dashes anywhere; punctuate with commas, colons, hyphens, or parentheses (Rule 20).
3. **Course Reference Material**:
   - Course notes, lectures, and study guide files are located in `G:/My Drive/Y3 - LAB OF SW DEV/`.
   - Shared group project Google Doc: `1kH6ZGQ4RNco1WXaenPUA6jxSaCGwWwdI_qhNe6bTVgM`.

---

## Current state

- **Goal:** Complete Lab of Software Project Development (ET7018) exercises and group project for AY 2026-27.
- **Done:**
  - Lab 1 completed (Git basics, repo creation, README edits, GitHub project/Kanban board, issue workflow).
  - Group project brainstorm completed; team unanimously selected "Formula 1 Data and Championship Analyzer".
  - Shared Google Doc cleaned from all other candidate topics; organized into `MAIN` and `Formula 1 Project Plan` tabs.
  - Data architecture evaluated: Ergast relational CSV selected as core offline backbone (satisfying Requirement 3); OpenF1 evaluated and reserved as an optional telemetry add-on.
  - Email draft for Prof. Zeynep Yucel reviewed and finalized (names, matricole, project name, flexible 2-sentence summary).
  - Session learnings and project facts saved in shared dev memory (`f1-project-selection-and-roadmap.md`).
- **Next:**
  - Send the project topic email to Prof. Zeynep Yucel (due Monday 16 Nov).
  - Create the dedicated group GitHub repository and add all 5 team collaborators.
  - Follow upcoming lecture and lab sessions (Weeks 2-5) on Moodle.
- **Open decisions:** None blocking (team roster and project topic settled).
- **Last updated:** 2026-11-16.
