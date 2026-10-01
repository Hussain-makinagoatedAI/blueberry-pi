# Blueberry Pi / OUR AI — Compute Sponsorship

## Overview

Blueberry Pi / OUR AI is an experimental AI research project with a verified 10-trillion-parameter target architecture and a training infrastructure prepared for progressive large-scale training.

The project's current genuinely trained model contains **10,786,944 parameters**.

The 10-trillion-parameter architecture has been verified, but the 10T model has **not** yet been trained.

## Current Verified State

| Item | Current State |
|---|---|
| Real trained model | 10,786,944 parameters |
| 10T architecture | VERIFIED |
| 10T total parameters | 10,111,341,735,936 |
| 10T active parameters/token | 325,258,752,000 |
| 10T trained weights | NOT YET CREATED |
| Measured data inventory | ~8.72B tokens |
| Tokenizer | bpe-500k-v1 (500,000 vocabulary) |
| External compute | 0 allocations |
| Project state | TRAINING-READY / BLOCKED_EXTERNAL_RESOURCE |

## Why External Compute Is Needed

The verified 10T architecture requires large-scale distributed GPU infrastructure that is beyond the project's current local development hardware.

The project is therefore seeking legitimate external compute through sponsorship, donated infrastructure, research support, or other no-liability arrangements.

## Initial Compute Milestone

The first target is the verified **bp-200m** training stage.

### Initial Target

**8× NVIDIA H100 80GB-class GPUs**, or objectively equivalent infrastructure capable of executing the documented training configuration.

The initial milestone is intended to establish the first real large-scale trained checkpoint and measured evaluation results before progressively scaling the model.

## Planned Training Progression

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
