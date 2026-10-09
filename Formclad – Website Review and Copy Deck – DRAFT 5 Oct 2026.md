# FORMCLAD – WEBSITE REVIEW AND COPY DECK – DRAFT
5 October 2026 | formclad.com.au (Webflow)

Two parts: what still needs doing to finish the site, and a page-by-page tone pass with proposed copy.
Nothing in Part B has been changed on the site yet. Mark each line KEEP, CHANGE or EDIT, and the approved lines get applied in one go.

---

## THE VOICE

Direction: Pentagram's authority with MASH's bluntness. Established, confident and mature, with one line per page that a reader might disagree with.

**Core message (from Sofia, 6 Oct; corrected 7 Oct):** what clients value is that Formclad is *project first*. We want the whole project finished to a high standard, not just our scope.

How to say it accurately:
- We work **through the builder**: we keep the programme on track, plan around the other trades, and finish the job properly.
- We do **not** coordinate the other trades directly. That's the builder's job.
- Our clients are **builders and owner-builders**. Don't lead with architects.
- Say what we do first: commercial and architectural roofing, cladding and roof plumbing.

Approved line: "We put the project first. We work through the builder to keep the programme on track, plan around the other trades, and finish the job properly." 

**Design rules (6 Oct):**
- No eyebrows or section labels above headings. Simple is best.
- Numbers (01, 02, 03) appear only in the main menu.
- Numbered steps in a sequence (e.g. "What happens next") are fine.
- Everything left-aligned, including the sector list (changed 8 Oct).
- Sectors, everywhere they appear: Commercial / Community / Education / Health / Hospitality / Residential (alphabetical). These match the actual project list (ELC, Goolwa Ambulance, Kalara and Mortlock clubrooms, Golden Grove Tavern) and the positioning (architectural residential plus selected small commercial). Industrial, Multi-residential, Civic, Workplace and Adaptive Reuse were removed.
- Framing: we skin the building and control the water. Metal roofing, wall cladding, flashings, gutters and drainage make one metal envelope whose job is keeping the building dry. Services H1: "Metal skin. Dry building." Second line held in reserve: "Skin, roof, water. Under control." The Home kicker keeps Roofing · Cladding · Roof plumbing (each is distinct).
- Footer service links use the Services page headings: Architectural metal roof systems / Wall cladding and façade / Roof plumbing and detailing / Remedial and complex upgrades.
- No promised response times: "we reply by email", not "within two business days".

**Colour rules (8 Oct, applied in the Designer, not yet published):**
- **White** is the base. Most sections are white and flow together, with no alternating grey bands. (Colour scheme 4, which was light grey, is now white.)
- **Warm stone #D6D2C4** is for page headers only (colour scheme 5).
- **Brand navy #252A34** gets one full-width statement block per page, plus the footer. Colour scheme 2, which was near-black #191919, is now navy.
  - Home: the mid-page CTA (section_cta19).
  - About: "Built around standards".
  - Services: "Who this is built for".
  - Projects: the proof section.
  - Careers: the culture section.
  - Contact: the existing dark band.
