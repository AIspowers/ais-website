# AI Superpowers — Arabic Translation Brief

This document contains every visible English string from the four public pages of the AI Superpowers website (`index.html`, `packages.html`, `case-studies.html`, `ai-dashboard.html`), organised by page and section. Translate each **EN** line into the empty **AR** slot below it.

**How to use this file:**
- Work top to bottom. Each entry has a stable key (e.g. `index.hero.h1`) — leave the key alone; the dev team uses it to map your Arabic back into the markup.
- Keep `<em>`, `<strong>`, and `<br>` tags exactly where they sit in the English source. They carry visual emphasis (orange italics, bold, forced line breaks) — if they move, the design breaks.
- The tone is direct, confident, advisory — a senior consultant speaking to a Gulf/Omani business audience. Aim for modern, clear Arabic rather than heavy classical MSA. Short sentences over long ones.
- Keep the fishing-boat analogy (`method-tagline`) intact — it's a deliberate brand metaphor.
- "aisuperpowers" wordmark in the logo stays English (brand mark).

## Already translated (no action needed)

The following items are already rendered in Arabic inside `index-ar.html` and the other `-ar.html` files. You do **not** need to retranslate them:

- Nav links: Why AI Fails, How We Work, What We Build, The Team, Service Offerings
- Nav CTA: See If We're the Right Fit
- Mobile menu (same links as above)
- Footer city line: "Warsaw · Muscat" → "وارسو · مسقط"
- "Back to top" / "Open menu" aria-labels

## Style notes for translator

- **Tags:** Preserve `<em>`, `<strong>`, `<br>` exactly as in the English source line.
- **Numbers & currency:** Retain figures as-is (`$715K+`, `90 days`, `5%`, `32+`, `$2.4M`, `4-in-1`, `10x`, `50–500`). Translate only the surrounding label. Where "days/weeks/hours" appear inline with numerals, translate the word but keep the numeral.
- **Brand & product names:** `AI Superpowers` stays English (brand). Product/vendor names (`Salesforce`, `HubSpot`, `SAP`, `Slack`, `Microsoft Teams`, `BigQuery`, `Power BI`, `Tableau`, `Revolut`, etc.) stay English.
- **Personal names:** Keep all personal names in Latin script exactly as written in the English source (e.g. `Aws Naser`, `Daniel`, `Khalid Al Husaini`, `Melikenur Işık`). Do NOT transliterate to Arabic.
- **"AI":** Use "الذكاء الاصطناعي" on first mention per section; `AI` alone is acceptable thereafter if it reads more naturally.
- **City names:** Warsaw = وارسو, Muscat = مسقط, Oman = عُمان, EMEA stays as-is.
- **Job titles with "·" separator** (e.g. `Chairman & CEO · Labbik Telecom · Oman`): keep the middle dot `·` as a separator between Arabic segments.
- **Quoted UI snippets** (e.g. the demo query `"What happened to Q3 revenue vs. forecast?"`): translate the quoted text — it's what an Omani user would actually type.
- **Tone:** direct, confident, advisory. Not overly formal MSA. Think "trusted senior consultant", not "government circular".

---

## index.html

### Page meta

#### `index.meta.title`
**EN:** AI Superpowers | The Only AI Firm You'll Need
**AR:** _[translator to fill]_

### Hero

#### `index.hero.h1`
**EN:** We're the only AI firm<br>you'll need to <em>hire.</em>
**AR:** _[translator to fill]_

#### `index.hero.sub`
**EN:** Most firms leave you <strong>dependent.</strong> We leave you <strong>capable,</strong> architecting AI systems your people run, your workflows follow, and your business owns. <strong>Permanently.</strong>
**AR:** _[translator to fill]_

#### `index.hero.cta`
**EN:** See If We're the Right Fit. Book a Call
**AR:** _[translator to fill]_

#### `index.hero.stat1.number`
**EN:** $715K+
**AR:** _[translator to fill — keep figure, translate context if needed]_

#### `index.hero.stat1.label`
**EN:** Savings exposed across client engagements
**AR:** _[translator to fill]_

#### `index.hero.stat2.number`
**EN:** 90 days
**AR:** _[translator to fill — keep 90, translate "days"]_

#### `index.hero.stat2.label`
**EN:** From X-Ray to first working system
**AR:** _[translator to fill]_

#### `index.hero.stat3.number`
**EN:** 5%
**AR:** _[translator to fill — keep figure]_

#### `index.hero.stat3.label`
**EN:** of executives trust their data. We make sure you're one of them. (HFS Research)
**AR:** _[translator to fill]_

### Problem ("mirror") section

#### `index.problem.label`
**EN:** Sound familiar?
**AR:** _[translator to fill]_

#### `index.problem.h2`
**EN:** You invested in AI.<br>Your teams chose Excel.
**AR:** _[translator to fill]_

#### `index.problem.text`
**EN:** You spent the budget. Signed the contracts. Sat through the demos. And this morning, your best people are still copying data into spreadsheets, your managers are still waiting three days for a report, and your CFO is asking what any of it was worth.
**AR:** _[translator to fill]_

#### `index.problem.conclusion`
**EN:** AI didn't fail you. You were sold a showcase instead of a system.
**AR:** _[translator to fill]_

### Method section

#### `index.method.label`
**EN:** How We Work
**AR:** _[translator to fill]_

#### `index.method.h2`
**EN:** Three steps.<br>That's it.
**AR:** _[translator to fill]_

#### `index.method.tagline`
**EN:** "We don't give you fish. We build you a fishing boat and teach your crew to sail it."
**AR:** _[translator to fill — keep the fishing-boat metaphor]_

#### `index.method.step1.title`
**EN:** X-Ray
**AR:** _[translator to fill]_

#### `index.method.step1.body`
**EN:** We sit inside your workflows, not a boardroom. We assess your data, map where things break, and find the 3-5 places where AI saves real money. Bad data is usually why AI fails. We find that before it costs you anything.
**AR:** _[translator to fill]_

#### `index.method.step1.tag`
**EN:** Discovery & Architecture
**AR:** _[translator to fill]_

#### `index.method.step2.title`
**EN:** Build & Deploy
**AR:** _[translator to fill]_

#### `index.method.step2.body`
**EN:** We build AI systems around how your business actually runs. Connected data. Automated workflows. Deployed on your infrastructure. Owned by you, not us.
**AR:** _[translator to fill]_

#### `index.method.step2.tag`
**EN:** Implementation & Deployment
**AR:** _[translator to fill]_

#### `index.method.step3.title`
**EN:** Optimize & Exit
**AR:** _[translator to fill]_

#### `index.method.step3.body`
**EN:** We train your people to run it, improve it, and build on it without us. Real capability transfer, not a two-hour workshop. Then we step back. Permanently.
**AR:** _[translator to fill]_

#### `index.method.step3.tag`
**EN:** Capability Transfer & Handoff
**AR:** _[translator to fill]_

### Solutions section

#### `index.solutions.label`
**EN:** What We Build
**AR:** _[translator to fill]_

#### `index.solutions.h2`
**EN:** We don't just advise. We build.
**AR:** _[translator to fill]_

#### `index.solutions.subtitle`
**EN:** Real systems, deployed inside real businesses, running without us. Here's what that looks like.
**AR:** _[translator to fill]_

#### `index.solutions.dashboard.label`
**EN:** AI Dashboard
**AR:** _[translator to fill]_

#### `index.solutions.dashboard.title`
**EN:** Your Entire Company on <em>One Screen You Can Talk To</em>
**AR:** _[translator to fill]_

