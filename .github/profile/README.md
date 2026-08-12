# darvh

<div align="center">

[![web](https://img.shields.io/badge/web-darvh.com-0d9488?style=flat-square&logo=astro&logoColor=white)](https://darvh.com)
[![bench live](https://img.shields.io/badge/bench-LIVE-22c55e?style=flat-square)](https://github.com/darvh/bench)
[![license MIT](https://img.shields.io/badge/license-MIT-6366f1?style=flat-square)](https://github.com/darvh/bench/blob/main/LICENSE)

</div>

Agent skills are easy to claim and hard to verify. We build the skills and the
bench that measures them in the same place, so a claim has to survive a
recorded cell before it gets published.

## Live

| product | what it does | source |
| --- | --- | --- |
| [bench](https://github.com/darvh/bench) | one harness for every product: docker image, containerized opencode, official verifier, per-cell result | repo |
| [signal](https://github.com/darvh/signal) | evidence-led uncertainty reduction and bounded recovery | repo + skill |
| [proof](https://github.com/darvh/proof) | turns a change into explicit obligations and reproducible evidence | repo |

## The bench

Every cell is one harbor job. Arms differ only by the skill installed in the
container plus a one-line hint. Nothing else: no host tooling, no plugins, no
MCP. If a claim does not come from a recorded cell, treat it as a proposal.

## Start here

- Read `bench/README.md` before trusting any skill claim.
- [darvh.com](https://darvh.com) publishes what is implemented and measured; proposals and hypotheses are labeled as such.
- Install signal from the signal repo's installer — one line, agent-agnostic, idempotent.
