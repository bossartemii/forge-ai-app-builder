# Forge for ChatGPT Android

This guide is for ChatGPT Android when custom GPTs, projects, or instruction-based workflows are available.

## Best setup

1. Open ChatGPT Android.
2. Open the settings or profile menu.
3. Look for:
   - custom GPT
   - project workflow
   - reusable instructions
   - GPT builder
4. Create a new GPT or project called:
   `Forge AI App Builder`
5. Paste the contents of `SKILL.md`.
6. Add a description like:
   “Build real SaaS apps, MVPs, dashboards, and landing pages from ideas to working code, validating what can be validated and documenting any platform limitations.”

## Starter prompt

Use this prompt:

“Use Forge. Build a SaaS product from this idea: [describe the idea]. Follow the Build Until Done workflow: analyze requirements, design UX, choose stack, generate complete code, implement auth/database/API if needed, verify what is possible, fix errors, and prepare deployment instructions.”

## Realistic expectations

ChatGPT Android may not be able to:
- run the project locally
- execute the full application
- deploy to production directly

That is okay. The proper workflow is:
- generate the project and code
- verify what is possible
- clearly say what could not be checked
- give the next best step for a real environment

## Good use cases

- product requirements
- app architecture
- UI flows
- SaaS MVP generation
- code scaffolding
- documentation and deployment handoff

## Avoid

- claiming “deployment completed” without a real deploy step
- claiming “tests passed” without real test execution
- presenting a mock page as a finished product

## Goal

Use ChatGPT Android as a structured builder, not as a fake “all in one environment.”
