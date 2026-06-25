# TurtleCMS
Solid Turtle CMS, to turn your solid pod into a website.

#design

```mermaid
flowchart TD
    A[Solid Pod\nSource Truth] --> sync/poll/webhook| B[Local RDF\nCache/Store]
    B --> C[Turtle CMS\nRenderer]
    C --> D[Static Site]
    D -->|SimplyEdit| E[Solid Login\nMetro]
    E --> F[Write directly\nto Pod]
```


#LICENSE
EUPL by Govert Combée
