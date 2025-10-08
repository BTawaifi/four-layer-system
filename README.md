# Four-Layer Rules System

A comprehensive system for AI-assisted development workflows, organized into four main layers: Specialists, Modifiers, Contexts, and Workflows.

## Directory Structure

```
four-layer-system/
├── specialists/               # Domain expertise specialists (29 total)
│   ├── programming-languages/ # Language-specific developers
│   ├── cloud-platforms/       # Cloud architecture specialists
│   ├── data-ai/              # Data science and ML specialists
│   ├── business-tech/        # Business and UX specialists
│   └── infrastructure/       # DevOps and infrastructure specialists
├── modifiers/                # Behavioral modifiers and constraints (24 total)
│   ├── output-behavior/      # Response style modifiers
│   ├── approach-philosophy/  # Development approach modifiers
│   ├── technology-specific/  # Framework/technology modifiers
│   └── system/               # System-level modifiers
├── contexts/                 # Session and workflow contexts (11 total)
│   ├── information-flow/     # Data and information management
│   ├── state-management/     # Task and goal tracking
│   ├── process-management/   # Workflow orchestration
│   └── ide-optimization/     # Cursor IDE-specific optimizations ⭐ NEW
├── workflows/                # Multi-step development workflows (124 total)
│   ├── analysis/             # Code analysis and review workflows
│   │   ├── accessibility/    # Web accessibility audits and compliance
│   │   ├── code-analysis/    # Code review, health checks, and type safety
│   │   ├── security/         # Security audits and risk assessments
│   │   ├── performance/      # Performance audits and profiling
│   │   ├── system/           # System audits, architecture reviews, business analysis
│   │   └── meta/             # Meta-workflow analysis and auditing
│   ├── creation/             # Content and code generation workflows
│   ├── debugging/            # Issue diagnosis and resolution workflows
│   ├── development/          # Full development lifecycle workflows
│   │   ├── ai-ml/            # AI/ML development, data prep, and MLOps
│   │   ├── blockchain/       # Smart contracts, Web3 frontend, blockchain deployment
│   │   ├── infrastructure/   # CI/CD, project setup, system migration
│   │   ├── product/          # Product roadmaps, feature development, technical debt
│   │   ├── api/              # API development workflows
│   │   └── general/          # General development and application workflows
│   ├── documentation/        # Documentation creation workflows
│   │   └── progressive/      # Session-based documentation workflows
│   ├── governance/           # Project governance and compliance workflows
│   ├── investigation/        # System investigation and exploration workflows
│   ├── meta/                 # Meta-workflows for system management
│   ├── project-management/   # Project planning and coordination workflows
│   ├── quality-assurance/    # Testing, verification, and implementation workflows
│   │   ├── testing/          # Test generation, strategies, and structures
│   │   ├── verification/     # ML verification and finding reverification
│   │   ├── implementation/   # Report remedies and hook creation
│   │   └── hooks/            # Automated quality assurance hooks
│   ├── refactoring/          # Code refactoring and optimization workflows
│   └── session-management/   # Session recovery and synchronization
├── templates/                # Communication and protocol templates (8 total
│   └── multi-agent/          # Multi-agent collaboration templates
│       ├── session_state_template.mdc     # Session coordination
│       ├── findings_template.mdc          # Analysis documentation
│       ├── handover_protocol_template.mdc # Agent transitions
│       ├── quality_monitoring_template.mdc # Quality assurance
│       ├── example_session_workflow.mdc   # Working example
│       └── protocols/                     # Specific handover protocols
├── quality-standards/        # Quality checklists and guidelines (3 total)
│   ├── quality-checklist-specialists.mdc  # Specialist validation
│   ├── quality-checklist-workflows.mdc    # Workflow validation
│   └── quality-review-process.mdc         # Review methodology
├── quality-automation/       # Automated quality validation (2 total)
│   ├── workflow-content-quality-automation.mdc # Automation workflow
│   └── quality-validation-script.mdc           # Validation engine
└── performance-monitoring/   # Performance tracking and optimization (2 total)
    ├── workflow-performance-monitoring-integration.mdc # Monitoring workflow
    └── performance-dashboard-template.mdc              # Dashboard template
```

### 🚨 Important Warnings

#### Do Not Skip IDE Optimization
**Critical**: Complex workflows without IDE optimization contexts will likely exceed token limits and cause session failures. Always initialize appropriate contexts before starting complex work.

