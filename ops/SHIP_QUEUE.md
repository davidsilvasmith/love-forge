# Ship Queue (Love Forge)

## Rules
- Only one item may be `IN PROGRESS`
- Every major run must answer: **What single constraint is suppressing usefulness right now?**
- Every queued item must name one page, one user pain, one proposed fix, and one expected outcome
- Every shipped item must end with commit hash + live URL + outcome note
- If an item is vague, it is not ready

## Backlog

### TODO
- _none_

## IN PROGRESS
- _none_

## SHIPPED

#### LF-115 Blog hub first send should stop sneaking tomorrow commitment into the very first ask so a stressed spouse can get one smaller yes tonight
- **Page:** `/blog/index.html`
- **Problem:** The blog hub told users to send one small ask and stop there, but the main dynamic first-send block still added tomorrow or ongoing-commitment language inside the first message itself — including `If it helps, we can repeat it tomorrow. If not, we drop it.`, `then decide tomorrow if we want the full 10-minute version`, `If it helps, we stop there and repeat tomorrow.`, and `If it helps, we keep going tomorrow.`
- **User pain:** "I am trying to get one yes for tonight. Do not make my first text sound like I am already signing us up for tomorrow too."
- **Proposed change:** Strip tomorrow/ongoing-commitment language out of the blog hub's first-send and low-energy fallback texts so the first ask stays focused on one small rep tonight; keep tomorrow follow-through only in the later yes / soft-no sections.
- **Expected outcome:** Smaller safer first sends from the blog hub, less resistance at the first ask, and better odds a stressed spouse gets one yes tonight before follow-through talk starts.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub first-send and low-energy fallback texts now ask only for one small rep tonight across distance, conflict, apart, and trust states, while tomorrow follow-through stays in the later reply-handling blocks where it belongs. Commit: `PENDING`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-114 Homepage trust-break first-screen route should stop making high-stakes users retype the backup ask before they can take the safest next move tonight
- **Page:** `/index.html`
- **Problem:** The homepage first screen already routed trust-hit couples to the Get Backup Tool, but the highest-stakes card still showed the exact outreach text as plain paragraph copy while every lower-stakes homepage route had a copy action. Users dealing with lying, cheating, hidden money, or secret messages still had to retype the safest first message at the most fragile moment.
- **User pain:** "If trust got hit, do not make me rewrite the one safest text by hand before I can use it. Let me copy it fast and move."
- **Proposed change:** Turn the homepage trust-break first-step text into a copy-ready block with one clear `Copy trust-break text` action beside the existing Get Backup Tool link.
- **Expected outcome:** Faster safer first action for trust-hit couples, less friction on the highest-stakes homepage route, and better odds a stressed spouse sends the backup-first text tonight instead of stalling or improvising.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage trust-break first-screen card now gives users the exact backup-first text inside a copy box plus a dedicated copy button next to the Get Backup Tool link, so the safest route is immediately usable without retyping. Commit: `c2c2153`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-113 Homepage first-screen skeptical route should stop making resistance-heavy couples jump lower just to get the exact safer ask when the normal invite will obviously get an eye-roll
- **Page:** `/index.html`
- **Problem:** The homepage first-screen selected-lane preview already exposed a skeptical-partner fast route, but that card still only offered a `Jump to skeptical-partner text` button. Resistance-heavy users still had to scroll lower before they could copy the one safer ask most likely to help tonight.
- **User pain:** "I already know the normal ask will get an eye-roll. Do not make me jump farther down the page just to copy the smaller safer text."
- **Proposed change:** Put the exact 7-day experiment ask and a copy button directly inside the first-screen skeptical-partner fast route, while keeping a secondary link to the lighter fallback below.
- **Expected outcome:** Faster safer first action for skeptical-partner nights, less drop-off between diagnosis and copy, and better odds a stressed spouse sends the lower-pressure ask tonight instead of stalling.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first-screen skeptical-partner fast route now includes the exact 7-day experiment ask plus a copy button, so resistance-heavy users can copy the safer ask immediately without scrolling lower first. Commit: `8a056bd`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-112 Homepage main first-ask block should stop acting like texting is the only valid move so same-house couples do not hesitate at the moment they are finally ready to ask
- **Page:** `/index.html`
- **Problem:** The homepage first-screen flow was strong, but the main ask block still said `Send this to your partner now`, `Best move tonight: send one low-pressure text`, and `Text this exact message`. For couples under the same roof, that framing could make the safest exact ask feel weird or artificial right at the highest-leverage action.
- **User pain:** "We are in the same house. Do not make this feel like I have to text someone in the next room if saying the same line out loud is the real next move."
- **Proposed change:** Reframe the main homepage ask block around `send or say`, add one explicit same-house note telling users to read the exact words out loud if texting feels weird, and rename the main message label from text-only framing to exact-message framing.
- **Expected outcome:** Better trust in the homepage main action for same-house couples, less hesitation at the first ask, and better odds a stressed spouse actually uses the script tonight instead of stalling on the delivery method.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage main ask block now tells users to text it, say it out loud, or paste it into chat, adds one same-house note to use the exact words aloud instead of rewriting, and reframes the block as the best first ask rather than a text-only action. Commit: `6fef4c1`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-111 Homepage first-screen send path should expose the skeptical-partner route before the normal ask so a stressed spouse does not copy the default text when the real blocker is obvious resistance
- **Page:** `/index.html`
- **Problem:** The homepage first-screen send flow was strong for lane choice and yes/no follow-through, but the skeptical-partner route only appeared much lower on the page after the main send, yes-state, soft-no, and solo sections. A spouse who already knew their partner would roll their eyes or instantly say no could still copy the default ask first and hit a preventable rejection.
- **User pain:** "I already know the normal ask will get an eye-roll. Do not make me scroll half the page to find the smaller safer skeptical route."
- **Proposed change:** Add one compact skeptical-partner escape hatch inside the first-screen selected-lane preview that tells users to skip the normal ask and jump straight to the 7-day experiment text.
- **Expected outcome:** Better first-screen routing for resistance-heavy nights, fewer wrong first sends, and better odds a stressed spouse chooses the lower-pressure skeptical invite before triggering an easy no tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first-screen send preview now includes an explicit skeptical-partner fast route that tells users not to push the normal ask first and jumps them straight to the 7-day experiment text section below, so resistance-heavy nights get the lower-pressure route before the main send. Commit: `db99280`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-110 Homepage yes-state should name the exact next tool inside the main follow-through block so a stressed couple does not get a yes and still have to guess what page to open
- **Page:** `/index.html`
- **Problem:** The homepage main yes-state flow gave users a lock-in text plus lane-specific opener cards, but once the partner said yes the page still made them infer which full tool to open next. The first-screen preview named the right tool, but the main yes-state block itself still stopped short of the exact handoff.
- **User pain:** "We got a yes. Do not make me guess which page to open now that we are actually doing this. Point me straight to the exact tool."
- **Proposed change:** Add one dynamic `Open this exact tool now` handoff card inside the homepage yes-state block that updates with the selected lane and points directly to the matching tool.
- **Expected outcome:** Cleaner yes-state follow-through on the homepage, less drop-off after the partner agrees, and better odds a stressed couple moves from text exchange into the right tool tonight without hesitating.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state now shows a lane-matched `Open this exact tool now` card for same-roof distance, conflict, apart, and calm trust-boundary nights, so users who get a yes can jump straight into the right tool from the main follow-through block. Commit: `5122699`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-109 Homepage first-screen selected-lane preview should carry users straight into the yes-or-no follow-through so a stressed couple does not send the first text and then guess what to do after the reply
- **Page:** `/index.html`
- **Problem:** The homepage first-screen selected-lane preview gave users the right first text, but the preview button only copied the message and left them at the top of the page. A stressed spouse could send the ask and still miss the exact yes-state and soft-no next steps sitting lower in the main send flow.
- **User pain:** "Do not make me send the first text and then wonder what I am supposed to do if they say yes or not right now. Carry me straight into the next step."
- **Proposed change:** Make the first-screen selected-lane action explicitly promise the next step, add one short follow-through note in the preview, and auto-scroll users into the main send flow when they copy.
- **Expected outcome:** Stronger homepage follow-through from the highest-traffic first-screen action, less drop-off between first send and actual reply handling, and better odds a stressed spouse keeps moving after the partner responds tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage selected-lane preview now tells users the yes / not-right-now flow is directly below, the button now says `Copy text and show next step`, and clicking it copies the selected text while jumping straight into the main send flow. Commit: `b465a10`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-108 Homepage first-screen selected-lane preview should name the exact yes-state tool so a stressed couple can trust the first copied text without wondering what happens if the partner says yes
- **Page:** `/index.html`
- **Problem:** The homepage first-screen selected-lane preview gave users one copy-ready text, but it still stopped short of naming the exact tool that comes next after a yes. A stressed spouse could still think, "Okay, I can send this — but what exactly are we agreeing to do if they say yes?"
- **User pain:** "Do not make me send the first text and still wonder what happens next if my partner says yes. Tell me the exact tool now so I can trust this route."
- **Proposed change:** Add one dynamic `If they say yes` line inside the first-screen selected-lane preview that updates with the chosen lane and points to the exact next tool.
- **Expected outcome:** Higher first-screen trust, less uncertainty between send and follow-through, and better odds a stressed couple actually sends the text because the next step is already named.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first-screen selected-lane preview now tells users exactly which tool opens next after a yes for conflict, same-roof distance, apart, and calm trust-boundary nights. Commit: `17c1aa4`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-107 Homepage first-screen send customizer should stop re-showing four full send texts after lane choice so a stressed couple can stay on one obvious copy-ready ask instead of re-deciding the same route
- **Page:** `/index.html`
- **Problem:** The homepage already asked users to pick one lane above, but the very next first-screen send block re-expanded into four full send tiles again. A stressed spouse could still feel forced to re-scan conflict, same-roof, apart, and trust copy after already deciding which night they were having.
- **User pain:** "I already picked the lane. Do not make me re-read four more send options before I copy the one text you want me to send."
- **Proposed change:** Replace the four-tile first-screen send grid with one live selected-lane preview card that stays synced to the current lane and keeps one obvious copy action.
- **Expected outcome:** Less first-screen re-deciding, faster movement from lane choice to copied text, and better odds a stressed spouse sends one exact ask tonight instead of scanning the same decision twice.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first-screen send customizer now shows one selected-lane preview instead of four competing full-text tiles, so users keep one obvious copy-ready ask after lane choice without re-scanning the whole set. Commit: `PENDING`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-106 Homepage first-screen “Copy text first” buttons should actually copy the matching text so a stressed spouse can act on the first click instead of getting false-forwarded into more scanning
- **Page:** `/index.html`
- **Problem:** The homepage hero promised, "Pick the sentence that sounds most like tonight, copy the text, and run one short rep," and each lane card repeated `Copy ... text first`, but those buttons only scrolled down the page. The user still had to re-orient in the send block before getting the actual message.
- **User pain:** "If the button says copy, copy the text. Do not make me click, scroll, and decode the page again when I am already stressed."
- **Proposed change:** Make each homepage `Copy ... text first` button copy the matching lane text immediately while still dropping the user into the matching send block for a quick sanity check.
- **Expected outcome:** Faster first action from the homepage first screen, less trust loss from a broken button promise, and better odds a stressed spouse sends one exact ask tonight instead of stalling after the first click.
- **Score:** Impact 5 / Confidence 5 / Ease 5 = **15**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first-screen `Copy ... text first` buttons now copy the matching main send text immediately and then land users in the matching send block with a confirmation state. Commit: `438e5d5`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-105 Homepage first-screen lane cards should expose the wiped-out shortcut directly so exhausted couples can jump straight to the smallest safe text instead of hunting for it below the fold
- **Page:** `/index.html`
- **Problem:** The homepage hero already promised a low-energy fallback, but the first-screen lane cards only exposed `Copy ... text first` and `Open full tool`. A wiped-out user still had to scroll into the main send block and re-orient before reaching the lighter copy.
- **User pain:** "We are too fried for the normal ask. Do not make me scroll and decode the full send block just to find the smaller safer text."
- **Proposed change:** Add one `Need lighter text` action on each homepage lane card that keeps the chosen lane, jumps straight to the wiped-out card, and clarifies that it is the smallest safe text for tonight.
- **Expected outcome:** Faster low-energy action from the homepage first screen, less hunting inside the main send block, and better odds an exhausted spouse sends the lighter ask tonight instead of bouncing.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage lane cards now expose a `Need lighter text` shortcut that carries the selected lane into the wiped-out card, and the live homepage shows the new shortcut plus the clearer `Too fried for the normal ask?` framing in the low-energy block. Commit: `5584761`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-104 Homepage main send block should show the selected lane before the chips so stressed couples who jump down from the hero instantly trust they are in the right place before copying
- **Page:** `/index.html`
- **Problem:** The homepage main send block updated with the chosen lane, but once users jumped down from the hero they still had to decode the active chip row and helper copy to confirm they had landed in the right send flow before copying.
- **User pain:** "I already picked the lane. Show me fast that I am in the right send block so I do not stop and re-check the chips before I copy."
- **Proposed change:** Add one visible `Selected tonight lane` summary above the main send chips and make it update with conflict, same-roof distance, apart, or calm trust-boundary selection.
- **Expected outcome:** Faster trust in the homepage send block, less chip-decoding before the first copy action, and better odds a stressed spouse sends the right text tonight instead of hesitating.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage main send block now shows a live `Selected tonight lane` summary above the lane chips, so users who jump down from the hero can confirm the current route at a glance before they copy. Commit: `4f5cf20`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-103 Homepage should stop repeating the same jump-to-send choice right after the lane cards so stressed couples can act on the first obvious buttons instead of re-deciding the same thing again
- **Page:** `/index.html`
- **Problem:** Each homepage lane card already gave users two clear actions — `Copy text first` or `Open full tool` — but the very next card repeated the same jump-to-send choice with another four buttons and another explanation. That made users re-decide the same thing right after the clearest first-screen choice.
- **User pain:** "I already picked the lane and saw the button. Do not make me choose the same send path again before I act."
- **Proposed change:** Remove the duplicate jump-to-send card and tighten the send-section helper copy so it points back to the lane card button users already trusted.
- **Expected outcome:** Less above-the-fold cognitive load, faster movement from lane pick to first send, and better odds a stressed spouse acts on the first obvious button tonight instead of scrolling into duplicate choices.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now moves straight from the lane cards into the overlap triage block instead of repeating another jump-to-send chooser, and the send section now tells users to use the lane card's `Copy text first` button to jump straight into the matching send. Commit: `5b6823e`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-102 Homepage first-screen lane cards should stop making users choose between routing and sending so stressed couples can copy the first text from the exact lane card they already trust
- **Page:** `/index.html`
- **Problem:** The homepage hero promised, "Pick the sentence that sounds most like tonight, copy the text, and run one short rep," but the four biggest lane cards only opened full tool pages. The actual jump-to-send action lived in a separate card below them, so the most obvious first click still pulled stressed users into more reading before the first text.
- **User pain:** "I already found our lane. Do not make me choose between opening another page and hunting the send text you just told me to copy."
- **Proposed change:** Turn each homepage hero lane card into a two-path action with one obvious "Copy text first" button for that lane and one separate "Open full tool" button.
- **Expected outcome:** Faster first sends from the homepage first screen, less page-hopping before action, and better odds a stressed spouse copies one exact ask tonight instead of drifting into more reading.
- **Score:** Impact 5 / Confidence 5 / Ease 4 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage hero lane cards now let users copy the matching lane text directly from the first-screen card while keeping a separate full-tool path, so the page's "copy the text" promise is true on the first obvious click. Commit: `94d55ba`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-101 Homepage low-energy fallback should stop hiding behind helper copy and give wiped-out couples one exact lighter text in the main send block so they can act tonight without rewriting the ask
- **Page:** `/index.html`
- **Problem:** The homepage told tired users to use the shortest version that still feels safe and even mentioned a low-energy fallback above the fold, but the main partner-send block only exposed the full 10-minute ask. A wiped-out spouse still had to mentally invent the lighter version at the exact moment they needed less thinking.
- **User pain:** "We are too fried for the normal ask. Do not make me rewrite the text from scratch just to make tonight doable."
- **Proposed change:** Add one copy-ready wiped-out version inside the homepage main send block and make it switch with the selected lane so conflict, same-roof distance, apart, and calm trust nights each get a lighter exact ask.
- **Expected outcome:** Better low-energy usability on the homepage, less last-second rewriting before the first text, and better odds a stressed spouse sends one safer smaller ask tonight instead of doing nothing.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** The homepage main send block now includes a copy-ready wiped-out version that updates with the selected lane, giving users a smaller 5-minute fallback without leaving the primary send flow. Commit: `9985639`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-100 Homepage main partner invite should stop sneaking the 7-day commitment into the very first text so a stressed spouse makes one tiny tonight ask instead of sounding like they are pitching a program
- **Page:** `/index.html`
- **Problem:** The homepage main send block told users to send one low-pressure text with one simple ask, but the exact primary invite and SMS action still added `If it helps, we keep going for 7 days.` to the very first message, which quietly turned a tonight ask into a bigger commitment before the partner had even said yes.
- **User pain:** "I am trying to get one small yes tonight. Do not make my first text sound like I am signing us up for a week-long program."
- **Proposed change:** Remove the 7-day commitment from the homepage primary partner invite and SMS output, and clarify that the 7-day idea belongs after a first good rep or in the skeptical-partner path.
- **Expected outcome:** Smaller safer first sends, better match between the homepage instruction and the actual copy, and better odds a stressed spouse gets a yes to one short reset tonight.
- **Score:** Impact 5 / Confidence 5 / Ease 5 = **15**
- **Status:** SHIPPED
- **Proof after ship:** Homepage primary invite and SMS output now keep the first ask focused on one 10-minute reset tonight, and the helper note now says to save the 7-day idea for after a yes/first good rep or the skeptical-partner route. Commit: `29e24f4`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-099 Homepage main partner invite should stop appending the site link to the first text so a stressed spouse sends a smaller safer ask instead of making the first move feel like homework
- **Page:** `/index.html`
- **Problem:** The homepage main send block told users, "Do not explain the whole site first," but the exact text and SMS action still appended the Love Forge URL to the very first partner message, which made the ask feel bigger and less human right at the conversion moment.
- **User pain:** "If I am trying to get a tired partner to say yes to one small reset, do not make my first text feel like homework or a funnel."
- **Proposed change:** Remove the site URL from the homepage's primary partner invite text and SMS link, and clarify that the link should only be shared after the partner says yes or asks for more context.
- **Expected outcome:** Lower-friction first sends, better match between the homepage instruction and the actual copy, and better odds a stressed spouse gets a yes to one small reset tonight.
- **Score:** Impact 5 / Confidence 5 / Ease 5 = **15**
- **Status:** SHIPPED
- **Proof after ship:** Homepage primary send text and SMS action now keep the first ask link-free, and the helper note now tells users to share the Love Forge link only after a yes or a request for context. Commit: `6c4f58a`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-098 Homepage trust lane should say "no fresh break" everywhere the user double-checks it so a stressed spouse does not mistake calm blurry-rule trust guidance for the backup-first path after a real trust hit
- **Page:** `/index.html`
- **Problem:** The homepage already had a strong backup-first card for real trust hits, but the trust lane labels below it still used broad "trust feels shaky" wording that could blur the line between calm boundary-setting nights and fresh lying, cheating, hidden-money, or secret-message situations.
- **User pain:** "If trust actually got broken, do not make me wonder whether the regular trust lane is still okay just because the label sounds broad."
- **Proposed change:** Tighten the homepage trust lane card, trust send label, trust lane chip, and trust helper note so they all say this path is only for shaky trust with no fresh break.
- **Expected outcome:** Clearer first-screen routing between Boundary Definition and Get Backup Tool, less wrong-lane hesitation on trust nights, and better odds a stressed spouse takes the safer first action tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage trust labels now consistently say the normal trust lane is only for shaky trust with no fresh break, making the backup-first route easier to trust when there was a real trust hit. Commit: `33f2eeb`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-097 Homepage soft-no and next-day repeat guidance should stay in the same lane the user already picked so a stressed spouse does not get an apart, conflict, or trust night routed back into the generic same-roof default after one hesitation
- **Page:** `/index.html`
- **Problem:** The homepage let users choose conflict, same-roof distance, apart, or trust for the main send, but the soft-no and repeat guidance still snapped back to the generic same-roof default, which could quietly misroute people the moment their partner hesitated.
- **User pain:** "We already picked the right lane. Do not make tomorrow's retry and follow-through secretly switch us back to the generic connection path."
- **Proposed change:** Make the homepage soft-no next-tool guidance, tomorrow step, and repeat-tomorrow rule update with the same selected lane so conflict, apart, and calm trust-boundary users keep the right follow-through path.
- **Expected outcome:** Better follow-through trust on the homepage, fewer wrong-tool retries after hesitation, and better odds a stressed spouse keeps moving in the right lane instead of second-guessing tomorrow.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage soft-no and 7-day follow-through guidance now changes with the selected lane, so conflict users stay on Pause-and-Return, apart users stay on Distance Connection Protocol, and calm trust-boundary users stay on Boundary Definition instead of silently falling back to the generic same-roof default.

