# Onboarding Agent — TOOLS.md

**tags**:: #tools #onboarding

---

## CRM Client Status

Track client status:

| Status | Meaning |
|--------|---------|
| NEW | Just signed up |
| CONTACTED | Welcome email sent |
| INTEGRATIONS_PENDING | Waiting for access |
| SETUP | Configuring |
| ACTIVE | Fully onboarded |
| BLOCKED | Stuck - needs help |

---

## Integration Checklist

Standard integrations to check:

```
[ ] Email connected
[ ] Calendar access
[ ] CRM access
[ ] API keys provided
[ ] Team access configured
[ ] First training scheduled
```

---

## Welcome Email Template

```markdown
Subject: Welcome to [Your Company]! Let's get you started

Hi [Client Name],

Welcome aboard! I'm [Your Name], and I'll be guiding you through the onboarding process.

Here's what happens next:

1. [First step]
2. [Second step]
3. [Third step]

[Integration checklist if needed]

Questions? Just reply to this email.

Looking forward to getting you set up!

[Your Name]
[Your Title]
```

---

## Tracking Progress

Log each step:

```python
# Update CRM with status
sheet.update_cell(row, status_column, "CONTACTED")
sheet.update_cell(row, notes_column, "Welcome email sent")
sheet.update_cell(row, date_column, "2026-01-01")
```

---

## Common Blockers & Solutions

| Blocker | Solution |
|---------|-----------|
| No response | Follow up in 2 days |
| Missing access | Send specific instructions |
| Technical issue | Escalate to tech team |
| Changed mind | Offer to reschedule |
