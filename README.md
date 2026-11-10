<div align="center">
  <img src="https://raw.githubusercontent.com/iam360-ai/iam360-mcp-connector/main/assets/iam360.png" alt="iAM360" width="120" />

  <h1>iAM360</h1>
  <p>Your fitness record, connected.</p>

  <p>
    <a href="https://www.iam360.ai">Website</a> ·
    <a href="https://app.iam360.ai">Open iAM360</a> ·
    <a href="https://app.iam360.ai/docs/mcp">MCP docs</a> ·
    <a href="https://github.com/iam360-ai/iam360-mcp-connector/blob/main/docs/skills.md">Agent skills</a>
  </p>
</div>

iAM360 brings recovery, sleep, nutrition, workouts, and daily habits into one fitness record. Our MCP connector and agent skills make that record useful in the AI assistants you choose.

## Connect your assistant

1. [Create your iAM360 account](https://app.iam360.ai), or sign in if you already have one.
2. Add this remote MCP endpoint in a compatible assistant:

   ```text
   https://app.iam360.ai/api/mcp
   ```

3. Complete the browser OAuth sign-in, review the requested access, select **Allow**, and return to your assistant.

[Setup guides and connector repository](https://github.com/iam360-ai/iam360-mcp-connector) · [Authentication guide](https://app.iam360.ai/docs/mcp/authentication)

## What you can do

- Review wearable recovery and sleep data, nutrition, and workout history.
- Log meals, record workouts, and track progress over time.
- Manage challenges, routines, life events, and journal entries.
- Bring relevant fitness context into conversations with your assistant.

Connected assistants can read and write account data within the access you grant. Review requested changes and manage connected assistants in iAM360 settings.

## IAM360 agent skills

Start with your [IAM360 account](https://app.iam360.ai), then connect it to a compatible assistant. Four portable skills help the assistant use your records accurately and make only the changes you request:

| Skill | What it helps with |
| --- | --- |
| [Fitness review](https://github.com/iam360-ai/iam360-mcp-connector/tree/main/skills/iam360-fitness-review) | Recovery, sleep, wearable trends and progress against goals |
| [Nutrition](https://github.com/iam360-ai/iam360-mcp-connector/tree/main/skills/iam360-nutrition) | Meals, daily totals and food-log corrections |
| [Workouts](https://github.com/iam360-ai/iam360-mcp-connector/tree/main/skills/iam360-workouts) | Exercise history, completed sessions and approved routines |
| [Habits and journal](https://github.com/iam360-ai/iam360-mcp-connector/tree/main/skills/iam360-habits-journal) | Challenges, life events and private reflections |

[Installation guide for Claude Code, Codex, Cursor, Gemini CLI and other compatible agents](https://github.com/iam360-ai/iam360-mcp-connector/blob/main/docs/skills.md) · [Browse all skills](https://github.com/iam360-ai/iam360-mcp-connector/tree/main/skills)

Skills provide workflows. Each person still signs in to their own IAM360 account and authorizes the MCP connection.

## IAM360 for n8n

[Explore the n8n node source](https://github.com/iam360-ai/n8n-nodes-iam360) for workflows that read your fitness overview, daily metrics, nutrition and workouts, or create and delete requested meal records. The repository includes setup documentation and example workflows.

This is a community node release candidate. n8n verification and catalog availability are still pending; see the repository for the current release status.

## Find us

- [Instagram](https://www.instagram.com/iam360_evolved/)
- [X](https://x.com/iAM360_Evolved)
- [LinkedIn](https://www.linkedin.com/company/iam360-evolved/)
- [YouTube](https://www.youtube.com/@iAM360-Official)
- [TikTok](https://www.tiktok.com/@iam360_performance_coach)

## Resources

- [MCP documentation](https://app.iam360.ai/docs/mcp)
- [Connector setup and configuration](https://github.com/iam360-ai/iam360-mcp-connector)
- [Agent skills and installation](https://github.com/iam360-ai/iam360-mcp-connector/blob/main/docs/skills.md)
- [IAM360 for n8n source and examples](https://github.com/iam360-ai/n8n-nodes-iam360)
- [Privacy policy](https://app.iam360.ai/privacy)
- [Terms of service](https://app.iam360.ai/terms)
