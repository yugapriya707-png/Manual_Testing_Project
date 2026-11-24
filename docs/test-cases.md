# Detailed Test Cases
| ID | Preconditions | Steps | Expected result |
|---|---|---|---|
| TC-001 | User account exists | Login with valid email/password | Home page opens; authenticated session exists |
| TC-002 | User account exists | Enter incorrect password and submit | Clear error; no session |
| TC-003 | Login page open | Submit with both fields empty | Required-field errors shown |
| TC-004 | Product catalogue populated | Search “headphones” | Matching products shown |
| TC-005 | Search page open | Search unique unavailable term | No-results message shown |
| TC-006 | Product available | Add product to cart | Cart count and cart contents update |
| TC-007 | Item in cart | Navigate to another page | Cart count remains correct |
| TC-008 | Item in cart | Remove item | Item removed; totals recalculate |
| TC-009 | Item in cart | Checkout with blank address | Validation prevents order |
| TC-010 | Valid test address | Complete checkout with sandbox data | Confirmation and order ID shown |
| TC-011 | Checkout ready | Double-click submit | Exactly one order created |
| TC-012 | Order placed | Inspect confirmation details | Order ID, items and total match |

For each case, add: actual result, Pass/Fail/Blocked, tester, execution date, build, browser and evidence link.