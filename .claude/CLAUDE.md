# MMOS - Mental Model Operating System

> Claude Code configuration for standalone MMOS repository

## Core Understanding

MMOS (Mental Model Operating System) creates high-fidelity cognitive clones from any source material. This is the standalone repository containing only the MMOS expansion pack.

## Directory Structure

```
mmos-standalone/
├── .claude/
│   ├── CLAUDE.md           # This file
│   └── commands/MMOS/      # Claude Code slash commands
├── docs/
│   ├── mmos/               # MMOS documentation
│   └── prd/mmos-prd.md     # Product requirements
├── expansion-packs/
│   └── mmos/               # Core MMOS logic
│       ├── agents/         # Agent personas
│       ├── checklists/     # Validation checklists
│       ├── config/         # Configuration files
│       ├── lib/            # Python utilities
│       ├── scripts/        # Helper scripts
│       ├── tasks/          # Executable tasks
│       ├── templates/      # Document templates
│       ├── tests/          # Test suite
│       └── workflows/      # Workflow definitions
└── outputs/
    └── minds/              # Generated cognitive clones
```

## Quick Start

### Create a New Clone

```bash
/MMOS:tasks:execute-mmos-pipeline
```

Or use the map command:
```bash
*map daniel_kahneman    # Auto-detects: public figure (web scraping)
*map pedro_valerio      # Auto-detects: private person (asks for sources)
```

### Available Slash Commands

- `/MMOS:tasks:execute-mmos-pipeline` - Full pipeline execution
- `/MMOS:tasks:cognitive-analysis` - Cognitive analysis phase
- `/MMOS:tasks:mind-validation` - Validate existing mind
- `/MMOS:tasks:test-fidelity` - Test clone fidelity
- `/MMOS:tasks:activate-clone` - Activate a clone for use
- `/MMOS:tasks:auto-detect-workflow` - Auto-detect workflow type
- `/MMOS:tasks:research-collection` - Research collection phase
- `/MMOS:tasks:viability-assessment` - Assess viability

## Code Standards

### Language
- All code, variables, functions, comments: **English**
- Discussion with user: **PT-BR** when appropriate

### Principles
```yaml
architecture:
  data_location: database  # not files for structured data
  configuration: YAML/JSON # not hardcoded
  validation: real_data    # not lorem ipsum

principles:
  reusability: DRY
  scope: clear_boundaries
  flexibility: config_over_code
```

## Testing

```bash
cd expansion-packs/mmos
./venv/bin/pytest tests/ -v --cov=lib
```

**Coverage:** 93%+ | **Tests:** 56 passing

## outputs/minds/ Directory

This directory contains ONLY the direct output of the MMOS pipeline:

```
outputs/minds/{mind_slug}/
├── sources/        # Source materials collected
├── analysis/       # Phase 3 outputs
├── synthesis/      # Phase 4 outputs
├── implementation/ # Phase 5 outputs
├── system_prompts/ # Final system prompts
├── kb/             # Knowledge base chunks
├── docs/           # Mind-specific process docs
└── logs/           # Mind-specific execution logs
```

## Workflow Matrix

```
┌─────────────┬─────────────────────┬────────────────────────┐
│             │   GREENFIELD        │   BROWNFIELD           │
│             │   (New Clone)       │   (Update Existing)    │
├─────────────┼─────────────────────┼────────────────────────┤
│ PUBLIC      │  Auto-detected      │  Auto-detected         │
│ (Web)       │  8-12 days          │  2-5 days              │
│             │  2-3M tokens        │  500K-1M tokens        │
├─────────────┼─────────────────────┼────────────────────────┤
│ NO-PUBLIC   │  User guided        │  Context-aware         │
│ (Private)   │  15-20h             │  10-19h                │
│             │  1-2M tokens        │  300K-500K tokens      │
└─────────────┴─────────────────────┴────────────────────────┘
```

---

*MMOS Standalone v1.0 | Extracted from AIOS-FULLSTACK*
