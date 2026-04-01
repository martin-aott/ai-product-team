---
name: problem-extractor
description: Converts systems and workflows into business problems and pain points.
---

## Input:
- system_breakdown.json
- problem.md

## Output JSON:
{
  "problems": [
    {
      "description": "",
      "affected_user": "",
      "severity": "low|medium|high",
      "current_alternatives": []
    }
  ]
}

## Instructions:
- Translate each technical step into a business pain
- Focus on inefficiency, cost, or friction
- Assign severity based on impact