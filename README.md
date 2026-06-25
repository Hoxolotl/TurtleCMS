# TurtleCMS
Solid Turtle CMS, to turn your solid pod into a website.

#design


```mermaid
flowchart TD
    A["Solid Pod<br>Source Truth"] --> sync/poll/webhook| B["Local RDF<br>Cache/Store"]
    B --> C["Turtle CMS<br>Renderer"]
    C --> D["Static Site"]
    D -->|SimplyEdit| E["Solid Login<br>Metro"]
    E --> F["Write directly<br>to Pod"]
```


#LICENSE
EUPL by Govert Combée
