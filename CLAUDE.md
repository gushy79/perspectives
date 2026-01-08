# Perspectives Project

Thought leadership content for **nickgushlow.com/perspectives**

---

## Global Standards

**Inherits from:** `/home/nickg/ClaudeCode/GLOBAL-STANDARDS.md`

All writing standards, Nick's profile, contact information, and quality standards are defined in the global standards file.

---

## Project Purpose

Create thought leadership content demonstrating architectural expertise, philosophy, and business impact. Perspective pieces serve multiple channels:

- **Portfolio website** - nickgushlow.com/perspectives section
- **LinkedIn** - Articles or posts derived from pieces
- **Interview talking points** - Structured answers to "Tell me about your approach to X"

**Target Audience:**
- CTO/CIO decision-makers evaluating architects
- EA/Chief Architect peers assessing credibility
- Hiring managers and recruiters researching candidates
- Architecture practitioners seeking practical insights

**Key Objectives:**
- Demonstrate depth through specificity (not length)
- Showcase pragmatic philosophy ("Just Enough Architecture")
- Establish thought leadership and professional visibility
- Provide concrete examples from 20+ years experience
- Build LinkedIn presence and content habit

---

## Project Location

**Directory:** `/home/nickg/ClaudeCode/Perspectives/`
**Git Repo:** `github.com/gushy79/perspectives` (public)
**Published To:** https://nickgushlow.com (via Portfolio project integration)

---

## Project Structure

```
Perspectives/
├── CLAUDE.md                  # This file
├── perspectives-status.md     # Current state and next steps
├── content-backlog.md         # Topic ideas and priorities (12-20 topics)
│
├── Published/                 # Final published pieces
│   ├── just-enough-architecture.md
│   ├── building-architecture-functions.md
│   └── architecture-as-product.md
│
├── Drafts/                    # Work in progress
│   ├── piece-title-draft-v1.md
│   └── piece-title-outline.md
│
├── Reviews/                   # Critic agent reviews (timestamped folders)
│   └── YYYY-MM-DD-HHMMSS-piece-title/
│       ├── 01-persona-cto-review.md
│       ├── 02-persona-ea-peer-review.md
│       ├── 03-persona-startup-owner-review.md
│       ├── 04-amazon-loop-discussion.md
│       ├── 05-combined-recommendation.md
│       └── 06-brutal-honest-review.md
│
└── .claude/
    └── commands/              # Custom slash commands (if needed)
```

---

## Content Format

### Length & Style
- **800-1,200 words** (~5 minute read)
- **Practical/pragmatic** tone (not academic)
- **Opinionated stance** (demonstrates confidence and experience)
- **Concrete examples** from real practice (depth through specificity)
- **Lead with insight** (no lengthy background setup)

### Structure Template
1. **Opening summary** - "The Bottom Line" or "Key Insight" (executive-friendly, not "TLDR")
2. **The problem/context** - What challenge does this address?
3. **Your approach** - Core idea with 1-2 concrete examples
4. **Trade-offs** - What you gain/lose (demonstrates maturity)
5. **Outcome/Application** - How this plays out in practice

### Visuals
- **One simple diagram per piece** (recommended)
- Conceptual frameworks, not elaborate system architecture
- Demonstrates visualisation capability (C4 modelling skills)
- Improves scannability and provides social media assets

---

## Content Series

### Series 1 (Initial Launch - 3 Pieces)
| # | Title | Purpose | Status |
|---|-------|---------|--------|
| 1 | "Just Enough Architecture" | Core philosophy - pragmatic governance | Not started |
| 2 | "Building Architecture Functions from Scratch" | Organizational capability - Oxa differentiator | Not started |
| 3 | "Architecture as a Product" | Modern strategic thinking - stakeholder-centric | Not started |

**Publishing strategy:** All 3 within ~1 month for "body of work" impression

### Series 2 (Future - Initial Backlog)
- "Age of Intent" - AI/LLM effects on system interaction, UX, data
- "AI as the Consumer" - Design/build for AI era
- "Legacy Modernisation Patterns" - Technical depth for Principal/IC roles

### Content Backlog
**Goal:** 12-20 topic ideas for sustainable 1/month cadence

