## Example Software Development Lifecycle (SDLC) Diagram

```mermaid

%% last used ID = id26

flowchart LR

subgraph C Suite
id01((High Level Product Strategy))
id04[Product Pitch/Vetting]
id14((Vetted, No))
id26[Leadership Acceptance]
id37[Additional Client Communications]
id38((Release Complete))
end

id01 --> id04
id04 --"No"--> id14
id04 --"Yes"--> id12
id23 --> id26
id26 --> id28
id36 --> id37
id37 --> id38

subgraph Customer Success & Analytics
id02((Customer Feedback))
id03((Team Recommendation))
id05[Vetting]
id06((Vetted, No))
id07{Recommend Platform Product}
id24[Adaptive Services Development]
id25[User Acceptance Testing]
id26{Platform?}
id27{Pass?}
id28{Pass?}
id29[Deployment]
id30[Documentation]
id35{Communication Intake}
id36[Release Communications]
end

id02 --> id05
id03 --> id05
id05 --"No"--> id06
id05 --"Yes"--> id07
id05 --"No"--> id24
id24 --> id25
id23 --> id25
id25 --> id26
id26 --"No"--> id27
id26 --"Yes"--> id28
id27 --"No"--> id24
id27 --"Yes"--> id29
id29 --> id30
id30 --> id35
id35 --> id36
id28 --"No"--> id21
id28 --"Yes"--> id31

subgraph Product Management
id08((Team Recommendation))
id09[Vetting]
id10((Vetted, No))
id11{Decision Intake}
id12{Platform Decision}
id13[Discovery]
id31{Deployment Activities}
id32[Documentation]
end

id08 --> id09
id09 --"No"--> id10
id09 --"Yes"--> id11
id07 --"Yes"--> id11
id11 --> id12
id12 --"Yes"--> id13
id13 --> id21
id31 --> id32
id31 --> id33
id32 --> id35

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
id33[Deployment]
id34[Release Notes & Technical Documentation]
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
id33 --> id34
id34 --> id35

```

---

## Notes & Additional Context

* The production version of this document was built in Lucidchart utilizing BPMN2.0 - I have done my best to recreate this diagram using a Mermaid flowchart, however there will be some missing notation that isn't supported by Mermaid
* The following activities also have subprocesses under each of them, also captured in the Lucidchart version:
  * Adaptive Services Development
  * Discovery
* This diagram represents the SDLC I developed for implementation within an organization that did not have any prior SDLC standard in place
  * While this process is built on predefined standards for SDLC, it is tailored to the unique size, composition, and needs of the team that I implemented this for
