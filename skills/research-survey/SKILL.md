---
name: research-survey
description: Conduct structured research surveying from a topic, paper cluster, or frontier question, then turn the result into viewpoints and reusable academic content. Use when the user wants a literature map, frontier overview, research opinion summary, scholar-facing social-media content, or a repeatable workflow for topic framing, literature synthesis, and insight extraction. Especially relevant for researchers working on fast-moving technical areas such as embodied AI, robot learning, and adjacent fields.
---

# Research Survey

Use this skill when the user wants help with:

- scoping a research topic into a surveyable question
- building a structured literature map
- understanding the frontier of a technical area
- extracting sharp research viewpoints from papers
- converting a survey into social posts, threads, or long-form notes
- building a repeatable personal academic content pipeline

## Goal

Produce outputs that help the user move from vague topic to clear judgment.

The skill should prioritize:

- compressed understanding rather than paper dumping
- explicit judgments rather than neutral summaries only
- structured comparison rather than isolated paper descriptions
- reusable outputs so one survey pass yields many downstream assets

## Default workflow

Follow this order unless the user asks for a specific stage only.

### 1. Frame the topic

Turn a broad area into one concrete question with academic tension.

Good scope:

- "What actually limits generalization in robot foundation models?"
- "Which routes in dexterous manipulation are genuinely scaling?"
- "What has world modeling solved in real-world robot learning, and what remains unsolved?"

For the chosen topic, define:

- the core question
- why it matters now
- who the target readers are
- what judgment the reader should gain
- what boundary conditions are in scope and out of scope

### 2. Build the research map

Organize the area around argument and method families, not just a list of papers.

Capture:

- problem setting
- representative methods
- data and training paradigm
- evaluation setup
- hidden assumptions
- unresolved limitations

Reduce the literature into 3-5 major routes, tensions, or schools of thought.

### 3. Extract viewpoints and research judgment

After surveying, force explicit takeaways in three buckets:

- `Consensus`: what the field broadly agrees on
- `Debates`: where disagreement or uncertainty remains
- `My Take`: the sharpest 2-5 judgments worth publishing

The skill should favor claims that are specific, defensible, and useful to other researchers. Whenever possible, distinguish:

- benchmark improvement versus capability improvement
- model contribution versus data or systems contribution
- short-horizon success versus robust real-world performance

### 4. Produce a survey artifact

By default, create at least one structured survey-style deliverable.

Good options:

- topic brief
- research map
- viewpoint memo
- annotated reading list

### 5. Convert one research pass into multiple assets

By default, repurpose the same research into:

- 3 short insight posts
- 1 thread or long post with 3-5 observations
- 1 visual outline or comparison table
- 1 longer note or article outline

If the user requests only one platform, adapt tone and length but keep the same intellectual core.

### 6. Preserve a repeatable content loop

Close by proposing a reusable publication set:

- a recurring column name
- next 3-5 adjacent topics
- a lightweight cadence such as weekly or biweekly

## Output formats

Pick the lightest format that matches the request.

### A. Topic brief

Use when the user is still choosing what to study or post.

Include:

- topic title
- why now
- target audience
- 3-5 subquestions
- likely post angles

### B. Research map

Use when the user asks for a survey, landscape, or frontier snapshot.

Include:

- topic definition
- route breakdown
- representative papers or method families
- comparison dimensions
- open questions

### C. Viewpoint memo

Use when the user wants distilled judgment after reading across papers.

Include:

- 1-2 sentence thesis
- consensus
- debates
- 3-5 research judgments
- what to watch next

### D. Content pack

Use when the user wants something directly publishable.

Include:

- 3-10 short posts
- 1 thread outline
- 3-5 signature claims
- optional Chinese and English variants when helpful

### E. Series plan

Use when the user wants a durable academic presence rather than one-off posts.

Include:

- content pillar names
- monthly cadence
- 4-week topic queue
- rules for converting new papers into posts

## Writing principles

- Write for informed researchers, not general-pop audiences, unless the user says otherwise.
- Prefer "what matters and why" over broad descriptions.
- Prefer mechanism, assumptions, and evaluation quality over hype.
- Distinguish benchmark gains from real capability gains whenever relevant.
- Surface hidden assumptions and failure modes.
- Avoid hype language unless the user explicitly wants promotional tone.
- Do not merely praise papers; explain what the paper changes, assumes, or misses.

## Platform adaptation

Adapt the same core idea to the destination:

- `X/Twitter`: sharper claims, shorter sequences, more contrast
- `LinkedIn`: broader framing, stronger relevance and implications
- `Zhihu/WeChat`: deeper explanation, more context, stronger narrative continuity
- `Newsletter/long note`: more synthesis, caveats, and structured comparison

## Default prompt template

If the user is vague, ask or assume the following inputs:

- topic or research question
- target platform
- target audience
- desired output: topic brief, survey, content pack, or series plan
- language preference

If the user does not specify, default to:

- audience: researchers and advanced students
- output: content pack
- language: match the user's language

## Good final deliverable

A strong response usually contains:

- a one-sentence thesis
- a compact map of the area
- several concrete judgments
- post-ready material that sounds like a real researcher

## Example requests

- "Help me survey recent robot learning papers and turn the result into a month of X posts."
- "Build a research-survey pipeline for embodied AI topics."
- "Survey world models for robotics and extract 5 opinions worth posting."
- "Give me a frontier overview of dexterous manipulation and explain what actually matters."
