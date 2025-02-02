# WSJF Backlog Prioritization Template

Use this template to calculate and track Weighted Shortest Job First (WSJF) scores for each backlog item.

## Fields (Recommended in JIRA or Spreadsheet)
1. **Business Value (BV)**: 1–10
2. **Time Criticality (TC)**: 1–10
3. **Risk Reduction (RR)**: 1–10
4. **Job Size (JS)**: 1–10
5. **WSJF** = (BV + TC + RR) / JS

## Example Table

| Backlog Item | BV  | TC  | RR  | JS  | WSJF (auto-calc) | Notes                                                |
|--------------|-----|-----|-----|-----|------------------|------------------------------------------------------|
| Item A       | 8   | 7   | 5   | 5   | (8+7+5)/5 = 4    | Potential for immediate customer impact             |
| Item B       | 3   | 9   | 6   | 6   | (3+9+6)/6 = 3    | Time-sensitive due to regulatory deadline           |

## Instructions
1. **Assign values** for BV, TC, RR, and JS based on team consensus.
2. **Sort backlog** by WSJF descending. High WSJF = highest priority.
3. **Review regularly**: Update scores as new info emerges.

> **Tips**  
> - Keep scoring consistent across teams by defining guidelines for each 1–10 rating.  
> - Combine with a Risk/ROAM board to highlight items that also mitigate major risks.

