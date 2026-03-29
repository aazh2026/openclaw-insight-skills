---
name: daily-insight
description: Generate daily entrepreneurship and innovation cognitive breakthrough content. Use when the user requests daily insight generation, cognitive breakthrough content, entrepreneurship knowledge sharing, or when explicitly triggered by heartbeat/cron to produce daily content. Covers startup lifecycle, innovation systems, company management, and business creativity domains.
---

# Daily Insight

Generate daily cognitive breakthrough content for entrepreneurship and innovation, following strict quality standards and format requirements.

## Overview

This skill enables systematic generation of high-quality, research-backed cognitive breakthrough content for entrepreneurs and business leaders. Each piece challenges conventional wisdom with empirical evidence from authoritative sources.

## Core Workflow

When triggered (via user request or heartbeat):

1. **Read Standards**: Load [references/instructions.md](references/instructions.md) for content requirements
2. **Check History**: Read `references/content-tracker.md` to identify already-covered topics
3. **Generate Content**: Create new insight following the 4-section format
4. **Update Tracker**: Record the new topic in content tracker
5. **Deliver**: Output the formatted content

## Content Standards (Non-Negotiable)

### Domains (Strictly Limited)
1. **Startup Lifecycle**: 0-to-1 cold start, lean startup, business model design, risk control, fundraising, equity design, team building, cash flow, startup cycles, failure research
2. **Innovation Systems**: Disruptive innovation, incremental innovation, product/business model/organizational/technological innovation, user needs innovation, implementation methodology
3. **Company Management**: Strategy, organization, talent, performance, operations, finance, governance, culture, supply chain, brand
4. **Business Creativity**: Generation methodology, screening/validation, commercialization, management systems, breakthrough logic, user insights

### Quality Requirements
- **Must** challenge conventional wisdom (counter-intuitive, anti-consensus)
- **Must** be backed by authoritative empirical research (SSCI/CSSCI, HBR/MIT Sloan, top business schools, consulting firms, public cases)
- **Must NOT** be entry-level科普, motivational鸡汤,励志文案, fragmented tips
- **Must NOT** fabricate, exaggerate, or speculate

### Output Structure (Fixed Format)

```
【今日认知突破】One-sentence core conclusion

【权威溯源依据】Complete verifiable sources
- Institution/Author: Title (Year), key details

【认知颠覆逻辑】Grounded logic breaking conventional wisdom
1. Key insight 1
2. Key insight 2
...

【落地应用参考】Business applications
- For investors: ...
- For entrepreneurs: ...
- For policymakers: ...
```

### Content Tracker Format

Maintain a running table in `references/content-tracker.md`:

```markdown
| Date | Domain | Core Conclusion | Sources |
|------|--------|-----------------|---------|
| YYYY-MM-DD | Category | Summary | Author/Source |
```

## Strict Prohibitions

- Zero tolerance for fabricated content
- No motivational鸡汤, fake success学, opportunism, dark学,割韭菜 methods
- No specific project recommendations / franchises / funding agencies / paid courses
- No entry-level科普, motivational copy, fragmented tips, empty slogans
- No negative evaluations / personal attacks
- No duplicate topics
- No unverified conjectures / personal experience / hollow theory

## References

- **[instructions.md](references/instructions.md)**: Detailed content generation standards and domain definitions
- **[content-tracker.md](references/content-tracker.md)**: Record of published topics (create if missing)
- **[templates.md](references/templates.md)**: Example content structures and patterns (optional)