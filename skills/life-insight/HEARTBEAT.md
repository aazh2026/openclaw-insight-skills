# Daily Insight - Heartbeat Tasks

## Daily Cognitive Insight Task

### Execution Check
1. Read `memory/heartbeat-state.json`, check "dailyInsight" field
2. If value is null or date is earlier than today, execute:
   - Generate cognitive breakthrough content meeting specifications
   - Update heartbeat-state.json dailyInsight to today's date
   - Send content to user

### Content Specifications
- Length: 300-500 Chinese characters
- Topics: Child education, family relationships, life-related deep insights
- Must cite traceable sources
- Counter-intuitive, deep, applicable

### Output Structure
- 【今日认知突破】One-sentence core conclusion
- 【权威溯源依据】Complete verifiable source
- 【认知颠覆逻辑】Explanation of why previous understanding was wrong
- 【认知应用参考】Practical application scenarios

### Important Limitations
- Cannot guarantee 100% daily continuity (depends on heartbeat configuration and system status)
- Content based on training data, cannot verify latest papers in real-time
- For controversial topics, honestly label uncertainty