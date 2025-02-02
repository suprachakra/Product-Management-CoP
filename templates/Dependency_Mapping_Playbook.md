# Dependency Mapping Playbook

A standardized approach to identifying, tracking, and resolving dependencies in a scaled Agile environment.

## Step-by-Step Guide

1. **Identify Dependencies**
   - During PI Planning, refine backlog items to spot cross-team or external vendor needs.
2. **Log Dependencies in JIRA**
   - Create custom fields: Dependency Name, Owning Team, Blocking Team, Status, Due Date
   - Use **Link Issues** functionality for cross-issue references.
3. **Visualize in Miro (Optional)**
   - Represent each team as a node; draw lines for dependencies, color-coded by priority/status.
4. **Set Escalation Rules**
   - E.g., if a dependency is overdue by >5 days, auto-notify RTE and relevant stakeholders.
5. **Monitor & Resolve**
   - Use a weekly “Dependency Standup” or incorporate into standard ART ceremonies.

## Example JIRA Fields

| Field            | Description                     | Example                           |
|------------------|---------------------------------|-----------------------------------|
| **Dependency**   | Short name/ID for the dependency| “Payment Gateway Integration”      |
| **Owning Team**  | Team responsible for resolving  | Team A                            |
| **Blocking Team**| Team blocked until resolved     | Team B                            |
| **Status**       | Not Started / In Progress / Done| “In Progress”                     |
| **Due Date**     | Target resolution date          | 2025-03-01                        |

## Best Practices
- Keep dependencies visible at all times (JIRA dashboards, Miro boards, Confluence pages).
- Regularly check for overdue dependencies to prevent hidden bottlenecks.

## Recommended Automation
- Configure JIRA automation to:
  - **Notify** relevant Slack/Teams channels when a dependency is created or updated.
  - **Escalate** to RTE if status is unchanged for >5 days.


