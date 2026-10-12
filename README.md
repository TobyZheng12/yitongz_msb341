# PengPal — local company for foreign travelers in China

> A platform where foreign travelers in China can find local Chinese people who speak their
> language. Replaced the medical school test prep idea in Sprint 2, after OpenAI's Muse and
> Dots launched and could do what we were planning. See decisions/002-pivot-to-pengpal.md.

**Live:** Not live yet. PengPal is at the pitch and business brief stage.
**Built by:** Yitong Zheng (yitongz), MSB 341 Product Management, BYU

## Context

Updated Sprint 2 (Oct 12, 2026). Changed from the study-strategy app because interviews and
competitor research killed that idea; see decisions/002-pivot-to-pengpal.md.

- **What I am building:** PengPal, a platform connecting foreign travelers in China with local
  Chinese people who speak their language. Previously a medical school test prep app, then a
  study-strategy app; both dropped in Sprint 2.
- **Who it is for:** Foreign travelers in China who do not speak Chinese, and the local Chinese
  people who want to meet them.
- **My role:** Customer discovery, competitor research, pitching, and teammate recruiting. My
  teammate Shulin works alongside me. We are still recruiting a third teammate, since neither of
  us can legally run the business as international students. I also build my own apps with
  Claude Code and Codex to learn the tools, listed below.
- **My user:** Foreign travelers going to China, and English-speaking locals in Chinese cities.

If your situation changes, revise this and note what changed. That is normal; a silent
mismatch between this file and your work is not.

## Where the work lives

- **Repos:** TobyZheng12/yitongz_msb341 (this one, shared with sdmurff and nmccaul);
  TobyZheng12/coffeechat-ai (public); TobyZheng12/TOBY.PAGE (public). The scripture study app
  is a local repo with no GitHub remote.
- **Live:** https://coffeechat-ai-six.vercel.app/ (CoffeeChatAI — networking assistant that
  generates call scripts, tracks follow-ups, and records notes); https://yitongz.com (personal
  professional website); https://scripture-primer.vercel.app/ (scripture study app).
- **Docs:** PengPal business brief for the advisor, and the Big Idea Competition pitch deck and
  video (submitted Oct 8, 2026).

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