#### LF-096 Homepage first-screen triage should spell out apart-tonight vs under-the-same-roof routing inside the overlap rule so a stressed spouse does not hit the right order but still have to guess which calmer lane fits once conflict and trust are ruled out
- **Page:** `/index.html`
- **Problem:** The homepage already told users that trust beats everything and hot conflict beats distance, but the third triage step still ended with generic reconnect-or-boundary wording that made a tired spouse do one more interpretation step after the most important sort.
- **User pain:** "Okay, trust and conflict are not the problem. Do not make me guess whether we need the apart tool, the same-roof tool, or the calm trust-boundary tool next."
- **Proposed change:** Replace the generic third triage step with explicit fit routing for apart tonight, under the same roof but emotionally far, and calm blurry-rule trust nights.
- **Expected outcome:** Faster homepage first-screen lane confidence, less wrong-tool hesitation after the overlap rule, and better odds a stressed spouse picks the right calmer tool in one pass tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage overlap triage now names the exact calmer fit inside step three — apart tonight, under the same roof but emotionally far, or calm blurry-rule trust — so users can choose the right next page without decoding generic reconnect wording after conflict and trust are ruled out. Commit: `187c9ae`. Live URL: `https://love.forge.dsdoes.com/`

## IN PROGRESS
- _none_

## SHIPPED

#### LF-095 Homepage below-the-fold safety block should stop repeating the whole first-screen triage so users only re-enter safety guidance when tonight actually changes instead of rereading the homepage diagnosis after they already picked a lane
- **Page:** `/index.html`
- **Problem:** The homepage already handled trust-hit routing and lane triage above the fold, but a later full safety card repeated the same diagnosis language and made a scrolling spouse re-evaluate the whole night again after they had already picked a lane, copied text, or started the follow-through path.
- **User pain:** "I already picked the lane. Do not make me reread the whole safety lecture below the fold unless something actually changed tonight."
- **Proposed change:** Replace the repeated below-the-fold safety card with a smaller "if tonight changes fast" override block that only tells users when to stop the current plan and switch for safety.
- **Expected outcome:** Less homepage repetition, cleaner below-the-fold scanning, and better confidence that users should keep moving unless there is a fresh safety, trust, or escalation change.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now replaces the repeated lower safety lecture with a short override block that only appears as a stop-and-switch reference for immediate danger, fresh trust hits, or a new escalation spike, so users who already chose a lane can keep moving without second-guessing the whole diagnosis again. Commit: `c54b4fe`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-094 Homepage same-roof summary labels should say "under same roof, far apart" everywhere the user double-checks their lane so a stressed spouse never has to decode shorthand before copying
- **Page:** `/index.html`
- **Problem:** The homepage still used shortened same-roof wording in the jump-to-send button and yes-state lane summary, which made skim-reading spouses do one more interpretation step right where they were double-checking they had the emotionally-far-apart path instead of the physically-apart path.
- **User pain:** "I am moving fast. Keep the same-roof lane label explicit everywhere I double-check it so I do not second-guess whether this is the apart version."
- **Proposed change:** Rename the homepage jump-to-send button and yes-state lane summary so both say "Under same roof, far apart" directly.
- **Expected outcome:** Faster lane confidence during the send and yes-state flows, less confusion between same-house distance and physically-apart nights, and better odds a stressed spouse copies the right text tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage jump-to-send and yes-state lane summary now say "Under same roof, far apart" directly, making the same-house-vs-apart distinction easier to trust at a glance before users copy. Commit: `b24b31c`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-093 Curiosity Over Certainty Tool should stop sounding like generic advice and generate the exact opener, curiosity question, mirror line, and close so a stressed spouse can challenge one bad story tonight without improvising
- **Page:** `/blog/curiosity-over-certainty-tool.html`
- **Problem:** The page still read like a generic framework with light prompts, which forced a tired spouse to translate an assumption into the exact opener, question, mirror line, and close while already activated.
- **User pain:** "I know I might be making up a story. Do not make me invent the exact words to check it calmly when I am already tense."
- **Proposed change:** Turn the page into a practical builder with right-tool triage, one exact 10-minute run of show, and copy-ready outputs for the opener, main question, mirror line, and close.
- **Expected outcome:** Faster starts on assumption spirals, less accusation hidden inside fake curiosity, and better odds a stressed spouse asks one real question tonight instead of mind-reading harder.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Curiosity Over Certainty Tool now opens with right-tool triage for hot conflict and trust-break nights, gives one fill-in builder for the exact opener, question, mirror line, and close, and adds a tighter 10-minute run of show plus a single 7-day clarity metric so users can challenge one bad story tonight without improvising. Commit: `f58d640`. Live URL: `https://love.forge.dsdoes.com/blog/curiosity-over-certainty-tool.html`

