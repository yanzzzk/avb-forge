# AVB-Forge

Active-Perception and Verifier-Guided Agentic Video Repair

AVB-Forge is an unofficial research extension built on Philo Labs' open-source
AgenticVBench. It studies whether typed media tools, active perception, and
non-leaky preflight verification improve video agents on official repair tasks.

This project is not affiliated with or endorsed by Philo Labs.

## Experiment variants

- A: general coding-agent baseline
- B: A with typed media tools
- C: B with OmniAgent-inspired active perception and evidence memory
- D: C with atomic claims, public preflight verification, and one retry

All variants use the same model, tasks, budgets, and official AgenticVBench
verifiers. Training is a separate optional phase after the A-D evaluation works.

## Status

- [x] Pin the upstream AgenticVBench revision
- [ ] Run the free oracle smoke test
- [ ] Parse the first official reward and trajectory
- [ ] Implement typed media tools
- [ ] Implement active perception
- [ ] Implement public preflight verification
- [ ] Run the A-D evaluation

## Upstream

See `UPSTREAM_COMMIT` for the exact AgenticVBench revision used by this project.

