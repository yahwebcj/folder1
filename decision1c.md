```mermaid


flowchart TD

A1[Block1]
A2[Block2]


        A(["Start"])
        A --> B{"Decision"}
        B --> C["Option A"]
        B --> D["Option B"]
        C --> E[foot]  
        E-->F([end]) 
        D-->F
