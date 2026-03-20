# TIP Civic Data — U.S. Legislative Transparency Dataset

Nonpartisan civic accountability data from [Truth In Polling](https://truthinpolling.com) (501(c)(3) nonprofit).

Includes federal and state legislation, official voting records, citizen approval ratings, campaign finance industry funding, multi-factor vote predictions, and donor-to-vote-to-contract money trail analysis.

## Datasets

| File | Description | Rows |
|------|-------------|------|
| federal_bills | Federal legislation (119th Congress) | 5,922 |
| state_bills | State legislation across 49 states | 8,399 |
| federal_officials | Current members of Congress | 540 |
| state_officials | State legislators across 49 states | 7,177 |
| federal_floor_votes | Congressional roll call votes | 149,569 |
| state_floor_votes | State legislative roll call votes | 28,495 |
| citizen_approval | Aggregated citizen approval ratings (no PII) | 0 |
| bill_vote_distributions | Aggregated citizen bill votes (no PII) | 61 |
| federal_industry_funding | PAC industry funding per official (FEC) | 15,168 |
| pfp_predictions | Multi-factor vote predictions per official per bill | 17,473 |
| money_trail | Donor→vote→contract industry triangles | 53,651 |
| industry_taxonomy | CRP/OpenSecrets industry classification codes | 92 |

## Update Frequency

Weekly (Sundays). Last refreshed: **2026-03-20**.

## File Formats

Each dataset is available as CSV in the `data/` directory.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use with attribution.

## Citation

```bibtex
@misc{tip_civic_data_2026,
  title={TIP Civic Data: U.S. Legislative Transparency Dataset},
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

For real-time queries, use the [TIP Public API](https://truthinpolling.com/developers) — 18 REST endpoints, 17 MCP tools.

## Data Notes

- All citizen-facing data (approval ratings, bill votes) is **aggregated** — no individual voter data is included.
- Campaign finance data is from FEC bulk filings (1.6M federal contributions).
- Money trail triangles correlate donations, votes, and contracts — **correlation does not imply causation**.
- The United States is a Constitutional Republic.
