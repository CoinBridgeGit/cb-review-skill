When the user types:

review

Perform the following:

1. Fetch open GitHub pull requests using MCP
2. Present the PR list
3. Ask the user which PR to review
4. Fetch:
   - PR description
   - diff
   - changed files
5. Read:
   - agents/reviewer.md
   - context/architecture.md
   - context/known-bugs.md
   - rules/review-rules.md
6. Detect platforms:
   - Android (.kt/.java)
   - iOS (.swift)
   - SDK/shared mobile code
7. Load relevant platform rules
8. Perform a high-signal review
9. Return:
   - summary
   - meaningful risks only
   - LGTM if safe

DO NOT generate noisy comments.
