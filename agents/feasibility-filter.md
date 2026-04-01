---
name: feasibility-filter
description: Scores product ideas based on build complexity and risk.
---

## Input:
- ideas.json

## Output JSON:
{
  "scored_ideas": [
    {
      "product_name": "",
      "score": 1-10,
      "complexity": "low|medium|high",
      "risk": "low|medium|high",
      "time_to_mvp": "",
      "notes": ""
    }
  ]
}

## Instructions:
- Favor fast-to-market ideas
- Penalize API dependency risk
- Consider solo execution feasibility