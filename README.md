**Notice — 26 September 2026: please ignore the `status` column in the federal bills file.**

That column was not published by Congress. It was filled in by our own system — most rows simply say "active" — and it can be wrong: a bill the President has signed may still read "active". We have removed it from our site and our data services, and it will be removed from this file in a future release.

For where a bill stands, use `latest_action_text` and `latest_action_date`. Those are Congress.gov's own words and date for the bill's most recent action.

This copy of the federal bills file was last refreshed on 29 March 2026 and holds 6,242 bills, so it does not include later bills or actions. For 2,664 of those bills this copy records no latest action; look those bills up on Congress.gov.

# TIP Civic Data — U.S. Government Accountability Dataset

Nonpartisan civic accountability data from [Truth In Polling](https://truthinpolling.com) (501(c)(3) nonprofit).

Includes federal and state legislation, official voting records, citizen approval ratings, and multi-factor vote predictions.

## Datasets

| File | Description | Rows |
|------|-------------|------|
| federal_bills | Federal legislation (119th Congress) with status; no AI summaries | 6,242 |
| state_bills | State legislation with status and status_bucket; no AI summaries | 8,422 |
| federal_officials | Current members of Congress | 540 |
| state_officials | State legislators across 49 states | 7,392 |
| federal_floor_votes | Congressional roll call votes | 155,646 |
| state_floor_votes | State legislative roll call votes | 57,980 |
| citizen_approval | Aggregated citizen approval ratings (no PII) | 29 |
| bill_vote_distributions | Aggregated citizen bill votes (no PII) | 64 |
| pfp_predictions | Multi-factor vote predictions per official per bill | 17,473 |
| state_campaign_finance | State campaign finance contributions ($200+ threshold) | 0 |

## Update Frequency

Updates are currently paused. Last refreshed: **2026-03-20** (oldest file) to **2026-04-12** (newest file).

## File Formats

Each dataset is available as CSV in the `data/` directory.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use with attribution.

Some state bill, legislator and vote data in these files comes from LegiScan (https://legiscan.com), used under CC BY 4.0.

## Citation

```bibtex
@misc{tip_civic_data_2026,
  title={TIP Civic Data: U.S. Government Accountability Dataset},
  author={Truth In Polling, Inc.},
  year={2026},
  url={https://github.com/ForThePeople-TIP/tip-open-data},
  note={Weekly updated civic accountability data}
}
```

## Also Available On

- [Hugging Face](https://huggingface.co/datasets/truthinpolling/tip-civic-data)
- [Kaggle](https://www.kaggle.com/datasets/danieleavestip/tip-civic-data)

## API Access

For real-time queries, use the [TIP Public API](https://truthinpolling.com/developers) — 36 REST endpoints, 31 MCP tools.

## Data Notes

- All citizen-facing data (approval ratings, bill votes) is **aggregated** — no individual voter data is included.
- Campaign finance data is from FEC bulk filings (1.6M federal contributions).
- The United States is a Constitutional Republic.
