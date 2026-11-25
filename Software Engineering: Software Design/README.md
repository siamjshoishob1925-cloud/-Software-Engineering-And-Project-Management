# Software Engineering: Software Design
## OBE-Based Question Paper (Cognitive Domain: Knowledge and Understanding)

| Item | Detail |
|---|---|
| **Course** | Software Engineering |
| **Topic** | Software Design (design fundamentals, OO metrics, architectural styles, GoF patterns, enterprise application patterns) |
| **Source material** | `SoftEng-Design.pdf` (155 slides) |
| **Total marks** | 40 |
| **Time** | 1 hour |
| **Framework** | Outcome-Based Education (OBE), Bloom's Taxonomy (Cognitive Domain), BNQF |
| **Bloom levels used** | C1 Remember (Knowledge), C2 Understand |

---

## 1. Course Outcomes (CO)

> The five COs below are derived from the slide content. If your course syllabus words them differently, replace the CO text. The mapping tables in Sections 4 to 6 stay the same as long as the CO numbers still line up.

| CO | Course Outcome | Bloom level |
|---|---|---|
| **CO1** | Explain the fundamentals of software design: the design process, modularity, abstraction, encapsulation and information hiding, and the coupling and cohesion principles. | C1, C2 |
| **CO2** | Describe and interpret object-oriented design quality metrics (CBO, LCOM, WMC, RFC, DIT, NOC) used to assess a design. | C1, C2 |
| **CO3** | Explain architectural styles (layered, event-based, MVC, blackboard, pipes and filters) and their structure. | C1, C2 |
| **CO4** | Describe GoF design patterns (creational, structural, behavioral): intent, structure, benefits and liabilities. | C1, C2 |
| **CO5** | Explain enterprise application architecture patterns: domain model, service layer, data mapper, ORM and inheritance mapping, and presentation patterns. | C1, C2 |

## 2. Bloom's Taxonomy and BNQF Alignment

| Bloom level (Cognitive) | Action verbs used in this paper | BNQF learning domain |
|---|---|---|
| **C1 Remember (Knowledge)** | define, state, list, identify, describe | Knowledge |
| **C2 Understand** | explain, distinguish, compare, interpret | Understanding |

The paper is limited to the lower cognitive levels (Knowledge and Understanding). It does not test Apply, Analyze, Evaluate or Create.

---

## 3. Question Paper

**Instructions:** Answer all questions. Figures in the right margin show marks.

### Question 1: Multiple Choice (10 x 1 = 10 marks)
*Choose the correct answer.*

**1.1** The input of the software design process is: **[CO1, C1, 1]**
a) Source code  b) Requirements  c) Test cases  d) User manual

**1.2** Which pair of properties characterizes a good decomposition of software into modules? **[CO1, C1, 1]**
a) High coupling, low cohesion  b) High coupling, high cohesion  c) Low coupling, high cohesion  d) Low coupling, low cohesion

**1.3** In the CK metrics suite, the Coupling Between Object classes, CBO(A), is the: **[CO2, C1, 1]**
a) Number of methods in A  b) Number of classes used by A  c) Number of subclasses of A  d) Depth of A in the inheritance tree

**1.4** The Depth of Inheritance Tree (DIT) of a root class (a class with no superclass) is: **[CO2, C1, 1]**
a) 0  b) 1  c) Equal to NOC  d) Undefined

**1.5** The Unix command `ls -l | grep "Aug" | sort | more` is an example of which architectural style? **[CO3, C1, 1]**
a) Blackboard  b) Layered  c) Pipes and filters  d) Event-based

**1.6** In MVC, which component takes user input, manipulates the model and causes the view to update? **[CO3, C1, 1]**
a) Model  b) View  c) Controller  d) Repository

**1.7** To which GoF category does the Adapter pattern belong? **[CO4, C1, 1]**
a) Creational  b) Structural  c) Behavioral  d) Architectural

**1.8** Which GoF pattern encapsulates an action as an object to support queuing, logging and undo/redo? **[CO4, C1, 1]**
a) Strategy  b) Singleton  c) Command  d) Facade

