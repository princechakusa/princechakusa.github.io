# PORTFOLIO_GUIDE.md

## Audit Results

### Critical Issues Found

1. **No GitHub profile README** — `princechakusa/princechakusa` repo does not exist. This is the single most impactful missing element on a GitHub profile. Every recruiter and collaborator who lands on your profile sees a blank default page instead of a curated introduction. HIGHEST PRIORITY.
2. **Repository naming inconsistencies** — `PaMarket` and `Guestcare` use PascalCase, which is a code class naming convention, not a repository naming convention. `ggs-v3-platform` is a cryptic internal codename that communicates nothing to an outside viewer.
3. **Missing repository descriptions** — `ggs-v3-platform` and `Guestcare` have no description text at all. GitHub shows these in search results, on your profile, and in your pinned repos. A blank description is a missed pitch opportunity.
4. **Casual repository description** — `fixhub-backend` uses the placeholder-quality description "This is for my Maintenance Dashboard." It reads like a draft note rather than a professional project summary.
5. **0 followers, 0 following** — No community engagement signals. GitHub's algorithm and human visitors both use follower count as a credibility proxy. Following relevant accounts in PropTech, hospitality tech, and full-stack development is the fastest free lever.
6. **No GitHub topics/tags on any repositories** — Topics are GitHub's primary SEO and discoverability mechanism. Without them, your repositories will not surface in topic-based searches (e.g., `property-management`, `proptech`, `hospitality`).
7. **No pinned repositories configured** — GitHub defaults to showing your six most recently updated repos. Without pinning, your profile may surface incomplete or experimental work rather than your strongest projects.
8. **Profile bio undersells** — "Customer Experience Specialist & Tech Enthusiast" is generic and does not communicate scope, geography, credentials, or technical depth. It could describe anyone.
9. **Stats inconsistency** — The portfolio site states 400+ units managed, but Prince's verified figure is 350+. Inconsistent self-reported numbers reduce credibility. Pick one accurate figure and use it everywhere.

---

### Recommended Repository Naming

| Current Name | Recommended Name | Reason |
|---|---|---|
| fixhub-backend | property-maintenance-hub | Descriptive, immediately searchable, follows kebab-case convention |
| PaMarket | pamarket | GitHub convention is lowercase kebab-case for all repo names |
| ggs-v3-platform | vacationhub-operations | Clear, professional, eliminates cryptic internal acronym |
| Guestcare | guestcare-platform | Lowercase, adds context about the product type |
| princechakusa.github.io | princechakusa.github.io | Keep as is — GitHub Pages naming convention requires this format |

---

### Recommended GitHub Profile Bio

```
Operations & Property Management Leader building PropTech solutions | 350+ units | Dubai UAE | CompTIA A+ | CS Student
```

This bio works because it: leads with professional identity, signals technical output (building), names the domain (PropTech), anchors with a quantified achievement (350+ units), gives geographic context (Dubai UAE), lists a hard credential (CompTIA A+), and shows current growth (CS Student).

---

### Recommended Pinned Repositories (in order)

1. `princechakusa.github.io` — Portfolio website; the anchor piece that ties everything together
2. `property-maintenance-hub` — Most professionally packaged project; leads with your core domain
3. `guestcare-platform` — Demonstrates hospitality technology focus
4. `vacationhub-operations` — Showcases analytics and operational intelligence work
5. `pamarket` — Shows web development breadth beyond your primary domain

Pin these in this order. GitHub displays pinned repos left-to-right, top row first. Your strongest pieces should land in slots 1 and 2 where eye-tracking research shows the most attention.

---

### Required GitHub Topics for Each Repository

Apply these via each repository's Settings tab or by editing the repository description on the repo homepage.

**princechakusa.github.io**
`portfolio` `html` `css` `javascript` `github-pages` `property-management`

**property-maintenance-hub**
`property-management` `maintenance` `dashboard` `supabase` `hospitality` `proptech`

