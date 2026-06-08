# Contribution [#]: [Issue Title]

**Contribution Number:** [1 / 2 / 3]  
**Student:** Yi-Han Chang
**Issue:** https://github.com/AcademySoftwareFoundation/OpenImageIO/issues/3908
**Status:** Phase I Complete

---

## Why I Chose This Issue

JPEG XL is an interesting image format because it aims to provide better compression, higher image quality, and more advanced features than older formats such as JPEG. Since OpenImageIO is widely used for image processing and graphics workflows, adding support for JPEG XL would help modernize the project and make it more useful for developers who work with new image formats. The issue caught my attention because it involves a real-world feature request that could benefit many users.

This issue also aligns with my learning goals. As a computer science student interested in software development and open-source contributions, I want to gain experience working with large codebases and understand how image libraries handle different file formats. By exploring this issue, I hope to learn more about image encoding and decoding, third-party library integration, and the process of adding new functionality to an established open-source project.
---

## Understanding the Issue

### Problem Description

Currently, OpenImageIO does not provide built-in support for the JPEG XL image format. Users who want to read, write, or process JPEG XL files through OpenImageIO cannot do so directly. The issue requests adding JPEG XL support so that images in this format can be loaded and saved using the same workflows available for other supported image formats.

Implementing this feature would likely require integrating a JPEG XL library, creating a new image format plugin, and ensuring that image metadata, color information, and other features are handled correctly. The goal is to allow OpenImageIO users to work with JPEG XL images as seamlessly as they do with existing formats such as JPEG, PNG, and TIFF.

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
