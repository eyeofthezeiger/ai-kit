# Adding to ai-kit

## Where it goes

- Instructions an agent follows for a kind of task: `skills/<name>/SKILL.md`
- A single prompt you paste or call: `prompts/<name>.md`
- A server that gives agents tools or data: `mcp/<name>/`
- Cases that check a skill or prompt still works: `evals/<name>/`
- Config only one tool understands: `platforms/<tool>/`

## Rules

1. Copy the `_template` in that folder. Names are kebab-case.
2. Write for any model. No tool names, slash commands or vendor features in the core.
3. Add at least three eval cases for every new skill or prompt.
4. Public-safe: no secrets, no company or client names, no internal URLs, no real user data.
5. List new entries in that folder's README.