**guestcare-platform**
`guest-experience` `hospitality` `crm` `short-term-rental` `automation` `dubai`

**vacationhub-operations**
`property-management` `kpi-dashboard` `hospitality` `analytics` `real-estate` `operations`

**pamarket**
`marketplace` `javascript` `ecommerce` `zimbabwe` `html` `css`

---

## Banner Design Concept

### Specifications

- **Dimensions:** 1500 x 500px (GitHub profile header standard)
- **Color palette:**
  - Espresso `#2C2420` — primary background
  - Gold `#B8860B` — accent, headline, decorative line
  - Cream `#F9F7F2` — body text, secondary elements
- **Style:** Modern minimal with a very slight grain texture overlay (3–5% noise). The grain adds tactility and prevents the flat digital look. No gradients — solid blocks of color with one gold accent line.
- **Typography:**
  - Name ("Prince Chakusa"): Playfair Display Bold, 72–80px, Cream `#F9F7F2`
  - Tagline ("Operations Leader. Technology Builder."): Montserrat SemiBold, 24–28px, Gold `#B8860B`
- **Structural elements:**
  - One horizontal gold rule (2px) running full width roughly one-third down from the top
  - Subtle grid lines (8–10% opacity) suggesting precision and systems thinking
  - Optional: Dubai skyline silhouette in very dark espresso-on-espresso (5–8% opacity), right-aligned, giving geographic anchoring without visual clutter
- **Recommended tools:** Figma (free tier is sufficient), Canva (use the 1500x500 custom size), or Adobe Express

### What to avoid
- Stock photography of laptops, coffee cups, or city skylines at full opacity — they read as template work
- Bright saturated colors that clash with your existing portfolio palette
- Cramming in logos, skill badges, or stats — the banner is branding, not a resume

---

## Profile Picture Style Recommendations

- **Subject:** Professional headshot. The portfolio already embeds a photo — use that same image for consistency across GitHub, LinkedIn, and email.
- **Crop:** Face takes 70–80% of the frame. A slight tilt (5–10 degrees) or 3/4 angle reads as approachable rather than stiff. GitHub crops to a circle, so center the face and leave minimal dead space at the edges.
- **Background:** Dark neutral or blurred architectural/interior background. This harmonizes with the espresso-and-gold palette. Avoid bright white or busy backgrounds — they fight with GitHub's interface.
- **Attire:** Business casual or smart casual with a visible collar. The collar communicates professionalism without being overly formal. Avoid t-shirts for a public professional profile.
- **Post-processing:** Slight contrast boost (10–15%), mild sharpening on the face, and a warm tone shift that complements the gold accent color. Avoid filters that desaturate skin tones.
- **Technical minimum:** 400x400px source file. GitHub renders profiles at 460px diameter maximum — anything below 400px will appear pixelated.
- **Style references:** Review the profile photo approach of Satya Nadella (Microsoft CEO), Naval Ravikant (investor/technologist), or senior hospitality executives on LinkedIn. Common pattern: simple background, direct gaze, neutral or dark clothing, no clutter.

---

## Suggested New Projects

Each project below is selected because it directly demonstrates a skill that PropTech employers, hospitality operators, and technical hiring managers look for in a candidate bridging operations and technology.

### 1. Property Management SOP Generator
**Stack:** Python, Markdown, Jinja2 templates
**Rationale:** Demonstrates automation of operational knowledge — a core PropTech differentiator. Shows that Prince can codify institutional expertise, not just perform it. Generates standard operating procedures from a structured data input. High resume signal for property management companies investing in operational technology.

### 2. STR Revenue Calculator and Forecasting Tool
**Stack:** JavaScript, Chart.js or Recharts, HTML/CSS
**Rationale:** Short-term rental revenue modeling is a tangible, shareable tool. Property owners and managers will actually use this, which means GitHub stars, forks, and real-world validation. Demonstrates PropTech and data visualization skills in one project.

