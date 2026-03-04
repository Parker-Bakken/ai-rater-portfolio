# Annotation Guidelines (Sample)

This file describes a simple sentiment labeling task you can expand.

## Labels

- **positive**: expresses satisfaction, enjoyment, approval
- **negative**: expresses dissatisfaction, anger, disapproval
- **neutral**: factual or mixed/unclear sentiment

## Rules of Thumb

- Prefer **neutral** if sentiment is ambiguous.
- If text contains both positive and negative, label based on the dominant sentiment; if equal, use **neutral**.
- Ignore sarcasm unless clearly indicated; if clearly sarcastic, label by intended meaning.

## Quality Checks

- Spot-check 10% of labels for consistency.
- Keep examples of edge cases in a separate file (optional).
