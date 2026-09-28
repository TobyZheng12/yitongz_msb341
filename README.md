# Sandbox — Study Strategy App (pivoting from MCAT-specific test prep)

> A study-help app for price-sensitive college students. Started as a medical school test
> prep idea; broadened after interviews showed we lack the domain depth for MCAT-specific
> content. See decisions/001-pivot-from-mcat-focus.md.

**Live:** Not live yet. Prototype: https://claude.ai/artifact/3Zhb5ev6J9Se4JbpZL1Sp3
**Built by:** Yitong Zheng (yitongz), MSB 341 Product Management, BYU

## Context

Fill this in during Sprint 1 and keep it current. Every sprint is read against it.

- **What I am building:** A study-strategy help app for price-sensitive college students.
  Pivoted away from a pure MCAT/medical-school test-prep focus after interviews (see
  decisions/001-pivot-from-mcat-focus.md). Still exploring, and open to also pursuing a
  prospective teammate's own project idea in parallel.
- **Who it is for:** Price-sensitive college students who want better study strategies —
  validated so far with pre-med students, not exclusively medical-school specific anymore.
- **My role:** Customer discovery and team recruiting. My teammate Shulin owns building and
  iterating on the product. We are also recruiting an American teammate, since both of us are
  international students and are not permitted to run the business ourselves.
- **My user:** Pre-med / college students, starting with the 3 interviewed this sprint.

If your situation changes, revise this and note what changed. That is normal; a silent
mismatch between this file and your work is not.

## What is in this repo

| Folder | What lives here |
|---|---|
| `sprints/` | One plan and one review per sprint |
| `discovery/` | Interviews, personas, what you learned about your user |
| `design/` | Flows, screens, usability test notes |
| `product/` | The build itself |
| `specs/` | One spec per feature, written before building it |
| `gtm/` | Launch, channels, copy, experiments |
| `metrics/` | What you measure and what it says |
| `decisions/` | Numbered records of what you decided and why |

Non-code work belongs here too. An interview, a pricing model, a landing page draft, and a
usability finding are all artifacts, and they get committed like anything else.

If you build an AI feature, put its eval set in `product/evals/`. A test set is how you know
whether a change to a prompt helped or hurt.

## Running it

[How to run this locally. Fill in once you have a stack.]

## Sprints

Each sprint:

```bash
/sprint-plan     # day one, then commit the plan
# ...build...
/sprint-review   # last day, then commit the report and write your retro
```

## Ground rules

- **Spec before build.** For anything non-trivial, the spec's commit should predate the
  feature's commits.
- **Decisions get recorded.** When you make a real choice, write it in `decisions/` with the
  alternatives you rejected.
- **No real customer contact details anywhere in this repo.** Anonymize people in interview
  notes: "dental office manager, Provo" rather than a name and an email.
- **Keep `CLAUDE.md` current.** It is what your agent knows about your work. Stale context
  produces bad output.
