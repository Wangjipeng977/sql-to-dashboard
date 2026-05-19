# User Provides Sql

[中文版](./README_zh.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.1-blue)](SKILL.md)

> user provides a SQL query and needs to generate a data dashboard or chart from query results

## What Problem This Solves

Brief paragraph explaining the specific engineering problem this skill solves.
When triggered: [trigger condition].

## Features

- Feature 1
- Feature 2
- Feature 3

## Quick Start

### Installation

```bash
# Via ClawHub
clawhub install User Provides Sql

# Or manually
cp -r User Provides Sql ~/.openclaw/skills/
```

### Usage

```bash
# Mode 1
clawhub run User Provides Sql --mode read

# Mode 2
clawhub run User Provides Sql --mode write --input ./data.json
```

## Directory Structure

```
User Provides Sql/
├── SKILL.md          # Entry point
├── LICENSE           # MIT
├── README.md         # This file
├── README_zh.md      # Chinese version
├── CONTRIBUTING.md    # Contribution guide
├── .gitignore
├── references/       # Templates and schemas
│   └── ...
└── scripts/          # Helper scripts (if any)
    └── ...
```

## Configuration

| Variable | Required | Description |
|----------|----------|-------------|
| `API_KEY` | Yes | API key for the service |

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

Powered by [MiniMax](https://minimax.io).