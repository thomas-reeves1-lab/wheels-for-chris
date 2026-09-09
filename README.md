# Wheels for Chris

A community raffle in Ulverstone, Tasmania, raising money for a reliable
accessible van for Chris. Run by Chris with his support workers and mates.

**Live site:** https://thomas-reeves1-lab.github.io/wheels-for-chris/

## What is in here

| File | What it is |
|---|---|
| `index.html` | The public raffle site. One page, mobile first. |
| `docs/money-setup.html` | How to take the money so it lands in Chris's own bank account. |
| `docs/runbook.html` | The organiser's runbook, including the permit call to make first. |
| `docs/design-kit.html` | Palette, fonts and the Canva asset briefs. |

## How to change the site

Everything editable lives in one `CONFIG` block at the top of `index.html`.
Change a value, commit, push. The live site updates in about a minute.

| Field | What it does |
|---|---|
| `checkoutUrl` | Where the buy buttons go. Empty means they send people to the bank transfer details instead of a dead link. |
| `payBsb`, `payAcct`, `payId` | Bank details for the transfer option. |
| `raised`, `ticketsSold` | The progress bar and counter. |
| `prizePool` | The prize list. Add an entry and the total, the packs and the winner count all recalculate. |
| `goal` | The target, currently $5,000. |
| `drawDate`, `drawDateLabel` | Draw day. The countdown reads `drawDate`. |
| `photoUrl` | Chris's photo, embedded as a data URI. |

## Before tickets go on public sale

Get the answer from Consumer, Building and Occupational Services in Tasmania
on whether this needs a minor gaming permit. Write down who you spoke to and
when. The runbook has the questions to ask.
