# softwaresoftware.dev

Open-source plugins, tools, and MCPs that make Claude Code do real work.

## What we build

**[Plugin ecosystem](https://plugins.softwaresoftware.dev)** — 30+ Claude Code plugins with automatic dependency resolution. Declare what you need, the installer wires it together.

- **Frameworks** — [Zapframe](https://zapframe.softwaresoftware.dev) (full SaaS from a prompt), [Liteframe](https://liteframe.softwaresoftware.dev) (static sites, zero ceremony)
- **Apps** — [Cardwatch](https://cardwatch.softwaresoftware.dev) (Pokemon card stock monitor), [Gummymine](https://gummymine.softwaresoftware.dev) (Reddit market research), [Tokenboard](https://tokenboard.softwaresoftware.dev) (usage leaderboard)
- **MCPs** — [Browser Bridge](https://claude-browser-bridge.softwaresoftware.dev) (control your real browser), [Gmail](https://gmail-mcp.softwaresoftware.dev), [Google Calendar](https://google-calendar-mcp.softwaresoftware.dev)
- **Capability providers** — notifications, scheduling, deployment, browser automation, secure data vaults, and more

## Quick start

```bash
# Add the marketplace
claude plugin marketplace add softwaresoftware-dev/softwaresoftware-plugins

# Install the installer
claude plugin install softwaresoftware@softwaresoftware-plugins
```

Then inside Claude Code:
```
/softwaresoftware:install <plugin-name>
```

## Links

- [softwaresoftware.dev](https://softwaresoftware.dev) — Home
- [plugins.softwaresoftware.dev](https://plugins.softwaresoftware.dev) — Plugin catalog
- [products.softwaresoftware.dev](https://products.softwaresoftware.dev) — Everything we ship
- [blog.softwaresoftware.dev](https://blog.softwaresoftware.dev) — Build logs and write-ups

All open source. MIT licensed. Self-hosted on our own hardware. $0/mo infrastructure.
