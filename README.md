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

## Dependencies, risks and decisions

# Project management practices

## Introduction to the lead role and the sprint cycle
### **The sprint meeting**

The sprint meeting is a crucial part of our development process. It marks the end of a sprint and the beginning of a new sprint.

A **Sprint Report** is sent out before the meeting and a **Sprint Meeting Summary** is sent out immediately after. Let us go through the three parts: report - meeting - summary. 
   - The sprint report
     - Purpose of the sprint report



   - A sprint meeting is performed with the following agenda: 

     - Demo - presenting what has been achieved

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
