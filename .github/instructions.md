# Repository Instructions

## Objective

This repository follows a planning-first and security-aware development process.

## Planning Requirements

Before starting implementation:

* Define the problem being solved
* Document expected outcomes
* Identify assumptions and constraints
* Break work into manageable tasks
* Record dependencies
* Define acceptance criteria

Required planning artifacts:

* `plan.md` — project or feature plan
* `requirements.md` — requirements and scope
* `decision-log.md` — architecture and design decisions

---

## Scope Control

Changes should:

* Stay within approved requirements
* Avoid unrelated refactoring
* Minimize impact to existing functionality

Out-of-scope work must be documented separately.

---

## Security Requirements

All changes should include security review where applicable.

Requirements:

* No secrets or credentials in code
* Validate external inputs
* Apply least-privilege principles
* Use secure defaults
* Review dependencies before adding
* Avoid unnecessary exposure of internal information

Required security artifacts:

* `security-review.md`
* `risk-assessment.md`

---

## Testing Requirements

Before completion:

* Add tests for new functionality
* Verify existing behavior still works
* Document manual verification steps

Required evidence:

* Test results
* Validation notes

---

## Documentation

Update documentation when changes affect:

* Setup
* Usage
* Architecture
* Security assumptions

Required updates:

* `README.md`
* Relevant project documents

---

## Pull Request Expectations

Include:

* Summary
* Scope
* Security considerations
* Testing evidence
* Deployment impact

Work is not complete until documentation and artifacts are updated.
