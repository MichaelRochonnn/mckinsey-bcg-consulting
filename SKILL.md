---
name: mckinsey-bcg-consulting
description: |-
  Use this skill as a router and knowledge graph for McKinsey/BCG-style consulting methods. Use when the user asks for structured problem solving, MECE issue trees, hypothesis-driven analysis, strategy, operations, execution, stakeholder management, consulting communication, proposals, high-pressure corporate navigation, professional-service career development, or applying multiple consulting frameworks together.
metadata:
  short-description: McKinsey/BCG consulting method router
---

# McKinsey & BCG Consulting Skill Library

This is the hub skill for the consulting-method library. It coordinates 75 focused sub-skills from the two source libraries:

- `麦肯锡方法`
- `麦肯锡 & 波士顿 - 解决问题方法和创造价值技巧`

Use this hub when the user describes a broad business, strategy, execution, communication, or career problem and may need more than one framework.

## Operating Rule

First classify the user's request, then load only the needed child skill files. Do not load every sub-skill.

1. Identify the situation type: problem solving, research, strategy, communication, execution, people dynamics, operations, growth, or career.
2. Select 1-4 child skills from the routing table below.
3. Read each selected child `SKILL.md`; read its `references/` files only if the child skill points to a needed example/template.
4. Apply the frameworks to the user's concrete context. State assumptions, separate facts from hypotheses, and avoid presenting framework labels as a substitute for judgment.
5. For complex work, produce an actionable consulting output: issue tree, hypotheses, evidence plan, recommendation, execution plan, stakeholder plan, or decision memo.

## Quick Routing

Use these as the first-pass entry points:

| User need | Start with | Often combine with |
|---|---|---|
| Define a fuzzy business problem | `mckinsey-problem-solving-methodology` | `mckinsey-issue-tree-structuring`, `mece-compliance-validation` |
| Build an issue tree or analysis structure | `structured-problem-solving-mckinsey` | `mckinsey-issue-tree-structuring`, `key-driver-analysis` |
| Validate MECE logic | `mece-compliance-validation` | `mckinsey-problem-solving-methodology-2` |
| Prioritize many initiatives | `impact-speed-prioritization-matrix` | `pareto-analysis-resource-optimization`, `work-prioritization` |
| Analyze market strategy | `3c-analysis-overlap-dynamics` | `external-forces-analysis`, `dynamic-strategic-positioning` |
| Analyze data without false correlation traps | `hypothesis-driven-data-analysis` | `fact-creation-methodologies`, `fact-based-research-mckinsey` |
| Prepare a client or executive presentation | `consulting-proposal-structures` | `mckinsey-communication-principles`, `effective-presentation-communication` |
| Run interviews or gather facts | `expert-interviewing-mckinsey` | `interview-techniques`, `mckinsey-research-methodology` |
| Move from recommendation to implementation | `mckinsey-project-lifecycle` | `project-execution-management`, `change-management-implementation`, `implementation-scaling-motivation-strategy` |
| Improve operations or manufacturing | `qcd-issue-tree-production-analysis` | `toyota-stop-valve-protocol`, `process-standardization-for-leverage` |
| Manage stakeholders or client buy-in | `consulting-client-engagement` | `difficult-stakeholder-management`, `esg-stakeholder-management` |
| Build or manage a consulting team | `team-facilitation-mckinsey` | `team-management-and-mobilization`, `team-cohesion-management` |
| Improve personal consulting effectiveness | `mckinsey-professional-principles` | `motivation-flow-state-management`, `left-right-brain-connectivity` |
| Navigate career or organization politics | `mckinsey-organization-dynamics` | `active-mentor-finding-management`, `career-expectation-management` |

## Reference Navigation

- Read `references/knowledge-graph.md` when you need the full domain map and dependency graph.
- Read `references/skill-index.md` when you need the complete list of child skills and their best-use cases.
- Read `references/workflow-compositions.md` when the task spans multiple phases and you need a recommended multi-skill sequence.

## Output Standards

Default to a concise consulting work product:

- Situation: the decision or problem in one paragraph.
- Structure: issue tree, options, or decision matrix.
- Analysis: facts, hypotheses, risks, and unknowns.
- Recommendation: the highest-leverage action with rationale.
- Next steps: owner, timing, evidence to collect, and stakeholder moves.

When the user asks for brainstorming, facilitation, interview scripts, proposal pages, project plans, or career coaching, adapt the output format to that artifact.

## Guardrails

- Use these frameworks as professional heuristics, not as proof of correctness.
- Do not invent proprietary McKinsey or BCG claims. If a point is inferred from the local library, say it as a framework-derived recommendation.
- Prefer the user's real constraints over textbook completeness.
- If the task is high-stakes, call out what should be verified with current data, legal/financial advice, or primary sources.
