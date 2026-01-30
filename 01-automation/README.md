
Jira Service Management – Automation

This section demonstrates the use of Jira Service Management automation rules to automatically triage and progress service desk requests.

The focus is on reducing manual effort, enforcing consistency, and improving response times for common request types.

Automation Scenario: New Employee Onboarding – Auto Triage

This automation rule is triggered when a New Employee request is created via the service portal.

The rule automatically:

Assigns ownership

Sets ticket priority

Transitions the ticket to the correct workflow state

01 – Automation Rule Overview

Screenshot: Jira Automation Overview.png

This view shows the complete automation rule configured within the Jira Service Management project.

Trigger: Work item created

Scope: Service desk project

Purpose: Automatically handle new employee onboarding requests

This demonstrates use of Jira’s rule-based automation and event-driven workflows.

02 – Trigger and Condition

Screenshot: Jira automation applied.png

The automation rule uses both a trigger and a condition to limit scope:

Trigger: Work item created

Condition: Request Type is New employee

This ensures only helpdesk onboarding requests are affected, preventing unintended automation on other ticket types.

03 – Automated Field Updates

Screenshot: Jira Automation Overview.png

Once the condition is met, the rule performs automated field updates:

Assigns the ticket to the correct agent

Sets priority to High

This removes the need for manual triage and ensures onboarding requests are handled promptly.

04 – Automated Workflow Transition

Screenshot: Jira Automation Overview.png

After field updates, the rule automatically transitions the ticket to:

Status: In Progress

This keeps workflow state aligned with real operational activity and avoids stalled tickets.

05 – Resulting Ticket State

Screenshot: New Employee Onboarding ticket view

The resulting ticket confirms the automation executed successfully:

Request type correctly identified

Priority applied automatically

Agent assigned

Status transitioned to In Progress

This demonstrates end-to-end automation execution.