### 3. Maintenance Response Time Analytics Dashboard
**Stack:** Python (pandas, matplotlib), Chart.js for frontend
**Rationale:** This project quantifies one of Prince's documented achievements (maintenance response time improvement). It transforms a resume bullet into interactive, verifiable proof. A hiring manager can see the methodology behind the claim.

### 4. Guest Review Sentiment Analyzer
**Stack:** JavaScript or Python, free NLP API (Hugging Face Inference API or Google Natural Language API free tier)
**Rationale:** Demonstrates AI integration without requiring expensive infrastructure. Guest reviews are the primary reputation management tool in short-term rental operations. A tool that analyzes sentiment trends shows both domain expertise and emerging technology adoption.

### 5. UAE Holiday Home Compliance Checklist App
**Stack:** React or vanilla JavaScript, local storage for state
**Rationale:** UAE's DTCM (Department of Tourism and Commerce Marketing) has specific holiday home licensing requirements. A compliance tool demonstrates deep local regulatory knowledge — a differentiated skill that non-Dubai-based PropTech candidates cannot replicate. Strong SEO potential on GitHub for Dubai real estate searches.

### 6. Property Operations Cost Tracker
**Stack:** Supabase (PostgreSQL), vanilla JavaScript, HTML/CSS
**Rationale:** Extends demonstrated Supabase experience from `property-maintenance-hub`. Shows full-stack capability with a practical, recurring operational use case. Cost tracking across multiple units is a real problem every property management company has.

### 7. WhatsApp Guest Communication Bot
**Stack:** Node.js, Twilio WhatsApp API or WhatsApp Business API, webhook handling
**Rationale:** WhatsApp is the dominant guest communication channel in the UAE and across short-term rental markets globally. An automated bot for check-in instructions, FAQ responses, or maintenance requests demonstrates automation skills in the exact tools operators actually use. High practical value = high visibility.

### 8. Airbnb Pricing Optimizer
**Stack:** Python, pandas, public Airbnb data (InsideAirbnb.com datasets), matplotlib or seaborn
**Rationale:** Pricing optimization is the highest-leverage variable in STR revenue management. Using publicly available Airbnb listing data to build a pricing model demonstrates data analysis skills, PropTech domain knowledge, and quantitative thinking — the combination that distinguishes a technologist-operator from a pure operator.

---
---

# ROADMAP_90_DAYS.md

## Phase 1: Foundation (Days 1–30) — "Build the Base"

The goal of Phase 1 is to eliminate all critical deficiencies identified in the audit. By Day 30, every existing repo should be clean and professional, the profile README should be live, and the visual identity should be established. No new projects are needed yet — fix what exists first.

---

### Week 1 (Days 1–7): Profile and Repository Hygiene

**Day 1–2: Create the GitHub Profile README**
- Priority: P1
- Estimated time: 3–4 hours
- Task: Create the `princechakusa/princechakusa` repository (must be public, same name as username). Add a `README.md` that includes: a one-paragraph bio, current role and location, key stats (350+ units, response time achievement), tech stack icons or badges, links to portfolio site and LinkedIn, and a "Currently building" or "Currently learning" section.
- Success metric: Profile README renders on `github.com/princechakusa` without any additional navigation

**Day 3: Update GitHub Bio and Profile Fields**
- Priority: P1
- Estimated time: 20 minutes
- Task: Go to Settings > Profile. Set bio to the recommended text. Add company (current employer or "Independent PropTech Builder"), location (Dubai, UAE), website (portfolio URL), and pronouns if desired.
- Success metric: Bio field populated with recommended text; location set to Dubai, UAE

**Day 4–5: Rename All Repositories**
- Priority: P1
- Estimated time: 1 hour total
- Task: Rename `PaMarket` to `pamarket`, `Guestcare` to `guestcare-platform`, `ggs-v3-platform` to `vacationhub-operations`, `fixhub-backend` to `property-maintenance-hub`. Go to each repo > Settings > Repository name. Warning: renaming breaks existing links — check for any hardcoded repo URLs in READMEs or external sites after renaming.
- Success metric: All five repos use kebab-case lowercase naming

