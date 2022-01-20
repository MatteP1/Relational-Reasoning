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
  - Definition
    - Show definition
    - Intuition
    - Give example of how it ensures numbers are the same
  - Alternative definition
    - Show definition
    - Correction - "all expressions in the relation are well-typed"
      - could have mode precise what that meant
    - Definitions are equivalent
- Logical Relations
  - Intuition about LR in general
    - They are relations.
    - Draw as circles
      - Create LR so it is contained in the relation of interest
      - Specific for CE and LR
  - Our way of showing LR is contained
    - Adequacy
    - Congruency
    - Well-typedness
  - Definition of LR
    - Split up into several layers that build on each other
    - "Interpretations"
    - Show full definition
  - Compatibility Lemmas
    - essentially just cases in proving congruency
    - showing them gives us LR is congruent relation
    - weakness - proofs are long and complicated; there may very well be mistakes. Further, there are quite many cases, and not all have been formally carried out. Using a tool like Coq would increase trust in the proofs.
      - Also idea for future work
      - The LR is heavily inspired by works from Amal Ahmed, so it is likely correct.
  - Soundness and Fundamental theorem.
    - Both of these points are very common occurrences when working with logical relations.
- Using Logical Relations
  - If time, go through Empty Type proof.
  - Illustrate how choice of R influences proof; making R non-empty may not allow the proof to go through.

### Improvements
"all expressions in the relation are well-typed" is vague
the expressions shouldn't just be well-typed at any type under any environment
They should be well-typed under the environments and at the type they are in relation with.
So if R(Xi, Gamma, e, e', tau) then Xi | Gamma |- e : tau and Xi | Gamma |- e' : tau

Much of the theory could be implemented in a system like Coq to ensure correctness of the work.