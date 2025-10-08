# Progressive Documentation Workflows

This directory contains documentation workflows designed specifically for Cursor IDE's session-based constraints. These workflows break complex documentation tasks into focused, time-limited sessions that preserve context across multiple IDE sessions.

## Available Progressive Workflows

### 1. Progressive API Documentation (`workflow-progressive-api-documentation.mdc`)
**Target Documentation:** REST APIs, GraphQL APIs, gRPC services, WebSocket APIs
**Session Count:** 6 focused sessions (30-90 minutes each)
**Total Time:** 4-6 hours over multiple days/weeks

**Session Breakdown:**
- **Session 1:** Foundation & Structure (API purpose, technical foundation, architecture)
- **Session 2:** Endpoint Inventory & Basics (endpoint catalog, request/response patterns)
- **Session 3:** Detailed Endpoint Documentation (high-priority endpoints, auth patterns)
- **Session 4:** Advanced Features & Edge Cases (bulk operations, real-time features)
- **Session 5:** Testing, Examples & Validation (code examples, testing strategies)
- **Session 6:** Publication & Maintenance Setup (publication prep, maintenance processes)

### 2. Progressive System Architecture Documentation (`workflow-progressive-system-architecture-docs.mdc`)
**Target Documentation:** System architecture, technical design, architectural decisions
**Session Count:** 6 focused sessions (45-75 minutes each)
**Total Time:** 5-7 hours over multiple days/weeks

**Session Breakdown:**
- **Session 1:** Architecture Vision & Context (business context, requirements, quality attributes)
- **Session 2:** Component & Data Architecture (system decomposition, technology stack)
- **Session 3:** Detailed Data & Integration Architecture (data models, integration patterns)
- **Session 4:** Runtime & Deployment Architecture (operational architecture, deployment patterns)
- **Session 5:** Architecture Validation & Decision Documentation (ADRs, requirements traceability)
- **Session 6:** Implementation Guidance & Documentation Assembly (developer guidelines, publication)

## Progressive Documentation Principles

### Session Design Philosophy
1. **Focused Scope:** Each session has a clear, achievable objective
2. **Time-Bound:** Sessions designed for 30-90 minute completion
3. **Quality Gates:** Each session includes validation checkpoints
4. **Context Preservation:** File-based state management across sessions
5. **Incremental Building:** Each session enhances previous work

### Cursor IDE Optimization
1. **Token Management:** Smaller sessions prevent context window exhaustion
2. **Memory Efficiency:** File-based context reduces conversation burden
3. **Session Recovery:** Clear state enables seamless continuation
4. **Quality Monitoring:** Built-in checkpoints ensure consistent progress

## When to Use Progressive Workflows

### Ideal Scenarios
- **Complex Documentation:** Projects requiring comprehensive documentation
- **Limited Session Time:** When you have only 30-90 minutes per session
- **High-Quality Requirements:** When documentation must meet professional standards
- **Team Collaboration:** When multiple people contribute to documentation
- **Frequent Interruptions:** When work sessions are regularly interrupted

### Best Suited For
- **API Documentation:** Technical specifications with examples and testing
- **System Architecture:** Complex technical design documentation
- **Large Codebases:** Comprehensive code documentation projects
- **Enterprise Software:** Documentation requiring formal processes
- **Open Source Projects:** Community-contributed documentation

## Workflow Execution Guide

### Preparation (Before First Session)
1. **Define Scope:** Clearly outline what needs to be documented
2. **Assess Current State:** Evaluate existing documentation and gaps
3. **Schedule Sessions:** Plan realistic session times and frequencies
4. **Prepare Environment:** Set up necessary tools and access
5. **Create State File:** Initialize session state tracking

### Session Execution Pattern
1. **Review Previous State:** Load and review progress from last session
2. **Set Session Goals:** Confirm specific objectives for current session
3. **Execute Work:** Complete the focused documentation tasks
4. **Quality Validation:** Apply session-specific quality checkpoints
5. **State Preservation:** Save progress and prepare for next session

### Session Transition Protocol
**End of Session:**
- Save all work with clear file naming
- Update session state with progress and next objectives
- Document any blocking issues or dependencies
- Note quality validation results

**Start of Next Session:**
- Review session state and previous deliverables
- Load relevant context files and documentation
- Verify environment and tool availability
- Begin work with clear session objectives

## File Organization and Naming

### Standard Directory Structure
```
documentation_project/
├── session_state.md                    # Current progress tracking
├── deliverables/                       # Completed documentation sections
│   ├── api_foundation_2025-09-22.md
│   ├── api_endpoints_basic_2025-09-23.md
│   └── api_endpoints_detailed_2025-09-24.md
├── drafts/                             # Working documents
├── reviews/                            # Quality reviews and feedback
└── archive/                            # Previous versions and superseded docs
```

