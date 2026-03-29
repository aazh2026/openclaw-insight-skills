---
name: daily-workplace-insights
description: Generate daily workplace management insights based on authoritative academic research. Use when asked to create daily workplace cognition breakthroughs, management insights, or evidence-based career advice. Triggers on phrases like "每日精进", "认知突破", "职场管理", "daily workplace insights". Generates content with proper academic citations from SSCI/CSSCI/HBR/top business schools/consulting firms.
---

# Daily Workplace Insights

Generate evidence-based workplace management insights with proper academic溯源.

## Core Principles

1. **Evidence-based only** - Every insight must trace to verifiable academic or industry research
2. **No fabrication** - Never invent studies, authors, or statistics
3. **Clear溯源** - Include full citations with journal names, years, and key findings
4. **Actionable** - Translate research into practical management implications

## Workflow

### 1. Select Topic

From the topic pool in [references/topic-pool.md](references/topic-pool.md), choose a topic that:
- Hasn't been covered recently
- Has sufficient academic research support
- Provides counter-intuitive or actionable insights

### 2. Research

Search for authoritative sources:
- SSCI/SCI journals (Journal of Applied Psychology, Administrative Science Quarterly, etc.)
- Harvard Business Review
- Top business schools (Harvard, Stanford, MIT Sloan, Wharton)
- Top consulting firms (McKinsey, BCG, Bain research divisions)
- CSSCI journals for China-specific contexts

Use web_search to find recent authoritative sources. Verify:
- Study authors and their affiliations
- Sample size and methodology
- Effect sizes and statistical significance

### 3. Generate Content Structure

Each insight follows this format:

```
## 📊 今日职场管理认知突破 | Day N

**日期：** YYYY-MM-DD
**主题：** [Clear, specific topic]

---

### 💡 核心认知

[1-2 paragraphs stating the counter-intuitive finding or key insight]

---

### 📚 权威溯源

1. **Author, A. A. (Year).** Title. *Journal Name*, Volume(Issue), pages.
   - Key finding with statistics

2. **Organization/Author (Year).** Study/Report name.
   - Key finding

[Minimum 2-3 sources, prefer peer-reviewed journals]

---

### 🎯 管理启示

[3-5 actionable bullet points for managers/practitioners]

---

### 📝 今日思考

[One reflective question for the reader]

---

*细分领域：Category / Subcategory*
*下次推送：Next date*
```

### 4. Update Tracking

After generating, update [references/topic-pool.md](references/topic-pool.md) to mark the topic as covered.

## Quality Standards

**Must have:**
- Specific, verifiable citations
- Effect sizes or statistical measures when available
- Counter-intuitive or non-obvious insights
- Practical applicability

**Must NOT have:**
- Vague claims without sources
- Overgeneralization from single studies
- Pop psychology without research backing
- Fabricated statistics or citations

## When Research is Insufficient

If you cannot find at least 2 high-quality sources for a topic:
1. Skip the topic
2. Select an alternative from the topic pool
3. Document the gap in [references/topic-pool.md](references/topic-pool.md)

Never lower quality standards due to lack of research.

## Resources

- [references/topic-pool.md](references/topic-pool.md) - Pre-defined topic pool with coverage tracking
- [references/research-sources.md](references/research-sources.md) - Trusted research sources and search strategies