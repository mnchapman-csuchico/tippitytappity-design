# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  History <|-- User
  class History{
        - user_id: int
        + wpm_history vector~int~
        + accuracy_history vector~double~
  }
  class User{
        - name: string
        + user_id: int
        - email: string
        - password: string
        - accuracy: double
        - wpm: int
        + login(user: string, pass: string) boolean
        + get_email() string
        - test_accuracy() void
        - test_wpm() void
  }
```
