# HACP

Official implementation of:

**Mitigating Object Hallucinations in Vision-Language Models via
Head-Level Attribution and Counteractive Pruning**

*Findings of EMNLP 2026*

> 🚧 Code release is in progress. The implementation, evaluation scripts,
> and reproduction instructions will be released in this repository.

## Abstract

Large vision-language models (LVLMs) excel at multimodal tasks but often generate instance-level object hallucinations, describing nonexistent objects. Yet most mitigation strategies rely on output-level or coarse-grained interventions, limiting their ability to identify and selectively regulate attention heads associated with faithful versus hallucinatory generation, often at the cost of descriptive coverage. To address this limitation, we propose HACP, a training-free framework that integrates head-level semantic attribution with instance-adaptive counteractive pruning. HACP introduces InfoSpectralScore to summarize spectral changes in head-perturbed representations and identify heads associated with hallucination or grounded generation, which are then selectively suppressed or reinforced during decoding. Across multiple LVLMs and benchmarks, HACP consistently reduces hallucinations while preserving descriptive coverage; on a 1000-image multi-label COCO subset, it lowers CHAIR-s/i from 66.7/18.0 to 43.4/8.6 and improves F1 from 73.0 to 77.0. These findings suggest that head-level attribution provides an actionable signal for fine-grained inference-time hallucination control in LVLMs, while helping preserve descriptive coverage.

## Poster

![HACP poster](poster/HACP-POSTER.png)

## Citation

Citation information will be updated after publication.
