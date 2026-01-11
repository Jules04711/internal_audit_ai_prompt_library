# Internal Audit AI Prompt Library

A comprehensive collection of AI prompts designed for internal audit professionals, aligned with the Institute of Internal Auditors (IIA) Global Internal Audit Standards effective January 2025.

---

## Overview

This prompt library provides internal auditors with structured, pre-built prompts to enhance audit efficiency and effectiveness when working with Large Language Models (LLMs) such as ChatGPT, Claude, Gemini, or Microsoft Copilot. The library supports both assurance and advisory engagements across all phases of the audit lifecycle.

**Version:** 1.0
**Release Date:** January 2026
**Total Prompts:** 44
**Standards Alignment:** IIA Global Internal Audit Standards (2025)

---

## Contents

| File | Description |
|------|-------------|
| `internal_audit_prompt_library.xlsx` | Excel workbook containing all 44 prompts organized by audit phase with metadata and guidance |
| `IA_AI_Prompt_Library_Training_Manual.docx` | Comprehensive training manual covering LLM fundamentals, prompt engineering, and practical application |

---

## Prompt Library Structure

The Excel workbook contains eight worksheets:

### Dashboard
- Template overview and navigation
- Quick links to each phase
- Prompt statistics summary

### Settings
- Dropdown values for skill levels and status
- IIA Standards reference (Domains I-V, Standards 13-15)
- Engagement type classifications

### Planning Phase (PLAN-001 through PLAN-010)
Prompts supporting IIA Standards 13.1-13.6 for engagement planning:

| Prompt ID | Title | Purpose |
|-----------|-------|---------|
| PLAN-001 | Engagement Risk Assessment | Identify and document risks per Standard 13.2 |
| PLAN-002 | Engagement Objectives Development | Develop SMART audit objectives per Standard 13.3 |
| PLAN-003 | Work Program Development | Create testing procedures per Standard 13.6 |
| PLAN-004 | Pre-Audit Information Request | Generate document request lists |
| PLAN-005 | Resource and Timeline Planning | Estimate resources per Standard 13.5 |
| PLAN-006 | Process Understanding - Narrative | Document process walkthroughs |
| PLAN-007 | Control Environment Assessment | Evaluate COSO control environment factors |
| PLAN-008 | Advisory Engagement Scope Agreement | Draft advisory scope agreements |
| PLAN-009 | Prior Audit Issue Analysis | Analyze prior findings for current planning |
| PLAN-010 | Engagement Opening Meeting Agenda | Prepare kickoff meeting materials |

### Fieldwork Phase (FIELD-001 through FIELD-012)
Prompts supporting IIA Standards 14.1-14.6 for performing engagement work:

| Prompt ID | Title | Purpose |
|-----------|-------|---------|
| FIELD-001 | Control Design Evaluation | Assess control design adequacy |
| FIELD-002 | Operating Effectiveness Testing | Design tests of operating effectiveness |
| FIELD-003 | Interview Question Development | Prepare skeptical interview questions |
| FIELD-004 | Data Analysis Anomaly Identification | Identify transaction anomalies |
| FIELD-005 | Workpaper Documentation | Structure workpaper evidence |
| FIELD-006 | Root Cause Analysis | Determine control failure causes |
| FIELD-007 | Sampling Methodology Design | Develop appropriate sampling approaches |
| FIELD-008 | Policy Compliance Evaluation | Evaluate against policy criteria |
| FIELD-009 | IT General Controls Assessment | Assess ITGC design and operation |
| FIELD-010 | Fraud Risk Indicator Analysis | Identify fraud red flags |
| FIELD-011 | Walkthrough Documentation | Document process walkthroughs |
| FIELD-012 | Advisory Analysis Framework | Structure advisory engagement analysis |

### Reporting Phase (RPT-001 through RPT-010)
Prompts supporting IIA Standard 15.1 for communicating engagement results:

| Prompt ID | Title | Purpose |
|-----------|-------|---------|
| RPT-001 | Finding Development - Five Attributes | Structure findings using condition, criteria, cause, effect, recommendation |
| RPT-002 | Executive Summary Development | Create summaries for leadership audiences |
| RPT-003 | Recommendation Writing | Develop actionable recommendations |
| RPT-004 | Management Response Facilitation | Help management develop responses |
| RPT-005 | Report Quality Review Checklist | Quality assurance for draft reports |
| RPT-006 | Positive Observation Documentation | Document effective controls and good practices |
| RPT-007 | Risk Rating Justification | Document risk rating rationale |
| RPT-008 | Advisory Engagement Deliverable | Structure advisory deliverables |
| RPT-009 | Closing Meeting Preparation | Prepare closing meeting materials |
| RPT-010 | Report Distribution and Communication | Determine distribution and approach |

### Follow-up Phase (FU-001 through FU-006)
Prompts supporting IIA Standard 15.2 for monitoring corrective actions:

| Prompt ID | Title | Purpose |
|-----------|-------|---------|
| FU-001 | Validation Testing Design | Design follow-up validation procedures |
| FU-002 | Remediation Status Assessment | Evaluate implementation status |
| FU-003 | Audit Committee Status Report | Generate status reports for governance |
| FU-004 | Escalation Recommendation | Prepare escalation for past-due items |
| FU-005 | Finding Closure Documentation | Document finding closure with evidence |
| FU-006 | Recurring Issue Analysis | Identify systemic patterns |

### General/Cross-Phase (GEN-001 through GEN-006)
Prompts for activities spanning multiple phases:

| Prompt ID | Title | Purpose |
|-----------|-------|---------|
| GEN-001 | Professional Email Communication | Draft audit-related emails |
| GEN-002 | Audit Terminology Explanation | Explain concepts to non-auditors |
| GEN-003 | Time and Budget Tracking Analysis | Analyze engagement productivity |
| GEN-004 | Continuing Education Summary | Summarize CPE for knowledge sharing |
| GEN-005 | Stakeholder Relationship Building | Develop relationship approaches |
| GEN-006 | New Auditor Onboarding Checklist | Create onboarding materials |

### Change Log
- Version history and approval tracking
- Document control information

---

## Prompt Metadata

Each prompt includes the following fields:

| Field | Description |
|-------|-------------|
| Prompt ID | Unique identifier (e.g., PLAN-001) |
| Title | Brief description of prompt function |
| Purpose | Detailed explanation of use case |
| Full Prompt Text | Complete prompt with placeholders |
| Variables | List of required inputs (e.g., {{audit_area}}) |
| Related IIA Standard | Applicable professional standard |
| Methodology Notes | Context on why this audit step matters |
| Skill Level | Beginner, Intermediate, or Advanced |
| Engagement Type | Assurance, Advisory, or Both |
| Tips for Customization | Guidance for adaptation |
| Example Input | Sample variable values |
| Example Output | Expected AI response description |
| Version | Prompt version number |
| Author | Prompt creator |
| Status | Draft, Active, Under Review, or Archived |
| Last Modified | Date of last update |

---

## Training Manual Contents

The training manual provides comprehensive guidance in eight chapters:

1. **Introduction to AI in Internal Audit**
   - Purpose and scope of the manual
   - Evolution of technology in auditing
   - Benefits and professional standards alignment

2. **Understanding Large Language Models**
   - Non-technical explanation of how LLMs work
   - Capabilities and limitations
   - Common platforms overview
   - Security and confidentiality considerations

3. **Prompt Engineering Fundamentals**
   - Anatomy of an effective prompt
   - CRAFT Framework (Context, Role, Action, Format, Tone)
   - Prompting techniques (zero-shot, few-shot, chain-of-thought)
   - Common mistakes to avoid
   - Variables and placeholders

4. **Using the Internal Audit Prompt Library**
   - Library structure overview
   - Column definitions and usage
   - Step-by-step usage instructions
   - Skill level progression
   - Assurance vs. advisory considerations

