# Verification

Measured results for Hospitality.

Every figure came from running the software while the data room was prepared. None of it is copied
out of a document, and each figure is reproducible by a buyer from the delivered files.

---

## Results

| Measure | Value |
|---|---|
| Unit tests passing | 62 |
| End-to-end tests passing | 13, against the real built applications |
| Tests failing | 0 |
| Type checks passing | 2 of 2 |
| Builds passing | 2 of 2, from the delivered files alone |
| Installers | 3, including one portable build |
| Copyleft dependencies | 0, across 668 packages |

## Worth knowing

One disclosed issue: an end-to-end command failed with “no tests found”, which a buyer running it would hit. The data room records it. Hospitality OS's coverage was materially strengthened during preparation.

## How this was produced

The software was run from the delivered files. Where a product ships with an installer, the
installer was built. Where a product declares a type check or a build step, both were run. Test
counts are the totals reported by the products' own test commands.

## What is not claimed

A verification record that lists only passes is not a verification record. The package's
open-items document lists every known gap, and it is part of the data room rather than something
a buyer has to discover. Where a test command did not run, where a path went unexercised, or
where behaviour at scale is unproven, the data room says so plainly.

That document is available under a signed non-disclosure agreement, together with the full
verification record and the provenance file. See [ACQUISITION.md](ACQUISITION.md).
