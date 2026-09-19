# dsml-mlsec-labs

> ML Security labs — adversarial attacks, membership inference, model stealing, data poisoning

**16 projects** from a 182-project DS/ML roadmap.

## What this repo is

A monorepo of short lab projects, one folder per project. The goal is coverage and fluency, not
production polish.

## Projects

### Beginner (5)

| # | Project | Status |
|---|---|---|
| 163 | Adversarial Example Generator (FGSM) | Not started |
| 164 | Model Stealing via Query Access | Not started |
| 165 | Membership Inference Attack Demo | Not started |
| 166 | Data Poisoning Attack Demo | Not started |
| 167 | Authenticated Model-Serving API | Not started |

### Intermediate (3)

| # | Project | Status |
|---|---|---|
| 169 | Model Watermarking for IP Protection | Not started |
| 171 | Model & Dataset Signing/Provenance | Not started |
| 172 | Encrypted Model-at-Rest & Secrets Management | Not started |

### Advanced (5)

| # | Project | Status |
|---|---|---|
| 173 | Certified Robustness Evaluation | Not started |
| 174 | Query Pattern Detection for Model-Extraction Defense | Not started |
| 175 | Privacy Budget Tracking Across Multiple Queries | Not started |
| 176 | Dependency & Pretrained-Model Vulnerability Scanner | Not started |
| 177 | Confidential Inference with a Trusted Execution Environment | Not started |

### Expert (3)

| # | Project | Status |
|---|---|---|
| 178 | Robust ML Pipeline for Production | Not started |
| 179 | Model Fingerprinting & Provenance Verification Platform | Not started |
| 180 | Federated Learning with Privacy Guarantees | Not started |

Update the **Status** column as projects are completed.

## Layout

One folder per project, prefixed with its roadmap number so it stays traceable:

```
dsml-mlsec-labs/
  163-<project-name>/
    notebooks/
    src/
    README.md
  ...
```

## Conventions

- Each project folder gets a short README: what it does, how to run it, what was learned.
- Datasets and model artifacts are gitignored — document how to obtain or regenerate them instead.
