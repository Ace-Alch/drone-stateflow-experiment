# Drone Stateflow Experiment: validation

## Current evidence

This documentation update inspected available text and file inventories. It did not execute the project, simulate a model or test hardware. Existing recorded results must be cited with their original conditions.

## Proposed checks

These are test plans. No row below is marked as passed.

| Check | Action | Evidence to retain | Status |
| :-- | :-- | :-- | :-- |
| V01: Blue-line input | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V02: State transitions | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V03: Motion commands | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V04: Hover state | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |

## Project-specific checks

- Verify or recover: Stateflow chart.
- Verify or recover: Transition guards.
- Verify or recover: Image input assumptions.
- Verify or recover: Run logs and simulator dependencies.

## Reporting rule

Report units, sample size, configuration, error bounds and failures. Separate a simulation result from a hardware result. Separate an emulator check from a physical-device check. A screenshot alone does not establish numerical accuracy.