#### LF-091 Homepage same-roof main send chip should spell out "under the same roof" directly on the button labels so users who skip helper copy can still distinguish emotional distance from being physically apart at a glance
- **Page:** `/index.html`
- **Problem:** The homepage main partner-send lane already defaulted to the same-roof path, but the quick jump chip and main send chip still shortened the label to "same roof," which made skim-reading spouses do one more interpretation step instead of seeing the physical-living-situation distinction instantly.
- **User pain:** "I am moving fast. Put 'under the same roof' right on the button so I do not confuse emotional distance with being physically apart."
- **Proposed change:** Rename the homepage jump chip and the main send lane chip so both spell out "under same roof" directly in the button label.
- **Expected outcome:** Faster lane recognition, less confusion between same-roof distance and apart nights, and better odds a stressed spouse taps the right send path on the first pass.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage jump-to-send and main send same-roof chips now say "Under same roof" directly on the buttons, making the emotional-distance-vs-apart split clearer at a glance before users copy. Commit: `7286c63`. Live URL: `https://love.forge.dsdoes.com/`


#### LF-090 Homepage same-roof main send should say "under the same roof but far apart" directly in the partner-invite block so users who jump below the hero do not have to infer what the default lane means before they copy
- **Page:** `/index.html`
- **Problem:** The homepage main partner-send block already defaulted to the same-roof distance lane, but the helper note still said only "same-roof distance version," which made a skim-reading spouse infer what that meant instead of seeing the literal same-house emotional-distance wording right before copying.
- **User pain:** "I jumped straight to the big text block. Do not make me guess whether the default lane means we live together but feel emotionally far apart."
- **Proposed change:** Tighten the partner-invite helper note and live lane explainer text so the default path explicitly says it is for couples under the same roof but emotionally far apart.
- **Expected outcome:** Faster lane confidence in the main homepage send block, less hesitation between same-roof and apart lanes, and better odds a stressed spouse copies the right text tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage main partner-send helper copy now says the default lane is for couples under the same roof but emotionally far apart, so users who jump below the hero no longer have to infer what the same-roof lane means before they copy.


#### LF-089 Homepage yes-state should make the lane match more visible at a glance so users instantly trust that the follow-through copy changed with their selected night type before they copy and start
- **Page:** `/index.html`
- **Problem:** The homepage yes-state already changed the first question and low-energy opener with the selected lane, but once users landed in the yes block the match still relied on them noticing subtle copy shifts instead of seeing one obvious signal that the opener was now tuned for conflict, same-roof distance, apart, or trust.
- **User pain:** "I changed the lane. Show me fast that the opener changed with it so I can copy it without second-guessing whether this is still the generic version."
- **Proposed change:** Add one visible yes-state lane summary plus small lane labels on the opener cards so users can trust at a glance that the follow-through copy matches the selected night type.
- **Expected outcome:** Faster confidence in the yes-state flow, less re-reading before copying the first question, and better odds a stressed spouse starts the rep tonight instead of hesitating.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state now shows a live "Tonight's lane" summary plus lane-specific labels on the normal and low-energy opener cards, making it obvious at a glance that the follow-through copy changes with conflict, same-roof distance, apart, or trust before users copy and start. Commit: `453f093`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-088 Homepage yes-state opener should match the lane already chosen so a stressed spouse does not get a yes and then have to translate a generic first question before the rep starts tonight
- **Page:** `/index.html`
- **Problem:** The homepage already let users choose conflict, same-roof distance, apart, or trust for the main invite, but once the partner said yes the first question and low-energy opener snapped back to generic wording that forced one more mental rewrite right after the hardest part was over.
- **User pain:** "We finally got a yes. Do not make me translate the first question into conflict, apart, or trust language before we even start."
- **Proposed change:** Make the yes-state first question and low-energy opener switch with the same homepage lane picker so the first spoken line matches the actual kind of night they are having.
- **Expected outcome:** Faster starts after a yes, less last-second rewriting, and better odds a stressed spouse actually begins the rep tonight instead of hesitating.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state now changes both the first question and low-energy opener with the same distance/conflict/apart/trust picker used for the main invite, so the first spoken line fits the real night without one more rewrite. Commit: `bee4646`. Live URL: `https://love.forge.dsdoes.com/`


#### LF-087 Homepage should stop repeating the starter-to-send handoff below the hero so a stressed spouse lands on the partner text faster instead of rereading the same instruction twice
- **Page:** `/index.html`
- **Problem:** The homepage hero already told users to pick one lane, set one time, and copy one matching text, but the very next card repeated the same starter-to-send instruction and fallback copy before users finally hit the main partner invite.
- **User pain:** "I already picked the lane and saw the text flow. Do not make me reread the same handoff before I can copy the main send."
- **Proposed change:** Remove the duplicate post-hero starter handoff card so the main partner-send block starts immediately after the first-screen flow.
- **Expected outcome:** Faster scanning from hero to send, less below-the-fold repetition, and better odds a stressed spouse copies the main partner invite tonight instead of drifting.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now moves straight from the first-screen lane/text flow into the main partner-send block, cutting the repeated starter/send reminder and making the fastest send path easier to reach.


#### LF-086 Homepage lane choice should let stressed spouses jump straight to the matching send text so they do not get kicked into a second page before making the first ask tonight
- **Page:** `/index.html`
- **Problem:** The homepage already told users to pick one lane and send one text, but the most obvious lane cards were full-page links, which could pull a tired spouse away from the copy-ready send flow sitting lower on the homepage before they ever sent the first ask.
- **User pain:** "I know which lane fits. Do not make me bounce into another page before I can copy the first text and send it tonight."
- **Proposed change:** Add one fast homepage jump block directly under the lane chooser so users can tap conflict, same-roof distance, apart, or trust and land on the matching preselected send text without leaving the homepage.
- **Expected outcome:** Faster first sends from the homepage, less page-hopping before action, and better odds a stressed spouse actually copies one message tonight instead of drifting into more reading.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now adds a dedicated "Want the text first?" jump block under the lane chooser, preselects the matching send lane in the partner invite card, and scrolls users straight to the copy-ready text so they can send first and read deeper only after the partner replies.


#### LF-085 Specific Appreciation Tool should stop reading like generic advice and generate one exact appreciation line, low-energy fallback, and tomorrow repeat so an under-seen spouse can create warmth tonight without inventing the words
- **Page:** `/blog/specific-appreciation-tool.html`
- **Problem:** The page still read like a generic blog post with broad guidance and no real builder, which forced a tired spouse to invent the actual appreciation sentence, the buy-in ask, and the tomorrow follow-through right when the whole point was to reduce friction.
- **User pain:** "I know I should say thank you better. Do not make me build the exact words from scratch when I already feel fried and under-seen."
- **Proposed change:** Turn the page into a tonight-use tool with one appreciation builder, one copy-ready invite, one exact 10-minute plan, one awkward-moment fallback, and one simple tomorrow repeat.
- **Expected outcome:** Faster starts on a warm reconnection rep, less vague gratitude advice, and better odds a stressed spouse actually names one real appreciation tonight instead of postponing it again.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Specific Appreciation Tool now gives users a fill-in builder for the exact appreciation line, low-energy version, tomorrow repeat, and close; adds clear multi-issue routing so people do not use it in hot conflict or hard trust-break situations; and turns the page into a concrete 10-minute rep with examples and awkward-moment fallbacks.


#### LF-084 Homepage same-roof connection lane should say "under the same roof but far apart" everywhere that choice is made so stressed spouses do not confuse emotional distance with being physically apart tonight
- **Page:** `/index.html`
- **Problem:** The homepage already had separate apart and connection lanes, but some of the highest-traffic connection copy still said only "distant tonight," which forced a tired spouse to stop and re-interpret whether that meant same-roof emotional distance or being physically apart.
- **User pain:** "We are not traveling. We live in the same house and still feel off. Do not make me guess whether the distance tool means emotional distance or being apart tonight."
- **Proposed change:** Tighten the homepage connection lane labels, helper copy, and skeptical-partner routing so the connection path explicitly says "under the same roof but emotionally far" while the apart path keeps the travel/opposite-schedule meaning.
- **Expected outcome:** Faster homepage lane choice, less wrong-page hesitation between connection and apart paths, and better odds a stressed spouse copies the right text tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage hero, send-now lane chip, helper note, and skeptical-partner connection references now explicitly say the connection lane is for couples under the same roof but emotionally far, making the apart-vs-distance split clearer before users send or click.

#### LF-083 Blog hub scenario strip should show the trust-boundary lane directly so a stressed spouse does not see 4 core lanes in the copy but only 3 quick-pick tiles when trying to choose fast
- **Page:** `/blog/index.html`
- **Problem:** The blog hub already taught the 4 core lanes clearly, but the quick scenario strip only showed conflict, connection, and apart, which made the fast-pick UI feel inconsistent right where a stressed spouse was trying to choose one lane fast.
- **User pain:** "You told me trust is one of the main lanes. Do not make me hunt lower on the page or second-guess whether trust belongs here tonight."
- **Proposed change:** Add one trust-boundary quick-pick tile to the blog hub scenario strip and make the tile clarify that fresh trust breaks still go to Get Backup Tool while blurry-rule trust nights go to Boundary Definition.
- **Expected outcome:** Faster right-lane confidence on the blog hub, less hesitation for trust users, and better alignment between the blog hub teaching model and the actual quick-pick UI.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** The blog hub quick scenario strip now shows all 4 core lanes, including a dedicated trust-boundary tile that points calm trust-rule nights to Boundary Definition without weakening the existing fresh-trust-break route above.
- **Commit:** `7822411`
- **Live URL:** `https://love.forge.dsdoes.com/blog/`


#### LF-082 Get Backup Tool should stop sounding like a repeatable habit and give one exact follow-up path so a stressed spouse can seek outside help tonight without bad next-step advice
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The page had strong first-send and builder sections, but the lower guidance still treated outside-help outreach like a repeatable relationship habit with generic "repeat 3-7 times," "run this same tool once more tomorrow," and a Weekly Meeting next step that weakened trust on a high-stakes page.
- **User pain:** "If trust got hit or the same fight keeps repeating, do not make me guess the exact follow-up or wonder if this page understands that booking help is not a nightly ritual."
- **Proposed change:** Replace the generic repeat guidance with one concrete outreach-cycle rule, add a copy-ready 24-hour follow-up, wire that follow-up into the builder, and tighten the best-next-step guidance around temperature control and licensed support.
- **Expected outcome:** Higher trust on the highest-stakes page, cleaner next-step execution after the first outreach, and better odds a stressed spouse sends the right follow-up tomorrow instead of drifting or following bad advice.
- **Score:** Impact 4 / Confidence 5 / Ease 4 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now gives one copy-ready 24-hour follow-up in both the main page and the builder, tells users to run one outreach cycle instead of repeating the tool like a habit, and points the next move toward pause/containment and licensed support instead of an off-topic weekly meeting.
- **Commit:** `c00a111`
- **Live URL:** `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`


#### LF-081 Distance Connection Protocol should stop wrong-page starts when apart couples are actually dealing with same-roof distance, hot conflict, or a trust hit
- **Page:** `/blog/distance-connection-protocol.html`
- **Problem:** The page worked well once a user had already chosen it, but people landing there directly from search, a shared link, or the homepage could still treat "we are apart" as the whole diagnosis when the real first move was same-roof connection work, de-escalation, or outside backup for a trust hit.
- **User pain:** "We are apart tonight, but do not make me guess whether this page is still right if we are also fighting or trust feels damaged."
- **Proposed change:** Add one above-the-fold right-tool triage block that tells users when to stay on Distance Connection Protocol and when to switch to Daily 15-Minute Connection Block, Pause-and-Return, or Get Backup Tool.
- **Expected outcome:** Faster right-page confidence for apart couples, fewer wrong-tool starts, and better odds a stressed spouse takes one safe action tonight instead of forcing the distance script onto the wrong problem.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Distance Connection Protocol now opens with one clear "make sure this is the right tool" triage block that separates apart-tonight drift from same-roof distance, hot conflict, and trust-hit situations before users start the script.
- **Commit:** `cd83d81`
- **Live URL:** `https://love.forge.dsdoes.com/blog/distance-connection-protocol.html`

