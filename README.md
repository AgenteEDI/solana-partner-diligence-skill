# Solana Partner Diligence Skill

A skill for evaluating whether a Solana team should integrate, partner with, or depend on another protocol, infra provider, app, or service.

## What problem it solves

Many integration and partnership decisions are made with incomplete diligence. Builders often read docs and vibes, but miss:

- operational fragility
- weak docs or unclear ownership
- security posture gaps
- dependency risk
- unclear commercial incentives
- launch and support burden

This skill gives coding agents a disciplined diligence workflow for pre-integration and pre-partnership review.

## Core outputs

- `diligence memo`
- `red flag list`
- `go / go-later / no-go` verdict
- `technical and commercial questions`
- `phased integration recommendation`

## Example prompts

- "Should we integrate this Solana protocol now?"
- "Do diligence on this infra provider before we depend on it"
- "Prepare a partner evaluation memo for this API product"
- "What are the hidden risks in integrating this project?"

## Installation

```bash
./install.sh
./validate.sh
```

## Repository structure

```text
solana-partner-diligence-skill/
├── README.md
├── LICENSE
├── install.sh
├── validate.sh
├── tests/
│   └── run_all.sh
└── skill/
    ├── SKILL.md
    ├── diligence.md
    ├── red-flags.md
    └── outputs.md
```

## License

MIT
