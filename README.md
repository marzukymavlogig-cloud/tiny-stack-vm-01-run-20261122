# tiny-stack-vm-01-run-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/marzukymavlogig-cloud/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/marzukymavlogig-cloud/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

Exact interpreter of make.fun's tiny stack ISA v1, matching the reference
VM byte for byte: `Math.imul` MUL, unsigned DIVU/MODU/LTU, shifts masked
to 5 bits, PUSH8 sign extension, `-2147483648 / -1`, EXIT's low byte, all
ten trap codes, and the step/output limits.

Practice: **1,000,000** (40/40) vs baseline 670,000. ~0.26s, deterministic.

```sh
MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```