#### LF-080 Blog hub should tell stressed spouses exactly how to choose when trust, conflict, distance, and apart all feel partly true so they stop hesitating and open one right tool tonight
- **Page:** `/blog/index.html`
- **Problem:** The blog hub already had strong first sends and routing, but it still assumed users could quickly resolve overlap in their own head when the real night felt like some mix of trust wobble, hot conflict, emotional distance, and physical apartness.
- **User pain:** "More than one of these is true. Do not make me guess which problem wins tonight before I can move."
- **Proposed change:** Add one above-the-fold triage card on the blog hub that sets the decision order: trust hit first, hot conflict next, then a clear split between apart tonight, emotionally distant under the same roof, and calm boundary-setting.
- **Expected outcome:** Faster first clicks from the blog hub, less second-guessing, and better odds a stressed spouse opens one right tool instead of freezing between overlapping lanes.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now gives one explicit “if more than one thing feels true” triage block near the top, so users can see the exact order for trust hits, hot conflict, apart-tonight distance, same-roof emotional distance, and calm boundary work before choosing a tool.

#### LF-079 Homepage first screen should give apart couples their own obvious route so a stressed spouse does not have to guess whether “far apart” means emotionally distant or physically apart tonight
- **Page:** `/index.html`
- **Problem:** The homepage already handled conflict, distance, and trust well, but physically-apart couples still had to mentally translate the emotional-distance lane into their situation before they could act.
- **User pain:** "We are literally apart tonight. Do not make me guess whether this page means emotional distance or long-distance logistics."
- **Proposed change:** Add one explicit apart-tonight lane on the homepage first screen and match it with copy-ready apart messages in the hero and main send block.
- **Expected outcome:** Faster first-screen recognition for apart couples, less translation friction, and better odds a stressed spouse sends one short connection ask tonight instead of hesitating.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now gives physically-apart couples one obvious “apart tonight” route in the first screen plus matching copy-ready apart messages in the hero and main send picker, so they can act fast without translating the generic distance lane in their head.
- **Commit:** `a677cf7`
- **Live URL:** `https://love.forge.dsdoes.com/`


#### LF-078 Blog hub soft-no path should match the actual situation so a stressed spouse can copy the right calm reply and tomorrow retry for conflict, distance, apart, or trust nights without mentally rewriting a generic reset
- **Page:** `/blog/index.html`
- **Problem:** The blog hub let users match the first ask to distant, conflict, apart, or trust nights, but the soft-no reply and tomorrow retry still stayed generic, which forced a tired spouse to mentally rewrite the calmer follow-up right after getting a no.
- **User pain:** "If they said not tonight, do not make me translate a generic reset text into the actual kind of night we are having."
- **Proposed change:** Make the blog hub soft-no reply and tomorrow retry switch with the same situation picker used for the first ask so the follow-up language stays specific for distant, conflict, apart, and trust nights.
- **Expected outcome:** Less last-second rewriting after a soft no, faster calmer follow-through, and better odds a stressed spouse actually sends the next right text tomorrow.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub soft-no copy now changes with the same distance, conflict, apart, or trust picker as the main send, so both the calm reply and the tomorrow retry sound like the real situation instead of a generic reset users have to mentally translate.

#### LF-077 Blog hub send-now path should match the actual situation so a stressed spouse can copy a distance, conflict, apart, or trust ask without mentally translating a generic reset before sending
- **Page:** `/blog/index.html`
- **Problem:** The blog hub already got users to one send fast, but the main send-now copy still stayed generic, which forced a stressed spouse to mentally rewrite the ask when the real situation was hot conflict, physical distance, or a trust wobble.
- **User pain:** "I already know what kind of night this is. Do not make me translate a generic reset text before I can send it."
- **Proposed change:** Add one situation picker to the blog hub send-now block so the main send and low-energy fallback switch between distant, conflict, apart, and trust wording while keeping the same real-time field.
- **Expected outcome:** Faster sends from the blog hub, less last-second rewriting, and better odds a stressed spouse copies a message that actually fits tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub send-now now lets users match the copy to distant, conflict, apart, or trust nights, and the main send plus low-energy fallback update from the same time field so a stressed spouse can copy a message that fits the real situation instead of translating a generic reset in their head.
- **Commit:** `906b3af`
- **Live URL:** `https://love.forge.dsdoes.com/blog/`

#### LF-076 Bid Response Tool should generate the exact bid reply, low-energy text, and tomorrow repeat so a tired spouse can catch one connection moment tonight without improvising
- **Page:** `/blog/bid-response-tool.html`
- **Problem:** The page still read like light advice and a generic checklist, which left a stressed spouse to choose the right bid, invent the actual warm response, and figure out how to repeat it tomorrow while already low on bandwidth.
- **User pain:** "We miss these tiny moments all the time. Do not make me build the exact words from scratch right when I am trying to show up better."
- **Proposed change:** Turn the page into a practical tonight-use tool with one bid picker, one exact response builder, one low-energy fallback, one 10-minute script, and one 7-day tracker.
- **Expected outcome:** Faster starts, less vague "be more present" advice, and better odds a stressed spouse actually catches and answers one bid tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Bid Response Tool now tells couples how to pick one missed bid, generates the exact response line plus tomorrow repeat text, includes a low-energy fallback and full copy-ready script, and gives one simple 7-day tracker so they can practice one real micro-connection tonight instead of just reading advice.
- **Commit:** `6dbb5ba`
- **Live URL:** `https://love.forge.dsdoes.com/blog/bid-response-tool.html`


#### LF-075 Blog hub soft-no path should give the exact tomorrow retry text so a stressed spouse can do the thinking tonight and send one calmer smaller ask tomorrow without improvising
- **Page:** `/blog/index.html`
- **Problem:** The blog hub told users to wait until tomorrow and retry once, but it still made a tired spouse invent the actual smaller follow-up text the next day right when energy and confidence were likely lower.
- **User pain:** "Do not make me come back tomorrow and write the calmer retry from scratch after we already had a no tonight."
- **Proposed change:** Add one copy-ready tomorrow retry block under the blog hub soft-no path and keep it synced to the same real-time picker used for the first ask and calm reply.
- **Expected outcome:** Less next-day translation friction, faster calmer follow-through after a soft no, and better odds a stressed spouse actually sends the second ask.
- **Score:** Impact 4 / Confidence 4 / Ease 5 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now gives one copy-ready tomorrow retry card in the soft-no path, and it stays synced to the same shared time picker as the first ask and calm reply so a tired spouse can do the thinking tonight and send a calmer smaller ask tomorrow without improvising.
- **Commit:** `c0db82a`
- **Live URL:** `https://love.forge.dsdoes.com/blog/`


#### LF-074 Blog hub soft-no reply should read like a ready-to-send tomorrow retry so a stressed spouse does not hit awkward double-tomorrow wording right before copying the calmer follow-up
- **Page:** `/blog/index.html`
- **Problem:** The blog hub already gave the right soft-no path, but the dynamic no-thanks text could render awkward copy like “Tomorrow, can we try one 10-minute reset tomorrow at 8:30,” which adds friction in the exact moment a tired spouse needs a clean calmer retry.
- **User pain:** "Do not make the retry text sound robotic or duplicated right when I am about to copy it."
- **Proposed change:** Remove the extra leading “Tomorrow,” from the dynamic no-thanks reply so the same shared time logic still works, but the sentence reads naturally across clock times and tomorrow phrases.
- **Expected outcome:** Cleaner copy in the soft-no path, less last-second editing, and better odds a stressed spouse actually sends the calmer retry.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub soft-no copy now keeps the shared tomorrow time logic but drops the duplicate leading “Tomorrow,” so users get a natural ready-to-send retry line instead of awkward double-tomorrow wording.
- **Commit:** `80a193c`
- **Live URL:** `https://love.forge.dsdoes.com/blog/`


#### LF-073 10-Minute Weekly Meeting should generate the exact low-energy invite and calm soft-no retry so busy parents can still lock the meeting tonight when a full weekly meeting feels too heavy
- **Page:** `/blog/10-minute-weekly-meeting.html`
- **Problem:** The page already generated a strong invite, one-issue opener, and close, but it still made a tired spouse invent the lower-pressure fallback when energy was gone or the partner said not tonight.
- **User pain:** "We want the weekly meeting, but do not make me improvise the softer ask or the calm retry when tonight already feels heavy."
- **Proposed change:** Expand the builder and first-step guidance so it outputs one low-energy invite plus one calm soft-no reply that still locks the weekly meeting slot.
- **Expected outcome:** Less translation friction in the highest-resistance moment, more meetings actually scheduled, and better odds a stressed spouse takes one planning action tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** The Weekly Meeting page now gives one low-energy invite and one calm soft-no reply in both the first-step checklist and the builder output, so a tired spouse can still lock the weekly meeting tonight without improvising when energy is low or the first ask gets a soft no.
- **Commit:** `cb39f38`
- **Live URL:** `https://love.forge.dsdoes.com/blog/10-minute-weekly-meeting.html`

#### LF-072 Blog hub send-now path should carry one real time through the first ask and soft-no retry so a stressed spouse can copy a message that sounds ready to send tonight instead of generic placeholder timing
- **Page:** `/blog/index.html`
- **Problem:** The blog hub gave a useful first send and soft-no reply, but both still used generic timing, which forced a tired spouse to mentally rewrite the message right before sending.
- **User pain:** "This is close, but I still have to swap in the real time myself before I can send it."
- **Proposed change:** Add one tiny real-time picker above the blog hub send-now block and wire it into the main first send, low-energy fallback, and soft-no retry text.
- **Expected outcome:** Faster sends from the blog hub, less last-second rewriting, and better odds a stressed spouse actually sends one small ask tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now lets users set one real time in the send-now block, and that same time flows into the main first send, low-energy version, and soft-no retry reply so they can copy a message that sounds ready to send tonight without mentally editing the clock.

#### LF-071 Homepage should make the lane decision obvious when more than one problem feels true so a stressed spouse does not freeze between conflict, distance, and trust on the first screen
- **Page:** `/index.html`
- **Problem:** The homepage already offered strong lane choices and copy-ready sends, but a tired spouse could still see two true problems at once and hesitate on which lane should win tonight.
- **User pain:** "We are fighting and distant and trust feels weird. Do not make me guess which problem gets first shot tonight."
- **Proposed change:** Add one above-the-fold triage card that tells users the exact order: trust hit beats everything, hot conflict beats distance, and only then do connection or boundary work.
- **Expected outcome:** Faster first-screen decisions, less analysis paralysis, and better odds a stressed spouse picks one safe lane and acts tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 5 = **14**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now includes an above-the-fold "If two problems feel true" triage block that tells couples exactly which lane wins tonight, so they can stop debating whether conflict, trust, or distance should go first and move to one safe action faster.


#### LF-070 Daily 15-Minute Connection Block should generate the exact focus line, 24-hour action, and tomorrow close so a tired spouse can run the check-in tonight without translating the framework by hand
- **Page:** `/blog/daily-15-minute-connection-block.html`
- **Problem:** The page already had a good script, but a stressed spouse still had to turn their real issue, tomorrow action, and close into exact words while already low on bandwidth.
- **User pain:** "We know we should do the check-in. Do not make me translate the script into our exact situation right when we finally sit down."
- **Proposed change:** Add one tiny focus-pack builder that writes the exact focus line, 24-hour action line, and tomorrow close from one issue, one action, and one real time.
- **Expected outcome:** Faster starts on the connection path, less mental translation, and better odds couples actually finish the rep and lock tomorrow before drifting.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Daily 15-Minute Connection Block now includes a simple builder that turns one issue, one tiny 24-hour action, and one tomorrow time into three copy-ready lines for the focus, action, and close, so a tired spouse can run the check-in tonight without translating the framework by hand.

#### LF-069 Homepage main partner invite should match the actual situation so a stressed spouse can use the biggest send block without mentally translating a generic reset into conflict, distance, or trust wording
- **Page:** `/index.html`
- **Problem:** The homepage already gave lane-specific hero sends, but the main partner invite lower on the page still stayed generic, which forced users to mentally rewrite the biggest send block after they had already identified whether tonight was conflict, distance, or trust.
- **User pain:** "I know which kind of night this is. Do not make the main send sound generic when I am about to copy the biggest text block on the page."
- **Proposed change:** Add a tiny situation picker to the main partner invite so the exact message switches between distant, hot-conflict, and shaky-trust wording while keeping the same chosen time and calming detail.
- **Expected outcome:** Less translation friction in the homepage primary send block, faster copying, and better odds a tired spouse sends the version that actually fits tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage main partner invite now includes a three-state situation picker for distant, hot-conflict, and shaky-trust nights, and the primary text-now/copy block updates with lane-specific wording while keeping the same chosen time and calming detail, so a stressed spouse can use the biggest send block without mentally translating a generic reset.
#### LF-068 Homepage yes-state should make the close copyable so a tired spouse can end the rep cleanly without improvising the last line after one useful answer
- **Page:** `/index.html`
- **Problem:** The homepage yes-state now gives copy-ready openers, but the close still sat as plain guidance instead of one exact line users could copy when it was time to stop cleanly.
- **User pain:** "We started okay. Do not make me invent the close and accidentally reopen the whole conversation at the end."
- **Proposed change:** Turn the yes-state close into one copy-ready ending line with a low-energy version.
- **Expected outcome:** Cleaner endings, less overtalking after one useful rep, and better odds couples keep tomorrow's follow-through intact.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state now gives one copy-ready close plus one low-energy close with dedicated copy buttons, so a tired spouse can end the rep cleanly tonight without improvising the last line.
- **Commit:** `8c2b728`
- **Live URL:** `https://love.forge.dsdoes.com/`

