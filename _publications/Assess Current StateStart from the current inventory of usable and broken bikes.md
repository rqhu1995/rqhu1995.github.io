1. **Assess Current State**:

   - Start from the current inventory of usable and broken bikes.

2. **Calculate Effective Sensitivity**:

   - For each potential adjustment (either reducing usable bikes or broken bikes), consider the change in dissatisfaction relative to the target usable inventory.

   - Normalize the sensitivities to a common scale, or use a combined metric to ensure fairness in comparison.

     Effective Sensitivity for Usable Bikes:
     $$
     S_{usable} = \frac{\text{dissat}[p, b] - \text{dissat}[p\pm1, b]}{\text{dissat}[p, b]}
     $$

     Effective Sensitivity for Broken Bikes:
     $$
     S_{broken} = \frac{\text{dissat}[p, b] - \text{dissat}[p, b-1]}{\text{dissat}[p, b]}
     $$

3. The color at grid represents the reduction rate on dissatisfaction if one usable bike (p1) or broken bike (p2) is handled at the point. P3 shows the reduction rate to optimal inventory at the point.

![image-20240602155416605](/Users/hurunqiu/Library/Application Support/typora-user-images/image-20240602155416605.png)

Always choose $\max(S_{usable}, S_{broken})$ conduct one bike load/unload, update the inventory, move the black point, compare until other constraints are violated. Basically use this sensitivity to guide the operation.

Or: Define some general sensitivity to directly split the two

1. $$
   \text{Time for usable} = \text{total time budget} \times \frac{S_{usable}}{S_{total}}
   $$
   $$
   \text{Time for broken} = \text{total time budget} \times \frac{S_{broken}}{S_{total}}
   $$

---

For problem of 