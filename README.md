## Model Specification

$$\log(M_i) = \alpha_{t[i]} + \beta_{p[i]} \times G_i$$


### Where:
- **$$Mᵢ$$** = the estimated market value of player *i*
- **$$\alpha_{t[i]}$$** = Multilevel intercept allowing team-specific variations ~ Normal(α_bar, σ_team)
- **$$α_bar$$** = Mean intercept across all teams ~ Normal(0, 1.5)
- **$$σ_team$$** = Standard deviation to account for team-wise variance ~ Exponential(1)
- **$$\beta_{p[i]}$$** = Slope parameter of goal involvements categorized by position played ~ Normal(0, 0.5)
- **$$Gᵢ$$** = Goal involvements of player *i*

Player position will be a categorical variable, and their team will be a multilevel variable.
