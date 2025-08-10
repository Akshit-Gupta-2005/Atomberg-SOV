# Share of Voice (SoV) Analysis

## Overview
This analysis quantifies the **Share of Voice** for different brands based on search results, adjusting for engagement and sentiment to get a clearer picture of online brand presence.

We calculate three metrics:
1. **Raw SoV (%)** – Proportion of brand mentions relative to all mentions.
2. **Weighted SoV (%)** – Raw SoV adjusted for engagement (likes, comments, shares, etc.).
3. **Share of Positive Voice (SoPV %)**
   – Proportion of positive mentions for a brand relative to total positive mentions.

---

## Example: Keyword – `smart fan`

| Brand     | Raw SoV (%) | Weighted SoV (%) | SoPV (%) |
|-----------|-------------|------------------|----------|
| Atomberg  | 65.52       | 99.89            | 65.52    |
| Usha      | 0.00        | 0.00             | 0.00     |
| Orient    | 17.24       | 0.11             | 17.24    |
| Havells   | 3.45        | 0.00             | 3.45     |
| Crompton  | 13.79       | 0.00             | 13.79    |

---

## Key Insights
- **Atomberg dominates** the “smart fan” conversation with both high presence and engagement.
- Competitors like Usha have **no visibility** in this keyword space.
- **Positive sentiment** is highest for Atomberg, reinforcing brand trust.

---

## Usage
1. Collect search results for a given keyword from sources like Google, YouTube, Amazon.
2. Extract:
   - Brand mentions
   - Engagement metrics
   - Sentiment (positive, neutral, negative)
3. Apply the SoV formulas:
   ```python
   Raw SoV (%) = (Brand Mentions / Total Mentions) * 100
   Weighted SoV (%) = (Engagement-Weighted Mentions / Total Engagement-Weighted Mentions) * 100
   SoPV (%) = (Positive Mentions / Total Positive Mentions) * 100
