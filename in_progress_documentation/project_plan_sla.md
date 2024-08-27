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
    <td colspan=3><"Macro": Jira | JIRA-####></td>
  </tr>
</table>

## Project Charter & Objectives
As Company aims to mature it’s tools and processes related to mission critical data, it’s also crucial to define the expectations and needs between data providers and data consumers. The objective of this project is to stand-up a skeleton structure of SLA’s between TeamA (data provider) and TeamB (data consumer) to serve as a stop-gap measure until such time as the ET sponsored data contracts project has been fully executed.

## What is in scope?
* A standardized process for assigning issue severity to data issues surfaced by TeamB that uses objective reasoning and data to inform the severity ranking relative to company goals and initiatives
* A set of expectations pertaining to both (1) the inputs provided by TeamB to properly triage data issues and (2) the escalation handling of data issues by TeamA

## What is not in scope?
* Dictating SLA’s between TeamA as a data consumer and source systems, such as SystemA, as data providers - this scope is encompassed by the BusinessUnit sponsored data contracts initiative

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
    <td>JIRA-#### - Updated Project Plan & Jira Tickets [CLOSED]</td>
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
    <td>JIRA-#### - 1st Draft Agreement [CLOSED]</td>
    <td><li>Jaimie Davis, TeamB</li><li>Director, TeamA</li></td>
    <td>MMM DD, YYYY</td>
    <td>[COMPLETE]</td>
  </tr>
  <tr>
    <td>JIRA-#### - Incorporate Project Team Feedback [IN PROGRESS]<br><br>JIRA-#### - Severity Issue Ranking Feedback [CLOSED]<br><br>JIRA-#### - Rank Outstanding Tickets to Vet Rubric [IN PROGRESS]</td>
    <td><li>Jaimie Davis, TeamB</li><li>SR Data Engineer, TeamB</li><li>Data Analyst, TeamA</li><li>Director, TeamA</li></td>
    <td>MMM DD, YYYY</td>
    <td>[IN PROGRESS]</td>
  </tr>
  <tr>
    <td>JIRA-#### - Approver Review [REQUESTED]</td>
    <td><li>Jaimie Davis, TeamB</li></td>
    <td>MMM DD, YYYY</td>
    <td>[NOT STARTED]</td>
  </tr>
  <tr>
    <td>JIRA-#### - Deprecate Old Documents [REQUESTED]</td>
    <td>Jaimie Davis, TeamB</td>
    <td>MMM DD, YYYY</td>
    <td>[NOT STARTED]</td>
  </tr>
</table>

### ET Timelines for SLO's

The below information was provided by Director, TeamA via Teams on MMM DD, YYYY.

*Hi Jaimie, BusinessUnit has a plan to develop the concept of 'data contracts' to address data-specific SLO's. Our first milestone is to document how Company will use data contracts, and define them for that purpose, by end of Q-. I scheduled a review with your team in mid-MMM to gather early feedback. Here's the overall goal in the context of the BusinessUnit plan:*
<table>
  <tr>
    <td><i>Business Value</i></td>
    <td><i>Operational Excellence: Improve BusinessUnit</i></td>
    <td><i>Centralized and compliant business systems for process streamlining, cost reduction, data quality improvements</i></td>
    <td><i>Enterprise Architecture: Service Management Maturity</i></td>
    <td><i>Develop and implement a management framework for data contracts. Data contracts are documented agreements between data producers and consumers that define, basically, the structure, format, and rules for exchange. Data contracts ensure that downstream consumers of data are not impacted by upstream operational deficiencies, and when they do occur, there is a documented and agreed-to response for resolution (aka SLOs). The framework should integrate with other business continuity processes, such as Service Tiers, SLOs, Issue Severity, and RCA.</i></td>
    <td><i><ol><li>Conceptualization of data contracts for Company (Q-)</li><li>Publish draft framework (Q-)</li><li>Execute pilot(s) (Q-)</li><li>Burn down of all in-scope interfaces (Q- - Q-)</li></ol></i></td>
  </tr>
</table>

## Risk Management

