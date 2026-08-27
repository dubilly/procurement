# Installation overview

## Which files should I use?

### Claude custom Skills
Use the individual ZIPs in `packages/`.

### ChatGPT native Skills
Use the individual ZIPs in `packages/` when Skills upload is available in your plan/workspace.

### ChatGPT without native Skills
Use the human-readable files in `skills/` inside a ChatGPT Project, plus the assistant instructions.

### Microsoft 365 Copilot / Copilot Studio
Use the assistant instructions as agent instructions. Add procurement files, policies, templates, and relevant workflow files as knowledge. See `INSTALL_MICROSOFT_COPILOT.md`.

## Suggested first install

Start with:

1. `procurement-skill.zip`
2. One child skill for the task you do most often
3. A second child skill after you test the first workflow

Example: For SaaS renewals, install `procurement-skill`, `pricing-model-review-skill`, `contract-risk-review-skill`, and `negotiation-prep-skill`.
