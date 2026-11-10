# Sprint 4 Review

**Window:** 2026-11-02 08:22 (plan committed) to 2026-11-09 night
**Sessions reviewed:** 15 across 4 projects (Claude Code 4, Codex 11; 11 sessions excluded at your request)
**Active session time:** about 9.5 hours (gaps under 15 minutes)
**Not visible to this review:** team meetings about twice a week; in-person interviews with 5+ students and professors who are interested in China or have traveled there; the China legal summary and equity doc, written in Claude Docs on claude.ai; Shulin's own work

## Where the work lives

| Place | Commits in the window | Shared with sdmurff |
|---|---|---|
| TobyZheng12/yitongz_msb341 (this repo) | 4 (Nov 2: Sprint 4 plan. Nov 9: learning log, README listing the Sprint 4 docs, plan change note) | Yes |
| shulinzzz/MSB-341_Shulin_Repo (teammate's repo, public) | 12, all by Shulin, on Nov 7 and Nov 9 (local time): prototype v2, the PengPal China operating strategy (a copy of your Nov 5 proposal, anonymized), decision 005 (Day One uses the language-exchange model, sold as a trip pass), mentor feedback notes, target customers, customer journey and channels | Public |
| TobyZheng12/coffeechat-ai | 0 | Yes |
| TobyZheng12/TOBY.PAGE | 0 | Invited Oct 26 |

- **Docs:** China legal summary, "PengPal 在中国合规运营：问题与解决方案" (Nov 5), https://claude.ai/artifact/XdyZ7eNXAHpxXoDogXVTCZ. Equity doc, "PengPal Team Talk: Equity, Money & Mission Handoff" (Nov 2), https://claude.ai/artifact/6X6hFvNh7bH5meAGhHBjSS. The next-steps lists are checklists inside these two docs. Both are set to "anyone with the link".
- **Live:** PengPal prototype at https://shulinzzz.github.io/MSB-341_Shulin_Repo/product/pengpal/; https://coffeechat-ai-six.vercel.app/; https://yitongz.com; https://scripture-primer.vercel.app/

## When you worked

Sessions were active on 7 of the 8 days in the window: Nov 2 through Nov 7, and Nov 9. Nov 8 had no sessions in the confirmed projects. Most prompts came on Nov 2 and Nov 3 (the plan, the grant question, the first mentor call prep) and on Nov 9 (meeting prep, the `/learn` session, and the wrap-up). Nothing was committed to this repo between Nov 2 and Nov 9.

## Where you got stuck

- **Finding where Scripture Central was built.** On Nov 2 you asked whether the scripture app was made in Claude Code or Codex and asked to see its database schema. The same two prompts were sent again on Nov 3. The sessions do not show a final answer.
- **Getting sprint output into checkable places.** On the last night, none of the five "done looks like" items were in this repo. The legal summary and equity doc existed in Claude Docs, and you chose to link them from the README rather than copy them in. The contact-after-booking prototype change had not been built; you gave the reason (the legal research changed the contact model), and the plan now records the move to Sprint 5.
- **The `/learn` session.** You started at Developing, asked to be taught directly instead of answering the first predict question, then asked to end early. The log is marked "stopped early".

## What took the most time

By prompt volume, the most time went to meeting and networking prep in the Codex "Networking" project, across Nov 3 to Nov 9: a Sandbox mentor call, a startup CTO, founders and executives, a BYU alumni relations manager, and follow-up messages. It also covered a question on whether an F-1 student can use the Rollins validation grant to reimburse a car rental used for customer interviews. The second-largest block was the Nov 9 evening wrap-up in this repo: the `/learn` session, the README, the plan change, and this review.

## Builder tools you used

Counts cover the whole of each confirmed session. Two of the sessions began before Nov 2, so some counts (for example `claude-api` and `vercel:deploy`, from an Oct 12 build session) come from before this sprint.

| Building block | What it is | What you used this sprint |
|---|---|---|
| Skills you wrote | Skills outside the course set | claude-api (1), vercel:deploy (1), from installed plugins, not written in this repo |
| Course skills | sprint-plan, sprint-review, sprint-coach, learn, eli5 | sprint-plan (2), sprint-review (2), learn (2) |
| Plugins | Skills or subagents that came from a plugin | vercel (1) |
| Slash commands | Commands typed with `/` | model (2) |
| Hooks | Scripts the harness runs on events | SessionStart:startup ran 6 times; none blocked |
| Subagents, named | Agents from `.claude/agents`, a plugin, or you | not used |
| Subagents, built-in | Claude Code's own, such as Explore | not used |
| Messages to other sessions | Sending work to another session | not used |
| Plan mode | Plan tool calls and turns in plan mode | not used |
| Permission mode | Turns in each mode | `auto` (100) |
| Permission prompts and denials | Prompts you answered, and calls a rule or check denied | allowed by a rule 17, approved by you 6, blocked by auto mode 1, denied by a rule 1 |
| Where sessions ran | Surface each session ran on | Claude desktop app 3, terminal or IDE 1, VS Code extension 1 |
| Worktrees | Isolated git checkouts | not used |
| Memory and instructions | Files loaded into sessions | MEMORY.md loaded 4 times, CLAUDE.md 1 time; memory file project-msb341-sprints.md edited 3 times, MEMORY.md 1 time |
| Reaching outside the repo | Service CLIs, MCP connectors, direct API calls | CLIs: gh 42, supabase 37, vercel 19. MCP: Claude Browser 86, Claude Docs 4, Google Drive 2, terminal 4, app session tools. Direct API calls: curl 14 |

Not used this sprint: subagents, plan mode, worktrees, messages to other sessions. Codex sessions do not show these building blocks; the table reflects the 4 Claude Code sessions.

Scan version: 2026-10-16.

## Users this sprint

| Date | What happened | Change that followed |
|---|---|---|
| Nov 3 to Nov 4 | A Sandbox mentor met with you about PengPal (meeting prep in Codex; notes kept in Notion) | Shulin's repo has "PengPal Sprint 4 mentor feedback notes" (Nov 9) and decision 005 the same night; the link between them is not shown in the sessions |

The scan found no other outside users of the work in the sessions. The in-person interviews you reported are not visible to this review.

## Learning sessions

1 session logged in the window: Application Architecture 1.

- **2026-11-09, Design the Data Model First** (Application Architecture). Logged as 10:44 to 21:51 with time away; stopped early. You asked to be taught in English and Chinese, to be taught directly instead of answering the first predict question, and to end quickly. Starting point Developing; confidence at the end Proficient. Still wondering: nothing.

You studied Application Architecture; the sprint's work was Launch and Learn.

## Axis

**Launch and Learn.** Most of the sprint's output was about how PengPal can operate as a business: the China legal summary and operating models, the equity and revenue rules, and the trip-pass model in decision 005. This is split with Discovery, because the customer interviews and mentor meetings were reported but are not visible in the sessions.

## Against your plan

**Goal was:** On November 9, find ways to run PengPal legally in China and make it workable for customers and guides; discover and discuss the equity of the company; start next steps for PengPal; learn more of the course website.

- Legal summary: done (Claude Doc, Nov 5).
- Equity document: drafted (Claude Doc, Nov 2). The sessions do not show whether the team discussion happened; it is listed under "not visible".
- Next-steps list: done, as checklists inside the two docs.
- Contact-after-booking prototype change: not done. Moved to Sprint 5 on Nov 9, with your reason in the plan's Changes note.
- `/learn` with a log in `learning/`: done (stopped early).

Four of the five items exist and can be checked. One moved to the next sprint, and the plan file records why.

---

## Your retro

*The builder's own answers, recorded word for word in step 7.*

**Did you hit the goal?** YES, I think I hit the goal, because I am able to learn and negotiate with my teammate on equity of the compnay, and we both agreed, and we found another co founder to join us to help us, and we are going to keep working on the equity and make it offical. We also learned a lot about the legal issue, and how to best make it work in china, and we've been able to talk to different people and get advise on market fit and also legal issue

**Hours, your estimate:** I worked on these for about 18-24 hours

**If the plan changed, why?** the main plan is the same, and we changed a little because of the legal issue that may make us change direction, but most plans are the same, and helped us achieve our goals.

**Actual difficulty:** 4

Because I had to negotiate with my teammate, and it was hard and it may affect how we work with each other, but it went well, and it also is hard to overcome the legal problem and issue. And it is also busy that we had to work on the Merit medical case competition but we did win 1st place.

**What will you change next sprint?** I will utilize AI, claude code to best help me achieve the goals and plans

A scheduled taks to remind me
