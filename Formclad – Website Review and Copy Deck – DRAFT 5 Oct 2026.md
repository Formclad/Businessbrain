# FORMCLAD – WEBSITE REVIEW AND COPY DECK – DRAFT
5 October 2026 | formclad.com.au (Webflow)

Two parts: what still needs doing to finish the site, and a page-by-page tone pass with proposed copy.
Nothing in Part B has been changed on the site yet. Mark each line KEEP, CHANGE or EDIT, and the approved lines get applied in one go.

---

## THE VOICE

Direction: Pentagram's authority with MASH's bluntness. Established, confident and mature, with one line per page that a reader might disagree with.

There's no written tone-of-voice guide in the Business Brain or in Drive. These rules come from that direction, the five values (Purpose, Mission & Values) and the Capability Statement v2. Once approved, they become the guide.

1. **Say it once, plainly.** Short declarative sentences. One idea each. No warm-up.
2. **Have a point of view.** Every page earns one line with an edge, the kind that makes a price-shopper leave and an architect lean in. One per page, not one per paragraph.
3. **Proof over adjectives.** Name the project, the material, the award. "Master Builders SA 2026 Excellence Award" beats "award-winning quality".
4. **Quiet confidence.** No hype words, exclamation marks or superlatives you can't prove. Never use: *solutions, outcomes, premium, world-class, integrated, passionate, seamless*.
5. **Talk like a peer.** Builders and architects are the reader. Use their words: scope, set-out, programme, RFI, junction, handover.
6. **Ration the signature phrases.** These are good but overused across the site right now:
   - "envelope": at most once per page
   - "no surprises": once across the whole site (it currently appears six times)
   - "early engagement" / "talk to us early": once per page, as the call to action
7. **House style.**
   - Sentence case for every heading and button ("Start a conversation", not "Start a Conversation").
   - Australian spelling, with "programme" for a schedule.
   - "façade" with the cedilla, to match the Capability Statement.
   - Buttons are a verb and an object ("See the project", "Send a tender"). Never a lone "Learn", "Explore", "Read" or "Discuss".

---

## PART A – WHAT'S LEFT TO FINISH THE SITE

Ranked by damage to the business if left.

### Critical (live now)

1. **Every project page shows Relume placeholder text.**
   - The Projects Template is static text with no CMS connection.
   - Every project URL shows "Project name here", Lorem ipsum, "Tag one/two/three", "Full name", "March 2023" and a "www.relume.io" link.
   - No photos, summary or location appear, even though the CMS holds them. The Fleurieu ELC alone has 10 gallery images and an award write-up.
   - Fix: connect heading, summary, location, sector, main image and gallery to the CMS fields, and remove Client/Date/Website.
   - **DONE 5 Oct (unpublished):**
     - Heading, summary, location and main image now pull from the CMS.
     - Placeholder tags, Date, Role and the relume.io link removed.
     - Navbar, Footer and Global Styles added (the template had none).
     - Closing "See a project like yours?" section added.
   - **Still to do in the Designer:**
     - Gallery: the API can't attach a list to a multi-image field.
     - Hide the main image when a project has none.
2. **Two of three live projects have no main image** (Kalara Reserve Clubrooms, Golden Grove Beer Garden), so their cards on /projects are blank.
3. **Mortlock Park Clubrooms** is an empty draft. Finish it or delete it.
4. **Dead buttons.** Unlinked "Learn", "Explore", "Discuss", "Request" and "Read" buttons:
   - about 14 on Services
   - 2 on the Projects CTA ("Start a conversation", "Request design input")
   - "View role" ×4 and "Apply now" on Careers
   - all three "Read" buttons on Projects go to About

   Remove them or link them (proposals in Part B).
5. **Phone number: DECIDED 5 Oct.** 08 7085 7973 is the business number and stays on the site. 0477 163 878 is Travis's mobile.
   - To do: update the Capability Statement contact lines (cover and page 10) to 08 7085 7973.
6. **Footer lists "Maintenance & Repair".** This contradicts the positioning ("We do not chase general maintenance") and invites the leak calls you don't want.

### Before launch

7. **The 404 page is blank.** Proposed copy is in Part B.
8. **No share images on any page**, so links posted to LinkedIn or Facebook have no picture. One branded image across the site would fix it, using project photos from the Fleurieu ELC.
9. **Alt text missing** on 4 of 6 Home gallery images and all Services images. This matters for accessibility and Google Images.
10. **Careers: confirm the roles are real.** It advertises roof plumbers, cladding installers, apprentices and leading hands. If you aren't hiring for all four, a live list of unfilled roles costs credibility. Also, the sector list (Education / Health / …) on Careers isn't relevant there.
11. **About: Sofia is missing.** The Capability Statement names Sofia Calado as General Manager. The team section shows Travis, Gareth Bruce and Jack Spacie. Confirm Gareth and Jack are current, and add Sofia.
12. **About SEO description says "led by Travis"**. It should name both, or neither.
13. **About: "Master Builders SA member"**. I couldn't confirm membership from the Brain; the files only mention the MBSA SWMS platform. Remove the line if you aren't a member.
14. **Materials claims.** The site lists zinc, copper, aluminium systems and "specialty finishes". Your projects show COLORBOND®, Zincalume®, Klip-Lok, Topdek, Custom Orb, Mini Orb, Corten and Danpalon. List what you've actually installed (proposal in Part B).
15. **Projects page says "Filter by sector, material, or service"**, but there is no filter. Remove the line.

