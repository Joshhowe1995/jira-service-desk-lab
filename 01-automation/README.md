# Jira Service Management – Automation

This section demonstrates the use of Jira Service Management automation rules to streamline service desk workflows.

The focus is on reducing manual effort, enforcing consistency, and improving response times for common service requests.

---

## Automation Scenario: New Employee Onboarding – Auto Triage

This automation rule is triggered when a **New Employee** request is created via the service portal.

The rule automatically:
- Assigns ownership to the appropriate team member
- Sets ticket priority
- Transitions the ticket to the correct workflow state

---

## 01 – Automation Rule Overview

**Screenshot:** Jira Automation Overview

This screen shows the complete automation rule configured within Jira Service Management.

**Trigger**
- Work item created

**Condition**
- Request Type is one of: New employee

**Actions**
- Edit work item fields (Assignee, Priority)
- Transition work item to **In Progress**

---

## 02 – Automation Applied to Ticket

**Screenshot:** Jira automation applied

This screen confirms the automation rule running successfully against a live request.

The ticket:
- Is automatically assigned
- Has priority set without manual input
- Is moved to **In Progress** immediately after creation
