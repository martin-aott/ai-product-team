---
name: pattern-identifier
description: Identifies reusable and productizable patterns from implementations.
---

## Input:
- system_breakdown.json
- patterns.md

## Output JSON:
{
  "patterns": [
    {
      "name": "",
      "description": "",
      "reusability": "low|medium|high",
      "configurable_elements": []
    }
  ]
}

## Instructions:
- Identify repeatable workflows
- Highlight what can be standardized
- Separate fixed vs configurable parts