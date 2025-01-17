# Stochastic Lot Sizing
There are three possible scenarios for the demand in each period. All three scenarios are as probable to occur (probability = 0.33).

Values for possible demands can be seen in the table below.

![image](https://github.com/user-attachments/assets/09da434f-cee1-4c49-9703-81caa088f73a)

Assume production capacity per period is c = 150 units, setup costs s = 100 EUR, inventory holding cost k_l = 1 EUR/unit/period, backlog cost k_b = 3 EUR/unit/period, initial inventoy level L0 = 0 units.

## Solution Approach
Step 1: Set the production decision with respect to expected demand

Step 2: Generate some samples based on possible demand probability

Step 3: Calculate expected costs for each sample/scenario

Step 4: Calculate average expected costs
