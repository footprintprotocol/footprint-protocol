# Footprint Protocol — Methodology Appendix

This document provides a high-level overview of the observation principles used by Footprint Protocol.

It intentionally avoids disclosing implementation details, thresholds, or detection logic to preserve system integrity.

---

## 1. Methodology Principles

Footprint Protocol is designed around the following principles:

- Observation over attribution
- Behavior over identity
- Transparency without labeling
- Neutrality without enforcement

All analysis is descriptive and derived exclusively from publicly available on-chain data.

---

## 2. Data Scope

Footprint Protocol observes on-chain data including, but not limited to:

- Transaction timestamps
- Transaction ordering
- Funding source paths
- Wallet creation and first-use events
- Smart contract interactions
- Liquidity provisioning and withdrawal events
- Staking and governance-related movements

No off-chain data sources are used.

---

## 3. Funding Source Observation

The protocol observes how wallets are initially funded and how capital flows between addresses.

This includes:
- First-hop funding relationships
- Reused funding paths
- Known exchange-originated funding flows

The protocol does not assert ownership or control relationships.  
Funding source observation is limited to continuity analysis.

---

## 4. Behavioral Sequence Observation

Footprint Protocol analyzes sequences of actions rather than isolated events.

Behavioral observation focuses on:
- Action ordering
- Time intervals between actions
- Structural similarity between action sequences
- Repetition of similar execution patterns

Single transactions are not evaluated in isolation.

---

## 5. Temporal Correlation

Time-based relationships are a key observation layer.

The protocol considers:
- Relative timing between funding and execution
- Repeated timing structures across wallets
- Consistent delay patterns between actions

Absolute timestamps are less relevant than relative temporal structure.

---

## 6. Footprint Clustering (High-Level)

When multiple wallets exhibit:
- Similar funding origin paths
- Comparable behavioral sequences
- Comparable temporal structures

They may be grouped into a footprint cluster.

Clusters represent recurring behavioral models, not entities, identities, or actors.

---

## 7. Non-Objectives

Footprint Protocol does not perform:
- Scam classification
- Risk scoring
- Reputation assignment
- Identity inference
- Automated alerts implying wrongdoing

Any conclusions drawn from observed data remain the responsibility of the user.

---

## 8. Methodology Disclosure Policy

To prevent adversarial adaptation:
- Detection thresholds are not public
- Clustering heuristics are not disclosed
- Scoring or weighting mechanisms are not exposed

This document reflects methodological intent, not implementation detail.

---

## 9. Ethical Considerations

Footprint Protocol is designed to enhance transparency without compromising anonymity.

The methodology avoids:
- Subjective judgment
- Public labeling
- Enforcement actions

The protocol exists to reveal patterns, not to assign blame.

---

## 10. Document Status

This methodology appendix is a living document and may evolve as the protocol matures.

---

Footprint Protocol  
On-chain footprints never disappear.
