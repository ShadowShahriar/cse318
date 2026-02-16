## Mid Term Examination

### Topic List

1. [**Definitions**](#definitions)
    - Information, Data, System, Information System
    - System Analysis, System Analyst
    - Design Methodology
    - SDLC, Agile, OOSAD
    - CASE Tools
    - Sprint
    - SCRUM
    - DFD, ER Diagram, Use Case Model
    - Project, Project Scheduling
    - PERT Diagram
    - Earliest Start (ES), Earliest Finish (EF)
    - Latest Start (LS), Latest Finish (LF)
    - Total (Project) Completion Time
    - Slack Time
    - Critical Path
    - Problem Statement
    - Rent & Lease

2. [**Theoretical Questions**](#theoretical-questions)
    - **Chapter I**
        1. [Roles of a System Analyst](#11-roles-of-a-system-analyst)
        2. [Qualities of a System Analyst](#12-qualities-of-a-system-analyst)
        3. [Characteristics of SLDC, SDLC Figure](#13-software-development-life-cycle-sdlc)
        4. [Agile Development](#14-agile-methodology)
        5. [Principles](#15a-principles-of-agile) & [Core Practices of Agile](#15b-core-practices-of-agile)
        6. [Five Stages of Agile Development](#15e-five-stages-of-agile-development)
        7. [OOSAD](#17a-oosad-methodology), [Usage of OOSAD](#17b-usage-of-oosad)
        8. [SDLC vs Agile vs OOSAD](#18-difference-between-sdlc-agile-and-oosad)
        9. [SDLC, Agile or OOSAD - When to use each?](#19a-when-to-use-sldc)
        10. [Types of CASE Tools](#110-types-of-case-tools)

    - **Chapter II**
        1. [Forces that shape an Organization](#21-forces-that-shape-an-organization)
        2. [ER Diagram: Entity and Relationship Types](#22-entity-and-relationship-types)
        3. [Components of Use Case Model](#23-components-of-use-case-model)
        4. [Types of Behavioral Relationships](#24-types-of-behavioral-relationships)
        5. [Why do we need a Use Case Model?](#25-why-do-we-need-a-use-case-model)
        6. Use Case Scenario

    - **Chapter III**
        1. Gantt Chart
        2. PERT Diagram
        3. What are some reasons to initial a new project?
        4. How to identify if we need to initiate a new project?
        5. Feasibility Analysis: Assessment & Output
        6. Types of Feasibility Analysis
        7. Why is Feasibility Analysis needed?
        8. Ascertaining Hardware and Software Needs: Chart

3. **Scenario-based Questions**
    - Gantt Chart, PERT Diagram
    - Context Level DFD
    - ER Diagram
    - Use Case Model **(5 Marks Confirmed)**
    - Choose appropriate Design Methodology and justify your answer

---

### Full Forms

| Abbreviation      | Phrase                                     |
| ----------------- | ------------------------------------------ |
| SDLC              | Software Development Life Cycle            |
| OOSAD             | Object-Oriented System Analysis and Design |
| UML               | Unified Modeling Language                  |
| CASE              | Computer-Aided Software Engineering        |
| DFD               | Data Flow Diagram                          |
| ER&nbsp;Diagram   | Entity-Relationship Diagram                |
| PERT&nbsp;Diagram | Program Evaluation and Review Technique    |
| SRS               | Software Requirement Specification         |

---

### Definitions

- <ins><strong>Information:</strong></ins> Raw data that has been processed, organized, and given context, making it meaningful for tasks like decision-making or communication. **Information essentially turns facts into understanding.**

- <ins><strong>Data:</strong></ins> Raw, unorganized facts, figures, symbols, or images (_e.g.:_ a series of digital pixels)

- <ins><strong>System:</strong></ins> **A group of interrelated components** that **functions together to achieve a goal**.

- <ins><strong>Information System:</strong></ins> An arrangement of **people, data, processes,** and **information technology** that interact to **collect, process, store,** and **provide** as output the information needed to support an organization.

- <ins><strong>System Analysis:</strong></ins> The collection of **notations, methodologies,** and **tools** to analyze a problem situation so that we can deliver a system that meets user requirements.

- <ins><strong>System Analyst:</strong></ins> A person who uses analysis and design techniques to solve business problems using information technology.

- <ins><strong>Design Methodology:</strong></ins> A structural framework, process or set of principles guiding designers from problem identification to solution.
    - <ins><strong>SDLC:</strong></ins> A cost-effective and time-efficient process that development teams use to design and build high-quality software.

    - <ins><strong>Agile:</strong></ins> An iterative, team-based approach to software development that focuses on delivering software faster, enhancing flexibility, and improving collaboration.

    - <ins><strong>OOSAD:</strong></ins> A structural methodology that models systems as interacting, real-world objects.

- <ins><strong>CASE Tools:</strong></ins> Software application programs that automate SDLC activities to improve software development productivity, quality, and speed.

- <ins><strong>Sprint:</strong></ins> Short, time-boxed, and repeatable development cycles, used to break large projects into manageable, actionable chunks.

- <ins><strong>SCRUM:</strong></ins> A management framework that teams use to self-organize tasks and work towards a specific goal.

- <ins><strong>DFD:</strong></ins> A graphical tool that maps flow of information for any process or system.

- <ins><strong>ER Diagram:</strong></ins> A high-level conceptual data model that visually represents the structure of a database system.

- <ins><strong>Use Case Model:</strong></ins> A visualization of a system that shows what users can do within a system.

- <ins><strong>Project:</strong></ins> A collection of organized tasks that can be performed either in sequential or in parallel manner to achieve a specific goal.

- <ins><strong>Project Scheduling:</strong></ins> The process of organizing and mapping out the sequences of tasks, timelines, and resources necessary to complete a project efficiently.

- <ins><strong>PERT Diagram:</strong></ins> A project management tool used to map out, schedule, and coordinate tasks within a project by visualizing task dependencies and timelines.

- <ins><strong>Slack Time (or float):</strong></ins> The amount of time a task can be delayed without affecting the project's overall deadline or subsequent tasks.

- <ins><strong>Critical Path:</strong></ins> The longest sequence of dependent tasks that must be completed on time for a project to finish by its deadline.

- <ins><strong>Problem Statement:</strong></ins> A concise, data-driven description of an issue, gap, or pain point that a project aims to resolve.

- <ins><strong>Rent and Lease:</strong></ins> Renting is short-term (weeks to months), allowing for quick moves. Leasing is a long-term, fixed-period contract, often 12 months or longer.

---

### Theoretical Questions

#### 1.1. Roles of a System Analyst

A system analyst must be experienced in working with computers and be able to work with people of all descriptions.

A System Analyst has three primary roles -

1. **Consultant** (The Problem Solver)
    - Analyzes existing systems

    - Gathers requirements

    - Proposes solutions

2. **Agent of Change** (The Facilitator)
    - <ins><strong>Bridges gaps:</strong></ins> Acts as a connection between business departments (_who need solutions_) and technical teams (_who build solutions_)

    - <ins><strong>Manages implementation:</strong></ins> Oversees the development and deployment of new systems, ensuring they meet specifications and integrate smoothly.

    - <ins><strong>Trains users:</strong></ins> Develops training programs and documentation to help employees adapt to new software and processes.

3. **Supporting Expert** (The Technical Guide)
    - <ins><strong>Designs systems:</strong></ins> Creates functional specifications, system architecture, and design documents for developers.

    - Tests and monitors systems

    - Stays up-to-date

---

#### 1.2. Qualities of a System Analyst

A great system analyst combines strong analytical and problem-solving skills with excellent communication, business acumen and technical knowledge to bridge the gap between IT and business needs.

Key qualities include -

1. Problem-solving
2. Communication
3. Strong personal and professional ethics
4. Self discipline and self-motivation

- <ins><strong>Problem Solving</strong></ins>

    Views the analysis of problems as a challenge and enjoys devising workable solutions.

- <ins><strong>Communication</strong></ins>
    1. Capable of relating meaningfully to other people over extended periods of time.

    2. Has enough computer experience to program and to understand the capabilities of computers.

    3. Obtain information requirements from users.

    4. Communicate what is needed to programmers.

- <ins><strong>Personal and Professional Ethics</strong></ins>

    Involves prioritizing public welfare, honesty, integrity, unbiased judgement and competence. It focuses on protecting user safety and data privacy while delivering qualityful and reliable systems. It ensures transparency, avoiding conflicts of interest and respecting colleagues and clients.

---

#### 1.3. Software Development Life Cycle (SDLC)

SDLC is a cost-effective and time-efficient process that development teams use to design and build high-quality software.

SDLC follows a systematic and oderly approach

- There is only way forward
- There is no undo button

<p align="center"><img src="../assets/images/sdlc.jpg" alt="SDLC" title="Figure 1.3: Software Development Life Cycle (SDLC) and its phases"/><br><i>figure 1.3: Software Development Life Cycle (SDLC) and its phases.</i></p>

<ins><strong>SDLC Characteristics:</strong></ins>

1. Developed through the use of specific cycles of activities by analyst and user.

2. Each phase has unique user activities and certain deliverable.

<ins><strong>SDLC Prerequisites:</strong></ins>

1. Users should know what they need. (**clear SRS**)

2. No repeated changes.

<ins><strong>When to use SDLC?</strong></ins>

1. When the requirements are clear and detailed.

2. When project scope, goals, budget and resources are defined.

<ins><strong>Where to use SDLC?</strong></ins>

1. Developing healthcare and Govt. systems.

2. Developing banking systems. (like ATM)

---

#### 1.4. Agile Methodology

Agile is an iterativem team-based approach to software development and project management that focuses on delivering value faster, enhancing flexibility, and improving collaboration.

Agile is a way to manage projects by breaking them into smaller parts. It focuses on working together and making constant improvements.

Most industry level software projects follow the **Agile Methodology**.

<p align="center"><img src="../assets/images/agile.png" alt="Agile" title="Figure 1.4: Agile Development"/><br><i>figure 1.4: Agile methodology.</i></p>

Agile offers -

1. Incremental delivery (called **Sprint**s)
2. Collaboration and Flexibility
3. Continual learning

- <ins><strong>Collaboration:</strong></ins>
    1. Flexible application and fast delivery.

    2. Proper transparent communication.

    3. No unneccessary documents.

    4. User-centric feedback in every phase of development.

- <ins><strong>Flexibility:</strong></ins>
    1. Low budget,

    2. Flexible timing,

    3. Always delivers the best quality.

- <ins><strong>Continual Learning:</strong></ins>
    1. Learning the users need as the project progresses.

    2. Implement new technologies on the fly.

**Agile is easy to understand but hard to master.**

Agile is based on -

- Values (Beliefs)
- Principles (How engineers act and think)
- Core Practices (What engineers do daily)

<ins><strong>Values of Agile:</strong></ins>

1. Communication,
2. Simplicity,
3. Riskier features are implemented later,
4. User feedback.

<ins><strong>Sprint Duration:</strong></ins> 1/2 week (max 4 weeks)

---

#### 1.5A. Principles of Agile

1. Deliver software frequently
2. Embrace change
3. Work with customers regularly
4. Keep a sustainable pace
5. Improve continously

#### 1.5B. Core Practices of Agile

1. Work in short cycles
2. Daily meetings
3. Tests frequently
4. Collaborate as a team

#### 1.5C. The Agile Team

1. **"The show must go on"**
2. Every developer can do multiple functions
3. Transparent and Collaborative

#### 1.5D. Adjustable Resources of Agile Development

1. Time
2. Cost
3. Quality (ensuring best quality)
4. Scope

---

#### 1.6A. Five Stages of Agile Development

1. Exploration

2. **Planning:** Customer decides what the development should tackle first.

3. **Iterations of First Release:** This is a continuous process. Here customer feedback is considered and daily meetings are hold.

4. **Productionizing:** A working software with initial features is being produced here.

5. **Maintenance:** Here riskier customer suggestions are considered. Team members may be rotated on or off the team.

#### 1.6B. Agile Characteristics

- Agile development demans skillful developers.

- Agile development is user-centric.

#### 1.6C. Where to use Agile?

1. In user-centric development projects, (e-commerce)

2. Where time and budget is flexible,

3. Where fast software delivery is expected.

---

#### 1.7A. OOSAD Methodology

OOSAD is a structural methodology that models systems as interacting, real-world objects.

- Uses object-oriented fundamentals.
- Maximum time is spent on design.

<ins><strong>OOSAD Phases:</strong></ins>

1. Analysis
2. Design
3. Implementation
4. Maintenance

<ins><strong>OOSAD Characteristics:</strong></ins>

1. Uses the four principles of **OOP** (**Inheritance, Polymorphism, Encapsulation, Abstraction**)
2. Focuses on real-world objects.
3. More importance on modeling the software.
4. Riskier features are usually implemented first.

<ins><strong>Benefits of OOP:</strong></ins>

1. Re-useability
2. Modularity

#### 1.7B. Usage of OOSAD

- Rapidly changing features and updates.
- When the system is very complex.

---

#### 1.8. Difference between SDLC, Agile, and OOSAD

| Aspect              | SDLC                                        | Agile                               | OOSAD                                             |
| :------------------ | :------------------------------------------ | :---------------------------------- | :------------------------------------------------ |
| Approach            | **Linear**, Sequential                      | Iterative, **Incremental**          | Interative, **Object-Oriented**                   |
| Flexibility         | **Low** adaptibility to change              | **High** adaptibility to change     | **Moderate** flexibility, but more upfront design |
| Documentation       | **Extensive** documentation for each phase  | **Minimal**                         | **Detailed modeling** using UML                   |
| Team Involvement    | Silos between phases (analysts, developers) | Collaborative, cross-functional     | Collaborative, but more focused on modeling       |
| Development Process | Clear, structured phases                    | Short sprints with regular feedback | Focus on designing objects and their behaviors    |
| Best for            | **Well-defined**, stable projects           | **Rapidly changing** requirements   | Complex, **long-term scalable** systems           |

---

#### 1.9A. When to use SLDC?

- When the project goals and requirements are well-defined.
- When the project has a clear SRS document.
- When there needs to be a fully featured project ready to be launched.
- When there are adequate resources and time to complete the full SDLC.

#### 1.9B. When to use Agile?

- When applications need to be developed quickly in response to a dynamic environment.
- When developing a fail-safe or backup system.
- When the customer is satisfied with incremental improvements.
- Where executives and analysts agree with the principles of Agile methodology.

#### 1.9C. When to use OOSAD?

- When systems can be added gradually, one subsystem at a time.
- When reuse of previously written software is possible. When the systems are modular.
- When it is acceptable to tackle the difficult problems first.

---

#### 1.10. Types of CASE Tools

1. **Upper Case:** Follows first 3 steps of SDLC.

2. **Lower Case:** Follows last 4 steps of SDLC.

3. **Integrated CASE:** Hybrid of upper case and lower case.

---

#### 2.1. Forces that shape an Organization

Three main forces interact to shape an organization:

1. Levels of Management
    1. **Strategic Management:** Focuses on short-term goals, (weekly/monthly), Defines the organization as a whole.
    2. **Middle Management:** Intercommunicates between strategic and operational managements,
    3. **Operational managements:** Employees who perform regular activities.

2. Organizational Environments
    1. Community (Has a physical location)
    2. Economic (Market factors)
    3. Political (State and local government)
    4. Legal (Federal, State, Regional)

3. Organizational Culture
    1. **Open System:** Free flow of information. Output from one system becomes input to another.
    2. **Closed System:** Restricted access to information.

---

#### 2.2. Entity and Relationship Types

Focus on entities and how they are connected with each-other.

<ins><strong>Relationship Types:</strong></ins>

1. One to One
2. One to Many
3. Many to Many

<ins><strong>Types of Entities:</strong></ins>

1. Fundamental (**Strong**) Entity
    - A real life object that can exist **independently**.
    - Can have one or more attributes.
    - **Example:** Student, Course, Employee.

2. Associative Entity
    - Created to resolve a **Many to Many** relationship between fundamental entities.

3. Attributive (**Weak**) Entity
    - Less likely used.
    - Used to store multi-valued attributes of fundamental entities.
    - Depends on fundamental entities.
    - **Example:** Phone Number.

---

#### 2.3. Components of Use Case Model

Use Case Model reveals what users can do within a system. It consists of three components:

1. **Actor**
    - **Primary Actor:** Gets benefit from the system.
    - **Supporting Actor:** Helps to keep the system running.

2. **Use Case**
    - Shows the requirements of the system.
    - Shows the tasks/functions an actor can perform using the system.

3. **Behavioral Relationships**

    Shows the interactions between,
    - **Actor** ~ **Use Case**
    - **Use Case** ~ **Use Case**
    - **Actor** ~ **Actor**

---

#### 2.4. Types of Behavioral Relationships

1. <ins><strong>Communicates</strong></ins>
    - Relationship between Actor ~ Use Case.
    - Represented with a solid line.
    - **Symbol:** ———
    - **Representation:**
        ```
        Actor ——— (Use Case)
        ```

2. <ins><strong>Includes</strong></ins>
    - **Mandatory**
    - Relationship between Use Case ~ Use Case.
    - One use case always includes another use case as part of its behavior.
    - One is **Base Use Case** and the other is **Included Use Case**.
    - The included use case must happen every time the base use case happens.
    - **Symbol:** ---&lt;&lt;includes&gt;&gt;---&gt;
    - **Representation:**
        ```
        (Base Use Case) ---<<includes>>---> (Included Use Case)
        ```

3. <ins><strong>Excludes</strong></ins>
    - **Optional**
    - One use case optionally extends another use case under certain conditions.
    - Happens only sometimes.
    - Adds extra behavior to the **Base Use Case**.
    - **Symbol:** ---&lt;&lt;extends&gt;&gt;---&gt;
    - **Representation:**
        ```
        (Base Use Case) <---<<includes>>--- (Extended Use Case)
        ```

4. <ins><strong>Generalizes</strong></ins>
    - Shows that a specialized thing inherits behavior from a general thing.
    - The relationship can be between,
        - **Use Case** ~ **Use Case**
        - **Actor** ~ **Actor**
    - **Symbol:** ———▷
    - **Representation:**
        ```
        Specialized ———▷ General
        ```

**Note:** Actors are external entity. So, the use case must be within a system boundary (rectangle) and the actors must be placed outside of it.

---

#### 2.5. Why do we need a Use Case Model?

- Use cases effectively communicate system requirements because the diagrams are kept simple.

- Use cases allow people to tell stories.

- Use case stories make sense to non-technical people.

- Use cases don't depend on a special language.

- Use cases can describe most functional requirements (such as **interaction between actors and applications**)

- Use cases can describe non-functional requirements (such as **performance and maintainability**) through the use of stereotypes.

- Use cases help analysts define boundaries.

- Use cases can be traceable, allowing analysts to identify links between use cases and other design and documentation tools.
