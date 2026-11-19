---
name: using-advanced-gsc
description: Answer questions about the user's own Google Search Console data with Advanced GSC SEO. Call get_capabilities first and use only the tools it lists.
---

# Using Advanced GSC SEO

Advanced GSC SEO is Google Search Console for one website, designed by enterprise SEO consultants. It is free to install. Sign-in is a Google account that already has Search Console access. Paid plans are optional.

## How to answer

1. Call `get_capabilities` first. Trust that response for the plan, the connected property, and which tools exist. Do not assume a tool is available because this skill mentions the product.
2. If no property is pinned, call `select_property`, show the sites it returns, and wait for the user to pick one.
3. Answer the user's question with the tools that response lists. Do not run a fixed audit, do not loop URL inspection, and do not request more than 300 rows.
4. When a tool response says a daily allowance is used up, stop and say so. Do not retry the same tool.

Free includes every Search Console tool for one property and 16 months of history. The tool responses report the daily allowances. Do not quote a number from memory when the tool response gives one.
