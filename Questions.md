# Questions

- Congruence Rule for T-var?
    use cgr-var, not cgr-var2
- Congruence Rule for T-rec (and other that use variables like T-match)?
    var's should be the same on both sides
- Name of rules. Is Cgr-... fine?
    cng maybe
- Is the proof of reflexivity correct?
    immediate from I.H on congruency rules.
    show 1 case
- What is the induction hypothesis in proof of lemma (R(..., e, e',...) and C => R(..., C(e), C(e'), ...)?
    forall the normal lemma. in other words
        forall xi, gamma, xi', gamma', e, e', tau, tau'. ... and C': ... => ... C'[e], C'[e]...
        (type of C' in I.H. unchanged... since it is forall quantified. In other words, only C changes to C')
    Reason about the type of C and C' in each case
  - Which cases should I prove?
        base []
        add
        fst
        rec
        app
        Tlam
        
    state with R only having congruency.

- Which compatibility lemmas should I prove?
    var
    add
    match (if similar, but simpler)
    fst
    rec
    app
    Tlam
    if space Tapp
- Is it correct that, after proving compatibility lemmas and adequacy of LR, then fundamental theorem follows from proof of reflexivity of R?
  - it follows fairly quickly by direct proof; each compatibility lemma corresponds to one case in the induction proof
  - but do we not also just get it from R is reflexive lemma?
  yes, we get it from R is reflexive lemma.
  define congruency and adequacy before defining CE. In proof of reflexivity, just state that a relation R with congruency is reflexive.