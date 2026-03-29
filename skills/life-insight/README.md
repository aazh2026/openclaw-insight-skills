# Daily Insight Skill

An OpenClaw skill for generating daily cognitive insights and breakthroughs.

## Overview

This skill generates daily cognitive breakthrough content focused on parenting, family relationships, and life wisdom. It follows a structured format to ensure high-quality, actionable insights backed by credible sources.

## Features

- 📚 **Educational Insights**: Focus on child education, family dynamics, and personal growth
- 🔬 **Research-Backed**: Every insight cites verifiable sources
- 🎯 **Actionable**: Practical applications you can implement immediately
- 🔄 **Daily Automation**: Designed to work with OpenClaw's heartbeat system

## Content Structure

Each daily insight follows this format:

- **【今日认知突破】** - Core conclusion in one sentence
- **【权威溯源依据】** - Complete verifiable source
- **【认知颠覆逻辑】** - Why previous understanding was wrong
- **【认知应用参考】** - Practical application scenarios

## Installation

1. Copy the `daily-insight` folder to your OpenClaw skills directory
2. The skill will be automatically detected and loaded

## Usage

### Manual Trigger

Ask your OpenClaw agent: "Generate today's cognitive insight"

### Automated (Heartbeat)

Add to your `HEARTBEAT.md`:

```markdown
## Daily Cognitive Insight Task

1. Read `memory/heartbeat-state.json`, check "dailyInsight" field
2. If value is null or date is earlier than today:
   - Use daily-insight skill to generate content
   - Update heartbeat-state.json with today's date
   - Send content to user
```

## State File Format

`memory/heartbeat-state.json`:

```json
{
  "lastChecks": {
    "dailyInsight": "2026-03-27"
  }
}
```

## License

MIT