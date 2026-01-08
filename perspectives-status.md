# QUICK STATUS (for Claude)

**Project:** Perspective Pieces - Thought Leadership Content
**Phase:** Planning - Series 1 (3 pieces)
**Last updated:** 2026-01-08

## Purpose

Create thought leadership content demonstrating architectural expertise, philosophy, and business impact. Content serves multiple channels:
- Portfolio website (Perspectives section)
- LinkedIn (potential articles/posts derived from pieces)
- Interview talking points (articulating approach and experience)

## Done
- Format decided: 800-1,200 words, practical/pragmatic style, visuals optional
- Topics selected: Series 1 (3 pieces) and Series 2 (future)
- Agent validation: exec-recruiter and personal-marketeer both endorsed format choices
- **architecture-peer agent built (2026-01-08)** - Technical credibility review for outlines and backlog curation
  - Moved to personal agents: `~/.claude/agents/architecture-peer.md`
  - Updated scope: Reviews perspectives, ADRs, proposals, architecture docs
- **perspective-critic → content-critic (2026-01-08)** - Multi-persona Amazon loop-style review for drafts
  - Renamed and moved to personal agents: `~/.claude/agents/content-critic.md`
  - Updated scope: Reviews any written content (perspectives, blogs, docs, proposals)
  - Same Amazon loop process (3 personas review independently, then discuss)

## Current State

**Series 1 (Initial Launch):**
Three pieces to be written, then Perspectives section implemented on website.

| # | Title | Status | Purpose |
|---|-------|--------|---------|
| 1 | "Just Enough Architecture" | Not started | Core philosophy - pragmatic governance |
| 2 | "Building Architecture Functions from Scratch" | Not started | Organizational capability - Oxa differentiator |
| 3 | "Architecture as a Product" | Not started | Modern strategic thinking - stakeholder-centric |

**Series 2 (Initial Backlog - 3 topics identified):**
- "Age of Intent" - AI/LLM effects on system interaction, UX, data
- "AI as the Consumer" - Design/build for AI era
- "Legacy Modernisation Patterns" - Technical depth for Principal/IC roles

**Content Backlog (to be built):**
- Target: 12-20 topics total (including Series 1 + Series 2 above = 6 so far)
- Need: 6-14 additional topic ideas
- Will be tracked in: `Resume/Perspectives/content-backlog.md` (to be created)
- Structure: Prioritised list with topic, purpose, target audience, estimated difficulty

## Next Steps (offer these)

