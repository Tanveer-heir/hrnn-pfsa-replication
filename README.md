# HRNN as Probabilistic Finite-State Automata — Replication

Empirical replication and extension of:
- Svete & Cotterell (2023) — Recurrent Neural Language Models as Probabilistic Finite-State Automata (EMNLP 2023)
- Svete et al. (2024) — Lower Bounds on the Expressivity of Recurrent Neural Language Models (NAACL 2024)

## What this project does
1. Implements a Weighted Finite-State Automaton (WFSA) from scratch
2. Trains an RNN to match the WFSA's probability distribution
3. Tests whether increasing precision helps represent nondeterministic automata
4. Empirically validates the theoretical hierarchy: Constant Precision < Linear Precision < CoT

## Status
🔧 In progress — started June 2026

## Papers
- Svete & Cotterell, EMNLP 2023
- Svete et al., NAACL 2024
- Nowak, Svete et al., ACL 2024