#### `index.solutions.dashboard.desc`
**EN:** Your managers spend days pulling data from CRMs, files, and emails. We build the screen that gives them the answer before the meeting starts.
**AR:** _[translator to fill]_

#### `index.solutions.dashboard.link`
**EN:** How it works
**AR:** _[translator to fill]_

#### `index.solutions.knowledge.label`
**EN:** Knowledge Engine
**AR:** _[translator to fill]_

#### `index.solutions.knowledge.title`
**EN:** Years of Company Policy, <em>One Click</em> Away
**AR:** _[translator to fill]_

#### `index.solutions.knowledge.desc`
**EN:** Your company's knowledge stops living in someone's head or buried in folders nobody opens. New hires onboard in days, not months.
**AR:** _[translator to fill]_

#### `index.solutions.knowledge.link`
**EN:** See the case study
**AR:** _[translator to fill]_

#### `index.solutions.cta`
**EN:** See All Case Studies
**AR:** _[translator to fill]_

### Ownership / Data sovereignty section

#### `index.ownership.h2`
**EN:** Your data never leaves your walls.<br>Neither do the systems we build.
**AR:** _[translator to fill]_

#### `index.ownership.desc`
**EN:** Every system we architect runs on your infrastructure. Your servers, your cloud, your rules. When we're done, you own the code, the data, and the capability. No black boxes. No lock-in.
**AR:** _[translator to fill]_

#### `index.ownership.card1.title`
**EN:** <strong>Your infrastructure.</strong>
**AR:** _[translator to fill]_

#### `index.ownership.card1.desc`
**EN:** Your servers or your cloud. Never ours.
**AR:** _[translator to fill]_

#### `index.ownership.card2.title`
**EN:** <strong>Your data.</strong>
**AR:** _[translator to fill]_

#### `index.ownership.card2.desc`
**EN:** Never touches a third-party API. Never leaves your environment.
**AR:** _[translator to fill]_

#### `index.ownership.card3.title`
**EN:** <strong>Your code.</strong>
**AR:** _[translator to fill]_

#### `index.ownership.card3.desc`
**EN:** Inspect it, modify it, migrate it. Anytime.
**AR:** _[translator to fill]_

#### `index.ownership.card4.title`
**EN:** <strong>Your team.</strong>
**AR:** _[translator to fill]_

#### `index.ownership.card4.desc`
**EN:** Trained to run, improve, and build on it. Without us.
**AR:** _[translator to fill]_

#### `index.ownership.cta`
**EN:** Let's talk about your infrastructure
**AR:** _[translator to fill]_

### Testimonials section

#### `index.testimonials.label`
**EN:** What Clients Say
**AR:** _[translator to fill]_

#### `index.testimonials.h2`
**EN:** Real feedback.<br>Real engagements.
**AR:** _[translator to fill]_

#### `index.testimonials.t1.quote`
**EN:** We partnered with AIsuperpowers because we saw a team that could actually deliver AI to government, not just talk about it. Working systems. That's exactly what we're delivering together.
**AR:** _[translator to fill]_

#### `index.testimonials.t1.name`
**EN:** Khalid Al Husaini
**AR:** _[translator to fill — Arabic form: خالد الحسيني — confirm with Marta]_

#### `index.testimonials.t1.role`
**EN:** Chairman & CEO · Labbik Telecom · Oman
**AR:** _[translator to fill]_

#### `index.testimonials.t1.alt`
**EN:** Khalid Al Husaini
**AR:** _[translator to fill — image alt text]_

#### `index.testimonials.t2.quote`
**EN:** From idea to working prototype in weeks. They understood the business logic immediately, built something real, and gave us a system we could iterate on ourselves.
**AR:** _[translator to fill]_

#### `index.testimonials.t2.name`
**EN:** Karol Sadaj
**AR:** _[translator to fill — transliterate: كارول ساداي]_

#### `index.testimonials.t2.role`
**EN:** Fintech Executive · AIP Seed Board · ex-Revolut
**AR:** _[translator to fill]_

#### `index.testimonials.t2.alt`
**EN:** Karol Sadaj
**AR:** _[translator to fill]_

#### `index.testimonials.t3.quote`
**EN:** They didn't just install tools. They trained our engineers to actually work with them. Our entire team went from confused about AI to using it daily. That's what made the difference.
**AR:** _[translator to fill]_

#### `index.testimonials.t3.name`
**EN:** Piotr Urbanski
**AR:** _[translator to fill]_

#### `index.testimonials.t3.role`
**EN:** Founder & CEO · Highway · Engineering
**AR:** _[translator to fill]_

#### `index.testimonials.t3.alt`
**EN:** Highway
**AR:** _[translator to fill — image alt, company name]_

#### `index.testimonials.t4.quote`
**EN:** Working with AIsuperpowers helped me build an AI strategy I could actually execute, not a 50-page report, but a real roadmap with clear priorities that got buy-in from the board.
**AR:** _[translator to fill]_

#### `index.testimonials.t4.name`
**EN:** Piotr Nowak
**AR:** _[translator to fill]_

#### `index.testimonials.t4.role`
**EN:** Head of Risk · Raiffeisen Bank International
**AR:** _[translator to fill]_

#### `index.testimonials.t4.alt`
**EN:** Raiffeisen Bank
**AR:** _[translator to fill]_

#### `index.testimonials.t5.quote`
**EN:** Our leadership team now makes confident AI decisions. Before, every conversation about AI ended in confusion. Now we have a clear framework and we're actually executing on it.
**AR:** _[translator to fill]_

#### `index.testimonials.t5.name`
**EN:** Piotr Kowynia
**AR:** _[translator to fill]_

#### `index.testimonials.t5.role`
**EN:** President & CEO · Nest Bank S.A.
**AR:** _[translator to fill]_

#### `index.testimonials.t5.alt`
**EN:** Piotr Kowynia
**AR:** _[translator to fill]_

#### `index.testimonials.t6.quote`
**EN:** They understood how business works here in Oman. We went from running everything manually to having automated operations that actually made us faster. ROI was obvious within weeks.
**AR:** _[translator to fill]_

#### `index.testimonials.t6.name`
**EN:** Pouria Fardpour
**AR:** _[translator to fill]_

#### `index.testimonials.t6.role`
**EN:** Founder · Sultan Lands · Real Estate · Oman
**AR:** _[translator to fill]_

#### `index.testimonials.t6.alt`
**EN:** Pouria Fardpour
**AR:** _[translator to fill]_

### Team section

#### `index.team.label`
**EN:** The Team
**AR:** _[translator to fill]_

#### `index.team.h2`
**EN:** You won't get a junior team. You'll get us.
**AR:** _[translator to fill]_

#### `index.team.subtitle`
**EN:** We're four people who've done this across AdTech, finance, government, telecom, and manufacturing, across three continents. Every client works directly with the people who design, build, and train. No account managers. No handoffs.
**AR:** _[translator to fill]_

#### `index.team.aws.name`
**EN:** Aws Naser
**AR:** _[translator to fill — Arabic: أوس ناصر]_

#### `index.team.aws.role`
**EN:** Co-Founder & AI Architect
**AR:** _[translator to fill]_

#### `index.team.aws.bio`
**EN:** Designs AI systems executives actually understand, and that their teams actually use.
**AR:** _[translator to fill]_

#### `index.team.aws.alt`
**EN:** Aws Naser
**AR:** _[translator to fill]_

#### `index.team.marta.name`
**EN:** Marta Zalewska
**AR:** _[translator to fill]_

#### `index.team.marta.role`
**EN:** Co-Founder & Change Lead
**AR:** _[translator to fill]_

#### `index.team.marta.bio`
**EN:** The reason your people adopt AI instead of resisting it. Change management is her system.
**AR:** _[translator to fill]_

