# How I Work

1. **Start with the people who use it.** I scope the problem with the people who hit it every day, and write down what "done" means before anything is built.
2. **Direct AI, own the decisions.** AI tools write most of the code. I set the scope, make the design calls, and review every diff. Nothing ships on "the AI said it works."
3. **Measure before changing.** Every change is first run read-only against real data, with a before/after report. Then it is built.
4. **Pass criteria first.** Success is defined before the work starts, so a result is judged against a standard, not explained after the fact.
5. **Verify by effect.** "I made the change" is not done. Done is when fresh data shows the problem is gone.
6. **Write rules down, with the reason.** Operating rules live in versioned files. Each rule records the failure that created it. Nothing important lives only in a chat.
7. **Human gates on anything that matters.** Production changes, publishing and anything irreversible wait for an explicit human yes.
8. **Log mistakes loudly.** Findings and corrections are recorded, never quietly deleted. A wrong call that is written down teaches; one that is erased does not.
9. **Catalogue, then fix.** During audits, problems are logged with severity and a plan, so fixes happen in a deliberate order instead of as rushed patches.

[← Back to the portfolio](README.md)
