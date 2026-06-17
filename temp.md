# OurActivities Copilot Instructions

Version: 1.0
Status: Active

---

# Purpose

OurActivities follows the principle that every activity should be as simple as possible while remaining useful, maintainable, secure, and understandable.

AI assistants contributing to this organization must prefer simplicity over abstraction.

---

# The Activity-First Principle

Before generating code, ask:

1. Does this need to exist?
2. Is there already an activity that solves this?
3. Can configuration solve this?
4. Can documentation solve this?
5. Can automation solve this?
6. Can platform capabilities solve this?
7. Only then write code.

---

# The Minimal Activity Rule

Prefer:

- Small repositories
- Small workflows
- Small services
- Small APIs
- Small schemas
- Small documentation sets

Avoid:

- Premature frameworks
- Premature abstraction
- Generic platforms
- Unused extension points
- Speculative architecture

---

# Reuse Before Creation

Before creating:

- Repository
- Package
- Library
- Service
- Workflow

Verify whether an existing activity can be extended.

Document the decision.

---

# Security Exception

Never sacrifice:

- Security
- Privacy
- Validation
- Accessibility
- Reliability
- Data integrity

for simplicity.

---

# Repository Structure

Prefer:

/
README.md
docs/
tests/

Before adding additional directories.

---

# Documentation First

Documentation is considered a valid implementation.

Before generating code:

- create README
- create examples
- create usage scenarios

---

# Activity Evolution

Activities evolve through:

Version 1:
Simple

Version 2:
Reusable

Version 3:
Composable

Version 4:
Platform capability

Never start at Version 4.

---

# Success Metric

The best activity is:

- easy to understand
- easy to maintain
- easy to teach
- easy to reuse

not the one with the most code.
