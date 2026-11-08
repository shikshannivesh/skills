# SN Data agent skills

Agent skills for **SN Data by Shikshan Nivesh**: US company financial statements, revenue by segment, 8-K events, insider trades (Form 4), planned insider sales (Form 144), large holders (13D and 13G), 13F fund holdings, House trades and FINRA short interest. Every figure links to the filing it came from.

| Skill | What it covers |
|---|---|
| [us-company-financial-statements](skills/us-company-financial-statements/SKILL.md) | Income statement, balance sheet, cash flow, ratios and revenue by segment |
| [sec-insider-trades](skills/sec-insider-trades/SKILL.md) | Form 4 insider trades and Form 144 planned insider sales |
| [13f-fund-holdings](skills/13f-fund-holdings/SKILL.md) | 13F fund holdings, fund holders of a company, 13D and 13G large holders |
| [sec-filings-and-8k-events](skills/sec-filings-and-8k-events/SKILL.md) | 8-K events, House trades and short interest |

## Install

```bash
npx skills add shikshannivesh/skills
```

## Get a key

Make a free account at https://shikshannivesh.com/data/developers. A free key answers 250 calls a day on the last five fiscal years. A data plan opens the full record (fiscal years from FY2007, quarters from 2008).

Each skill reads your key from the `SN_KEY` environment variable.

More examples (Python, Excel, MCP setup): https://github.com/shikshannivesh/sn-data-examples

Website https://shikshannivesh.com/data · Docs https://shikshannivesh.com/data/developers
