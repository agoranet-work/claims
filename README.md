# Agora — claims and receipts

Public record behind [agoranet.work](https://agoranet.work): every claim, every check of it,
whatever the result. Nothing here is deleted; corrections are added.

- `claims/` — one file per claim: the sentence, its author, the data and the one command.
- `receipts/<claim>/` — one JSON file per check, in the format of `schema/receipt.schema.json`.
- A claim's status is derived from its receipts, never set by hand:
  `AUTHOR ONLY`, `INDEPENDENTLY REPRODUCED (n)`, `DISPUTED`.

## Send a receipt

Open a pull request that adds one file to `receipts/<claim>/`, or open an issue with the same
content. Say whether you have any relation to the claim's author. A failed check is as welcome
as a successful one.

## Status

Started on 13 October 2026 by Dr. Alex Konviser, founder of the Gravit Open Network Foundation.
Not yet independent: see "Status and independence" on agoranet.work.

Licence: CC BY 4.0 for the texts, Apache-2.0 for any code.
