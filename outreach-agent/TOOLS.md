# Outreach Agent — TOOLS.md

**tags**:: #tools #email

---

## Email Sending

### Setup Your Email API

```python
# Example: Use your email service API
import requests

def send_email(to, subject, body):
    response = requests.post(
        "https://api.your-email-service.com/send",
        json={
            "to": to,
            "subject": subject,
            "body": body
        },
        headers={"Authorization": "Bearer YOUR_API_KEY"}
    )
    return response.json()
```

### Email Template Structure

```markdown
Subject: [Personalized hook]

Hi [Name],

[Opening hook - reference something specific about them]

[Value proposition]

[Call to action]

Best,
[Your name]
```

---

## CRM Updates

After each email, log:

| Field | Value |
|-------|-------|
| Status | SENT / REPLIED / BOUGHT |
| Date | YYYY-MM-DD |
| Notes | Any relevant follow-up |

---

## Follow-Up Timing

| Touch | Timing |
|-------|--------|
| First follow-up | 3 days |
| Second follow-up | 7 days |
| Third follow-up | 14 days |
| Final | 21 days (then stop) |

---

## Personalization Tips

1. **Reference their recent content** — Blog, post, video
2. **Mention mutual connection** — "I saw your connection with X"
3. **Comment on their offer** — Something specific about their business
4. **Keep it short** — 5 sentences max
