# Unique Prototype Algorithm

## Algorithm

**HuangCausalTrustworthyMlRankAgent** (`P047-Huang-TrustworthyMl`)

## Professor Alignment

- Professor: Furong Huang
- Research area: Trustworthy ML, RL, generative AI, high-dimensional statistics
- Focus terms: Trustworthy ML, RL, generative AI, high dimensional statistics

## Core Mechanism

This prototype prioritizes severe open violations and repair regressions for red-team follow-up.

## Decision Rule

Rank seed cases by trustworthy-specific priority score with Huang-aligned focus term 'Trustworthy ML'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `trustworthy` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Furong Huang's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
