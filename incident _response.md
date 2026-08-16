# Incident Response

## 1. Purpose

This document sets out a practical procedure for identifying, containing, and resolving technical incidents affecting Vipto's product or infrastructure, distinct from the ordinary bug-fixing process described in [`workflow.md`](./workflow.md).

## 2. What Qualifies as an Incident

An incident is an unplanned event that disrupts, degrades, or compromises the availability, integrity, or security of Vipto's product or systems, as distinct from a routine bug affecting a non-critical feature under normal operating conditions.

## 3. Bug Versus Production Incident

A defect identified during development or testing, before it reaches users, is treated as an ordinary bug and handled through the standard workflow described in [`workflow.md`](./workflow.md). A defect or disruption affecting the live, released product is treated as a production incident and follows the elevated process described in this document.

## 4. Severity Levels

Incidents are assessed on a severity basis reflecting their actual impact: incidents that render the product unusable for a significant proportion of users, or that involve a security compromise, are treated as high severity; incidents that degrade functionality without rendering the product unusable are treated as medium severity; and incidents with limited, narrow impact are treated as low severity, with response urgency scaled accordingly.

## 5. Who Should Be Informed

Any contributor or intern identifying a suspected incident should immediately inform the Engineering Lead, and, where the incident has a security dimension, should also follow the reporting process described in [`security.md`](./security.md).

## 6. Immediate Containment

Where reasonably possible, immediate steps are taken to limit the impact of the incident, which may include reverting a recent release, disabling an affected feature, or restricting access to an affected system, pending fuller investigation.

## 7. Investigation

Following containment, the team investigates the root cause of the incident, drawing on logs, recent changes, and any other relevant information, to understand what happened and what is required to resolve it fully rather than only its immediate symptoms.

## 8. Communication Through Teams

Incident response is coordinated in real time through Microsoft Teams, allowing the relevant contributors to stay aligned on the status of containment, investigation, and resolution as the incident is worked through.

## 9. GitHub Issue Creation

Once the immediate response is underway, a GitHub Issue is created to document the incident, its identified cause, and the fix being developed, ensuring the incident is tracked through Vipto's standard workflow once the acute phase has passed.

## 10. Fix Development

A fix for the underlying cause of the incident is developed following the standard development process described in [`workflow.md`](./workflow.md), expedited as appropriate to the severity of the incident.

## 11. Testing

The fix is tested with particular attention to confirming that it resolves the incident without introducing a new regression, given the elevated risk associated with an expedited release.

## 12. Deployment

Once tested and approved, the fix is deployed following the release process described in [`release.md`](./release.md), with deployment approval obtained even where the process is expedited due to incident severity.

## 13. Monitoring

Following deployment of a fix, the affected system is monitored to confirm the incident has been fully resolved and has not recurred or manifested in a related form elsewhere in the product.

## 14. Resolution

An incident is considered resolved once the underlying cause has been fixed, the fix has been deployed and verified, and any residual impact on users has been addressed to the extent reasonably possible.

## 15. Documentation

Following resolution, the GitHub Issue and any related Confluence documentation are updated to reflect the final resolution, providing a complete record of the incident for future reference.

## 16. Post-Incident Review

For incidents of medium or high severity, the team conducts a brief post-incident review to understand what allowed the incident to occur and whether any process, testing, or monitoring gap contributed to it.

## 17. Preventive Actions

Where the post-incident review identifies a preventable contributing factor, corresponding preventive action is identified and tracked as a GitHub Issue, so that the improvement is actually implemented rather than remaining only a lesson noted informally.

## 18. Engineering Lead Escalation

The Engineering Lead holds overall responsibility for coordinating incident response, and any contributor uncertain about how to proceed during a suspected incident should escalate directly to the Engineering Lead without delay.
