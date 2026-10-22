# Judgments

84 judgments and orders: 71 of the Supreme Court in [supreme-court/](supreme-court/), 12 of the
Delhi High Court in [high-courts/delhi/](high-courts/delhi/) and 1 of the Bombay High Court in
[high-courts/bombay/](high-courts/bombay/).

## Reading a file name

`sc-2019-watali.pdf` is the court, the year of the judgment, and a short name for the case.

| Prefix | Court |
|---|---|
| `sc-` | Supreme Court of India |
| `dhc-` | Delhi High Court |
| `bhc-` | Bombay High Court |

Some names add what the document is, for example `-reference-order`. The full case name, citation, bench and date
of every file are in [CATALOGUE.md](../CATALOGUE.md). The same judgments grouped by subject are in
[judgments-by-topic/](../judgments-by-topic/).

## Where the copies come from

| Source | Files |
|---|---|
| Supreme Court of India (e-SCR), via the Indian Supreme Court Judgments dataset by Dattam Labs (CC-BY-4.0) | 57 |
| Court copy supplied to the team | 12 |
| Supreme Court of India (sci.gov.in) | 5 |
| Delhi High Court, via the Indian High Court Judgments dataset by Dattam Labs (CC-BY-4.0) | 3 |
| The court's own PDF, as hosted by livelaw.in | 2 |
| verdictum.in (watermarked copy; the official copy was not located) | 1 |
| Copy supplied to the team (verdictum.in, watermarked; official copy awaited) | 1 |
| Ministry of Home Affairs (mha.gov.in), advisory of 17.10.2024 | 1 |
| Delhi High Court (delhihighcourt.nic.in) | 1 |
| The Supreme Court's signed record, as hosted by sabrangindia.in | 1 |

- **Dattam Labs datasets:** open copies (CC-BY-4.0) of the courts' own judgments; the Supreme Court ones are the
  e-SCR (Supreme Court Reports) text.
- **Court copy supplied to the team:** a copy given to the team, with no public link. Its sha256 is in
  [sources.json](../sources.json) all the same.
- **As hosted by livelaw.in or sabrangindia.in:** the court's own PDF (its neutral-citation stamp or digital
  signature is on it), taken from a legal news site because the court's site gives no stable link.
- **Watermarked:** a copy from verdictum.in, used where the court's official copy was not located. Check a passage
  against the official copy before quoting it.

A judgment's later history (overruled, referred to a larger bench, distinguished) is not recorded here.
