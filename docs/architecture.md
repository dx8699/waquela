# Architecture Overview

Waquela is the public product brand. CKD is the underlying technology. This overview describes the implemented boundaries at a product level; implementation source, private configuration, and operational resources are not included.

## Main Boundaries

| Boundary | Role |
| --- | --- |
| Human / AI client | The person directs the work. A supported AI client assists with available capabilities. |
| MCP / Web | Entry points for AI-assisted workflows and direct web use. Client capability sets can differ. |
| Identity and Authority | Authentication and scoped permissions determine which resources and actions are available. |
| Kernel | Checks and executes supported workflows within their admission and revision boundaries. |
| Cards / Proposals / Current | Cards hold accepted information; Proposals record suggestions; Current presents accepted information. |
| Publication | Exposes selected snapshots and checks their current availability. |
| Transaction Office / Inbox | Receives external information and presents it privately to the owner for review. |
| Firestore persistence | Stores product records and read projections behind the applicable access boundaries. |

## Authoritative Facts and Derived Views

Accepted information, saved Proposals, and publication history have different roles. A suggested change or an external submission is not accepted Card state.

Current and discovery lists are derived views of their underlying records. A discovery index does not create access permission or replace authoritative availability checks.

## Revision Checks

Supported updates check the relevant accepted revision. This helps prevent a proposal based on an outdated Card or section from replacing newer accepted information.

The person still decides whether a supported change should be applied. Revision checks do not make an unsupported Proposal executable.

## Permission Boundaries

Private Card access and owner Inbox access require appropriate authority. Public viewing exposes an available publication snapshot, rather than the private Card behind it.

An external visitor can submit information through an available public Office. Visitor identity and reply details remain unverified, and the submission does not grant Card access or automatically change accepted information.

## Scope of This Overview

This is an overview of the bounded Beta workflows. General Relation and context systems, independent Activated Topology lifecycle management, arbitrary user-editable topologies, autonomous Agent execution, and spatial interaction are not presented as completed product capabilities.

Client behavior and production acceptance vary by workflow. The AI-connected Mixed Inbox version mismatch is unresolved; see the [Beta notes](beta.md).

[Product overview](overview.md) · [Current features](features.md) · [Return to README](../README.md)
