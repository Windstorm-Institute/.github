# Windstorm Institute

**Theoretical and experimental research on the mathematical constraints &mdash; information-theoretic and thermodynamic &mdash; that govern what physical systems can do, across substrates.**

Led by Grant Lavell Whitmer III &middot; Fort Ann, NY

> Two research programs. Thirteen papers. Track 1 (complete arc): the throughput basin in serial decoders, from ribosomes to AI transformers. Track 2 (active line of inquiry): non-equilibrium entropic bounds in analog gravity systems.

---

## Track 1 &mdash; The Throughput Basin (Papers 1&ndash;9, complete arc)

| # | Paper | Key Finding | DOI | Code Mirror |
|---|-------|-------------|-----|-------------|
| 1 | [The Fons Constraint](https://github.com/Windstorm-Institute/fons-constraint) | 64-codon alphabet derivation | [10.5281/zenodo.19274048](https://doi.org/10.5281/zenodo.19274048) | [Labs](https://github.com/Windstorm-Labs/fons-constraint) |
| 2 | [The Receiver-Limited Floor](https://github.com/Windstorm-Institute/receiver-limited-floor) | Vocab-independent BPT (1,749 models, *p* = 0.643) | [10.5281/zenodo.19322973](https://doi.org/10.5281/zenodo.19322973) | [Labs](https://github.com/Windstorm-Labs/receiver-limited-floor) |
| 3 | [The Throughput Basin](https://github.com/Windstorm-Institute/throughput-basin) | 31-system convergence to [3,6] bits | [10.5281/zenodo.19323194](https://doi.org/10.5281/zenodo.19323194) | [Labs](https://github.com/Windstorm-Labs/throughput-basin) |
| 4 | [The Serial Decoding Basin τ](https://github.com/Windstorm-Institute/serial-decoding-basin) | τ = 4.16 ± 0.19 bits | [10.5281/zenodo.19323423](https://doi.org/10.5281/zenodo.19323423) | [Labs](https://github.com/Windstorm-Labs/serial-decoding-basin) |
| 5 | [The Dissipative Decoder](https://github.com/Windstorm-Institute/dissipative-decoder) | Regime A/B; ribosome at φ ≈ 1.02; silicon ~10⁹× above Landauer (useful-dissipation) | [10.5281/zenodo.19433048](https://doi.org/10.5281/zenodo.19433048) | [Labs](https://github.com/Windstorm-Labs/dissipative-decoder) |
| 6 | [The Inherited Constraint](https://github.com/Windstorm-Institute/inherited-constraint) | AI inherits ~4.4 BPT from biological language | [10.5281/zenodo.19432911](https://doi.org/10.5281/zenodo.19432911) | [Labs](https://github.com/Windstorm-Labs/inherited-constraint) |
| 7 | [The Throughput Basin Origin](https://github.com/Windstorm-Institute/throughput-basin-origin) | At 92M, on Markov synthetic data, achieved BPT tracks training-corpus token entropy. **Published with internal adversarial review.** | [10.5281/zenodo.19498582](https://doi.org/10.5281/zenodo.19498582) | [Labs](https://github.com/Windstorm-Labs/throughput-basin-origin) |
| 8 | [The Vision Basin](https://github.com/Windstorm-Institute/vision-basin) | Cross-modal throughput: language, vision, audio. 12 models, real LJ Speech. | [10.5281/zenodo.19672827](https://doi.org/10.5281/zenodo.19672827) | [Labs](https://github.com/Windstorm-Labs/vision-basin) |
| 9 | [The Hardware Basin](https://github.com/Windstorm-Institute/hardware-basin) | Quantization cliff is about level allocation, not bit count. NF4 vs symmetric. | [10.5281/zenodo.19672921](https://doi.org/10.5281/zenodo.19672921) | [Labs](https://github.com/Windstorm-Labs/hardware-basin) |

> **Note on Paper 7:** Published with its full internal adversarial review, which identifies items that constrain how strongly the headline can be read. Read the [adversarial review](https://github.com/Windstorm-Institute/throughput-basin-origin/blob/main/review/adversarial_review.md) and the [companion article](https://windstorminstitute.org/articles/throughput-basin-origin.html) as a unit.

> **Note on Papers 1–4 retroactively:** the τ = 4.16 figure is in bits per BPE token. The same tokenizer-unit confound the adversarial review identifies for Paper 7's SYN-8 result applies to the τ measurement as well. A bits-per-source-symbol re-measurement is now in scope for Paper 7.1. See the [callout in the τ article](https://windstorminstitute.org/articles/serial-decoding-basin.html).

---

## Track 2 &mdash; Entropic Bounds in Analog Systems (Papers 10&ndash;13, line of inquiry active)

Track 2 applies the same Clausius-inequality / entropy-production lens that drives Track 1's thermodynamic argument to a different substrate &mdash; gravity-adjacent physical systems. Four papers as of May 2026: a narrow falsifiable laboratory prediction (Paper 10), a broad interpretive synthesis (Paper 11), a methodology case study on a candidate extension that turned out to be a 1981 result in disguise (Paper 12), and a direct lattice-QFT test that falsifies the literal bipartition-entropy reading of the framework's static identification while showing partial survival of the modular-Hamiltonian reading in 1+1D (Paper 13).

| # | Paper | Key Finding | DOI | Code Mirror |
|---|-------|-------------|-----|-------------|
| 10 | [The Phonon Bound](https://github.com/Windstorm-Institute/phonon-extraction-bound) | BEC analog gravity: η ≤ 1/(1 + T/T<sub>res</sub>) ⇒ predicted **17% efficiency suppression** at T/T<sub>res</sub> = 0.2; 5-test QuTiP Lindblad validation, 1 clean scope limit | [10.5281/zenodo.20014391](https://doi.org/10.5281/zenodo.20014391) | [Labs](https://github.com/Windstorm-Labs/phonon-extraction-bound) |
| 11 | [Gravitational Entropy Escrow](https://github.com/Windstorm-Institute/gravitational-entropy-escrow) | The universe attracts because the books want to balance. Newton, Bekenstein–Hawking, equivalence principle, and Milgrom *a*<sub>0</sub> as facets of one principle. Genzel five-case test rules out evolving *a*<sub>0</sub> at >0.10 dex. | [10.5281/zenodo.20032023](https://doi.org/10.5281/zenodo.20032023) | [Labs](https://github.com/Windstorm-Labs/gravitational-entropy-escrow) |
| 12 | [C8 Clarification Note](https://github.com/Windstorm-Institute/c8-clarification-note) | Multi-LLM-proposed entropy 4-current "C8" reduces to saturated Bekenstein 1981; methodology case study on multi-LLM adversarial review, dimensional analysis traps, and reality-checks against published values. Companion to Paper 11. | [10.5281/zenodo.20041992](https://doi.org/10.5281/zenodo.20041992) | [Labs](https://github.com/Windstorm-Labs/c8-clarification-note) |
| 13 | [Lattice QFT Test of the Static Escrow Postulate](https://github.com/Windstorm-Institute/lattice-qft-test) | Direct lattice-QFT test of the framework's load-bearing static identification *S*<sub>esc</sub> = \|*U*<sub>grav</sub>\|/*T*<sub>Unruh</sub>. Bipartition-entropy reading falsified in both 1+1D (R spans 10⁵⁶) and 3+1D (R<sub>Δ</sub> &lt; 10⁻³, MI decays as L⁻⁴). Modular-Hamiltonian reading partially survives in 1+1D in a small-d<sub>1</sub> window with prefactor ≈ 1/30; previously-published "L^{0.7}" sublinear fit corrected to a regime-dependent crossover. Companion 3+1D paper finds non-recovery of BW asymptote within resolvable d<sub>1</sub>. Horizon-limit recoveries (Bekenstein–Hawking via surface gravity) independent of these tests. Supplement to Paper 11. | [10.5281/zenodo.20043421](https://doi.org/10.5281/zenodo.20043421) | [Labs](https://github.com/Windstorm-Labs/lattice-qft-test) |

> **Track 2 scope note.** This line opens with a falsifiable lab prediction and a broad framing; the cluster-cores difficulty (Paper 11 §8.2) is a real open problem, and the order-unity coefficient α ≈ 1.34 (Paper 11 §8.4.3) awaits a matched-asymptotic Rindler–de Sitter derivation. Paper 12 documents one candidate covariant extension that didn't pan out, and the AI-dialogue methodology lessons that came out of working it through.

---

## Discussion & engagement

Different conversation types belong on different surfaces:

- **Discuss the *ideas* in a paper** → comments at the bottom of the [website article](https://windstorminstitute.org) for that paper. Powered by GitHub Discussions on the website repo; sign in with GitHub to comment.
- **Typo, citation issue, or paper-content correction?** → Open an Issue on the relevant Institute repo above (each paper has a dedicated repo).
- **Bug in the analysis code, or a reproduction question?** → Open an Issue on the corresponding Labs repo above.
- **Q&A — version compatibility, hardware, generalization to other inputs?** → Start a Discussion on the Labs repo (Discussions are enabled on all 12 Labs repos as of May 2026).
- **Watch the whole fleet at once.** Click "Watch" on the [Windstorm-Institute](https://github.com/Windstorm-Institute) and [Windstorm-Labs](https://github.com/Windstorm-Labs) org pages to get notifications across all 26 paper repos.

---

## About

The Windstorm Institute investigates whether fundamental limits constrain information processing and energy/entropy bookkeeping across substrates &mdash; from molecular biology to artificial intelligence to analog gravity systems.

- **Website:** [windstorminstitute.org](https://windstorminstitute.org)
- **Zenodo Community:** [zenodo.org/communities/windstorm-institute](https://zenodo.org/communities/windstorm-institute/)

## Where things live

| Org | Purpose |
|-----|---------|
| [Windstorm-Institute](https://github.com/Windstorm-Institute) | Manuscripts, theory, paper publication repositories (13 repos) |
| [Windstorm-Labs](https://github.com/Windstorm-Labs) | Experiment code, raw outputs, plots, reproducibility (13 repos, mirrored 1:1 with Institute) |
| [sneakyfree/windstorm-institute-site](https://github.com/sneakyfree/windstorm-institute-site) | Website source. Discussions on this repo back the article-comment widgets via Giscus. |

---

*Papers: CC BY 4.0 · Code: MIT*