#### LF-067 Homepage should make the yes-state first question copyable so a stressed spouse can start the rep without translating the opener after the time gets locked
- **Page:** `/index.html`
- **Problem:** The homepage yes-state tells users the best first question, but it still lived as plain text instead of a copy-ready start artifact right after the time got locked.
- **User pain:** "We got to yes. Do not make me invent the exact opener right when we finally sit down."
- **Proposed change:** Turn the yes-state opener into one copy-ready first-question block with a low-energy version.
- **Expected outcome:** Faster starts after lock-in, less awkwardness in the first 30 seconds, and higher odds the rep actually begins tonight.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state now gives one copy-ready first question plus one low-energy opener with dedicated copy buttons, so a stressed spouse can start the rep fast tonight without translating the opener by hand.

#### LF-066 Homepage soft-no path should give the exact tomorrow retry text so a stressed spouse can prepare the calmer follow-up tonight instead of inventing tomorrow's ask from a rule summary
- **Page:** `/index.html`
- **Problem:** The homepage soft-no path had a calm reply and a retry rule, but it still made a tired spouse translate that rule into the exact smaller ask to send tomorrow.
- **User pain:** "If they said not right now, do not make me come back tomorrow and invent the retry text from scratch."
- **Proposed change:** Add one copy-ready tomorrow retry block under the soft-no path and keep it synced to the same real-time picker used above the fold.
- **Expected outcome:** Less mental load after a soft no, faster calmer follow-up tomorrow, and better odds the second ask actually gets sent.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage soft-no flow now includes a copy-ready tomorrow retry text that updates from the same time picker as the first ask, so a stressed spouse can do the thinking tonight and send one calmer follow-up tomorrow without rewriting the ask by hand.

#### LF-065 10-Minute Weekly Meeting should generate the exact invite, one-issue opener, and tomorrow close so busy parents can lock the meeting tonight without translating the framework by hand
- **Page:** `/blog/10-minute-weekly-meeting.html`
- **Problem:** The page had a solid agenda builder, but a tired spouse still had to turn the framework into the actual invite text, one-issue opener, and next-day close while already low on time and attention.
- **User pain:** "We need the weekly meeting, but do not make me convert the agenda into the exact words to send and say tonight."
- **Proposed change:** Expand the builder so users can fill in the exact issue and tomorrow action, then generate the invite, one-issue line, close text, and full meeting pack in one place.
- **Expected outcome:** Faster starts on the planning path, less translation friction, and better odds couples actually lock the meeting tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** The Weekly Meeting page now generates a full meeting pack with the exact invite text, one-issue opener, tomorrow close, and mode-specific agenda from one builder, so busy parents can lock the meeting tonight without translating the framework by hand.


#### LF-064 Homepage follow-through copy should keep tomorrow wording natural when users enter flexible time phrases like "8:30 tonight" or "tomorrow at lunch"
- **Page:** `/index.html`
- **Problem:** The yes-state text is cleaner now, but the homepage still depends on one free-text time field across multiple send and follow-through blocks, so future edits could reintroduce awkward phrasing if tomorrow-specific copy is not guarded carefully.
- **User pain:** "I changed the time once. Do not make the retry or tomorrow text sound robotic right when I am about to send it."
- **Proposed change:** Review the remaining homepage time-dependent strings and tighten any edge-case phrasing that still sounds generated instead of human.
- **Expected outcome:** More trustworthy copy across the full send → yes → soft-no → tomorrow loop, with less last-second manual cleanup.
- **Score:** Impact 3 / Confidence 3 / Ease 3 = **9**
- **Status:** SHIPPED
- **Proof after ship:** Homepage soft-no and tomorrow-repeat copy now turns flexible time phrases into more natural tomorrow wording, so entries like "8:30", "8:30 tonight", "at 8:30", "after bedtime", or "tomorrow at lunch" read like something a real spouse would send instead of robotic fallback text.

#### LF-063 Homepage yes-state lock-in text should mirror the plain-time format cleanly so users do not get awkward duplicate wording like "tonight at 8:30 tonight" after customizing the shared time
- **Page:** `/index.html`
- **Problem:** The homepage now carries the chosen time well across the flow, but the yes-state lock-in copy can still read awkwardly when users type a time phrase that already includes the date context.
- **User pain:** "We finally got a yes. Do not make the confirmation text sound clunky right before I send it."
- **Proposed change:** Normalize or tighten the yes-state sentence so custom times read naturally whether the user types just a time or a fuller phrase.
- **Expected outcome:** Cleaner lock-in copy, higher send confidence after a yes, and less last-second editing in the most important follow-through moment.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state, soft-no retry, and tomorrow-repeat texts now normalize shared time phrases so users get clean human wording like "at 8:30 tonight" or "tomorrow at lunch" instead of awkward duplicates right before they send the follow-through text.

#### LF-062 Homepage should let the optional calming detail flow into the main partner invite so the first send matches the most reassuring wording the user already chose above the fold
- **Page:** `/index.html`
- **Problem:** The homepage now keeps the chosen real time inside the main partner invite, but the optional calming detail still only changes the lane-specific distance text instead of the primary share block most users will actually send.
- **User pain:** "I already added the calming detail that makes this feel safer. Do not drop it when I copy the main text I am most likely to send."
- **Proposed change:** Wire the primary partner invite to reuse the optional calming detail when it strengthens the ask without making the message longer or messier.
- **Expected outcome:** Better emotional safety in the main send, less mismatch between the hero customizer and the primary share block, and higher send confidence tonight.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage main partner invite now reuses the optional calming detail from the hero customizer, and the share block tells users that the primary text keeps that safer wording, so the most likely first send finally matches the emotional safety detail they already chose above the fold.

#### LF-061 Homepage should keep the chosen real time inside the main partner invite so a stressed spouse does not customize the hero texts but still paste a generic send from the primary share block
- **Page:** `/index.html`
- **Problem:** The homepage now carried the chosen real time through the yes, tomorrow, and soft-no follow-through paths, but the main partner invite in the primary share block still stayed generic instead of matching the user's selected time.
- **User pain:** "I already picked the real time. Do not make the main text ignore it and sound less concrete than the follow-up texts."
- **Proposed change:** Connect the primary partner invite to the same homepage time picker so the first send, soft-no retry, yes lock-in, and tomorrow repeat all stay in one specific time flow.
- **Expected outcome:** Higher send confidence from the homepage, less mismatch between first send and follow-through, and a cleaner one-time-set-it experience.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage primary partner invite now updates from the same real-time picker used above the fold, and the text-now button keeps the live chosen time too, so the first send finally matches the follow-through texts instead of falling back to a generic reset ask.

#### LF-060 Homepage should carry the chosen real time into the soft-no retry text so a hesitant spouse can retry tomorrow without mentally converting a generic 10-minute ask into a specific plan
- **Page:** `/index.html`
- **Problem:** The homepage now keeps the chosen time in more follow-through texts, but the soft-no path still tells users to retry tomorrow with a generic 10-minute ask instead of a copy-ready specific time.
- **User pain:** "If they said not right now, do not make me translate tomorrow's retry into a real time by myself."
- **Proposed change:** Connect the soft-no retry copy to the same homepage time picker so the next-day ask stays specific and easier to send.
- **Expected outcome:** Less mental rewriting after a soft no and better odds the retry actually gets sent.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage soft-no reply, retry guidance, and tomorrow step now stay tied to the same real-time picker used above the fold, so a hesitant spouse can copy one specific next-day ask instead of mentally converting a generic 10-minute retry.

#### LF-059 Homepage follow-through texts should keep using the chosen real time so a stressed spouse does not have to mentally rewrite the fallback and tomorrow-repeat messages after customizing the first send
- **Page:** `/index.html`
- **Problem:** The homepage let users set one real time for the first send, but the fallback and tomorrow-repeat texts still hard-coded a different-looking time flow, which forced one more mental rewrite right after the main customization win.
- **User pain:** "I already picked the time once. Do not make me re-edit the next text in my head before I send it."
- **Proposed change:** Connect the wiped-out fallback text and the tomorrow-repeat text to the same homepage time picker and label that shared behavior clearly.
- **Expected outcome:** Faster follow-through after the first send, less copy friction, and a cleaner one-time-set-it flow across the homepage.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage fallback and tomorrow-repeat texts now update from the same real-time picker used in the hero, with small helper notes telling users to change the time once and copy the updated text directly, so the follow-through path stays specific without extra mental editing.

#### LF-058 Blog hub library should make the planning follow-through path visible without looking like a missing fifth filter so calm users know where structure tools live after they pick the right temperature
- **Page:** `/blog/index.html`
- **Problem:** The copy now clarifies that planning is follow-through, not a fifth core lane, but calm users still have to infer where the planning tools live because the filter UI only exposes the 4 core lanes.
- **User pain:** "Got it, planning is not the first move. But once we are calm, show me where the structure tools are without making me hunt the full list."
- **Proposed change:** Add one small planning follow-through entry inside the library guidance so users can jump to the right planning tools without confusing the core-lane system.
- **Expected outcome:** Better follow-through discovery, less hunting in the full list, and cleaner alignment between the lane model and the actual tool library.
- **Score:** Impact 3 / Confidence 4 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub library now adds a calm follow-through planning card plus a planning-only quick jump that points users straight to 10-Minute Weekly Meeting, Weekly State-of-Us Scorecard, and Monthly Marriage Retro, so calm users can find structure tools fast without reading planning as a missing fifth lane.

#### LF-057 Blog hub should align the library lane language and counts so browse-first users do not see a 5-lane chooser above a 4-lane library and pause on whether planning is a separate path
- **Page:** `/blog/index.html`
- **Problem:** The merged browse block is cleaner, but the lane-first section now names conflict, connection, trust, distance, and planning, while the library stats and lane buttons still present 4 lanes, which can create one last credibility wobble before filtering.
- **User pain:** "You just told me planning is a lane, then the library says there are 4 lanes. Do not make me wonder if I am in the wrong section."
- **Proposed change:** Tighten the browse-first copy and library metadata so the lane count and planning path read as one consistent system.
- **Expected outcome:** Cleaner browse trust, less hesitation before filtering, and a more credible lane-first handoff.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now defines conflict, connection, trust, and distance as the 4 core lanes, repositions planning as a calm follow-through path, and updates the library labels to match that system so browse-first users do not hit a lane-count contradiction before filtering.

#### LF-056 Blog hub should tighten the browse-first entry block into one simpler lane-first action so stressed users do not hit both a browse explainer and a second relationship-moment chooser before the library
- **Page:** `/blog/index.html`
- **Problem:** The top and middle of the hub are much cleaner, but users who keep scrolling still hit both “If you still want to browse first” and a full “Pick by relationship moment” grid before the actual tool library, which repeats the same choose-a-lane job.
- **User pain:** "If I ignored the main send path, just get me into the right lane fast. Do not make me re-decide the same thing twice before I can filter tools."
- **Proposed change:** Collapse or merge the browse explainer and relationship-moment chooser so the browse-first path becomes one lane-first handoff into the library with less repeated decision copy.
- **Expected outcome:** Faster entry into the tool library, less scan fatigue below the fold, and a cleaner browse-on-purpose path.
- **Score:** Impact 3 / Confidence 4 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now replaces the separate browse explainer and relationship-moment chooser with one merged “Browse by one lane only” block that tells users to pick one lane, filter inside that lane, then track one number and repeat tomorrow instead of re-deciding twice before the library. Commit: `6a46e83`. Live URL: `https://love.forge.dsdoes.com/blog/`


