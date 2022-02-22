# foo-mermaid

# test-mermaid
Test mermaid

```mermaid
flowchart LR
    Start --> Stop
```

## Simple Graph

```mermaid
flowchart LR
    A((A)) -->|7| B((B))
    A -->|2| C((C))
    B -->|3| A
    B -->|5| C
    C -->|1| A
    C -->|3| B
```

## Variant 2

```mermaid
flowchart LR
    A -->|7| B
    A -->|2| C
    B -->|3| A
    B -->|5| C
    C -->|1| A
    C -->|3| B
```

## Medium
        
```mermaid
flowchart LR
    A -->|5| B
    B -->|5| A
    B -->|10| C
    C -->|5| D
    C -->|20| B
    D --> |5| E
    E --> |5| B
```
