# Notes for slides

## Meta information
Length: 15 min


## Content
Follow high-level structure of report
Also include parts that could be improved

### Structure
- Explanation of Language
  - Basics
    - System F
    - STLC with parametric polymorphism
  - Specifics
    - call by value
    - booleans and integers
    - sum types and prod types
  - Main Results
    - Type safety
    - Normalising
    - Deterministic
- Contextual Equivalence
  - Todo
- Logical Relations
  - Todo
- Todo

### Improvements
"all expressions in the relation are well-typed" is vague
the expressions shouldn't just be well-typed at any type under any environment
They should be well-typed under the environments and at the type they are in relation with.
So if R(Xi, Gamma, e, e', tau) then Xi | Gamma |- e : tau and Xi | Gamma |- e' : tau