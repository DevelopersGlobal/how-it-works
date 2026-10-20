# Contributing

This series only works if the entries stay honest. If you want to add one, welcome - here is how.

## Two ways to contribute

1. **Pick up an open entry.** Issues labeled `entry` are topics waiting for someone. Comment on the one you want so two people do not capture the same thing.
2. **Propose a new entry.** Open an issue with the app or feature and the one specific question you want answered. "How does WhatsApp Web work?" is too broad. "What happens when the page loads before you scan the QR code?" is an entry.

## The rules every entry follows

These are the same rules in the README, and they are not negotiable:

- **Every claim links to captured evidence.** If you cannot point to something the app actually did or sent, it does not get stated as fact. Mark it **(inferred)** or **(unknown)** instead.
- **Public, unauthenticated captures only.** No accounts, no logging in, no private data, no bypassing access controls. If a question needs a logged-in session to answer, narrow the question.
- **No raw secrets in published evidence.** Tokens, storage values and identifiers that appear in captures are redacted or described, never pasted.
- **State your limits.** What you could not capture, what was too big to analyze, what the environment could not see. Unknowns stay unknown.
- Entries are made with [REA](https://github.com/morluto/rea) or equivalent open tooling, and the evidence excerpt ships with the entry so anyone can check the work.

## Entry format

Follow the structure of [entry 001](entries/001-whatsapp-web/README.md):

- One app or feature, one question.
- Plain English. The target reader is curious, not necessarily an engineer.
- Each finding next to its evidence, with inferred and unknown parts marked.
- A limits section.

New entries go in `entries/NNN-app-name/` with the next free number, and get a row in the table in the main README.

## Process

1. Comment on the issue (or open your proposal) and wait for a go-ahead, so work is not duplicated.
2. Fork, work on a branch, open a pull request.
3. Expect review on the evidence first, the writing second. A claim without evidence gets asked about.

## What makes a good entry topic

- An app or feature a huge number of people use every day.
- A question people actually wonder about.
- Answerable from public, unauthenticated behavior.