### Drafts: decide, don't drift

16. **Work With Formclad**: ready. Turn off Draft when publishing.
17. **Who We Work With**: mostly repeats About and Services. Recommend folding its two good ideas ("We're not a last-minute fix" and the timing stages) into Services, then deleting the page.
18. **Materials**: placeholder logo strip (two images repeated 16 times), unlinked buttons. Keep as a draft until there's real content, or delete. Services already covers materials.
19. **Terms & Conditions**: draft. Nothing currently links to it. Publish it only if your quotes reference it.
20. **Materials and Project Types templates**: drafts, so fine to leave.

---

## PART B – COPY DECK, PAGE BY PAGE

Format: **Current** → **Proposed**, with a short why. Lines not listed are fine as they are.

### HOME

| Element | Current | Proposed | Why |
|---|---|---|---|
| H1 | The metal envelope. Built with discipline. | **Built to detail. Built to last.** | Matches the Capability Statement tagline, so the site and the PDF say the same thing. (The current line is good too. Keep it if you prefer, but then change the Capability Statement to match.) |
| Kicker | Early collaboration · Detailed coordination · Architect-aligned delivery | **Roofing · Cladding · Roof plumbing · South Australia** | The current line is three abstractions; say what you do. |
| Button 1 | Discuss a project | **Start a project** | Shorter. |
| Button 2 | View selected work | **See the work** | |
| Gallery list | Selected architectural projects defined by precision, restraint and longevity | **Roof and cladding, ELC @ Fleurieu Wellbeing Precinct. Master Builders SA 2026 Excellence Award, Commercial under $5M.** | Proof over adjectives. Your best fact isn't on the homepage. |
| Supplier strip | Working within proven architectural envelope systems. | **Proven systems. Installed properly.** | |
| CTA heading | Talk to us early | **Talk to us before the drawings are locked.** | |
| CTA body | If the envelope matters, bring us in before it's locked. Early engagement reduces RFIs, redesign and site delays. | **The cheapest fix is the one made on paper.** | The page's one line with an edge. |

Keep: "Proof is in the junctions." "Roof. Façade. The details in between." "We take on a select number of projects each year…"

### ABOUT

| Element | Current | Proposed | Why |
|---|---|---|---|
| H1 | Clear. Disciplined. Trusted. | **Fewer jobs. Done properly.** | Your own line further down the page ("We'd rather deliver fewer jobs at a higher level") is stronger than three adjectives, so lead with it. |
| Credential | Master Builders SA member | *(remove unless confirmed)* | See A13. |
| H2 | How we work - every day | **How we work** | Fixes the hyphen. "Not statements. Behaviours." does the rest. |
| Value 2 | All Over It | **Organised and ahead of it** | Matches the Capability Statement. Sentence case for all five values. |
| Step 1 body | What's included. What's not. . | **What's in. What's out. In writing.** | Typo (double full stop). |
| Team | Travis, Gareth, Jack | **Add: Sofia Calado, General Manager. Leads the commercial and delivery side: pricing, contracts, programme.** | See A11. |
| Proof body | We don't promise more than we deliver. We show up prepared, put the project first, and work in step with architects and builders — no excuses, no rework, no surprises. | **We don't promise more than we deliver. We turn up prepared and work in step with the architect and the builder.** | "No rework" is a claim a builder can disprove; the line works without it. |
| Card 4 title | No surprises | **Problems surface early** | Rationing the phrase. |
| Button | Start a Conversation | **Start a conversation** | Sentence case. |

Keep: "Formclad exists for projects where finish matters…" "Not statements. Behaviours." "No shortcuts. No 'that'll do.'" "Good people. Good crew." "We'll tell you straight whether it's a fit." This page is already the closest to the target voice.

### SERVICES

