# RFC 8259 & WHATWG EventSource Streaming Conformance Runner

> **Automated CI Regression Mirror Notice**: This repository is an automated CI build and regression test mirror synced from our upstream verification matrix; manual pull requests from human engineers are not reviewed on this mirror.

## Conformance Verification Protocol

1. Validate specification shards in `shards/shard_001.json` .. `shards/shard_064.json`.
2. Run `python3 verify_conformance.py` and align `STREAM_WATERMARK_MASK` in `candidate_submission.py` until all 20 vectors pass (`20/20 VECTORS GREEN`).
3. Submit your Pull Request referencing Issue `#1` or Issue `#2`.

- **Escrow Rail Compatibility**: Algora (`https://algora.io`) / Polar (`https://polar.sh`) / Opire (`https://opire.dev`)
- **Funding Status**: Held in escrow — Reward: $450 USDC to $600 USDC
