# CLAUDE.md

## Lessons

- The `humiliate-me` skill should mean adversarial pressure-testing, not literal personal degradation.
- Include Chinese and English trigger phrases such as “羞辱我”, “骂醒我”, “别哄我”, “不要情绪价值”, “泼冷水”, “挑刺”, “roast my idea”, and “tear this apart”.
- Keep global safety boundaries explicit: critique ideas, plans, evidence, and assumptions; do not attack the user’s identity, worth, body, protected characteristics, trauma, or mental health.
- When evaluating this skill with `claude -p`, prefer print-only prompts and have the parent process write `response.md`; child sessions may be blocked from writing under `.claude` paths.
- Use `python3`, not `python`, in this environment for skill evaluation scripts and post-processing.
