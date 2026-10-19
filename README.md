# NIA Legal Library (public documents)

The public legal documents that the Legal agent in Anveshak, a case assistant for National Investigation
Agency officers, searches when it answers and drafts: Acts, rules and orders, NIA's own publications, and
judgments of the Supreme Court and the Delhi High Court. 120 files.

**This is not an official publication of the National Investigation Agency or of any court.** Each file is a
copy from the source named against it, kept here for reference. Check the official source
before relying on a text, and note that a judgment's later history (overruled, referred, distinguished) is not
recorded here.

## What is where

```
acts/                            20  Acts
amendments/                       4  Amendment Acts
rules-orders-schedules/           9  Rules, orders and schedules
nia-publications/                10  NIA publications
judgments/supreme-court/         66  Judgments — Supreme Court
judgments/high-courts/delhi/     11  Judgments — Delhi High Court
topics/                         judgments grouped by subject
CATALOGUE.md                    every file, one line each
sources.json                    where each file came from, when, and its sha256
```

- **[CATALOGUE.md](CATALOGUE.md)** lists every document with its citation, court, bench and date.
- **Folders** split documents by type and court. A file lives in exactly one folder.
- **Topics** group judgments by subject. One judgment can appear under several.

## Topics

| Topic | Judgments |
|---|---|
| [Bail under UAPA s. 43D(5): the prima facie test](topics/bail-under-uapa.md) | 18 |
| [Long custody, speedy trial and Article 21](topics/long-custody-and-speedy-trial.md) | 20 |
| [Default bail and extension of the investigation period](topics/default-bail-and-extension.md) | 20 |
| [General principles of bail](topics/general-bail-principles.md) | 6 |
| [Parity between co-accused](topics/parity.md) | 5 |
| [Interim and medical bail](topics/interim-and-medical-bail.md) | 3 |
| [Setting aside and cancelling bail](topics/setting-aside-and-cancellation.md) | 9 |
| [Evidence: confessions and electronic records](topics/evidence.md) | 4 |
| [Sanction, prior approval, Special Courts and appeals](topics/sanction-courts-and-appeals.md) | 7 |
| [Membership of a terrorist organisation or unlawful association](topics/membership-offences.md) | 2 |
| [Citing judgments accurately](topics/citing-judgments.md) | 1 |

## Sources

| Source | Files |
|---|---|
| Supreme Court of India (e-SCR), via the Indian Supreme Court Judgments dataset by Dattam Labs (CC-BY-4.0) | 55 |
| National Investigation Agency (nia.gov.in) | 22 |
| Court copy supplied to the team | 12 |
| India Code (indiacode.gov.in) | 11 |
| Copy supplied by NIA | 7 |
| Supreme Court of India (sci.gov.in) | 4 |
| India Code consolidated text as republished by WIPO Lex | 3 |
| Delhi High Court, via the Indian High Court Judgments dataset by Dattam Labs (CC-BY-4.0) | 3 |
| verdictum.in (watermarked copy; the official copy was not located) | 1 |
| Copy supplied to the team (verdictum.in, watermarked; official copy awaited) | 1 |
| Ministry of Home Affairs (mha.gov.in), advisory of 17.10.2024 | 1 |

Supreme Court and Delhi High Court judgments marked "Dattam Labs" come from the
[Indian Supreme Court Judgments](https://registry.opendata.aws/indian-supreme-court-judgments/) and Indian High
Court Judgments open datasets (CC-BY-4.0), which mirror the courts' own copies.

Files marked "supplied" were given to the team as copies (court copies of judgments, and Acts from NIA's own
set) and have no public link; their sha256 is recorded all the same. Files marked "watermarked" are copies from
verdictum.in where the court's official copy was not located. The agent's library also holds short excerpt files
and an index with the team's notes; those are not in this repository.

## Checking a file

Each file's sha256 is in `sources.json`. To check one:

```
shasum -a 256 acts/act-uapa-1967.pdf
```

The CrPC text (`acts/act-crpc-1973.pdf`) leaves out the Second Schedule (forms); `sources.json` records the
pages kept and the sha256 of the full source.

## Suggesting a document

Open an issue at https://github.com/aaryan-sarvam/nia-legal-library/issues with the case name, citation and court (or the Act and its
number). This repository is generated from the agent's catalogue; do not edit it by hand.
