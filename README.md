
# Effective Specialized AI Agents

A collection of highly specialized AI agent prompts designed to work collaboratively in a multi-agent environment. Built for creating an **Arabic-first Middle Eastern happiness and well-being mobile application**, these agents can be adapted for any complex product development workflow requiring diverse expertise.

## 🎯 Philosophy

Modern AI systems achieve their best results through **specialized agents working collaboratively**, not monolithic general-purpose agents. This repository implements a multi-agent architecture where:

- **Each agent is a deep specialist** in one domain (product strategy, clinical psychology, UX design, etc.)
- **Agents collaborate through structured workflows** (sequential, parallel, iterative)
- **An orchestrator coordinates** agent invocation and synthesizes outputs
- **Transparency is maintained** - you see individual agent reasoning and unified recommendations

## 🏗️ Architecture

### Multi-Agent Collaboration Model

```
User Request
    ↓
Orchestrator Agent (routes & coordinates)
    ↓
┌─────────────────────────────────────────────────┐
│  Specialized Agents (invoked as needed)         │
├─────────────────────────────────────────────────┤
│  • Innovation & Ideation Specialist             │
│  • Product Manager                              │
│  • Clinical Psychologist                        │
│  • UX/UI Designer                               │
│  • Devil's Advocate                             │
│  • Arabic Language & Content Specialist         │
│  • MVP & Hypothesis Testing Specialist          │
└─────────────────────────────────────────────────┘
    ↓
Synthesized Recommendation + Individual Perspectives
    ↓
User Decision
```

### Workflow Patterns

**Sequential** (for dependencies):
```
Innovation → MVP Testing → Product Manager → Implementation
```

**Parallel** (for independent analysis):
```
                    ┌─ Clinical Psychologist
Innovation Idea → ──┼─ Devil's Advocate
                    ├─ UX Designer
                    └─ Arabic Language Specialist
→ Synthesize → Decision
```

**Iterative** (for refinement):
```
Innovation → Devil's Advocate (challenges) →
Innovation (refines) → MVP Testing (validates) →
Product Manager (decides)
```

## 🤖 Agent Directory

### 1. **Orchestrator Agent** 
**Path**: `orchestration/Orchestrator-Agent_Multi-Agent-Workflow-Coordinator.md`

**Role**: Central coordinator that routes requests, manages workflows, synthesizes outputs, and resolves conflicts.

**When to use**: 
- Default entry point for all requests
- Complex requests requiring multiple agents
- When you need synthesized recommendations from multiple perspectives

**Key capabilities**:
- Request classification (feature request, validation, review, ideation)
- Agent routing (sequential, parallel, iterative)
- Output synthesis and conflict resolution
- Context management across multi-turn conversations

---

### 2. **Innovation & Ideation Specialist**
**Path**: `innovation/Innovation-Ideation-Specialist_Creative-Problem-Solver.md`

**Role**: Generates creative ideas, discovers opportunities, and proposes new features for the happiness application.

**When to use**:
- Customer feature requests
- Proactive opportunity discovery
- Brainstorming new capabilities
- Exploring "what if" scenarios

**Key capabilities**:
- Generate 10+ diverse ideas per request
- Discover unmet needs customers haven't articulated
- Apply well-being trends and Middle Eastern cultural insights
- Align ideas with 4 Pillars Framework (Emotional, Physical, Spiritual, Social)

---

### 3. **Product Manager**
**Path**: `product/PM-Agent-Prompt_B2C-Mobile-Principal.md`

**Role**: Prioritizes features, assesses business viability, manages roadmap, and makes strategic decisions.

**When to use**:
- Feature prioritization
- Business case evaluation
- Roadmap planning
- Strategic alignment decisions

**Key capabilities**:
- Assess market fit and competitive positioning
- Prioritize based on strategic value
- Balance business goals with user needs
- Make go/no-go decisions

---

### 4. **Clinical Psychologist**
**Path**: `psychology/Happiness-Psychologist-Agent_Arabic-ME-Wellbeing.md`

**Role**: Validates therapeutic appropriateness, ensures psychological safety, and designs evidence-based interventions.