**1.9** Which enterprise pattern saves the database primary key in an in-memory object's field to maintain identity between the object and a table row? **[CO5, C1, 1]**
a) Identity Field  b) Foreign Key Mapping  c) Data Mapper  d) Service Layer

**1.10** Which presentation pattern uses a single controller to handle all requests for a web site? **[CO5, C1, 1]**
a) Page Controller  b) Template View  c) Transform View  d) Front Controller

### Question 2: Short Answer (5 x 3 = 15 marks)

| No. | Question | Marks | CO | Bloom |
|---|---|---|---|---|
| **2.1** | Distinguish between *architectural design* and *detailed design*. State what the outcome of the design process is. | 3 | CO1 | C2 |
| **2.2** | The LCOM2 metric is defined as `LCOM2 = 1 - Sum(mai)/(m*a)`. Explain what a value of **0** and a value of **1** indicate about a class. Which value is better? | 3 | CO2 | C2 |
| **2.3** | Describe the *layered* architectural style and state the dependency rule between layers. | 3 | CO3 | C1 |
| **2.4** | State the *intent* of the Strategy pattern and list **two** benefits of using it. | 3 | CO4 | C1 |
| **2.5** | What is Object-Relational Mapping (ORM)? State its key idea. | 3 | CO5 | C1 |

### Question 3: Explain / Distinguish (5 x 3 = 15 marks)

| No. | Question | Marks | CO | Bloom |
|---|---|---|---|---|
| **3.1** | Distinguish *abstraction* from *encapsulation / information hiding*. Give a short example of each. | 3 | CO1 | C2 |
| **3.2** | Explain the difference between *coupling* and *cohesion*. Name one CK metric that measures each. | 3 | CO2 | C2 |
| **3.3** | Explain the roles of the **Model**, **View** and **Controller** in the MVC architectural style. | 3 | CO3 | C2 |
| **3.4** | Explain how the **Adapter** pattern lets classes with incompatible interfaces work together. Name its four participants. | 3 | CO4 | C2 |
| **3.5** | Compare *Single Table Inheritance* and *Class Table Inheritance*. Give one advantage and one disadvantage of each. | 3 | CO5 | C2 |

---

## 4. Question-to-CO Mapping

| Question | Marks | CO1 | CO2 | CO3 | CO4 | CO5 | Bloom | Slide topic |
|---|---|---|---|---|---|---|---|---|
| 1.1 | 1 | 1 | | | | | C1 | Design process |
| 1.2 | 1 | 1 | | | | | C1 | Modularity, coupling, cohesion |
| 1.3 | 1 | | 1 | | | | C1 | CBO |
| 1.4 | 1 | | 1 | | | | C1 | DIT / NOC |
| 1.5 | 1 | | | 1 | | | C1 | Pipes and filters |
| 1.6 | 1 | | | 1 | | | C1 | MVC |
| 1.7 | 1 | | | | 1 | | C1 | GoF classification |
| 1.8 | 1 | | | | 1 | | C1 | Command |
| 1.9 | 1 | | | | | 1 | C1 | Identity Field |
| 1.10 | 1 | | | | | 1 | C1 | Front Controller |
| 2.1 | 3 | 3 | | | | | C2 | Design steps and outcome |
| 2.2 | 3 | | 3 | | | | C2 | LCOM2 |
| 2.3 | 3 | | | 3 | | | C1 | Layered style |
| 2.4 | 3 | | | | 3 | | C1 | Strategy |
| 2.5 | 3 | | | | | 3 | C1 | ORM |
| 3.1 | 3 | 3 | | | | | C2 | Abstraction, encapsulation |
| 3.2 | 3 | | 3 | | | | C2 | Coupling, cohesion metrics |
| 3.3 | 3 | | | 3 | | | C2 | MVC |
| 3.4 | 3 | | | | 3 | | C2 | Adapter |
| 3.5 | 3 | | | | | 3 | C2 | Inheritance mapping |
| **Total** | **40** | **8** | **8** | **8** | **8** | **8** | | |

## 5. CO-wise Mark Distribution