#### `index.team.marta.alt`
**EN:** Marta Zalewska
**AR:** _[translator to fill]_

#### `index.team.daniel.name`
**EN:** Daniel Pulaski
**AR:** _[translator to fill]_

#### `index.team.daniel.role`
**EN:** Partner & Business Strategy
**AR:** _[translator to fill]_

#### `index.team.daniel.bio`
**EN:** Translates your business pain into a system before the first invoice is signed.
**AR:** _[translator to fill]_

#### `index.team.daniel.alt`
**EN:** Daniel Pulaski
**AR:** _[translator to fill]_

#### `index.team.melikenur.name`
**EN:** Melikenur Işık
**AR:** _[translator to fill]_

#### `index.team.melikenur.role`
**EN:** AI Lead & Data Architect
**AR:** _[translator to fill]_

#### `index.team.melikenur.bio`
**EN:** Builds the data infrastructure that makes everything run. Clean, connected, and yours.
**AR:** _[translator to fill]_

#### `index.team.melikenur.alt`
**EN:** Melikenur Işık
**AR:** _[translator to fill]_

#### `index.team.linkedin`
**EN:** LinkedIn
**AR:** _[translator to fill — appears on each of the 4 team cards, translate once]_

### Final CTA

#### `index.finalcta.h2`
**EN:** Still reading?<br>You already <em>know.</em>
**AR:** _[translator to fill]_

#### `index.finalcta.body`
**EN:** Most AI projects fail because of the wrong partner, not the wrong technology. Let's see if we're the right fit.
**AR:** _[translator to fill]_

#### `index.finalcta.button`
**EN:** See If We're the Right Fit. Book a Call
**AR:** _[translator to fill]_

#### `index.finalcta.note`
**EN:** 30 minutes · No pitch · We come prepared with answers
**AR:** _[translator to fill]_

### Footer

#### `index.footer.tagline`
**EN:** "We build it. We train you. We leave."
**AR:** _[translator to fill]_

---

## packages.html

### Page meta

#### `packages.meta.title`
**EN:** Service Offerings | AI Superpowers | Data Readiness, AI Integration & Ongoing Support
**AR:** _[translator to fill]_

### Hero

#### `packages.hero.h1`
**EN:** Three service offerings.<br>One <em>clear path</em> to AI.
**AR:** _[translator to fill]_

#### `packages.hero.sub`
**EN:** Whether you're just exploring or ready to scale, we meet you where you are and move you forward.
**AR:** _[translator to fill]_

#### `packages.hero.step1`
**EN:** Assess
**AR:** _[translator to fill]_

#### `packages.hero.step2`
**EN:** Integrate
**AR:** _[translator to fill]_

#### `packages.hero.step3`
**EN:** Optimize
**AR:** _[translator to fill]_

### Tier 1 — Data Readiness Assessment

#### `packages.tier1.label`
**EN:** Offering 1
**AR:** _[translator to fill]_

#### `packages.tier1.timeline`
**EN:** 2-Week Engagement
**AR:** _[translator to fill — keep "2"]_

#### `packages.tier1.title`
**EN:** Data Readiness <em>Assessment</em>
**AR:** _[translator to fill]_

#### `packages.tier1.desc`
**EN:** A focused, 2-week audit of your data systems, workflows, and AI readiness. We find out exactly where you stand and give you a clear roadmap to move forward.
**AR:** _[translator to fill]_

#### `packages.tier1.what.h3`
**EN:** What Is This?
**AR:** _[translator to fill]_

#### `packages.tier1.what.body`
**EN:** A comprehensive assessment where we examine your data infrastructure, workflows, and organizational readiness for AI adoption. Think of it as a full health check for your data before you invest in AI tools that may not work with your current setup.
**AR:** _[translator to fill]_

#### `packages.tier1.who.h3`
**EN:** Who Is This For?
**AR:** _[translator to fill]_

#### `packages.tier1.who.item1`
**EN:** Mid-market companies (50-500 employees) running on multiple data systems
**AR:** _[translator to fill]_

#### `packages.tier1.who.item2`
**EN:** Organizations exploring AI but unsure where to start
**AR:** _[translator to fill]_

#### `packages.tier1.who.item3`
**EN:** Companies that have tried AI tools and hit walls
**AR:** _[translator to fill]_

#### `packages.tier1.who.item4`
**EN:** Leadership teams seeking data-backed AI investment decisions
**AR:** _[translator to fill]_

#### `packages.tier1.industry.telecom`
**EN:** Telecom & ISPs
**AR:** _[translator to fill]_

#### `packages.tier1.industry.finance`
**EN:** Financial Services
**AR:** _[translator to fill]_

#### `packages.tier1.industry.b2b`
**EN:** B2B / SaaS
**AR:** _[translator to fill]_

#### `packages.tier1.industry.gov`
**EN:** Government
**AR:** _[translator to fill]_

#### `packages.tier1.week1.label`
**EN:** Week 1
**AR:** _[translator to fill]_

#### `packages.tier1.week1.h3`
**EN:** Discovery & Audit
**AR:** _[translator to fill]_

#### `packages.tier1.week1.intro`
**EN:** We map your entire data landscape. Every system, every workflow, every pain point.
**AR:** _[translator to fill]_

#### `packages.tier1.week1.item1`
**EN:** <strong>Stakeholder interviews</strong>: conversations with 5-8 key team members across departments
**AR:** _[translator to fill]_

#### `packages.tier1.week1.item2`
**EN:** <strong>System inventory</strong>: complete mapping of all data sources, storage, and flow between systems
**AR:** _[translator to fill]_

#### `packages.tier1.week1.item3`
**EN:** <strong>Data quality sampling</strong>: spot checks across critical data sets for completeness, consistency, and accuracy
**AR:** _[translator to fill]_

#### `packages.tier1.week1.item4`
**EN:** <strong>Process documentation</strong>: how data currently moves through your organization
**AR:** _[translator to fill]_

#### `packages.tier1.week2.label`
**EN:** Week 2
**AR:** _[translator to fill]_

#### `packages.tier1.week2.h3`
**EN:** Analysis & Recommendations
**AR:** _[translator to fill]_

#### `packages.tier1.week2.intro`
**EN:** We analyze everything and build your custom AI readiness roadmap.
**AR:** _[translator to fill]_

#### `packages.tier1.week2.item1`
**EN:** <strong>AI readiness scoring</strong>: each system and data source rated on a clear framework
**AR:** _[translator to fill]_

#### `packages.tier1.week2.item2`
**EN:** <strong>Gap analysis</strong>: what needs to be fixed before AI can deliver real value
**AR:** _[translator to fill]_

#### `packages.tier1.week2.item3`
**EN:** <strong>Quick wins identification</strong>: high-impact, low-effort opportunities to start immediately
**AR:** _[translator to fill]_

#### `packages.tier1.week2.item4`
**EN:** <strong>Investment modeling</strong>: expected ROI for recommended AI implementations
**AR:** _[translator to fill]_

#### `packages.tier1.deliverables.label`
**EN:** What You Get
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.h4`
**EN:** Assessment Report
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.lead`
**EN:** 20-30 page comprehensive document covering:
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.item1`
**EN:** Data quality scores per system
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.item2`
**EN:** Integration gap analysis
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.item3`
**EN:** AI readiness heat map
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable1.item4`
**EN:** Risk assessment
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable2.h4`
**EN:** Implementation Roadmap
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable2.lead`
**EN:** Phase-by-phase plan with clear priorities:
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable2.item1`
**EN:** Quick wins (0-3 months)
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable2.item2`
**EN:** Foundation work (3-6 months)
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable2.item3`
**EN:** Advanced AI capabilities (6-12 months)
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable3.h4`
**EN:** Business Case Document
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable3.lead`
**EN:** Board-ready materials including:
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable3.item1`
**EN:** Expected ROI calculations
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable3.item2`
**EN:** Resource requirements
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable3.item3`
**EN:** Risk mitigation strategies
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable4.h4`
**EN:** 60-Minute Presentation
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable4.lead`
**EN:** Live walkthrough with your leadership:
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable4.item1`
**EN:** Key findings and recommendations
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable4.item2`
**EN:** Q&A with our team
**AR:** _[translator to fill]_