5. **Phase-Specific Prompt Guidance**
   - Planning phase prompts and applications
   - Fieldwork phase prompts and applications
   - Reporting phase prompts and applications
   - Follow-up phase prompts and applications

6. **Quality Assurance and Professional Judgment**
   - Human-AI partnership principles
   - Quality review checklist for AI outputs
   - Documentation requirements
   - Avoiding over-reliance on AI
   - Supervisor review considerations

7. **Advanced Prompting Techniques**
   - Prompt chaining for complex tasks
   - Data analysis applications
   - Customizing library prompts
   - Creating custom prompts
   - Iterative refinement strategies

8. **Practice Exercises**
   - Planning phase scenarios
   - Fieldwork phase scenarios
   - Reporting phase scenarios
   - Prompt engineering exercises

**Appendices:**
- Quick Reference Card (CRAFT Framework, Common Variables, Quality Checklist)
- IIA Standards Quick Reference
- Glossary of Terms

---

## Getting Started

### Prerequisites
- Access to an LLM platform (ChatGPT, Claude, Microsoft Copilot, Google Gemini, or similar)
- Microsoft Excel to view the prompt library
- Microsoft Word to view the training manual
- Familiarity with IIA Global Internal Audit Standards (2025)

### Quick Start

1. Open `internal_audit_prompt_library.xlsx`
2. Navigate to the Dashboard tab for an overview
3. Select the appropriate phase tab for your current audit activity
4. Choose a prompt matching your task
5. Read the Methodology Notes to understand the professional context
6. Copy the Full Prompt Text
7. Replace all `{{placeholders}}` with engagement-specific information
8. Paste into your AI platform
9. Review and refine the output using professional judgment
10. Document AI use per departmental policy

### Best Practices

- Read the training manual before extensive use of the library
- Always verify AI-generated content for accuracy and appropriateness
- Apply professional judgment to all AI outputs
- Maintain confidentiality by anonymizing sensitive information
- Document AI use in workpapers as required by policy
- Use the Methodology Notes to reinforce audit knowledge

---

## Skill Levels

| Level | Description | Recommended For |
|-------|-------------|-----------------|
| Beginner | Highly structured prompts with embedded explanations | Staff auditors, new team members |
| Intermediate | Prompts requiring some audit experience and judgment | Senior auditors, experienced staff |
| Advanced | Complex, judgment-intensive prompts | Audit managers, senior specialists |

---

## IIA Standards Alignment

This library aligns with the following IIA Global Internal Audit Standards (2025):

| Domain/Standard | Description |
|-----------------|-------------|
| Domain I | Purpose of Internal Auditing |
| Domain II | Ethics and Professionalism |
| Domain III | Governing the Internal Audit Function |
| Domain IV | Managing the Internal Audit Function |
| Domain V | Performing Internal Audit Services |
| Standard 13 | Engagement Planning (13.1-13.6) |
| Standard 14 | Performing Engagement Work (14.1-14.6) |
| Standard 15 | Communicating Engagement Results (15.1-15.2) |
| Principle 4.3 | Professional Skepticism |

---

## Security and Confidentiality

When using AI tools with audit information:

- Remove or anonymize names, account numbers, and identifying details
- Use enterprise versions with appropriate data handling agreements when available
- Never enter passwords, social security numbers, or financial account details
- Consider discoverability implications for AI-generated content
- Follow organizational policies regarding AI use documentation
- Verify confidentiality protections of the AI platform being used

---

## Version History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | January 2026 | Initial release with 44 prompts across all phases |

---

## Contact

For questions, suggestions, or contributions to this prompt library, contact [Jules Martin](https://github.com/Jules04711).

---

## Disclaimer

This prompt library is intended to assist internal auditors in their work. AI-generated outputs should be reviewed for accuracy and appropriateness before use. The internal auditor remains responsible for all work product quality and must apply professional judgment to all AI-assisted deliverables. This library does not replace professional training, experience, or judgment.
