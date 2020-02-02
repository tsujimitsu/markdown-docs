## p2

### p2-1

<img src="http://placehold.jp/24/cccccc/ffffff/250x50.png?text=dummy-logo" width=20%>

### p2-2

```plantuml
@startuml

actor Promoter
actor Entrant

Promoter --> (Create Event)
Promoter -> (Attend Event)

Entrant --> (Find Event)
(Attend Event) <- Entrant

(Attend Event) <.. (Create Member)  : <<include>>

@enduml
```
