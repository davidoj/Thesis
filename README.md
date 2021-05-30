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

## Chapter 3: Two player statistical models

- Traditional statistical models are ''player one'' models (where that ''player one'' is ''nature'')
    - This can be motivated directly supposing probabilities model the long run behaviour of mechanisms, or via exchangeability in the Bayesian setting
- A simple generalisation: two-player models, where only one player is ''nature''
    - Common formulations of decision problems require ''player two'' statistical models
    - ''Counterfacutal'' questions also require ''player two''
    - We can add ''player one'' either via mechanisms or functional exchangeability - result: two player statistical models
- Causal inference imposes an additional constraint: observations cannot be affected by player two's actions
    - See-do models
    - See-do models are closely related to Statistical Decision Theory:
        - See-do model + utility = statistical decision problem
        - See-do model + decision rule + utility = risk
        - Complete class theorem
        - Statistical model dominance
        - Causal dominance*

## Chapter 4: See-do models vs alternatives

- There are a lot of alternative causal models:
    - Causal Bayesian Networks (normal/''abductive'' variations)
    - Structural Causal Models (normal/''abductive'' variations)
    - ''Heckman structural equation models''
    - Potential outcomes models (unit/population variations)
    - Single world intervention graphical models
    - ''Dawid decision-theoretic models''
    - ''Heckerman deterministic decision-theoretic models''
    - Lattimore/Rohde Bayesian causal models
- They're all see-do models with two main axes of differentiation:
    - Double exchangeable vs not doubly exchangeable (abductive vs non-abductive)
    - Deterministic vs stochastic (potential outcomes exist vs not exist)
- Two additional ways to differentiate models that aren't as much discussed:
    - Side effects vs no side-effects 
    - Prior vs no prior

## Chapter 5: Getting from "see" to "do"/Inference principles

- D-causation/D-control
- Imitability and contextual imitability

## Chapter 6: God's computer?

- Are causal models marginals of ''God's computer'', or do we need alternative justifications?
- Theorem: You can't "do" a contradiction + God's computer records necessarily related variables + consistency of marginals => God's computer is not a "do-intervention" causal model (even with cycles)
- Do-interventions have an alternative justification via imitability + maximum entropy

## Chapter 7: Conclusion

- Conclude whatever ends up coming before