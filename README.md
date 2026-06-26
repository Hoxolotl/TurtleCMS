# TurtleCMS
Solid Turtle CMS, to turn your solid pod into a website.

#design
* flow
 * go to website
 * log in
  * actually logs into the pod
 * Edit website
  * actually edits the .ttl file(s) on the pod
 * Save
  * actually saves the file on the pod, and tells the website to copy the file from the pod to the (web)server    

#Todo
* Metro JS:
 * [ ] get everything.js from https://github.com/muze-nl/metro/tree/copilot/monorepofix-tests-workflow/dist
 * [ ] login to pod in the websites/-name-website- folder
 * [ ] retrieve all files and copy to the local (web) server
 * [ ] subscribe to the files to update them if they're changed

* "translation" file format
 * have several .ttl files to generate pages on the website.
  * using schema.org there will probably be 3 files
   * [ ] content ( text ) and where it's placed on the website and in what format
   * [ ] formats and how they're translated to html web elements
   * [ ] formats and how they're styled 

* Simply edit/things
    ** log into the website(pod)
    ** make changes to the page by actually editing the .ttl files on the pod



```mermaid
flowchart TD
    A["Solid Pod Source Truth"] --> B["Local RDF Cache/Store"]
    B --> C["Turtle CMS Renderer"]
    C --> D["Static Site"]
    D -->|SimplyEdit| E["Solid Login Metro"]
    E --> F["Write directly to Pod"]
```

#LICENSE
EUPL by Govert Combée
