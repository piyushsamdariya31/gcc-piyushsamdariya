# GCC Ledger

India's GCC ecosystem, with a receipt for every number.

GCC Ledger helps a company plan its first India Global Capability Centre. It ranks cities against the company's own plan and priorities, shows where published figures disagree, tracks new centres, and counts the public evidence behind each setup provider's track record. Every figure links to its source and carries a grade:

- **A**: from the organisation that made the claim, or a direct report
- **B**: a roundup restating someone else's claim
- **C**: a post with no traceable origin

## What's on the page

| Tab | What it does |
| --- | --- |
| Plan an entry | Rank cities by fit for your team size, seniority and priorities; see cost, incentives you actually qualify for, and a board memo |
| Truth check | Eight basic questions, every published answer, and what each one counts |
| New centres | 59 recent GCC openings and expansions, with source grades and setup partners |
| Provider receipts | Each provider's claimed track record next to client announcements that name it |
| Ask the ledger | Search the ledger in plain language |
| Add evidence | Paste an announcement and get a structured, graded record |

## AI is optional

The site needs no API key. Without AI, the research desk returns matching records, the board memo is built from the figures, and extraction uses rules.

Visitors who have an Anthropic API key can turn on AI from the **AI** button at the top right. The key is stored only in their own browser and sent directly to Anthropic. It never touches this repository or the server.

## Deploy

It's a single static page with no build step and no dependencies.

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Leave the framework as **Other** and click **Deploy**. `vercel.json` already points Vercel at the `public` folder.

To preview locally, open `public/index.html` in a browser.

## Data

Collected from 63 public sources between 17 and 18 October 2026: industry reports, state policy documents, company announcements and real-estate research. Salary medians and verified GCC counts are Flexiple's published figures; office rents are CRE Matrix's. The cost model's loaded-cost multiplier and seat size are stated assumptions you can change on the page.
