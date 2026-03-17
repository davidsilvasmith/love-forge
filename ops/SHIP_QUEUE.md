# Ship Queue (Love Forge)

## Rules
- Only one item may be `IN PROGRESS`
- Every shipped item must end with commit hash + live URL + outcome note
- If an item is vague, it is not ready

## Backlog

### TODO
- LF-013 Get Backup Tool should add helper-specific outreach examples so users do not stall after choosing
  - **Page:** `/blog/third-party-escalation-tool.html`
  - **Problem:** The page now makes helper choice faster, but the outreach script is still generic instead of showing one ready text for therapist, coach, and trusted mentor.
  - **User pain:** "Okay, we picked the helper. What exactly do I text this person?"
  - **Proposed change:** Add three short copy-ready outreach examples matched to therapist, coach, and trusted mentor.
  - **Expected outcome:** More sends tonight, less rewriting, better follow-through after the chooser.
  - **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**

## IN PROGRESS
- _none_

## SHIPPED

#### LF-012 Get Backup Tool makes the helper-choice order faster to scan on mobile
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The tool had the right sequence, but the helper-type choice was buried in body copy instead of a faster visual decision block.
- **User pain:** "Just tell me who to contact first so we can send the messages tonight."
- **Proposed change:** Turn the helper-type order into one obvious chooser with one-line guidance for therapist, coach, or trusted mentor.
- **Expected outcome:** Faster outreach, less debate, better follow-through on the trust-break path.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now shows a three-card helper chooser near the top, gives a default rule for therapist-first trust breaks, and updates the partner script to match the faster chooser. Commit: `26f8a9a`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-011 Homepage surfaces the safest trust-break route before generic communication tools
- **Page:** `/index.html`
- **Problem:** The homepage safety section mentioned trust breaks, but stressed users could still miss the strongest route when lying, cheating, or hidden money was the real emergency.
- **User pain:** "If trust got broken, just tell me the safest first move tonight."
- **Proposed change:** Turn the trust-break warning into one sharper first-action block with one exact script and one clearer route into third-party escalation.
- **Expected outcome:** Safer triage, more credible trust handling, less chance users start with the wrong page.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage trust triage now names concrete trust-break cases, tells users not to start with a big feelings talk, gives one copy-ready escalation script, and routes them straight into the Get Backup Tool before generic communication tools. Commit: `a5be076`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-010 Blog hub cuts duplicate chooser blocks so the fastest next tool stays obvious
- **Page:** `/blog/index.html`
- **Problem:** The blog hub repeated the same choose-a-tool decision in too many formats, which turned a fast decision page into extra scanning.
- **User pain:** "I already picked the problem. Stop making me choose again and again."
- **Proposed change:** Remove repeated chooser strips and popular-tool blocks so the page keeps one clear quick start, one relationship-moment picker, and one filterable library.
- **Expected outcome:** Faster scanning, less analysis paralysis, and quicker clicks into one useful tool.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now drops the extra chooser row, the situation/time board, and the popular-tools wall so users hit one decision block and then the filterable full library without repeated re-deciding. Commit: `c9867a4`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-009 Homepage makes the “partner said yes” state one obvious next move
- **Page:** `/index.html`
- **Problem:** After the partner invite, the “yes” block still made users scan three equal tiles instead of showing the fastest first move.
- **User pain:** "Okay, they said yes. What do I send first?"
- **Proposed change:** Turn the yes-state block into one primary lock-in action with one opener, one close, and one low-energy fallback.
- **Expected outcome:** Faster follow-through after partner buy-in, less hesitation between yes and an actual scheduled rep.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now makes the yes-state feel like one immediate move by leading with a copy-ready lock-in text, adding exact-time guidance, and demoting the opener and close to support steps so stressed spouses can schedule the rep fast. Commit: `4b39ecc`. Live URL: `https://love.forge.dsdoes.com/`


