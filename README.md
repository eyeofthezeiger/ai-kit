# ai-kit

Tool-agnostic AI building blocks: skills, prompts, MCP servers and evals that work with any model or agent tool.

## What goes here

- `skills/` reusable agent skills, plain markdown, one folder each
- `prompts/` standalone prompts, plain markdown
- `mcp/` MCP servers, which work across MCP clients
- `evals/` test cases for skills and prompts
- `platforms/<tool>/` only the thin glue a specific tool needs (config, file layout)

## The rule

The core stays generic. If it only works in one tool, it goes in `platforms/<tool>/`. Everything else is written so any model can follow it.

## Using it

- Copy a skill or prompt into your project, or point your tool at this folder.
- See `platforms/` for how each tool picks up skills.

## Adding things

See [ADDING.md](ADDING.md). Each folder has a `_template` to copy.

## Sibling repos

- [agent-starter](https://github.com/eyeofthezeiger/agent-starter): agent project template; keeps its own copies of skills
- [fullstack-starter](https://github.com/eyeofthezeiger/fullstack-starter): full-stack project template
- [patterns](https://github.com/eyeofthezeiger/patterns): snippets, configs and how-tos
- [handoffs-public](https://github.com/eyeofthezeiger/handoffs-public): reusable handoff docs for agents

## License

MIT. See [LICENSE](LICENSE).
