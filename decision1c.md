---
config:
      theme: redux
---
flowchart TD
        A(["Start"])
        A --> B{"Decision"}
        B --> C["Option A"]
        B --> D["Option B"]
        C --> E[foot]  
        E-->F([end]) 
        D-->F
