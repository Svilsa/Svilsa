```mermaid
graph LR
    A(Try) --> B(Fail)
    B --> C(Try Again)
    C --> D(Fail Better) 
    D --> C
    C ---> E(Succeed)
```
