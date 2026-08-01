# Buyer Persona Builder

Research and build one or more buyer personas profile for a new market or domain in hours, not weeks.

Skip weeks of interview scheduling. Get a research-backed persona first draft in hours by synthesizing job postings, analyst reports, product docs, forums, and reviews. Then use real interviews to validate.

**Use this skill if you're:**
- Entering a new market without interview access
- Launching a new product where you don't know the key buyers yet
- Accelerating persona work when you have a few weeks, not months.

---

## What's in the repo

- **buyer-persona-skill.md**: The full skill definition. Shows the research strategy (which angles to cover: job descriptions, analyst reports, docs, forums, reviews), the one-page persona structure, and how to orchestrate the research autonomously.
- **persona-template.md**: Markdown template for importing personas into Notion, Google Docs, or your wiki. Copy-paste ready.
- **persona-template.html**: HTML template for a clean, one-page web or print-ready version.
- **example-output/maria-fleet-operations-manager.md**: A complete example persona showing the expected output format and level of specificity.

---

## How to use it

### Step 1: Set up Claude

If you're running this in Claude.ai or Claude Code:

1. Download or copy buyer-persona-skill.md to your Claude Project's skills section, or paste it as a custom instruction.
2. Download persona-template.md (for Notion/Docs) and/or persona-template.html (for web/print) if you want to customize output formatting.

If you're using Claude via API:
- Include the buyer-persona-skill.md content in your system prompt when calling the API.

### Step 2: Prompt the skill

The best results come from giving context upfront: your domain, company size, and what you have (or don't have) to work with. If you already know which roles matter, name them:

```
I'm launching a predictive maintenance SaaS for logistics fleets (50-500 vehicles).
Help me build 2 personas: the operations manager who gets the breakdown calls, and the 
CFO who approves the budget. I have no interview access yet.
```

If you don't know who the key buyers are yet, that's fine too — the skill will research the market and propose who to profile before going deep:

```
I'm launching a predictive maintenance SaaS for logistics fleets (50-500 vehicles).
I don't know yet who the key buyers are in this space. Can you research the market, 
suggest 2-3 personas worth profiling, and build them out once I confirm?
```

A shorter prompt works too ("Build buyer personas for a fleet maintenance SaaS"). The skill will ask a few quick questions to fill the gaps before researching.  
But the more context you give upfront, the less back-and-forth and the sharper the first draft.

### Step 3: Let the skill do the research

The skill will:
1. Identify research angles (job descriptions, analyst firms, forums, help docs, reviews)
2. Search across those angles in parallel
3. Identify the personas you asked for
4. Write one profile per persona: Example Titles, Summary, Wants/Needs/Desires, Challenges, Tasks

### Step 4: Choose your format

After the personas are drafted, the skill asks:

- **Notion/Docs?** Get markdown that copies straight into Notion or Google Docs
- **Web/Print?** Get the HTML version for a polished one-pager

### Step 5: Use the output

Personas go straight into:
- **Positioning work:** Who are we talking to? What matters to them?
- **GTM planning:** Which channels? Which proof points?
- **Sales enablement:** How does each persona buy? What concerns them?
- **Content strategy:** What questions does each persona have?

---

## Persona structure

One page per persona, structured like this:

- **Example Titles:** 3-5 job titles this role might have (from job postings)
- **Summary:** 2-3 sentences: who they are, what they do, what their world looks like
- **Wants, Needs and Desires:** 4-5 bullets on what they're trying to achieve
- **Challenges:** 4-5 bullets on what's hard or frustrating
- **Tasks and Responsibilities:** 4-5 bullets on what they actually do

Plus: a source line at the bottom ("Built from: 8 job postings, 3 analyst reports, 12 forum discussions") so you know how credible each section is, and verified URLs for each source.

---

## When this works best

✓ Entering a new market without direct customer access  
✓ Launching a new product to an unfamiliar buyer profile  
✓ First-pass persona work before committing to interviews  
✓ Identifying which roles matter in a new category  
✓ Validating personas you already think exist  

✗ Synthesizing 50+ interview transcripts into personas (you can use this skill from the Product Marketing Alliance [customer-research](https://github.com/pmalliance/product-marketing-skills/blob/main/skills/customer-research.skill) instead)  
✗ Personas for product you already sell (you have interview data; use that first) 

---

## Why this approach

I created this skill to accelerate the knowledge of key buyer personas in a new domain. Sometimes you do not have enough time to interview prospects when you're new to a market. A Google search, a Reddit thread, and a job posts already contain key elements: how people talk about their problems, what they're measured on, what frustrates them.

The research strategy: job descriptions + analyst reports + docs + forums + reviews—works because each source validates or challenges the others. A job posting tells you responsibilities. A forum thread tells you actual frustrations. An analyst report tells you market trends. Together, they paint a credible first picture.

One page per persona (not 5 pages) forces clarity. If you can't say it in a page, you don't understand it yet.

Sourcing everything (showing where each claim comes from) means you know what's corroborated and what's inference. That shapes how you use the personas: strong claims go into messaging, inferences go into "validate with real interviews."

---

## Example

The `example-output/` folder shows what the skill produces. One persona for a fleet operations manager in logistics: her title variants, what she does daily, what she wants, what frustrates her, what she's responsible for.

That example is fabricated to show structure. A real run would be just as specific but grounded in actual job postings, analyst reports, and forum discussions.

---

## Limitations & Next Steps

This skill produces a first draft based on public research. After you have your persona profile(s):
- **Validate with real interviews.** Talk to 3-5 people per persona to validate assumptions.
- **Use [customer-research](https://github.com/pmalliance/product-marketing-skills/blob/main/skills/customer-research.skill)** for deeper interview-based synthesis.
- **Watch for blind spots.** Public research is better than nothing but misses context only customers know.

---

## Who built this

[Laure Brosseau](https://www.laurebrosseau.com) — Senior Product Marketing leader with 15+ years in B2B SaaS.   
Built Akeneo's PMM function from scratch. Led positioning, go-to-market, competitive intelligence, and win-loss analysis across product launches that generated €25M+ in ARR.

This is the skill I wish I'd had at Akeneo: it starts the research for you, pulling from job postings, forums, and analyst reports instead of you digging through it all by hand.

See more at [laurebrosseau.com](https://www.laurebrosseau.com) or [github.com/LaureBrosseau](https://github.com/LaureBrosseau).

---

## License

Open to use and share. No restrictions.
