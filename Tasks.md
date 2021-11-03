# Tasks

## STLC and learning
- [x] Read sections 1-4 in note by Lau
- [x] Define type safety for STLC
- [x] Define Logical Relations for type safety for STLC
- [x] Prove the two intermediate lemmas
- [x] Read parts I and II of types and programming languages
- [x] Watch videos on Blackboard

## System F. The Language
- [x] Write in language (System F) in report
- [x] Define and prove "Evaluation under Context" lemma for System F w/rec
  - [x] Define k = [] or Val(e) lemma. Show 1 case
  - [x] Write in complete EuC lemma
  - [x] Proof read
- [x] Refactor for terminating language
- [ ] Substitution
- [ ] Fix typ-setting

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
- [ ] Finish writing text
- [ ] Proof read

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
- [ ] Fix type-setting
- [ ] Proof read

## Using the Logical Relations


## Report Writing


## Exam period
- [ ] Watch exam video on Blackboard