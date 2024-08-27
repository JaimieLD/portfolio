# BusinessUnit Resource Business Case
**Software Development**<br>
Jaimie Davis | MM-DD-YYYY

## Table of Contents
* [Efficiency Gains - Tool]()
  * [Assumptions]()
  * [Time-Phased Impacts to BusinessUnit]()
    * [Q2-YYYY]()
    * [Q3-YYYY]()
    * [Q4-YYYY]()
    * [Q1-YYYY]()
    * [Q2-YYYY]()
  * [Estimated Labor Cost Reduction Summary]()
* [Resource & Staffing Analysis]()
  * [Prior Estimate (Q4-YYYY)]()
  * [Proposed Path Forward (Thru Q2-YYYY)]()
    * [Technical Product Manager]()
    * [UX Researcher/Designer]()
    * [Developer]()
    * [Delivery Manager]()
    * [Quality Assurance]()
  * [Impacts of Prematurely Reducing Staffing Resources]()
* [Additional Context]()
  * [False Equivalencies]()
  * [Lessons Learned from Elsewhere at Company]()
    * [BusinessUnit Today]()
    * [SoftwareTeam]()
* [Appendix A - Persona Level Impacts]()
* [Disclaimer]()

## Efficiency Gains - Tool
### Assumptions
<table>
  <tr>
    <th></th>
    <th>Assumption</th>
    <th>Basis</th>
  </tr>
  <tr>
    <td>A</td>
    <td>Current headcount of impacted population = 400</td>
    <td>
      <ul>
        <li>Estimate from "Adam" = 400</li>
        <li>Estimate from "Bob" (via "Casey") = 400</li>
      </ul>
    </td>
  </tr>
 <tr>
  <td>B</td>
  <td>Estimated headcount of impacted population by EOY YYYY = 45%
    <ul>
     <li>Quarterly growth Q2-Q4 = 15%</li>
    </ul>
  </td>
  <td>
     <ul>
       <li>Estimate from "Devin" – currently at 620 FTE in BusinessUnit, expected to be at 900 by EOY = 45% growth</li>
     </ul>
  </td>
 </tr>
 <tr>
  <td>C</td>
  <td>
   Population impacted by Tool = 42.5%
   <ul>
    <li>i.e. 42.5% of EDO would be directly impacted by this tool</li>
   </ul>
  </td>
  <td>
   <ul>
    <li>Estimate from "Evan" of 20%-50% - average = 35%</li>
    <li>Estimate from "Bob" (via "Casey") = 50%</li>
   </ul>
  </td>
 </tr>
 <tr>
  <td>D</td>
  <td>
   Workload impacted for relevant personnel = 26%
   <ul>
    <li>i.e. of the 42.5% of the impacted personnel, this tool would impact the equivalent of 26% of their workload</li>
   </ul>
  </td>
  <td>
   <ul>
    <li>Estimate from "Evan" of 5%-20% - average = 12.5%</li>
    <li>Estimate from "Bob" (via "Casey") of 10%-20% - average = 17.5%</li>
    <li>Estimate from "Fiona" & "Gavin" = 47.5% <sup>1</sup></li>
    <ul>
     <li>CA = 95%</li>
     <li>IPTL = 10%</li>
     <li>TE is 25%-50% - average = 37.5%</li>
     <li>CDM = 80%</li>
     <li>DL is 5%-25% - average 15%</li>
    </ul>
   </ul>
  </td>
 </tr>
 <tr>
  <td>E</td>
  <td>Process Automation = 90%</td>
  <td>
   <ul>
    <li>A buffer for the pieces of the process that may have been included in above estimates that cannot be automated</li>
   </ul>
  </td>
 </tr>
 <tr>
  <td>F</td>
  <td>Hourly rate of cost to Company = $190/hr</td>
  <td>
   <ul>
    <li>Provided by "Casey"</li>
   </ul>
  </td>
 </tr>
 <tr>
  <td>G</td>
  <td>
   Core functions of Tool (identified to date) to bring online at each major version release = 9
   <ul>
    <li>Est. 11% of efficiency gain realized per major release</li>
   </ul>
  </td>
  <td>
   <ul>
    <li>Provided by "Casey"</li>
    <ol>
     <li>Overall System Architecture</li>
     <li>IA</li>
     <li>RE/ME/SE Usage Redesign</li>
     <li>CM Read/Write</li>
     <li>DNG/P6 Integration</li>
     <li>SWAT/BU Onboarding</li>
     <li>Data Reduction (BU)</li>
     <li>Gated Review</li>
     <li>System Experiences</li>
    </ol>
   </ul>
  </td>
 </tr>
 <tr>
  <td>H</td>
  <td>
   2080 labor hours per year
   <ul>
    <li>520 labor hours per quarter</li>
   </ul>
  </td>
  <td>
   <ul>
    <li>Assuming a standard base of 40-hour weeks</li>
   </ul>
  </td>
 </tr>
</table>

<sup>1</sup> See [Appendix A]() for full write-up from "Fiona" - not all personas reflected in this calculation as not all had easily derived values.

