# OfficeLuv Incident Response Protocol

## Diagnosing Severity
### Severity 1: Critical
Impairs and prevents customer operations and/or affects our bottom line. Incidents with severity 1 must be dealt with immediately. (i.e. All Hands On Deck)
Some examples include:
- Customers not being able to log in.
- Customers not being able to purchase.
- Unable to bill our customers.

### Severity 2: Moderate
Prevents internal operations but operations has a workaround. Incident will require some level of internal communication. (i.e. Look At)
Some examples include:
- Humanity is down and staff cannot clock in/out.

### Severity 3: Low
Impairs internal operations but does not prevent them. Incident may or may not require internal communication. Severity 3 incidents are resolved as bugs in the current sprint. (i.e. Ignore For Now)

## Roles in an Incident Response
### Incident Commander
- The primary decision-maker in the incident
- Responsible for communicating the incident across the organization
- Source of truth for the status of the incident
- Delegates as necessary
- Only one person can hold the role of the Incident Commander

### Solutioneer
- Responsible for solving the incident
- Can be one or more people

### Marketing/Communications
- Communicates out to external users
- Works closely with the Incident Commander

## Process for Handling a Severity 1 Incident
- An incident is reported. (i.e. call from ops, Heroku alert)
- We alert the team of the incident in person or via text. This communication will state the severity level and topic of the incident. Members must respond to severity 1 incidents immediately.
- We will move into the Slack channel designated for incident reports, #SitRep. In the channel, we will restate the severity and topic of the incident. Members will also state the role they will hold during this incident.
- The #SitRep channel will serve as a running log of how the incident is being handled. (i.e. a migration has happened, a deploy has gone out)

## Process for Post Mortem
Once the incident has been resolved, a formal situation report will be generated that answers the following questions:
- What was the incident that was reported?
- What time was the incident reported?
- What time was the incident closed?
- What was the response time?
- Who played a role in the incident?
- What was the solution?
- Who did this incident impact?
- How were they impacted?

The post-mortem will also be attached.
The team will also generate a post-mortem that will serve as a retrospective. It will contain associated learnings from the incident.
The Incident Commander will email the situation report to stakeholders.
All these documents will be attached to the topic in the #SitRep Slack channel for future access.

## Next Steps
We need to create a runbook detailing technical steps in case of handling an incident:
- The deployment process

We need training drills to confidently handle incident responses.
