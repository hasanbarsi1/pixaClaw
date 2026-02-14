# Contributing to PIXACLAW

Thanks for your interest in contributing!

## Getting Started

```bash
git clone https://github.com/hasanbarsi1/PIXACLAW
cd PIXACLAW
npm install
npm run build
```

## Development

```bash
# Build TypeScript
npm run build

# Run locally
./PIXACLAW.sh start

# View logs
./PIXACLAW.sh logs all
```

### Project Structure

- `src/` - TypeScript source (queue processor, channel clients, routing)
- `lib/` - Bash scripts (daemon, setup wizard, messaging)
- `scripts/` - Installation and bundling scripts
- `.agents/skills/` - Agent skill definitions
- `docs/` - Documentation

## Submitting Changes

1. Fork the repo and create a branch from `main`
2. Make your changes
3. Test locally with `PIXACLAW start`
4. Open a pull request

## Reporting Issues

Open an issue at [github.com/jlia0/PIXACLAW/issues](https://github.com/jlia0/PIXACLAW/issues) with:

- What you expected vs what happened
- Steps to reproduce
- Relevant logs (`PIXACLAW logs all`)

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