**Immediate (Series 1 - First 3 Pieces):**
1. **Outline first piece** - Step 1 of workflow (choose #1 "Just Enough Arch" or #2 "Building Functions")
2. **Review outline with agents** - Step 2: architecture-peer + personal-marketeer feedback
3. **Nick writes first draft** - Step 3 of workflow (with validated outline)
4. **Run critic agent review** - Step 4 of workflow (Amazon loop-style review → 6 files in timestamped folder)
5. **Refine based on feedback** - Steps 5-7 of workflow
6. **Repeat for pieces #2 and #3** - Same 7-step process
7. **Review and refine all 3 pieces** - Ensure consistency, visual needs
8. **Hand off to website workstream** - Ready for Perspectives section implementation

**Content Pipeline (Sustainable Habit Building):**
9. **Create content backlog (12-20 ideas)** - Work together to build ~1 year of topic ideas (1/month cadence)
    - Best done after first piece is published (builds momentum from success)
    - Creates `Resume/Perspectives/content-backlog.md` with prioritised list
    - **Maintained by:** personal-marketeer + architecture-peer agents
10. **Regular backlog review** - Monthly/weekly review to adjust priorities, add/remove topics based on hot trends
    - Keep backlog dynamic and responsive to architecture community discussions
    - **Reviewed by:** personal-marketeer + architecture-peer agents

## Format Guidelines

**Length:** 800-1,200 words (~5 minute read)
- Short enough to respect busy readers (recruiters, hiring managers)
- Long enough to demonstrate depth through specificity

**Style:** Practical/Pragmatic
- Real-world examples and trade-offs
- Conversational but professional
- Opinionated stance (demonstrates confidence and experience)
- Lead with insight, not background

**Structure (recommended):**
1. **Opening summary** - "The Bottom Line" or "Key Insight" (executive-friendly, not "TLDR")
2. **The problem/context** - What challenge does this address?
3. **Your approach** - Core idea with 1-2 concrete examples from practice
4. **Trade-offs** - What you gain/lose with this approach (demonstrates maturity)
5. **Outcome/Application** - How this plays out in practice

**Visuals:** Recommended (one per piece)
- One simple diagram per piece (demonstrates C4/visualisation skills without being explicit)
- Not elaborate system architecture - conceptual diagrams or frameworks
- Breaks up text, improves scannability, provides social media assets
- Agent feedback: "Architects who can visualise are more valuable than those who cannot"

## Key Constraints
- **Concrete examples required** - Each piece needs "here's how this played out in practice"
- **British English spelling** - colour, modernisation, organisation
- **Avoid staying abstract** - Depth through specificity, not length
- **One core idea per piece** - Focused, not comprehensive
- **Timing:** Publish all 3 within ~1 month for "body of work" impression

## Key Decisions Made
- **Format:** Short-form (800-1,200) over medium (1,500-2,500) or long (3,000-5,000)
- **Rationale:** Respects busy readers, demonstrates executive communication skills
- **Opening summary:** "The Bottom Line" or "Key Insight" (more executive than "TLDR")
- **Visuals:** One simple diagram per piece RECOMMENDED (agent feedback: demonstrates visualisation capability)
- **Topic #2 as differentiator:** "Building Architecture Functions" is strongest unique positioning
- **Sequencing:** Consider leading with #2 for maximum impact
- **Series 2 (AI topics):** After Series 1 published (avoid scope creep)
- **Agent validation:** Both exec-recruiter and personal-marketeer endorsed choices
- **Writing workflow:** 7-step collaborative process with outline review (architecture-peer + personal-marketeer) BEFORE writing, then multi-persona critic agent review of draft
- **Agent roles clarified:** exec-recruiter for CV/LinkedIn/hiring appeal; architecture-peer for technical credibility/peer respect; personal-marketeer for brand strategy
- **Content backlog strategy:** Build 12-20 topic ideas for sustainable 1/month cadence; regular review to stay current with trends
- **LinkedIn habit building:** Use perspectives as foundation for consistent LinkedIn presence (not currently posting)

## Content Backlog Strategy

**Purpose:** Build sustainable writing habit and LinkedIn presence

**Goals:**
- Create 12-20 topic ideas (~1 year of content at 1/month cadence)
- Establish regular posting rhythm on LinkedIn
- Build habit of consistent content creation
- Maintain relevance by tracking hot topics in architecture space

**Review Cadence:**
- **Weekly/Monthly reviews:** Adjust priorities based on current trends
- **Add new topics:** Capture emerging architecture discussions
- **Remove stale topics:** Drop ideas that no longer feel relevant
- **Reorder by impact:** Prioritise topics with highest strategic value

**Content Mix (suggested):**
- **Philosophy pieces** (e.g., "Just Enough Architecture") - 20-30%
- **Practical patterns** (e.g., "Legacy Modernisation") - 30-40%
- **Organizational capability** (e.g., "Building Functions") - 20-30%
- **Emerging trends** (e.g., "Age of Intent", AI topics) - 10-20%

**Benefits:**
- Never face "blank page" writer's block
- Can write opportunistically when topic becomes hot
- Demonstrates thought leadership consistency over time
- Builds LinkedIn visibility systematically

## Cross-Workstream Dependencies

**→ Website:**
- Once 3 pieces complete, implement Perspectives section on nickgushlow.com
- Design/build section to display pieces (cards, list, or feature layout)

**→ LinkedIn:**
- Derive 2-3 posts per piece (extract key insights as standalone content)
- Optional: Publish full pieces as LinkedIn articles
- Build regular posting habit (1/month minimum with perspectives content)

**→ Interview Prep:**
- Each piece provides structured answer to "Tell me about your approach to X"
- Examples from pieces become talking points for STAR-format stories

## Success Criteria

**For each piece:**
- ✅ 800-1,200 word count
- ✅ At least one concrete example from real experience
- ✅ Clear opinionated stance (not neutral survey)
- ✅ Practical value for practicing architects
- ✅ Demonstrates business impact thinking (not just technical)

**For the series:**
- ✅ Consistent voice and quality across all 3
- ✅ Progression: Philosophy → Capability → Strategy
- ✅ All published within ~1 month of each other
- ✅ Ready for website Perspectives section implementation

## Reference Documents
- `website-session-logs.md` - Original perspectives section planning
- Agent feedback (2026-01-07): exec-recruiter and personal-marketeer validation

## Writing Workflow (7-Step Collaborative Process)

### **Step 1: Outline/Structure**
- Work together (Nick + Claude) to create outline
- Define: opening summary, problem/context, approach, trade-offs, outcome
- Identify concrete examples to include
- Sketch potential visual/diagram concept

### **Step 2: Outline Review (architecture-peer + personal-marketeer)** ✅ **AGENTS READY**
- **Get agent feedback BEFORE Nick writes** (saves time by catching issues early)
- **architecture-peer** (personal agent `~/.claude/agents/architecture-peer.md`) reviews: Is this technically sound? Will EA/Chief Architect peers respect this?
- **personal-marketeer** (personal agent `~/.claude/agents/personal-marketeer.md`) reviews: Does this build brand effectively? Is positioning right?
- Discuss feedback and refine outline based on recommendations

### **Step 3: Nick Writes First Draft**
- Nick writes the piece independently (now with validated outline)
- Target: 800-1,200 words
- Include concrete examples from practice
- Draft visual if applicable

### **Step 4: Multi-Persona Critic Agent Review** ✅ **AGENT READY**
- **content-critic** (personal agent `~/.claude/agents/content-critic.md`) performs Amazon loop-style review
- **Persona 1:** CIO/CTO executive leader (content quality/soundness - "would this be sound advice if presented to my exec?")
- **Persona 2:** Enterprise Architect peer (technical credibility and depth)
- **Persona 3:** Startup owner (practical business impact lens)
- Each persona reviews independently
- Personas then compare notes and see if others' views change their own
- **Outputs (6 files in timestamped Reviews folder):**
  - Individual persona reviews (3 files)
  - Amazon loop discussion (1 file)
  - Combined recommendation (1 file)
  - Brutal honest review (1 file)

### **Step 5: Discuss Reviews & Changes**
- Nick and Claude discuss critic agent output
- Identify which recommendations to adopt
- Prioritise changes (must-fix vs nice-to-have)

### **Step 6: Nick Rewrites**
- Nick incorporates agreed changes
- Refines based on feedback

### **Step 7: Optional Re-Review**
- If changes are simple: Skip re-review
- If significant rewrites: Offer to run critic agent again
- Nick decides based on scope of changes
