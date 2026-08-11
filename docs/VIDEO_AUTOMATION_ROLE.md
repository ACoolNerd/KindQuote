# KindQuote — Video Automation Role

`KindQuote` is the Kind Home Loans application/content adapter in the ACool video automation system.

## Responsibilities
- Maintain a structured registry for approved mortgage program content and source URLs.
- Request script/storyboard/render jobs from `ACoolAGENT`.
- Use prompt contracts from `ACoolPROMPT`.
- Store program, state/market, disclosure, CTA, loan-officer, campaign, and approval metadata.
- Embed approved videos on landing pages and program pages.
- Never generate current rates, APR, fees, loan limits, eligibility, timelines, licensing, or approval claims without an approved current data source.

## Program Families — Source Snapshot 2026-08-11
Observed on Kind Home Loans public pages:
- FHA
- Conventional
- Jumbo
- Reverse Mortgage
- True Stated
- Refinance Mortgage
- VA Loans
- Zero Down
- Non-QM 40 Year Loan
- Bank Statement Program
- Income Loan Program

## Minimum Video Set Per Program
- 3-minute explainer
- 90-second explainer
- 60-second explainer
- 30-second short
- 15-second hook
- FAQ clips
- process clip
- checklist clip
- 16:9 / 9:16 / 4:5 / 1:1 outputs
- captions + transcript + thumbnail brief + metadata + disclosures

## Approval State
`DRAFT -> SOURCED -> SCRIPTED -> COMPLIANCE_REVIEW -> APPROVED -> RENDERING -> QA -> PUBLISH_READY -> PUBLISHED`

See `ACoolNerd/ACoolECOSYSTEM/docs/video-automation/MASTER_REPOSITORY_MANIFEST.md` for the system contract.
