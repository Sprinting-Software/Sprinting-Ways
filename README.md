# Sprinting-Ways

Welcome to this introduction to ways of working in Sprinting Software. 

> A leader is one who knows the way, goes the way, and shows the way.
> John C. Maxwell

You may call this the Sprinting methodology or method. We call it Sprinting Ways. 

##

# Project Management concepts

## Product vs project - modes of working

We have two modes of working: 

Product mode/kanban mode: we work on a best effort-basis without critical long-term due dates. The success criteria is to maximize the output of working software given the available capacity. We may still have long-term critical goals but we have flexibility in how the goals are achieved. For instance we may adjust scope to meet the deadline. 

Project mode: we work against a critical long-term due date. The success criteria is to have the project scope delivered in its whole. Missing part of the scope or missing the due date severely limits or even negates the delivered business value. 

It is important to understand that there is a whole spectrum between these two ways of working and most teams will have periods of product mode and other periods of project mode. In addition, project mode often comes in a variant where the due date is fixed whereas the scope or the cost may be negotiable.

We strive toward Product-mode of working for multiple reasons, including: 

- It tends to be more sustainable
- It stays true to the agile spirit of “reacting to change over following a plan”
- It builds upon and enforces trust between the vendor and the customer

Having said that, working in project mode can be extremely valuable and often it is the only meaningful thing in a given context.

Products and Projects have the following differences: 

