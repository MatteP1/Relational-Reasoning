# Tasks

## STLC and learning
- [x] Read sections 1-4 in note by Lau
- [x] Define type safety for STLC
- [x] Define Logical Relations for type safety for STLC
- [x] Prove the two intermediate lemmas
- [x] Read parts I and II of types and programming languages
- [x] Watch videos on Blackboard

## System F w/ recursive functions. The Language
- [x] Write in language (System F w/rec) in report
- [x] Define and prove "Evaluation under Context" lemma for System F w/rec
  - [x] Define k = [] or Val(e) lemma. Show 1 case
  - [x] Write in complete EuC lemma
  - [x] Proof read

## Contextual Equivalence
- [x] Define Contextual Equivalence for System F w/rec
- [x] Write in Contextual Equivalence
- [x] Explanation and intuition
  - [x] Talk about CE being enough for integers
  - [x] Talk about CE being enough for non-base types (specifically function type)
    - [x] Show congruence rule for function application, and argue it's correctness, and why it is enough (see google photos)
- [ ] Mention the other, equivalent way of defining Contextual Equivalence (see google photos)
  - [ ] Congruence Rules
  - [x] Adequacy
  - [ ] To a large extend, prove they are equivalent
    - [x] ctxeq(forallC) => congruence (we showed one rule) and adequate (google photo)
    - [ ] other direction: (google photo)
      - [x] main proof
      - [x] define helper lemma
      - [ ] prove helper lemma
        - [x] define reflexivity lemma
        - [x] prove reflexivity lemma
          - [x] show one case (Tlam)
        - [ ] show cases
          - [ ] base [*]
          - [ ] add
          - [ ] fst
          - [ ] rec
          - [ ] app
          - [ ] Tlam
- [ ] Fix type-setting
  - [x] ctx-equiv -> CE
  - [x] type environment and variable environment (tctx -> venv)
  - [ ] refactor judgements
- [ ] Define Congruency and Adequacy as separate properties
  - [ ] In case of reflexivity and Lemma 6, state only for relations having congruency (and possibly well-typedness).
- [ ] Finish writing text
- [ ] Proof read

## Logical Relations
- [x] Define a logical relations model for CE
- [x] Write in LR
  - [x] val- and exp-interpretation
  - [x] varenv- and typenv-interpretation
- [ ] Fix type-setting
- [ ] Prove compatibility lemmas (only unit and add with well-typedness)
  - [x] Unit
  - [x] Add
  - [ ] Match (if-similar, but simpler)
  - [ ] Fst
  - [ ] Rec
  - [ ] App
  - [ ] Tlam
  - [ ] Tapp (if space)

## Using the Logical Relations


## Report Writing


## Exam period
- [ ] Watch exam video on Blackboard