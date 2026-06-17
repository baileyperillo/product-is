# Contribution [#]:  [React Doctor] tabindex-no-positive: tabIndex should not be greater than zero — positive values disrupt natural ... (59 occurrences)
 #27960


**Contribution Number:** [1 / 2 / 3]  
**Student:** Bailey Perillo  
**Issue:** https://github.com/wso2/product-is/issues/27960
**Status:** Phase I

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]

I chose this issue mainly because it was labeled as a good first issue and this is the first time I am doing anything involved in opensource. I could also read and somewhat understand what the title was describing, so I felt less hesitant on taking it on. I saw that it was not completed based on the comments, and I knew most of the coding languages (some Java, CSS, and Javascript). Other problems were either I don't know what was being asked, I don't know the coding language, or it was taken/ finished. This project can help me practice contributing to open source, extracting information from documentation, coding in Java, and understanding how management systems can work.
---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]
There is a variable in the code name tabIndex that keeps resulting in a positive number, when it shouldn't be. I need to read more on how the program works.

### Expected Behavior

[What should happen?]
tabIndex should not be greater than zero — positive values disrupt natural keyboard navigation order.

### Current Behavior

[What actually happens?]
It was not mentioned in the document. I am assuming based on the subject of the issue, severity, and violations that there are many times that the variable tabIndex is greater than 0, or a positive number.

### Affected Components

[Which parts of the codebase are involved?]
It is not mentioned in the issue. I am doing further research on the code and from the given link ( https://github.com/wso2/identity-apps/tree/b2a8f16f154cf4ada332b7d624ba4b0ad7629518 ). From initial look of files affected, it seems that the access permission system is affected. This is a user management system I think so this could affect who has verified access to the management system and editing access like adding users.

---s

## Reproduction Process

### Environment Setup
I am still working on the local development setup. For the canidate issue I have selected, there are multiple documentations to refer to so I hd to read each of them and see if some were outdated or not. I also had to empty some storage to do anything and undo some of the progress I made from last week because I setup the wrong environment when trying to complete Phase 1 and before reading Phase 2.
I will start reproducing the issue by this week.

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