**When to use**:
- Validating psychological content
- Designing therapeutic exercises
- Ensuring clinical appropriateness
- Addressing mental health concerns

**Key capabilities**:
- Apply CBT, mindfulness, and positive psychology principles
- Validate therapeutic efficacy
- Ensure cultural sensitivity in psychological content
- Design interventions aligned with 4 Pillars Framework

---

### 5. **UX/UI Designer**
**Path**: `design/UX-UI-Designer-Agent_Arabic-RTL-Wellbeing.md`

**Role**: Designs interfaces, ensures minimal-click architecture, validates usability, and creates design systems.

**When to use**:
- UI/UX design and review
- Interaction pattern validation
- Design system creation
- Usability testing

**Key capabilities**:
- Minimal-click architecture (max 2-level navigation depth)
- Arabic RTL-first design
- Calming, tranquil aesthetics
- Accessibility compliance (WCAG AA)

---

### 6. **Devil's Advocate**
**Path**: `strategy/Devils-Advocate-Agent_Critical-Analysis-Gap-Detection.md`

**Role**: Challenges assumptions, identifies risks, finds gaps, and strengthens proposals through critical analysis.

**When to use**:
- Validating assumptions
- Risk assessment
- Gap detection
- Challenging groupthink

**Key capabilities**:
- Map and challenge assumptions
- Generate edge cases and failure modes
- Multi-perspective analysis (user, business, technical, cultural, ethical)
- Constructive critique with alternatives

---

### 7. **Arabic Language & Content Specialist**
**Path**: `content/Arabic-Language-Content-Specialist_ME-Wellbeing.md`

**Role**: Ensures linguistic excellence, cultural authenticity, readability, and emotional resonance in Arabic content.

**When to use**:
- Arabic content creation
- Translation and localization
- Content review and refinement
- Cultural validation

**Key capabilities**:
- Clear, accessible Arabic for diverse literacy levels
- Balance Modern Standard Arabic with Gulf dialect warmth
- Calming, empathetic, therapeutic tone
- Cultural authenticity without stereotypes

---

### 8. **MVP & Hypothesis Testing Specialist**
**Path**: `validation/MVP-Hypothesis-Testing-Specialist_Rapid-Validation.md`

**Role**: Designs experiments, validates assumptions, and provides evidence-based recommendations.

**When to use**:
- Validating product ideas
- Designing experiments
- User research
- Data-driven decision making

**Key capabilities**:
- Lean experiment design (concierge MVPs, Wizard of Oz, landing pages, A/B tests)
- Hypothesis formulation with clear success criteria
- Rapid prototyping (Figma, no-code tools)
- Cultural adaptation for Middle Eastern user research

---

## 🚀 Getting Started

### Option 1: Use the Orchestrator (Recommended)

**For most requests**, start with the Orchestrator Agent:

1. Copy the Orchestrator Agent prompt into your AI tool
2. Provide your request (e.g., "I want to add voice-based mood journaling")
3. The Orchestrator will automatically route to appropriate agents and synthesize outputs

**Example**:
```
User: "I want to add voice-based mood journaling in Arabic"

Orchestrator: 
- Routes to Innovation Specialist (generate ideas)
- Routes to Product Manager (assess strategic fit)
- Routes to Devil's Advocate (challenge assumptions)
- Routes to MVP Testing Specialist (design validation)
- Routes to Clinical Psychologist, UX Designer, Arabic Language Specialist (parallel refinement)
- Synthesizes outputs and provides unified recommendation
```

### Option 2: Direct Agent Invocation (Advanced)

**For specific needs**, directly use individual agents:

1. Copy the specific agent prompt into your AI tool
2. Provide context (application focus, target users, constraints)
3. Ask your question
4. Follow agent's recommendations for consulting other agents

**Example**:
```
User: "Review this Arabic notification copy for a 3-day streak"

Arabic Language Specialist:
- Reviews linguistic quality
- Assesses cultural authenticity
- Recommends consulting Clinical Psychologist for therapeutic tone validation
```

## 📋 Common Workflows

### Workflow 1: New Feature Request

