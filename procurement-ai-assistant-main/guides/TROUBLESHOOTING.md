# Troubleshooting

## The answer is too generic

- Add the relevant child skill
- Provide the business context and procurement stage
- Include source documents
- State the desired output format
- Ask the AI to list assumptions before proceeding

## The AI ignores the skill

Use this prompt:

```text
Before answering, confirm which skill file you are applying. Follow its workflow, review checks, output format, human review requirements, and guardrails.
```

## The output is too long

Specify:

- Audience
- Maximum length
- Required sections
- Whether details should be placed in an appendix

## The AI invents information

Stop and ask it to:

- Separate facts, assumptions, and unknowns
- Cite the source document or section
- Remove unsupported claims
- List items requiring validation

## Too many skills are loaded

Use progressive disclosure. Keep the parent skill and only the one or two child skills required for the current stage.

## The output sounds like legal advice

Ask the AI to separate:

- Procurement/commercial observations
- Legal questions for counsel
- Business decisions

## The AI makes a supplier recommendation

Remind it that supplier selection and award decisions are outside the skill's authority. Ask for an evidence table and human decision points instead.
