# MMOS - Mental Model Operating System

> Create high-fidelity cognitive clones from any source material

MMOS (Mental Model Operating System) is an AI-orchestrated system for creating cognitive clones - AI models that think, communicate, and make decisions like specific individuals.

## Quick Start

### With Claude Code

```bash
# Create a new clone
/MMOS:tasks:execute-mmos-pipeline

# Or use the map command
*map daniel_kahneman    # Public figure (web scraping)
*map pedro_valerio      # Private person (asks for sources)
```

### Update an Existing Clone

```bash
*map pedro_valerio      # Auto-detects: brownfield (reads metadata)
```

## Workflow Matrix

| | GREENFIELD (New) | BROWNFIELD (Update) |
|---|---|---|
| **PUBLIC** (Web) | 8-12 days, 2-3M tokens | 2-5 days, 500K-1M tokens |
| **PRIVATE** (Materials) | 15-20h, 1-2M tokens | 10-19h, 300K-500K tokens |

## Directory Structure

```
mmos/
├── .claude/commands/MMOS/  # Claude Code commands
├── docs/
│   ├── mmos/               # System documentation
│   └── prd/                # Product requirements
├── expansion-packs/mmos/   # Core logic
│   ├── lib/                # Python utilities
│   ├── workflows/          # Workflow definitions
│   ├── tasks/              # Executable tasks
│   └── tests/              # Test suite (56 tests, 93%+ coverage)
└── outputs/minds/          # Generated clones
```

## Available Commands

| Command | Description |
|---------|-------------|
| `/MMOS:tasks:execute-mmos-pipeline` | Full pipeline execution |
| `/MMOS:tasks:cognitive-analysis` | Cognitive analysis phase |
| `/MMOS:tasks:mind-validation` | Validate existing mind |
| `/MMOS:tasks:test-fidelity` | Test clone fidelity |
| `/MMOS:tasks:activate-clone` | Activate a clone |
| `/MMOS:tasks:auto-detect-workflow` | Auto-detect workflow |

## Testing

```bash
cd expansion-packs/mmos
python -m pytest tests/ -v --cov=lib
```

## Requirements

- Claude Code CLI
- Python 3.10+
- Web access (for public figure research)

## License

See [LICENSE](expansion-packs/mmos/LICENSE)

---

*MMOS v3.0 | Standalone Edition*
