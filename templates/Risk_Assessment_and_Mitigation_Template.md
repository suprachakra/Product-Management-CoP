# Risk Assessment and Mitigation Template

Use the ROAM (Resolved, Owned, Accepted, Mitigated) model to proactively manage risks and keep delivery on track.

## Risk Fields

| Field                | Description                                                    | Example                                      |
|----------------------|----------------------------------------------------------------|----------------------------------------------|
| **Risk Description** | Brief summary of the identified risk                          | “Potential delay in 3rd party API”           |
| **Likelihood**       | Probability of occurrence (e.g., High/Med/Low or 1–5 scale)   | High                                         |
| **Impact**           | Severity if the risk materializes (High/Med/Low or 1–5 scale) | High                                         |
| **Risk Score**       | Likelihood x Impact                                           | 4 x 4 = 16                                   |
| **Owner**            | Person/team accountable                                       | Jane Doe                                     |
| **Mitigation Plan**  | Strategy for reducing or removing the risk                    | “Build fallback API mock”                    |
| **ROAM Status**      | Resolved, Owned, Accepted, Mitigated                          | Owned                                        |
| **Target Date**      | When the risk must be addressed                               | 2025-04-15                                   |

## Steps to Use
1. **Identify Risks**: During PI Planning, backlog grooming, or daily standups.
2. **Score & Prioritize**: High-risk (high-likelihood, high-impact) items must be tackled first.
3. **Develop Mitigation Plans**: Document in JIRA or Confluence.
4. **Track ROAM Status**: Update frequently to reflect progress or changes.
5. **Escalate as Needed**: If a high-risk item remains “Owned” but not actively mitigated, escalate to leadership or RTE.

## Example Table

| Risk                  | Likelihood | Impact | Owner     | Mitigation Plan                  | ROAM Status | Target Date |
|-----------------------|-----------:|-------:|----------|----------------------------------|------------|------------:|
| API Delay             | High (4)   | High(4)| Jane Doe | Build fallback mock to proceed   | Owned      | 2025-04-15 |
| Infrastructure Outage | Med (3)    | High(4)| John Doe | Set up failover environment      | Mitigated  | 2025-03-20 |

> **Tip**: During retrospectives, review resolved risks to capture lessons learned in the Knowledge Repository.

