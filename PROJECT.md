# Blueberry Pi / OUR AI — Project Brief

## Executive Summary

Blueberry Pi / OUR AI is an experimental AI research project focused on developing and evaluating a large-scale AI system with a verified 10-trillion-parameter target architecture.

The project has completed its model-architecture, training-infrastructure, data-preparation, checkpoint, and evaluation-readiness work that can be performed without large-scale external compute.

The remaining requirement is real large-scale GPU infrastructure for actual training.

## What Is Real Today?

The current genuinely trained Blueberry Pi model contains:

**10,786,944 parameters**

The larger architecture has been verified independently through live construction and exact parameter counting.

The verified 10T architecture contains:

**10,111,341,735,936 total parameters**

and:

**325,258,752,000 active parameters/token**

## What Has Not Happened Yet?

The 10T model has **not** been trained.

There are currently:

**0 real trained 10T weights**

and:

**0 external large-scale compute allocations**

This distinction is intentional. The project does not represent an architecture as a trained model.

## Technical Readiness

The project has prepared and validated infrastructure covering:

- model construction
- exact parameter counting
- MoE routing
- active-parameter verification
- data preparation
- tokenizer integration
- distributed-training preparation
- checkpoint save/load
- checkpoint integrity
- resume compatibility
- RNG restoration
- progression gates
- benchmark/evaluation infrastructure
- reproducible dry runs and testing

## Data

The currently measured data inventory is approximately:

**8.72 billion tokens**

The project uses:

**bpe-500k-v1**

with exactly:

**500,000 vocabulary entries**

Additional data expansion procedures are documented for the eventual large-scale training budget.

## Training Roadmap

The planned progression is:

200M  
→ 1B  
→ 3B  
→ 5B  
→ 7B  
→ 9B  
→ 100B  
→ 1T  
→ 5T  
→ 10T

Each progression stage is intended to produce a real trained checkpoint and measurable evaluation evidence.

## Initial Compute Requirement

The first large-scale milestone is:

**8× NVIDIA H100 80GB-class GPUs, or objectively equivalent infrastructure**

The purpose of this initial allocation is to execute the bp-200m training stage and establish a real large-scale training result.

## Sponsorship Objective

The project is seeking legitimate external GPU/cloud sponsorship.

The desired structure is:

**Blueberry Pi / OUR AI:** project ownership retained by the project owner

**Sponsor:** provides or directly covers GPU/cloud infrastructure

**Owner out-of-pocket compute cost:** $0

The project does not seek to create personal cloud debt, billing liability, or hidden infrastructure charges for the owner.

## Why Sponsor?

A sponsor would enable a technically prepared project to move from verified architecture and infrastructure into actual large-scale training.

The project is designed around:

- reproducibility
- transparent reporting
- measurable milestones
- checkpoint integrity
- explicit capability evaluation
- separation of verified facts from future goals

## Transparency Standard

Blueberry Pi does not claim:

- a completed 10T training run
- a trained 10T model
- 5T trained tokens
- frontier benchmark results
- performance beyond another AI system without measured evidence

Current claims are limited to what has actually been verified.

## Project Status

**ENGINEERING READY**

**TRAINING-READY**

**SPONSORSHIP READY**

**BLOCKED_EXTERNAL_RESOURCE**

## Learn More

See:

- `README.md` — project overview
- `SPONSORSHIP.md` — compute sponsorship request
- `CONTACT.md` — sponsorship contact path
- GitHub Discussions — public project and sponsorship discussion

---

Blueberry Pi / OUR AI is currently seeking the external compute required to begin real large-scale training.