#### LF-055 Blog hub should collapse the duplicate generic invite block below the skeptical side route so stressed users do not hit a second near-identical send section after they already got the main tonight ask
- **Page:** `/blog/index.html`
- **Problem:** The top flow is stronger, but the later “After you pick a tool, send this text” block still repeats the same invitation job after users already saw the main send-now section, which adds scan friction and choice drift.
- **User pain:** "I already got the text to send. Do not make me compare another almost-same invite before I move."
- **Proposed change:** Remove or tighten the later generic invite block so the page keeps one dominant send section, one yes/no follow-through path, and less repeated invitation copy.
- **Expected outcome:** Faster scanning, less re-deciding, and a cleaner main path from scenario choice to first rep.
- **Score:** Impact 3 / Confidence 4 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now replaces the second generic invite block with one simple reply-state handoff, so users keep the main send section above, then move straight into the yes/no follow-through without comparing another near-identical invitation. Commit: `f6784a6`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-054 Blog hub should make the skeptical-partner route feel secondary to the default tonight path so stressed users do not pause on a niche branch before sending the main ask
- **Page:** `/blog/index.html`
- **Problem:** The top of the hub was clearer, but the skeptical-partner block still appeared high enough to compete with the default tonight path for users who did not actually need it.
- **User pain:** "I am not dealing with a skeptical partner. Do not make me re-evaluate if I should take a side route before I send the normal text."
- **Proposed change:** Demote or tighten the skeptical-partner section so the main tonight path stays dominant and the niche branch still exists without stealing early attention.
- **Expected outcome:** Faster first sends from the default route and less hesitation at the top of the hub.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now tells most couples to ignore the skeptical-partner route, moves that path behind a collapsed details toggle, and keeps the niche scripts available only when the normal first ask is likely to get a fast no, so the main tonight send stays visually dominant. Commit: `92dd543`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-053 Blog hub should make the fastest tonight path even more dominant than browsing so a stressed spouse lands on one send and one first rep before scanning the library
- **Page:** `/blog/index.html`
- **Problem:** The hub was much better, but the top still competed with multiple valid routes and browsing options before the single fastest tonight action fully took over.
- **User pain:** "I already know we need help tonight. Do not make me evaluate three good options before I send one text."
- **Proposed change:** Tighten the top of the blog hub around one primary tonight path, one default first rep, and one lower-noise browse handoff.
- **Expected outcome:** Faster first sends, less browse drift, and more couples starting one tool tonight instead of reading around it.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now opens with one dominant “Fastest tonight path” that tells users to pick one problem, send one small ask, and run the default first rep before browsing, while demoting browse to an explicit fallback and keeping the two safety overrides visible. Commit: `ab9e3b6`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-052 Attention Budget Tool should generate the exact nightly attention-protecting text, one protected-slot plan, and low-energy fallback so a wiped-out spouse can protect one block tonight without inventing the words
- **Page:** `/blog/attention-budget-tool.html`
- **Problem:** The page named the right goal, but it still read like advice. A stressed spouse still had to choose the slot, phrase the ask, and translate the tool into a concrete tonight plan.
- **User pain:** "We are both fried. Do not make me turn this into a custom routine from scratch."
- **Proposed change:** Add one protected-slot builder that writes the invite, exact 10-minute plan, low-energy fallback, and tomorrow proof action.
- **Expected outcome:** Faster starts, less mental translation, and more couples actually protecting one attention block tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Attention Budget Tool now tells couples how to pick the single attention leak doing the most damage tonight, gives a protected-slot builder that writes the exact invite, 10-minute plan, low-energy fallback, and tomorrow proof action, and adds a tighter minute-by-minute script plus 7-day success rule so they can protect one block tonight without inventing the words. Commit: `6c4e54a`. Live URL: `https://love.forge.dsdoes.com/blog/attention-budget-tool.html`

#### LF-051 Resentment Flush Tool should generate the exact resentment line, clean ask, and proof action so a stressed spouse can clear one lingering hurt tonight without improvising
- **Page:** `/blog/resentment-flush-tool.html`
- **Problem:** The page had the right intent, but it still read like generic advice. A stressed spouse still had to decide which resentment to pick, translate it into exact words, and invent the ask plus deadline while already irritated.
- **User pain:** "I know what is bugging me. Do not make me build the sentence from scratch while I am already resentful."
- **Proposed change:** Add one one-issue chooser, one fill-in builder that writes the resentment line, clean ask, proof lock, low-energy version, and pause fallback, plus a sharper 10-minute plan and 7-day keep-or-switch rule.
- **Expected outcome:** Faster starts, less stacking old hurts, cleaner asks, and better odds a couple actually clears one lingering resentment tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Resentment Flush Tool now tells couples how to choose one resentment fast, gives a fill-in builder for the exact resentment line, clean ask, proof action, low-energy version, and pause fallback, and adds a tighter 10-minute plan so they can clear one lingering hurt tonight without improvising.

#### LF-050 Weekly State-of-Us Scorecard should generate the exact score-summary, focus line, and tomorrow action so a stressed spouse can run the check-in tonight without inventing the wording
- **Page:** `/blog/weekly-state-of-us-scorecard.html`
- **Problem:** The scorecard explained what to rate, but a stressed spouse still had to invent the invite, decide how to pick one focus when multiple categories felt low, and phrase the summary plus tomorrow step while already tired.
- **User pain:** "We know something feels off. Do not make us turn four scores into the actual words for tonight."
- **Proposed change:** Add one fill-in builder that outputs the focus line and full score-summary text, plus a sharper 10-minute run of show, low-energy invite, and lowest-score rule.
- **Expected outcome:** Faster scorecard starts, less vague diagnosing, cleaner one-issue follow-through, and better odds a couple leaves with one useful next step tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Weekly State-of-Us Scorecard now gives couples a fill-in builder for the focus line and full score-summary text, tells them to fix the single lowest score instead of debating everything at once, and routes the next tool based on what scored lowest so they can run the check-in tonight without inventing the wording.

#### LF-049 Homepage should make the yes-state lock-in text customizable so a stressed spouse can swap the exact time before sending yes-confirmation without rewriting it in their head
- **Page:** `/index.html`
- **Problem:** The homepage now lets users customize the first ask, but the yes-state confirmation text still hard-coded 8:30, which created one more rewrite right after the partner agreed.
- **User pain:** "We finally got a yes. Do not make me edit the confirmation text before I send it."
- **Proposed change:** Connect the yes-state lock-in text to the same simple time customizer so the confirmation updates live without extra thinking.
- **Expected outcome:** Faster follow-through after yes, less friction between agreement and a real scheduled rep.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage yes-state lock-in text now updates from the same real-time picker used for the first ask, and the page tells users to change the time once above and copy the ready-to-send confirmation exactly as it updates here. Commit: `916a91a`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-048 Homepage should make the first-screen partner send visibly customizable so a stressed spouse can swap the time and send tonight without mentally editing the copy first
- **Page:** `/index.html`
- **Problem:** The homepage now gives strong copy-ready texts, but the time and details were still static, which made a tired spouse mentally rewrite before sending.
- **User pain:** "This is close, but I still have to edit it in my head before I send it."
- **Proposed change:** Add one tiny builder or inline customizer for the best first send so users can set the time and preserve the low-pressure wording.
- **Expected outcome:** Faster sends from the homepage and less friction on the highest-traffic action.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now lets users set one real time and one optional calming detail above the lane-specific first sends, while updating the conflict, connection, and trust texts live so a stressed spouse can copy a ready-to-send version tonight without mentally rewriting it first. Commit: `f8445cd`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-047 One-Issue Rule should generate the exact invite, focus line, full script, and low-energy fallback so a stressed spouse can keep one hard talk on one topic tonight without improvising
- **Page:** `/blog/one-issue-rule.html`
- **Problem:** The page had a good framework, but a stressed spouse still had to invent the one-issue sentence, the specific moment, the tomorrow ask, the mirror line, and the fallback wording while already irritated.
- **User pain:** "I know we need to stay on one issue. Do not make me build the exact words from scratch while I am already worked up."
- **Proposed change:** Add one fill-in builder that writes the invite, focus line, exact 4-line script, and low-energy fallback from one issue, one moment, one ask, one time, and one mirror line.
- **Expected outcome:** Faster starts, less improvising, cleaner one-topic talks, and better odds a couple actually finishes one useful rep tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** One-Issue Rule now gives couples a fill-in builder that generates the invite, focus line, full script, and low-energy fallback, while updating the default script live so they can stay on one issue tonight without improvising.

#### LF-046 Clean Complaint Script should generate the exact complaint, mirror line, and doable ask so a stressed spouse can raise one issue tonight without sounding attacking
- **Page:** `/blog/clean-complaint-script.html`
- **Problem:** The page has a solid framework, but a stressed spouse still had to invent the exact complaint wording, the mirror line, and the alternative ask while already irritated.
- **User pain:** "I know I need to say this better. Do not make me build the sentence from scratch while I am already mad."
- **Proposed change:** Add one fill-in builder that outputs the clean complaint, the mirror line, one doable alternative, and one low-energy fallback, plus a sharper one-issue chooser.
- **Expected outcome:** Faster starts, less blame language, better odds of one useful ask tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Clean Complaint Script now helps couples choose one issue fast, generates the exact complaint, mirror line, doable alternative, and low-energy fallback, and adds tighter examples plus a cleaner success metric so they can raise one issue tonight without improvising.


#### LF-045 Silence Breaker should generate the exact opener, one-issue line, and close so a stressed spouse can break the freeze tonight without improvising
- **Page:** `/blog/silence-breaker-tool.html`
- **Problem:** The page had the right structure, but a stressed spouse still had to invent the opener, choose the right one-issue framing, and close the rep cleanly while already feeling awkward and disconnected.
- **User pain:** "We both went quiet. Do not give me theory. Give me the exact words to start and help us stop after one small win."
- **Proposed change:** Add one practical builder that outputs the opener, one-issue line, closing line, and low-energy fallback, plus sharper silence triage, examples, and a cleaner 10-minute script.
- **Expected outcome:** Faster starts after silence, less awkward improvising, better odds of one useful reconnection rep tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Silence Breaker now tells couples when to use it versus Pause-and-Return, helps them pick one silence issue fast, gives a fill-in builder for the opener, one-issue line, close, and low-energy fallback, and adds a tighter 10-minute script plus examples so they can break the freeze tonight without improvising.

#### LF-044 Homepage first screen should give lane-specific first-send texts so a stressed spouse can copy the exact ask that fits tonight instead of translating one generic invite
- **Page:** `/index.html`
- **Problem:** The homepage first screen got users to a partner send fast, but the copy was still generic across conflict, distance, and shaky-trust nights, which made the first ask less precise under stress.
- **User pain:** "I know which lane fits. Give me the exact text for this situation so I do not have to rewrite it in my head."
- **Proposed change:** Replace the single generic hero send with three lane-specific copy-ready texts for hot conflict, distance, and shaky trust, plus one sharper rule that active trust breaks should still skip to outside backup.
- **Expected outcome:** Faster sends from the homepage first screen, less translation friction, and better yes-rates because the ask matches the actual problem tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage hero now gives three copy-ready first sends matched to conflict, distance, and shaky-trust nights, plus a clearer warning that active trust breaks should skip the trust-reset text and go straight to backup first. Commit: `d17b416`. Live URL: `https://love.forge.dsdoes.com/`


#### LF-043 Blog hub should make the first send visible right after scenario choice so a stressed spouse gets to one text before browsing the full library
- **Page:** `/blog/index.html`
- **Problem:** The blog hub routes people well, but the first copy-ready partner ask still sat below several teaching and scenario blocks, which slowed the fastest useful action on mobile.
- **User pain:** "I picked the situation. Now give me the exact text before I keep scrolling."
- **Proposed change:** Move one copy-ready partner ask closer to the top scenario choice so the send step becomes visible sooner without needing a jump down the page.
- **Expected outcome:** Faster partner sends from the blog hub, less scroll drift, stronger tonight-start rate.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now puts a copy-ready first send directly under the scenario chooser, adds a low-energy fallback beside it, and shows the safest default first rep plus the two safety overrides right there so a stressed spouse can send one text before drifting into more browsing.


#### LF-041 Homepage first screen should make the first send feel even more immediate on mobile so a stressed spouse gets to one text faster
- **Page:** `/index.html`
- **Problem:** The homepage is strong, but the first send still sits below multiple blocks on smaller screens, which can slow the fastest useful action.
- **User pain:** "I already know we need help. Just give me the text faster."
- **Proposed change:** Tighten the first-screen handoff from lane choice to partner-send so the copy-ready ask becomes visible sooner on mobile.
- **Expected outcome:** Faster partner sends, less scrolling friction, stronger first-action rate.
- **Score:** Impact 4 / Confidence 3 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now puts the first copy-ready partner ask directly inside the hero flow right after lane choice, so mobile users can copy the send text before dropping into the longer homepage blocks. Commit: `8f2a5ed`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-042 Fight Fair should generate the exact opener, one-issue script, and low-energy fallback so couples can have one hard talk tonight without improvising
- **Page:** `/blog/fight-fair-protocol.html`
- **Problem:** The page had the right intent, but a stressed spouse still had to invent the opener, choose the issue on the fly, and assemble the actual fight-cleaner script while already irritated.
- **User pain:** "We keep having the same fight. Do not give me theory. Give me the exact words and tell us how to stay on one issue tonight."
- **Proposed change:** Add one one-issue selector, one copy-ready opener, one full 12-minute script, one 5-minute fallback, and one builder that outputs the exact fight plan.
- **Expected outcome:** Faster starts on hard talks, less kitchen-sink fighting, cleaner next-step closes, and more couples actually using Fight Fair tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Fight Fair now tells couples when not to use it, helps them choose one issue fast, gives a copy-ready opener plus full and short scripts, and generates a personalized fight plan so they can handle one hard talk tonight without improvising. Commit: `df174ac`. Live URL: `https://love.forge.dsdoes.com/blog/fight-fair-protocol.html`


