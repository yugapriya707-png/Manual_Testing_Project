# Bug Report Template and Samples
## Required fields
Bug ID, concise title, environment/build, module, preconditions, reproducible steps, expected result, actual result, severity, priority, reproducibility, attachments, reporter, status.

## BUG-001 — Checkout accepts empty address
- Severity: High | Priority: P1 | Status: Open
- Steps: Add item → checkout → leave address blank → submit.
- Expected: Validation blocks submission and identifies address field.
- Actual: Sample observation: order proceeds.
- Impact: Orders may be created without delivery information.

## BUG-002 — Cart badge does not refresh
- Severity: Medium | Priority: P2 | Status: Open
- Steps: Add item → navigate to another page.
- Expected: Badge reflects current cart count.
- Actual: Sample observation: badge remains zero.

## BUG-003 — Search is case-sensitive
- Severity: Medium | Priority: P2 | Status: In Progress
- Steps: Search same keyword with different capitalization.
- Expected: Equivalent results.
- Actual: Sample observation: results differ.