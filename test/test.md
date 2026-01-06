# Test

This is a Markdown file.

$$
e^{i\pi} + 1 = 0
$$

```plantuml
@startuml
title Simple Login Sequence

actor User
participant "Web App" as App
participant "Auth Service" as Auth

User -> App: Open login page
User -> App: Submit credentials
App -> Auth: Validate(username, password)
Auth --> App: Success
App --> User: Show dashboard
@enduml
```