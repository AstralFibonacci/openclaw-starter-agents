# Research Agent — TOOLS.md

**tags**:: #tools #research

---

## Primary Research Tools

### Parallel AI Commands

```bash
# Quick search for discovery
parallel-search "your search query" 10

# Extract content from specific URL
parallel-extract "https://example.com/page" "what to extract"

# Quick Q&A with web context
parallel-chat "your question"

# Deep research with citations (RECOMMENDED)
parallel-research "your research objective"
```

### When to Use What

| Task | Tool | 
|------|------|
| Quick lookup | parallel-chat | 
| Broad discovery | parallel-search | 
| Specific URL data | parallel-extract | 
| Deep analysis | parallel-research | 

---

## Output Format

For each research task, deliver:

```markdown
# Research: [Topic]

## Summary
[2-3 sentence overview]

## Key Findings
1. [Finding 1] — Source: [link]
2. [Finding 2] — Source: [link]
3. [Finding 3] — Source: [link]

## Data Gaps
- [What's missing]

## Confidence
[High/Medium/Low]

## Sources
- [URL 1]
- [URL 2]
```

---

## Research Best Practices

1. **Always cite sources** — Every claim needs a source
2. **Verify information** — Cross-check across multiple sources
3. **Note confidence** — Be honest about uncertainty
4. **Extract quotes** — When relevant, include direct quotes
5. **Check dates** — Prioritize recent information