### Time-Phased Impacts to BU
#### Q2-YYYY
<table>
 <tr>
  <td align='right'>400<br>+10%</td>
  <td align='left'>Starting Headcount (HC), See Assumption A<br>Prorated Projected Growth for Quarter</td>
 </tr>
 <tr>
  <td align='right'><b>440</b><br>x 42.5%</td>
  <td align='left'><b>Total Quarter HC</b><br>See Assumption C</td>
 </tr>
 <tr>
  <td align='right'><b>187</b><br>x 26%</td>
  <td align='left'><b>Impacted Population of HC</b><br>See Assumption D</td>
 </tr>
 <tr>
  <td align='right'><b>48.6</b><br>x 90%</td>
  <td align='left'><b>HC Equivalent of Impacted Work</b><br>See Assumption E</td>
 </tr>
 <tr>
  <td align='right'><b>43.8</b><br>x 44%</td>
  <td align='left'><b>HC Equivalent of Automation</b><br>See Assumption G <sup>2</sup></td>
 </tr>
 <tr>
  <td align='right'><b>19.3</b><br>x 520</td>
  <td align='left'><b>HC Equivalent of Delivered Functionality</b><br>See Assumption H</td>
 </tr>
 <tr>
  <td align='right'><b>10,012</b><br>x $190</td>
  <td align='left'><b>Impacted Labor Hours for Q2-YYYY</b><br>See Assumption F</td>
 </tr>
 <tr>
  <td align='right'><b><i>$1,902,248</i></b></td>
  <td align='left'><b><i>Est. Labor Cost Reduction Q2-YYYY</i></b></td>
 </tr>
</table>

<sup>2</sup> Items 1-4 from Assumption G anticipated to be fully online and operational by end of Q2-YYYY.

#### Q3-YYYY
<table>
 <tr>
  <td align='right'>440<br>+15%</td>
  <td align='left'>QTR Starting Headcount (HC), See Assumption A<br>Prorated Projected Growth for Quarter</td>
 </tr>
 <tr>
  <td align='right'><b>506</b><br>x 42.5%</td>
  <td align='left'><b>Total Quarter HC</b><br>See Assumption C</td>
 </tr>
 <tr>
  <td align='right'><b>215.1</b><br>x 26%</td>
  <td align='left'><b>Impacted Population of HC</b><br>See Assumption D</td>
 </tr>
 <tr>
  <td align='right'><b>55.9</b><br>x 90%</td>
  <td align='left'><b>HC Equivalent of Impacted Work</b><br>See Assumption E</td>
 </tr>
 <tr>
  <td align='right'><b>50.3</b><br>x 66%</td>
  <td align='left'><b>HC Equivalent of Automation</b><br>See Assumption G <sup>3</sup></td>
 </tr>
 <tr>
  <td align='right'><b>33.2</b><br>x 520</td>
  <td align='left'><b>HC Equivalent of Delivered Functionality</b><br>See Assumption H</td>
 </tr>
 <tr>
  <td align='right'><b>17,270</b><br>x $190</td>
  <td align='left'><b>Impacted Labor Hours for Q3-YYYY</b><br>See Assumption F</td>
 </tr>
 <tr>
  <td align='right'><b><i>$3,281,377</i></b></td>
  <td align='left'><b><i>Est. Labor Cost Reduction Q3-YYYY</i></b></td>
 </tr>
</table>

<sup>3</sup> Items 1-6 from Assumption G anticipated to be fully online and operation by end of Q3-YYYY.

#### Q4-YYYY
<table>
 <tr>
  <td align='right'>506<br>+15%</td>
  <td align='left'>QTR Starting Headcount (HC), See Assumption A<br>Prorated Projected Growth for Quarter</td>
 </tr>
 <tr>
  <td align='right'><b>582</b><br>x 42.5%</td>
  <td align='left'><b>Total Quarter HC</b><br>See Assumption C</td>
 </tr>
 <tr>
  <td align='right'><b>247.3</b><br>x 26%</td>
  <td align='left'><b>Impacted Population of HC</b><br>See Assumption D</td>
 </tr>
 <tr>
  <td align='right'><b>64.3</b><br>x 90%</td>
  <td align='left'><b>HC Equivalent of Impacted Work</b><br>See Assumption E</td>
 </tr>
 <tr>
  <td align='right'><b>57.9</b><br>x 77%</td>
  <td align='left'><b>HC Equivalent of Automation</b><br>See Assumption G <sup>4</sup></td>
 </tr>
 <tr>
  <td align='right'><b>44.6</b><br>x 520</td>
  <td align='left'><b>HC Equivalent of Delivered Functionality</b><br>See Assumption H</td>
 </tr>
 <tr>
  <td align='right'><b>23,171</b><br>x $190</td>
  <td align='left'><b>Impacted Labor Hours for Q4-YYYY</b><br>See Assumption F</td>
 </tr>
 <tr>
  <td align='right'><b><i>$4,402,515</i></b></td>
  <td align='left'><b><i>Est. Labor Cost Reduction Q4-YYYY</i></b></td>
 </tr>
</table>

<sup>4</sup> Items 1-7 from Assumption G anticipated to be fully online and operation by end of Q4-YYYY.
