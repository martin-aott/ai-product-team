# Product Discovery Flow

1. Run technical-decomposer
   → output: system_breakdown.json

2. Run problem-extractor
   → input: breakdown + problem.md
   → output: problems.json

3. Run pattern-identifier
   → input: breakdown + patterns.md
   → output: patterns.json

4. Run product-strategist
   → input: problems + patterns + outcome.md
   → output: ideas.json

5. Run feasibility-filter
   → input: ideas.json
   → output: scored_ideas.json

6. Run gtm-translator
   → input: scored_ideas.json
   → output: go_to_market.json