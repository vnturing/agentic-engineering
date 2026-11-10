# Agentic Engineering Resources

## Knowledge
- [Anthropic: Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Context as a finite attention budget; smallest set of high-signal tokens. Use for: the core mental model.
- [Chroma: Context Rot](https://research.trychroma.com/context-rot)
  18-model study of performance vs input length. Use for: evidence that long context is not used uniformly (synthetic tasks; mechanism unexplained).
- [Claude Code: Best practices](https://code.claude.com/docs/en/best-practices)
  Official workflow guidance (verify, /clear, subagents, lean CLAUDE.md). Use for: concrete habits.
- [Simon Willison: Agentic Engineering Patterns](https://simonwillison.net/guides/agentic-engineering-patterns/)
  Evolving guide by a practitioner. Use for: principles, testing, anti-patterns (unreviewed code).
- [Anthropic: How AI assistance impacts the formation of coding skills](https://www.anthropic.com/research/AI-assistance-coding-skills) (paper: https://arxiv.org/abs/2601.20245)
  RCT, 52 mostly junior engineers; vendor-run, small, one library. Use for: skill atrophy and interaction patterns that preserve learning.
- [METR: Early-2025 AI and experienced developer productivity](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)
  RCT, 16 devs, 246 tasks; 19% slower, felt faster. Use for: perception vs reality (older tools).
- [Gloaguen et al.: Evaluating AGENTS.md](https://arxiv.org/pdf/2602.11988)
  Context files gave no success gain and 20%+ more cost. Use for: keeping instruction files lean.

## Wisdom (Communities)
- Not yet researched.

## Gaps
- Rigorous evidence on human review capacity for agent output (how much diff a person can check well)
- Longer-term studies of skill atrophy beyond a single short task
- Check for newer METR follow-ups (2026) before relying on the 19% figure
- [Willison: Agentic manual testing](https://simonwillison.net/guides/agentic-engineering-patterns/agentic-manual-testing/)
  Exercise code for real (curl, Playwright), record commands with output (Showboat). Use for: lesson 3 verification habits.
