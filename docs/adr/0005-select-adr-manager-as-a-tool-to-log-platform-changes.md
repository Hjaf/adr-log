# Select ADR-manager as a tool to log platform changes

* Status: accepted
* Date: 2023-11-24

## Context and Problem Statement

Many projects in the organisation depend on the platform and its state, however the platform vendor published changes to existing or new functionality frequently which may need to be configured in a particular way to be compliant.
All existing and new projects need to understand what or why certain capabilites are configured as they are to make the decision. 
Existing projects that may be affected by a change to the platform will have the necessary insight that includes the reasoning. 
When analysing history of a projects earlier design choices of earlier versions may be difficult to understand without backround. 
.. something something

## Considered Options

* Pure MADR template with a custom UI and automation for updating.
* Conventions in git history
* ADR-Manager

## Decision Outcome

Chosen option: "Pure MADR template with a custom UI and automation for updating.", because Easier to integrate with architecture contracts, techonolgy lifecycle and radars etc
