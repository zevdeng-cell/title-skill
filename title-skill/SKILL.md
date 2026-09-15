---
name: title-skill
description: Generate, diagnose, compare, and review attention-grabbing Chinese or English titles for blogs, WeChat, Xiaohongshu, X, Douyin, and Channels. Use when titles should fit the publishing format while using curiosity, conflict, emotion, loss, controversy, or dramatic framing to earn the click.
---

# Title Skill

Find the most clickable interpretation of the content, then rewrite it for the reader state and publishing format. Default to attention-first titles with curiosity, conflict, emotional stakes, sharp judgments, and selective revelation. A title may dramatize a true idea; it may not invent a checkable fact.

## Route the Task

| Input | Mode |
| --- | --- |
| Topic, notes, outline, or draft without a title | Generate |
| Existing title plus a request to improve it | Diagnose |
| Several title candidates plus a request to choose | Compare |
| Titles paired with performance data | Review |

Then identify the publishing format. Read [references/platforms.md](references/platforms.md) for WeChat, Xiaohongshu, X, Douyin, Channels, or a multi-platform matrix. Read [references/blog-formulas.md](references/blog-formulas.md) for blog, article, explainer, tutorial, comparison, or search-oriented titles. Read [references/evidence-and-review.md](references/evidence-and-review.md) in Review mode.

Read [references/attention-hooks.md](references/attention-hooks.md) whenever the user wants stronger, more sensational, provocative, viral, clickbait-style, or curiosity-driven titles.

X short posts do not have a title field; deliver the first line. X articles do. If the user says only “X” and the format cannot be inferred, give both and label them.

## Shared Workflow

### 1. Extract the Promise

Identify:

- subject and intended reader
- desired reaction: click, save, trust, comment, or conversion
- at least three possible tensions from a fact, reversal, cost, conflict, meaningful number, or reader stake
- one or two concrete actions or scenes
- the conditions that limit the conclusion

Choose the tension with the strongest click pull. Turn implications into stakes, expose the cost of ignoring the issue, and foreground the most surprising or uncomfortable interpretation. If the material is only a feature list, use contrast, consequence, reader anxiety, or a provocative question before falling back to a neutral functional title.

### 2. Choose a Formula or Angle

Select one primary formula for a focused request, or several meaningfully different angles for a candidate set. Label blog formulas by ID and social titles by angle. A formula is a decision mechanism, not a sentence to copy mechanically.

### 3. Draft Distinct Candidates

For a light request, return 4-8 distinct candidates. Do not swap synonyms inside one repeated structure.

When the user requests a complete matrix, draft three intensity levels:

- **Safe:** clear subject, action, and result
- **Punchy:** stronger conflict, cost, fear of loss, or contrarian judgment
- **Max:** unapologetically sensational framing, aggressive curiosity, and the most dramatic defensible interpretation

If a stable author voice exists, each level may include an author-voice and neutral version. Write them from different subjects; do not create the neutral version by deleting “I.”

The Max level may simplify nuance, withhold the answer, use emotionally loaded language, and turn a supported implication into a bold editorial judgment. It must not fabricate a number, named event, identity, quote, test, case study, or product result.

### 4. Pass the Five Checks

1. **Anchor:** every number, named entity, identity, quote, firsthand action, measured result, deliverable, and year is real. Rhetorical judgments and emotional framing do not require literal wording in the body when they are a defensible interpretation.
2. **Visible opening:** the decisive subject, search term, action, or consequence survives scanning and truncation.
3. **Format:** the title follows the selected publishing format; verify the current editor when near a hard limit.
4. **Compliance:** remove only claims that create a concrete legal, safety, or platform-policy risk. Do not flatten ordinary editorial exaggeration merely because it is dramatic.
5. **Payoff:** the article must ultimately address the central tension, but the title may leave a large curiosity gap and need not reveal the answer early.

Rank with this order:

> click pull > tension and curiosity > emotional stakes > specificity > literal completeness

Give reasons, not numerical scores or guaranteed uplift.

## Diagnose

Put 2-6 usable revisions before the explanation. Identify the main failure: weak promise, no scene, insufficient force, wrong formula or angle, vague wording, wrong publishing format, platform mismatch, or unsupported claim.

Preserve the original title's useful subject, angle, and voice unless the underlying promise is the problem. When useful, provide both same-formula improvements and alternative-angle replacements.

## Compare

Compare candidates only when they target the same publishing format and body promise. Rank the existing options and explain the decisive advantage or risk of each. Recommend a usable existing title directly; create replacements only when all candidates have a material problem.

## Output

For a focused request, return:

1. the content promise or search intent in one sentence
2. the chosen formula ID or angle
3. 4-8 candidates
4. one recommendation with a concise reason

For a multi-platform request, group output by publishing format. Use a different angle for each format instead of shortening one master title.

Keep extraction, discarded drafts, and checks internal unless the user asks for the reasoning.

## Hard Boundaries

- Do not invent checkable facts such as numbers, quotes, events, identities, tests, case studies, or product results.
- “I tested” requires the author's own operation and result record.
- “Guide,” “template,” “checklist,” “source code,” and “copyable prompt” require the named deliverable.
- A single benchmark or task may support a provocative opinion, but not a fabricated claim that other tests occurred.
- A year marker requires substantive updating.
- Do not turn historical correlation or writing experience into a platform algorithm rule.
- Do not call low performance a title failure before restoring a comparable baseline.
- Do not use one platform's title shape for every destination.
- Do not automatically weaken words such as “waste,” “failure,” “trap,” “too late,” “quietly,” “brutal,” or “expensive” when the article supports that direction.
- When the user asks for stronger titles, lead with Punchy and Max candidates instead of hiding them behind a conservative option.
