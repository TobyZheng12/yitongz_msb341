# Learning log: Design the Data Model First

**Section:** [Design the Data Model First](https://byu-strategy.github.io/product-management/08-data-and-apis.html#the-data-model-is-the-skeleton)
**Date:** 2026-11-09
**Time:** 10:44 to 21:51 (the section was fetched at 10:44; the time between includes time away)
**Finished:** stopped early
**Axis:** Application Architecture
**Starting point:** Developing (shown: Developing)

This log is a record of learning, not a score.

## What I asked about

- Asked to be taught in both English and Chinese.
- Asked to be taught directly instead of answering the first predict question.
- Asked to end the session quickly.

## What we covered

- Predict: saving `pages = "about three hundred"` into a number column. Did not answer; was taught: a spreadsheet accepts it, a database rejects it because column types and rules (such as `CHECK`) are enforced on every write.
- Table, row, column, primary key, using a library example (`books`).
- Foreign key: `books.member_id` points at `members.id`. One member has many books, so the foreign key goes on the "many" side; the database refuses a `member_id` that does not exist.
- Started a new case (teachers and classes: which table gets the foreign key). Stopped before answering.
- Not reached: many-to-many join tables, the full schema, why the data model is hard to change, migrations, developing against a disposable copy.

## In my own words

> Skipped.

## Misconceptions

None came up.

## Check

Not taken.

## Confidence

Proficient

## Pictures

None.

## Still wondering

Nothing.

## Next

- Answer the teachers and classes case, then many-to-many and migrations in this section.
