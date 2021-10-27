# Questions

- do we need to ever write rho(e) and e[typ/X], given that there are no types in our expressions?
    - Otherwise, how do I get through Tlam and Tapp cases?
    no we don't

Value interpretation:
    define a well-typedness relation, e.g. W, and say in all below that that the values are in the W relation W[t]_rho(v1,v2)

- Is my value interpretation for function type correct?
    changed language

- Expression interpretation 
    (forall v . e ->* v ==> exists v' . e' ->* v' /\ V[t]_{rho}(v, v')) /\ (forall v' . e' ->* v' ==> exists v . e ->* v /\ V[t]_{rho}(v, v'))
    - could this work? it may shorten the proofs quite a bit (if we only show one side of the /\ )
    Change language...
    ∀v1,v2.e1⇓v1∧e2⇓v2=⇒ VJτKρ(v1,v2)

- Cng-rec
    - How do we use the initial assumption?
        - How do we instantiate it?
            see google photo
    

- Cng-Tlam
    - Should I prove well-typedness in this case. It seems relevant.
    no

- Should I show substitution lemma? It has been shows in notes by Lau.
    refer to Lau