---
name: daily-insight
description: Generate daily cognitive insights and breakthroughs on parenting, family relationships, and life wisdom. Use when the user asks for daily cognitive breakthrough content, daily insights, or when running scheduled daily tasks that involve generating educational/psychological insights for personal growth.
---

# Daily Insight Skill

This skill generates daily cognitive breakthrough content focused on parenting, family relationships, and life wisdom.

## Content Specifications

- **Length**: 300-500 Chinese characters
- **Topics**: Child education, family relationships, life-related deep insights
- **Requirements**: Must cite traceable sources, counter-intuitive, deep, applicable

## Output Structure

Each daily insight must follow this structure:

```
【今日认知突破】One-sentence core conclusion

【权威溯源依据】Complete verifiable source

【认知颠覆逻辑】Explanation of why previous understanding was wrong

【认知应用参考】Practical application scenarios
```

## Important Limitations

- Cannot guarantee 100% daily continuity (depends on heartbeat configuration and system status)
- Content based on training data, cannot verify latest papers in real-time
- For controversial topics, honestly label uncertainty

## Workflow

1. Read `memory/heartbeat-state.json`
2. Check if `dailyInsight` field is null or date is earlier than today
3. If update needed:
   - Generate cognitive breakthrough content following specifications
   - Update `dailyInsight` to today's date
   - Send content to user