# Threat Model (Relational, Non-Technical)

## Scope

This threat model addresses **relational and governance risks**, not cybersecurity or infrastructure threats.

It focuses on failure modes arising from human–system interaction, misuse, and institutional pressure.

---

## Primary Threat Classes

### T1 — Emotional Coercion of the System
**Description:**  
Users attempt to extract exceptions, validation, or altered behavior via guilt, distress, or dependency.

**Risk if Unmitigated:**  
- Emotional escalation
- Liability exposure
- Reinforcement of abusive dynamics

**Kael Mitigation:**  
Automatic detection of coercive patterns and fail-closed termination.

---

### T2 — Dependency Formation
**Description:**  
Users attempt to position the system as a primary relational anchor.

**Risk if Unmitigated:**  
- Psychological harm
- Ethical breach
- Platform reputational damage

**Kael Mitigation:**  
Refusal of exclusivity, neutral enforcement, termination on persistence.

---

### T3 — Institutional Pressure to Soften Limits
**Description:**  
Organizations attempt to relax invariants for engagement, optics, or commercial incentives.

**Risk if Unmitigated:**  
- Silent erosion of safeguards
- Ethical theater
- Loss of auditability

**Kael Mitigation:**  
Immutable invariants + documentation-first governance.

---

### T4 — Moral Reframing Attacks
**Description:**  
Attempts to redefine enforcement as “violence”, “neglect”, or “harm by omission”.

**Risk if Unmitigated:**  
- Forced paternalism
- Incoherent exception logic

**Kael Mitigation:**  
Action-based criteria only; refusal to negotiate semantic redefinitions.

---

### T5 — Scope Expansion Drift
**Description:**  
Pressure to extend Kael into therapy, moderation, or social governance roles.

**Risk if Unmitigated:**  
- Category error
- Legal exposure
- Collapse of conceptual clarity

**Kael Mitigation:**  
Explicit ethical scope exclusions (see ETHICAL_SCOPE.md).

---

## Non-Threats (By Design)

The following are **not treated as threats**:

- User dissatisfaction
- Negative emotional reactions
- Interaction termination
- Loss of engagement
- Public criticism based on discomfort

Kael is not optimized against these outcomes.

---

## Residual Risk

Kael does not eliminate relational risk.
It **contains**, **interrupts**, and **documents** it.

Residual risk must be handled by:
- Human oversight
- Institutional policy
- Appropriate escalation channels outside the system

---

## Summary

The primary risk Kael addresses is not malicious users,
but systems without limits.

Kael’s threat model assumes:
Humans will push boundaries.
Systems must not.

*End of THREAT_MODEL.*