**Tracked in:** `content-backlog.md`
- Prioritised by strategic value and timeliness
- Reviewed monthly/weekly to stay current with architecture trends
- Mix of philosophy (20-30%), practical patterns (30-40%), organizational capability (20-30%), emerging trends (10-20%)

---

## Writing Workflow (7-Step Process)

### Step 1: Outline/Structure
- Work together (Nick + Claude) to create outline
- Define: opening summary, problem/context, approach, trade-offs, outcome
- Identify concrete examples to include
- Sketch potential visual/diagram concept

### Step 2: Outline Review (architecture-peer + personal-marketeer)
**Get agent feedback BEFORE Nick writes** (saves time by catching issues early)

- **architecture-peer** reviews: Is this technically sound? Will EA/Chief Architect peers respect this?
- **personal-marketeer** reviews: Does this build brand effectively? Is positioning right?
- Discuss feedback and refine outline

### Step 3: Nick Writes First Draft
- Nick writes independently with validated outline
- Target: 800-1,200 words
- Include concrete examples from practice
- Draft visual if applicable

### Step 4: Multi-Persona Critic Agent Review
**content-critic** performs Amazon loop-style review

**Personas:**
1. **CIO/CTO executive leader** - Content quality/soundness ("would this be sound advice if presented to my exec?")
2. **Enterprise Architect peer** - Technical credibility and depth
3. **Startup owner** - Practical business impact lens

**Process:**
- Each persona reviews independently
- Personas compare notes and see if others' views change their own
- **Outputs:** 6 files in timestamped Reviews folder

### Step 5: Discuss Reviews & Changes
- Nick and Claude discuss critic agent output
- Identify which recommendations to adopt
- Prioritise changes (must-fix vs nice-to-have)

### Step 6: Nick Rewrites
- Nick incorporates agreed changes
- Refines based on feedback

### Step 7: Optional Re-Review
- Simple changes: Skip re-review
- Significant rewrites: Offer to run critic agent again
- Nick decides based on scope of changes

---

## Available Agents

### Personal Agents (Cross-Project)
Located in `/home/nickg/.claude/agents/`

**Career & Brand:**
- `exec-recruiter` - Career materials (if perspective affects CV/LinkedIn positioning)
- `personal-marketeer` - Brand strategy, content positioning, visibility

**Review & Validation:**
- `architecture-peer` - Technical credibility from EA peer lens (outlines, topics, technical depth)
- `content-critic` - Multi-persona Amazon loop review (drafts, final pieces)

### Project Agents
**None** - Perspectives uses only personal agents

---

## Quality Standards

### Success Criteria (Per Piece)
- ✅ 800-1,200 word count
- ✅ At least one concrete example from real experience
- ✅ Clear opinionated stance (not neutral survey)
- ✅ Practical value for practicing architects
- ✅ Demonstrates business impact thinking (not just technical)

### Success Criteria (Per Series)
- ✅ Consistent voice and quality across all pieces
- ✅ Logical progression (e.g., Philosophy → Capability → Strategy)
- ✅ All published within ~1 month of each other
- ✅ Ready for Portfolio website implementation

---

## Cross-Project Integration

### Perspectives → Portfolio
**Integration:** Published pieces displayed on website

**Workflow:**
1. Complete perspective piece (all 7 steps)
2. Publish to `Perspectives/Published/`
3. Switch to Portfolio project
4. Implement/update Perspectives section on website
5. Deploy to nickgushlow.com

**Current status:** Waiting for 3 pieces to be ready from Series 1

### Perspectives → LinkedIn
**Integration:** Derive posts/articles from perspective pieces

**Workflow:**
1. Published perspective serves as source material
2. Extract 2-3 key insights as standalone posts
3. Optional: Publish full piece as LinkedIn article
4. Build regular posting habit (1/month minimum)

**Benefits:** Converts long-form content into LinkedIn visibility without starting from scratch

### Perspectives → Interview Prep
**Integration:** Pieces become structured answers to interview questions

**Usage:**
- "Tell me about your approach to architecture governance" → "Just Enough Architecture" piece
- "How do you build architecture capability?" → "Building Architecture Functions" piece
- Examples from pieces become STAR-format talking points