### File Naming Convention
```
[content_type]_[component]_[detail]_[YYYY-MM-DD].md
```

**Examples:**
- `api_foundation_context_2025-09-22.md`
- `arch_components_data_2025-09-23.md`
- `guide_testing_examples_2025-09-24.md`

### Session State File Format
```markdown
# Documentation Progress State
**Project:** [Project Name]
**Workflow:** [Workflow Type - API/System Architecture/etc.]
**Last Session:** [Session Number - Description]
**Completion Percentage:** [X%]
**Next Session:** [Number - Brief Description]
**Open Items:** [Bullet list of remaining work]
**Quality Score:** [X/10 - Brief justification]
**Blockers:** [Any issues preventing progress]
```

## Quality Assurance Integration

### Session Quality Checkpoints
Each session includes specific quality validation:
- **Content Completeness:** Required sections and information covered
- **Technical Accuracy:** Information verified and up-to-date
- **Clarity and Readability:** Language appropriate for target audience
- **Consistency:** Alignment with previous sessions and overall documentation
- **Practical Value:** Documentation provides actionable information

### Cross-Session Validation
- **Continuity Review:** New content aligns with previous sessions
- **Reference Accuracy:** Links and references remain valid
- **Scope Adherence:** Documentation stays within defined boundaries
- **Progress Validation:** Measurable advancement toward completion

## Customization Guidelines

### Adapting for Different Documentation Types
- **User Guides:** Add more screenshots and step-by-step instructions
- **Technical Specifications:** Emphasize detailed technical requirements
- **Process Documentation:** Include workflow diagrams and decision trees
- **Compliance Documentation:** Add regulatory requirement validation

### Scaling for Project Size
- **Small Projects:** Combine sessions or reduce depth of coverage
- **Large Projects:** Split sessions further or add parallel tracks
- **Enterprise Projects:** Include additional compliance and governance sessions

### Team Collaboration Adjustments
- **Multiple Contributors:** Add session ownership and review checkpoints
- **Distributed Teams:** Emphasize file-based communication and async reviews
- **Cross-Functional Teams:** Include stakeholder validation sessions

## Success Metrics and Monitoring

### Session Effectiveness Metrics
- **Completion Rate:** Percentage of sessions completed on schedule
- **Quality Scores:** Average quality checkpoint scores across sessions
- **Time Adherence:** Sessions completed within planned timeframes
- **Context Preservation:** Smooth transitions between sessions

### Documentation Quality Metrics
- **Completeness:** All planned sections and topics covered
- **Accuracy:** Technical information verified and current
- **Usability:** Documentation effectively used by target audience
- **Maintenance:** Documentation remains current and useful

### Cursor IDE Compatibility Metrics
- **Session Recovery:** Successful continuation across IDE sessions
- **Token Efficiency:** No context window limitations encountered
- **Memory Management:** No conversation memory issues
- **Quality Continuity:** Consistent quality across session boundaries

## Troubleshooting and Best Practices

### Common Challenges
**Session Time Overruns:**
- Break large tasks into smaller, focused subtasks
- Use time-boxing techniques (25-minute pomodoro sessions)
- Prepare materials in advance to maximize productive time

**Context Loss Between Sessions:**
- Always update session state files before ending session
- Use clear file naming and location conventions
- Maintain summary documents for quick context refresh

**Quality Inconsistencies:**
- Apply consistent quality checklists across all sessions
- Include cross-session review checkpoints
- Maintain style guides and templates

**Scope Creep:**
- Revisit project scope at the start of each session
- Use session objectives to maintain focus
- Document scope change decisions explicitly

### Optimization Strategies
**Session Preparation:**
- Review previous session deliverables before starting
- Prepare reference materials and templates in advance
- Set clear success criteria for the session

**During Session Execution:**
- Take brief notes on key decisions and open questions
- Save work frequently with clear version markers
- Use templates and checklists to maintain consistency

**Session Completion:**
- Validate work against quality checkpoints
- Update all relevant state and tracking files
- Prepare clear objectives for the next session
- Document any blockers or dependencies

## Integration with Other Templates

### Multi-Agent Templates
- Use session state files to coordinate with other documentation contributors
- Apply handover protocols when transitioning between documentation phases
- Leverage quality monitoring templates for documentation validation

### Workflow Integration
- Progressive documentation works well with development workflows
- Can be integrated into CI/CD processes for automated validation
- Supports agile documentation practices with iterative improvement

These progressive workflows enable comprehensive, high-quality documentation while working effectively within Cursor IDE's session-based constraints and maintaining productivity across multiple work sessions.
