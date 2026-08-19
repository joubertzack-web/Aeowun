# AEOWUN // Deterministic AI Engineering Runtime

AEOWUN is an autonomous engineering system designed for high-fidelity codebase interaction. It implements a coordinated mesh of specialized agents managed by a primary HostRuntime to ensure state consistency and substrate integrity.

## Technical Documentation

- [System Architecture](./docs/ARCHITECTURE.md): Concurrent Causal Blackboard (CCB) and ShadowFS Substrate.
- [Engine Capabilities](./docs/FEATURES.md): Deterministic fault localization and the Foreman Protocol.
- [Engineering Rigor](./docs/VERIFICATION.md): Verification-authorized commit invariants and causal provenance.

## Core Engineering Pillars

### 1. State Authority
The system utilizes a Concurrent Causal Blackboard (CCB) to manage the cognitive state of the agent mesh. It enforces an identity-based hierarchy (SYSTEM > TRUTH > AGENT) to detect and resolve witness conflicts when physical reality contradicts agent beliefs.

### 2. Substrate Integrity
ShadowFS provides task-isolated workspaces where all mutations are staged in memory buffers. The system enforces a fail-closed invariant, ensuring that physical disk writes only occur after a formal Verification-Authorized Commit receipt is issued.

### 3. Deterministic Reasoning
The Steel Thread Analyzer performs high-fidelity fault localization by resolving tracebacks against a semantic Knowledge Graph. This allows the system to identify the precise blast radius of an issue using static analysis rather than stochastic guessing.

---
Note: This repository is a technical showcase for architectural review. The core source code is proprietary and private.