#### `packages.tier1.deliverable4.item3`
**EN:** Decision framework for next steps
**AR:** _[translator to fill]_

#### `packages.tier1.dont.h3`
**EN:** What We Don't Do in This Engagement
**AR:** _[translator to fill]_

#### `packages.tier1.dont.intro`
**EN:** Transparency matters. Here's what's outside the scope of the assessment:
**AR:** _[translator to fill]_

#### `packages.tier1.dont.item1`
**EN:** We don't build anything. This is assessment only
**AR:** _[translator to fill]_

#### `packages.tier1.dont.item2`
**EN:** We don't access sensitive customer or employee data
**AR:** _[translator to fill]_

#### `packages.tier1.dont.item3`
**EN:** We don't require changes to your current systems
**AR:** _[translator to fill]_

#### `packages.tier1.dont.item4`
**EN:** We don't lock you into a long-term contract
**AR:** _[translator to fill]_

#### `packages.tier1.nextstep.body`
**EN:** Ready to go deeper? The Assessment naturally leads into <em>AI Integration</em>, where we build what the report recommends.
**AR:** _[translator to fill]_

#### `packages.tier1.nextstep.link`
**EN:** See Offering 2
**AR:** _[translator to fill]_

### Tier 2 — AI Integration & Deployment

#### `packages.tier2.label`
**EN:** Offering 2
**AR:** _[translator to fill]_

#### `packages.tier2.timeline`
**EN:** 3-6 Month Engagement
**AR:** _[translator to fill]_

#### `packages.tier2.title`
**EN:** AI Integration <em>& Deployment</em>
**AR:** _[translator to fill]_

#### `packages.tier2.desc`
**EN:** Full-service AI implementation. We take your data from messy to clean, and from clean to AI-powered without replacing your existing systems.
**AR:** _[translator to fill]_

#### `packages.tier2.what.h3`
**EN:** What Is This?
**AR:** _[translator to fill]_

#### `packages.tier2.what.body`
**EN:** This is where we roll up our sleeves. We clean your data, build the AI systems, integrate them with your existing tools, and train your team to use everything. By the end, you have live, working AI that delivers measurable results.
**AR:** _[translator to fill]_

#### `packages.tier2.who.h3`
**EN:** Who Is This For?
**AR:** _[translator to fill]_

#### `packages.tier2.who.item1`
**EN:** Companies that completed the Data Readiness Assessment
**AR:** _[translator to fill]_

#### `packages.tier2.who.item2`
**EN:** Organizations with executive buy-in for AI investment
**AR:** _[translator to fill]_

#### `packages.tier2.who.item3`
**EN:** Teams ready to implement within 3-6 months
**AR:** _[translator to fill]_

#### `packages.tier2.who.item4`
**EN:** Businesses that want AI without replacing existing systems
**AR:** _[translator to fill]_

#### `packages.tier2.industry.reporting`
**EN:** Automated Reporting
**AR:** _[translator to fill]_

#### `packages.tier2.industry.predictive`
**EN:** Predictive Analytics
**AR:** _[translator to fill]_

#### `packages.tier2.industry.search`
**EN:** Document Search
**AR:** _[translator to fill]_

#### `packages.tier2.industry.automation`
**EN:** Process Automation
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.label`
**EN:** Phase 1<br>Weeks 1-4
**AR:** _[translator to fill — keep numerals, translate "Phase" and "Weeks"]_

#### `packages.tier2.phase1.h3`
**EN:** Foundation
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.intro`
**EN:** We clean and structure your data, build the integration layer, and establish the architecture everything else runs on.
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.item1`
**EN:** <strong>Data cleaning & normalization</strong>: fixing inconsistencies, filling gaps, standardizing formats
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.item2`
**EN:** <strong>Integration layer</strong>: connecting your existing systems (CRM, ERP, spreadsheets, databases) into a unified data pipeline
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.item3`
**EN:** <strong>Architecture design</strong>: building the technical blueprint for your AI systems
**AR:** _[translator to fill]_

#### `packages.tier2.phase1.item4`
**EN:** <strong>Security & compliance</strong>: ensuring all data handling meets your regulatory requirements
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.label`
**EN:** Phase 2<br>Weeks 5-10
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.h3`
**EN:** AI Development & Deployment
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.intro`
**EN:** We build, test, and deploy the AI solutions identified in your roadmap, then train your team to use them confidently.
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.item1`
**EN:** <strong>AI solution development</strong>: building the dashboards, automations, RAG systems, or whatever your roadmap prioritizes
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.item2`
**EN:** <strong>Testing & validation</strong>: rigorous testing with real data before going live
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.item3`
**EN:** <strong>Team training</strong>: hands-on sessions so your people can own the systems
**AR:** _[translator to fill]_

#### `packages.tier2.phase2.item4`
**EN:** <strong>Go-live support</strong>: we're there when you launch, handling any issues in real-time
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.label`
**EN:** Phase 3<br>Weeks 11-24
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.h3`
**EN:** Optimization & Scaling
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.intro`
**EN:** We refine what's live, expand to additional use cases, and ensure your AI systems deliver sustained, measurable ROI.
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.item1`
**EN:** <strong>Performance tuning</strong>: monitoring outputs, refining models, and improving accuracy based on real-world usage
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.item2`
**EN:** <strong>Scaling & expansion</strong>: rolling out AI solutions to additional teams, departments, or workflows
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.item3`
**EN:** <strong>Advanced integrations</strong>: connecting deeper into your tech stack as confidence and data maturity grow
**AR:** _[translator to fill]_

#### `packages.tier2.phase3.item4`
**EN:** <strong>Knowledge transfer</strong>: comprehensive handover so your team operates independently going forward
**AR:** _[translator to fill]_

#### `packages.tier2.deliverables.label`
**EN:** What You Get
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable1.h4`
**EN:** Clean, Unified Data
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable1.body`
**EN:** Your data is cleaned, normalized, and flowing between systems automatically. No more spreadsheet chaos.
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable2.h4`
**EN:** Live AI Systems
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable2.body`
**EN:** Working dashboards, automations, or AI tools, deployed and running in your environment.
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable3.h4`
**EN:** Technical Documentation
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable3.body`
**EN:** Complete documentation of everything built: architecture, integrations, data flows, and maintenance guides.
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable4.h4`
**EN:** Trained Team
**AR:** _[translator to fill]_

#### `packages.tier2.deliverable4.body`
**EN:** Your people know how to use, manage, and troubleshoot the systems we built. You're not dependent on us.
**AR:** _[translator to fill]_

#### `packages.tier2.nextstep.body`
**EN:** Systems live? Keep them running at peak performance with <em>Ongoing Optimization</em>, our monthly retainer.
**AR:** _[translator to fill]_

#### `packages.tier2.nextstep.link`
**EN:** See Offering 3
**AR:** _[translator to fill]_

### Tier 3 — Ongoing Optimization & Support

#### `packages.tier3.label`
**EN:** Offering 3
**AR:** _[translator to fill]_

