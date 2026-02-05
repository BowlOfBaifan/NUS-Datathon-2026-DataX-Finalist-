# Improvement Insights

## 1. Duplicate Questions (Score > 0.9)

- **Q1: Other - Write In (Required):What do you wish to learn more about regarding the organisation as an employer? (Pick 3)  
  Q2: Other - Write In (Required):What do you wish to learn more about regarding the organisation as an employer? (Pick 3)  .1**
  - KEEP: Q1
  - DROP: Q2
  - Reason: These are identical questions. Q2 is likely a copy resulting from an error.

- **Q1: Which of these factors would most motivate you to apply for a position at the organisation?  
  Q2: Other - Write In (Required):Which of these factors would most motivate you to apply for a position at the organisation?  **
  - KEEP: Q1
  - DROP: Q2
  - Reason: Q2 is redundant since Q1 already captures motivational factors, and "Other" can be included as an option in Q1 itself.

## 2. Potentially Redundant Questions (0.8 < Score < 0.9)
All pairs in this range refer to different options for the question, "What do you wish to learn more about regarding the organization as an employer? (Pick 3)". These are NOT redundant; they are simply different possible answers to the same underlying question. The redundancy score is high because of the similar question prompt prepended to each answer.

Therefore:
No potentially redundant questions detected.

## 3. Survey Segmentation Recommendation

Organize the survey into the following sections, in this order:

1.  **Demographic Information:** This section sets the context and allows for basic segmentation of responses.
2.  **Employer Perception:** Understanding current perception is important before asking about specific information needs.
3.  **Information Interest - Employer:** This section delves into what candidates want to know, building upon their existing perception.
4.  **Motivation to Apply:** This section explores the key factors that would encourage applications, leveraging previously gathered insights.

## 4. Question Clarity Improvements

- Original: Types of roles available:What do you wish to learn more about regarding the organisation as an employer? (Pick 3)
- Improved: I would like to learn more about the types of roles available at the organization. (Pick 3)
- Reason: Removing the repeated question at the beginning of each question makes the answer options cleaner and easier to read. The same applies to other similar questions in "Information Interest - Employer"
