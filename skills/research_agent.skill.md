---
name: agentic-research-agent
description: "Autonomous research agent that investigates topics, extracts insights, and structures findings from multiple sources."
version: 1.0.0
author: Eiom
tags: [research, writing, agent, automation]
---

# Agentic Research Agent

Investigates any topic by searching the web, extracting content, and synthesizing structured findings.

## When to Use
- Researching background for an article
- Competitive analysis for market research
- Gathering sources for a report

## Procedure
1. web_search(query, limit=10) on the topic
2. web_extract(urls) on top 5 results
3. Synthesize findings into structured outline
4. Save to datos/research/{topic}.json
5. Return outline ready for Draft Agent

## Verification
- [ ] Minimum 5 sources consulted
- [ ] Each source has a URL and timestamp
- [ ] Findings structured with sections
- [ ] Contradictions noted explicitly
