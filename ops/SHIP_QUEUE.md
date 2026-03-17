# Ship Queue (Love Forge)

## Rules
- Only one item may be `IN PROGRESS`
- Every shipped item must end with commit hash + live URL + outcome note
- If an item is vague, it is not ready

## Backlog

### TODO
- **LF-006** Homepage should prune duplicate choice blocks below the fold
  - **Page:** `/index.html`
  - **Problem:** The homepage has strong first-screen clarity, but lower sections repeat similar choices and can dilute momentum.
  - **User pain:** "I already know my problem. I do not want to keep re-deciding the same thing."
  - **Proposed change:** Cut or merge duplicate chooser blocks so the homepage keeps one clear path to first action, fallback, and next tool.
  - **Expected outcome:** Faster scanning, less overload, higher clickthrough into one tool.
  - **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**

## IN PROGRESS
- _none_

## SHIPPED

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
