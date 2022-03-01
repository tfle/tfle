## Spice up your profile README with a flowchart
```mermaid
%%{init:{"theme":"base"}}%%
flowchart LR
    classDef clickStyle stroke:#0000EE,stroke-width:2px
    A([Start]) ==>B{{Do you like<br> flowcharts?}}
    B --Yes--> C[Let's make<br> a flowchart!] --> D{{Do you want to read<br> the documentation first?}}
    D --Yes--> E([Check out the basic<br> flowchart syntax here!])
    D --No--> F([Play with the<br> Mermaid Live Editor!])
    B --No--> B1[I understand.<br> Really, I do.] --> B2([There are better ways<br> to visualise processes.])
    click B2 "https://youtu.be/dQw4w9WgXcQ" _blank
    click E "https://mermaid-js.github.io/mermaid/#/flowchart" _blank
    click F "https://mermaid.live/" _blank
    class B2,E,F clickStyle
```
