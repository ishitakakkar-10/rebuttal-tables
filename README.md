# HarmThoughts Rebuttal Materials

This repository contains supplementary tables referenced in the rebuttal for the HarmThoughts submission.

## Contents

| File | Description |
|--------|-------------|
| `table1_failure_patterns.md` | Distribution of safety failure patterns across models, including unsafe final answers (U) and hidden-harm cases (H). |
| `table2_per_class_results.md` | Per-class performance of the fine-tuned classifier on the HarmThoughts test set. |
| `table3_trace_length_results.md` | Sentence-level detection performance stratified by reasoning-trace length. |

## Notes

- All classifier metrics are computed on the held-out HarmThoughts test set.
- Table 2 reports sentence-level classification performance for each behavior category.
- Table 3 evaluates whether performance varies across traces of different lengths.
- For Table 1, unsafe (U) and hidden-harm (H) outcomes are determined using LlamaGuard classifications of the final answer.

This repository is provided solely to support the anonymous review process.