**Day 6–7: Add Descriptions to All Repositories**
- Priority: P1
- Estimated time: 1 hour total
- Task: For each repo, click the gear icon next to "About" on the repo homepage. Write a one-sentence description (aim for 10–15 words, lead with the problem it solves or the value it provides). Replace `fixhub-backend`'s casual description with a professional one.
- Suggested descriptions:
  - `property-maintenance-hub`: "Property maintenance request and tracking dashboard built with Supabase and vanilla JavaScript"
  - `guestcare-platform`: "Guest experience management system for short-term rental operations"
  - `vacationhub-operations`: "Operations analytics platform for vacation rental portfolio management"
  - `pamarket`: "Online marketplace connecting buyers and sellers in Zimbabwe"
  - `princechakusa.github.io`: "Personal portfolio and professional website"
- Success metric: All repos show a description in the About section

---

### Week 2 (Days 8–14): Topics, Pinning, and README Upgrades

**Days 8–10: Add GitHub Topics to All Repositories**
- Priority: P1
- Estimated time: 30 minutes total
- Task: For each repo, click the gear icon next to "About." Add the topics listed in the Portfolio Guide's "Required GitHub Topics" section. Use the exact topic strings — GitHub auto-links these to topic pages.
- Success metric: Every repo shows at least 5 topic tags on its page

**Days 11–12: Configure Pinned Repositories**
- Priority: P1
- Estimated time: 15 minutes
- Task: On your profile page, click "Customize your pins." Select repos in the recommended order: portfolio site, property-maintenance-hub, guestcare-platform, vacationhub-operations, pamarket. Confirm the display order reflects priority.
- Success metric: Profile page shows exactly 5 pinned repos in the specified order

**Days 13–14: Write READMEs for the Two Repos Missing Them**
- Priority: P1
- Estimated time: 2–3 hours per README
- Task: Both `guestcare-platform` and `vacationhub-operations` lack READMEs (or have minimal ones). Each README should include: project title, one-paragraph description, problem it solves, tech stack, setup/installation instructions, screenshots or a demo GIF, and current status. A README without screenshots is invisible to non-technical viewers.
- Success metric: Both repos have a README that would make sense to someone seeing the project for the first time

---

### Week 3 (Days 15–21): Visual Identity

**Days 15–17: Create Banner Image**
- Priority: P2
- Estimated time: 2–3 hours
- Task: Use Figma, Canva, or Adobe Express to create the 1500x500px banner following the design concept in the Portfolio Guide. Export as PNG at 2x resolution (3000x1000px) to remain crisp on retina screens. Upload to the profile README as the first element using a standard Markdown image tag.
- Success metric: Banner displays on profile README without pixelation at both standard and high-density displays

**Days 18–19: Confirm and Update Profile Photo**
- Priority: P2
- Estimated time: 1 hour (includes any light editing)
- Task: Upload or confirm the professional headshot following the style recommendations. Use the same photo on GitHub and LinkedIn for consistent cross-platform identity recognition. If retaking is needed, use the style guide in the Portfolio Guide.
- Success metric: Profile photo is a clean headshot where the face fills 70–80% of the circular crop

**Days 20–21: Upgrade `princechakusa.github.io` README**
- Priority: P2
- Estimated time: 1–2 hours
- Task: The portfolio website repo README should function as a project card for the site itself. Add: a screenshot of the homepage, deployment badge (GitHub Pages status), tech used, link to live site, and a brief note about what the site demonstrates.
- Success metric: `princechakusa.github.io` repo README contains a screenshot and live site link

---

### Week 4 (Days 22–30): Community Foundation and Consistency Pass

