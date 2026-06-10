# Safe AI-Assisted Development Workflow
## Summary
This repository demonstrates a controlled workflow for using AI on small code and documentation projects without losing human review, test discipline, or clean git history.
## Core workflow
plan → sandbox edit → test → diff review → approval → source apply → source test → git commit → checkpoint

## Problem solved
AI coding tools can be useful, but they can also create risk:
- too many edits at once
- invented details
- skipped tests
- unclear diffs
- weak review process
- messy project history

This workflow keeps AI-assisted work scoped, reviewable, and recoverable.
## Public proof included
The included `repo_cleanup_demo` proof shows a small client-style documentation cleanup:
- before README: unclear purpose and missing run/test instructions
- after README: clearer purpose, file list, run command, test command, and workflow note
- visible patch included
- proof case study included

## Real session example: rejected destructive rewrite

During a documented session on June 7, the AI proposed a README rewrite that removed the majority of an existing documentation file — replacing a detailed workflow reference with a condensed summary. The logged diff showed the change before anything touched the source: a net loss of approximately 95 lines of structured content (safety rules, review queues, command references, and workflow paths) replaced by 26 lines.

The diff review gate exposed it. Rejection reason logged: "deleted too much existing useful documentation; reject destructive rewrite before source apply."

The source file was never modified.

This is what the approval gate is for. The AI produced a plausible-looking change. The diff made the real impact visible. Human judgment stopped it.

## Repository structure
- `docs/AI_WORKFLOW_SERVICE_ONE_PAGER.md`: short service explanation
- `docs/AI_WORKFLOW_CLIENT_CHECKLIST.md`: reusable client-work checklist
- `docs/AI_WORKFLOW_SERVICE_PROFILE_BLURBS.md`: profile and service blurbs
- `proofs/repo_cleanup_demo/`: before/after proof files
- `PUBLIC_SAFETY_REVIEW_REPORT.md`: public-safety review

## Skills demonstrated
- AI-assisted workflow design
- sandbox-first change process
- test-backed documentation cleanup
- git history discipline
- before/after case proof
- technical writing for small projects
## Service angle
I can help small projects use AI safely by inspecting the repo, planning changes, editing in a sandbox, running tests, showing diffs, applying only approved changes, and leaving behind documentation plus clean project history.
