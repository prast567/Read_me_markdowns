# Read_me_markdowns

## Heading1
### Heading2
###### HEading6

## Emphasis

*This text will be italic*\
_This will also be italic_\
**This text will be bold**\
__This will also be bold__\
*You **can** combine them*

## Unorderred Lists:-
* Item 1
* Item 2
  * Item 2a
  * Item 2b

## Ordered List
1. Item 1
2. Item 2
3. Item 3

## Links
[GitHub](http://github.com)


## Mernaid
```mermaid
flowchart TD

U[User Query] --> CM[Chat Manager]

CM --> R{Router}

R --> S[Structured Data Agent]
R --> U[Unstructured Data Agent]
R --> M[Multimodal Data Agent]

S --> PG[(PostgreSQL Database)]
S --> F[Fairness Audit]

U --> MDB[(MongoDB)]
U --> VDB[(Chroma Vector DB)]
U --> P[PII Detection]

M --> B[(Azure Blob Storage)]
M --> C[CLIP + Content Safety]

S --> CM
U --> CM
M --> CM

CM --> OUT[Final Response]
