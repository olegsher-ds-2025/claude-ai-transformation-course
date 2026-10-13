# AI Transformation with Claude — course build (memory for next session)

Learner: Oleg (Vastama Ltd), Python developer and data scientist, Israel. Goal: become an AI transformation consultant for SMBs on Claude products.
Last updated: 2026-10-13.

## Status: ALL 12 MODULES WRITTEN AND PUBLISHED
| # | Module | Artifact | Drive file |
|---|--------|----------|------------|

Drive folder: projects/AI_course. Local-folder mount from the desktop app failed in this session; uploads went through the Google Drive connector (create_file, text/html, no conversion).

## How it was built
- Opus orchestrated; Module 1 written by Opus as the template; Modules 2–12 written by Sonnet subagents; Drive uploads by a Haiku subagent.
- Checks done: style block identical, SVG text inside viewBox, no page overflow at 400px, no emoji, no prices; Python blocks py_compile'd by agents; Module 10 PII tests pass; Module 11 code runs; Module 6 tested against mcp<2.

## Known gaps / verify before teaching
- No lab code has been run against the live Claude API (no key in the build container).
- Module 6 pins `mcp[cli]<2` because mcp 2.x renamed FastMCP to MCPServer; revisit.
- Module 7 Claude Code flags/hook names written from memory; verify against docs.claude.com/en/docs/claude-code.
- Module 8 Agent SDK API (claude-agent-sdk query/ClaudeAgentOptions) and Managed Agents: verify current API.
- Module 4 has 2 SVGs (others have 3).
- Model IDs in code: claude-haiku-5-5 / claude-sonnet-5-5 / claude-opus-5-5.

## Lesson page template (copy module-01/index.html)
- Same <style> block and tokens (light + dark), same fonts, no <html>/<head>/<body> tags
- Order: eyebrow, h1, lede, chips, objectives, N.x sections, 2–3 flat SVGs (classes s-acc/s-warm/s-plain/ln/dot), .tbl tables, .tip, .lab with runnable Python, Deliverable, Self-check (5 + <details>), Further reading, .nav
- Plain English, no emoji, no prices; Israeli SMB examples (Hebrew/Russian/English)

## Possible next steps
- Course hub page linking all 12 modules (index)
- Run every lab against the live API and fix
- Hebrew version of Module 1 briefing and Module 12 outreach material
- Slides deck per module for workshops
