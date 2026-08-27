# Getting Started

This guide is written for procurement professionals who do not need to be technical.

## What you are downloading

The repository contains Markdown instruction files. They teach an AI system how to follow procurement workflows.

They are not executable software by themselves. You use them by adding the files to an AI conversation, project, custom assistant, or future agent.

## Fastest way to use the assistant

### Step 1: Choose your workflow

Examples:

- New request: `procurement-intake-skill.md`
- Supplier research: `market-research-skill.md`
- RFx drafting: `rfp-drafting-skill.md`
- Pricing review: `pricing-model-review-skill.md`
- SLA review: `sla-review-skill.md`
- Contract review: `contract-risk-review-skill.md`
- Negotiation: `negotiation-prep-skill.md`
- Supplier QBR: `supplier-qbr-skill.md`
- Spend analysis: `spend-analysis-skill.md`

### Step 2: Add the parent and child skill

Add these files to the AI tool:

1. `skills/procurement-skill.md`
2. The relevant child skill
3. Your approved source documents or data

For multi-stage work, add the supporting child skills as needed.

### Step 3: Use the starter prompt

```text
Use procurement-skill.md as the parent skill and [child-skill-name]. Review the files I provided, identify missing information and assumptions, follow the skill workflow, and provide a procurement-ready output with risks, recommended next steps, and human review items.
```

### Step 4: Review the output

Before using the result:

- Validate facts and sources
- Confirm assumptions
- Review confidential information
- Obtain required legal, privacy, security, accessibility, finance, technical, and business approvals
- Keep supplier selection and final decisions with authorized humans

## Using in ChatGPT

1. Create a new Project.
2. Add the parent and child skill files as project sources.
3. Add the master instructions from `assistant/PROCUREMENT_ASSISTANT_INSTRUCTIONS.md` as project instructions.
4. Add approved procurement source documents.
5. Start a chat inside the project and use the starter prompt.

Official reference: https://help.openai.com/en/articles/10169521-projects-in-chatgpt

You may also attach the files directly to a one-off chat, but a Project is more practical for repeated work.

## Using in Claude

1. Create a Project.
2. Upload the parent and child skill files to project knowledge.
3. Add the master assistant instructions as project instructions.
4. Add approved source documents.
5. Start a project chat and use the starter prompt.

Official reference: https://support.claude.com/en/articles/9517075-what-are-projects

## Using in another AI tool

Use the same pattern if the tool supports files or persistent instructions:

1. Add the master instructions
2. Add the parent skill
3. Add the relevant child skill
4. Add source documents
5. Ask the model to follow the skill workflow

Features and file limits vary by platform and organization.

## Recommended everyday workflow

1. Start with an approved, sanitized input pack.
2. Ask the AI to identify missing information before drafting.
3. Review the first output.
4. Correct assumptions and add context.
5. Ask the AI to run the validation or challenge loop.
6. Export the result into your normal procurement template.
7. Complete human and specialist reviews.

## First three use cases to try

### 1. Intake review
Upload an intake form and use `procurement-intake-skill.md`.

### 2. Pricing review
Upload a pricing schedule and use `pricing-model-review-skill.md`.

### 3. SLA stress test
Upload an SLA section and use `sla-review-skill.md`.

These provide useful support without giving AI final decision authority.