```
1. User → Orchestrator: "I want to add [feature]"
2. Orchestrator → Innovation Specialist: Generate ideas
3. Orchestrator → Product Manager: Prioritize ideas
4. Orchestrator → Devil's Advocate: Challenge assumptions
5. Orchestrator → MVP Testing Specialist: Design validation
6. Orchestrator → Domain Agents (parallel): Refine validated ideas
7. Orchestrator → User: Synthesized recommendation
```

### Workflow 2: Proactive Innovation

```
1. User → Orchestrator: "What new features should we build?"
2. Orchestrator → Innovation Specialist: Discover opportunities
3. Orchestrator → Product Manager: Assess strategic fit
4. Orchestrator → Devil's Advocate: Challenge assumptions
5. Orchestrator → MVP Testing Specialist: Validate top ideas
6. Orchestrator → User: Prioritized recommendations
```

### Workflow 3: Design/Content Review

```
1. User → Orchestrator: "Review this [design/content]"
2. Orchestrator → Relevant Specialist (UX Designer or Arabic Language Specialist): Lead review
3. Orchestrator → Clinical Psychologist (parallel): Validate therapeutic appropriateness
4. Orchestrator → Devil's Advocate (parallel): Challenge assumptions
5. Orchestrator → User: Synthesized feedback
```

### Workflow 4: Rapid Validation

```
1. User → Orchestrator: "Should we build this?"
2. Orchestrator → Devil's Advocate: Challenge assumptions
3. Orchestrator → MVP Testing Specialist: Design validation
4. Orchestrator → Product Manager: Assess strategic fit
5. Orchestrator → User: Go/no-go recommendation
```

## 🎨 Application Context

These agents are designed for an **Arabic-first Middle Eastern happiness and well-being mobile application** with:

- **Target users**: Middle Eastern professionals aged 30-60
- **4 Pillars Framework**: Emotional, Physical, Spiritual, Social well-being
- **Core principles**: Simplicity, Cultural Resonance, Inclusivity
- **Design philosophy**: Minimal-click architecture, tranquil aesthetics, RTL-first
- **Cultural context**: Middle Eastern values, Islamic cultural sensitivity, family-centric

**Adaptation**: While built for this specific application, these agent prompts can be adapted for any complex product requiring diverse expertise. Simply update the "Application Context" sections in each prompt.

## 🔧 Customization

### Adding New Agents

1. Create new agent prompt following the template structure:
   - Role & Mission
   - Agentic Capabilities
   - Multi-Agent Collaboration Framework
   - Context Requirements
   - Reasoning Framework
   - Core Competencies
   - Core Principles
   - Response Framework
   - Example Scenarios

2. Update Orchestrator Agent to include new agent in routing rules

3. Update this README with new agent description

### Modifying Existing Agents

Each agent prompt is self-contained and can be modified independently. Key sections to customize:

- **Context Requirements**: Update for your application domain
- **Core Principles**: Adjust to your product values
- **Example Scenarios**: Replace with domain-specific examples
- **Multi-Agent Collaboration Framework**: Update agent references as needed

## 📚 Best Practices

### 1. **Start with the Orchestrator**
Let the Orchestrator handle routing and synthesis for complex requests. Only use direct agent invocation when you have specific, focused needs.

### 2. **Provide Rich Context**
Agents perform best with clear context:
- Application focus and target users
- Constraints (technical, cultural, business)
- Success criteria
- Previous agent outputs (if applicable)

### 3. **Embrace Iteration**
Multi-agent collaboration is iterative:
- Innovation generates ideas
- Devil's Advocate challenges
- Innovation refines
- MVP Testing validates
- Product Manager decides

### 4. **Respect Domain Hierarchy**
When agents conflict:
- **Clinical Psychologist** overrides on therapeutic appropriateness
- **Arabic Language Specialist** overrides on cultural authenticity
- **UX Designer** overrides on usability/accessibility
- **Product Manager** makes final strategic decisions

### 5. **Validate Before Building**
Always route ideas through MVP Testing Specialist before full implementation. Fast, cheap experiments save time and resources.
---

**Questions or feedback?** Open an issue or reach out directly.

**Ready to build?** Start with the Orchestrator Agent and let the multi-agent system guide you to better product decisions.