**Days 22–25: Follow Relevant Accounts**
- Priority: P2
- Estimated time: 1–2 hours spread across days
- Task: Follow 50–75 accounts in the following categories: PropTech developers and founders, hospitality technology builders (search GitHub topics: `proptech`, `short-term-rental`, `property-management`), full-stack developers building operational tools, and developers in the UAE and Africa tech communities. Quality over quantity — follow accounts that post real code, not just forks.
- Success metric: Following count reaches at least 50 by Day 30

**Days 26–27: Consistency Audit**
- Priority: P2
- Estimated time: 1 hour
- Task: Cross-check that the stat "350+ units" appears consistently on GitHub bio, portfolio website, LinkedIn, and any other profiles. Confirm no profile says "400+" anywhere. Ensure job titles and dates are consistent across platforms.
- Success metric: Single consistent figure used across all platforms

**Days 28–30: Contribution Graph**
- Priority: P3
- Estimated time: Ongoing
- Task: Make at least one real commit per day during Days 28–30. These can be README improvements, topic additions via API, or small code fixes. The goal is to break the visual "no activity" gap on the contribution graph, which signals to profile visitors that the account is active.
- Success metric: Contribution graph shows activity in all three remaining days of the month

---

## Phase 2: Content (Days 31–60) — "Fill the Portfolio"

The goal of Phase 2 is to add at least two new projects that demonstrate quantified technical work, and to deepen the documentation quality across existing repos.

---

### Week 5 (Days 31–37): Build Project 1

**Days 31–37: Build Maintenance Response Time Analytics Dashboard**
- Priority: P1
- Estimated time: 8–12 hours across the week
- Task: Build the project described in "Suggested New Projects" item 3. This project is highest priority for Phase 2 because it directly substantiates an existing resume claim (improved maintenance response times). Structure it as: data input layer (CSV or manual entry), calculation layer (Python pandas or plain JS), visualization layer (Chart.js bar and trend charts), and a brief written methodology section in the README explaining the metrics used.
- Week breakdown:
  - Days 31–32: Set up repo, write full README before writing any code (README-driven development forces clarity)
  - Days 33–35: Build core calculation and visualization logic
  - Days 36–37: Polish, add screenshots, deploy if applicable
- Success metric: Public repo with working demo, full README, at least 3 screenshots, and applied topics

---

### Week 6 (Days 38–44): Build Project 2

**Days 38–44: Build STR Revenue Calculator and Forecasting Tool**
- Priority: P1
- Estimated time: 8–12 hours across the week
- Task: Build the project described in "Suggested New Projects" item 2. Focus on the user-facing calculation interface — inputs for nightly rate, occupancy rate, number of units, operating costs, and seasonality adjustments. Output a monthly/annual revenue forecast with a simple chart. Host on GitHub Pages so it runs in the browser without any backend.
- Week breakdown:
  - Days 38–39: Write README, sketch the input/output interface, set up repo
  - Days 40–42: Build calculator logic and Chart.js visualization
  - Days 43–44: Test edge cases, polish UI, deploy to GitHub Pages
- Success metric: Live GitHub Pages deployment linked from README, working calculator with chart output

---

### Week 7 (Days 45–51): Deepen Existing Repo Documentation

**Days 45–48: Add Screenshots and Demo GIFs to All Repos**
- Priority: P2
- Estimated time: 3–4 hours total
- Task: Every repo should have at least one screenshot or screen recording in its README. For tools with UIs, use a GIF (record with Loom, GIPHY Capture, or ScreenToGIF). For backend projects, show the API response or a diagram. A repo with no visuals reads as incomplete to non-technical reviewers.
- Success metric: All five existing repos show visual media in their READMEs

**Days 49–51: Write Challenges and Decisions Sections in READMEs**
- Priority: P2
- Estimated time: 2–3 hours total
- Task: Add a short "Technical Decisions" or "What I Learned" section to at least three READMEs. This is the most underused README section and the one that most impresses senior engineers and hiring managers. Describe one architectural decision per project — why you chose Supabase over another database, why you structured the data model a certain way, what you would do differently.
- Success metric: At least three repos have a "Technical Decisions" or "Lessons Learned" section

