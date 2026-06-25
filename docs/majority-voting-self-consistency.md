# Majority Voting / Self-Consistency

[Back to README](../README.md)

## Detailed Overview
By generating multiple independent reasoning paths at higher temperatures and voting on the final answers, models significantly improve their reliability and accuracy.

## Diagram
```mermaid
flowchart TD
    A[Prompt] --> B[Path 1: Ans A]
    A --> C[Path 2: Ans B]
    A --> D[Path 3: Ans A]
    B & C & D --> E[Vote: A wins]
```

