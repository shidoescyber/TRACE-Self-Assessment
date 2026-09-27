# TRACE-Self-Assessment
Score your org's AI governance in 10 minutes. TRACE (Track, Restrict, Audit, Confirm, Expose) is a free self-assessment mapped to NIST AI RMF 1.0, 15 questions, 5 categories, one clear answer: where's your biggest AI risk exposure right now, and what to fix first
Why this exists

AI agents are already deleting production databases, leaking data through prompt injection, and operating with far more access than anyone signed off on. Most organizations don't have a framework to catch this — they have good intentions and a Slack message that says "be careful with AI."

TRACE gives you a structured, 5-category scorecard to find out where your actual exposure is, before an incident finds it for you.

What's in this repo
File	Description
TRACE_Self_Assessment.md	The full self-assessment — 15 scored questions across 5 categories, plus scoring guidance and a one-week starter plan
TRACE_Self_Assessment.pdf	Print-friendly / shareable version of the same assessment
The 5 categories
T — Track — Do you know what your AI agents are doing?
R — Restrict — Is agent access scoped like a service account?
A — Audit — Do you know what your AI was trained on and where your data goes?
C — Confirm — Is every irreversible action gated by human approval?
E — Expose — Have you found the shadow AI already in your environment?

Each category is scored 0–3 across 3 questions (0–9 per category, 0–45 total). Your lowest-scoring category is your biggest exposure — start there.

How to use it
Download or clone this repo
Open the Markdown or PDF version
Score each question 0–3 honestly — this is a diagnostic, not a report card
Total each category and identify your lowest score
Use the one-week starter plan to take your first action

No signup, no gate, no catch. Fork it, adapt it, use it in a client engagement — just keep the attribution.

Framework mapping

TRACE is mapped to the NIST AI Risk Management Framework 1.0 and the NIST Generative AI Profile (AI 600-1). Every category ties back to specific NIST subcategories — see the assessment file for the full mapping.

About

TRACE was created by Shikirra (@ShiDoesCyber), a GRC and Security Analyst working across 40+ client environments in healthcare, financial services, government, and enterprise. Built from named, publicly reported AI governance incidents — not theory.

First presented at BSides Atlanta 2026.

License

Free to use, share, and adapt with attribution. See LICENSE for details.

Questions, feedback, or want help implementing TRACE at your org? Open an issue or Reach out via linkedin.com/in/shikirrawilliams/
