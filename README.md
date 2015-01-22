A way to import and execute basic process models using MarkLogic's CPF feature.

## Why? Just... Why!?!

This project aims to provide a new useful way to define CPF Pipelines. This means providing a way to model CPF pipelines
and then take those models to generate a pipeline. Rather than create a custom modelling tool just for CPF, it is easier
to use one of the many process model formats and existing tools, and provide a palette of MarkLogic specific actions for
these tools.

This functionality can also be used by MarkLogic customers to implement extended workflow functionality. BPMN2 model
import and standard activity types are supported, allowing implementation of Content-Centric Workflow.

## Information on MarkLogic Workflow
- Overview
 - Product overview - OVERVIEW.md <-- START HERE!!!
 - Technical overview - TECHINTRO.md
- For workflow modellers/implementors
 - Installation - INSTALL.md
 - BPMN2 modelling - MODELLING.md
 - CPF pipeline modelling - TBC
- For developers
 - Linking a UI/application to MarkLogic Workflow - RESTAPI.md
 - Creating your own Activity types - TBC
 - For upcoming features see SPRINTS.md

- INSTALL.md - How to install MarkLogic Workflow in to a MarkLogic Server
- MODELLING.md - How to import a workflow model in to MarkLogic Workflow
- RESTAPI.md - How to create and interact with a running process
- DESIGN.md - The design behind the Workflow Engine