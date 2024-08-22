# TeamA-TeamB SLA's Project Plan

*Notes:*

## Table of Contents
 * [Project Roles & Responsibilities](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#project-roles--responsibilities)
 * [Project Charter & Objectives](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#project-charter--objectives)
 * [What is in scope?](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#what-is-in-scope)
 * [What is not in scope?](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#what-is-not-in-scope)
 * [Critical Milestones & Timeline](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#critical-milestones--timeline)
   * [Re-planning Activities](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#re-planning-activities)
     * [Completed](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#completed)
   * [Updated Project Plan (Jira)](https://github.com/JaimieLD/pdm_portfolio/blob/main/in_progress_documentation/project_plan_sla.md#updated-project-plan-jira)

## Project Roles & Responsibilities
<table>
  <tr>
    <th>Project Lead</th>
    <td><li>Jaimie Davis, TeamB</li></td>
    <th>Project Team</th>
    <td><li>SR Data Engineer, TeamB</li><li>Data Analyst, TeamA</li><li>Director, TeamA</li></td>
  </tr>
  <tr>
    <th>Stakeholders and Approvers</th>
    <td colspan=3><li>SR Director, TeamA</li><li>SR Director Data Science, TeamB</li><li>Analytics Manager, TeamB</li></td>
  </tr>
  <tr>
    <th>Draft Agreement (Output)</th>
    <td colspan=3>Link to agreement doc</td>
  </tr>
  <tr>
    <th>Epic</th>
    <td colspan=3><"Macro": Jira | BEAR-####></td>
  </tr>
</table>

## Project Charter & Objectives
As Company aims to mature it’s tools and processes related to mission critical data, it’s also crucial to define the expectations and needs between data providers and data consumers. The objective of this project is to stand-up a skeleton structure of SLA’s between TeamA (data provider) and TeamB (data consumer) to serve as a stop-gap measure until such time as the ET sponsored data contracts project has been fully executed.

## What is in scope?
* A standardized process for assigning issue severity to data issues surfaced by TeamB that uses objective reasoning and data to inform the severity ranking relative to company goals and initiatives
* A set of expectations pertaining to both (1) the inputs provided by TeamB to properly triage data issues and (2) the escalation handling of data issues by TeamA

## What is not in scope?
* Dictating SLA’s between TeamA as a data consumer and source systems, such as SystemA, as data providers - this scope is encompassed by the ET sponsored data contracts initiative

## Critical Milestones & Timeline
### Re-planning Activities
#### Completed
- [x] Jaimie Davis | Reach out to Director, TeamA to obtain SLO's project timelines from ET
- [x] Jaimie Davis | Coordinate project dependencies and/or parallel path efforts as needed based on ET timelines vs. desired timelines from TeamB Stakeholder(s)
- [x] Jaimie Davis | Update Jira accordingly to reflect TeamB project plan for SLA's implementation, including due dates and overall timelines

### Updated Project Plan (Jira)
<table>
  <tr>
    <th>Activity</th>
    <th>Responsible</th>
    <th>Due Date</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>BEAR-#### - Updated Project Plan & Jira Tickets [CLOSED]</td>
    <td><li>Jaimie Davis, TeamB</li></td>
    <td>MMM DD, YYYY</td>
    <td>[COMPLETE]</td>
  </tr>
  <tr>
    <td>Data Contracts Kick-off Meeting</td>
    <td><li>Director, TeamA</li><li>Data Analyst, TeamA</li></td>
    <td>MMM DD, YYYY</td>
    <td>[COMPLETE]</td>
  </tr>
  <tr>
    <td>BEAR-#### - 1st Draft Agreement [CLOSED]</td>
    <td><li>Jaimie Davis, TeamB</li><li>Director, TeamA</li></td>
    <td>MMM DD, YYYY</td>
    <td>[COMPLETE]</td>
  </tr>
  <tr>
    <td>BEAR-#### - Incorporate Project Team Feedback [IN PROGRESS]<br><br>BEAR-#### - Severity Issue Ranking Feedback [CLOSED]<br><br>BEAR-#### - Rank Outstanding Tickets to Vet Rubric [IN PROGRESS]</td>
    <td><li>Jaimie Davis, TeamB</li><li>SR Data Engineer, TeamB</li><li>Data Analyst, TeamA</li><li>Director, TeamA</li></td>
    <td>MMM DD, YYYY</td>
    <td>[IN PROGRESS]</td>
  </tr>
  <tr>
    <td>BEAR-#### - Approver Review [REQUESTED]</td>
    <td><li>Jaimie Davis, TeamB</li></td>
    <td>MMM DD, YYYY</td>
    <td>[NOT STARTED]</td>
  </tr>
  <tr>
    <td>BEAR-#### - Deprecate Old Documents [REQUESTED]</td>
    <td>Jaimie Davis, TeamB</td>
    <td>MMM DD, YYYY</td>
    <td>[NOT STARTED]</td>
  </tr>
</table>

### ET Timelines for SLO's

The below information was provided by Director, TeamA via Teams on MMM DD, YYYY.

*Hi Jaimie, ET has a plan to develop the concept of 'data contracts' to address data-specific SLO's. Our first milestone is to document how Company will use data contracts, and define them for that purpose, by end of Q-. I scheduled a review with your team in mid-MMM to gather early feedback. Here's the overall goal in the context of the ET plan:*
<table>
  <tr>
    <td><i>Business Value</i></td>
    <td><i>Operational Excellence: Improve ET</i></td>
    <td><i>Centralized and compliant business systems for process streamlining, cost reduction, data quality improvements</i></td>
    <td><i>Enterprise Architecture: Service Management Maturity</i></td>
    <td><i>Develop and implement a management framework for data contracts. Data contracts are documented agreements between data producers and consumers that define, basically, the structure, format, and rules for exchange. Data contracts ensure that downstream consumers of data are not impacted by upstream operational deficiencies, and when they do occur, there is a documented and agreed-to response for resolution (aka SLOs). The framework should integrate with other business continuity processes, such as Service Tiers, SLOs, Issue Severity, and RCA.</i></td>
    <td><i><ol><li>Conceptualization of data contracts for Company (Q-)</li><li>Publish draft framework (Q-)</li><li>Execute pilot(s) (Q-)</li><li>Burn down of all in-scope interfaces (Q- - Q-)</li></ol></i></td>
  </tr>
</table>

## Risk Management

table here

## Communications & Touch Points

### Upcoming Meetings
- [x]

### Open Action Items
- [x]

## Meeting Notes
### MM/DD/YYYY Data issues severity brainstorm 2 of 2
notes here
