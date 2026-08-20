# Vinh Nguyen

Solution Architect at FPT Software, based in Đà Nẵng, Vietnam. I design AI systems on AWS and still write the code every week — the two halves are the point.

### What I work on

- **Agentic systems and AI automation**, mostly for small teams and solo operators — the unglamorous parts: intake, follow-up, reporting.
- **Retrieval-augmented generation, LLM evaluation, Amazon Bedrock.**
- **Making automated work verifiable.** An agent that runs unattended is only useful if you can tell afterwards whether it was right. Evaluation harnesses, audit trails, and results published even when the answer is no.

### Featured work

**[ai-crypto](https://github.com/vinhnguyenthanhdn/ai-crypto)** &nbsp;[![stars](https://img.shields.io/github/stars/vinhnguyenthanhdn/ai-crypto?style=flat&label=stars)](https://github.com/vinhnguyenthanhdn/ai-crypto/stargazers) [![last commit](https://img.shields.io/github/last-commit/vinhnguyenthanhdn/ai-crypto?style=flat&label=last%20commit)](https://github.com/vinhnguyenthanhdn/ai-crypto/commits)

A research platform for discovering and rigorously *falsifying* crypto trading strategies. Every configuration it has searched so far has been rejected; it publishes the machinery that reached that verdict and the evidence that the verdict is trustworthy. Running counts live in [docs/backtest-results.md](https://github.com/vinhnguyenthanhdn/ai-crypto/blob/main/docs/backtest-results.md).

**[bedrock-eval-harness](https://github.com/vinhnguyenthanhdn/bedrock-eval-harness)** &nbsp;[![CI](https://img.shields.io/github/actions/workflow/status/vinhnguyenthanhdn/bedrock-eval-harness/ci.yml?branch=main&style=flat&label=CI)](https://github.com/vinhnguyenthanhdn/bedrock-eval-harness/actions/workflows/ci.yml) [![release](https://img.shields.io/github/v/release/vinhnguyenthanhdn/bedrock-eval-harness?style=flat&label=release)](https://github.com/vinhnguyenthanhdn/bedrock-eval-harness/releases)

Keep a fixed set of cases and answer the two questions that follow any model or prompt change: did it get better, and what does it now cost? A run is a file rather than a terminal scrollback that is gone, so two runs can be compared case by case instead of by one average — two runs can score the same and still have lost a case and gained another. No model has been called yet; every number in the repo is a fixture and labelled as one.

**[claude-jobs](https://github.com/vinhnguyenthanhdn/claude-jobs)** &nbsp;[![npm](https://img.shields.io/npm/v/claude-jobs?style=flat&label=npm)](https://www.npmjs.com/package/claude-jobs) [![stars](https://img.shields.io/github/stars/vinhnguyenthanhdn/claude-jobs?style=flat&label=stars)](https://github.com/vinhnguyenthanhdn/claude-jobs/stargazers)

Scheduled, unattended Claude Code CLI runs on your existing subscription, no API key. The wrapper details that decide whether a 3am job succeeds or fails silently.

**[claude-router](https://github.com/vinhnguyenthanhdn/claude-router)** &nbsp;[![CI](https://img.shields.io/github/actions/workflow/status/vinhnguyenthanhdn/claude-router/test.yml?branch=main&style=flat&label=CI)](https://github.com/vinhnguyenthanhdn/claude-router/actions/workflows/test.yml) [![stars](https://img.shields.io/github/stars/vinhnguyenthanhdn/claude-router?style=flat&label=stars)](https://github.com/vinhnguyenthanhdn/claude-router/stargazers)

Point Claude Code at a different model provider for one terminal session, without editing global settings you then have to remember to undo. The launcher and the VSCode switch each ship in two versions, PowerShell and POSIX shell, so Windows and macOS both get the same three modes. [Linux](https://github.com/vinhnguyenthanhdn/claude-router/issues/6) is the remaining gap, mostly install paths and where VSCode keeps its settings, and reviewed pull requests are welcome.

### Open-source contributions

Merged into other people's repositories. The conversation on each pull request is the part worth reading.

- **[openclaw/openclaw#76538](https://github.com/openclaw/openclaw/pull/76538)** — a regression test for session repair trimming the final assistant response after tool usage. Six comments before it went in. Tests only, no product code.
- **[xiufengsun/TokenTracker#482](https://github.com/xiufengsun/TokenTracker/pull/482)** — merged in seven hours and shipped in `0.91.0` the same day.

Open and waiting on review: [nizos/tdd-guard#199](https://github.com/nizos/tdd-guard/pull/199), [vercel-labs/agent-browser#1698](https://github.com/vercel-labs/agent-browser/pull/1698), [xiufengsun/TokenTracker#483](https://github.com/xiufengsun/TokenTracker/pull/483).

### Background

Sixteen years in software: seven in games (Unity, Unreal, webgame), five running product and a company, the last three on AI automation. Architects who stopped coding design things their team cannot build; managers who never coded commit to dates the system cannot meet.

### Certifications

AWS Certified Generative AI Developer – Professional (2026) · PMP (2024) · PMI-ACP (2021, expired 2024)

### Working together

Open to project work, hourly consulting, and monthly retainers — remote. Issues and pull requests on any repo above are welcome; the ones tagged `good first issue` are scoped to a single sitting.

[vinhnguyenthanhdn.github.io](https://vinhnguyenthanhdn.github.io) · [LinkedIn](https://www.linkedin.com/in/vinhnguyen203/)
