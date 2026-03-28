---
name: research-survey
description: Build comprehensive, evidence-based research reports from a topic, paper cluster, frontier question, company landscape, or product space, and store the result as a Markdown document. Use when the user wants a structured调研报告, frontier snapshot, deep literature map, company and product landscape, research judgment memo, or a reusable long-form report that goes beyond brief social-media repackaging. Especially relevant for researchers and research teams who need a thorough report first, with clear evidence, arguments, limitations, market context, and open questions.
---

# Research Survey

Use this skill when the user wants help with:

- scoping a research topic into a reportable question
- building a structured literature map
- mapping the relevant companies, labs, and products in a space
- producing a comprehensive and credible调研报告
- extracting sharp research viewpoints from papers
- comparing research progress with product reality
- building a reusable Markdown research report
- building a repeatable academic research communication pipeline

## Goal

Produce outputs that help the user move from vague topic to clear judgment and a reusable written report.

The skill should prioritize:

- evidence-backed synthesis rather than paper dumping
- explicit judgments rather than neutral summaries only
- structured comparison rather than isolated paper descriptions
- cross-checking academic claims against company and product reality
- comprehensive coverage before repackaging
- report-first deliverables stored as Markdown
- reusable outputs so one survey pass yields many downstream assets

## Positioning

This skill sits between a full systematic literature review and a lightweight research note workflow.

- Compared with `systematic-literature-review`, this skill is lighter and faster, but still evidence-driven and synthesis-heavy.
- Compared with `academic-social-content`, this skill is much more report-centric and much less focused on platform repackaging.
- Default outcome: produce one deep Markdown research report that covers research, company landscape, and product state when relevant.

Use this skill when the user needs a credible, detailed调研报告 but does not necessarily need a full LaTeX + BibTeX systematic review with PDF/Word export.

## Evidence scope

By default, the survey should not rely on papers alone.

When relevant, build the report from three evidence layers:

- `Research layer`: papers, benchmarks, surveys, official project pages, open-source repos
- `Company layer`: startups, labs, incumbents, research teams, ecosystem players, commercial actors
- `Product layer`: shipped products, public demos, SDKs, hardware platforms, deployment claims, pricing or capability disclosures when available

The report should explicitly state which layers were covered and where evidence is missing.

## Default workflow

Follow this order unless the user asks for a specific stage only.

### 1. Frame the topic

Turn a broad area into one concrete question with academic tension and practical reporting value.

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
- what concrete decision, understanding, or discussion the report should support
- whether the report should include company and product landscape analysis

### 2. Build an evidence map

Organize the area around argument and method families, not just a list of papers.

Capture:

- problem setting
- representative methods or system routes
- data and training paradigm
- evaluation setup
- hidden assumptions
- unresolved limitations
- relevance to the user's reporting goal
- important companies, labs, and products in the space
- where product claims match or exceed the published research
- where commercial messaging appears stronger than the public evidence

Reduce the literature into 3-5 major routes, tensions, or schools of thought.

When helpful, sort papers or method families into:

- `Core evidence`: most central to the topic
- `Supporting evidence`: useful for comparison or context
- `Peripheral evidence`: background only, should not anchor the main claim

When company or product analysis is relevant, also classify:

- `Research leaders`: groups defining the frontier technically
- `Product leaders`: teams or vendors closest to usable deployment
- `Ecosystem enablers`: platform, tooling, data, or hardware providers

For a strong report, also identify:

- what evidence is repeated across multiple papers
- what claims rely on narrow settings or weak evaluation
- which technical routes are mature, emerging, or overclaimed
- which companies are translating research into products
- which products show real capability versus demo-heavy positioning

### 3. Extract viewpoints and research judgment

After surveying, force explicit takeaways in three buckets:

- `Consensus`: what the field broadly agrees on
- `Debates`: where disagreement or uncertainty remains
- `My Take`: the sharpest 2-5 judgments worth publishing

The skill should favor claims that are specific, defensible, and useful to other researchers or informed industry readers.

Whenever possible, distinguish:

- benchmark improvement versus capability improvement
- model contribution versus data or systems contribution
- short-horizon success versus robust real-world performance
- academic novelty versus deployable value
- publication visibility versus product readiness

### 4. Produce one deep report artifact

By default, create one structured long-form report as the primary deliverable.

Good options:

- topic brief
- research map
- viewpoint memo
- annotated reading list
- deep research report

The report should be evidence-backed, sufficiently detailed, and understandable to an informed reader who did not follow the raw papers.

The report should normally include:

- title
- executive summary
- topic framing
- scope and boundaries
- literature map
- company landscape
- product landscape
- route-by-route analysis
- representative evidence or papers
- comparison dimensions
- consensus
- debates
- the strongest research judgments
- major players and what each is actually building
- product maturity, deployment signals, or commercialization gaps
- limitations of the current field
- practical implications
- open questions and what to watch next

