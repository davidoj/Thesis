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
    - Definition
    - Examples
- See-do models answer Pearl's three levels of questions:
    - What am I likely to see next? - see-only
    - What happens next if I do something? - resolvable to a hypothesis sufficient see-do
    - What would have happened if I had done something different? - not resolvable to hypothesis sufficient see-do
- Additional kind of question: "what *should* I do?" = "what happens if I do something?" + "what do I want to happen?"
    - Generates a statistical decision problem
    - Complete class theorem and Bayes decision rules
- Special cases of see-do models
    - Hypothesis sufficiency
    - D-causation/D-control

## Chapter 4: See-do models vs alternatives

- There are a lot of alternative causal models:
    - Causal Bayesian Networks (normal/''abductive'' variations)
    - Structural Causal Models (normal/''abductive'' variations)
    - ''Heckman structural equation models''
    - Potential outcomes models (general/treatment effects variations)
    - Single world intervention graphical models
    - ''Dawid decision-theoretic models''
    - ''Heckerman deterministic decision-theoretic models''
    - Lattimore/Rohde Bayesian causal models
- They're all see-do with two main axes of differentiation:
    - Extendably exchangeable or not (abductive vs non-abductive)
    - Deterministic vs stochastic (potential outcomes exist vs not exist)
- Two additional ways to differentiate models:
    - Side effects vs no side-effects 
    - Prior vs no prior

## Chapter 5: Getting from "see" to "do"/Inference principles

- Contextual imitability

## Chapter 6: God's computer?

- Are causal models marginals of ''God's computer'', or do we need alternative justifications?
- Theorem: You can't "do" a contradiction + God's computer records necessarily related variables + consistency of marginals => God's computer is not a "do-intervention" causal model (even with cycles)
- Do-interventions have an alternative justification via imitability + maximum entropy

## Chapter 7: Conclusion

- Conclude whatever ends up coming before