# Google Quantum AI — Verifiable Quantum Circuit Compilation

A portfolio case study documenting my participation in the Kaggle **Google Quantum AI — Verifiable Quantum Circuit Compilation** competition.

## Competition and notebook

- **Competition:** https://www.kaggle.com/competitions/google-verifiable-quantum-circuit-compilation
- **Public Kaggle notebook:** https://www.kaggle.com/code/mohamedthoufhiq/notebook0c18b2c9cf
- **Author:** Mohamed Thoufhiq

## Project overview

The competition evaluates quantum circuit compilation across three benchmark tasks:

1. **DQI** — the main implementation and optimization focus documented in this portfolio.
2. **Inverse Square Root** — included in the combined submission using the competition sample circuit.
3. **DFTHCSOS** — included in the combined submission using the supplied baseline circuit family and supporting data.

The work uses the competition's KickMix circuit tooling and official verification workflows.

## My implementation scope

My code-development work focused on the DQI benchmark. The inverse-square-root and DFTHCSOS components in the combined submission were supplied baseline artifacts that I checked with the official verifiers. They are not presented here as independent optimizations authored by me.

The public Kaggle notebook is the primary reproducibility reference. DQI source files and further implementation notes will be added to this repository after the exact source is reviewed and checked against the competition's code-sharing rules.

## Verification record

The following results were observed during verification of the combined submission:

| Benchmark | Verifier result | Verified shots |
|---|---:|---:|
| DQI | PASS | 102,400 |
| Inverse Square Root | PASS | 200,540,928 |
| DFTHCSOS | PASS | 254,464 |

These are task-verification outcomes, not claims of a prize or winning rank. At the time of the recorded Kaggle leaderboard screenshot, the submission displayed a public score of **1.00000** and a position of **3367**. Leaderboard positions can change while a competition is active.

## Repository contents

This repository is being built as a documented technical case study. The Kaggle notebook is linked above; implementation source and supporting documentation will be added after review. The competition submission ZIP is intentionally not duplicated here as a substitute for readable source code.

## Competition rules and reuse

Please review the official competition rules before reusing or redistributing code, benchmark data, or submission artifacts:

https://www.kaggle.com/competitions/google-verifiable-quantum-circuit-compilation/rules

The benchmark assets and supplied baselines remain subject to the competition's terms and applicable licenses.

## Acknowledgements

Thanks to Google Quantum AI and Kaggle for providing the benchmark tasks and verification framework.

---

**GitHub:** https://github.com/mohamedthoufhiq-cell  
**Kaggle notebook:** https://www.kaggle.com/code/mohamedthoufhiq/notebook0c18b2c9cf
