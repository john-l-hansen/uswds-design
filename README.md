# People’s Design System Collaboration Prototype

A lightweight contribution model for improving shared design systems without requiring contributors to work inside a centralized Figma workspace.

This prototype explores how individual designers, contractors, agencies, and external partners can propose improvements to shared components, patterns, and tokens while preserving a centralized source of truth.

Instead of duplicating components across teams, improvements can be developed locally, validated, reviewed, versioned, and published for broader reuse.

---

# Why this exists

Shared design systems often serve multiple teams, agencies, and external contributors—but many lack a structured space for proposing reusable improvements.

As needs evolve, contributors may create local fixes, custom variants, or entirely separate components without a clear pathway for sharing improvements back with the broader system.

This prototype explores a lightweight contribution model that creates a shared space for:

- proposing component improvements  
- validating reusable solutions  
- documenting changes  
- reviewing updates  
- versioning design decisions  
- publishing improvements for broader reuse  

The goal is to make shared systems easier to improve without requiring every contributor to work in the same design file.

---

# Contribution Model

The workflow mirrors traditional software contribution models:

Issue → Branch → Test → Pull Request → Review → Merge → Release

Translated into design operations:

Problem Identified  
↓  
Local Figma Branch / File  
↓  
Component Improvement  
↓  
Validation  
↓  
Save Updated Local `.fig` File  
↓  
Git Commit  
↓  
Proposal Submission / Pull Request  
↓  
Review  
↓  
Merge  
↓  
Release / Publish  
↓  
Cross-Team Adoption

Contributors do not need direct access to a centralized Figma file.

They need:

- a local workspace  
- documented improvements  
- reusable solutions  
- a clear review pathway  
- version control discipline  

---

# Source of Truth

This model separates responsibilities across platforms:

Figma = visual source of truth  
GitHub = contribution governance + version history  
Releases = approved versions for adoption

Design changes are created locally in Figma.

Before submitting changes:

1. Save a local copy of the updated `.fig` file  
2. Replace/update the repository source file  
3. Commit changes  
4. Submit for review  

This ensures design work remains versioned similarly to software contributions.

---

# Contribution Requirements

Each proposed improvement should include:

- problem being solved  
- current implementation  
- proposed solution  
- before/after screenshots  
- Figma link or local file reference  
- reusability rationale  
- accessibility considerations (if applicable)  
- implementation notes  

---

# Review Criteria

Proposed updates should improve one or more of the following:

- flexibility  
- accessibility  
- scalability  
- maintainability  
- consistency  
- reduced duplication  
- documentation clarity  

---

# Example Contributions

## USA Banner Refactor

Improved banner flexibility for future customization.

Updates included:

- modular Info Card components  
- expanded/collapsed state handling  
- optional leading mark visibility  
- configurable leading mark types  
- reduced structural duplication  

---

## Button Flexibility Update

Improved button scalability and interaction parity.

Updates included:

- consolidated default and large sizing into shared properties  
- added large variants across all button colors  
- added hover interaction states for prototyping  

---

## Combo Box Interaction Update

Improved usability testing fidelity.

Updates included:

- added hover states  
- added focus states  
- added hover prototype interactions  

---

# Release Model

Merged updates can be grouped into releases.

Example prerelease:

v0.1.4-beta.1

This signals:

- approved internal contribution workflow  
- pending broader stakeholder review  
- ready for future stable release  

Final release example:

v0.1.4

---

# Repository Structure

/components  
/proposals  
/examples  
/governance  
/resources  
/releases  

---

# Goal

This project explores how shared design systems can evolve more like modern software ecosystems:

- distributed contribution  
- centralized governance  
- reusable improvements  
- transparent versioning  
- lower barriers to participation  

The long-term goal is to make shared systems easier to improve while reducing duplicated effort across teams.
