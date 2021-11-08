# Questions

- what should the environments be in the examples?

- Identity
  - show just (e _) v ->* v or also e ctx-equiv Lambda lambda x. x?
  
- Empty type
  - can't we instantiate "forall t1, t2, R . ..." with two different types (say Z and B), and then the empty relation? then we get * | * |- e' : Z and * | * |- e : B, would that be a contradiction, or do I need to prove that no such e' exists (or is this in fact what we are proving with the proof)?