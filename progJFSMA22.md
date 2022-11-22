
## Test mermaid

```mermaid
stateDiagram-v2
    [*] --> CreateRequest
    CreateRequest --> WaitMsg
    WaitMsg --> handleRefuse : refuse
    handleRefuse --> WaitMsg
    WaitMsg --> handleAgree : agree
    state forkAgree   <<fork>>
    handleAgree --> forkAgree
    forkAgree --> handleInform
    forkAgree --> WaitMsg
    handleInform --> handleAllResult : all results
    handleAllResult --> [*]
    
  
