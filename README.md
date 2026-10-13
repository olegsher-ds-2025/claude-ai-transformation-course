# AI Transformation with Claude

A 12-week, technical and practical self-study course for becoming an AI transformation consultant for small and mid-size companies, built around Anthropic's Claude products. Python-first. Every module ends with a lab and a deliverable you can show a client.

Start at `index.html` (course home) or `syllabus/index.html` for the overview, or read the modules below. Each page is a single self-contained HTML file (light and dark theme, works on a phone).

## Modules

| Part | # | Module | Lab / deliverable |
|---|---|---|---|
| 1 Foundations | 1 | [Transformation landscape](modules/module-01.html) | Same task on two models; "Claude for SMBs" one-pager |
| | 2 | [Prompt and context engineering](modules/module-02.html) | Tested library of 15 business prompts |
| | 3 | [Claude apps for knowledge work](modules/module-03.html) | Demo company workspace; rollout playbook |
| 2 Building | 4 | [Claude API in Python](modules/module-04.html) | Invoice extractor, realtime and batch |
| | 5 | [Knowledge retrieval (RAG)](modules/module-05.html) | Hebrew/English "ask our documents" assistant |
| | 6 | [Model Context Protocol (MCP)](modules/module-06.html) | data.gov.il MCP server; CRM server with confirm flag |
| | 7 | [Claude Code as a delivery engine](modules/module-07.html) | Reusable client-project template |
| | 8 | [Agents, Skills and plugins](modules/module-08.html) | Lead-to-proposal agent and Skill |
| 3 Production | 9 | [Evaluation, cost and reliability](modules/module-09.html) | Eval harness, cost dashboard, routing |
| | 10 | [Security, governance and compliance](modules/module-10.html) | Injection red-team, PII redaction, policy templates |
| 4 Practice | 11 | [Discovery, ROI and proposals](modules/module-11.html) | Audit scoring, ROI calculator, SOW template |
| | 12 | [Capstone and positioning](modules/module-12.html) | Case study, go-to-market plan |

## Status and caveats

- Written October 2026. Claude model names, API parameters, Claude Code settings and Agent SDK calls change quickly: check each against docs.claude.com before relying on it.
- Lab code has been compiled and, where possible, tested offline, but has **not** been run against the live Claude API. Run each lab with your own key and fix what breaks.
- Module 6 pins `mcp[cli]<2` because newer MCP SDK releases renamed `FastMCP`.
- Module 10 is not legal advice. Verify privacy and AI-regulation points with counsel.
- Examples and sample data are fictional.

`CLAUDE.md` holds the page template and build notes for continuing the course with Claude Code.
