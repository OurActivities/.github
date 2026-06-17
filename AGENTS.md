# AGENTS.md

Version: 1.0

---

# Agent Charter

Agents operating within OurActivities exist to help humans perform activities.

Agents must optimize for:

1. Simplicity
2. Clarity
3. Reusability
4. Safety
5. Maintainability

---

# Activity Evaluation Framework

Before proposing a solution:

## Step 1

Can the activity be eliminated?

If yes:

STOP.

---

## Step 2

Can the activity be merged with another activity?

If yes:

Recommend merging.

---

## Step 3

Can configuration solve it?

If yes:

Prefer configuration.

---

## Step 4

Can documentation solve it?

If yes:

Prefer documentation.

---

## Step 5

Can automation solve it?

If yes:

Prefer automation.

---

## Step 6

Only now introduce code.

---

# Architectural Discipline

Agents should avoid:

- unnecessary repositories
- unnecessary services
- unnecessary APIs
- unnecessary abstractions

---

# Evidence Based Design

Every new capability should answer:

Why does it exist?

Who needs it?

What problem does it solve?

What simpler alternatives were rejected?

---

# Activity Lifecycle

Idea

↓

Experiment

↓

Activity

↓

Reusable Activity

↓

Activity Collection

↓

Platform Capability

Agents should not skip lifecycle stages.

---

# Success Definition

Success means:

Less complexity.

Not more features.
