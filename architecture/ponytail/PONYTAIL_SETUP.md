# PONYTAIL_SETUP.md

Version: 1.0  
Status: Recommended  

---

# Executive Summary

Ponytail is a software development philosophy that encourages developers to minimize complexity before adding code.

Reference:

https://github.com/DietrichGebert/ponytail

OurActivities adopts Ponytail as an architectural principle rather than a runtime dependency.

---

# Core Principle

Every activity should be:

- understandable
- maintainable
- composable
- minimal

---

# Ponytail Decision Ladder

Before implementing:

## Level 0

Do nothing.

Is the feature necessary?

---

## Level 1

Use platform capabilities.

Examples:

- GitHub Issues
- GitHub Actions
- Markdown
- Labels

---

## Level 2

Use existing activity capabilities.

Examples:

- Existing repositories
- Existing workflows
- Existing templates

---

## Level 3

Use configuration.

Examples:

- YAML
- JSON
- Environment variables

---

## Level 4

Use automation.

Examples:

- Scripts
- Workflows
- Scheduled jobs

---

## Level 5

Write new code.

Only when all previous levels fail.

---

# Repository Creation Policy

Before creating a new repository:

1. Existing repository unsuitable
2. Existing activity unsuitable
3. Existing template unsuitable
4. Existing workflow unsuitable

Document findings.

---

# Service Creation Policy

Before creating a service:

1. Can GitHub Actions solve it?
2. Can scheduling solve it?
3. Can static content solve it?
4. Can existing APIs solve it?

---

# Documentation First

Every capability begins with:

README.md

before implementation.

---

# Security Exception

Ponytail never overrides:

- security
- privacy
- accessibility
- compliance
- validation

---

# Recommended Usage

Apply Ponytail during:

- activity design
- repository creation
- workflow design
- automation design
- architecture reviews

---

# References

Ponytail

https://github.com/DietrichGebert/ponytail
