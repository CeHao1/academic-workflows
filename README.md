# academic-workflows

Reusable Codex workflows and skills for academic research communication.

## Repository structure

```text
academic-workflows/
  README.md
  .gitignore
  docs/
    ACADEMIC_CONTENT_WORKFLOW.md
  skills/
    research-survey/
      SKILL.md
      references/
        platform-templates.md
        robot-learning-angles.md
```

## Current skills

| Skill | Purpose | Key outputs |
| --- | --- | --- |
| `research-survey` | Turn a research topic, literature cluster, frontier question, company landscape, or product space into a comprehensive, evidence-based Markdown research report | topic brief, research map, viewpoint memo, deep research report, series plan |

## Supporting docs

- `docs/ACADEMIC_CONTENT_WORKFLOW.md`
  A human-readable workflow note describing how to reuse the skill and how the content pipeline is organized.

## Recommended usage

In a future Codex session, refer to the skill explicitly, for example:

- `Use the research-survey skill to turn robot foundation model generalization into a deep Markdown research report with key companies and products.`
- `Use the research-survey skill and give me a research map plus a detailed report on dexterous manipulation, including the main teams and platforms.`
- `Use the research-survey skill to extract evidence-backed viewpoints from recent world-model-for-robotics papers and compare them with the current product landscape in a Markdown report.`

## How to add a new skill

For each new skill, create one folder under `skills/`:

```text
skills/
  new-skill-name/
    SKILL.md
    references/
```

Use this rule of thumb:

- put trigger logic, workflow, and output requirements in `SKILL.md`
- put reusable examples, templates, and domain notes in `references/`
- keep repo-wide guidance in the root `README.md` or `docs/`

## Suggested repository growth

Over time, this repo can include:

- more skills for specific academic tasks
- `references/` folders with reusable templates
- robot-learning-specific variants
- evaluation prompts for testing workflow quality
