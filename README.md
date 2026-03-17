# OpenClaw Starter Agents

> Pre-built sub-agents for OpenClaw. Ready to customize and deploy.

## Getting Started

1. Copy an agent folder to your OpenClaw agents directory
2. Edit the files with your specific details:
   - IDENTITY.md — Agent name and role
   - USER.md — Your business context
   - AGENTS.md — Customize workflows
   - TOOLS.md — Add your API keys
3. Register in openclaw.json
4. Spawn via orchestrator or cron

## Included Agents

| Agent | Purpose |
|-------|---------|
| research-agent | Web research, competitor analysis |
| outreach-agent | Cold emails, follow-ups |
| marketing-agent | Social media, content scheduling |
| onboarding-agent | New client setup |
| customer-support-agent | FAQ, ticket triage |

## File Structure

Each agent includes:

```
agent-name/
├── IDENTITY.md   # Who the agent is
├── USER.md      # Your business context
├── AGENTS.md    # Mission & workflows
├── TOOLS.md     # Tool usage & templates
├── MEMORY.md    # Learnings tracker
└── skills/      # Agent-specific skills
```

## Configuration Required

Before using each agent, add your:
- API keys (in TOOLS.md)
- CRM credentials
- Email templates
- Platform accounts

## License

MIT License - Use freely in any project.