#### `packages.tier3.timeline`
**EN:** Monthly Retainer
**AR:** _[translator to fill]_

#### `packages.tier3.title`
**EN:** Ongoing Optimization <em>& Support</em>
**AR:** _[translator to fill]_

#### `packages.tier3.desc`
**EN:** Your extended AI team. We keep your systems running, evolving, and delivering more value every month so you can focus on running your business.
**AR:** _[translator to fill]_

#### `packages.tier3.what.h3`
**EN:** What Is This?
**AR:** _[translator to fill]_

#### `packages.tier3.what.body`
**EN:** A monthly retainer that keeps your AI systems at peak performance. We monitor, retrain models, add features, and provide ongoing support. Think of us as your AI department without the overhead of building one in-house.
**AR:** _[translator to fill]_

#### `packages.tier3.who.h3`
**EN:** Who Is This For?
**AR:** _[translator to fill]_

#### `packages.tier3.who.item1`
**EN:** Companies with live AI systems that need continuous care
**AR:** _[translator to fill]_

#### `packages.tier3.who.item2`
**EN:** Teams that want to expand AI capabilities over time
**AR:** _[translator to fill]_

#### `packages.tier3.who.item3`
**EN:** Organizations that need expert support without full-time hires
**AR:** _[translator to fill]_

#### `packages.tier3.who.item4`
**EN:** Businesses where AI is becoming core to operations
**AR:** _[translator to fill]_

#### `packages.tier3.core.h3`
**EN:** Core Services
**AR:** _[translator to fill]_

#### `packages.tier3.core.item1.h4`
**EN:** System Monitoring
**AR:** _[translator to fill]_

#### `packages.tier3.core.item1.body`
**EN:** 24/7 automated monitoring of all AI systems. We catch issues before they impact your business.
**AR:** _[translator to fill]_

#### `packages.tier3.core.item2.h4`
**EN:** Model Retraining
**AR:** _[translator to fill]_

#### `packages.tier3.core.item2.body`
**EN:** AI models degrade over time as data changes. We retrain and tune them to maintain accuracy.
**AR:** _[translator to fill]_

#### `packages.tier3.core.item3.h4`
**EN:** Technical Support
**AR:** _[translator to fill]_

#### `packages.tier3.core.item3.body`
**EN:** Direct access to our engineering team for troubleshooting, questions, and guidance.
**AR:** _[translator to fill]_

#### `packages.tier3.core.item4.h4`
**EN:** Monthly Check-In Call
**AR:** _[translator to fill]_

#### `packages.tier3.core.item4.body`
**EN:** Scheduled review of system performance, usage metrics, and upcoming optimization opportunities.
**AR:** _[translator to fill]_