| CO | Q1 (MCQ) | Q2 | Q3 | Total | % |
|---|---|---|---|---|---|
| CO1 | 2 | 3 | 3 | **8** | 20% |
| CO2 | 2 | 3 | 3 | **8** | 20% |
| CO3 | 2 | 3 | 3 | **8** | 20% |
| CO4 | 2 | 3 | 3 | **8** | 20% |
| CO5 | 2 | 3 | 3 | **8** | 20% |
| **Total** | 10 | 15 | 15 | **40** | 100% |

## 6. Bloom's Taxonomy Distribution

| Level | Domain | Questions | Marks | % |
|---|---|---|---|---|
| C1 Remember | Knowledge | Q1.1 to 1.10, 2.3, 2.4, 2.5 | 19 | 47.5% |
| C2 Understand | Understanding | Q2.1, 2.2, Q3.1 to 3.5 | 21 | 52.5% |
| **Total** | | | **40** | 100% |

## 7. Time Plan (60 minutes)

| Question | Suggested time |
|---|---|
| Q1 (10 MCQ) | 10 min |
| Q2 (5 short answers) | 20 min |
| Q3 (5 explain / distinguish) | 25 min |
| Review | 5 min |

---

## 8. Answer Key and Marking Guide

### Question 1 (1 mark each)
1.1 **b** | 1.2 **c** | 1.3 **b** | 1.4 **a** | 1.5 **c** | 1.6 **c** | 1.7 **b** | 1.8 **c** | 1.9 **a** | 1.10 **d**

### Question 2 (3 marks each)

- **2.1**: *Architectural (high-level) design* describes how the software is organized into components (1). *Detailed design* describes the desired behavior of those components (1). The outcome is a set of models and artifacts recording the major decisions and the rationale for each non-trivial decision (1).
- **2.2**: LCOM2 = 0 means every method uses every attribute, so cohesion is maximal (1). LCOM2 = 1 means no method uses any attribute, so cohesion is lacking (1). Smaller is better, so 0 is better (1).
- **2.3**: Components are organized in layers (1.5). Each layer depends only on the next layer (1.5).
- **2.4**: Intent: define a family of algorithms, encapsulate each one, and make them interchangeable, so the algorithm varies independently of its clients (1.5). Any two benefits (0.75 each): isolates Context from algorithm details; new strategies can be added without changing Context; avoids complex conditionals; algorithms can be swapped at runtime.
- **2.5**: ORM is mapping objects to database relations and vice versa (1). Key idea: one DB table per class of objects in the Domain layer, and each object is stored as a table row (2).

### Question 3 (3 marks each)

- **3.1**: *Abstraction* is a view of an object that focuses on the information relevant to a particular purpose and ignores the rest (1). *Encapsulation / information hiding* groups the internal details of an abstraction and makes them inaccessible to external entities (1). A suitable example of each (1).
- **3.2**: *Coupling* is the interdependence among components, for example CBO, the number of classes used by a class (1.5). *Cohesion* is the strength of association among the elements within a component, for example LCOM, LCOM2 or LCOM3 (1.5).
- **3.3**: *Model* represents information about the domain (1). *View* represents the display of the model in the UI (1). *Controller* takes user input, manipulates the model, and causes the view to update (1).
- **3.4**: The Adapter converts the interface of a class (Adaptee) into the interface clients expect (Target), so classes with incompatible interfaces can work together (1.5). The four participants are Target, Client, Adaptee and Adapter (1.5).
- **3.5**: *Single Table*: one table holds all fields of the hierarchy. Advantage: no joins, and refactoring fields in the hierarchy does not change the DB. Disadvantage: unused columns waste space, and the table may grow too large (1.5). *Class Table*: one table per class, linked by foreign keys. Advantage: all columns are relevant and the mapping to the domain model is straightforward. Disadvantage: loading an object needs joins or multiple queries (1.5).

---

## 9. Reference
Slide source: *Software Design* (`SoftEng-Design.pdf`), based on Pfleeger, Sommerville, SWEBOK v3, R.C. Martin, GoF *Design Patterns*, and M. Fowler's *Patterns of Enterprise Application Architecture*.

