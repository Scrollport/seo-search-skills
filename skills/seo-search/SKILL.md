---
name: seo-search
description: Route an SEO or search request to the smallest verified Scrollport Skill for opportunity research or a cited content brief. Use for "improve our SEO," "find organic opportunities," "keyword research," "content plan," or "SEO content brief" when the requested artifact is not yet clear.
license: MIT
metadata:
  scrollport-status: verified
---

# SEO and search

Choose one outcome before selecting tools or spending credit. This router does
not perform SEO research itself; it loads the smallest verified function Skill
that owns the requested deliverable.

Before routing, use any supplied positioning, audience or client brief. If the
project contains `.agents/product-marketing.md`, read it as context; it is not
evidence and does not replace the task-specific domain, market or objective.

## Route the request

- Use [SEO Opportunity Map](../seo-opportunity-map/SKILL.md) when the user needs
  to compare a domain with search competitors, identify evidence-backed organic
  opportunities, decide which topics deserve further work, or when the user gives a broad
  request such as “improve our SEO.”
- Use [SEO Content Brief](../seo-content-brief/SKILL.md) when the user already
  has a business topic or selected opportunity and needs a cited, writer-ready
  brief.
- For a broad request such as “improve our SEO,” start with SEO Opportunity Map
  unless the user already supplied a prioritised topic and explicitly wants a
  brief.

Do not execute both function Skills merely because both are installed. If the user
wants the sequence, complete and review the opportunity map first; treat any
selected topic and second paid plan as a new checkpoint before loading the
content-brief workflow.

Return the selected Skill, the artifact it will produce and why the other route
does not own the current job. Do not make the user choose between tool names.

## Boundaries

The available function Skills do not provide continuous rank tracking, a full
technical site audit, content publication, backlink outreach or ranking
guarantees. State that boundary when the requested outcome falls outside the
package; do not improvise a new paid workflow under the router.

After choosing a function, read its complete `SKILL.md` and follow its inputs,
cost ceiling, approvals, state and acceptance criteria. If the selected Skill
is not present in the current installation, ask before installing it from this
repository and pin the source revision.