---

### Week 8 (Days 52–60): Begin Project 3 and Community Engagement

**Days 52–57: Start UAE Holiday Home Compliance Checklist App**
- Priority: P2
- Estimated time: 6–8 hours
- Task: This is a domain expertise showcase. Start building the project described in "Suggested New Projects" item 5. Even a 60% complete version with a good README demonstrates specialized local knowledge that competing candidates lack. Focus on getting the core checklist functionality working with localStorage persistence.
- Success metric: Repo created, README written, core checklist functionality working (completion by Day 60 not required)

**Days 58–60: Community Engagement Sprint**
- Priority: P2
- Estimated time: 2–3 hours across three days
- Task: Star 20–30 repositories in your domain (PropTech, hospitality tech, property management tools). Open one GitHub Discussion or leave one substantive comment on an open issue in a public repo you use or admire. These small interactions often result in follow-backs and build the profile activity signal.
- Success metric: At least 20 repos starred; one public interaction (comment or discussion post) visible on profile

---

## Phase 3: Visibility (Days 61–90) — "Get Discovered"

The goal of Phase 3 is to take the now-clean, content-rich profile and distribute it to the people who should see it — without spamming or performing inauthentically.

---

### Week 9 (Days 61–67): LinkedIn and Cross-Platform Syndication

**Days 61–63: Update LinkedIn Profile with GitHub Links**
- Priority: P1
- Estimated time: 1–2 hours
- Task: Add GitHub profile URL to LinkedIn contact section. Add `property-maintenance-hub` and `princechakusa.github.io` as Featured items on LinkedIn. Write a LinkedIn post announcing one of the new projects built in Phase 2 — describe the problem it solves, not just the tech stack. Tag relevant PropTech communities.
- Success metric: GitHub URL visible on LinkedIn; one project post published with at least one project linked

**Days 64–67: Write One Technical Post or GitHub Discussion**
- Priority: P2
- Estimated time: 3–4 hours
- Task: Write a short (500–800 word) technical post — either as a GitHub Gist, a DEV.to article, or a LinkedIn article — about a specific technical decision from one of your projects. Topic ideas: "Why I chose Supabase for a property management tool instead of Firebase," or "What I learned building a maintenance dashboard for 350 units." This type of content drives profile traffic organically.
- Success metric: One published technical post with a link back to the relevant GitHub repo

---

### Week 10 (Days 68–74): SEO and Discoverability Optimization

**Days 68–70: Optimize Repository Descriptions for Search**
- Priority: P2
- Estimated time: 1 hour
- Task: Review all repo descriptions for keyword density. GitHub search indexes repo names, descriptions, and README content. Ensure that phrases like "property management," "short-term rental," "Dubai," "Supabase," and "hospitality" appear naturally in descriptions and README first paragraphs. Do not keyword-stuff — one natural occurrence per keyword per document is sufficient.
- Success metric: Each repo description and README first paragraph contains at least two searchable domain keywords

**Days 71–74: Complete UAE Compliance App and Deploy**
- Priority: P2
- Estimated time: 4–6 hours
- Task: Finish the UAE Holiday Home Compliance Checklist App started in Week 8. Deploy to GitHub Pages. Add to pinned repos if it is stronger than one of the current five. Submit the project to any relevant PropTech or UAE tech communities or forums as a free resource.
- Success metric: App deployed to GitHub Pages, repo pinned or linked from profile README

---

### Week 11 (Days 75–81): Profile Review and Gap Fill

**Days 75–77: Full Profile Review**
- Priority: P2
- Estimated time: 2 hours
- Task: View your own profile as a logged-out user (open an incognito browser window). Assess: Does the profile clearly communicate who you are and what you build within 10 seconds? Are all pinned repos showing correct descriptions and topics? Is the README rendering correctly? Does the contribution graph show consistent activity? Fix any gaps identified.
- Success metric: Profile makes immediate sense to a cold visitor within 10 seconds; no broken images or empty sections

