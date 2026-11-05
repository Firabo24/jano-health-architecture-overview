# Jano Health — Public Architecture Overview

Jano Health is an early-stage healthcare technology initiative exploring a modular, interoperable and offline-aware health information and clinical-support platform, initially designed around the realities of Ethiopia's health system.

This repository contains a **public, high-level overview only**. It intentionally does not contain the internal architecture baseline, detailed identity/security design, threat models, patient-safety registers, operational controls, API contracts, or internal approval and gap registers.

## What we are building

Our long-term direction is to help care teams work with more connected information, support continuity across care settings, and make useful clinical knowledge easier to access—while keeping clinical decisions and accountability with qualified people.

## Logical architecture

The current conceptual model has five areas:

1. **Healthcare OS** — clinical capabilities and care-delivery workflows.
2. **Jano Core** — foundational identity, organization, access and platform capabilities.
3. **AI Platform** — governed assistive intelligence, not an autonomous clinician.
4. **Data Platform** — governed data lifecycle, information products and analytics.
5. **Interoperability** — standards-oriented exchange with authorized external systems.

These are logical responsibility areas, not a commitment to five separately deployed services.

## Design principles

- Clinical authority remains with appropriately qualified people and accountable care organizations.
- AI is assistive, bounded, reviewable and subject to appropriate clinical governance.
- Privacy, security, auditability and patient trust are architectural requirements.
- Offline capability is important for constrained-connectivity settings; it does not imply that every clinical action can be performed offline.
- The platform should be modular and interoperable rather than tied to one facility or one vendor.
- Local language, accessibility and low-resource operating conditions matter from the beginning.

## Current maturity and limitations

This is an **early-stage architecture and prototype effort**. The Project Founder approved the consolidated Jano Health architecture baseline on **5 November 2026**, for architecture scope only. That approval establishes the accepted design direction; it is not independent design-authority review, clinical approval, legal/privacy clearance, security certification, partner authorization, implementation verification, or release approval.

The public material describes intended direction, not a certified or clinically validated product. It does not claim live-patient deployment, operational facility adoption, regulatory approval, government integration, Fayda partner authorization, clinical effectiveness, or production readiness. Clinical, legal/privacy, security, facility, partner, verification and release validation remain separate requirements.

## Repository contents

- `docs/architecture/overview.md` — conceptual architecture.
- `docs/architecture/principles.md` — design principles and boundaries.
- `docs/architecture/identity-and-interoperability.md` — public-level identity and integration posture.
- `docs/project/current-status.md` — maturity and claims boundary.
- `docs/project/architecture-approval-status.md` — founder approval scope and remaining gates.
- `SECURITY.md` — security reporting guidance.
- `LICENSE_DECISION_REQUIRED.md` — licensing status.

## Contributions

Documentation feedback is welcome through issues and pull requests. Do not submit patient information, credentials, private partner material, security vulnerabilities, or confidential clinical/operational information. See `CONTRIBUTING.md`.

## Important

Jano Health is not a substitute for professional medical judgment. Nothing in this repository is clinical guidance, an implementation authorization, or permission to process live patient data.
