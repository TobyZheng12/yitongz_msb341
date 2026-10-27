# Sprint 3 Review

**Window:** 2026-10-14 to 2026-10-26
**Sessions reviewed:** 7 across 4 projects (Claude Code 4, Codex 3; 23 sessions excluded at your request)
**Not visible to this review:** meetings with Shulin to plan and rehearse the Big Idea pitch,
the competition itself on Oct 23, the in-person usability tests on Oct 21 and Oct 26 (written up
afterward, see below), design discussions with Shulin about the prototype, and studying for the
course midterm, including earlier concepts (Agentic Workflow and Design), outside these sessions. You also reported talking with more than five Chinese-speaking BYU
students about PengPal; three of those conversations are written up. Shulin's PengPal prototype
work happened in her repo; its commits are listed below.

## Where the work lives

- **TobyZheng12/yitongz_msb341** (this repo, shared with sdmurff and nmccaul): 8 commits in the
  window, including this review. The Sprint 3 plan (Oct 14); on Oct 26, a course skill refresh,
  the `/learn` skill, the README update listing the PengPal prototype and the Big Idea result,
  two learning logs, and the two usability test write-ups with updated insights.
- **shulinzzz/MSB-341_Shulin_Repo** (Shulin's course repo, public): 2 commits to
  `product/pengpal/` on Oct 21, both by Shulin. They added host photos with $24 visit and $40
  half-day pricing, and renamed PengPal's Chinese name to 朋派. Live at
  https://shulinzzz.github.io/MSB-341_Shulin_Repo/product/pengpal/ as an eight-screen
  interactive demo of one trip, with sample people and costs and no real bookings.
- **TobyZheng12/coffeechat-ai** (public; invited sdmurff on Oct 26, not yet accepted): 2 commits.
  - Oct 16: Fix parsed titles keeping articles ('an a procurement intern')
  - Oct 16: Fix spoken introductions: separate profile source text from spoken language
  - Live at https://coffeechat-ai-six.vercel.app/
- **TobyZheng12/TOBY.PAGE** (public; invited sdmurff on Oct 26, not yet accepted): 1 commit.
  - Oct 20: Add CoffeeChat AI project and BYU research experience
  - Live at https://yitongz.com
- **scripture-primer** (local repo, no GitHub remote): 0 commits in the window.

## When you worked

Recorded work happened on 7 of the 13 days: Oct 14, 15, 16, 20, 21, 22, and 26 (Oct 21 is the
first usability test, which you reported). Most of it came in three places: CoffeeChat AI fixes
on Oct 15 and 16, the first usability test and Big Idea pitch preparation from Oct 21 to the
morning of Oct 23, and the second usability test, both learning sessions, and this wrap-up on
Oct 26. Nothing was recorded on Oct 17, 18, 19, 24, or 25.

## Where you got stuck

- **CoffeeChat AI on Oct 15 and 16.** You found your own personal information showing in the
  public app and asked for it to be fixed. Two of the responses were cut off mid-stream and had to
  be resumed. The work ended with two bug-fix commits on Oct 16, for parsed job titles and spoken
  introductions.
- **The pitch the day before the competition.** On Oct 22 the slides were due within an hour,
  and you questioned whether the $24 price worked for the business. You asked for a mentor-style
  critique of content, speaker notes, and design. After the slides were turned in, you asked for
  a new script for the third slide. You pitched on Oct 23 and placed 2nd, plus Crowd Choice.
- **The User Stories learning session.** It started at 11:11 on Oct 26 and stopped before the
  end. You then asked to finish the next section as fast as possible, and the Running a Usability
  Test session ran in quick mode for 11 minutes.

## What took the most time

By prompt volume in the confirmed sessions, the two largest blocks were Oct 26 (the two learning
sessions, an audit of the APIs in your own apps tied to the Anatomy of an Application chapter,
and this wrap-up) and Oct 22 to 23 (pitch content, pricing, and the script). The CoffeeChat AI
fixes were fewer prompts but long, tool-heavy responses.

## Builder tools you used

| Building block | What it is | What you used this sprint |
|---|---|---|
| Skills you wrote | Skills you or a plugin added | claude-api (1), vercel:deploy (1) |
| Course skills | sprint-plan, sprint-review, learn, sprint-coach, eli5 | sprint-plan (1), learn (2), sprint-review (1) |
| Plugins | Bundles of skills or agents | vercel (1) |
| Slash commands | Commands typed with `/` | /learn |
| Hooks | Scripts that run on events | SessionStart (4 runs); none blocked anything |
| Subagents | Named: none. Built-in (such as Explore): none | not used |
| Messages to other sessions | Handing work to another session | not used |
| Plan mode | Planning before acting | not used |
| Permission mode | How much the agent may do without asking | `auto` (25 turns) |
| Permission prompts and denials | Prompts answered, calls blocked | 1 approved by you, 4 allowed by a rule, 1 denied by a rule, 1 blocked by auto mode (adding a repo collaborator) |
| Where sessions ran | Surface | Claude desktop app (2), VS Code extension (1) |
| Worktrees | Parallel copies of a repo | not used |
| Memory and instructions | Files loaded or edited | MEMORY.md loaded in this repo's session; project-msb341-sprints.md edited |
| Reaching outside the repo | CLI tools, MCP servers, direct API calls | CLIs: supabase, vercel, gh. MCP: Claude_Browser (86 calls), terminal. Direct API: curl (10) |

Codex sessions do not show these. Not used this sprint: subagents, plan mode, worktrees,
messages to other sessions.

Scan version: 2026-10-16.

## Users this sprint

The scan found no outside users in the session logs. You reported these in-person usability
tests of the PengPal prototype, written up in `design/usability-tests/`:

| Date | What happened | Change that followed |
|---|---|---|
| Oct 21 | Two returned missionaries who speak Chinese used the prototype on their phones to find a local friend. Both succeeded; both were unsure how to contact the local after booking. | No change yet |
| Oct 26 | A third returned missionary did the same task. Succeeded; raised the same post-booking question. | No change yet |

## Learning sessions

2 sessions logged in the window, both on the Design axis.

| Date | Section | Axis | Minutes | What you asked | Start / shown | Confidence | Question left |
|---|---|---|---|---|---|---|---|
| Oct 26 | User Stories | Design | not measured (stopped early; the log includes time away) | taught in English and Chinese; default path | Developing / Developing to Proficient | not given | none |
| Oct 26 | Running a Usability Test | Design | 11 | taught quickly, in English and Chinese; quick path | Developing (assumed) / Proficient | not given | none |

You studied two Design sections, and the sprint's work advanced Design.

## Axis

**Design.** The written-up work is usability testing: three people used the PengPal prototype on
their phones to complete one task, with results recorded in `design/usability-tests/`, alongside
the two Design learning sessions and the website update. It is split with Launch and Learn:
pitching PengPal at the Big Idea Competition, including its pricing and script, took the
rehearsal time this review cannot see.

## Against your plan

**Goal was:** For our Sandbox project, PengPal (a platform for foreign travelers to find local
guides in China), have a clear prototype built with Claude Code that I can share with others and
use to find potential customers. Keep learning new AI skills by using Claude Code to build:
improve my personal website so it has a better design and serves me better, and fix bugs in
CoffeeChat AI. Spend time learning the course content, such as Testing the Design and User
Stories.

Mostly. A PengPal prototype exists at a shareable link. Shulin built it in her repo, and none of
your sessions or commits touched it; you report that the two of you discussed it together and
that you contributed ideas on its design and which features to add. You and Shulin showed it to potential customers: three
usability tests with returned missionaries are written up (Oct 21 and Oct 26). All three found
and booked a local friend without help, and all three raised the same question about contacting
the local after booking. Nothing has been changed in the prototype because of it yet. The tests
were written up on Oct 26, not within a day of the Oct 21 session. CoffeeChat AI got two bug fixes. The personal site
got one commit adding CoffeeChat AI and research experience, not a redesign; the plan made the
redesign conditional on whether it was needed. Both named course sections were studied with
`/learn` on the last day of the sprint, one of them stopped early. Not in the plan: PengPal placed
2nd and won Crowd Choice ($1,300) at the Big Idea Competition.

---

## Your retro

*The builder's own answers, recorded word for word in step 7.*

**Did you hit the goal?** I think I hit the goals, because I worked hard to achieve the goals, and I am keep learning new things from this class and Claude Code, and I also spent a lot of time studying for the midterm exam last week, and I got a score that I satisfy with, so I hit the goal for the goals I set in the sprint, and also worked hard to hit the goal in the test and learned the knowledges i need for the exam, and agentic workflow, strategies, and design.

**What did the report show you?** I didn't expect we would participate in the Big Idea competition with our product, and even win $1300 from it, and got to get good feedbacks from Rollins center's founders, and entrepreneurs. I didn't noticed from myself that we have this big potential to create this good idea and product that can help people travellingto China, and learn about Claude Code and agentic workflow with Claude and AI tools this quick

**If the plan changed, why?** Most of the plan didn't change, but we happened to participate in the Big Idea Competition, so we set a new goal to improve our product PengPal and try hard to win the competition and pitch it better, and reached all the goals.

**Actual difficulty:** I think 4, because there's more things we need to manage actually, and some other classes are more work and with extra midterms, and I was also sick this past couple days, so I need to make up and study harder to achieve these goals.

**What will you change next sprint?** I will use claude code to find my weakness, and learn new skills on design, to help me improve my websites and apps with better design