<table>
  <tr>
    <th></th>
    <th>Date</th>
    <th>Submitted By</th>
    <th>Risk</th>
    <th>Mitigating Strategy</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>1</td>
    <td>MMM DD, YYYY</td>
    <td>Data Analyst, TeamA</td>
    <td>
      <ul>
        <li>Concern from Data Analyst, TeamA pertaining to BDF/TeamA being accountable for resolution of data issues originating at the source system level (ex. TeamA can only be as responsive to SystemA data issues as the SystemA team is to them when the issue originates at the SystemA level - such as with the API’s)</li>
        <ul>
          <li>The primary concerns identified and discussed pertained to SystemA data:</li>
          <ul>
            <li>The majority of data issues escalated to TeamA from TeamB have pertained to SystemA data, and as a result have then been escalated up to SystemA by the TeamA team</li>
            <li>The SysetmA team has been given the specific direction to prioritize development time and effort on developing functionality in support of manufacturing - only a small amount of team bandwidth is allocated to triaging and resolving bugs/issues</li>
            <li>TeamB (and BusinessUnit) are one customer among many who will be escalating these issues, so even a high priority issue for TeamB may not be determined by SystemA (or other groups) to be high priority relative to issues surfaced across the business</li>
          </ul>
        </ul>
      </ul>
    </td>
    <td>
      <ul>
        <li>Agreement to include a disclaimer than acknowledges the scope of source system SLA’s/SLO’s will be addressed by the data contracts initiative and that the agreement with TeamB solely pertains to the handling of issues escalated by TeamB - the desired outcomes will not be fully realized until the data contracts are in place</li>
        <li>Utilize the agreement between TeamA & TeamB to provide repeatable and scalable structure to how TeamB surfaced data issues are triaged</li>
        <ul>
          <li>Instead of TeamB self assigning prioritization of an issue, utilizing standardized inputs and a severity ranking matrix to assign priority to issues relative to impacts on business operations and goals</li>
        </ul>
      </ul>
    </td>
    <td>[MITIGATED]</td>
  </tr>
  <tr>
    <td>2</td>
    <td>MMM DD, YYYY</td>
    <td>SR Data Engineer, TeamB</td>
    <td>
      <ul>
        <li>Allowing impacts to BusinessOperation to have equal importance as something that goes in front of executive leadership and this having the end result of everything still being “high priority”</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Possible mitigating strategies: (1) add additional criteria to the impact and urgency tables or (2) migrate to a 4-dimensional ranking model</li>
      </ul>
    </td>
    <td>[MITIGATED]</td>
  </tr>
  <tr>
    <td>3</td>
    <td>MMM DD, YYYY</td>
    <td>Jaimie Davis, TeamB</td>
    <td>
      <ul>
        <li>BusinessUnit reprioritization of initiatives for YYYY - reduced support for SystemB may also have impacts on the prioritization of Data Contracts</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>The purpose of this project is to get the MVP solution in place that meets TeamB’s requirements until such time as Data Contracts are in place - as such it is built in/assumed that the outputs of this project need to be sufficient for an undetermined amount of time, which can also account for any schedule slips on Data Contracts due to resource reallocations on the BusinessUnit side.</li>
      </ul>
    </td>
    <td>[OPEN]</td>
  </tr>
</table>

## Communications & Touch Points

### Upcoming Meetings
- [x] MMM DD, YYYY 10:35am PT | SLA's/SLO's Huddle (Jaimie & Director, TeamA)
- [x] MMM DD, YYYY  9:00am PT | DaaS Service Tier - Questionnaire and Discussion
- [x] MMM DD, YYYY 11:00am PT | Data issue severity brainstorm 1 of 2
- [x] MMM DD, YYYY 11:30am PT | Data issue severity brainstorm 2 of 2
- [x] MMM DD, YYYY 11:30am PT | Data incidents - impact, urgency, and severity dry-run
- [x] MMM DD, YYYY 11:00am PT | Data contracts p4p review *(moved from MMM DD due to holiday)*

### Open Action Items
- [x] MMM DD, YYYY | Jaimie Davis to create draft agreement doc to work in
- [x] MMM DD, YYYY | Director, TeamA to draft proposed Jira structure/process for collecting the parameter inputs as well as the proposed severity ranking matrix
- [x] MMM DD, YYYY | SR Data Engineer, TeamB, <Jira macro | key = JIRA-####>

## Meeting Notes
### MM/DD/YYYY Data issues severity brainstorm 2 of 2
#### Attendees
* SR Data Engineer, TeamB
* Data Analyst, TeamA
* Jaimie Davis, TeamB
* Director, TeamA
* Analytics Manager, TeamB

#### Invite Details/Agenda (Director, TeamA)
*Following up with this group after an initial data contracts design session on Monday MM/DD. I’ll bring the outcome of that meeting here for prelim review, and also quickly coordinate a status update on any actions taken in session 1 of 2.*

#### Notes
* How could we capture financial impacts, or should we? (Previously had discussed revenue impacts - maybe to start this is a simple y/n rather than actually trying to quantify? Not necessarily trying to capture labor cost, machine hours cost, materials cost, or opportunity cost.)
* “Manufacturing” - possibly define this as including Production Schedule, overall concept: how do we use schedule as a more effective leading indicator when evaluating priority of data issues severity
* Overall risk/concern and proposed mitigating strategy
  * risk: allowing impacts to BusinessOperation to have equal importance as something that goes in front of executive leadership and this having the end result of everything still being “high priority”
  * possible mitigating strategies: (1) add additional criteria to the impact and urgency tables or (2) migrate to a 4-dimensional ranking model

#### Action Items
- [x] MMM DD, YYYY | SR Data Engineer, TeamB, <Jira macro | key = JIRA-####>

#### Risk(s) Discussed
<table>
  <tr>
    <td>
      <ul>
        <li>Allowing impacts to BusinessOperation to have equal importance as something that goes in front of executive leadership and this having the end result of everything still being “high priority”</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Possible mitigating strategies: (1) add additional criteria to the impact and urgency tables or (2) migrate to a 4-dimensional ranking model</li>
      </ul>
    </td>
  </tr>
</table>
