# Install in Claude

The `packages/` folder contains Claude-ready custom Skill ZIPs.

## Prerequisite

Claude Skills require **Code execution and file creation** to be enabled. Organization settings can affect availability on Team and Enterprise accounts.

## Install a custom skill

1. Download the individual ZIP you want from `packages/`, for example `pricing-model-review-skill.zip`.
2. In Claude, go to **Customize > Skills**.
3. Select the **+** button, then **Create skill**.
4. Choose **Upload a skill**.
5. Upload the ZIP.
6. Enable the skill.
7. Repeat for other procurement skills you want Claude to use.

Claude reads the skill metadata first and can load the full instructions when a request is relevant. Multiple enabled skills can be used together when relevant.

## ZIP structure

Each installer in this repository is packaged as:

```text
pricing-model-review-skill.zip
└── pricing-model-review-skill/
    ├── SKILL.md
    └── LICENSE.txt
```

Do not upload `procurement-ai-assistant-all-skill-zips.zip` directly as a skill. Extract it first, then upload the individual skill ZIPs.

## Test after install

Try: `Review this SaaS renewal pricing and identify cost drivers, renewal exposure, comparability issues, and questions we should ask the supplier.`

Claude should use the relevant enabled procurement skill automatically. If it does not, make the request more explicit and confirm the skill is enabled.
