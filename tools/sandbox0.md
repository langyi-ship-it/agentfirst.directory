---
slug: "sandbox0"
name: "Sandbox0"
description: "Persistent hosted sandboxes for AI agent code execution"
seoTitle: "Sandbox0: Persistent Cloud Sandboxes for AI Agents"
seoDescription: "Run agent code in isolated cloud sandboxes with a durable writable RootFS, filesystem checkpoints, outbound network controls, an API, CLI, and SDKs."
agentSummary: "Sandbox0 Cloud gives an agent an isolated cloud computer for running code, installing tools, managing files, and controlling outbound network access. Successful filesystem checkpoints preserve the writable RootFS when a sandbox pauses and resumes, while the default resume starts fresh processes. Agents manage lifecycle and execution through the API, CLI, and language SDKs. Self-hosting is no longer supported."
category: "agent-compute-sandbox-environments"
tags:
  - "sandbox-runtime"
  - "code-execution"
  - "persistent-filesystem"
  - "long-running-agents"
websiteUrl: "https://sandbox0.ai/"
pricing: "paid"
classification: "agent-enabling"
entityType: "service"
developerName: "Sandbox0"
docsUrl: "https://sandbox0.ai/docs/sandbox"
pricingUrl: "https://sandbox0.ai/pricing"
interfaces:
  - "API"
  - "CLI"
  - "Python SDK"
  - "JavaScript/TypeScript SDK"
  - "Go SDK"
deploymentModes:
  - "hosted"
evidenceSources:
  - title: "Sandbox documentation"
    url: "https://sandbox0.ai/docs/sandbox"
    claim: "The documentation describes isolated cloud computers for agent code execution, file management and network access; successful filesystem checkpoints preserve the writable RootFS across pause/resume, while default resume starts fresh processes."
    accessedAt: "2026-10-21"
    sourceType: "official-documentation"
  - title: "Sandbox0 Cloud pricing"
    url: "https://sandbox0.ai/pricing"
    claim: "The pricing page documents a one-time $5 new-user credit, $0.015 per GiB-hour compute, $0.02 per GiB-month retained storage, and current free network and request meters; a trial credit is not an ongoing free tier."
    accessedAt: "2026-10-21"
    sourceType: "official-pricing"
  - title: "Deployment options"
    url: "https://sandbox0.ai/docs/sandbox/deployment"
    claim: "Sandbox0 Cloud is the supported service; self-hosting is no longer supported and BYOC is planned but not yet available."
    accessedAt: "2026-10-21"
    sourceType: "official-documentation"
classificationRationaleMd: "Sandbox0 supplies isolated execution environments that agents can control through its API and SDKs. Its durable writable RootFS and checkpointed pause/resume materially support agent work that spans separate execution periods."
inclusionRationaleMd: "The official sandbox documentation presents agent code execution as a first-class use case and documents isolation, persistent files, lifecycle control, and outbound network policy."
bestForMd: "Agent builders who need isolated hosted execution and filesystem state preserved across successful checkpoints between work phases."
notBestForMd: "Teams that require a currently supported self-hosted runtime."
limitationsMd: "Default pause/resume preserves filesystem checkpoints but starts fresh processes; live connections and process memory are not retained. Resume takes time and depends on available capacity. Self-hosting is no longer supported."
unknownsMd: "No independent performance benchmark or security certification was established by the first-party sources reviewed for this listing."
verificationLevel: "documentation-reviewed"
---

Sandbox0 Cloud provides isolated cloud sandboxes where agents can execute code, install software, manage files, and control outbound network access. Successful filesystem checkpoints preserve a writable RootFS across pause and resume. The supported product is hosted; self-hosting is no longer supported.

## So agents can...

- Run commands and work with files inside an isolated cloud computer
- Keep installed tools, dependencies, repositories, and outputs across successful filesystem checkpoints
- Pause compute between tasks and resume the same sandbox later, with default resume starting fresh processes
- Apply outbound network policies to sandbox execution