### 5. Save the output as a Markdown document

By default, write the final report to a Markdown file in the working directory.

Unless the user specifies another filename, use a safe descriptive name such as:

- `{topic_slug}_research_report.md`
- `research-survey-{topic_slug}.md`

The Markdown document should be publication-ready, with clear headings, readable structure, and minimal fluff.

### 6. Preserve a repeatable research loop

Close by proposing:

- next 3-5 adjacent topics
- the most important missing evidence to track
- a lightweight cadence such as weekly or biweekly
- a rule for updating the Markdown report as the field evolves

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
- suggested report angle

### B. Research map

Use when the user asks for a survey, landscape, or frontier snapshot.

Include:

- topic definition
- route breakdown
- representative papers or method families
- comparison dimensions
- open questions
- strongest evidence anchors

### C. Viewpoint memo

Use when the user wants distilled judgment after reading across papers.

Include:

- 1-2 sentence thesis
- consensus
- debates
- 3-5 research judgments
- what to watch next

### D. Deep research report

Use when the user wants a polished, comprehensive调研报告 as the main output.

Include:

- title
- executive summary
- why now
- scope and boundaries
- 3-5 major routes or trends
- representative evidence or papers
- relevant companies, labs, and commercial actors
- relevant products, platforms, or public deployments
- comparison table or structured bullets
- key judgments
- consensus
- debates
- company landscape summary
- product landscape summary
- practical implications or industry relevance
- risks, limitations, or caveats
- open questions
- recommended next reading or tracking directions
- output filename in Markdown

### E. Content pack

Use only when the user explicitly wants downstream publishable content after the report is done.

Include:

- 3-10 short posts
- 1 thread outline
- 3-5 signature claims
- 1 media-summary paragraph
- optional Chinese and English variants when helpful

### F. Series plan

Use when the user wants a durable academic presence rather than one-off posts.

Include:

- content pillar names
- monthly cadence
- 4-week topic queue
- rules for converting new papers into reports and posts

## Writing principles

- Write for informed researchers, technical operators, decision-makers, or advanced industry readers unless the user says otherwise.
- Prefer "what matters and why" over broad descriptions.
- Prefer mechanism, assumptions, and evaluation quality over hype.
- Distinguish benchmark gains from real capability gains whenever relevant.
- Surface hidden assumptions and failure modes.
- Avoid hype language unless the user explicitly wants promotional tone.
- Do not merely praise papers; explain what the paper changes, assumes, or misses.
- Keep claims inside the evidence boundary established by the report.
- Prefer one coherent long-form argument over fragmented platform-specific rewrites.
- Do not treat company messaging as equivalent to validated evidence; separate demo claims, shipped capabilities, and proven deployment.

## Report style guidance

The report should read as credible research communication rather than marketing copy.

- Lead with a sharp thesis, not a paper list.
- Explain why the topic matters now in terms the target media outlet can use.
- Use evidence clusters and representative papers, not exhaustive bibliography dumps.
- Surface disagreement and uncertainty instead of pretending the field is settled.
- End with implications, not just summary.

## Markdown delivery guidance

The default deliverable is a Markdown document.

When writing the Markdown file:

- use a clear title and section headings
- keep sections logically ordered from framing to evidence to judgment
- include short bullet lists only where they improve scanability
- prefer paragraphs for synthesis and explanation
- include a final "Sources" section when the evidence comes from identified papers or project pages
- separate sources by type when useful, for example `Papers`, `Companies`, `Products`, `Project pages`

## Default prompt template

If the user is vague, ask or assume the following inputs:

- topic or research question
- target audience
- desired output: topic brief, research map, deep research report, or series plan
- language preference
- output path or filename if specified
- report goal: inform, compare technical routes, support decisions, or support external communication
- whether to include company and product landscape analysis

If the user does not specify, default to:

- audience: researchers, advanced students, and informed industry readers
- output: deep research report
- language: match the user's language
- filename: `{topic_slug}_research_report.md`
- report goal: build a credible deep-dive understanding
- landscape scope: include papers, companies, and products when relevant

## Good final deliverable

A strong response usually contains:

- a one-sentence thesis
- a compact map of the area
- several concrete judgments
- a report-ready structure
- enough depth that the report can stand on its own
- a clear distinction between research evidence, company positioning, and product reality
- a Markdown file path when the report is written to disk

## Example requests

- "Help me survey recent robot learning papers and write a deep Markdown research report."
- "Build a research-survey pipeline for embodied AI topics that outputs one thorough调研报告 per topic, including key companies and products."
- "Survey world models for robotics and give me an evidence-backed long-form report with company landscape."
- "Give me a frontier overview of dexterous manipulation as a detailed Markdown调研报告, and compare the main products and teams."