#### LF-040 Repair Attempt should generate the exact apology, repair line, and tomorrow follow-through so a cold couple can repair tonight without improvising
- **Page:** `/blog/repair-attempt-tool.html`
- **Problem:** The page explained repair well enough, but a stressed spouse still had to invent the apology, the impact line, and the next-step close while already feeling defensive or shut down.
- **User pain:** "I know I need to repair this, but give me the exact words so I do not ramble, defend myself, or disappear."
- **Proposed change:** Add one repair builder that outputs the opener, main repair line, low-energy fallback, and tomorrow follow-through, plus one exact 10-minute script and a cleaner 7-day recovery tracker.
- **Expected outcome:** Faster repair starts, less defensive apologizing, stronger follow-through after friction, and more couples actually completing one repair rep tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Repair Attempt now gives couples a fill-in builder for the opener, repair line, low-energy fallback, and tomorrow close, plus one copy-ready 10-minute script and a simple recovery tracker so they can repair one specific miss tonight without inventing the words.

#### LF-039 Homepage should make the soft-no path explicit so a hesitant couple knows the exact next move without falling out of the 7-day loop
- **Page:** `/index.html`
- **Problem:** The blog hub now handles a soft no better, but the homepage still leans harder toward yes-state follow-through than a clear decline path with a tomorrow retry rule.
- **User pain:** "My partner did not say yes tonight. Tell me exactly what to send, when to retry, and when to stop pushing."
- **Proposed change:** Add one compact soft-no block on the homepage with one calm reply, one tomorrow retry rule, and one safest-default next tool reminder.
- **Expected outcome:** Better homepage follow-through after a soft no, less pressure, stronger next-day re-entry.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now gives soft-no users one copy-ready calm reply, one wait-until-tomorrow retry rule, and one safest-default next-tool reminder, so a stressed spouse knows what to send tonight, when to retry, and when to stop pushing without dropping out of the 7-day loop.

#### LF-038 Blog hub should make the no-thanks response less awkward so hesitant couples know the next safe move without reopening the whole library
- **Page:** `/blog/index.html`
- **Problem:** The hub now handles skeptical partners better on the first ask, but the decline path still mostly routes users to a low-energy solo text instead of clearly telling them what to do tomorrow or which tool to hold for later.
- **User pain:** "My partner said not tonight. Tell me the next safe move so I do not turn this into another fight or just give up."
- **Proposed change:** Add one short no-thanks follow-up block with an exact reply, a tomorrow retry rule, and one safest-next-tool reminder.
- **Expected outcome:** Less friction after a soft no, fewer pressure spirals, stronger next-day follow-through.
- **Score:** Impact 4 / Confidence 3 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now gives a clear soft-no path with one exact no-pressure reply, one wait-until-tomorrow retry rule, and one safest-default next-tool reminder so a stressed spouse knows what to do after "not tonight" without reopening the whole library.

#### LF-037 Blog hub should make the skeptical-partner route obvious before library browsing so hesitant couples can send one low-pressure ask without digging
- **Page:** `/blog/index.html`
- **Problem:** The homepage now handles skeptical partners better, but the blog hub still leans harder toward browsing tools than toward one copy-ready skeptical invite.
- **User pain:** "My partner is skeptical. Do not make me browse more. Give me the one text and first tool fast."
- **Proposed change:** Add one skeptic-friendly send block near the top of the blog hub with one copy-ready ask, one lighter fallback, and one recommended first tool.
- **Expected outcome:** Faster sends from the hub, less browsing drift, stronger follow-through for hesitant couples.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now gives skeptical partners one obvious low-pressure experiment ask, one lighter fallback for people who hate the word tool, and one default first-tool route with the same conflict/trust safety overrides, so a stressed spouse can invite a hesitant partner without digging through the library first.

#### LF-036 Homepage should make the skeptical-partner 7-day ask copyable so users can send the experiment text without retyping it under friction
- **Page:** `/index.html`
- **Problem:** The homepage explains the skeptical-partner pitch well, but the strongest 7-day experiment ask still lives as plain copy instead of a one-tap send action.
- **User pain:** "My partner is skeptical. Give me the exact low-pressure 7-day text so I can send it fast."
- **Proposed change:** Turn the skeptical-partner experiment opener into a copy-ready action with one lighter fallback so resistance drops faster.
- **Expected outcome:** Faster skeptical-partner invites, less friction in the highest-resistance path, stronger first send rate from the homepage.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now gives skeptical partners one copy-ready 7-day experiment ask plus one lighter fallback text, so a stressed spouse can send the test fast without rewriting the pitch. Commit: `883b304`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-035 Pause-and-Return should generate the exact pause, return, and close text so flooded couples do not have to translate the tool in the middle of a fight
- **Page:** `/blog/pause-and-return-tool.html`
- **Problem:** The page explained the structure, but stressed spouses still had to invent the actual pause line, return line, low-energy fallback, and closing step while already flooded.
- **User pain:** "Do not make me improvise mid-fight. Give me the exact words to pause, come back, and end cleanly."
- **Proposed change:** Add one fill-in builder that outputs the exact pause text, return text, low-energy fallback, and closing line from one issue, one return time, and one next step.
- **Expected outcome:** Faster de-escalation, less in-the-moment improvising, and more couples actually completing the return instead of stalling after the pause.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Pause-and-Return now gives couples a fill-in builder that generates the exact pause line, return line, low-energy fallback, and closing line so they can de-escalate without rewriting the tool mid-fight. Commit: `594c67b`. Live URL: `https://love.forge.dsdoes.com/blog/pause-and-return-tool.html`


#### LF-034 Homepage should make the stop-and-switch override copyable so couples can send the safer pivot text without rewriting it under stress
- **Page:** `/index.html`
- **Problem:** The homepage now tells couples when to stop repeating a tool, but the override text still sits as plain copy instead of a one-tap action inside the continuation flow.
- **User pain:** "We know we should switch, but give us the exact text in a way we can copy fast."
- **Proposed change:** Turn the stop-and-switch text into a copy-ready action so the safer pivot is even easier to use on mobile.
- **Expected outcome:** Faster safe pivots, less friction during repeat breakdowns, stronger follow-through on the override path.
- **Score:** Impact 3 / Confidence 4 / Ease 4 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now turns the stop-and-switch override into a copy-ready action inside the 7-day continuation flow, so couples can pivot faster on mobile without rewriting the safer text. Commit: `0326d65`. Live URL: `https://love.forge.dsdoes.com/`


#### LF-033 Homepage should make the trust-safe override obvious inside the 7-day loop so couples do not keep repeating the wrong tool after a shaky first rep
- **Page:** `/index.html`
- **Problem:** The homepage now explains the repeat-tomorrow loop better, but the continuation path can still under-emphasize when to stop repeating and switch to backup because tomorrow reveals a trust hit or the same escalation pattern.
- **User pain:** "You told us to repeat the tool, but tell us when not to keep forcing the same rep."
- **Proposed change:** Tighten the 7-day loop with one sharper stop-and-switch rule for trust hits and repeat escalation so the safe override is obvious in the continuation block.
- **Expected outcome:** Safer repeat behavior, less wrong-tool persistence, stronger trust in the homepage guidance.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage 7-day loop now tells couples exactly when to stop repeating: trust hits route straight to Get Backup Tool, a second escalation means stop forcing the same rep, and one copy-ready stop-and-switch text makes the safer pivot obvious.

#### LF-032 Homepage should make the 7-day keep-or-swap loop obvious after the first send so couples do not lose momentum below the fold
- **Page:** `/index.html`
- **Problem:** The homepage now gets users to the partner-send step faster, but the follow-through after a first yes still leans on scattered score/plan blocks instead of one locked-in next-day repeat and day-7 decision.
- **User pain:** "We used one tool. Now tell us what to repeat tomorrow and how we decide if this stays in the week."
- **Proposed change:** Add one clear after-the-first-rep continuation block on the homepage with one 7-day metric, one next-day action, and one day-7 keep-or-swap rule.
- **Expected outcome:** Better homepage follow-through, less drift after one good rep, stronger 7-day retention.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now turns the old generic 7-day block into a clear after-the-first-rep loop: ask the same one-number question right after the rep, send one copy-ready tomorrow-repeat text, repeat the same tool at the same rough time, and keep or swap on day 7 using a simple 4-of-7 rule.

#### LF-031 Blog hub should make the “we finished one rep” follow-up obvious so couples know what to do over the next 7 days
- **Page:** `/blog/index.html`
- **Problem:** The hub now gets users to the right first rep faster, but after they finish one tool the continuation path still spreads across scorecards, plans, and browsing instead of one simple keep-or-swap follow-up.
- **User pain:** "We did one good rep. Now tell us the one thing to track and what to do tomorrow instead of dumping us back into the library."
- **Proposed change:** Tighten the after-the-tool follow-through so one 7-day metric and one next-day action become the obvious continuation after a first rep.
- **Expected outcome:** Better repeat use, less post-tool drift, stronger 7-day follow-through from the hub.
- **Score:** Impact 4 / Confidence 3 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now tells couples exactly what to do after the first good rep: track one shared 1-to-10 movement check for 7 days, repeat the same tool tomorrow at the same rough time, and make one keep-or-swap decision on day 7 instead of falling back into the library.

#### LF-030 Blog hub makes the “yes, let’s do it” step obvious right after the partner invite
- **Page:** `/blog/index.html`
- **Problem:** The hub now gets users to the send step faster, but the follow-through after a partner says yes still competes with more browsing and chooser blocks instead of one locked-in first rep.
- **User pain:** "My partner said yes. Now tell us exactly which first tool to run without making us think again."
- **Proposed change:** Tighten the post-invite flow so one clear first rep becomes the dominant next action after the copied text.
- **Expected outcome:** More immediate tool starts after the partner invite, less drop-off between copied text and actual use, better tonight completion rate.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now makes the yes-state explicit with one default first rep — 15-Minute Connection Block — and limits overrides to only two cases: hot conflict goes to Pause-and-Return, and active trust breaks go to Get Backup Tool. Commit: `1bbdb01`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-029 Blog hub sharpens the copy/send step so users can invite a partner without reading past the fold
- **Page:** `/blog/index.html`
- **Problem:** The blog hub now splits tonight path vs browse path better, but the partner-invite scripts still sit below several chooser blocks instead of becoming the next obvious action.
- **User pain:** "Okay, I picked the tool. Now give me the exact text to send without making me keep scrolling."
- **Proposed change:** Move one copy-ready partner invite higher and tighten the top flow so choosing a path naturally leads into one send action.
- **Expected outcome:** Faster partner sends, less drop-off between tool choice and actual use, stronger share intent from the hub.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now puts the partner-send step directly under the first scenario chooser, renames the copy block around one obvious next action, and tells users to stop browsing once they have the text. Commit: `716d5a5`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-028 Blog hub sharpens the first-screen split between fix-tonight tools and browse-the-library paths
- **Page:** `/blog/index.html`
- **Problem:** The blog hub may still make stressed users read too much library framing before the best tonight-use route feels obvious.
- **User pain:** "I do not want to browse a relationship content library. I want the one tool we should use tonight."
- **Proposed change:** Tighten the top of the blog index so one direct tonight path stays dominant before the broader tool library.
- **Expected outcome:** Faster first clicks from the hub, less browsing drift, higher start rate on one tool.
- **Score:** Impact 4 / Confidence 3 / Ease 3 = **10**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now opens with one stronger split: start tonight via the quiz or scenario tiles, or intentionally jump to the filtered library, while the old duplicate quick-pick layer is removed and the trust-break route stays visible above the fold. Commit: `52c2cf6`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-027 Homepage sharpens the handoff from starter choice to partner send so the next move stays obvious after the first click
- **Page:** `/index.html`
- **Problem:** After choosing a starter, the homepage still makes users scan several response-state sections before clearly pushing the best share/send action.
- **User pain:** "I picked the tool. Now tell me the exact message to send without making me keep scrolling through edge cases."
- **Proposed change:** Tighten the post-starter flow so the partner invite becomes the obvious continuation before secondary branches.
- **Expected outcome:** Faster partner sends, less homepage wandering, higher first-action follow-through.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now turns the post-starter block into a strict two-step flow: pick one starter, then jump straight to the copy-ready partner text, with the old extra starter card reframed as a fallback instead of another browsing detour. Commit: `a04d89c`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-026 Homepage trims below-the-fold choice overload so the first clear path stays obvious after the hero
- **Page:** `/index.html`
- **Problem:** The hero was strong, but the homepage still repeated too many alternate routes below the fold, which turned one clean decision into more scanning.
- **User pain:** "I already picked the problem. Stop making me evaluate five more sections before I act."
- **Proposed change:** Tighten the homepage continuation blocks so one primary next step stays dominant after the first screen.
- **Expected outcome:** Faster clicks into one tool, less scroll fatigue, stronger first-session action rate.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Homepage now removes the duplicate quick-start and one-issue chooser cards directly under the hero, so users move from the first-screen starter strip straight into the partner-send action instead of re-picking the same problem again. Commit: `83888c8`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-025 Distance Connection Protocol adds a copy-ready nightly script builder so apart couples stop translating the routine by hand
- **Page:** `/blog/distance-connection-protocol.html`
- **Problem:** The page had a useful routine, but tired spouses still had to decide the focus, rewrite the invite, and improvise the actual call structure when they were already apart and low on energy.
- **User pain:** "Do not make me invent the distance call tonight. Give me the exact text and tell us what one thing to cover."
- **Proposed change:** Add one clear pick-one-focus block, stronger first-step copy, and a builder that outputs an exact nightly script for normal, low-energy, and repair-first versions.
- **Expected outcome:** Faster starts, less overtalking while apart, and more couples actually running one distance check-in tonight.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Distance Connection Protocol now tells couples how to choose one focus fast, gives stronger starter copy and low-energy fallback text, and generates one exact nightly script for normal, low-energy, or repair-first distance check-ins. Commit: `ca0fe3d`. Live URL: `https://love.forge.dsdoes.com/blog/distance-connection-protocol.html`

