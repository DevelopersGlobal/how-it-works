# how-it-works

How the apps everyone uses actually work, reverse engineered one feature at a time.

Every entry takes one app or feature that millions of people use daily, investigates it with [REA](https://github.com/morluto/rea) (an open source reverse engineering toolkit), and explains the findings in plain English. Every claim links back to captured evidence. When something is inferred rather than directly observed, it is marked as such.

## Why this exists

Most "how X works" content is guesswork or marketing. The interesting answers are on the wire and in the code the app itself ships. If a claim here cannot be backed by something the app actually did or sent, it does not get stated as fact.

## The method

1. Pick a feature people are curious about.
2. Capture what the app really does: network traffic, workers, storage, page structure, and where useful the shipped code, using REA's observation and analysis tools.
3. Write up what was verified, with the evidence next to each claim.
4. List what could not be verified. Unknowns stay unknown.

## Rules every entry follows

- Only claims backed by captured evidence are stated as fact. Everything else is marked **(inferred)** or **(unknown)**.
- Evidence excerpts are published with each entry so anyone can check the work.
- Captures are of public, unauthenticated behavior only. No accounts, no private data, no bypassing of access controls.
- Storage values and tokens that appear in captures are never published in raw form.
- Limits of the capture environment are stated honestly in each entry.

## Entries

| # | Subject | Question |
|---|---------|----------|
| [001](entries/001-whatsapp-web/README.md) | WhatsApp Web | What actually happens when the page loads, before you scan the QR code? |

## Suggest an entry

Open an issue with the app or feature and the specific question you want answered. The more specific the question, the better the entry.

## License

[MIT](LICENSE)
