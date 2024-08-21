# Product Brief: ToolName "CR" v1
 
*Notes:*
* *All the contents of this document have been scrubbed of real names, references to tools/systems/hardware, and any other otherwise sensitive or potentially proprietary information.*
* *This document is regularly maintained in Atlassian Confluence, so some minor changes have been made to accommodate the formatting constraints outside of Confluence.*
* *All contents of this document are my own work, though not an exhaustive representation of my inputs. I have chosen to omit some sections where the inputs were supplied by other parties to limit the scope of this document to examples of my own work for the purposes of evaluating my skillset and capabilities.*
* *This write-up was in support of a new feature to an existing custom software solution, so there is context that the full project/product team already had regarding the tools referenced that may not be fully captured in this document.*

## Product Summary (Parent Level)
<"Macro": Table of Conents | type = flat | maxLevel = 1>

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

text here

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

table here

---

### Links/Documentation

text here

---

## Additional Content

text here