**Days 78–81: Start Fourth Project (Optional but High-Value)**
- Priority: P3
- Estimated time: 6–10 hours
- Task: Begin the Property Management SOP Generator (Python, described in "Suggested New Projects" item 1). This project is particularly strong because it demonstrates the ability to codify operational knowledge programmatically — a skill explicitly valued in PropTech product roles. Even a README-only start with a working minimal prototype is sufficient for Phase 3.
- Success metric: Repo created with README; at least one working generation script committed

---

### Week 12 (Days 82–90): Finalize and Measure

**Days 82–85: Final README Pass**
- Priority: P2
- Estimated time: 3–4 hours
- Task: Do a final proofread of all READMEs. Check: consistent tense (present for active projects, past for completed ones), no placeholder text remaining, all links work, all screenshots load. Pay special attention to the profile README — this is the document with the highest view count.
- Success metric: Zero broken links or placeholder text across all repos

**Days 86–88: Engage with GitHub PropTech Community**
- Priority: P3
- Estimated time: 2–3 hours
- Task: Find and contribute to at least one open-source property management or hospitality technology project — even a documentation fix counts. A contribution to someone else's repo shows collaborative capability and often results in profile visits from the repo maintainer's network.
- Success metric: At least one contribution (PR, issue, or discussion) visible on contribution graph from an external repo

**Days 89–90: Measure and Plan Next 90 Days**
- Priority: P2
- Estimated time: 2 hours
- Task: Pull the following metrics and record them: follower count, total stars across repos, monthly profile views (available in GitHub Insights), top-referred repos. Compare against Day 0 baselines. Plan the next 90 days based on which projects got the most traction.
- Success metric: All metrics documented; 90-day-2 plan drafted

---

## 90-Day Success Metrics

| Metric | Day 0 Baseline | Day 30 Target | Day 60 Target | Day 90 Target |
|---|---|---|---|---|
| Profile README live | No | Yes | Yes | Yes |
| Repos with descriptions | ~3 of 5 | 5 of 5 | 5+ of 5+ | All repos |
| Repos with topics | 0 of 5 | 5 of 5 | All repos | All repos |
| Repos with screenshots in README | Unknown | 5 of 5 | All repos | All repos |
| Pinned repos configured | No | Yes (5 pinned) | Yes | Yes |
| Followers | 0 | 5–10 | 15–30 | 30–60 |
| Following | 0 | 50 | 75 | 100 |
| Total repos with full READMEs | ~1 | 5 | 7 | 8+ |
| New projects added | 0 | 0 | 2 | 3–4 |
| GitHub Pages deployments | 1 | 1 | 2 | 3 |
| Contribution graph activity | Sparse | Active in Phase 1 weeks | Consistent | No gaps in 90-day window |
| Technical posts published | 0 | 0 | 0–1 | 1–2 |
| Profile bio updated | No | Yes | Yes | Yes |
| Cross-platform consistency | Inconsistent | Resolved | Maintained | Maintained |

### What "Done" Looks Like After 90 Days

A recruiter or PropTech hiring manager who lands on `github.com/princechakusa` should immediately see:

1. A professional banner and headshot that match the portfolio website
2. A profile README that communicates scope, domain expertise, geography, and technical capability in under 30 seconds
3. Five pinned repos that each solve a real operational problem, with screenshots and full documentation
4. A contribution graph showing consistent engagement over the past 90 days
5. A follower count above zero with outbound following that signals genuine community participation
6. At least two new projects that did not exist before this roadmap — projects that only someone with Prince's specific operational background and Dubai-market knowledge could have built

The goal is not to look like a prolific open-source contributor. The goal is to look like an operations leader who builds purposeful, well-documented technology tools to solve the specific problems he encounters in his domain. That is a rare and commercially valuable profile.
