# Fork setup

This is a fork of [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) for adding custom tools.

- **upstream**: `https://github.com/omni-mcp/isaac-sim-mcp.git` (original repo)
- **origin**: https://github.com/dcmcshan/isaac-sim-mcp (your fork; push with `git push origin main`)

Pull upstream changes:
```bash
git fetch upstream
git merge upstream/main
```

Cursor uses this repo for the **isaac-sim** MCP server (see `~/.cursor/mcp.json`). Add new tools in `isaac_mcp/server.py` and in the extension under `isaac.sim.mcp_extension/` as needed.
