# Questions

- Empty type. What is it? how does it relate to the theorem I have proved?
    V X . X is empty – there are no values of that type. we can also derive that other types must then also be empty: composite types. we show it for expressions, which then implies values. Given our language is normalising, then we can show it generally for expressions since, if there are no values of an empty type, then there can't be any expressions of an empty type, since expressions will normalise to a value.


- Identity. How does this relate to theorems for free?
  - in other words, what is a free theorem?
        we only need to look at types to conclude something about the expression. 
        a standard way to prove theorems like this is using logical relations.


- What should introduction and conclusion entail?
    introduction: motivate
        program equivalence
        contextual equivalence is one notion of this. informal definition
        Then talk about the language and some of its features. We shall then talk about
        contextual equivalence in this language and see some interesting examples.
        Turns out we will need logical relations...

- What should "Comparison to Other Work and Ideas for Future Work" entail?
  - Already have some ideas. Are they good?
  - maybe merge ideas for future work and conclusion?
delete chapter. expand conclusion chapter to: conclusion and ideas for future work.



- LR model, LR, logical relation. Correct terminology.
  - Does it make sense to say that the LR model consists of value interpretation, expression interpretation, variable env interpretation, type env interpretation and the final LR predicate (xi, gamma |- e LR e' : t)?
  - Does it make sense to refer to the relation defined by the last predicate as LR?

The lr model is only the last part
we separate it into smaller points... value interpretations, expression interpretations and so on...


- getting more space
  - move evaluation under context proof to appendix
    - remove corollary from EuC together with proof
  - move proof of Identity: Contextual equivalence to appendix.
    - most of it is unfolding definitions and applying fundamental theorem, and in the end using identity: reduction and determinacy
  - Merge chapter 6 and 7. conclusion and ideas for future work.

- is my section on definition of LR (4.2) ok?


send report in after rewriting section 4.2
by the end of next week.