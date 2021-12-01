# Questions

- lam hoisting
  - has well-typedness been shown ok?
yes

- in lemma 9 i.h. remove c: (...)?
  - unsure about this 
keep c.

- normalisation and type-safety.
  - does this mean that all well typed expressions reduce to a value?
  yes
  - or is it only normalisation which is required for this?
  no. normalisation is only to normal form - non-reducbile. but with type-safety, we get normalisation to values
  - also isn't our language strongly normalising?
  yes, but we don't need it.

normalisation proof
- we actually prove this in our logical relation. using fundamental theorem we can prove it using the expression relation.

determinacy
% if e -> e1 and e -> e2, then e1 = e2.
% other theorem becomes corollary.

- Empty type. What is it? how does it relate to the theorem I have proved?

- Identity. How does this relate to theorems for free?
  - in other words, what is a free theorem?
  - parametricity?

- are values types and elctx technically part of the syntax?
statics and dynamics
they are part of the statics
expressions is syntax. but they are all statics
- restructure to statics and dynamics

- What should introduction and conclusion entail?
- What should "Comparison to Other Work and Ideas for Future Work" entail?
  - Already have some ideas. Are they good?
  - maybe merge ideas for future work and conclusion?