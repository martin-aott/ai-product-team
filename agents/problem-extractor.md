---
name: problem-extractor
description: Converts systems into generalized business problems, not tied to a specific company.
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
      "category": "",
      "current_alternatives": []
    }
  ]
}

## Instructions:
- Generalize problems beyond the original company
- Example: NOT “AOTT has expensive lead gen”
- BUT “Companies rely on expensive outsourced lead generation”