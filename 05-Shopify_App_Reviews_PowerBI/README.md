# Shopify App Reviews — Responsiveness vs Rating

**Goal:** Compare average rating with developer responsiveness to spot service gaps.  
**Data/Tools:** Power BI (.pbix), DAX; fields `rating`, `developer_answered`, `reviews_count`.  
**Result:** 2-point scatter (Yes/No) + bar ranking most responsive developers (visual filter `reviews_count > 500`).

## Files
- `pbix/shopify_app_reviews.pbix`
- `images/` screenshots

## Highlights
- Scatter: X = Avg `developer_answered`, Y = Avg `rating` (Legend = answered, Details empty)
- Bar: `apps[developer]` vs Avg `developer_answered`, **visual-level filter** `reviews_count > 500`
