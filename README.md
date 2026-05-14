# McKinsey & BCG Consulting Skill Library

## About

`mckinsey-bcg-consulting` is a Codex Skill library for applying McKinsey/BCG-style consulting methods to complex business work. It packages structured problem solving, MECE issue trees, hypothesis-driven analysis, strategy, operations, executive communication, stakeholder management, implementation planning, and professional-development playbooks into one reusable skill system.

The library is designed as a router plus a set of focused child skills: use the hub skill when a problem spans multiple consulting domains, or call a child skill directly when the task is narrow.

## What Is Included

- `SKILL.md`: the hub skill and routing layer.
- `references/knowledge-graph.md`: the consulting-method knowledge graph.
- `references/skill-index.md`: the full child skill index.
- `references/workflow-compositions.md`: recommended multi-skill workflows.
- 75 child skills covering problem solving, research, strategy, communication, execution, operations, teams, clients, and career navigation.

## Install

Copy this repository into your Codex skills directory:

```bash
cp -R mckinsey-bcg-consulting ~/.codex/skills/
```

Then restart or refresh Codex so the skill list is reloaded.

## Usage

Use the hub skill for broad business problems:

```text
Use $mckinsey-bcg-consulting to structure this market-entry problem and recommend an analysis path.
```

Call a specific child skill when you already know the needed framework:

```text
Use $mece-compliance-validation to check this issue tree.
Use $consulting-proposal-structures to turn this recommendation into a client-ready proposal.
Use $hypothesis-driven-data-analysis to evaluate whether these correlations imply causation.
```

## Common Workflows

- Strategy case: problem definition, issue tree, 3C analysis, external forces, prioritization, recommendation narrative.
- Executive memo: structured analysis, key drivers, concise recommendation, risks, and next steps.
- Data-heavy analysis: hypotheses, causality checks, fact gaps, and evidence plan.
- Transformation: client engagement, project lifecycle, execution management, change governance, scaling.
- Operations crisis: stop-valve protocol, QCD issue tree, root-cause analysis, process standardization.
- Career navigation: organization dynamics, expectations, mentorship, professional principles, boundaries.

## Design Principles

- Load only the child skills needed for the task.
- Treat frameworks as decision aids, not automatic answers.
- Separate facts, hypotheses, assumptions, and recommendations.
- Prefer practical next steps over exhaustive textbook coverage.

## Repository

GitHub: https://github.com/MichaelRochonnn/mckinsey-bcg-consulting
