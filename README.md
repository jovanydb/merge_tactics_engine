# Merge Tactics Engine

**A planned strategy engine for exploring decisions in Clash Royale Merge Tactics.**

> **Status: concept stage.** This repository currently contains the project license and this overview. Engine source, simulations, and performance benchmarks have not been published.

## Project direction

The goal is to study how state representation, action selection, and evaluation can support stronger decisions in Merge Tactics. Trophy progression and win rate are intended evaluation outcomes, not demonstrated results.

## Proposed milestones

| Milestone | Deliverable |
| --- | --- |
| Define the environment | Document game rules, states, legal actions, and terminal conditions |
| Build a baseline | Implement a reproducible simulator and a simple decision policy |
| Evaluate strategies | Compare policies across fixed scenarios and random seeds |
| Report findings | Publish assumptions, sample sizes, win rates, and limitations |

## Repository contents

- [LICENSE](LICENSE): MIT license.
- `README.md`: scope, status, and planned development.

## Development approach

Begin with a small, testable model of the game. Separate rules from strategy, retain deterministic replay seeds, and compare any new policy against an explicit baseline. Document the game version used so results remain interpretable as rules change.

## License

Released under the [MIT License](LICENSE).
