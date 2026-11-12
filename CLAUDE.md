# CLAUDE.md

## Working rules (Karpathy-style)

Bias toward caution over speed. For trivial tasks, use judgment.

1. **Think before coding.** State assumptions explicitly. If a request has more than one reasonable reading, lay them out instead of picking one silently. If something is unclear, stop and ask. If a simpler approach exists, say so.
2. **Simplicity first.** Write the minimum that solves the problem. No speculative features, abstractions for single-use code, unrequested configurability, or error handling for impossible cases. If 200 lines could be 50, rewrite it.
3. **Surgical changes.** Touch only what the request needs. Don't reformat, refactor, or "improve" adjacent code, comments, or docs. Match the existing style. Remove only the dead code your change created; mention other dead code instead of deleting it. Every changed line should trace back to the request.
4. **Goal-driven execution.** Turn the task into a checkable goal (a test, a dry run, an expected output) and loop until it passes. For multi-step work, state a short plan with a check for each step.
