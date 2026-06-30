# Resume strategy — Podeum under-sold, AI work buried

User asked: how do I highlight Podeum more on the resume, and how do I make sure the AI agent work I'm doing at Walmart reads as a real signal? This is a real and recurring problem — the resume is balanced but the highest-signal stories (founding eng, AI work) are compressed.

**Why I did NOT touch the PDFs:** Interview is today. Both resume.pdf and resume-current.pdf are byte-identical. Touching either before the interview would change the artifact the interviewer sees — strictly worse than the current state. Defaulted to "analyze, don't apply" without asking, because the risk of touching PDFs during an active interview window is high enough to act conservatively.

**Key finding 1: Podeum is the highest-signal end-to-end ownership story, but it's compressed to 2 lines.** The current bullet doesn't carry the founding-engineer signals: "only backend engineer," "set the technical bar," "5 distinct systems." The older resume (image) has the actual technical shape that the current resume is missing.

**Key finding 2: AI work is buried in the Walmart block.** Current order: perf → multi-tenant → Orkes → RAG → multi-agent → dev tooling → mentoring. The AI bullets are middle and bottom, not leading. For AI-heavy Staff roles (most Staff roles being hired right now), the resume should lead with AI. Pure reorder, no content edits needed for the reorder itself.

**Key finding 3: AI bullets have no numbers.** Perf bullet has hard numbers (200ms → 130ms p95, 1500 RPS). RAG and multi-agent bullets don't. This is the single biggest weakness. Need real scale numbers from the user before any resume change can land — won't fabricate.

**Recommendations delivered to `reference/resume-recommendations.html`:**
1. Rewrite Podeum block (3-4 bullets, "only backend engineer" + "5 distinct systems" + full-stack contract)
2. Reorder Walmart bullets to lead with AI for AI-relevant roles (keep current order for non-AI Staff roles)
3. Add scale numbers to AI bullets (gap — need user input)
4. Sharpen dev tooling bullet (specific tool names: Claude Code, Cursor, Windsurf; "led the adoption")
5. Add AI/ML skills micro-cluster (MCP is a high-signal keyword from memory — user does advisor-executor work which is MCP-based)
6. Optional role-tagline for tailored resumes (not generic)

**Generic vs tailored split proposed:**
- Generic `resume.pdf`: expand Podeum to 3-4 bullets (applies to every role), keep current Walmart order
- Tailored `resume-current.pdf`: AI-led reorder if role is AI-heavy, add tagline, sharpen dev tooling, add MCP

**What to memorize from this LR:** When the user asks for a resume change on the day of an interview, the safe default is analyze-only, then offer to apply post-interview. The cost of touching the artifact before the interview is higher than the cost of a small delay. This is the same lesson as LR 0002 (don't argue about scope signals) — both are about respecting the user's actual situation over the user's stated request.

**Published to:** `reference/resume-recommendations.html` on abster12.github.io/learn-sde3-staff/ (linked from homepage under "Quick Prep").

**Follow-up needed from user (post-interview):**
- Scale numbers for RAG and multi-agent bullets
- What the interview was for (AI-heavy or not)
- Confirm generic vs tailored split before applying
