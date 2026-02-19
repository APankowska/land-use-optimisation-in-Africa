# land-use-optimisation-in-Africa
Linear Programming project analysing optimal land allocation on a 500-acre farm in Africa. The maximises profit under land, labour, budget, and capacity constraints, including livestock and crop decisions. Developed as part of a Management Science coursework using mathematical optimisation techniques. 


# Linear Programming & Management Science Project
## Project Overview
This project presents a mathematical optimisation model developed to determine the optimal allocation of land and resources on a 500-acre farm in Africa.

The objective was to maximise total profit while considering real-world constraints such as:
 - Land availability (500 acres)
 - Seasonal labour limitations
 - Livestock housing capacity
 - Budget constraints
 - Grazing requirements
 - Weather impact scenarios
 - Asset depreciation (advanced model)
   
The project was completed as part of a Management Science coursework and includes three progressively developed optimisation models.


## Problem Context
The farm operates under limited financial and physical resources and must decide:
 - How many cows and chickens to keep
 - How much land to allocate to crops (tea, coffee, wheat)
 - How to distribute labour across seasons
 - How to remain profitable under environmental uncertainty
   
The challenge was to build structured optimisation models that reflect realistic agricultural constraints.


## Model 1 – Base Linear Programming Model
#### Objective:
Maximise total annual profit from:
 - Livestock (cows, chickens)
 - Crops (tea, coffee, wheat)
   
#### Decision Variables:
 - Number of cows (NCOW)
 - Number of chickens (NCHN)
 - Acres of tea (T)
 - Acres of coffee (CFF)
 - Acres of wheat (W)
   
#### Constraints:
 - Total land ≤ 500 acres
 - Grazing land (2 acres per cow)
 - Barn capacity (cows)
 - Coop capacity (chickens)
 - Budget ≤ £20,000
 - Labour hours per season

   
#### Outcome:
Model 1 provided the optimal combination of crops and livestock under standard conditions, identifying which activities generated the highest marginal contribution to profit.


## Model 2 – Extended Model with Seasonal & Environmental Factors
Model 2 introduced more realistic constraints:
 - Seasonal labour distribution
 - Tighter operational restrictions
 - Sensitivity to resource limitations
   
#### Key Improvements:
 - Better reflection of real farming conditions
 - Analysis of bottlenecks (labour vs land vs budget)
 - Identification of limiting constraints
   
#### Insight:
Labour availability became a critical constraint in certain seasons, directly affecting optimal crop allocation.


## Model 3 – Advanced Scenario Analysis
Model 3 incorporated:
 - Weather variability scenarios
 - Asset depreciation effects
 - Financial risk considerations
   
#### Purpose:
To analyse how environmental uncertainty impacts:
 - Profitability
 - Production decisions
 - Resource allocation
   
#### Key Insight:
The optimal solution changes under adverse weather conditions, highlighting the importance of diversification and risk management in agricultural planning.


## Results Summary
Across the three models:
 - Profitability was highly sensitive to labour and grazing constraints
 - Crop allocation shifted depending on environmental assumptions
 - Livestock decisions were influenced by housing and budget limitations
 - Advanced modelling improved strategic planning quality
   
The progressive modelling approach demonstrated how increasing model complexity improves decision-making realism.


## Recommendations
Based on the modelling results:
 - Optimise land allocation dynamically depending on seasonal labour availability.
 - Diversify crop production to reduce weather-related risk.
 - Monitor labour constraints carefully, as they significantly impact profitability.
 - Consider long-term asset depreciation in strategic planning.
 - Maintain a balance between livestock and crops to reduce operational risk.

   
## Conclusion
This project demonstrates how Linear Programming and optimisation techniques can support data-driven agricultural decision-making in resource-constrained environments.

The three-model approach illustrates:
 - The value of incremental model development
 - The importance of incorporating real-world constraints
 - The impact of uncertainty on optimal strategies
   
The project combines mathematical modelling, analytical reasoning, and applied management science to solve a realistic optimisation problem.


## Tools & Techniques
 - Linear Programming
 - Mathematical Optimisation
 - Constraint Modelling
 - Scenario Analysis
 - Sensitivity Analysis
 - FICO Xpress

   