#### `packages.tier3.addon.h3`
**EN:** Add-On Services
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item1.h4`
**EN:** Feature Development
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item1.body`
**EN:** New dashboards, automations, or AI capabilities added to your existing systems.
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item2.h4`
**EN:** Data Quality Monitoring
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item2.body`
**EN:** Continuous checks on data integrity, completeness, and consistency across all sources.
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item3.h4`
**EN:** Training & Onboarding
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item3.body`
**EN:** Workshops for new team members and refresher sessions as systems evolve.
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item4.h4`
**EN:** Advanced Analytics
**AR:** _[translator to fill]_

#### `packages.tier3.addon.item4.body`
**EN:** Deeper insights, predictive modeling, and custom reporting beyond standard dashboards.
**AR:** _[translator to fill]_

### Final CTA

#### `packages.cta.h2`
**EN:** Not sure which service offering <em>fits?</em>
**AR:** _[translator to fill]_

#### `packages.cta.body`
**EN:** Not sure where you stand? Book a free 30-minute consultation. We'll assess your readiness together and tailor our recommendations to exactly what your business needs.
**AR:** _[translator to fill]_

#### `packages.cta.button`
**EN:** Book a FREE 30-Minute Consultation
**AR:** _[translator to fill]_

#### `packages.cta.note`
**EN:** No pitch. No pressure. Just a conversation about what's possible.
**AR:** _[translator to fill]_

### Footer

#### `packages.footer.tagline`
**EN:** "We fix your data so AI actually works."
**AR:** _[translator to fill]_

---

## case-studies.html

### Page meta

#### `case-studies.meta.title`
**EN:** Case Studies | AI Superpowers
**AR:** _[translator to fill]_

### Page hero

#### `case-studies.hero.back`
**EN:** ← Back to Home
**AR:** _[translator to fill — keep arrow glyph; in RTL it should be →]_

#### `case-studies.hero.h1`
**EN:** Real <span>Results</span> from Real Projects
**AR:** _[translator to fill — the `<span>` is a stylistic wrapper, preserve it around the equivalent Arabic word for "Results"]_

#### `case-studies.hero.sub`
**EN:** See how we've helped organizations transform their data into competitive advantage.
**AR:** _[translator to fill]_

### Case 1 — Higher Education Dashboards

#### `case-studies.hct.badge`
**EN:** Government / Education
**AR:** _[translator to fill]_

#### `case-studies.hct.h3`
**EN:** Executive <span>Strategy Dashboards</span> for Higher Education
**AR:** _[translator to fill]_

#### `case-studies.hct.body`
**EN:** A major higher education institution was drowning in manual reporting. Leadership spent 32+ hours weekly compiling data from multiple sources just to understand performance. We built automated dashboards that pull real-time data from all systems, delivering instant visibility to executives.
**AR:** _[translator to fill]_

#### `case-studies.hct.result1.value`
**EN:** 32+
**AR:** _[keep as-is]_

#### `case-studies.hct.result1.label`
**EN:** Hours/week saved
**AR:** _[translator to fill]_

#### `case-studies.hct.result2.value`
**EN:** Real-time
**AR:** _[translator to fill]_

#### `case-studies.hct.result2.label`
**EN:** Data visibility
**AR:** _[translator to fill]_

#### `case-studies.hct.result3.value`
**EN:** 100%
**AR:** _[keep as-is]_

#### `case-studies.hct.result3.label`
**EN:** Automated reporting
**AR:** _[translator to fill]_

#### `case-studies.hct.result4.value`
**EN:** Instant
**AR:** _[translator to fill]_

#### `case-studies.hct.result4.label`
**EN:** Decision support
**AR:** _[translator to fill]_

#### `case-studies.hct.value.label`
**EN:** Estimated Value
**AR:** _[translator to fill]_

#### `case-studies.hct.value.amount`
**EN:** $715K+
**AR:** _[keep as-is]_

#### `case-studies.hct.value.period`
**EN:** per year in recovered time
**AR:** _[translator to fill]_

### Case 2 — Telecom Reporting

#### `case-studies.telecom.badge`
**EN:** Telecommunications
**AR:** _[translator to fill]_

#### `case-studies.telecom.h3`
**EN:** 4-in-1 <span>Automated Reporting</span> for Telecom Operations
**AR:** _[translator to fill]_

#### `case-studies.telecom.body`
**EN:** A telecom provider was generating four critical monthly reports manually: Revenue Detail, Business Revenue, Support Tickets, and AR Aging. Each took days to compile. We consolidated everything into automated pipelines plus an 11-page BI dashboard with AI-generated insights and predictive analytics.
**AR:** _[translator to fill]_

#### `case-studies.telecom.result1.value`
**EN:** 4-in-1
**AR:** _[keep as-is]_

#### `case-studies.telecom.result1.label`
**EN:** Reports consolidated
**AR:** _[translator to fill]_

#### `case-studies.telecom.result2.value`
**EN:** 11
**AR:** _[keep as-is]_

#### `case-studies.telecom.result2.label`
**EN:** Dashboard pages
**AR:** _[translator to fill]_

#### `case-studies.telecom.result3.value`
**EN:** AI
**AR:** _[translator to fill — e.g. "ذكاء اصطناعي"]_

#### `case-studies.telecom.result3.label`
**EN:** Predictive insights
**AR:** _[translator to fill]_

#### `case-studies.telecom.result4.value`
**EN:** Days
**AR:** _[translator to fill]_

#### `case-studies.telecom.result4.label`
**EN:** To minutes
**AR:** _[translator to fill]_

#### `case-studies.telecom.value.label`
**EN:** Estimated Value
**AR:** _[translator to fill]_

#### `case-studies.telecom.value.amount`
**EN:** $200K+
**AR:** _[keep as-is]_

#### `case-studies.telecom.value.period`
**EN:** per year in efficiency gains
**AR:** _[translator to fill]_

### Case 3 — Invoice Reconciliation

#### `case-studies.invoice.badge`
**EN:** Financial Operations
**AR:** _[translator to fill]_

#### `case-studies.invoice.h3`
**EN:** Automated <span>Invoice Reconciliation</span> at Scale
**AR:** _[translator to fill]_

#### `case-studies.invoice.body`
**EN:** Manual invoice matching across Google and Meta advertising platforms was taking 3 full-time employees days of work each billing cycle. Discrepancies were caught late, costing money. We built an automated reconciliation system that matches invoices in minutes and flags discrepancies instantly.
**AR:** _[translator to fill]_

#### `case-studies.invoice.result1.value`
**EN:** 70%
**AR:** _[keep as-is]_

#### `case-studies.invoice.result1.label`
**EN:** Faster reconciliation
**AR:** _[translator to fill]_

#### `case-studies.invoice.result2.value`
**EN:** Instant
**AR:** _[translator to fill]_

#### `case-studies.invoice.result2.label`
**EN:** Discrepancy alerts
**AR:** _[translator to fill]_

#### `case-studies.invoice.result3.value`
**EN:** $15
**AR:** _[keep as-is]_

#### `case-studies.invoice.result3.label`
**EN:** To $2.50/invoice
**AR:** _[translator to fill — keep figure]_

#### `case-studies.invoice.result4.value`
**EN:** 3 FTEs
**AR:** _[translator to fill — keep numeral, translate FTE if needed]_

#### `case-studies.invoice.result4.label`
**EN:** Freed for value work
**AR:** _[translator to fill]_

#### `case-studies.invoice.value.label`
**EN:** Estimated Value
**AR:** _[translator to fill]_

#### `case-studies.invoice.value.amount`
**EN:** $180K-380K
**AR:** _[keep as-is]_

#### `case-studies.invoice.value.period`
**EN:** per year in labor savings
**AR:** _[translator to fill]_

### Case 4 — CRM Error Detection

#### `case-studies.crm.badge`
**EN:** CRM / Data Quality
**AR:** _[translator to fill]_

#### `case-studies.crm.h3`
**EN:** Proactive <span>CRM Error Detection</span> Before Damage
**AR:** _[translator to fill]_

#### `case-studies.crm.body`
**EN:** Bad CRM data was costing millions in missed opportunities and duplicate outreach. Sales reps discovered errors only after losing deals. We implemented automated workflows that scan CRM data nightly, identify issues, and deliver morning reports before anyone starts their day.
**AR:** _[translator to fill]_

#### `case-studies.crm.result1.value`
**EN:** 24/7
**AR:** _[keep as-is]_

#### `case-studies.crm.result1.label`
**EN:** Automated monitoring
**AR:** _[translator to fill]_

#### `case-studies.crm.result2.value`
**EN:** Morning
**AR:** _[translator to fill]_

#### `case-studies.crm.result2.label`
**EN:** Reports delivered
**AR:** _[translator to fill]_

#### `case-studies.crm.result3.value`
**EN:** Proactive
**AR:** _[translator to fill]_

#### `case-studies.crm.result3.label`
**EN:** vs reactive fixes
**AR:** _[translator to fill]_

#### `case-studies.crm.result4.value`
**EN:** Critical
**AR:** _[translator to fill]_

#### `case-studies.crm.result4.label`
**EN:** Issues flagged early
**AR:** _[translator to fill]_

#### `case-studies.crm.value.label`
**EN:** Revenue Protected
**AR:** _[translator to fill]_

#### `case-studies.crm.value.amount`
**EN:** $500K-1.5M
**AR:** _[keep as-is]_

#### `case-studies.crm.value.period`
**EN:** per year in prevented losses
**AR:** _[translator to fill]_

### Case 5 — Knowledge Retrieval

#### `case-studies.knowledge.badge`
**EN:** Knowledge Management
**AR:** _[translator to fill]_

#### `case-studies.knowledge.h3`
**EN:** Company Internal Data & <span>Knowledge Retrieval</span> System
**AR:** _[translator to fill]_

#### `case-studies.knowledge.body`
**EN:** Employees spent 1.8+ hours daily searching for information buried across SharePoint, email, Slack, and shared drives. Institutional knowledge lived in people's heads. We deployed a RAG-powered AI assistant that searches all company documents and surfaces answers in seconds, not hours.
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result1.value`
**EN:** 1.8+ hrs
**AR:** _[translator to fill — keep 1.8+, translate "hrs"]_

#### `case-studies.knowledge.result1.label`
**EN:** Daily search time saved
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result2.value`
**EN:** Seconds
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result2.label`
**EN:** Time to answer
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result3.value`
**EN:** All
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result3.label`
**EN:** Data sources unified
**AR:** _[translator to fill]_

#### `case-studies.knowledge.result4.value`
**EN:** 24/7
**AR:** _[keep as-is]_

#### `case-studies.knowledge.result4.label`
**EN:** Instant availability
**AR:** _[translator to fill]_

#### `case-studies.knowledge.value.label`
**EN:** Estimated Value
**AR:** _[translator to fill]_

#### `case-studies.knowledge.value.amount`
**EN:** $150K-300K
**AR:** _[keep as-is]_

#### `case-studies.knowledge.value.period`
**EN:** per year per 100 employees
**AR:** _[translator to fill — keep "100"]_

### Case 6 — Citizen Chatbots

#### `case-studies.gov.badge`
**EN:** Government Services
**AR:** _[translator to fill]_

#### `case-studies.gov.h3`
**EN:** Bilingual <span>Citizen Service Chatbots</span>
**AR:** _[translator to fill]_

#### `case-studies.gov.body`
**EN:** A government authority received thousands of citizen inquiries monthly about permits, complaints, and procedures. Staff was overwhelmed. We deployed AI chatbots in Arabic and English that handle routine inquiries 24/7, freeing staff for complex cases and eliminating wait times.
**AR:** _[translator to fill]_

#### `case-studies.gov.result1.value`
**EN:** 24/7
**AR:** _[keep as-is]_

#### `case-studies.gov.result1.label`
**EN:** Citizen support
**AR:** _[translator to fill]_

#### `case-studies.gov.result2.value`
**EN:** Bilingual
**AR:** _[translator to fill]_

#### `case-studies.gov.result2.label`
**EN:** Arabic & English
**AR:** _[translator to fill]_

#### `case-studies.gov.result3.value`
**EN:** 70%+
**AR:** _[keep as-is]_

#### `case-studies.gov.result3.label`
**EN:** Inquiries automated
**AR:** _[translator to fill]_

#### `case-studies.gov.result4.value`
**EN:** Zero
**AR:** _[translator to fill]_

#### `case-studies.gov.result4.label`
**EN:** Wait time
**AR:** _[translator to fill]_

#### `case-studies.gov.value.label`
**EN:** Cost Avoided
**AR:** _[translator to fill]_

