# Federated Design Collaboration Prototype

A lightweight contribution model for improving shared government design systems without requiring shared Figma workspaces.

This prototype explores how individual contributors and agencies can propose improvements to shared components, patterns, and tokens while preserving a centralized source of truth.

Instead of duplicating components across agencies, improvements can be developed locally, validated, reviewed, and published for broader reuse.

---

## Why this exists

Many agencies use shared systems such as the U.S. Web Design System (USWDS) as a baseline while creating custom patterns to meet agency-specific needs.

This creates a common challenge:

- duplicate components
- inconsistent implementations
- isolated improvements
- limited contribution pathways for external designers

This prototype proposes a federated model where contributors can improve components locally and submit reusable updates back to a shared system.

---

## Contribution Model

The workflow mirrors a traditional development contribution model:

Issue → Branch → Test → Pull Request → Review → Merge → Pull Latest

Translated into design operations:

Problem Identified  
↓  
Local Figma Branch / File  
↓  
Component Improvement  
↓  
Validation  
↓  
Proposal Submission  
↓  
Review  
↓  
Shared Library Update  
↓  
Cross-Agency Adoption

Contributors do not need direct access to a central Figma file.

They need:

- a local workspace
- a documented improvement
- a clear review pathway

---

## Contribution Requirements

Each proposed improvement should include:

- Problem being solved  
- Current implementation  
- Proposed solution  
- Before/after screenshots  
- Figma link  
- Reusability rationale  
- Accessibility considerations (if applicable)

---

## Review Criteria

Proposed updates should improve one or more of the following:

- flexibility
- accessibility
- scalability
- maintainability
- consistency
- reduced duplication

---

## Example Contributions

### USA Banner Refactor

Improved banner flexibility for future agency customization.

Updates included:

- modular Info Card components
- expanded/collapsed state handling
- optional leading mark visibility
- configurable leading mark types
- reduced structural duplication

This serves as an example of how a local component improvement could be proposed back into a broader design system.

---

## Repository Structure

```bash
/components
/proposals
/examples
/governance
/resources
