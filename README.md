# TurtleCMS
Solid Turtle CMS, to turn your solid pod into a website.

#design
                ┌──────────────┐
                │ Solid Pod    │
                │ Source Truth │
                └──────┬───────┘
                       │
                sync/poll/webhook
                       │
                       ▼
                ┌──────────────┐
                │ Local RDF    │
                │ Cache/Store  │
                └──────┬───────┘
                       │
                       ▼
                ┌──────────────┐
                │ Turtle CMS   │
                │ Renderer     │
                └──────┬───────┘
                       │
                       ▼
                ┌──────────────┐
                │ Static Site  │
                └──────┬───────┘
                       │
                 SimplyEdit
                       │
                       ▼
                Solid Login
                 (Metro)
                       │
                       ▼
                Write directly
                  to Pod


#LICENSE
EUPL by Govert Combée
