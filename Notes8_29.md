#Software Processes
---

>Are a structural set of activites required to develop a software system

SP Model is an abstract representation of a SW Processes
##Common Features
###Specification
    - Define what the system is supposed to do
###Design & Implementation
    - Define the organization of the system and realize it
###Validation
    - Ensuring that the system does what the "customer" wants
###Evolution
    - Making changes to the system in response to changing customer needs

##Plan Driven v. Agile Process
###Plan Driven
    - All the process activities are planned in advance and progress is measured
###Agile
    - Planning is incremental, easier to change the process to reflect changing customer requirements
###In Practice
    - Most practical processes incorporate elements of both plan-driven and agile approaches.
    - There are no right or wrong software development processes

##Software Process Models
Three broad categories:
###Waterfall
    - Plan-driven; Separate and distinct phases of specification & development
###Incremental
    - Specification, development, and validation are inter-learned
      - may be either Plan driven or Agile
###Integration & Configuration
    - System assembled from preexisting configurable components
      - may be either Plan driven or Agile
###In Practice...
    - Most large systems are developed using bits from all three Models

##Waterfall
![alt text][WaterfallChart]

>Traditional Waterfall(WF): Complete a stage before moving on to the next one

- Main drawback: doesn't handle changing requirements gracefully
- When the requirements are well understood and changes would be minimal, the WF can be a great way to develop a system
Today, the waterfall is mostly used for large systems projects where that system is being developed at several sites.[the plan driven nature of this process helps coordinate the work]

##Incremental
![alt text][IncrementalChart]

Pros:
- Cheaper to accommodate changing requirements
- Getting feedback early helps prevent further work that would be deemed unacceptable by the customer
- More rapid delivery and deployment of useful (but not full featured) software to the customer is possible
Cons:
- The process is opaque: There is no way for managers to measure progress
- The softwares structure tends to be degrade with new increment
  - unless time(and money) are spent on refactoring to improve the software, the product will become increasingly brittle and hard/expensive to change

##Integration & Configuration
![alt text][IntegrationChart]
IdeaL Wherever possible, reuse existing solutions(components or complete application systems(COTS - Commercial-Off-The-Shelf))

Reuse is now standard approach for building many types of business systems
Pros:
- Cheaper and less risky than development from scratch
- Can lead to fast delivery and deployment of a system
Cons:
- Requirements compromises are to be expected - may not meet real user needs
- Loss of control over evolution of reused elements
  - To upgrade or not to upgrade, that is the question.


[WaterfallChart]:https://github.com/gera-cameron/CEN3031LectureNotes/blob/master/Charts/Waterfall.png
[IncrementalChart]:https://github.com/gera-cameron/CEN3031LectureNotes/blob/master/Charts/Incremental.png
[IntegrationChart]:https://github.com/gera-cameron/CEN3031LectureNotes/blob/master/Charts/Integration&Config.png
