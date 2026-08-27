# Install in ChatGPT

## Native Skills (when available in your ChatGPT plan/workspace)

1. Download the individual skill ZIP you want from `packages/`.
2. In ChatGPT, open **Plugins**, then the **Skills** tab.
3. Choose **Create** and **Upload from your computer**.
4. Select the skill ZIP.
5. Review the skill before enabling it.
6. Repeat for other procurement skills you want available.

The packages follow the Agent Skills open format used by ChatGPT. Availability and admin permissions depend on the user's ChatGPT plan/workspace.

## Simple fallback: ChatGPT Project

If native Skills are not available to you:

1. Create a ChatGPT Project named `Procurement Assistant`.
2. Upload `skills/procurement-skill.md` plus the child skill files you need.
3. Add `assistant/PROCUREMENT_ASSISTANT_INSTRUCTIONS.md` as the project instructions/reference.
4. Add approved procurement documents only when your organization's AI/data policy permits it.
5. Start with a concrete request, such as: `Use the pricing model review workflow to review this 3-year SaaS pricing schedule.`

## Recommended starting set

Install the parent `procurement-skill` plus 2–3 child skills you use frequently. Add the rest as needed.
