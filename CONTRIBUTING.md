# Contributing to Project OpenProbe

We welcome community-submitted evaluation tasks, edge cases, and independent telemetry audits.

## Submission Guidelines

1. **Test Vectors**: New multimodal test cases must specify input modality (camera, microphone, tool API), expected failure modes, and reproducible environmental conditions.
2. **Telemetry Formatting**: Submissions must validate against `benchmark_matrix.json` prior to pull request generation.
3. **Data Integrity**: Raw interaction logs belong under `/logs/`, while aggregate score scripts remain in `/scripts/`.