![Differences](blob:https://sprinting.atlassian.net/0b467a39-3ce4-4820-b9d7-4324f1bb6423#media-blob-url=true&id=7fe231ac-40e4-4491-ab9c-896d6cf1b3ac&contextId=566460428&collection=contentId-566460428)

## Project management principles

About this document

This document describes the core project management principles and practices. The primary target audience is project leads (agile project managers) but developers and stakeholders may find it valuable as well. 

This document is mostly relevant when we are dealing with project-mode of working, not product-mode, see the previous section to understand the difference. 

## Motivation

Project management is the discipline by which we ensure delivery of a project. A project in our context will be defined to be any undertaking carried out collaboratively and carefully planned to achieve a particular aim. A project will have a scope, a budget and a deadline. 

As reliability is a key objective for us, the project management discipline should be mastered by all project leads. 
The high-level principles

Our approach to project management is composed from the following principles:

- A feature-oriented task break-down structure

- Provide “median estimates” (*)

- Aggregate task buffers into a project buffer

- Empower cross-functional teams and keep them fully accountable

- Remember that building software is the art of being practical - not sophisticated 

- Prune the project model to fit your actual needs

(*) Median estimates are defined as estimates which overshoot in 50% of the cases and undershoot in the other 50% of the cases. 
The approach in a nutshell

In a nutshell a project has two phases: 

- The Preparation phase - a short time-boxed activity which involves mostly a few people such as an architect and management. 

- The Execution phase - an iterative process where a fully allocated team works in sprints. The execution phase consists of planned sprints and a buffer sprints. 

In between the two phases, management must ensure a full kit before the project can be started. The following diagram illustrates it. 

## The preparation phase

The preparation phase consists of these steps (bolded terms are defined in later sections):

- Get the full set of input material relevant for the project. This is called the project request material. 

- Fill out the project workbook according to the description in the appendix.

The preparation phase is normally carried out by an architect, a key developer or other senior personel. 

## Ensuring full kit

Ensuring full kit means that certain conditions are met before project execution is allowed to start. The conditions of a full kit are: 

- The project sponsor has approved the project plan which obviously means that all the sections are understood and approved. In detail, it means:

   - the budget needed to cover the sprint plan, the team size and roles is approved 

   - the project sponsor has commited to ensure participation by a product owner on the sprint meetings according to the sprint plan

   - the success criteria are approved by the project sponsor 

   - the project sponsor understands the sprint goals and agrees that they together with the non-functional requirements will cover the intended target system

   - the feature design is being a reasonably accurate description of the desired behavior

   - the dependencies are understood and project sponsor and can commit to them

   - the preliminary assumptions are understood and approved

   - the limitations are approved by the project sponsor

   - the project risks are acknowledged by the project sponsor as possible sources of delays of the project deadline. The listed mitigations are understood and approved. 

   - the solution architecture diagrams are approved

- Management has committed to the staffing plan needed by the project 

Ensuring full kit is a hygiene factor that needs to be counted in to ensure a healthy project and a healthy overall organization. 

## The execution phase - planned sprints

Once the execution phase starts the project workbook is turned into a living document which will be continously changed. 

The execution phase of the project consists of a number of so-called planned sprints followed by a number of buffer sprints. A planned sprint has sprint goals, a buffer sprint has no sprint goals. The purpose of the buffer sprint is to protect the due date and reflect the fact that software projects has a lot of inherint uncertainty and variability. Pretending the opposite is a fallacy. 

Each planned sprint consists of the following high-level activities:

- The sprint goals are implemented, tested and deployed to an agreed environment.

- In the end of the sprint: 

   - A sprint report is produced and sent to the product owner

   - A sprint meeting is performed with the following agenda: 

     - Demo - presenting what has been achieved

     - Scoping - ensuring the scope is well-described, well understood and agreed upon. This is often called backlog refinement. 

     - Planning - ensuring the sprint plan for remaining sprints is updated. 

   - Minutes of meeting are sent out to keep stakeholders informed. 

- During the sprint demo all left-overs from the implemented features will be listed. The left-overs should be estimated.

- The penetration of the project buffer will be calculated as the sum of estimates from all left-overs across all completed sprints. From here the general project health will be inferred according to the formula: 

> Project health = % of project buffer being penetrated / % of non-buffers sprints being completed. 

## The execution phase - buffer sprints

In order to protect the due date and minimize the risk in the project, we add a number of buffer sprints. The number of buffer sprints can vary between 25%-100% of the number of planned sprints. For instance, in a project with a lot of uncertainty we may have 6 planned sprints and 4 buffer sprints. In a less risky project we could have 6 planned sprints and 1 or 2 buffer sprint. 

Buffer sprints may still hold high-level sprint goals such as “GO-LIVE” or “Preprod env working”

## Working against soft and hard due dates
Whenever we work in project mode (see  [Product vs project - modes of working](#project-management-concepts)) the end date of the project is by definition a hard due date. 

When we work in product mode it is a different matter. Not all due dates are equally critical.

This page explains the differences. 

|          |   **Hard due date**  |  **Softdue dates**  |
| -------- | -------------------- | ------------------- |
|Principles| - Hard due dates should be <br/> applied only when needed <br/> - We focus on the critical path of tasks <br/> - We carefully keep track of dependencies, <br/> risks and decisions, see <br/> [Project management principles](#project-management-principles)<br/>- We work with milestones and deadlines <br/>- We make sure to have safety buffers at<br/> the end of all our activities, see<br/>[Project management principles](#project-management-principles)| - We focus on maximizing the business<br/> value resulting from our efforts.<br/>- We consider the due date more like a<br/> desireable outcome but not a must-win battle.<br/> - The project sponsor must understand that the<br/> due date is not guaranteed as no overall project<br/> buffers have been built in. |
|Sucess criteria | - The due date is met. Depending on<br/> the context it may or may not be an<br/> advantage if the project is completed<br/> before the due date or not.|  - The customer gets maximum business<br/> value from the time available.|
|When do we<br/> have hard and<br/> soft due dates | - When we work with low-trust<br/> customers such as new customers      <br/>- When critical business milestones<br/> must be met at a certain point in time.<br/>- When we have given a fixed price<br/> on a new project. | - When we work with high-trust customers,<br/> such as customer that we already delivered well to. <br/>- When the business does not have critical<br/> milestones depending on our deliveries <br/>- When the customer perceives the work delivered<br/> as best-effort |

The following diagram illustrates the differences between the two different kinds of due dates. 
![diagram1](download.png)

The criticality of due dates is of course a spectrum ranging from a very soft due date to a very hard due date. The following diagram illustrates this idea: 
![diagram2](download1.png)
It is crucial that the lead and the entire team understand when we deal with very hard due dates. The importance of reaching these due dates is several orders of magnitude more important than meeting the very soft due dates. Understanding the difference allows us to apply our focus, energy and determination when it matters the most. 

Very hard due dates are often called must-win battles or Messi-moments. It takes a tremendous amount of talent and determination to meet fixed due dates in complex software projects. 

![messi](messi.png?style=centerme)
<br/>

## Dependencies, risks and decisions
We use three kinds of logs to manage project work. These are logs of dependencies, risks and decisions. To make it clear what we talk about, a **log** is tabular information with status updates on a certain topic. The following is an example decision log. 

|   #       |   **Decision**  |  **Status**  |
| -------- | -------------------- | ------------------- |
|1| *We will build the app in native languages Swift for iOS<br/> and Kotlin for Android* | *2022-04-03: Decision point raised at the sprint meeting <br/><br/>2022-04-17: Decision point agreed over a phone call.* |
|2| *xxx* | *xxx* |

Next let us define them one by one.  

|   **Term**  |  **Definiton**  |
| -------------------- | ------------------- |
| Dependency log|A dependency log is a list of external deliverables (i.e. something to be done that is<br/> outside the control of the sprint team). Each dependency is described by a title and<br/> a responsible person/team. In addition it may have a description and/or a list of<br/> accept criteria depending on the nature of the project. |
| Decision log| A decision log contains decisions and the process around them. The normal process is<br/> that a question comes up during the implementation process and when it has been<br/> answered, it becomes a decision. In the meantime, it is often necessary to turn it into<br/> an assumption so that development activities can be planned around it while<br/> stakeholders takes the decision. The decision log is driven by the need for<br/> stable grounds for the implementation of the project or to minimize the risk of future<br/> disputes. The Decision Log should not manage scope decisions unless they are<br/> significantly impacting the architecture of the solution. <br/><br/>A decision should use an imperative language such as “We will…” or “We should…”. |
|Risk log| The Risk Log gives an overview of the risks managed by the project. Risks are<br/> unknowns that can impact the feasibility of the project (scope, due date or cost).<br/><br/> PS: Security risks are a special kind of risks associated with running software. Such risks is not a part of the project risk log but should rather be part of a company-wide security exception log.
<br/>
# Project management practices

## Introduction to the lead role and the sprint cycle
### **The sprint meeting**

The sprint meeting is a crucial part of our development process. It marks the end of a sprint and the beginning of a new sprint.

A **Sprint Report** is sent out before the meeting and a **Sprint Meeting Summary** is sent out immediately after. Let us go through the three parts: report - meeting - summary. 

### **The sprint report**
**Purpose of the sprint report**
   - To communicate as clearly as possible what has been delivered
   - To proof that certain features were actually working at the time of delivery
   - To allow stakeholders to stay informed even without participation on the sprint meeting. 

**Structure of the sprint report**
   - Delivery summary - summarise on bullet form what has been delivered. This is the pitch of the report. 
   - Staffing - make stakeholders aware of the people working in the team. Mention names and roles.<br/>Mention vacation or off-days both of the delivered sprint or coming sprints. 
   - What has been delivered - describe the features delivered in a format that is easily understood by the stakeholders. 
   - Left overs - mention any issues or missing things in the features delivered. 

   We have templates for the sprint report here: https://sprinting.atlassian.net/wiki/pages/createpage.action?spaceKey=SP&title=Sprint%20report%20template%20from%20ClubSalling 

   **Sprint report principles**
  - “Show what is done”: Focus on what has been delivered. Spend time on the details. Remember that quality is about details. 
   - “No burndown charts”: We rarely use burn down charts or other usual metrics used in software projects.<br/>Often such charts are speculative and not adding ultimate value (remember, the objective of Sprinting is creating<br/> business value through running software).  
   - “No left-over is too small to mention”: We strive for perfection, hence any bug or missing detail should be<br/> listed in the section of left-overs. We demonstrate our eye for quality in our ability to know exactly what<br/> left-overs we have when we deliver a sprint. 

 ### **The sprint meeting**

 **Purpose of the sprint meeting**

We want the sprint meeting to be a catalyst of information sharing, decision making and coordination so  that the<br/>  rest of the sprint is free of discussions, new decisions and changes of direction.This is possible if the sprint meeting<br/>  is facilitated in the right way and covers all ground needed.  

**Agenda of the sprint meeting**
   - Demo: Present the output of the most recent sprint. 
   - Scope grooming: Process and clarify what should be delivered in future sprints 
   - Planning: Create the clearest possible priorities for the next sprint and adjust the sprint plan.

**About “Demo”**
   - “Perform live-demos”: Live demos are  effectively communicating what was done. Show it!
   - “Timebox your live demos”: Live-demos can easily get out of control and you can end up spending too much time on it.<br/> Make sure to be well-prepared and disciplined around it. Mix in sprint report walk-throughs to keep the time box. 
   - “Stimulate feedback”: Go slowly and stimulate feedback from stakeholders. Ask them to imagine that we would go to<br/> production tomorrow with the presented feature. Would they miss anything?
   - “Engage stakeholders in dog-footing“: Encourage stakeholders to test the new features themselves where possible.<br/> Make sure you have stable test-environments for stakeholders. If we produce native apps, invest time in build,<br/> deploy and distribution of native apps. 

   **About “Scoping” (also called “refinements”)**

   The purpose of the scoping session is to refine the shared understanding of future features to be built. Sometimes this is called backlog grooming.

The purpose is two-fold:
   - Scope exploration: exploring the features to be built. Describing in greater details how things should work. 
   - Scope alignment: agreeing on priorities for each aspect of the features. 
   
   Scoping can happen in different ways, for instance: 
   - If we are building graphical user interfaces, then we should walk through UX designs and write down stories. 
   - If we have collected input from stakeholders during the sprint (requirements, new ideas etc.) we should analyze<br/> them and add them to the scope breakdown section.

   The scoping session is governed by these principles: 
  - “100-50-5”: A rule of thumb is that scoping must make the next sprint 100% clarified, the next-next sprint 50% <br/>clarified and all other future sprints 5% clarified.

  **About “Planning”**
  The planning session has the following activities: 
    
  - Prioritize left-overs: During the sprint demo and during the writing of the sprint report, we normally find<br/> some left-overs. During the planning we should go through the left-overs and prioritize like this: 
    - Prio 0 = todo immediately
    - Prio 1 = todo on next buffer sprint
    - Prio 2 = todo after the current phase. 
  - Revisit the scope of the next 1-2 sprints: Reconsider how much can be done 
<br/>
<br/>
   ### **The sprint minutes of meeting (MoM)**
   **What is Sprint MoM?**<br/>
A brief email containing all the notes taken during the sprint meeting. The minutes are also saved on Confluence<br/> 
so that we can always go back and find minutes. 

**Purpose of the sprint MoM**
   - To clearly inform about the updated project plans so that the risk of future misunderstanding are minimized. 
   - To clearly inform about follow-up actions expected from people outside the delivery team. 
   - To inform everybody about decisions taken on the meetings
   <br/>
<br/>
### **Sprint cycle**
The 2-week sprint cycle encompasses the following activities. 
   <br/>
<br/>
### **Specification**
Write down specifications so that developers can implement the desired features. There are no hard rules about how<br/> this is approached and the following is just ideas: 
   - The specification can be written directly into tickets/cards
   - The specification can be written on Confluence pages and tickets can refer to them. 
   - The specification can be high-level or low-level and technical or non-technical
      <br/>
<br/>
### **Task break-down and delegation**
Split the work in tickets.

Find out which developers should be involved in which tasks and assign priority. Delegation is normally most<br/> efficiently done by the lead splitting tasks on developers but other approaches can work as well (for instance<br/> developers picking themselves from a board). 
      <br/>
<br/>

### **Coordination**
If tasks requires coordination among developers, you have to handle that part. Here are some thoughts about how that is done: 
  - Prefer peer-to-peer communication over group communication. Hence, don’t use daily meetings for such things. <br/>Consider more light-weight approaches such as: 
    - Create a slack-thread with the two involved developers and ask them to coordinate. 
    - Write in the ticket to one developer “Ping Peter when you get to this ticket to get further explanation”
    - Write in the ticket “WAIT FOR OK FROM PETER” to indicate that the ticket is waiting for some other person to do<br/>  some thing. 
    - Arrange a meeting with the involved developers. 
          <br/>
<br/>
### **Verification and feedback**
The lead is the most important person to verify implemented features and give feedback. The following are core<br/> principles around verification and feedback: 
  - the lead need to spend considerable amount of time on testing during the sprint. 
  - developers need to deliver code continuously throughout the sprint to avoid verification to be piled up. 
  - the lead must both verify behavior and quality
   <br/>
<br/>
### **Test case and seed data development**
As part of the sprint cycle manual test-cases must be written, either by the lead or by some other member of the team. Test-cases should be written in a way that effectively tests the system with a minimum of effort. 

Test-cases will also allow new-comers to quickly learn about how the platform works. 
   <br/>
<br/>
### **Regression testing**
As part of the release process the lead must make sure proper regression testing is performed on each release.<br/> If possible automation should take care of the regression testing as much as possible. 
   <br/>
<br/>
### **Releasing**
Part of the sprint is to release new versions of the software. The release typically happens in the end of the sprint.
<br/>
<br/>
## Estimates

## Typical tasks for a project lead

## More about the sprint meeting

## More about the project workbook

## The quality assurance approach

## Manual test cases

## The daily meeting

## About Minutes of Meetings (MoM)

# About documentation

## Why documentation is important

## Documentation principles

## The recommended documentation structure

## Standard documents


Our ways of working in one convenient, evolving place.

link to another page: [click](pages/example2.md)
