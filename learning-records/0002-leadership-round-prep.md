# Leadership Round prep — story spine extracted from resume, not personal projects

User asked for leadership round prep with a key constraint: personal projects are hard to describe. This drove the choice to extract stories directly from resume bullets, all of which are now Staff-tellable in 90 seconds each.

**Correction during the session:** First draft of the prep doc used 4 stories, all from Walmart. User pushed back: "There's nothing here for the Rakuten or the founding engineer experience that is the highest signal of end to end ownership of everything." This is a real and correct signal. The doc was rewritten with 5 stories and a clear lead order. **Lesson learned for future leadership prep:** when the question is about end-to-end ownership, the founding-engineer role is almost always the strongest story in the user's history — even if it's older and shorter on the resume, the *signal* is denser. Do not default to the current role by recency.

**The 5 stories (all from resume, lead with Podeum):**

1. **Podeum — founding engineer, 0 → 10k DAU** (LEAD STORY, SCOPE / END-TO-END OWNERSHIP) — designed and built auth, virtual economy, IAP, real-time feeds. No separate platform team. Different systems, different consistency needs, all owned. Use for: "led end-to-end" / "most scope I've owned" / "high-growth environment" (the round's stated focus) / "picked the architecture."
2. **Perf work 200ms → 130ms p95 at Walmart** (INFLUENCE) — wrote a doc, aligned DB team + infra team, drove changes through design review. Use for: "influenced without authority" / "set SLOs" / "cross-team work."
3. **Multi-tenant onboarding architecture at Walmart** (AMBIGUITY) — defined the unit of isolation and sharing; avoided "build a platform" trap. Use for: "ambiguity" / "set boundaries" / "designing for unknown future."
4. **Orkes integration end-to-end at Walmart** (INTEGRATION / JUDGMENT) — picked what to adopt, wrap, reject; built the SDK adapter layer. Use for: "third-party integration" / "adopting a new technology" / "wrapping an external dependency."
5. **Rakuten — high-volume payments at scale** (SCALE / CORPORATE DELIVERY) — batch design, multi-brand, the mock-server framework that unblocked the team. Use for: "built something the team / org used" / "reliability in a high-stakes domain" / "unblocked team velocity."

**Why this matters for future sessions:** The 5 hardest questions (why still SE3, disagreement, failure, 2-3 year trajectory, influence without authority) are all answered with these stories + frame. If user faces another behavioral round, no need to rebuild — same 5 stories, lead with Podeum for ownership questions.

**Drill plan delivered (60-90 min):** 10 min reading + 15 min drilling Podeum out loud ×3 (the lead) + 10 min drilling "why still SE3" + 10 min drilling "where do you want to be" + 10 min drilling stories 2-5 out loud + 10 min real weakness + 10 min company research.

**Published to:** `reference/leadership-round-prep.html` on abster12.github.io/learn-sde3-staff/ (linked from homepage under "Quick Prep" section).

**What to memorize from this LR:** When the user says a story is missing, they're right. The user's signal on which story carries the most weight is authoritative — do not argue with it, do not relitigate it. Rewrite to match. The cost of missing it the first time is the user re-asking; the cost of missing it twice is they stop trusting the work.
