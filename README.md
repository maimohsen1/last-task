
Comparison of Explainable AI (XAI) Techniques
LIME (Local Interpretable Model-Agnostic Explanations)

Type: Model-Agnostic

Advantages:

Easy to implement

Provides local explanations for individual predictions

Disadvantages:

Explanation changes depending on the sample

Slower with large models

Best Use Case:
Explaining individual predictions

SHAP (SHapley Additive exPlanations)

Type: Model-Agnostic (or Specific with Tree Explainer)

Advantages:

Highly accurate

Provides contribution value of each feature

Consistent explanations

Disadvantages:

Computationally heavy with large datasets

More complex to understand

Best Use Case:
Explaining individual predictions or the entire model

Partial Dependence Plot (PDP)

Type: Model-Agnostic

Advantages:

Easy to plot and interpret

Shows the average effect of a feature on predictions

Disadvantages:

Assumes feature independence (which might not hold in practice)

Best Use Case:
Explaining the average effect of a particular feature

Counterfactual Explanations (DiCE)

Type: Model-Agnostic

Advantages:

Answers "what-if" scenarios

Suggests actionable changes to input

Disadvantages:

Slow with large models

Sometimes generates impractical counterfactuals

Best Use Case:
Generating actionable, human-understandable alternatives
