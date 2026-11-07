# mcp

MCP (Model Context Protocol) servers. Any MCP client can use them, so they stay out of `platforms/`.

One folder per server, with:

- `README.md`: what tools and resources it exposes, how to run it, which env vars it needs
- the server code, in whatever language suits it
- `.env.example` with placeholder values only

Client setup snippets for a specific tool go in `platforms/<tool>/`.

- [_template](_template/README.md): copy to start a new server