#### LF-008 Homepage turns the partner-share block into one clearer send action
- **Page:** `/index.html`
- **Problem:** The homepage still asked users to share the site in several ways before clearly telling them which share action was best tonight.
- **User pain:** "Just tell me the easiest message to send so we can start."
- **Proposed change:** Simplify the share section to one primary partner invite path, one fallback, and one stronger reason to send it now.
- **Expected outcome:** Faster partner invites, less hesitation, more starts from one copied message.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now gives one clear partner-invite text as the primary action, explains why that ask is safer after a hard day, and fixes the shared link to the live Love Forge domain. Commit: `ee90186`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-007 Homepage turns the 7-day plan into one cleaner continuation block
- **Page:** `/index.html`
- **Problem:** After the starter flow, the homepage split the next step across a separate plan card, score tracker card, and final CTA card.
- **User pain:** "I picked a lane. Now just help me keep going without more reading."
- **Proposed change:** Merge the 7-day plan, score tracker, and next-action CTA into one tighter continuation block with one obvious path.
- **Expected outcome:** Better continuation after first click, less drop-off below the fold, cleaner path into the plan flow.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now groups the 7-day path, score tracker, and next step into one continuation block so users can lock a time, copy the tracker once, and choose the guided plan or quiz without bouncing between separate cards. Commit: `1c02000`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-006 Homepage prunes duplicate choice blocks below the fold
- **Page:** `/index.html`
- **Problem:** The homepage had a strong first screen, but lower sections kept asking users to pick a lane again in slightly different formats.
- **User pain:** "I already know my problem. I do not want to keep re-deciding the same thing."
- **Proposed change:** Cut duplicate chooser blocks so the homepage keeps one clear path to first action, fallback, and next tool.
- **Expected outcome:** Faster scanning, less overload, higher clickthrough into one tool.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now keeps the first-screen lane chooser and removes repeated below-the-fold pickers by problem, mode, time, stack, and visual lane, so the page stays focused on taking one action tonight. Live URL: `https://love.forge.dsdoes.com/`

#### LF-005 Blog conflict routing now sends hot couples to de-escalation first
- **Page:** `/blog/index.html`
- **Problem:** The blog hub told users that hot conflict beats other work, but some conflict entry points still routed them straight into a longer fight tool.
- **User pain:** "We are already heated. Do not send us into a bigger talk first."
- **Proposed change:** Make the conflict quick-pick and decision board route to Pause-and-Return first, and add one explicit rule that hot conflict must cool down before Fight Fair.
- **Expected outcome:** Safer first move, less overwhelm, and faster starts for couples in active escalation.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now sends active-conflict users to Pause-and-Return as the first move in every main conflict entry point, and explicitly says Fight Fair comes after both people are calm. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-004 Trust lane page should choose the safest first move fast
- **Page:** `/blog/boundary-definition-tool.html`
- **Problem:** Trust pain pages can still feel like more reading instead of an immediate first move.
- **User pain:** "If trust feels off, tell me exactly what to say and what to lock down tonight."
- **Proposed change:** Tighten first screen, add one sharper starter script, and make the first boundary decision easier to scan.
- **Expected outcome:** Faster trust-lane starts, less hesitation, better odds a couple actually runs the tool tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Boundary page now tells users the safest first move before they pick a rule: stop if it feels unsafe, use Phone + DMs only for one specific trust issue, and default to Time + availability when the real problem is overload. Live URL: `https://love.forge.dsdoes.com/blog/boundary-definition-tool.html`

#### LF-002 Blog index becomes decision hub
- **Page:** `/blog/index.html`
- **Problem:** Too many tools can feel like a wall of links.
- **User pain:** "Just tell me which tool to use for my situation."
- **Proposed change:** Group tools by moments: conflict, distance, trust, connection, planning.
- **Expected outcome:** Higher clickthrough to relevant tools, lower overwhelm.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now groups the first decision by relationship moment so a stressed spouse can choose conflict, connection, trust, distance, or planning without scanning the whole library. Commit: `c6d8ed7`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-001 Homepage hero for stressed couples
- **Page:** `/index.html`
- **Problem:** First screen may not instantly tell a tired spouse what this site helps with tonight.
- **User pain:** "I don't need theory. I need something that helps us stop fighting or reconnect tonight."
- **Proposed change:** Tighten hero headline, subhead, and primary paths so visitors can choose one immediate outcome fast.
- **Expected outcome:** Better first-screen clarity, more clicks into tool pages.
- **Score:** Impact 5 / Confidence 4 / Ease 4 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Hero now tells stressed spouses to pick one reset in under 60 seconds, adds direct situation language for conflict/distance/trust, and keeps a low-energy fallback in the first screen. Commit: `05e7cde`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-003 Make one flagship tool undeniably useful tonight
- **Page:** `/blog/one-issue-rule.html`
- **Problem:** Strong concept, but page should feel more like a tonight-use playbook than a blog post.
- **User pain:** "We keep spiraling into five fights at once."
- **Proposed change:** Add a tighter 3-step tonight plan, realistic examples, copy buttons, and a mini instruction manual.
- **Expected outcome:** More saves/shares, better perceived usefulness.
- **Score:** Impact 5 / Confidence 4 / Ease 3 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Added copy-ready starter + 4-line script, three realistic examples, and a mini instruction manual with common mistake + awkward fallback. Live URL: `https://love.forge.dsdoes.com/blog/one-issue-rule.html`
