# Architecture principles

## 1. Clinical accountability

Software can organize information and support decisions, but it must not obscure who is clinically accountable. Clinical policy, intended use, escalation and release require qualified review.

## 2. Human-supervised intelligence

AI is a governed assistive capability. Its tasks, permitted inputs and outputs, limitations, provenance, evaluation and oversight must be defined before clinical use.

## 3. Privacy and trust by design

Collect and expose only what is needed for an authorized purpose. Identity, authentication, access authorization and clinical attribution are distinct concerns. Sensitive data must not be placed in public repositories, ordinary logs or unapproved third-party services.

## 4. Offline-aware, not indiscriminately offline

The system should tolerate unreliable connectivity and support safe continuity. Each operation must be separately assessed for offline eligibility, authority, conflict handling and recovery. Offline-first is not blanket permission to create or finalize clinical records while disconnected.

## 5. Modular responsibility

Separate clinical capabilities, shared platform foundations, AI, data stewardship and external exchange by responsibility. Do not assume that each logical area must be an independent microservice.

## 6. Interoperability with governance

Use appropriate standards and explicit partner contracts. External exchange requires authorization, data minimization, identity mapping, provenance and conformance testing.

## 7. Localization and accessibility

Design for low-bandwidth environments, modest devices, accessibility, and clinician-reviewed Afaan Oromoo and Amharic experiences.

## 8. Evidence before claims

Distinguish architecture proposals, implemented features, tested behavior, clinical validation, regulatory/partner authorization and production operation. Never present one as evidence of another.
