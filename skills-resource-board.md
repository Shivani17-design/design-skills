# Skills Resource Board

> Invoke any skill with `/skill-name` in the Claude Code chat.

---

## Core / Utility

| Skill | Command | What it does |
|-------|---------|--------------|
| Update Config | `/update-config` | Configure Claude Code settings.json — permissions, hooks, env vars, automated behaviors |
| Keybindings Help | `/keybindings-help` | Customize keyboard shortcuts and rebind keys in `~/.claude/keybindings.json` |
| Simplify | `/simplify` | Review changed code for reuse, quality, and efficiency, then fix issues found |
| Fewer Permission Prompts | `/fewer-permission-prompts` | Scan transcripts for common tool calls and add an allowlist to reduce prompts |
| Loop | `/loop` | Run a prompt or slash command on a recurring interval (e.g. `/loop 5m /foo`) |
| Schedule | `/schedule` | Create, update, list, or run scheduled remote agents on a cron schedule |
| Claude API | `/claude-api` | Build, debug, and optimize Claude API / Anthropic SDK apps with prompt caching |
| Init | `/init` | Initialize a new project or workspace |
| Review | `/review` | Review code changes |
| Security Review | `/security-review` | Audit code for security vulnerabilities |

---

## Anthropic Skills

| Skill | Command | What it does |
|-------|---------|--------------|
| Schedule | `/anthropic-skills:schedule` | Schedule recurring remote agents |
| Setup Cowork | `/anthropic-skills:setup-cowork` | Set up collaborative working sessions |
| Consolidate Memory | `/anthropic-skills:consolidate-memory` | Clean up and consolidate memory files |
| XLSX | `/anthropic-skills:xlsx` | Work with Excel spreadsheet files |
| PDF | `/anthropic-skills:pdf` | Read, parse, or generate PDF files |
| DOCX | `/anthropic-skills:docx` | Work with Word document files |
| PPTX | `/anthropic-skills:pptx` | Work with PowerPoint presentation files |
| Skill Creator | `/anthropic-skills:skill-creator` | Create new custom skills |
| Design Review | `/anthropic-skills:design-review` | Run a structured design review |

---

## Design Research

| Skill | Command | What it does |
|-------|---------|--------------|
| Synthesize | `/design-research:synthesize` | Synthesize research findings into insights |
| Interview | `/design-research:interview` | Conduct or structure user interviews |
| Test Plan | `/design-research:test-plan` | Create a usability test plan |
| Discover | `/design-research:discover` | Run a discovery phase for a design problem |
| User Persona | `/design-research:user-persona` | Build detailed user personas |
| Usability Test Plan | `/design-research:usability-test-plan` | Draft a usability testing plan |
| Card Sort Analysis | `/design-research:card-sort-analysis` | Analyze results from a card sorting exercise |
| Journey Map | `/design-research:journey-map` | Create a user journey map |
| Diary Study Plan | `/design-research:diary-study-plan` | Plan a longitudinal diary study |
| Interview Script | `/design-research:interview-script` | Write a structured interview script |
| Summarize Interview | `/design-research:summarize-interview` | Summarize and extract key themes from an interview |
| Affinity Diagram | `/design-research:affinity-diagram` | Organize research data into an affinity diagram |
| Jobs to Be Done | `/design-research:jobs-to-be-done` | Frame user needs using the JTBD framework |
| Empathy Map | `/design-research:empathy-map` | Build an empathy map for a user segment |

---

## Design Systems

