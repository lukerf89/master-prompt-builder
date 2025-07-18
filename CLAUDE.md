# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This directory contains a curated collection of nonprofit AI prompt templates organized by complexity level. It serves as a focused subset of the broader nonprofit AI cookbook, containing the most sophisticated and comprehensive templates for advanced nonprofit use cases.

## Architecture

The repository is organized into two main complexity tiers:

### high_complexity_examples/
Contains comprehensive prompt templates with full structural elements:
- **Financial Templates**: 6 specialized templates for nonprofit financial operations (budget analysis, financial forecasting, document verification, performance analysis, reconciliation, donor behavior analysis)
- **Communications Templates**: Advanced templates for annual reports, grant reports, and social media strategy
- **Structure**: Each template includes ROLE_AND_GOAL, STEPS, OUTPUT, CONSTRAINTS, CONTEXT, FEW_SHOT_EXAMPLES, and RECAP sections

### medium_complexity_examples/
Contains structured prompt templates with core elements:
- **Operational Templates**: Volunteer management, program evaluation, newsletter creation, timesheet processing
- **Structure**: Each template includes ROLE_AND_GOAL, STEPS, and OUTPUT sections with some additional context

## Template Architecture Pattern

All templates follow a consistent structural pattern:

```
<ROLE_AND_GOAL>
[Defines AI persona and specific objective]
</ROLE_AND_GOAL>

<STEPS>
[Detailed process workflow]
</STEPS>

<OUTPUT>
[Specific format requirements]
</OUTPUT>
```

High-complexity templates additionally include:
- `<CONSTRAINTS>`: Dos and don'ts for execution
- `<CONTEXT>`: Background information and considerations
- `<FEW_SHOT_EXAMPLES>`: Detailed examples with input/output pairs
- `<RECAP>`: Summary of key principles

## Template Variables System

Templates use a bracketed variable system for customization:
- `[ORGANIZATION_NAME]`: The nonprofit's name
- `[MISSION_STATEMENT]`: Organization's mission
- `[TARGET_AUDIENCE]`: Primary stakeholder group
- `[DOCUMENT_TYPE]`: Specific document being processed
- `[PLATFORM_LIST]`: Social media platforms
- `[VALUE_1]`, `[VALUE_2]`, etc.: Organizational values

## Financial Template Specialization

The financial templates are designed specifically for nonprofit contexts and include:
- Restricted fund compliance requirements
- Grant reporting and compliance considerations
- Board oversight and authorization frameworks
- Nonprofit accounting standards (vs. for-profit)
- Impact measurement alongside financial metrics
- Stakeholder-specific reporting requirements

## Content Strategy Framework

Templates follow a mission-centric approach:
- All content must connect to organizational mission
- Multi-stakeholder consideration (donors, volunteers, beneficiaries, partners)
- Resource-conscious design (accounting for limited nonprofit capacity)
- Ethical storytelling that respects beneficiary dignity
- Community-building over broadcasting

## Template Quality Standards

- Defensive security focus (no templates for malicious use)
- Nonprofit-specific context and requirements
- Clear variable placeholder system
- Actionable output specifications
- Scalable complexity (medium → high complexity pathway)
- Real-world example integration in high-complexity templates