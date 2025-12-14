# Copilot Instructions – Journey Inspired Platform

## Repository Role
This is a strategic, documentation-first platform repository.
Accuracy, clarity, and auditability are mandatory.

## Project Context
**Journey Inspired Platform** is an enterprise-grade digital travel concierge platform covering three tourism domains:
- **Health & Wellness Tourism**: Medical services, wellness retreats, therapeutic travel
- **Education Tourism**: Study abroad, educational exchanges, skills development travel
- **Property Tourism**: Real estate exploration, investment tours, relocation services

This repository serves as the system-of-record for:
- Architecture documentation and design decisions
- Governance framework and compliance requirements
- Grant-related documentation and stakeholder communications
- AI-assisted development workflows and standards

**Stakeholder Context**: Outputs must align with grant applications, regulatory compliance reviews, and executive stakeholder presentations.

## Repository Structure
```
journey-inspired-platform/
├── .github/
│   └── copilot-instructions.md    # This file
├── README.md                        # Project overview
└── docs/                            # (To be created) Detailed documentation
```

## Getting Started

### For Copilot Agents
1. Read this file completely before making any changes
2. Review README.md for project overview
3. Check existing documentation in /docs (when created)
4. When in doubt, prioritize documentation accuracy over speed

### Prerequisites
- Understanding of enterprise documentation standards
- Familiarity with markdown formatting conventions
- Context awareness for grant/compliance environments

## Expectations
- Follow enterprise software documentation standards
- Prefer explicit structure over assumptions
- Align outputs to grant, compliance, and stakeholder review contexts
- Maintain professional, audit-ready documentation quality
- Use clear, unambiguous language suitable for non-technical stakeholders

## Prohibited
- No speculative features or roadmap items without explicit approval
- No framework sprawl or technology selection without documentation
- No undocumented architectural changes or decisions
- No placeholder content or "TODO" markers in committed documentation
- No assumptions about user requirements or business priorities

## Documentation Standards

### Format Requirements
- Use standard markdown (.md) format
- Follow consistent heading hierarchy (H1 for title, H2 for major sections, H3 for subsections)
- Include table of contents for documents longer than 3 sections
- Use bullet points for lists, numbered lists for sequential steps
- Include last-updated date at the bottom of major documents

### Content Requirements
- Write in clear, professional language
- Define acronyms on first use
- Include context and rationale, not just technical details
- Cross-reference related documents using relative links
- Ensure all statements are verifiable and traceable

### Review Process
- All documentation changes require review before merge
- Major architectural decisions require explicit stakeholder approval
- Compliance-related content must be validated for accuracy
- Grant-related materials follow stricter review protocols

## Git Workflow

### Branching Strategy
- Create feature branches from main: `feature/<descriptive-name>`
- Use descriptive branch names: `docs/add-architecture-overview`
- Keep branches focused on a single topic or issue

### Commit Messages
- Use clear, descriptive commit messages
- Format: `<type>: <short description>`
- Types: `docs:`, `fix:`, `refactor:`, `chore:`
- Example: `docs: Add architecture decision record for database selection`

### Pull Requests
- Reference related issues in PR description
- Provide context and rationale for changes
- Request review from appropriate stakeholders
- Ensure all documentation is complete before requesting merge

## Documentation Discipline
- All major changes must update README or /docs
- Create Architecture Decision Records (ADRs) for significant choices
- Update this copilot-instructions.md file when workflow changes
- Maintain changelog for version-controlled documentation releases

## When to Ask for Clarification

### Always Ask When:
- Requirements conflict with prohibited actions
- Stakeholder context is ambiguous or missing
- Technical decisions require architectural approval
- Compliance or regulatory implications are unclear
- Grant-specific terminology or requirements are undefined

### Proceed with Confidence When:
- Formatting existing documentation to standards
- Fixing grammar, spelling, or clarity issues
- Adding cross-references between documents
- Organizing content into clearer structure
- Following explicit, documented patterns

## Validation Expectations
- Verify all links work (both internal and external)
- Check markdown rendering (headings, lists, tables)
- Ensure consistency with existing documentation style
- Validate technical accuracy of any code examples or configurations
- Confirm alignment with project context and stakeholder needs
