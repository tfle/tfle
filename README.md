## How to spice up your profile README with a flowchart

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
    B --Yes--> C{{Want to read the<br> documentation first?}}
    C --Yes--> D([Grok the docs!])
    C --No--> E([Learn via play!])
    B --No--> B1{{Do you<br> like spice?}}
    B1 --Yes--> B2(["🌶️"])
    B1 --No--> B1    
    click B2 "https://github.com/tfle/tfle/discussions/new?category=spice&title=🌶%EF%B8%8F%20Adding%20spice%21%20🌶%EF%B8%8F&body=Just%20click%20%22Start%20discussion%22%20to%20add%20spice%21" _blank
    click D "https://mermaid-js.github.io/mermaid/#/flowchart" _blank
    click E "https://mermaid.live/" _blank
    class B2,D,E clickStyle
```
