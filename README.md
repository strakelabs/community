# Strake community

Public issue tracker and discussion space for [Strake](https://strake.sh) — a BYOK (bring-your-own-key) proxy for AI assistants and agents.

No code lives here. The application code is split across our other repos; this repo exists so you have a clear place to report bugs, request features, and talk to the team out in the open.

## Found a bug?

[Open an issue](https://github.com/strakelabs/community/issues/new) and include:

- What you tried to do
- What happened instead
- Browser / OS / anything the rest of us would need to reproduce it
- Screenshots or redacted request/response snippets when relevant

Security issues are different — **please don't open a public issue for those**. Email [security@strakelabs.com](mailto:security@strakelabs.com) instead. See our [security policy](https://strake.sh/security/) and the [`/.well-known/security.txt`](https://strake.sh/.well-known/security.txt) file for details.

## Want to propose a feature or kick off a discussion?

[Start a discussion](https://github.com/strakelabs/community/discussions). Roadmap thoughts, integration requests (a new upstream provider, a new tool you want first-class docs for), pricing feedback — all fair game.

## Getting support

For account-specific help, billing questions, or anything you don't want in public: [hello@strakelabs.com](mailto:hello@strakelabs.com).

We read everything. We read faster when you tell us what you've already tried.

## Integrations and plugins

| Tool | Package | Notes |
|---|---|---|
| **OpenClaw** | [`@strakelabs/openclaw-strake`](https://www.npmjs.com/package/@strakelabs/openclaw-strake) | Provider plugin — route OpenClaw inference through a Strake endpoint without exposing your real API key |
| **Cursor / VS Code** | built-in | Use your Strake endpoint URL as a custom OpenAI-compatible base URL |
| **Claude Code** | built-in | Set `ANTHROPIC_BASE_URL` to your Strake endpoint |
| **OpenAI SDK** | built-in | Pass `baseURL` and `apiKey` from your Strake endpoint |

More integration guides at [strake.sh/docs](https://strake.sh/docs/).

## Links

- [strake.sh](https://strake.sh) — product overview and pricing
- [app.strake.sh](https://app.strake.sh) — dashboard (sign in)
- [strake.sh/docs](https://strake.sh/docs/) — integration snippets for Cursor, Claude Code, OpenAI/Anthropic SDKs
- [strake.sh/security](https://strake.sh/security/) — how we protect your keys
- [strake.sh/privacy](https://strake.sh/privacy/) · [strake.sh/terms](https://strake.sh/terms/)

---

Strake is operated by Dalton Solutions, LLC.
