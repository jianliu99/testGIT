# Mermaid Diagram Example

This is a sample Mermaid diagram in a GitHub Markdown file:

```mermaid
graph TD;
    A[Start] --> B{Is it clear?};
    B -->|Yes| C[End];
    B -->|No| D[Revise];
    D --> B;

graph TD2;
    A1[Start] --> B1{Is it clear?};
    B1 -->|Yes| C1[End];
    B1-->|No| D1[Revise];
    D1 --> B1;
