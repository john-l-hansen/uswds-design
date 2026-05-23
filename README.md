# USWDS Collaboration Prototype

![Status](https://img.shields.io/badge/status-proposed-blue)

This is a lightweight contribution prototype for improving shared design systems without requiriing contributors to work inside a centralized Figma workspace.

This prototype explores how individual designers, contractors, agencies, and external partners can propose improvements to shared components, patterns, and tokens while preserving a centralized source of truth.

Instead of duplicating components across teams, improvements can be developed locally, validated, reviewed, versioned, and published for broader reuse.

**References:**

[USWDS For Designers Repository](https://github.com/uswds/uswds-for-designers/?tab=readme-ov-file#coffee-january-2025-uswds-design-kit-for-figma-beta-03-uswds-3110)

[USWDS Design Kit Figma File](https://www.figma.com/community/file/1440921849343185329)

[United States Web Design System (USWDS) Documentation](https://designsystem.digital.gov/)

---

# Why this exists

As needs evolve, contributors may create local fixes, custom variants, or entirely separate components without a clear pathway for sharing improvements back with the broader system.

This prototype explores a lightweight contribution model that creates a shared space for:

- proposing component improvements  
- validating reusable solutions  
- documenting changes  
- reviewing updates  
- versioning design decisions  
- publishing improvements for broader reuse  

The goal is to make shared systems easier to improve without requiring every contributor to work in the same design file.

<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/1fb001fc-1f29-48a0-8c01-7757bad94f3d" />
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/2501447c-6ce8-43e1-a67b-c1511ba2919a" />
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/2ad478f8-7c12-4e9a-a8b1-53170834b866" />
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/fa700d9c-ebf9-45ba-bd43-5c8b8092bc3f" />
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/b3135ca9-6393-4344-9be4-c83850937ce1" />

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

# Example Submission

<img width="3337" height="1706" alt="image" src="https://github.com/user-attachments/assets/340f2bd4-396f-4714-a103-21f08bdb9ca3" />


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

<img width="2874" height="2149" alt="Button update contribution proposal document." src="https://github.com/user-attachments/assets/129ac39a-e15b-4974-8f03-dac7c84076df" />

---