| Skill | Command | What it does |
|-------|---------|--------------|
| Tokenize | `/design-systems:tokenize` | Convert design values into design tokens |
| Audit System | `/design-systems:audit-system` | Audit an existing design system for gaps or inconsistencies |
| Create Component | `/design-systems:create-component` | Spec and scaffold a new design system component |
| Design Token | `/design-systems:design-token` | Define or document a design token |
| Theming System | `/design-systems:theming-system` | Plan a multi-theme or dark mode system |
| Component Spec | `/design-systems:component-spec` | Write a detailed component specification |
| Naming Convention | `/design-systems:naming-convention` | Establish naming conventions for tokens, components, or files |
| Pattern Library | `/design-systems:pattern-library` | Build or document a pattern library |
| Documentation Template | `/design-systems:documentation-template` | Create a documentation template for design system components |
| Icon System | `/design-systems:icon-system` | Design or audit an icon system |
| Accessibility Audit | `/design-systems:accessibility-audit` | Audit the design system for accessibility compliance |

---

## UX Strategy

| Skill | Command | What it does |
|-------|---------|--------------|
| Strategize | `/ux-strategy:strategize` | Define a high-level UX strategy |
| Benchmark | `/ux-strategy:benchmark` | Run a competitive or baseline benchmarking exercise |
| Frame Problem | `/ux-strategy:frame-problem` | Frame and articulate the core design problem |
| Design Principles | `/ux-strategy:design-principles` | Define guiding design principles |
| Design Brief | `/ux-strategy:design-brief` | Write a structured design brief |
| Competitive Analysis | `/ux-strategy:competitive-analysis` | Conduct a competitive analysis |
| Opportunity Framework | `/ux-strategy:opportunity-framework` | Map and prioritize design opportunities |
| North Star Vision | `/ux-strategy:north-star-vision` | Articulate a north star vision for the experience |
| Experience Map | `/ux-strategy:experience-map` | Create a high-level experience map |
| Metrics Definition | `/ux-strategy:metrics-definition` | Define success metrics for a design initiative |
| Stakeholder Alignment | `/ux-strategy:stakeholder-alignment` | Plan and facilitate stakeholder alignment |

---

## UI Design

| Skill | Command | What it does |
|-------|---------|--------------|
| Type System | `/ui-design:type-system` | Design a typography system |
| Color Palette | `/ui-design:color-palette` | Build a color palette |
| Responsive Audit | `/ui-design:responsive-audit` | Audit a UI for responsive design issues |
| Design Screen | `/ui-design:design-screen` | Design a specific screen or UI view |
| Layout Grid | `/ui-design:layout-grid` | Define a layout grid system |
| Illustration Style | `/ui-design:illustration-style` | Define an illustration style guide |
| Visual Hierarchy | `/ui-design:visual-hierarchy` | Analyze and improve visual hierarchy |
| Typography Scale | `/ui-design:typography-scale` | Build a modular typography scale |
| Color System | `/ui-design:color-system` | Design a complete color system with semantic tokens |
| Data Visualization | `/ui-design:data-visualization` | Design data visualization components or guidelines |
| Spacing System | `/ui-design:spacing-system` | Define a spacing and density system |
| Responsive Design | `/ui-design:responsive-design` | Plan responsive breakpoints and layouts |
| Dark Mode Design | `/ui-design:dark-mode-design` | Adapt a UI for dark mode |

---

## Interaction Design

| Skill | Command | What it does |
|-------|---------|--------------|
| Error Flow | `/interaction-design:error-flow` | Map and design error states and recovery flows |
| Design Interaction | `/interaction-design:design-interaction` | Design a specific interaction or micro-interaction |
| Map States | `/interaction-design:map-states` | Map all UI states for a component or flow |
| Animation Principles | `/interaction-design:animation-principles` | Define animation and motion principles |
| Gesture Patterns | `/interaction-design:gesture-patterns` | Design or document gesture-based interactions |
| Micro-Interaction Spec | `/interaction-design:micro-interaction-spec` | Spec a micro-interaction in detail |
| Error Handling UX | `/interaction-design:error-handling-ux` | Design the full error handling UX for a feature |
| Loading States | `/interaction-design:loading-states` | Design loading and skeleton states |
| State Machine | `/interaction-design:state-machine` | Model a UI as a state machine |
| Feedback Patterns | `/interaction-design:feedback-patterns` | Design feedback and confirmation patterns |

---

## Prototyping & Testing

