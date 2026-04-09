# Contributing to atlas-dev-hub

Thanks for taking the time to contribute. This guide covers how to submit examples.

## Submit an example

The best contributions are working code that solves a real problem. If you've integrated an ATLAS API and built something useful, we want it in the org.

### How it works

Each example lives as its own repo inside `atlas-dev-hub`. The process:

1. **Fork** [example-template](https://github.com/atlas-dev-hub/example-template) to your personal GitHub
2. **Build** your example following the structure and guidelines in the template README
3. **Submit** by opening an issue using the [Submit an example](ISSUE_TEMPLATE/submit_example.md) template — link your repo and fill in the checklist
4. **Review** — a maintainer will review your repo within 5 working days and leave feedback if anything needs changing
5. **Transfer** — once approved, we'll transfer the repo into `atlas-dev-hub` where it lives permanently under your commit history

Your name stays in the commit history. You'll be credited as the author in the repo README.

### What makes a good example

- Solves one specific problem clearly — not a kitchen sink
- Includes a README that explains the problem, prerequisites, and how to run it
- Uses the latest stable NuGet packages
- Handles errors — don't assume the happy path
- No hardcoded credentials, connection strings, or session keys — use `appsettings.json` and gitignore it

### Naming your repo

Use the format `example-[api]-[what-it-does]`, for example:

- `example-sqlrace-live-session`
- `example-stream-api-consumer`
- `example-display-api-custom-widget`


## Code standards

- **C#** examples should target .NET 6 or later
- **Python** examples should target 3.9 or later
- Follow standard language conventions — no custom formatters required
- Keep dependencies minimal. If you need a package beyond the ATLAS ones, explain why in your README
- Never commit API keys, credentials, or connection strings


## Code of conduct

All contributors are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful. Be specific. Help others learn.
