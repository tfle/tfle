## Spice up your profile README with a flowchart

```mermaid
%%{init:{
    "theme": "base",
    "flowchart": {
        "diagramPadding": "0",
        "nodeSpacing": "50",
        "rankSpacing": "50"
    }
}}%%

flowchart LR
    classDef clickStyle stroke:#0000EE,stroke-width:2px    
    A([Start]) ==>B{{Do you like<br> flowcharts?}}
    B --Yes--> C[Let's make<br> a flowchart!] --> D{{Want to read the<br> documentation first?}}
    D --Yes--> E([Grok the docs!])
    D --No--> F([Learn via play!])
    B --No--> B1{{Do you<br> like spice?}}
    B1 --Yes--> B2(["🌶️"])
    B1 --No--> B1    
    click B2 "https://youtu.be/dQw4w9WgXcQ" _blank
    click E "https://mermaid-js.github.io/mermaid/#/flowchart" _blank
    click F "https://mermaid.live/" _blank
    class B2,E,F clickStyle
```
