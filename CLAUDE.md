# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

**30 Days Of Claude** — a structured, beginner-friendly GitHub course teaching Claude AI from scratch, modeled after the [30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) format. Pure Markdown — no build system, no dependencies.

## Repository Structure

```
claude/
├── README.md                        # Main course page with full table of contents
├── images/                          # Banners and screenshots
├── NN_Day_Topic_Name/               # One folder per day (zero-padded, e.g. 01, 02…30)
│   └── NN_day_topic_name.md         # Day content file (same name as folder, lowercased)
```

**Five content phases:**
- Days 01–07: Foundations (complete — full content written)
- Days 08–14: The Art of Prompting (stubs only — next to write)
- Days 15–21: Use Cases (stubs only)
- Days 22–28: Advanced Claude (stubs only)
- Days 29–30: Projects (stubs only)

Stub files contain only navigation links and a "Coming soon" notice.

## Content Conventions

Every day file must follow this structure (in order):

1. `# 🤖 Day N — Title`
2. Navigation: `[<< Day N-1](../prev/) | [Day N+1 >>](../next/)`
3. `## What You Will Learn Today` — bullet list of outcomes
4. Content sections with `##` headers
5. `## Summary` — recap with 🌕 milestone marker
6. `## Exercises` with three subsections:
   - `### Level 1 — Beginner`
   - `### Level 2 — Intermediate`
   - `### Level 3 — Challenge`
7. `🧡🧡🧡 HAPPY LEARNING 🧡🧡🧡`
8. Navigation repeated

**Tone:** Conversational, beginner-friendly. No assumed prior knowledge of AI or coding. Use analogies, comparison tables, and "Try this:" example prompts throughout.

**Formatting patterns used across all days:**
- Comparison tables for side-by-side concepts
- `>` blockquotes for tips (`💡`) and warnings (`⚠️`)
- Fenced code blocks for example prompts (use plain text, no language tag)
- `✅` / `❌` / `⚠️` for can/can't/caution lists

## Adding a New Day (Replacing a Stub)

1. Open `NN_Day_Topic_Name/NN_day_topic_name.md`
2. Replace the stub content with full day content following the conventions above
3. Ensure navigation links point to the correct previous and next day folders
4. Update nothing in README.md — links are already in place

## README Badges

The README badges reference `amir-sharfu/30-Days-of-Claude` on GitHub.

## Sibling Repositories

The parent directory `D:\claude_project\Claude-Lecture\` contains two related future courses (currently empty):
- `claude-code/` — planned course on Claude Code CLI
- `claude-cowork/` — planned course on Claude co-working workflows

Do not modify those directories when working in this repo.
