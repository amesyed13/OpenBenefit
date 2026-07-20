# OpenBenefit

> An open-source reference platform for designing transparent, explainable, and auditable benefit eligibility systems.

---

## Vision

Modern benefit eligibility systems often become difficult to maintain as business rules evolve, regulations change, and decision logic grows more complex.

OpenBenefit explores how enterprise software engineering practices can improve these systems by combining:

- Versioned business rules
- Explainable eligibility decisions
- Human-in-the-loop review
- Complete audit history
- Cloud-ready architecture
- Responsible AI assistance

The project is intended as an educational and engineering reference implementation rather than a production government system.

---

## Why OpenBenefit?

Many organizations struggle with questions such as:

- How should business rules change over time?
- How can historical decisions be reproduced?
- How should automated decisions be explained?
- Where should AI assist users—and where should deterministic rules remain authoritative?
- How can enterprise systems remain maintainable as policies evolve?

OpenBenefit is an attempt to answer those questions through software.

---

## Current Status

**Project Stage:** Architecture & Design

Current milestones completed:

- ✅ Project Charter
- ✅ Problem Research
- ✅ Comparable Project Analysis
- ✅ Software Requirements Specification
- ✅ Architecture Decision Records
- ✅ Modular Architecture Planning

Implementation begins next.

---

## Planned Technology Stack

| Layer | Technology |
|--------|------------|
| Frontend | Angular |
| Backend | ASP.NET Core (.NET 8) |
| Database | SQL Server |
| ORM | Entity Framework Core |
| Authentication | JWT |
| Documentation | Swagger / OpenAPI |
| Testing | xUnit |
| Logging | Serilog |
| Deployment | Docker |
| Cloud | Azure (later phases) |

---

## Core Principles

OpenBenefit follows several engineering principles:

- Keep business rules outside application logic.
- Every decision should be explainable.
- Every decision should be reproducible.
- Every rule change should be versioned.
- Every important action should be auditable.
- Human reviewers make final eligibility decisions.
- AI should assist—not replace—deterministic decision making.

---

## Repository Roadmap

### Phase 1

- Research
- Requirements
- Architecture

### Phase 2

- Database Design
- REST APIs
- Rule Engine
- Applicant Portal

### Phase 3

- Caseworker Portal
- Administration Portal
- Audit History
- Rule Versioning

### Phase 4

- Testing
- Docker
- Azure Deployment
- Documentation
- Public Release

---

## Disclaimer

OpenBenefit uses fictional benefit programs and synthetic applicant data.

It is an educational software engineering project and must not be used to determine eligibility for any real government, healthcare, financial, or public-benefit program.

---

## Author

**Ameema Misbha Sayyada**

Building OpenBenefit in public as part of a long-term exploration of enterprise software architecture, cloud-native engineering, and explainable decision systems.
