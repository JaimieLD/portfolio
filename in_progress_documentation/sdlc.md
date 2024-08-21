## Example Software Development Lifecycle (SDLC) Diagram

```mermaid

flowchart LR

subgraph C Suite
id01((High Level Product Strategy))
id04[Product Pitch/Vetting]
id14((Vetted, No))
end

id01 --"No"--> id14
id01 --"Yes"--> id04
id04 --"Yes"--> id12

subgraph Customer Success & Analytics
id02((Customer Feedback))
id03((Team Recommendation))
id05[Vetting]
id06((Vetted, No))
id07{Recommend Platform Product}
end

id02 --> id05
id03 --> id05
id05 --"No"--> id06
id05 --"Yes"--> id07

subgraph Product Management
id08((Team Recommendation))
id09[Vetting]
id10((Vetted, No))
id11{Decision Intake}
id12{Platform Decision}
id13[Discovery]
end

id08 --> id09
id09 --"No"--> id10
id09 --"Yes"--> id11
id07 --"Yes"--> id11
id11 --> id12
id12 --"Yes"--> id13
id13 --> id21

subgraph Development
id15((Team Recommendation))
id16[Vetting]
id17((Vetted, No))
id18{Engineering Roadmap?}
id19[Technical Feasibility]
id20[Project Planning]
id21[Development]
id22[Pre-release Testing]
id23{Acceptance Testing}
end

id15 --> id16
id16 --"No"--> id17
id16 --"Yes"--> id18
id18 --"No"--> id11
id18 --"Yes"--> id19
id19 --> id20
id20 --> id21
id21 --> id22
id22 --> id23

```

---

## Notes & Additional Context

* The production version of this document was built in Lucidchart utilizing BPMN2.0 - I have done my best to recreate this diagram using a Mermaid flowchart, however there will be some missing notation that isn't supported by Mermaid
* The following activities also have subprocesses under each of them, also captured in the Lucidchart version:
  * Adaptive Services Development
  * Discovery
