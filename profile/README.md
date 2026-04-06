# softwaresoftware.dev

Plugins, tools, and MCPs for Claude Code.

30+ plugins that handle real workflows. You declare what you need, the installer figures out the rest.

## Install

```bash
claude plugin marketplace add softwaresoftware-dev/softwaresoftware-plugins
claude plugin install softwaresoftware@softwaresoftware-plugins
```

Then inside Claude Code:

```
/softwaresoftware:install <plugin-name>
```

## What's here

**Frameworks.** [Zapframe](https://zapframe.softwaresoftware.dev) scaffolds a full SaaS (Django + Next.js). [Liteframe](https://liteframe.softwaresoftware.dev) ships static pages to Nginx.

**Apps.** [Cardwatch](https://cardwatch.softwaresoftware.dev) monitors Pokemon card stock. [Gummymine](https://gummymine.softwaresoftware.dev) scrapes Reddit for what people actually want. [Tokenboard](https://tokenboard.softwaresoftware.dev) is a Claude Code usage leaderboard.

**MCPs.** [Browser Bridge](https://claude-browser-bridge.softwaresoftware.dev) lets Claude control your real browser. [Gmail](https://gmail-mcp.softwaresoftware.dev) and [Google Calendar](https://google-calendar-mcp.softwaresoftware.dev) do what you'd expect.

**Providers.** Notifications, scheduling, deployment, browser automation, secure data vaults. Plugins declare abstract capabilities and the installer picks the right provider for your environment.

## Links

[softwaresoftware.dev](https://softwaresoftware.dev) · [plugins](https://plugins.softwaresoftware.dev) · [all products](https://products.softwaresoftware.dev) · [blog](https://blog.softwaresoftware.dev)

Open source. MIT licensed. Self-hosted. $0/mo infrastructure.
