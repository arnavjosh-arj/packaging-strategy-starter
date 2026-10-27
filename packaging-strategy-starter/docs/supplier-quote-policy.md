# Supplier Quote Policy

Taken from 04_sustainability_policy_brief and applied in the Workshop 5 n8n workflow.

## Rules

1. **Price rule.** A premium above 15% over the current price requires a business case memo and finance committee review.
2. **Certification rule.** Certification must be third-party. A supplier's own claim is not enough.

## How the workflow applies them

- Quotes with a premium of **15% or less** are logged automatically with the status *Auto-approved*.
- Quotes **above 15%** pause for a human decision. The approver chooses Approve or Reject and leaves a comment, and the result is logged.
- The AI step writes a short briefing and flags any certification described as self-reported.

## What the workflow does not replace

The approval form is a checkpoint, not the real review. The business case memo and the finance committee review still happen outside the workflow.