| Skill | Command | What it does |
|-------|---------|--------------|
| Prototype Plan | `/prototyping-testing:prototype-plan` | Plan what to prototype and how |
| Experiment | `/prototyping-testing:experiment` | Design and run a design experiment |
| Evaluate | `/prototyping-testing:evaluate` | Evaluate a prototype or design decision |
| Test Plan | `/prototyping-testing:test-plan` | Write a research or usability test plan |
| Test Scenario | `/prototyping-testing:test-scenario` | Write specific test scenarios for user testing |
| Wireframe Spec | `/prototyping-testing:wireframe-spec` | Create a wireframe specification document |
| Accessibility Test Plan | `/prototyping-testing:accessibility-test-plan` | Plan accessibility testing for a feature |
| User Flow Diagram | `/prototyping-testing:user-flow-diagram` | Map out a user flow diagram |
| A/B Test Design | `/prototyping-testing:a-b-test-design` | Design an A/B test for a UX hypothesis |
| Click Test Plan | `/prototyping-testing:click-test-plan` | Plan a first-click or click test |
| Prototype Strategy | `/prototyping-testing:prototype-strategy` | Define the overall prototyping strategy |
| Heuristic Evaluation | `/prototyping-testing:heuristic-evaluation` | Run a heuristic evaluation of a UI |

---

## Design Ops

| Skill | Command | What it does |
|-------|---------|--------------|
| Plan Sprint | `/design-ops:plan-sprint` | Plan a design sprint |
| Setup Workflow | `/design-ops:setup-workflow` | Set up a team design workflow |
| Handoff | `/design-ops:handoff` | Prepare design handoff documentation |
| Team Workflow | `/design-ops:team-workflow` | Document or improve team design workflows |
| Design QA Checklist | `/design-ops:design-qa-checklist` | Create a design QA checklist |
| Version Control Strategy | `/design-ops:version-control-strategy` | Plan version control for design files |
| Design Review Process | `/design-ops:design-review-process` | Define a design review process |
| Design Sprint Plan | `/design-ops:design-sprint-plan` | Plan a full design sprint |
| Handoff Spec | `/design-ops:handoff-spec` | Write a developer handoff specification |
| Design Critique | `/design-ops:design-critique` | Run a structured design critique session |

---

## Designer Toolkit

| Skill | Command | What it does |
|-------|---------|--------------|
| Write Case Study | `/designer-toolkit:write-case-study` | Write a portfolio case study |
| Write Rationale | `/designer-toolkit:write-rationale` | Write a design rationale document |
| Build Presentation | `/designer-toolkit:build-presentation` | Build a design presentation |
| Design Rationale | `/designer-toolkit:design-rationale` | Document decision-making rationale for a design |
| Presentation Deck | `/designer-toolkit:presentation-deck` | Create a structured presentation deck |
| Case Study | `/designer-toolkit:case-study` | Build a full design case study |
| Design System Adoption | `/designer-toolkit:design-system-adoption` | Plan or track design system adoption |
| Design Token Audit | `/designer-toolkit:design-token-audit` | Audit existing design tokens for issues |
| UX Writing | `/designer-toolkit:ux-writing` | Write or improve UX copy and microcopy |

---

## Standalone Design Skills

| Skill | Command | What it does |
|-------|---------|--------------|
| Design Brief | `/design-brief` | Create a design brief for a project |
| Brief to Tasks | `/brief-to-tasks` | Break a design brief into actionable tasks |
| Design Tokens | `/design-tokens` | Generate or manage design tokens |
| Design Flow | `/design-flow` | Map a design flow end-to-end |
| Frontend Design | `/frontend-design` | Translate designs into frontend implementation guidance |
| Design Review | `/design-review` | Run a structured design review |
| Grill Me | `/grill-me` | Get challenged with hard questions about a design decision |
| Information Architecture | `/information-architecture` | Plan or audit the information architecture of a product |

---

*Total: 100+ skills across 10 categories*