#### Quality Automation is Mandatory
**Critical**: All content must pass quality validation before use. Skipping quality checks significantly increases the risk of errors and reduces system effectiveness.

#### Monitor Performance Continuously
**Important**: Performance issues can cascade rapidly in complex workflows. Regular monitoring and prompt response to alerts is essential for maintaining system reliability.

#### Use Multi-Agent Protocols
**Important**: When collaborating with multiple agents, always use standardized handover protocols to ensure state consistency and prevent work loss.

## How to Use

### 🚀 Enhanced Usage Patterns

#### For Simple Tasks (Quick Implementation)
```bash
# Basic four-layer combination
@specialist-[domain]-expert @modifier-[behavior] @workflow-[task]
```

**Example:**
```
@specialist-python-developer @modifier-performance-critical @workflow-ml-data-preparation
```

#### For Complex Workflows (Enterprise Implementation)
```bash
# 1. Initialize IDE optimization contexts
@context-cursor-session-workflow-manager "[project-name]" "[duration]" "[complexity]"

# 2. Enable token and quality optimization
@context-token-efficiency-manager "[budget]" "[content-type]" "[quality]"

# 3. Execute enhanced workflow with monitoring
@workflow-[enhanced-workflow] --quality-monitoring --performance-tracking

# 4. Use multi-agent protocols for collaboration
@protocol-[appropriate-handover] [transition-details]
```

**Enterprise Example:**
```
@context-cursor-session-workflow-manager "Enterprise ML Platform" "12 sessions" "critical"
@context-token-efficiency-manager "premium" "technical" "production"
@workflow-fullstack-web-development --multi-agent --quality-gate
```

### 🎯 Rule Selection Guide

#### Specialists by Domain (29 Total)
- **Programming Languages** (8): Python, JavaScript, Go, Rust, Java, .NET, iOS, Android
- **Cloud Platforms** (3): AWS Architect, Azure Architect, GCP Architect
- **Data & AI** (6): Data Engineer, Data Scientist, ML Researcher, Quantitative Analyst, PostgreSQL Admin, ML Auditor
- **Business & Tech** (5): Product Manager, Business Analyst, UX Designer, Technical Writer, UX Researcher
- **Infrastructure** (7): Backend Developer, Frontend Developer, DevOps Engineer, Security Auditor, QA Tester, Database Administrator, Senior Software Engineer

#### Modifiers by Category (24 Total)
- **Output Behavior** (5): Concise, Verbose, Code-Only, Explain Like I'm Five, Sanitized
- **Approach Philosophy** (7): Performance Critical, Conservative, Experimental, Production ML Mindset, Backward Compatible, Cloud Agnostic, No New Dependencies
- **Technology Specific** (7): React Best Practices, Angular Standards, API Design, Mobile First, Target Language Version, Compatibility Matrix, Experimental Mode
- **System** (5): Think Step-by-Step, Ask Clarifying Questions, Read-Only Mode, Output Format, Verbose Output

#### Contexts by Purpose (11 Total)
- **Information Flow** (4): Establish Aliases, Filter Apply Lens, Flush and Focus, Load Supplementary Info, Set Ground Truth
- **State Management** (2): Define Task List, Set Primary Goal
- **Process Management** (1): Workflow Progress Tracker
- **IDE Optimization** (4): ⭐ NEW - Session Workflow Manager, Token Efficiency Manager, Progressive Context Loader, Enhanced Flush and Focus

#### Workflows by Category (124 Total)
- **Analysis** (25): Security audits, performance profiling, accessibility, code analysis, system audits
- **Creation** (9): Full-stack development, content generation, API development
- **Debugging** (11): Issue diagnosis, root cause analysis, debugging workflows
- **Development** (34): AI/ML pipelines, blockchain, infrastructure, product development, API workflows
- **Documentation** (9): Technical writing, progressive documentation ⭐ NEW
- **Quality Assurance** (18): Testing strategies, verification, implementation, hooks
- **Session Management** (2): Recovery and synchronization ⭐ NEW
- **Other Categories** (16): Governance, investigation, meta, project management, refactoring

## Contributing

When adding new rules:
1. Follow the established naming convention: `type-descriptive-name.mdc`
2. Include proper YAML frontmatter with `alwaysApply` and `description` fields
3. Place files in the appropriate subdirectory based on their category
4. Update cross-references if adding new rule types