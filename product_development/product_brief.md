# Product Brief: RedactedToolName "CR" v1
 
*Notes:*
* *All the contents of this document have been scrubbed of real names, references to tools/systems/hardware, and any other otherwise sensitive or potentially proprietary information.*
* *This document is regularly maintained in Atlassian Confluence, so some minor changes have been made to accommodate the formatting constraints outside of Confluence.*
* *All contents of this document are my own work, though not an exhaustive representation of my inputs. I have chosen to omit some sections where the inputs were supplied by other parties to limit the scope of this document to examples of my own work for the purposes of evaluating my skillset and capabilities.*
* *This write-up was in support of a new feature to an existing custom software solution, so there is context that the full project/product team already had regarding the tools referenced that may not be fully captured in this document.*

## Table of Contents
* [Product Summary](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#product-summary-parent-level)
  * [Product Details](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#product-details)
  * [Summary](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#summary)
    * [Problem Statement](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#problem-statement)
    * [Opportunity](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#opportunity)
  * [Business Value/Success Metrics](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#business-value--success-metrics)
    * [Impact](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#impact)
    * [Reach](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#reach)
    * [Time Criticality](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#time-criticality)
    * [Metrics](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#metrics)
  * [Stakeholders](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#stakeholders)
  * [Roadmap](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#roadmap)
  * [Page Tree](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#page-tree)
* [Research: RedactedToolName "CR" v1 - Child Page, level = 1](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#research-redactedtoolname-cr-v1-child-page-level--1)
  * [Research Questions](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#research-questions)
  * [Method](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#method)
  * [Findings](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#findings)
    * [Requirements](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#requirements)
  * [Links/Documentation](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#linksdocumentation)
* [Additional Content](https://github.com/JaimieLD/pdm_portfolio/blob/main/product_development/product_brief.md#additional-content)

## Product Summary (Parent Level)
<"Macro": Table of Contents | type = flat | maxLevel = 1>

### Product Details
<!--need to do some formatting on this table still-->
<table>
  <tr>
    <td><b>Team/Pod</b></td>
    <td>CM Pod</td>
  </tr>
  <tr>
    <td><b>Application</b></td>
    <td>RedactedToolName</td>
  </tr>
  <tr>
    <td><b>Product Lead</b></td>
    <td>Jaimie Davis</td>
  </tr>
  <tr>
    <td><b>Design Lead</b></td>
    <td>UXLeadName</td>
  </tr>
  <tr>
    <td><b>Engineering Lead</b></td>
    <td>DevLeadName</td>
  </tr>
  <tr>
    <td><b>Initiative(s)</b></td>
    <td><"Macro": Jira | Key = BEAR-####></td>
  </tr>
</table>

### Summary

#### Problem Statement

The "ECR" (RedactedToolName) process presently is the largest bottleneck in the overall "CM" process for the RedactedBusinessUnitInfo. Specifically, the ability to initiate the process as well as identify status, actions/next steps, and responsible parties for actions does not exist so "ECR" tickets stagnate at various stages of their lifecycle for weeks, months, or in extreme cases years before being closed out.

#### Opportunity

By utilizing RedactedToolName APIs to surface up "ECR" tickets within the RedactedToolName interface, users would be able to quickly drill down to view open actions assigned to them and easily navigate into supporting workflows within one cohesive UI, allowing for immediate action to be taken. Simply by surfacing up the data in a navigable way, RedactedToolName would drastically reduce the cycle time of the "CM" process. By further integrating and automating inputs between the "ECR" ticket and the "IA" step, there would be a drastic reduction in touch-time for executing on the activities as well as a reduction in human error in the inputs.

### Business Value / Success Metrics

#### Impact

Streamlined "CR" management will lead to a drastic reduction in overall "CM" process cycle time as "CRs" have been identified as the largest bottleneck in the overall process.

#### Reach

A successful tool supporting the "CR" process would be leveraged by, at minimum, the entire "CDMA" and "RE" community – a user base of approximately ### individuals. The dashboard & search functionality could have broader usage across the business than can presently be estimated. (Possible user base of #,###+ individuals.)

#### Time Criticality

There are inefficient work arounds available today, so this effort is not blocking production efforts. However, there is a high error rate with the manual work arounds, so the goal is to provide MVP functionality within 1-quarter and then to reevaluate needs and urgency for follow-up iterations.

#### Metrics

<table>
 <tr>
  <th>Qualitative Feedback</th>
  <th>Quantitative Feedback</th>
 </tr>
 <tr>
  <td>
   <ul>
    <li>Customer satisfaction survey prior to launch and after launch (UX + Product)
    <ul>
     <li>Perceived time savings (by persona)
    </ul>
    <li>Analyze rejection reasons
    <li>Determine why approvals are cleared
    <li>Understand if dashboard has helped users
   </ul>
  </td>
  <td>
   <ul>
    <li>Customer satisfaction survey prior to launch and after launch (UX + Product)
    <li>Number of "CRs" created in RedactedToolName
    <li>Data quality (analyze the number of edits)
    <li>RedactedToolName dashboard (weekly monitoring)
    <li>Number of help desk inquiries / number of clicks on the help icon
    <li>Track number of times the approvals are cleared
   </ul>
  </td>
 </tr>
</table>
<table>
 <tr>
  <th></th>
  <th>KPI</th>
  <th>Collection Method(s)</th>
  <th>Owner(s)</th>
  <th>Frequency</th>
  <th>Timing</th>
  <th>Target(s)</th>
 </tr>
 <tr>
  <td rowspan=2><b>Qualitative</b></td>
  <td>"CR" rejection reason analysis</td>
  <td>Manual Analysis</td>
  <td>
   <ul>
    <li>Researcher
    <li>UX Lead
    <li>Product Analyst
   </ul>
  </td>
  <td>Bi-Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>TBD - need to first determine baseline</td>
 </tr>
 <tr>
  <td>"CR" approval reason analysis</td>
  <td>Manual Analysis</td>
  <td>
   <ul>
    <li>Researcher
    <li>UX Lead
    <li>Product Analyst
   </ul>
  </td>
  <td>Bi-Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>TBD - need to first determine baseline</td>
 </tr>
 <tr>
  <td rowspan=2><b>Both</b></td>
  <td>Customer Satisfaction Baseline</td>
  <td>Survey</td>
  <td>
   <ul>
    <li>Reseacher
    <li>UX Lead
    <li>Product Analyst
   </ul>
  </td>
  <td>1 time</td>
  <td>30-days prior to go-live</td>
  <td>n/a</td>
 </tr>
 <tr>
  <td>Customer Satisfaction</td>
  <td>Survey</td>
  <td>
   <ul>
    <li>Researcher
    <li>UX Lead
    <li>Product Analyst
   </ul>
  </td>
  <td>1 time</td>
  <td>30-days post go-live</td>
  <td>##%+ increase in scoring results from baseline</td>
 </tr>
 <tr>
  <td rowspan=4><b>Quantitative</b></td>
  <td>Number of "CRs" created via RedactedToolName</td>
  <td>RedactedToolName</td>
  <td>
   <ul>
    <li>Technical Project Manager
    <li>Product Analyst
   </ul>
  </td>
  <td>Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>Week 1: ##<br>Weeks 2+: ##% increase week over week</td>
 </tr>
 <tr>
  <td>Data quality analysis (# of edits)</td>
  <td>RedactedToolName</td>
  <td>
   <ul>
    <li>Technical Project Manager
    <li>Product Analyst
   </ul>
  </td>
  <td>Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>##% of all "CRs" created for the week</td>
 </tr>
 <tr>
  <td>Number of help desk inquiries vs. clicks on help icon</td>
  <td>RedactedToolName</td>
  <td>
   <ul>
    <li>Technical Project Manager
    <li>Product Analyst
   </ul>
  </td>
  <td>Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>Help desk inquiries ##% of help icon interacts</td>
 </tr>
 <tr>
  <td>Number of approvals cleared</td>
  <td>RedactedToolName</td>
  <td>
   <ul>
    <li>Technical Project Manager
    <li>Product Analyst
   </ul>
  </td>
  <td>Weekly</td>
  <td>Begin 1-week post go-live</td>
  <td>TBD - need to first determine baseline</td>
 </tr>
</table>

---

### Stakeholders

* RedactedName; Sr Mgr, "ECDM"
* RedactedName; Director, "EDI"
* RedactedName; "PASE"
* RedactedName; Analyst, "CDM"

---

### Roadmap

<"Macro": Advanced Roadmaps for Jira in Confluence | url = placeholder>

---

### Page Tree

<"Macro": Children Display | depth=2>

## Research: RedactedToolName "CR" v1 (Child Page, level = 1)

<"Macro": Table of Contents | type = flat | maxLevel = 1>

### Research Questions
*This content was captured in a separate research plan document for this feature.* <br>
Research plan document: <Link | url>

---

### Method

The primary method for research on this effort will be 1:1 interviews and job shadowing with "CDMAs" and "REs".

---

### Findings

As an "RE"/"ME", from within RedactedToolName I should be able to…
* See the two initial navigation options within RedactedToolName at the time of this feature development, which should be
  * Manage "CRs" (below)
  * "IA" (linked, already active)
  
Conceptual experience/navigation walk-through (subject to change based on UX design & development inputs):
* Navigate to a **"MCRs"** “dashboard”
  * From this dashboard be provided with:
    * An option to "CNCR"
      * This selection should take a user to a webform that prompts for all inputs required to supply the "CR" data back to a RedactedToolName "ECR" ticket type (example <"Macro": Jira | Key = BEAR-####>)
        * All interactions for this process to occur natively within the RedactedToolName tool itself with RedactedToolName "CR" functionality acting as a database rather than a user facing interface
        * Development on this to support modularity for future onboarding of other programs who do not utilize the same RedactedToolName ticket type – however, initial development will only support the "ECR" ticket type
        * Leverage dynamic interactions with RedactedToolName to support this functionality and allow for easier expansion to other ticket types to support additional "EPs"
      * Once the "CR" has been created the user should be taken to their **"MCR"** dashboard where the newly created "CR" will be displayed in the **"MOCR"** queue
    * **"MOCR"**
      * Below the **"CNCR"** option should be a section displaying all of the active user’s presently open "CRs"
        * Where…
          * RedactedToolName active user = Reporter
        * Information displayed should include
          * "CR" summary field as hyperlink to the native display of the "CR"
          * Status
          * Assignee
          * Last Updated
          * Selection: **"SIA"**
            * This should take the user to the "IA" module within RedactedToolName
              * If possible – can any RedactedInfo search data be derived from the "CR" ticket to automate the "IA" search when accessed from this screen?
                * If yes – please proceed with that option
                * If no – take the user to the standard starting screen of the <”IA”> module
              * Remaining interaction should take the user through **"IA" (link)** and **"CRSCA" (link)**
          * Selection: **"AA"**
            * Once "IA" has been conducted and the necessary artifacts and subtasks (via "CRSCA" (link)) attached to the "CR", the RedactedToolName Active User should have the ability to
              * Increment the Workflow forward to the Pending Approval/Pending Review Status
              * Assign to Approver
    * **"CRPMA"**
      * Below the **"MOCR"** section under **"MCR"** should be a section displaying all of the open "CRs" pending the active user’s approval
        * Where…
          * Status = Ready for Approval / Ready for Review
          * Assignee = Active RedactedToolName User
            * Assumption here is that the Approver will become the Assignee at this step – this assumption needs to be validated
          * Information displayed should include
            * "CR" summary field as hyperlink to the native display of the "CR"
            * Status
            * Reporter
            * Last Updated
            * Selection: **"RCR"**
              * Redundant function with the hyperlinked summary field but creates a distinct call to action for the user
    * **"CRPMC"**
      * Below the **"CRPMA"** section under <”MCR”> should be a section displaying all of the open "CRs" pending the active user’s closure
        * ***Open Question***: Can we derive this status from the workflows available?
          * Proposed where…
            * Status = Approved
            * All subtasks = Closed
            * Assignee = RedactedToolName Active User
              * Assumption here is that the Closer will become the Assignee at this step – this assumption needs to be validated
            * Information displayed should include
              * "CR" summary field as hyperlink to the native display of the "CR"
              * Status
              * Reporter
              * Last Updated
              * Selection: **"CCR"**
                * Redundant function with the hyperlinked summary field but creates a distinct call to action for the user

#### Requirements

<table>
 <tr>
  <th colspan=4>"CR" Dashboard Epic: <"Macro": Jira | Key = BEAR ####></th>
 </tr>
   <tr>
    <th>Requirement</th>
    <th>Summary</th>
    <th>Short Description</th>
    <th>Jira Ticket</th>
   </tr>
   <tr>
    <td rowspan=8>Quick List Pages</td>
    <td rowspan=8>Display the list of "CRs" and Subtasks for ReactedPrograms. The <b>All "ECRs"</b> list displays all the "CRs".<br><br>The other quick list pages display "CRs" and Subtasks (except for the <b>I'm an approver</b> page because there are no Subtask Approvers).</td>
    <td>Add <b>"CRs"</b> to RedactedToolName Navigation</td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td><b>All "ECRs"</b> Quick List</td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td><b>I'm an assignee</b> Quick List</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td><b>I'm a reporter</b> Quick List</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td><b>I'm an approver</b> Quick List</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td><b>I'm watching</b> Quick List</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Quick Lists with no "CRs" and Subtasks</td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Number of Records in Quick Lists</td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Pagination</td>
    <td>Paginated quick lists to handle displaying the large number of "CRs" and Subtasks.</td>
    <td>Pagination</td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Filtering</td>
    <td></td>
    <td>Project Filter for <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td rowspan=7>Filtering</td>
    <td rowspan=7>Each quick list's filters vary, but the core filters are: Project, Reporter, Assignee, Label, Status, Component, Fix Version, and Type.</td>
    <td>Reporter, Assignee, & Label Filters for <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Status Filter for <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Component and Fix Version Filters for <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Filters for <b>I'm an approver</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Filters for <b>I'm an assignee</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Filters for <b>I'm a reporter</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Filters for <b>I'm watching</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td rowspan=2>Searching</td>
    <td rowspan=2>Exact match search on the "CR"/Subtask's Key field. Partial match search on the "CR"/Subtask's Summary field.</td>
    <td>Search <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Search <b>I'm an Assignee/Reporter/Approver/Watching</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td rowspan=2>Sorting</td>
    <td rowspan=2>Ascending and descending sorting on selected fields.</td>
    <td>Sort <b>All "ECRs"</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
   <tr>
    <td>Sort <b>I'm an Assignee/Reporter/Approver/Watching</b></td>
    <td><"Macro": Jira | Key = BEAR-###></td>
   </tr>
</table>

---

### Links/Documentation

* links to external documentation utilized in research efforts

---

## Additional Content

The following are additional sections that would be built out as part of a Product Brief - over the course of Discovery - in partnership with Dev. However, details have been omitted due to sensitivity of information contained.

* Development: RedactedToolName "CR" v1 (Child Page, Level = 1)
  * Development Estimates
    * Developer Level of Effort (LOE) Estimates
    * Roadmap
  * Development
    * App Access
    * Code Access
    * API Documentation
    * Architecture
    * Data Model
    * Security Strategy
    * Quality Assurance
    * Links / Documentation
* Delivery: RedactedToolName "CR" v1 (Child Page, Level = 1)
  * User Evaluation
  * Pilot Program
    * Summary
      * Goals
      * Pilot Results Readout
      * Links
    * Metrics
    * Logistics
      * Timing
      * Target Audience
      * Activities
      * Pilot Release Checklist
  * Release Checklist
  * Communication Plan
  * Training Plan
  * Links / Documentation