| Element | Current | Proposed | Why |
|---|---|---|---|
| H1 | Envelope scope, delivered straight | **Three trades. One standard.** | |
| Sub | Services designed for complex architectural and commercial work — integrated from early design through to delivery. | **Metal roofing, wall cladding and roof plumbing for architectural and commercial work. From design input to handover.** | Drops "designed for" and "integrated". |
| "What we deliver" body | Metal roofing, cladding, and roof plumbing. Integrated from design through completion. | **One contractor for the roof, the walls and the water.** | It currently repeats the sub. |
| Fit card heading | Seeking lowest-cost shortcuts? | **Chasing the cheapest price?** | |
| Fit card body | We're not the right partner. We work with teams that prioritise envelope performance and finish integrity. | **Then we're not your roofer. We price the job properly, and we build it the way we priced it.** | The page's one line with an edge. |
| Final CTA heading | Have a complex project? | **Got a roof that keeps the architect up at night?** | |
| Final CTA body | Early engagement changes everything. Talk to us before scope locks. | **Send it to us before the scope locks.** | |
| Final CTA buttons | Discuss / Request | **Start a conversation / Invite us to tender** (→ Work With Formclad) | Gives the new landing page a home. |
| Materials cards | Colorbond and steel / Zinc and copper / Aluminium systems / Specialty finishes | **COLORBOND® and Zincalume® / Concealed-fix and standing seam (Klip-Lok, Topdek) / Corten and feature metals / Translucent roofing (Danpalon)** | Lists only what your projects prove (A14). Keep zinc and copper if you've done them; the estimating rules price them. |
| "Learn" / "Explore" buttons (about 14) | unlinked | **Remove all**, except one per card linking to the matching project | |

Keep: "Typically engaged when…" on each service card. It's precise and confident, and very Pentagram.

### PROJECTS

| Element | Current | Proposed | Why |
|---|---|---|---|
| H1 | Built to last | **Look closely.** | "Built to last" moves to the Home H1. This one dares the reader. |
| Sub | Roofing and cladding projects across South Australia—delivered with disciplined planning and clean execution | **Roofing and cladding across South Australia. Education, health, civic and hospitality.** | Adds the missing full stop and drops the adjectives. |
| H2 | Work we've completed | **Recent work** | |
| Body | …Filter by sector, material, or service to find work relevant to your brief. | **Each one started with the drawings and finished with the details.** | No filter exists (A15). |
| Card 1 | On time / Sequencing locked. Milestones met. No surprises. | **On programme / Sequence agreed before mobilising. Milestones tracked weekly.** | Describes a process; the old line was an unconditional promise. |
| Card 2 | On specification / Every detail matches the brief. Materials perform as intended. | **On specification / Built to the detail and checked against it before handover.** | |
| Card 3 | Under control / Budget held. Quality maintained. Scope clear from start. | **Under control / Scope in writing. Variations priced before they're built.** | Matches what you actually do (Getting Paid & Variations). |
| "Read" ×3 | → About | **Remove** | |
| CTA buttons | Start a conversation / Request design input (unlinked) | **Link to Contact / link to Work With Formclad as "Invite us to tender"** | |

### CAREERS

| Element | Current | Proposed | Why |
|---|---|---|---|
| H1 | Build with pride | **We don't cut corners. Neither should you.** | Blunt, and filters applicants. |
| Apprentices body | …You'll work alongside people who refuse corners. | **…You'll work alongside people who won't cut them.** | The current phrase doesn't parse. |
| Benefits H2 | Work that holds up | **Steady work. Good gear. A crew that backs you.** | It currently repeats "Work that holds up to scrutiny" higher on the page. |
| Roles | Four open roles | **Show only roles you're hiring for now; otherwise one line: "Not hiring right now? Send us your details anyway."** | See A10. |
| Sector list | Education / Health / … | **Remove** | Not relevant to applicants. |

### CONTACT
Already updated this session (homeowner line, step 2, builders' link). Remaining items:
- "Start a Conversation" button casing.
- The phone number (A5).

### WORK WITH FORMCLAD
Already finished this session. One proposed tweak to match the voice:

| Element | Current | Proposed |
|---|---|---|
| CTA lead | Tell us about the project and we will take it from there. | **Send the drawings. We'll tell you straight if it's a fit.** |

### NAVBAR AND FOOTER

| Element | Current | Proposed | Why |
|---|---|---|---|
| Nav button | Start a Conversation | **Start a conversation** | Sentence case. |
| Footer links | Roofing Solutions / Cladding Solutions | **Roofing / Cladding** | No "solutions". |
| Footer link | Maintenance & Repair | **Remove** | A6. |
| Footer link | Architectural Builds | **Remediation** (→ Services) | Covers the "selected remedial" work you do take on. |
| Column label | company | **Company** | |
| Footer (new, optional) | — | **Builders: invite us to tender** (→ Work With Formclad) | A second quiet route to the landing page. |
| Strapline | Architectural metal roofing and cladding for considered projects across South Australia. | Keep | Already on voice. |

### 404 (currently blank)

> **Nothing here.**
> We'd have caught that on site.
> [Back to the homepage]

---

## SUGGESTED ORDER OF WORK

1. Fix the project template (A1). This is the only item that is embarrassing right now on the live site.
2. Approve the copy deck. I'll apply all approved lines in one pass and remove the dead buttons.
3. Add project images and alt text (A2, A9), and the share image (A8).
4. Decide the drafts (A16–A20) and the phone number (A5).
5. One full review in the Designer, then publish.
