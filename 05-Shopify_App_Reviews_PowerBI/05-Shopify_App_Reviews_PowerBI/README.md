# Shopify App Reviews — Responsiveness vs Rating

**Goal:** Compare average rating with developer responsiveness to spot service gaps.  
**Tools/Data:** Power BI; fields `rating`, `developer_answered`, `reviews_count`.  
**Result:** 2-point scatter (Yes/No) + ranked bar of most responsive developers (visual filter `reviews_count > 500`).

## Highlights (Screenshots)
![Overview](../images/overview.png)
![Key Insight](../images/bar.png)



## What to look for
- Scatter: X = Avg `developer_answered`, Y = Avg `rating` (Details empty, Legend by answered)
- Bar: `apps[developer]` vs Avg `developer_answered`, **visual-level filter** `reviews_count > 500`
