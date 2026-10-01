# Blueberry Pi / OUR AI

A technically verified AI research project targeting a 10-trillion-parameter architecture.

## Quick Links

- [Project Brief](PROJECT.md) — project overview, technical readiness, and roadmap
- [Compute Sponsorship](SPONSORSHIP.md) — compute sponsorship requirements and ownership structure
- [Contact](CONTACT.md) — sponsorship discussion and contact path
- [GitHub Discussions](../../discussions) — public project and sponsorship discussion

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

> **Important:** The verified 10T architecture must not be confused with a trained 10T model. The current genuinely trained model contains 10,786,944 parameters. Real 10T trained weights require large-scale external compute.

## What Is Blueberry Pi?

Blueberry Pi / OUR AI is an experimental AI research project focused on developing and evaluating a highly capable large-scale AI system and the infrastructure required to train, evaluate, and scale it.

The project emphasizes:

- reproducibility
- transparent reporting
- checkpoint integrity
- measurable evaluation
- data provenance
- explicit separation between architecture and trained weights

## What Has Been Completed

The project has completed substantial engineering and readiness work, including:

- verified large-scale model architectures
- exact parameter-count verification
- MoE routing and active-parameter verification
- training infrastructure
- checkpoint save/load and integrity protections
- resume compatibility
- RNG restoration
- distributed-training preparation
- data preparation and provenance tracking
- tokenizer development and evaluation
- benchmark/evaluation infrastructure
- progression gates
- reproducible local validation
- dry-run training progression
- sponsorship and compute-acquisition documentation

## Current Trained Baseline

The current genuinely trained Blueberry Pi model contains:

**10,786,944 parameters**

This baseline is preserved and SHA-pinned.

Larger model stages are currently architecture/configuration targets and have not been represented as trained models.

## Verified 10T Architecture

The target 10T architecture has been live-constructed and exactly parameter-count verified.

### Total Parameters

**10,111,341,735,936**

### Active Parameters per Token

**325,258,752,000**

The architecture includes the project's large-scale MoE configuration and is intended for distributed training on external GPU infrastructure.

## Data & Tokenizer

The currently measured data inventory contains approximately:

**8.72 billion tokens**

The project uses the frozen:

**bpe-500k-v1**

tokenizer with exactly:

**500,000 vocabulary entries**

The data pipeline includes documented deduplication, contamination screening, domain balancing, provenance tracking, and SHA-verified manifests.

The current 8.72B-token inventory is **not** being represented as the eventual 5T-token training supply.

## Training Infrastructure

The project has prepared infrastructure for:

- distributed training
- mixture-of-experts routing
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

The project includes a benchmark and evaluation system with:

- benchmark registry
- version and provenance controls
- evaluation adapters
- contamination safeguards
- reproducible evaluation workflows
- checkpoint-based comparisons

External benchmark results are not claimed unless they have actually been measured.

## Training Roadmap

The planned progression is:

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
