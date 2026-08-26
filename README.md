# Cron Carnival

> Your scheduled jobs are rides, and failure brings the clowns.

A CLI that schedules jobs like carnival rides, where each cron entry has a queue, a jester, and a failure clown. When a job misses its slot, the daemon prints a clown report and demands a confetti patch.

## Features
- Define rides in a simple YAML file with cron schedules
- Live terminal carousel shows queue length and jester mood
- Failure clown report suggests a one-line fix and logs the humiliation
- Confetti mode replays successful jobs as ANSI fireworks

## Stack
- Rust
- Clap
- Serde
- Cron

## Getting started
```
cargo run -- init; edit rides.yaml; cargo run -- serve; cargo run -- confetti
```

---
*Farmed 🚜 by [Appshaker](https://github.com/buberlo) — shaken into existence.*
