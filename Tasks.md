# Tasks

## STLC and learning
- [x] Read sections 1-4 in note by Lau
- [x] Define type safety for STLC
- [x] Define Logical Relations for type safety for STLC
- [x] Prove the two intermediate lemmas
- [x] Read parts I and II of types and programming languages
- [x] Watch videos on Blackboard
- [ ] Read parts of types and programming languages again
- [ ] Read Theorems for free!

## System F. The Language
- [x] Write in language (System F) in report
- [x] Add explaining text to each part
- [x] Define and prove "Evaluation under Context" lemma for System F w/rec
  - [x] Define k = [] or Val(e) lemma. Show 1 case
  - [x] Write in complete EuC lemma
  - [x] Proof read
- [x] Refactor for terminating language
- [x] Substitution
- [x] Normalisation
- [x] Determinacy
  - [x] For one step
  - [x] Multi-step evaluation to a value.
- [x] Fix type-setting

## Contextual Equivalence
- [x] Define Contextual Equivalence for System F
- [x] Write in Contextual Equivalence
- [x] Explanation and intuition
  - [x] Talk about CE being enough for integers
  - [x] Talk about CE being enough for non-base types (specifically function type)
    - [x] Show congruence rule for function application, and argue it's correctness, and why it is enough (see google photos)
- [x] Mention the other, equivalent way of defining Contextual Equivalence (see google photos)
  - [x] Congruence Rules
  - [x] Adequacy
  - [x] Prove they are equivalent
    - [x] ctxeq(forallC) => congruence (we showed one rule) and adequate (google photo)
    - [x] other direction: (google photo)
      - [x] main proof
      - [x] define helper lemma
      - [x] prove helper lemma
        - [x] define reflexivity lemma
        - [x] prove reflexivity lemma
          - [x] show one case (Tlam)
        - [x] show cases
          - [x] base [*]
          - [x] add
          - [x] fst
          - [x] rec
          - [x] app
          - [x] Tlam
- [x] Fix type-setting
  - [x] ctx-equiv -> CE
  - [x] type environment and variable environment (tctx -> venv)
  - [x] refactor judgements
- [x] Define Congruency and Adequacy as separate properties
  - [x] In case of reflexivity and Lemma 6, state only for relations having congruency (and possibly well-typedness).
- [x] Refactor for terminating language
- [x] Finish writing text
- [x] Fix type-setting

## Logical Relations
- [x] Define a logical relations model for CE
- [x] Write in LR
  - [x] val- and exp-interpretation
  - [x] varenv- and typenv-interpretation
- [x] Prove compatibility lemmas (only unit and add with well-typedness)
  - [x] Unit
  - [x] Add
  - [x] Match (if-similar, but simpler)
  - [x] Fst
  - [x] Lam
  - [x] App
  - [x] Tlam
  - [x] Tapp (if space)
- [x] Show results about LR
  - [x] LR => Ctx
    - [x] adequacy
    - [x] congruency
  - [x] Fundamental theorem
- [x] Finish writing text
  - [x] Section 4.1 Logical relations
  - [x] Section 4.2 Defining the LR Model
  - [x] Section 4.3 Compatibility lemmas
  - [x] Section 4.4 Properties of LR
- [x] Fix type-setting

## Using the Logical Relations
- [x] Identity
  - [x] Identity derivation
    - [x] write in theorem
      - [x] empty environments
    - [x] prove it
  - [x] Identity contextual equivalence
    - [x] write in theorem
      - [x] general environments
    - [x] prove it
      - [x] the proof itself
      - [x] determinacy
        - [x] State it (in language chapter)
      - [x] substitution preserves typing
        - [x] prove it
- [x] Empty type
  - [x] write in theorem
  - [x] prove it
- [x] Idempotency
  - [x] write in theorem
  - [x] prove it
- [x] Commutativity
  - [x] write in theorem
  - [x] prove it
  - [x] check correctness
- [x] Lam hoisting
  - [x] write in theorem
  - [x] prove it
  - [x] check correctness
  - [x] Well-typedness
    - [x] build expression from assumptions and then fund thm.
- [x] Finish writing text
  - [x] Identity
  - [x] Empty type
  - [x] Idempotency
  - [x] Commutativity
  - [x] Lam hoisting
- [x] fix type-setting

## Report Writing
- [x] Appendix
- [x] Write introduction
- [x] Write conclusion and ideas for future work
- [x] Write abstract
- [x] Proper references
  - get your bibtex entries from \url{https://dblp.org/}
- [ ] Fix annotated mistakes
- [ ] Shorten report
- [ ] Format appendix
- [ ] Proofread report

## Exam period
- [ ] Watch exam video on Blackboard