## Introduction

- Introduce whatever ends up coming next
- People like manipulating things, and want to know what happens after they've done some manipulations

## Chapter 2: Technical prerequisites

- Probability measures, Markov kernels
- Probability spaces, kernels spaces, "generalised" random variables
- Marginal distributions, conditional distributions
- String diagrams
    - With random variables
- Generalised conditional independence
- Representation of kernel spaces with product of disintegrations
- *Maybe:* D-separation equivalent in string diagrams

## Chapter 3: See-do models are all you need

- See-do models are statistical models with *options*
    - Hypothesis sufficiency
- See-do models answer Pearl's three levels of questions:
    - What am I likely to see next? - see-only
    - What happens next if I do something? - resolvable to a hypothesis sufficient see-do
    - What would have happened if I had done something different? - not resolvable to hypothesis sufficient see-do
- Additional kind of question: "what *should* I do?" = "what happens if I do something?" + "what do I want to happen?"
    - Generates a statistical decision problem
    - Complete class theorem and Bayes decision rules

## Chapter 4: See-do models vs alternatives

- Do-interventions
    - Theorem: You can't "do" a contradiction => can construct variable sets with no "hard" do-interventions (even with cycles!)
    - It's widely accepted that a causal graphical model with too few variables will yield "wrong" do-interventions
    - But a causal graphical model with too many variables has no do-interventions
    - Conclusion: do-interventions must be defined with respect to a canonical set of variables "not too small, not too big"
    - Comment: this seems like too many implicit contingencies for the basic notion of an action
    - The basic notion of an action in a see-do model: an element of the set of options
- Counterfactuals are more than "Potential Outcomes" (random variables with shared space + consistency):
    - Prop: Existence of a real variable *Y* + supposition *i* implies the existence of counterfactual *Y^i*
    - Prop: *Y := f(X)* implies *Y^i=f(X^i)*
    - Conclusion: "counterfactual sample spaces"


## Chapter 5: Getting from "see" to "do"/Inference principles

- Invariance (graphical models)
- Exchangeability (potential outcomes)
- Reproducibility (see-do models)


## Chapter 6: Conclusion

- Conclude whatever ends up coming before