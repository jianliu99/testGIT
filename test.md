# Mermaid Diagram Example

This is a sample Mermaid diagram in a GitHub Markdown file:

```mermaid
graph TD;
    A[Start] --> B{Is it clear?};
    B -->|Yes| C[End];
    B -->|No| D[Revise];
    D --> B;
