# Analytics, Reporting, and Software Team Operating Model
## Table of Contents
* Team Structure
  * Functional
  * Operational

## Team Structure
### Functional
```mermaid

block-beta

columns 4

%% business hierarchy
id01["Organizational Hierarchy, Level 1:"]
id02["Company"]:3
id03["Organizational Hierarchy, Level 2:"]
id04["Business Unit"]:3
id05["Organizational Hierarchy, Level 3:"]
id06["Program Management Office"]:3
id07["Organizational Hierarchy, Level 4:"]
id08["Embedded Data Science Team"]:3

%% verticals
id09["Functional Teams:"]
id10["Analytics & Reporting"]
id11["Business Analysis & Product"]
id12["Software Development"]

%% row 1
id13["Roles:"]
id14["Data Engineering"]
id15["Product Management"]
id16["Dev Lead/Full Stack"]

%% row 2
space
id17["Business Intelligence"]
id18["Product Ownership"]
id19["Front End Development"]

%% row 3
space
space
id20["Technical Project Management"]
id21["Back End Development"]

%% row 4
space
space
id22["Process Analysis"]
space

%% row 5
space
space
id23["UX Research & Design"]
space

%% row 6
space
space
id24["Quality Assurance"]
space

%% row label styling
style id01 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px
style id03 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px
style id05 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px
style id07 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px
style id09 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px
style id13 fill:#f0f0f0, stroke:#b4b4b4, stroke-width:2px


```

### Operational
* This team was part of a larger matrixed organization and followed the same approach by matrixing resources from the above model (vertical reporting organizations, "Functional Teams") across product focused delivery teams (aka "Pods").

```mermaid

block-beta

columns 6

%% pods
space
id01["CM Pod"]
id02["TM Pod"]
id03["ME Pod"]
id04["DA Pod"]
id05["A&R Pod"]
%% styling
%% style id01 fill:#f0f0f0, stroke:#b4b4b4
%% style id02 fill:#f0f0f0, stroke:#b4b4b4
%% style id03 fill:#f0f0f0, stroke:#b4b4b4
%% style id04 fill:#f0f0f0, stroke:#b4b4b4

%% quality assurance
id06["Quality Assurance"]
id07["QA Lead"]:2
space
id08["QA Lead"]
space
space
id09["QA Automation Engineer"]:2
space
space
space
%% styling
%% style id05 fill:#ffcc80, stroke:#fcbb58
%% style id06 fill:#fcdeb1, stroke:#fcd79f

%% dev engineering
%% row 1
id10["Development"]
id11["Front End Dev"]
id12["JR Full Stack Dev"]
id13["Full Stack Dev"]
id14["Data Engineer"]
id15["BI Analyst"]
%% row 2
space
id16["Back End Dev"]
id17["Full Stack Dev"]
id18["Full Stack Dev"]
id19["Data Engineer"]
space
%% row 3
space
space
id20["JR Front End Dev"]
space
id21["Data Engineer"]
space

%% dev leads
id22["Dev Leads"]
id23["Dev Lead"]
id24["SR Dev Lead"]
id25["SR Dev Lead"]
id26["SR Data Engineer"]
id27["BI Lead"]

%% user experience
%% row 1
id28["User Experience"]
id29["UX Designer"]:3
space
id30["UX Designer"]
%% row 2
space
id31["UX Researcher"]:2
space
space
id32["UX Researcher"]

%% process analysis
id33["Process Analysis"]
id34["Process Analyst"]:2
space
id35["Process Analyst"]:2

%% product
%% row 1
id36["Product"]
id37["Product Owner"]:2
space
space
space
%% row 2
space
id38["Product Manager"]:5

%% management team
id39["Management"]
id40["Manager, Software Development"]:5
space
id41["Manager, Business Analysis & Product"]:5
space
id42["Manager, Analytics & Reporting"]:5

%% executive leadership
id43["Executive Leadership"]
id44["Director, Data Science"]:5
space
id45["SR Director, Program Management Office"]:5

```
