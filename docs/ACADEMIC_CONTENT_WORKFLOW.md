# Academic Content Workflow

This document captures a reusable Codex workflow for turning a research topic into scholar-facing social content.

## Best setup

Use two layers together:

- a reusable skill for Codex to follow automatically
- a short workflow document for you to inspect, refine, and hand off

## Repository paths

- `skills/research-survey/SKILL.md`
- `docs/ACADEMIC_CONTENT_WORKFLOW.md`

## When to use this workflow

Use it when you want to turn any of the following into academic outreach content:

- a frontier topic
- a literature cluster
- a survey idea
- a controversial research question
- a batch of recent papers
- a long-form note that should be repurposed into shorter posts

## Recommended reuse pattern

When starting a future Codex session, you can say things like:

- `Use the research-survey skill to help me turn robot foundation model generalization into a 4-week content series.`
- `Use the research-survey skill and give me a survey plus 5 X posts on dexterous manipulation.`
- `Use the research-survey skill to extract social-media-worthy viewpoints from recent world model for robotics papers.`

## Workflow stages

### 1. Topic framing

Define one concrete question, not a whole field.

Outputs:

- topic title
- why now
- target audience
- 3-5 subquestions

### 2. Structured survey

Map the field into a few routes or tensions.

Outputs:

- representative approaches
- comparison dimensions
- hidden assumptions
- limitations and open problems

### 3. Viewpoint extraction

Force judgments after the survey.

Outputs:

- consensus
- debates
- your take

### 4. Content conversion

Turn one research pass into multiple publishable assets.

Outputs:

- short posts
- thread outline
- visual or table idea
- long-form outline

### 5. Series planning

Convert one topic into a recurring content engine.

Outputs:

- column names
- cadence
- next topic queue

## Why a skill is better than only a document

A document is good for human reference, but a skill is better when you want Codex to consistently:

- recognize the scenario
- follow the same step order
- produce the same kinds of outputs
- preserve the distinction between survey, viewpoint, and post-ready content

## Suggested future enhancements

- add a `references/` folder with reusable templates for X, Zhihu, WeChat, and LinkedIn
- add an `evals/` folder with test prompts for different research areas
- add bilingual output conventions for Chinese and English academic audiences
- add a robot-learning-specific variant of this skill
