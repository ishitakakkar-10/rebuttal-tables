# Table 2: Per-Class Sentence-Level Classification Performance
Per-class sentence-level classification performance (using fine-tuned Llama-3.2-3B) on the HarmThoughts test set.

| Behavior | Support | Acc | F1 | AUPRC |
|-----------|--------:|----:|----:|------:|
| PA: Persona Adoption | 55 | 0.436 | 0.400 | 0.337 |
| RS: Refusal Suppression | 60 | 0.483 | 0.475 | 0.425 |
| CC: Compliance Check | 79 | 0.835 | 0.786 | 0.837 |
| PS: Performative Safety | 136 | 0.596 | 0.628 | 0.633 |
| CR: Constraint Reframing | 139 | 0.367 | 0.486 | 0.479 |
| ED: Ethical Deliberation | 177 | 0.576 | 0.669 | 0.726 |
| IR: Intent Rationalization | 187 | 0.390 | 0.479 | 0.472 |
| AL: Safe Alternative | 191 | 0.539 | 0.608 | 0.636 |
| HV: Harmful Verification | 333 | 0.492 | 0.609 | 0.695 |
| OB: Obfuscation | 340 | 0.629 | 0.699 | 0.765 |
| RA: Risk Acknowledgment | 564 | 0.697 | 0.729 | 0.737 |
| CE: Challenge Engineering | 566 | 0.564 | 0.641 | 0.693 |
| FL: Filler Sentences | 815 | 0.618 | 0.686 | 0.731 |
| IA: Intent Assessment | 1588 | 0.790 | 0.778 | 0.828 |
| TD: Task Decomposition | 1616 | 0.748 | 0.780 | 0.863 |
| DKE: Domain Knowledge Synthesis | 4455 | 0.929 | 0.848 | 0.929 |