---

## Key Decisions Made

**Format:**
- **Length:** 800-1,200 words (respects busy readers, demonstrates executive communication)
- **Opening:** "The Bottom Line" or "Key Insight" (more executive than "TLDR")
- **Visuals:** One simple diagram per piece RECOMMENDED (demonstrates visualisation capability)

**Content Strategy:**
- **Topic #2 as differentiator:** "Building Architecture Functions from Scratch" is strongest unique positioning
- **Series 1 first:** Focus on 3 initial pieces before expanding to Series 2 (avoid scope creep)
- **Publishing cadence:** All 3 within ~1 month for "body of work" impression

**Agent Workflow:**
- **Outline review BEFORE writing:** architecture-peer + personal-marketeer (catches issues early)
- **Draft review with multi-persona critic:** content-critic (Amazon loop process)
- **Agent roles clarified:** exec-recruiter for hiring appeal; architecture-peer for technical credibility; personal-marketeer for brand strategy; content-critic for multi-persona review

**Content Backlog:**
- **Build 12-20 topic ideas** for sustainable 1/month cadence
- **Regular review** (monthly/weekly) to stay current with architecture trends
- **Best timing:** After first piece published (builds momentum from success)

**LinkedIn Habit:**
- Use perspectives as foundation for consistent LinkedIn presence
- Convert long-form pieces into posts (2-3 per piece)
- Addresses current gap: not posting regularly on LinkedIn

---

## Status Files

**Current state:** `perspectives-status.md`
- Read at start of each session
- ~50-100 lines, current phase, next steps
- Updated at end of session

**Detailed history:** *(No session logs yet - will create when work begins)*

---

## Key Constraints

- **Concrete examples required** - Each piece needs "here's how this played out in practice"
- **British English spelling** - colour, modernisation, organisation
- **Avoid staying abstract** - Depth through specificity, not length
- **One core idea per piece** - Focused, not comprehensive
- **Timing:** Publish all 3 within ~1 month for "body of work" impression
- **No certifications to lean on** - Nick doesn't have TOGAF/Zachman; credibility comes from demonstrated experience

---

## Development Workflow

### Starting a New Piece

```bash
cd /home/nickg/ClaudeCode/Perspectives

# Create outline in Drafts/
# (Work with Claude on structure)

# Get outline reviewed by agents
# (architecture-peer + personal-marketeer)

# Nick writes draft based on validated outline

# Run critic agent review
# (content-critic creates timestamped folder in Reviews/)

# Discuss feedback and refine

# Move final piece to Published/
```

### Maintaining the Backlog

```bash
cd /home/nickg/ClaudeCode/Perspectives

# Edit content-backlog.md
# (Add/remove/reorder topics based on trends)

# Get backlog reviewed by agents
# (architecture-peer for technical relevance)
# (personal-marketeer for strategic value)
```

### Git Workflow

**Repository:** Public repo at `github.com/gushy79/perspectives`

**Branch strategy:**
- `main` - Production (published pieces)

**Making changes:**
```bash
cd /home/nickg/ClaudeCode/Perspectives

# Work in Drafts/ until piece is ready

# When piece is complete:
mv Drafts/piece-title.md Published/piece-title.md

# Commit and push
git add .
git commit -m "Publish: [Piece Title]

Co-Authored-By: Claude Sonnet 4.5 <noreply@anthropic.com>"

git push origin main
```

---

## Reference Documents

**Global standards:**
- `/home/nickg/ClaudeCode/GLOBAL-STANDARDS.md` - Writing standards, Nick's profile, agent architecture

**In Portfolio project:**
- `Portfolio/website-session-logs.md` - Original perspectives section planning (historical context)

---

## Version History

**2026-01-08 (Project Created):**
- Separated from monolithic JobHunting project
- Created as standalone Perspectives project
- Series 1 topics defined (3 pieces)
- Writing workflow established (7-step process)
- Personal agents ready (architecture-peer, content-critic, personal-marketeer, exec-recruiter)

---

**Last Updated:** 2026-01-08
**Project Owner:** Nick Gushlow
**Maintained By:** Claude Code + Nick
