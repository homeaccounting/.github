## HomeAccounting

**Self-hosted personal finance that doesn't feel self-hosted.** Your money, your
server, your data.

Most finance apps die at the same point: logging a transaction is tedious, so
you stop. HomeAccounting attacks capture from three directions — your bank
brings transactions in on its own, a plain sentence records one, or you send a
message to a Telegram chat you already have open.

### What's here

| Repository | What it is |
| --- | --- |
| [backend](https://github.com/homeaccounting/backend) | Haskell API — event-sourced core, bank providers, Telegram capture |
| [web](https://github.com/homeaccounting/web) | React client |
| [site](https://github.com/homeaccounting/site) | www.homeaccounting.com |

### Why you might trust it with your finances

- **Open source, AGPL-3.0.** The whole thing is auditable, and the licence
  keeps it that way.
- **Bank credentials are encrypted at rest** — AES-256-GCM with a rotatable
  key. No plaintext tokens, ever.
- **Self-host if you prefer.** Run it on your own machine and your data never
  touches our servers.
- **A real disclosure policy** — see
  [SECURITY.md](https://github.com/homeaccounting/backend/blob/master/SECURITY.md)
  and `security@homeaccounting.com`. Please don't report vulnerabilities in
  public issues or chat.

### Contributing

Bank providers are the most valuable contribution: each one opens a market.
Start in [Discussions](https://github.com/orgs/homeaccounting/discussions)
or the [community](https://www.homeaccounting.com/community) — Discord in
English, Telegram in Ukrainian — and see the
CONTRIBUTING guide in whichever repository you're working on.

We're early. Things are missing, and we'd rather say so than oversell.