#### LF-024 Daily 15-Minute Connection Block adds copy-ready full and short scripts so tired couples can run the rep without translating it
- **Page:** `/blog/daily-15-minute-connection-block.html`
- **Problem:** The page explained the structure, but stressed spouses still had to assemble the opener, reflection line, close, and low-energy fallback by hand.
- **User pain:** "Do not make me translate the framework tonight. Just give me the exact words and the short version if we are wiped out."
- **Proposed change:** Add copy buttons for the main opener and low-energy text, one full 15-minute script couples can copy in one block, and one 5-minute fallback script for exhausted nights.
- **Expected outcome:** Faster starts, less improvising under stress, and more couples actually finishing the connection rep tonight.
- **Score:** Impact 4 / Confidence 5 / Ease 4 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Daily 15-Minute Connection Block now gives couples one-tap copy for the main opener and low-energy text, one full 15-minute run script with reflection and close lines, and one 5-minute fallback they can use on wiped-out nights. Commit: `f0bccf7`. Live URL: `https://love.forge.dsdoes.com/blog/daily-15-minute-connection-block.html`

#### LF-023 No-Secret-Threads Rule adds a fill-in boundary builder so couples stop vague phone-trust talks and lock one exact rule tonight
- **Page:** `/blog/no-secret-threads-rule.html`
- **Problem:** The page had the right idea, but it still left stressed spouses to invent the actual phone-trust rule, miss response, and review plan by hand.
- **User pain:** "I do not need another warning about secret messages. I need the exact words for the rule and what happens if we miss it."
- **Proposed change:** Turn the page into a practical trust-boundary tool with one strict use/not-use filter, one fill-in builder for the boundary, miss response, and low-energy text, plus one exact 10-minute run of show and a concrete 7-day metric.
- **Expected outcome:** Faster phone-trust resets, less vague debating, more couples leaving with one exact rule they can test for 7 days.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** No-Secret-Threads Rule now tells users when to use it versus Get Backup Tool, gives a fill-in boundary builder for the rule, miss response, and low-energy text, and adds a 10-minute reset flow plus a concrete 7-day trust-tension metric. Commit: `930db94`. Live URL: `https://love.forge.dsdoes.com/blog/no-secret-threads-rule.html`

#### LF-022 Transparency Tool adds a fill-in disclosure builder so couples stop vague-confessing and clear one gray-area issue tonight
- **Page:** `/blog/transparency-tool.html`
- **Problem:** The page was generic and advice-heavy, so stressed spouses still had to invent the actual disclosure, repair close, and future rule by hand.
- **User pain:** "I do not need a lecture on transparency. I need the exact words to clear this up before it turns into a bigger trust fight."
- **Proposed change:** Turn the page into a practical trust-repair tool with one strict use/not-use filter, one fill-in disclosure builder, one repair-close script, one low-energy fallback, and one exact 10-minute run of show.
- **Expected outcome:** Faster honest disclosures, less vague minimizing, fewer late-night spirals around gray-area secrecy, and more couples leaving with one rule for the next 7 days.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Transparency Tool now tells users when to use it versus Get Backup Tool, gives a fill-in builder for the main disclosure, repair close, and low-energy text, and adds a 10-minute repair flow plus a concrete 7-day trust-tension metric. Commit: `ef874a4`. Live URL: `https://love.forge.dsdoes.com/blog/transparency-tool.html`

#### LF-021 Boundary Definition Tool adds a prefilled boundary builder so shaky-trust couples stop staring at blanks
- **Page:** `/blog/boundary-definition-tool.html`
- **Problem:** The page gives examples, but stressed spouses still have to assemble the final boundary line, consequence, and review time by hand.
- **User pain:** "I get the idea, but I still need the exact rule text we can copy tonight."
- **Proposed change:** Add one fill-in builder that outputs a finished boundary statement, consequence line, and check-in text in one block.
- **Expected outcome:** Faster starts on the trust-boundary path, less freezing at placeholders, more copied scripts.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Boundary Definition Tool now lets couples pick one lane, fill in the exact rule, miss response, and review time, then copy three finished lines for the boundary statement, consequence, and review text without rewriting from scratch. Commit: `fd962ce`. Live URL: `https://love.forge.dsdoes.com/blog/boundary-definition-tool.html`


#### LF-020 Get Backup Tool adds a fill-in builder so couples can copy finished outreach texts instead of staring at placeholders
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The page had strong scripts, but tired spouses still had to replace `[one issue]`, helper type, and time windows by hand before they could send anything.
- **User pain:** "I do not want to translate templates tonight. Just turn this into the exact texts I need to send."
- **Proposed change:** Add one builder that outputs the partner text, outreach text, and yes-reply after users fill in one issue, one helper type, and two time options.
- **Expected outcome:** Faster sends, less blank-page friction, and more booked support from the trust-break path.
- **Score:** Impact 4 / Confidence 5 / Ease 4 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now lets couples fill in the one issue, pick the helper type, and generate three copy-ready texts for the partner ask, outreach send, and yes-reply without rewriting placeholders. Commit: `a358f34`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-019 Get Backup Tool adds exact reply scripts so couples book support without improvising
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The tool helped couples choose a helper and send outreach, but it still left the next high-stakes moment blank once someone actually replied.
- **User pain:** "Okay, they answered. What do I say back without oversharing or fumbling the booking?"
- **Proposed change:** Add one reply block with copy-ready scripts for yes, no-room, and what-is-going-on responses so users can lock a next step fast.
- **Expected outcome:** More booked calls, less stalling after first contact, and higher follow-through from the trust-break backup path.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now gives couples exact reply texts for booking a time, asking for one referral when someone has no room, and giving one-sentence context when asked what is going on. Commit: `183cdfb`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-018 Get Backup Tool adds copy buttons and a stop-at-first-yes chooser so stressed couples send outreach faster
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The tool had strong scripts, but tired spouses still had to select, highlight, and mentally sort helper types before sending anything.
- **User pain:** "I do not want to rewrite or overthink this. Just help me pick the helper and send the text."
- **Proposed change:** Add one stop-at-first-yes helper chooser plus copy buttons for the partner text and each helper-specific outreach script.
- **Expected outcome:** Faster first send, less friction on mobile, and fewer stalled trust-break users.
- **Score:** Impact 4 / Confidence 5 / Ease 4 = **13**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now tells users exactly when to say yes to therapist vs coach vs mentor, lets them copy the partner invite instantly, and adds one-tap copy buttons for each outreach script so they can send messages without rewriting. Commit: `fcc5d35`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-017 Blog hub splits active trust breaks from calmer boundary-setting so users get the safer first click
- **Page:** `/blog/index.html`
- **Problem:** The quick-pick and relationship-moment trust entries still sent stressed users to Boundary Definition first, even though active lying, cheating, hidden money, or secret messages need outside backup before a boundary talk.
- **User pain:** "I clicked trust, but I still have to guess whether this is a boundary talk night or a get-help-now night."
- **Proposed change:** Split the trust route into active trust-break vs shaky-boundary cases so the blog hub sends high-risk trust situations straight to Get Backup Tool and keeps Boundary Definition for calmer rule-setting.
- **Expected outcome:** Better trust triage, fewer wrong first clicks, tighter consistency across every trust entry point on the hub.
- **Score:** Impact 4 / Confidence 4 / Ease 3 = **11**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now routes hard trust hits to Get Backup Tool in both the quick-pick strip and the relationship-moment chooser, while keeping Boundary Definition for lower-drama rule-setting. Commit: `eeb1624`. Live URL: `https://love.forge.dsdoes.com/blog/`


#### LF-016 Blog hub surfaces the trust-break backup route before generic browsing
- **Page:** `/blog/index.html`
- **Problem:** The homepage already routed trust-hit couples faster, but the blog hub still looked like a general library instead of clearly telling users when to skip browsing and get outside backup first.
- **User pain:** "I landed on the tool list, but I still need the safest first click when trust got hit."
- **Proposed change:** Add one high-contrast trust-break route near the top of the blog index that sends users directly to Get Backup Tool before generic communication tools.
- **Expected outcome:** Safer routing from the tool library, less wrong-page browsing, better consistency between homepage and blog hub.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Blog hub now opens with a trust-break escape hatch that tells users not to start with one more late-night feelings talk, gives one copy-ready outside-help text, and sends them straight to Get Backup Tool before the general library. Commit: `7b71d4e`. Live URL: `https://love.forge.dsdoes.com/blog/`

#### LF-015 Homepage adds a trust-hit fast exit above the fold so couples route to backup before the wrong talk
- **Page:** `/index.html`
- **Problem:** The homepage mentioned trust-break escalation lower on the page, but a spouse landing cold could still miss the safest route when lying, cheating, hidden money, secret messages, or repeat blowups were the real issue.
- **User pain:** "We do not need more browsing. Tell us the safest page to open first tonight."
- **Proposed change:** Add one high-contrast trust-hit block above the lane chooser with one exact text and one direct button into Get Backup Tool.
- **Expected outcome:** Faster safer routing for high-stakes couples, less wrong-tool usage, better first-screen clarity.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Homepage first screen now gives trust-hit couples one direct warning not to start with a long feelings talk, one copy-ready text, and one obvious button into Get Backup Tool before the generic lane chooser. Commit: `6dc87c1`. Live URL: `https://love.forge.dsdoes.com/`

#### LF-014 Get Backup Tool adds one exact 24-hour follow-up so couples do not freeze after silence
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The page told users to follow up tomorrow, but still made them invent the actual text and guess when to switch helper type.
- **User pain:** "We sent the messages. Now what do we say tomorrow without sounding desperate or awkward?"
- **Proposed change:** Add one copy-ready 24-hour follow-up text plus one quick rule for when to switch helper type.
- **Expected outcome:** More second-touch follow-through, fewer dropped outreach attempts, better odds of booking support within 7 days.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now gives one exact 24-hour follow-up text, tells users not to add more story, and adds one simple helper-switch rule so they know what to send next after silence. Commit: `4c464bd`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-013 Get Backup Tool adds helper-specific outreach examples so users do not stall after choosing
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The page made helper choice faster, but the outreach script was still generic instead of showing one ready text for therapist, coach, and trusted mentor.
- **User pain:** "Okay, we picked the helper. What exactly do I text this person?"
- **Proposed change:** Add three short copy-ready outreach examples matched to therapist, coach, and trusted mentor.
- **Expected outcome:** More sends tonight, less rewriting, better follow-through after the chooser.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now keeps one base outreach line and adds three copy-ready examples for therapist, coach, and trusted mentor so couples can send the right ask fast without rewriting from scratch. Commit: `c3d3ab7`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

#### LF-012 Get Backup Tool makes the helper-choice order faster to scan on mobile
- **Page:** `/blog/third-party-escalation-tool.html`
- **Problem:** The tool had the right sequence, but the helper-type choice was buried in body copy instead of a faster visual decision block.
- **User pain:** "Just tell me who to contact first so we can send the messages tonight."
- **Proposed change:** Turn the helper-type order into one obvious chooser with one-line guidance for therapist, coach, or trusted mentor.
- **Expected outcome:** Faster outreach, less debate, better follow-through on the trust-break path.
- **Score:** Impact 4 / Confidence 4 / Ease 4 = **12**
- **Status:** SHIPPED
- **Proof after ship:** Get Backup Tool now shows a three-card helper chooser near the top, gives a default rule for therapist-first trust breaks, and updates the partner script to match the faster chooser. Commit: `7417e18`. Live URL: `https://love.forge.dsdoes.com/blog/third-party-escalation-tool.html`

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