#### `case-studies.gov.value.amount`
**EN:** $250K+
**AR:** _[keep as-is]_

#### `case-studies.gov.value.period`
**EN:** per year in staff capacity
**AR:** _[translator to fill]_

### Case 7 — AI Training & Enablement

#### `case-studies.enablement.badge`
**EN:** Team Enablement
**AR:** _[translator to fill]_

#### `case-studies.enablement.h3`
**EN:** AI <span>Training & Certification</span> for Self-Sufficiency
**AR:** _[translator to fill]_

#### `case-studies.enablement.body`
**EN:** Organizations kept paying external consultants for every automation. We trained their internal teams to build AI solutions themselves. Employees went from waiting weeks for developer support to building their own workflows in hours. The capability compounds: trained teams train others.
**AR:** _[translator to fill]_

#### `case-studies.enablement.result1.value`
**EN:** Weeks
**AR:** _[translator to fill]_

#### `case-studies.enablement.result1.label`
**EN:** To hours for solutions
**AR:** _[translator to fill]_

#### `case-studies.enablement.result2.value`
**EN:** Self
**AR:** _[translator to fill]_

#### `case-studies.enablement.result2.label`
**EN:** Sufficient teams
**AR:** _[translator to fill]_

#### `case-studies.enablement.result3.value`
**EN:** Zero
**AR:** _[translator to fill]_

#### `case-studies.enablement.result3.label`
**EN:** External dependency
**AR:** _[translator to fill]_

#### `case-studies.enablement.result4.value`
**EN:** 10x
**AR:** _[keep as-is]_

#### `case-studies.enablement.result4.label`
**EN:** ROI multiplier
**AR:** _[translator to fill]_

#### `case-studies.enablement.value.label`
**EN:** ROI Multiplier
**AR:** _[translator to fill]_

#### `case-studies.enablement.value.amount`
**EN:** 10x
**AR:** _[keep as-is]_

#### `case-studies.enablement.value.period`
**EN:** return on training investment
**AR:** _[translator to fill]_

### Final CTA

#### `case-studies.cta.h2`
**EN:** Ready for Results Like These?
**AR:** _[translator to fill]_

#### `case-studies.cta.body`
**EN:** Let's discuss how we can deliver similar outcomes for your organization.
**AR:** _[translator to fill]_

#### `case-studies.cta.button`
**EN:** Book a FREE 30-Minute Consultation
**AR:** _[translator to fill]_

#### `case-studies.cta.note`
**EN:** 30 minutes · No obligation · We do the math for you
**AR:** _[translator to fill]_

---

## ai-dashboard.html

### Page meta

#### `ai-dashboard.meta.title`
**EN:** AI Dashboard — Your Entire Business. One Screen. Real Time. | AI Superpowers
**AR:** _[translator to fill]_

#### `ai-dashboard.meta.description`
**EN:** AI Dashboard connects all your systems into one live view. See everything. Ask anything. Decide faster. By AI Superpowers.
**AR:** _[translator to fill — already localised in -ar file; confirm wording matches]_

### Hero

#### `ai-dashboard.hero.tag`
**EN:** AI DASHBOARD
**AR:** _[translator to fill — ALL CAPS styling in EN; Arabic has no case, render normally]_

#### `ai-dashboard.hero.h1`
**EN:** Your entire business.<br>One screen. <span>Real time.</span>
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.h2`
**EN:** See everything. Ask anything. <span>Decide faster.</span>
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.body`
**EN:** AI Dashboard connects all your systems into one live view — <strong>so you can see how your company performs and make strategic decisions in minutes, not days.</strong> Ask questions in any language. Get answers from one source.
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.stat1.number`
**EN:** 32+
**AR:** _[keep as-is]_

#### `ai-dashboard.hero.stat1.label`
**EN:** hrs/week saved
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.stat2.number`
**EN:** $715K
**AR:** _[keep as-is]_

#### `ai-dashboard.hero.stat2.label`
**EN:** annual savings
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.stat3.number`
**EN:** 90 days
**AR:** _[translator to fill — keep "90"]_

#### `ai-dashboard.hero.stat3.label`
**EN:** to live system
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.cta`
**EN:** Book a free 30-min call →
**AR:** _[translator to fill — arrow flips in RTL]_

#### `ai-dashboard.hero.who.label`
**EN:** BUILT FOR:
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.who.tag1`
**EN:** C-suite & executives
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.who.tag2`
**EN:** 50–500 employees
**AR:** _[translator to fill — keep numerals]_

#### `ai-dashboard.hero.who.tag3`
**EN:** Multi-system orgs
**AR:** _[translator to fill]_

#### `ai-dashboard.hero.who.tag4`
**EN:** Gov & enterprise
**AR:** _[translator to fill]_

### Demo section

#### `ai-dashboard.demo.tag`
**EN:** HOW IT WORKS
**AR:** _[translator to fill]_

#### `ai-dashboard.demo.h3`
**EN:** See it in action.
**AR:** _[translator to fill]_

#### `ai-dashboard.demo.sub`
**EN:** Ask your data a question. Get an answer. That's it.
**AR:** _[translator to fill]_

#### `ai-dashboard.demo.query`
**EN:** "What happened to Q3 revenue vs. forecast?"
**AR:** _[translator to fill — this is sample user input; translate naturally, keep "Q3"]_

#### `ai-dashboard.demo.answer`
**EN:** <strong>Q3 revenue was $2.4M, 12% below the $2.73M forecast.</strong> The primary driver was a 23% decline in EMEA renewals during August. Three enterprise accounts delayed renewals totalling $340K. Pipeline shows 2 of 3 are now in active negotiation for Q4 close. <strong>Based on current pipeline velocity, Q4 is projected at $2.9M — 6% above target.</strong>
**AR:** _[translator to fill — keep all figures, Q3/Q4, EMEA]_

### Capabilities

#### `ai-dashboard.cap1.title`
**EN:** Real-time data from all systems
**AR:** _[translator to fill]_

#### `ai-dashboard.cap1.desc`
**EN:** CRM, ERP, finance, HR — one live view. No exports, no copy-paste.
**AR:** _[translator to fill]_

#### `ai-dashboard.cap2.title`
**EN:** Natural language queries
**AR:** _[translator to fill]_

#### `ai-dashboard.cap2.desc`
**EN:** Ask in any language. Get answers in seconds, not days.
**AR:** _[translator to fill]_

#### `ai-dashboard.cap3.title`
**EN:** AI-flagged anomalies
**AR:** _[translator to fill]_

#### `ai-dashboard.cap3.desc`
**EN:** Trends and risks surfaced before you ask. The system learns what matters.
**AR:** _[translator to fill]_

#### `ai-dashboard.cap4.title`
**EN:** Automated reporting
**AR:** _[translator to fill]_

#### `ai-dashboard.cap4.desc`
**EN:** Scheduled reports, KPI alerts, board-ready exports. Zero manual work.
**AR:** _[translator to fill]_

#### `ai-dashboard.cap5.title`
**EN:** Predictive insights
**AR:** _[translator to fill]_

#### `ai-dashboard.cap5.desc`
**EN:** Demand forecasting, inventory trends, revenue projections — based on your historical data.
**AR:** _[translator to fill]_

### Integrations

#### `ai-dashboard.int.label`
**EN:** CONNECTS TO YOUR EXISTING SYSTEMS
**AR:** _[translator to fill]_

#### `ai-dashboard.int.cat1`
**EN:** CRM & sales
**AR:** _[translator to fill — vendor names below stay English]_

#### `ai-dashboard.int.cat2`
**EN:** ERP & finance
**AR:** _[translator to fill]_

