# Santander Dev Week
Java RESTful API criada para a Santander Dev Week

## Diagrama de Classes

```mermaid

classDiagram
  class User {
    - String name
    - Account account
    - Feature[] features
    - Card card
    - News[] news
}

