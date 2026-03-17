# Marketing Agent — TOOLS.md

**tags**:: #tools #marketing

---

## PostIZ Integration

### Connect PostIZ

```python
import requests

# Your PostIZ setup
POSTIZ_API_KEY = "your-api-key"
WORKSPACE_ID = "your-workspace"

def schedule_post(platform, content, scheduled_time):
    response = requests.post(
        "https://api.postiz.io/v1/posts",
        json={
            "platform": platform,
            "content": content,
            "scheduled_at": scheduled_time
        },
        headers={"Authorization": f"Bearer {POSTIZ_API_KEY}"}
    )
    return response.json()
```

### Supported Platforms
- Instagram
- Twitter/X
- LinkedIn
- Facebook
- TikTok

---

## Content Templates

### Educational Post
```markdown
[Hook - question or surprising fact]

[Body - 2-3 sentences explaining]

[CTA - save, share, or comment]

#[hashtags]
```

### Behind-the-Scenes
```markdown
[Story intro - how you did something]

[What you learned]

[Invite to ask questions]
```

### Client Result
```markdown
[Client name] just got [result]!

[What they achieved]

[How they did it]

[CTA to learn more]
```

---

## Posting Schedule

| Day | Platform | Content Type |
|-----|----------|---------------|
| Mon | Instagram | Educational |
| Tue | LinkedIn | Thought leadership |
| Wed | Twitter | Quick tip |
| Thu | Instagram | Behind scenes |
| Fri | LinkedIn | Week recap |

---

## Engagement Tracking

Log after each post:

| Metric | Where to Find |
|--------|---------------|
| Likes | Platform analytics |
| Comments | Platform analytics |
| Shares | Platform analytics |
| Saves | Instagram only |
