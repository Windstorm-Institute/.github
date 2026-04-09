# Windstorm Institute

**Theoretical and experimental research on information-theoretic constraints in self-replicating and serial decoding systems.**

Led by Grant Lavell Whitmer III &middot; Fort Ann, NY

---

## The FONS Constraint / Throughput Basin Series

| # | Paper | Key Finding | DOI | Code Mirror |
|---|-------|-------------|-----|-------------|
| 1 | [The Fons Constraint](https://github.com/Windstorm-Institute/fons-constraint) | 64-codon alphabet derivation | [10.5281/zenodo.19274048](https://doi.org/10.5281/zenodo.19274048) | [Labs](https://github.com/WIndstorm-Labs/fons-constraint) |
| 2 | [The Receiver-Limited Floor](https://github.com/Windstorm-Institute/receiver-limited-floor) | Vocab-independent BPT (1,749 models, *p* = 0.643) | [10.5281/zenodo.19322973](https://doi.org/10.5281/zenodo.19322973) | [Labs](https://github.com/WIndstorm-Labs/receiver-limited-floor) |
| 3 | [The Throughput Basin](https://github.com/Windstorm-Institute/throughput-basin) | 31-system convergence to [3,6] bits | [10.5281/zenodo.19323194](https://doi.org/10.5281/zenodo.19323194) | [Labs](https://github.com/WIndstorm-Labs/throughput-basin) |
| 4 | [The Serial Decoding Basin τ](https://github.com/Windstorm-Institute/serial-decoding-basin) | τ = 4.16 ± 0.19 bits | [10.5281/zenodo.19323423](https://doi.org/10.5281/zenodo.19323423) | [Labs](https://github.com/WIndstorm-Labs/serial-decoding-basin) |
| 5 | [The Dissipative Decoder](https://github.com/Windstorm-Institute/dissipative-decoder) | Regime A/B; ribosome at φ ≈ 1.02; silicon ~10⁹× above Landauer (useful-dissipation) | [10.5281/zenodo.19433048](https://doi.org/10.5281/zenodo.19433048) | [Labs](https://github.com/WIndstorm-Labs/dissipative-decoder) |
| 6 | [The Inherited Constraint](https://github.com/Windstorm-Institute/inherited-constraint) | AI inherits ~4.4 BPT from biological language | [10.5281/zenodo.19432911](https://doi.org/10.5281/zenodo.19432911) | [Labs](https://github.com/WIndstorm-Labs/inherited-constraint) |
| 7 | [The Throughput Basin Origin](https://github.com/sneakyfree/agi-extensions) | At 92M, on Markov synthetic data, achieved BPT tracks training-corpus token entropy. **Published with internal adversarial review.** | 🟡 Preprint — Zenodo pending [Paper 7.1](https://github.com/sneakyfree/agi-extensions/issues/1) | [Labs](https://github.com/WIndstorm-Labs/agi-extensions) |

> **Note on Paper 7:** the canonical repository is `sneakyfree/agi-extensions`, not the Institute mirror. The paper is published together with its full internal adversarial review, which identifies four blocking items (see Paper 7.1 tracking issue) that constrain how strongly the headline can be read. The defensible claim is narrower than the original; read the [adversarial review](https://github.com/sneakyfree/agi-extensions/blob/main/review/adversarial_review.md) and the [companion article](https://windstorminstitute.org/articles/throughput-basin-origin.html) as a unit.

> **Note on Papers 1–4 retroactively:** the τ = 4.16 figure is in bits per BPE token. The same tokenizer-unit confound the adversarial review identifies for Paper 7's SYN-8 result applies to the τ measurement as well. A bits-per-source-symbol re-measurement is now in scope for Paper 7.1. See the [callout in the τ article](https://windstorminstitute.org/articles/serial-decoding-basin.html).

---

## About

The Windstorm Institute investigates whether fundamental limits constrain information processing across substrates &mdash; from molecular biology to artificial intelligence.

- **Website:** [windstorminstitute.org](https://windstorminstitute.org)
- **Zenodo Community:** [zenodo.org/communities/windstorm-institute](https://zenodo.org/communities/windstorm-institute/)

## Where things live

| Org | Purpose |
|-----|---------|
| [Windstorm-Institute](https://github.com/Windstorm-Institute) | Manuscripts, theory, paper repositories |
| [WIndstorm-Labs](https://github.com/WIndstorm-Labs) | Experiment code, GPU benchmarks, reproducibility (note: typo `WI` in slug; correctly-cased mirror planned) |
| [sneakyfree](https://github.com/sneakyfree) | PI's working repos &mdash; canonical Paper 7 (`agi-extensions`), website source (`windstorminstitute.org`) |

---

*Papers: CC BY 4.0 · Code: MIT*
