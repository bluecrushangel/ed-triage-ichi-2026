# Paper Title

Accepted at IEEE ICHI 2026

**Authors:** KMA Solaiman, Joshua Sebastian, Karma Tobden

## Abstract

Emergency triage decisions are often made under severe information constraints. However, most data-driven deterioration models are evaluated using signals that are not available during initial patient assessment.

In this work, we present a **leakage-aware benchmarking framework** for early deterioration prediction, designed to evaluate model performance under realistic, time-limited sensing conditions.

Using a patient-deduplicated cohort derived from MIMIC-IV-ED, we compare:
- **Hospital-rich triage settings**, and  
- A **vitals-only, MCI-like scenario**, where inputs are restricted to information available within the first hour of presentation.

Across multiple modeling approaches, we find that predictive performance declines only modestly when limited to vitals. This suggests that early physiological measurements retain substantial clinical signal.

Through structured ablation and interpretability analyses, we identify:
- **Respiratory signals** and  
- **Oxygenation measures**  

as the most influential contributors to early risk stratification. Models also exhibit **stable, graceful degradation** as sensing availability is reduced.

This work provides a clinically grounded benchmark to support the evaluation and design of **deployable triage decision support systems**, particularly in resource-constrained environments.

## Manuscript
[Download the accepted manuscript](./ICHI2026_accepted_manuscript.pdf)

## Note
This repository hosts the accepted manuscript version of the paper. The final published version will appear in IEEE Xplore.
