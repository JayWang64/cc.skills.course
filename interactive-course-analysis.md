# Interactive Course Transformer: Content Analysis

## Source Material
"The Complete Guide to Building Skills for Claude" — Anthropic's 32-page official guide (January 2026)

---

## Phase 1: Content Analysis

### 1. Core Transformation
**From:** Someone who has never built a Claude Skill and sees it as abstract/complex
**To:** Someone who has a fully structured, deployable Skill folder with SKILL.md, proper YAML frontmatter, clear instructions, and a testing plan — ready to upload and iterate

### 2. Key Frameworks (7 total)

1. **Progressive Disclosure Architecture** — The three-level information loading system (YAML frontmatter → SKILL.md body → linked files) that minimizes token usage while maintaining expertise
2. **Skill Folder Anatomy** — The required structure: SKILL.md + optional scripts/, references/, assets/ directories with strict naming conventions (kebab-case, case-sensitive)
3. **YAML Frontmatter Design** — The "most important part" — writing name + description fields that control when Claude loads your skill (trigger phrases, what/when pattern)
4. **Three Use Case Categories** — Document & Asset Creation, Workflow Automation, MCP Enhancement — the mental model for what kind of skill you're building
5. **Five Workflow Patterns** — Sequential Orchestration, Multi-MCP Coordination, Iterative Refinement, Context-Aware Tool Selection, Domain-Specific Intelligence
6. **Testing Triangle** — Triggering tests (does it load?), Functional tests (does it work?), Performance comparison (is it better?)
7. **The Kitchen Analogy** — MCP = professional kitchen (tools/ingredients), Skills = recipes (instructions on how to create something valuable)

### 3. Exercises (Explicit and Implicit)

- **Define 2-3 concrete use cases** before writing any code (explicitly stated)
- **Write a use case definition** with trigger, steps, and result (explicit template provided)
- **Create the folder structure** with proper naming (implicit — they describe the structure but don't force you to build it)
- **Write the YAML frontmatter** with description field using what/when pattern (explicitly emphasized as "most important part")
- **Write main instructions** in the recommended structure (explicit template)
- **Run triggering tests** — write "should trigger" and "should NOT trigger" lists (explicit)
- **Run functional tests** — define given/when/then scenarios (explicit)
- **Compare performance** — with vs. without skill (explicit)
- **Write an installation guide** (explicit template provided)
- **Position your skill** — write outcome-focused description (explicit good/bad examples)

### 4. Common Objections & Resistance

1. "I don't know what use case to build for" — paralysis before starting
2. "My description is fine" — writing vague descriptions like "Helps with projects"
3. "I'll just put everything in SKILL.md" — ignoring progressive disclosure, making the skill too large
4. "Testing seems like overkill" — skipping the triggering/functional test phase
5. "I don't have an MCP server so skills aren't for me" — not realizing Category 1 (Document & Asset Creation) needs no MCP at all
6. "I'll figure out distribution later" — not thinking about how others will find and install the skill

### 5. Deliverable

A complete, uploadable Skill folder containing:
- Properly named folder (kebab-case)
- SKILL.md with valid YAML frontmatter (name + description with trigger phrases)
- Written main instructions with step-by-step workflow, examples, and troubleshooting
- A triggering test plan (5+ "should trigger" queries, 3+ "should NOT trigger" queries)
- A one-paragraph positioning statement (outcome-focused)

### 6. Voice/Tone

The original guide is **technical but approachable, documentation-style**. Key phrases:
- "A skill is a set of instructions—packaged as a simple folder—that teaches Claude how to handle specific tasks or workflows"
- "Think of it like Home Depot"
- "The most effective skill creators iterate on a single challenging task until Claude succeeds, then extract the winning approach into a skill"
- "If you already have a working MCP server, you've done the hard part"
- "Skills are living documents"
- Uses tables for comparison, provides good/bad examples side by side
- Direct but not aggressive — workshop instructor energy, not drill sergeant

**Transformation tone target:** Direct, no-BS workshop-style. Push harder than the original — the guide is reference material, the lesson is a working session.

---

## Phase 2: See `interactive-course-prompt.md`

## Phase 3: Quality Check Notes — See bottom of `interactive-course-prompt.md`
