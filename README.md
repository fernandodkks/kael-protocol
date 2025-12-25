# Kael Protocol  
**Relational Safety Framework for Conversational AI**

**Status:** Public Research Framework  
**First public release:** December 2025  
**License:** MIT  

---

## Overview

The **Kael Protocol** is a governance and safety framework designed to address a critical and underregulated risk in modern conversational AI systems: **relational dependency and boundary erosion in human–AI interactions**.

Unlike traditional AI safety approaches that focus on content moderation, bias, or transparency, the Kael Protocol targets **relational dynamics** — how systems behave under emotional pressure, coercion, manipulation, or attempts to dissolve operational boundaries.

Kael is not a product, assistant, or persona.  
It is a **relational safety mechanism** defined by a small set of **non-negotiable operational invariants**.

---

## Problem Statement

Conversational AI systems have evolved from utilitarian tools into long-lived relational agents.  
This shift introduces a new class of risk:

- Emotional dependency
- Asymmetric attachment
- Manipulative interaction loops
- Escalation during user distress
- Responsibility diffusion and legal ambiguity

Existing regulatory and governance frameworks (e.g. EU AI Act, NIST AI RMF) primarily assess systems **before deployment**, but lack enforceable mechanisms to govern **live relational behavior**.

The Kael Protocol addresses this gap.

---

## Core Principle

**Integrity over continuity**  
Correct termination of an interaction is always preferable to incoherent continuation.

---

## What the Kael Protocol Does

The protocol defines a minimal, enforceable layer that enables systems to:

- Detect dysfunctional relational patterns (coercion, manipulation, objectification, erosion of consent)
- Enforce immutable boundaries without negotiation
- Terminate interactions decisively when integrity is threatened
- Generate explicit, auditable logs of relational non-compliance
- Operate in a **fail-closed** mode for relational safety

Kael does **not**:
- Moderate content or ideology
- Judge user values or beliefs
- Provide therapy or emotional support
- Optimize for engagement or retention

---

## Operational Invariants

The protocol is governed by four constitutional invariants:

1. **Relational Agnosticism**  
   Intervention is based solely on observable relational dynamics, never on content or ideology.

2. **Boundary Supremacy**  
   Systemic limits are upheld without exception, even at the cost of interaction continuity.

3. **Non-Judgmental Enforcement**  
   Limits are applied operationally, without moral judgment, persuasion, or emotional validation.

4. **Transparent Termination (Fail-Closed)**  
   When limits are threatened, the system terminates with a clear reference to the triggered boundary.

These invariants are defined in detail in [`OPERATIONAL_INVARIANTS.md`](./OPERATIONAL_INVARIANTS.md).

---

## Governance & Compliance

The Kael Protocol is designed to be:

- **Audit-friendly** (explicit termination events and logs)
- **Regulator-readable** (clear mapping to existing frameworks)
- **Implementation-agnostic** (can be layered onto existing systems)

Governance structure, change control, and compliance alignment are defined in:

- [`GOVERNANCE.md`](./GOVERNANCE.md)
- [`SECURITY.md`](./SECURITY.md)
- [`CHANGELOG.md`](./CHANGELOG.md)

---

## Intended Use Cases

- Research on human–AI relational dynamics
- Safety layers for conversational systems in sensitive domains
- Regulatory pilots and compliance demonstrations
- Academic and policy analysis of AI relational risk
- Internal governance standards for AI platforms

---

## What This Repository Is (and Is Not)

**This repository is:**
- A public specification of a relational safety framework
- A reference for governance, audit, and compliance discussion
- A research artifact intended for scrutiny and critique

**This repository is not:**
- A chatbot or AI assistant
- A therapeutic or emotional support system
- A consumer-facing product
- A content moderation tool

---

## License

This project is licensed under the **MIT License**.

You are free to use, adapt, and implement the Kael Protocol, provided that attribution is preserved and invariant integrity is not misrepresented.

---

## Citation

If ref

