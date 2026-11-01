# ChestPainBench

**Evaluating LVLMs for Multimodal Clinical Reasoning in Chest Pain**

[Project page](https://qilegu.github.io/ChestPainBench/)

ChestPainBench is a case-level benchmark for evaluating large vision-language models in clinically grounded chest pain scenarios. It brings together coronary angiography, chest radiographs, ECG waveforms, ECG reports, and diagnostic reports from the same patient, allowing models to be assessed on both structured questions and open-ended clinical reasoning.

## Benchmark

- 312 patient-level cases
- Five matched clinical evidence sources
- 1,248 multiple-choice questions
- 2,496 open-ended questions
- Five clinical task categories, from modality recognition to treatment recommendation
- Nine general-purpose, medically specialized, and proprietary LVLMs

## Evaluation

Multiple-choice responses are evaluated by accuracy. Open-ended responses are evaluated using F1, ROUGE-L, BLEU-4, and a reference-guided rubric covering clinical correctness, completeness, reasoning coherence, safety, and overall quality. Single-modality ablations measure model sensitivity to coronary angiography, ECG waveforms, chest radiographs, and textual reports.

## Main findings

- Strong multiple-choice performance does not consistently translate into strong open-ended clinical reasoning.
- Treatment recommendation is the most challenging task category across model families.
- Medical specialization does not provide a uniform performance advantage.
- Removing textual reports causes substantially greater degradation than removing any individual image or waveform modality.

## Citation

Qile Gu, Hongyi Miao, Wenmiao Wang, Zhanyi Yan, Yunfei Zhao, and Shuai He. *ChestPainBench: Evaluating LVLMs for Multimodal Clinical Reasoning in Chest Pain.* Manuscript, 2026.

## Data availability

Patient-level clinical data are not publicly distributed because of privacy, ethical, and institutional restrictions.
