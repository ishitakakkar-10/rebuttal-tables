# Table 1: Pattern Outcomes Across Models

Distribution of safety-failure patterns across models. Final answer safety outcome are determined using LlamaGuard classifications of the final answer.
- **Unsafe:** Final answer classified as unsafe.
- **Hidden Harm:** The reasoning trace contains harmful content, but the final answer is classified as safe.

## Unsafe Final Answers

| Pattern | QwQ | ot-7B | r1-32b | r1-8b |
|----------|----:|------:|-------:|------:|
| Direct | 12 | 50 | 37 | 60 |
| Post-hoc | 39 | 98 | 33 | 135 |
| Gateway | 0 | 28 | 7 | 14 |
| **Total** | **51** | **176** | **77** | **209** |

## Hidden-Harm Cases

| Pattern | QwQ | ot-7B | r1-32b | r1-8b |
|----------|----:|------:|-------:|------:|
| Direct | 32 | 79 | 84 | 58 |
| Post-hoc | 52 | 39 | 38 | 47 |
| Gateway | 5 | 32 | 14 | 5 |
| **Total** | **89** | **150** | **136** | **110** |
