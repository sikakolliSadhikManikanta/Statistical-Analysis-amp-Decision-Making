## Industry-Style Hypothesis Validation (Policy Decision)

### Objective:The objective of this analysis is to determine whether properties with more than 2 bathrooms command significantly higher prices compared to properties with 2 or fewer bathrooms.
## Business Problem
A housing policy group believes that larger properties with additional bathrooms attract premium market prices.
This analysis validates the claim using statistical hypothesis testing.
## Statistical Test Used
#Independent Two-Sample T-Test
This test is appropriate because:
* Two independent groups are being compared
* Group 1: Properties with more than 2 bathrooms
* Group 2: Properties with 2 or fewer bathrooms
* Property price is a numerical variable
## Hypotheses
### Null Hypothesis (H₀)
Properties with more than 2 bathrooms do not command higher prices.
### Alternative Hypothesis (H₁)
Properties with more than 2 bathrooms command higher prices.
## Significance Level
α = 0.05
A 5% significance level is used for the hypothesis test.
## Methodology
1. Load and preprocess the dataset
2. Separate properties into two groups based on bathroom count
3. Perform an Independent Two-Sample T-Test
4. Compare p-value with significance level
5. Draw statistical and business conclusions
## Interpretation of p-value
* If:
p-value < 0.05
Reject the null hypothesis.
This indicates strong statistical evidence that properties with more than 2 bathrooms command premium prices.
* Otherwise:
Fail to reject the null hypothesis.
This indicates insufficient evidence to support the claim.
## Business Recommendation
If the null hypothesis is rejected:
* Developers should prioritize larger homes with additional bathrooms
* Policymakers may encourage development of premium residential properties
* Bathroom count can be considered an important pricing factor in housing policy decisions
If the null hypothesis is not rejected:
* Bathroom count alone may not significantly influence premium pricing
* Additional factors such as location, parking, and property type should also be considered
## Conclusion
This analysis helps policymakers and developers understand whether bathroom count significantly impacts property pricing and supports data-driven housing decisions.