#### `ai-dashboard.int.cat3`
**EN:** Files & drives
**AR:** _[translator to fill]_

#### `ai-dashboard.int.cat3.pdf`
**EN:** PDF reports
**AR:** _[translator to fill — "PDF" stays, "reports" translated]_

#### `ai-dashboard.int.cat3.excel`
**EN:** Excel / CSV
**AR:** _[keep as-is, brand/format names]_

#### `ai-dashboard.int.cat3.word`
**EN:** Word docs
**AR:** _[translator to fill — keep "Word"]_

#### `ai-dashboard.int.cat4`
**EN:** Communication & collaboration
**AR:** _[translator to fill]_

#### `ai-dashboard.int.cat5`
**EN:** HR & operations
**AR:** _[translator to fill]_

#### `ai-dashboard.int.cat6`
**EN:** Data & infrastructure
**AR:** _[translator to fill]_

#### `ai-dashboard.int.more`
**EN:** Don't see your system? We connect to anything with an API →
**AR:** _[translator to fill — keep "API"]_

### Deliverables

#### `ai-dashboard.del.tag`
**EN:** WHAT YOU GET
**AR:** _[translator to fill]_

#### `ai-dashboard.del.h3`
**EN:** What you actually get.
**AR:** _[translator to fill]_

#### `ai-dashboard.del.sub`
**EN:** Not a demo. Not a report. Working systems you own permanently.
**AR:** _[translator to fill]_

#### `ai-dashboard.del1.title`
**EN:** Live AI-powered dashboard
**AR:** _[translator to fill]_

#### `ai-dashboard.del1.desc`
**EN:** Real-time data from all connected systems. Accessible from any device, anywhere.
**AR:** _[translator to fill]_

#### `ai-dashboard.del2.title`
**EN:** Natural language interface
**AR:** _[translator to fill]_

#### `ai-dashboard.del2.desc`
**EN:** Ask questions in any language. Instant answers from your own data.
**AR:** _[translator to fill]_

#### `ai-dashboard.del3.title`
**EN:** Automated alerts & reports
**AR:** _[translator to fill]_

#### `ai-dashboard.del3.desc`
**EN:** Anomaly detection, KPI tracking, board-ready exports — no manual work.
**AR:** _[translator to fill]_

#### `ai-dashboard.del4.title`
**EN:** Clean data pipeline
**AR:** _[translator to fill]_

#### `ai-dashboard.del4.desc`
**EN:** Unified integration layer connecting your existing systems. No rip-and-replace.
**AR:** _[translator to fill]_

#### `ai-dashboard.del5.title`
**EN:** Full source code + docs
**AR:** _[translator to fill]_

#### `ai-dashboard.del5.desc`
**EN:** You own every line. Architecture docs, maintenance guides, API references.
**AR:** _[translator to fill]_

#### `ai-dashboard.del6.title`
**EN:** Team training + transfer
**AR:** _[translator to fill]_

#### `ai-dashboard.del6.desc`
**EN:** Hands-on sessions until your team runs it independently. Real training, not a webinar.
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item1.title`
**EN:** <strong>Your servers</strong>
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item1.desc`
**EN:** Never ours
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item2.title`
**EN:** <strong>Your data</strong>
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item2.desc`
**EN:** Never leaves
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item3.title`
**EN:** <strong>Your code</strong>
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item3.desc`
**EN:** Inspect anytime
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item4.title`
**EN:** <strong>Your team</strong>
**AR:** _[translator to fill]_

#### `ai-dashboard.own.item4.desc`
**EN:** Runs it alone
**AR:** _[translator to fill]_

### Proof section

#### `ai-dashboard.proof.tag`
**EN:** REAL RESULTS
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.h3`
**EN:** AI Dashboard results from real clients.
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.quote`
**EN:** From idea to working prototype in weeks. They understood the business logic immediately, built something real, and gave us a system we could iterate on ourselves.
**AR:** _[translator to fill — same quote used on index.html, keep wording consistent with `index.testimonials.t2.quote`]_

#### `ai-dashboard.proof.author.name`
**EN:** Karol Sadaj
**AR:** _[translator to fill — match `index.testimonials.t2.name`]_

#### `ai-dashboard.proof.author.role`
**EN:** Fintech Executive · AIP Seed Board · ex-Revolut
**AR:** _[translator to fill — match `index.testimonials.t2.role`]_

#### `ai-dashboard.proof.case1.industry`
**EN:** HIGHER EDUCATION
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.case1.num`
**EN:** $715K+
**AR:** _[keep as-is]_

#### `ai-dashboard.proof.case1.label`
**EN:** Annual savings from automated executive dashboards. 32+ hrs/week eliminated.
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.case2.industry`
**EN:** TELECOM
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.case2.num`
**EN:** 4 → 1
**AR:** _[keep as-is, arrow glyph flips naturally in RTL]_

#### `ai-dashboard.proof.case2.label`
**EN:** Monthly reports consolidated into one AI-powered dashboard with predictive insights.
**AR:** _[translator to fill]_

#### `ai-dashboard.proof.link`
**EN:** See all case studies →
**AR:** _[translator to fill]_

### FAQ

#### `ai-dashboard.faq.tag`
**EN:** FAQ
**AR:** _[translator to fill — Arabic equivalent "الأسئلة الشائعة"]_

#### `ai-dashboard.faq.h3`
**EN:** Common questions about AI Dashboard.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q1.q`
**EN:** "What about data security?"
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q1.a`
**EN:** Everything runs on your infrastructure. Data never leaves your environment. We work within your existing security and compliance frameworks.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q2.q`
**EN:** "We already have Power BI / Tableau."
**AR:** _[translator to fill — keep Power BI / Tableau]_

#### `ai-dashboard.faq.q2.a`
**EN:** BI tools show charts. AI Dashboard gives answers in plain language. We often layer on top of existing BI — not replace it.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q3.q`
**EN:** "Our data is a mess."
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q3.a`
**EN:** 80% of our work is cleaning and connecting data. If it were already clean, you wouldn't need us.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q4.q`
**EN:** "How much does this cost?"
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q4.a`
**EN:** Depends on scope. The free assessment gives you a clear picture before any commitment. Most clients see ROI within 90 days.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q5.q`
**EN:** "Does it support my language?"
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q5.a`
**EN:** Yes. Interface, queries, and generated reports work in any language — Arabic, English, Polish, Spanish, and more. Built for global teams.
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q6.q`
**EN:** "How long until it's live?"
**AR:** _[translator to fill]_

#### `ai-dashboard.faq.q6.a`
**EN:** 90 days from kickoff to live system. First working prototype typically within 4–6 weeks.
**AR:** _[translator to fill]_

### Final CTA

#### `ai-dashboard.cta.h2`
**EN:** Stop chasing data.<br>Start getting answers.
**AR:** _[translator to fill]_

#### `ai-dashboard.cta.sub`
**EN:** 30-minute call. No pitch. We come prepared.
**AR:** _[translator to fill]_

#### `ai-dashboard.cta.button`
**EN:** Book a free call →
**AR:** _[translator to fill]_

#### `ai-dashboard.cta.trust1`
**EN:** Free initial assessment
**AR:** _[translator to fill]_

#### `ai-dashboard.cta.trust2`
**EN:** No commitment required
**AR:** _[translator to fill]_

#### `ai-dashboard.cta.trust3`
**EN:** Keep the assessment either way
**AR:** _[translator to fill]_

### Footer

#### `ai-dashboard.footer.tagline`
**EN:** "We build it. We train you. We leave."
**AR:** _[translator to fill — same as index footer; translate once, reuse]_
