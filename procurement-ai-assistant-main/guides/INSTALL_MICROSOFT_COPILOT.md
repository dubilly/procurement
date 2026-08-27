# Use with Microsoft 365 Copilot / Copilot Studio

Microsoft 365 Copilot Agent Builder and Copilot Studio use **agent instructions** and **knowledge sources** rather than the same ZIP-based custom Skill installation flow used by Claude.

## Microsoft 365 Copilot Agent Builder

1. In Microsoft 365 Copilot, select **New agent**.
2. Create an agent called `Procurement Assistant`.
3. In the agent's **Instructions**, add the core operating instructions from `assistant/PROCUREMENT_ASSISTANT_INSTRUCTIONS.md` and the workflow instructions you want the agent to follow.
4. Add approved policies, templates, contracts, playbooks, and other reference material under **Knowledge**.
5. Add starter prompts for common procurement tasks.
6. Test the agent before sharing it.

Keep the distinction clear:

- **Instructions** tell the agent how to work.
- **Knowledge** gives the agent information to reference.

## Copilot Studio

You can build the same concept in Copilot Studio and add files such as `.md`, `.txt`, PDF, Word, Excel, CSV, JSON, or YAML as knowledge. For more advanced automation, add tools/actions and approval steps after testing the instruction-only version.

## Important

Do not assume that uploading a `SKILL.md` as knowledge makes it a native Agent Skill. For Microsoft 365 Copilot, translate the relevant workflow into agent instructions and use files as knowledge/reference material.
