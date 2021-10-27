# Questions

- do we need to ever write rho(e) and e[typ/X], given that there are no types in our expressions?
    - Otherwise, how do I get through Tlam and Tapp cases?

- Is my value interpretation for function type correct?

- Expression interpretation 
    (forall v . e ->* v ==> exists v' . e' ->* v' /\ V[t]_{rho}(v, v')) /\ (forall v' . e' ->* v' ==> exists v . e ->* v /\ V[t]_{rho}(v, v'))
    - could this work? it may shorten the proofs quite a bit (if we only show one side of the /\ )

- Cng-rec
    - How do we use the initial assumption?
        - How do we instantiate it?

- Cng-Tlam
    - Should I prove well-typedness in this case. It seems relevant.

- Should I show substitution lemma? It has been shows in notes by Lau.