# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  Test <|-- User
  class Test
  {
        
  }

  class User
  {
        - name: string
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
