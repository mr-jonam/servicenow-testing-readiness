# ServiceNow Testing Readiness: decision guide

Ask clearer questions about upgrades and workflow change.

**For:** ServiceNow product owners, workflow owners and QA leads discussing upgrades or configuration changes.

**Decision in focus:** What evidence would explain the effect of a workflow change to its owner?

## Describe the workflow outcome

Start with the person requesting a service and the person expected to fulfil it. An approval, assignment or notification can matter to the business even when the initial submission succeeds. These are examples to guide the conversation, not an instance-specific risk analysis.

**Question to discuss:** What should a requester and fulfiller both be able to confirm?

## Put ATF in its documented context

ServiceNow publishes Automated Test Framework documentation by release family. Use the official entry point to check current capabilities and supported scope for your instance. Do not infer full workflow coverage from the presence of ATF or a number of automated checks.

**Question to discuss:** Which acceptance question needs evidence beyond the current automation discussion?

## Include access and external handovers

Ask whether the change affects role visibility, approvals, a portal or an external integration. A technical result and an accepted service outcome may need different explanations. Discuss safe non-production boundaries with the authorised platform owner.

**Question to discuss:** Which handover or role could make the workflow behave differently?

## Bring uncertainty to the upgrade conversation

A useful brief names the change category and business workflow without exposing instance URLs, configuration exports, ticket contents or access details. Platform-family references are starting points and must be checked against the target release.

**Question to discuss:** Who decides what unresolved evidence is acceptable for the change?

## Read next

Read [source status and retrieval limitations](SOURCES.md), try the local mini tool using the [README instructions](README.md#start-here), or [discuss the question on LinkedIn](https://www.linkedin.com/in/manoj-rollo/). A short, non-confidential outline is enough. Professional assessment or delivery is separately scoped. This guide does not assess a system or approve a release.