- The last section before the footer is always white, so there's a clear gap above the navy footer.
- **Radical red #FF2E63** is for buttons and accents only. It is never a background.
- Changing a section's colour means changing its colour-scheme class, not adding one-off colours.
- Careers role cards: each "Apply" link jumps to the form on the same page (#apply). With four roles, there's no need for separate role pages.

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

> **STATUS: PUBLISHED 7 Oct 2026, 9:12am Adelaide (22:42 UTC 6 Oct)** to formclad.com.au and www.formclad.com.au. Work With Formclad taken off Draft and published in the same release.
>
> **Still to do in the Designer after launch:** project gallery on Projects Template, main photos for Kalara Reserve and Golden Grove, Careers "Position of interest" dropdown options.
>
> **Applied**
> - Every Part B change on Home, About, Services, Projects, Careers, Work With Formclad, Navbar, Footer and 404.
> - Dead buttons removed: 18 on Services, 3 on Projects, 2 on About, 6 on Careers.
> - Careers "View role" ×4 and "Apply now" now jump to the application form (#apply).
> - Projects and Services CTAs linked to Contact and to Work With Formclad.
> - About SEO description now names Travis and Sofia.
> - Also fixed: Services "Program" → "Programme", "facade" → "façade", "&" → "and" in card headings.
>
> **Resolved 6 Oct**
> - Master Builders SA membership confirmed; the line stays.
> - Materials confirmed. Cards rewritten: COLORBOND® and Zincalume® / Zinc and copper / Aluminium systems / Corten and feature metals.
> - Careers roles now:
>   - Qualified roof plumbers
>   - Subcontractors
>   - Casuals
>   - "Not on the list?" (fourth card kept for the grid layout)
>
>   Form radio "Supervisory or leading hand" is now "Subcontractor with own ABN".
>
> **Still open**
> - About team: Sofia's card added 6 Oct, after Travis. General Manager; bio: "Keeps the crew looked after, the projects moving and the next job coming in." Gareth and Jack stay.
>   - Team photos are hidden on all cards. To show them, upload full-size headshots in the Designer and unhide the image on each card.
>   - Estimating and accounts are with BuildLaunch (Mairead, Marianne). They're not named on the site; an optional "dedicated specialists" line is still to be decided.
> - Careers "Position of interest" dropdown options: edit in the Designer (not editable through the API). They should be Qualified roof plumber / Subcontractor / Casual / Other.
>
> **Emails confirmed 6 Oct:** estimates@ and accounts@ are both active and in use.
>
> **Note:** Services and Projects now link to Work With Formclad. That page must come off Draft in the same publish, or those buttons will 404.

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
| Fit card heading | Seeking lowest-cost shortcuts? | **Removed 8 Oct.** Talking about price this openly reads as tacky. Don't discuss pricing on the site. | |
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

---

## PART C – CLEARING OLD WORDPRESS PAGES FROM GOOGLE (7 Oct 2026)

Google still lists pages from the old WordPress site. They no longer exist on Webflow and now show a "page not found". Found in a search for "formclad roofing":
- /category/books/ ("Books")
- /people-spearheading-the-new-design-revolution/ (theme demo post)
- /author/admin/page/2/ ("admin – Page 2")
- /tag/material/ ("Material Tag")

### Step 1 – 301 redirects in Webflow
In Webflow: **Site settings → Publishing → 301 redirects**. Add each row (old path → redirect to), then **publish the site**. Redirects only take effect after a publish.

| Old path | Redirect to | Covers |
|---|---|---|
| `/people-spearheading-the-new-design-revolution` | `/` | The demo post |
| `/category/(.*)` | `/` | /category/books and any other category pages |
| `/tag/(.*)` | `/services` | /tag/material and any other tag pages |
| `/author/(.*)` | `/about` | /author/admin and its page 2, 3… |
| `/page/(.*)` | `/` | Old blog paging |
| `/feed` | `/` | Old RSS feed |
| `/wp-content/(.*)` | `/` | Old images and uploads still indexed |
| `/wp-admin` | `/` | Old login page |
| `/wp-login.php` | `/` | Old login page |

`(.*)` means "anything after this", so one row catches every page in that group. Webflow doesn't need trailing slashes.

### Step 2 – Google Search Console
1. Go to search.google.com/search-console and add the property **formclad.com.au** (Domain property).
   - If it asks for DNS verification, choose the "HTML tag" method on a URL-prefix property instead.
   - Paste the tag into Webflow: Site settings → SEO → Google Site Verification.
   - Publish, then click Verify.
2. **Sitemaps** → submit `https://www.formclad.com.au/sitemap.xml`.
3. **Removals → New request → "Remove all URLs with this prefix"**, one request each:
   - `https://www.formclad.com.au/category/`
   - `https://www.formclad.com.au/tag/`
   - `https://www.formclad.com.au/author/`
   - `https://www.formclad.com.au/people-spearheading-the-new-design-revolution/`

   Removals hide the results within about a day. The redirects make the removal permanent.
4. **URL inspection → Request indexing** for `https://www.formclad.com.au/` and `https://www.formclad.com.au/about`, so Google picks up the new descriptions sooner.

### Off-site, not the website
- **Google Business Profile:** phone shows 0477 163 878 (Travis's mobile). Change it to 08 7085 7973 and add business hours.
- **Facebook, Instagram, LinkedIn bios:** still use "solutions" and "premium outcomes". Update them to the project-first message.

---

## PART D – DIRECT CLIENTS (7 Oct 2026)

**Decision:** no separate homeowner page yet. Direct clients (owner-builders, owners of architectural homes or commercial buildings) are inside the Business Plan's market position. A dedicated page waits until there are two or three direct-client projects to show.

**Published 7 Oct, 9:32am Adelaide:** new Services section after "Who this is built for":
> **Working with us directly** – Owner-builders, and owners of architectural homes or commercial buildings, can engage us directly. It works best when there are drawings, a clear scope and time to do it properly. We'll tell you early if a builder is the better route. [Talk to us about your project → Contact]

The Services page is now left-aligned like About (the sector list stays centred).

**Before taking the first direct job:** confirm SA domestic building contract and building indemnity insurance requirements with Master Builders SA or the broker.

## SERVICES PAGE RESTRUCTURE (8 Oct 2026, unpublished)

Order: Header → What we deliver → Materials → Where projects win or lose → Who we work with (navy) → Closing CTA (white).

**Where projects win or lose** (the how). Intro: "Most roof problems are decided before anyone climbs a ladder."
- On paper: Falls, junctions and fixings resolved while changing them still only takes a pen.
- Where trades meet: Our work meets windows, frames and finishes. We fit around what's there and leave our part right for the next trade.
- Project first: Sites change. When they do, we adjust. The finished building matters more than our part of it.
- At handover: Every seam, edge and flashing checked against the drawings. Nothing left for someone else to fix.

**Who we work with** (the who; merges "Who this is built for" and "Working with us directly"). Intro: "Whoever brings us in, the project comes first."
- Builders: Most of our work comes through builders. We price the drawings, work in with the other trades on site, and finish our part to the standard the building deserves.
- Architects: Bring us in while the details are still on paper. We'll help make the roof and façade buildable, then deliver it through your builder.
- Owners and owner-builders: Owner-builders, and owners of architectural homes, can engage us directly when there are drawings and a clear scope. If a builder is the better route, we'll tell you early.
- Button: Talk to us about your project.

Copy rules from this round: don't promise dates (delays happen; say project first instead). Don't claim we coordinate other trades; we work in with their work. No pricing talk.

Design: no stock icons, no boxed cards. Cards use the "is-rule" modifier: no background, a thin line on top (navy on white, faint white on navy).

## TYPE AND ALIGNMENT (8 Oct 2026, unpublished)

- **One left edge.** The navbar container now has the same 80rem max width as the page content, so the FORMCLAD wordmark lines up with every headline on every page.
- **Page H1s are sentence case** (shared "head" style): weight 500, up to 5.5rem, with more room above the headline in every page header. The wordmark is the only all-caps lockup at the top of a page. The Home hero ("hero-headline", over a photo) stays in caps for now, pending a decision.
- **About, How we work** is a plain full-width list, not an accordion: value on the left, line on the right, thin navy rules. No chevrons. "Built on collaboration" now reads: "We work in with the builder and the trades around us."

## ABOUT PAGE TEST LAYOUT AND NEW FOOTER (8 Oct 2026, unpublished)

Reference direction: Built Environs, Haven Constructions, 38th. White space is held by structure (a rule on top, a narrow left column for the heading, content in the right two-thirds) rather than left floating.

**About (test page, before rolling out site-wide)**
1. Header on white (no stone band). H1 "The project comes first." with "comes first." in radical red (the one-word accent, class text-accent).
2. Full-width project photo directly under the headline (aerial roof).
3. Credentials line.
4. Why builders come back (image cards).
5. How we work: rule on top, H2 left, values right in large type.
6. Built around standards (now white; still uses a Relume stock image, to replace).
7. The team: the page's navy statement block, with the heading left and names and roles right in two columns on faint rules. "Good people. Good crew." sits below it with a light outline button.
8. CTA on white.
Removed the hidden leftover sections (stats, layout121).

**Wordmark rule:** one wordmark. The navbar and footer FORMCLAD use the same face, weight 600, -0.01em tracking, uppercase. The footer version is scaled to the full container width.

**Footer:** links and tagline at the top, a "Recently completed" card (currently text only, linking to the ELC; add the photo in the Designer and update it when a new project goes live), then the full-width wordmark, then legal and socials.

**Team portraits:** book 20 minutes of on-site crew portraits at the Mortlock Park shoot.

**Update 9 Oct:** About header test rejected. It's back to the stone header band with a plain sentence-case H1 ("The project comes first."), no red accent and no photo under the headline. Stone page headers stay the site-wide system. Standards section copy updated, and its image is the Fleurieu ELC (our photo, despite the Relume file name). The credentials line has moved to the bottom of About.
