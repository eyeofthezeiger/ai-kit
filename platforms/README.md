# platforms

Thin glue for specific tools. The skills and prompts themselves live in the generic folders; this is only how each tool finds them.

- [claude-code](claude-code/README.md)
- [cursor](cursor/README.md)
- [codex](codex/README.md)

To add a tool: make `platforms/<tool>/` with a README that says where the tool looks for instructions and how to point it at `skills/` and `prompts/`. Check the tool's own docs, since these layouts change.
