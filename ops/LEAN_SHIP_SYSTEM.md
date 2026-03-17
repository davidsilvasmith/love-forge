# Lean Ship System (Love Forge)

## Diagnosis
We created a fake team and too many cron loops.
That produced suggestions, handoffs, and churn.
It did **not** reliably produce shipped pages, measured improvements, or clear proof of value.

The bottleneck is not ideas.
The bottleneck is **decision focus + shipping discipline**.

## 80/20 Rule
The 20% of work that matters most:
1. Pick the single highest-leverage page.
2. Make one concrete improvement that increases usefulness.
3. Commit + push.
4. Verify it is live.
5. Log what changed and why.

Everything else is support work.
If it does not help one of those five steps, cut it.

## New Operating Model

### One Owner
One execution owner per cycle:
- **Release Owner** = the only role allowed to decide what ships in that cycle.

No multi-role council. No chained handoffs. No hourly brainstorming swarm.

### One Queue
Keep exactly one ranked backlog file:
- `ops/SHIP_QUEUE.md`

Each item must include:
- page
- problem
- user pain in plain English
- proposed change
- expected outcome
- proof after ship

### WIP Limit = 1
Only one item can be `IN PROGRESS` at a time.
Do not start a second improvement until the first is:
- committed
- pushed
- verified live
- logged

### One Atomic Ship
Each ship should fit one of these buckets:
- headline/hero clarity
- page structure/scannability
- one practical tool upgrade
- one trust improvement
- one CTA improvement

If a change touches more than one page, it still needs one clear thesis.
No mixed bags.

## Publish Standard
Every ship must produce all of this:
1. commit hash
2. changed files
3. live URL
4. one-sentence reason this should help users
5. next metric or observation to watch

If any of those are missing, value was not captured.

## Cadence

### Default cadence: manual and deliberate
Use **manual release cycles**, not autonomous cron swarms.

Recommended rhythm:
- 1 planning pass
- 1 shipping pass
- 1 verification pass
- 1 short retrospective

That is enough.

### Optional automation later
If automation returns, use **one** cron only:
- once per day max
- job = produce a ranked shortlist only
- never auto-edit + auto-publish + auto-cascade across roles

## Prioritization Framework
Score each candidate 1-5 on:
- **Impact**: likely to improve usefulness or conversions
- **Confidence**: how sure we are this helps
- **Ease**: how fast we can ship and verify

Prioritize by total score.
Ties go to the faster ship.

## What to Work On First
For Love Forge, prioritize in this order:
1. Homepage first-screen clarity
2. Best tool pages people would actually share with a spouse tonight
3. Blog index clarity and navigation
4. Lead capture only after the site feels genuinely useful

## Kill List
Stop doing this:
- hourly expert-role prompts
- multiple overlapping reviewers for the same page
- long handoff chains
- vague “brand/design/story” passes without a live ship
- measuring activity by message volume instead of shipped proof

## Success Definition
A productive day is not “the team had many ideas.”
A productive day is:
- 1 to 3 verified ships
- each with a clear thesis
- each logged with proof
- backlog updated
- next priority obvious

## Commander's Intent
Make the site so useful a stressed spouse can land on one page,
understand the problem in 10 seconds,
and take one action tonight.

That is the standard.
