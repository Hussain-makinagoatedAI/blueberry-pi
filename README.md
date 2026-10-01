# Blueberry Pi / OUR AI

A technically verified AI research project targeting a 10-trillion-parameter architecture.

## Current Status

**Project state:** TRAINING-READY / BLOCKED_EXTERNAL_RESOURCE

| Item | Verified State |
|---|---|
| Real trained model | 10,786,944 parameters |
| 10T architecture | VERIFIED |
| 10T total parameters | 10,111,341,735,936 |
| 10T active parameters/token | 325,258,752,000 |
| 10T trained weights | NOT YET CREATED |
| Measured data inventory | ~8.72B tokens |
| Tokenizer | bpe-500k-v1 (500,000 vocabulary) |
| External compute | 0 allocations |
| Initial compute target | 8× H100 80GB-class |
| Owner compute cost | $0 |

> **Important:** The verified 10T architecture must not be confused with a trained 10T model. The current trained model contains 10,786,944 parameters. Real 10T trained weights require large-scale external compute.

## What Is Blueberry Pi?

Blueberry Pi / OUR AI is an experimental AI project focused on building and evaluating a highly capable large-scale model and its supporting training, evaluation, and agent infrastructure.

The project is being developed with an emphasis on reproducibility, verification, checkpoint integrity, transparent evaluation, and strict separation between configured architecture and genuinely trained weights.

## What Has Been Completed

- Verified 10T architecture
- Exact parameter-count verification
- MoE routing and active-parameter verification
- 500,000-token vocabulary
- Large-scale data preparation and provenance tracking
- Training and checkpoint infrastructure
- Resume and integrity protections
- Distributed training preparation
- Benchmark/evaluation infrastructure
- Reproducible local and dry-run validation
- Training progression from 200M through the 10T target

## Current Trained Baseline

The current genuinely trained Blueberry Pi model contains:

**10,786,944 parameters**

This baseline is preserved and SHA-pinned.

All larger model stages are currently architecture/configuration targets and have **not** been represented as trained models.

## 10T Architecture

The verified target architecture contains exactly:

**10,111,341,735,936 total parameters**

with:

**325,258,752,000 active parameters per token**

The architecture has been live-constructed and independently parameter-count verified.

## Data & Tokenizer

The current measured data inventory contains approximately:

**8.72 billion tokens**

The project uses the frozen:

**bpe-500k-v1**

tokenizer with exactly **500,000 vocabulary entries**.

The data pipeline includes deduplication, contamination screening, domain balancing, provenance tracking, and SHA-verified manifests.

## Training Infrastructure

The project has prepared infrastructure for:

- distributed training
- MoE routing
- checkpoint save/load
- checkpoint integrity verification
- resume compatibility
- RNG restoration
- training gates
- progression control
- utilization monitoring
- reproducible evaluation

The first large-scale training milestone is the **bp-200m** stage.

## Evaluation

The project includes a benchmark/evaluation system with:

- version and provenance controls
- adapter contracts
- contamination safeguards
- reproducible evaluation workflows
- the project's preserved external benchmark registry

External frontier benchmark results have **not** been fabricated or claimed.

## Training Roadmap

```text
200M
  ↓
1B
  ↓
3B
  ↓
5B
  ↓
7B
  ↓
9B
  ↓
100B
  ↓
1T
  ↓
5T
  ↓
10T
