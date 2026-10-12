# Waquela Overview

**Your AI. Shared Possibilities.**

Your AI works with you.<br>
Waquela helps you work with others.

Waquela is an experimental, human-directed workspace powered by CKD. It helps people work together on a shared matter using their own AI, organize information, review proposed changes, and share selected information with clear permission boundaries.

## One Matter. Multiple People. Their Own AI.

### Example: Buying a Used Car

The participants in this example are fictional.

- A buyer uses ChatGPT to organize a car purchase in a Waquela Card and publishes selected requirements.
- A seller using Claude can review the public information and submit an offer through an available submission path.
- An inspector can contribute a vehicle report.
- A family member can provide advice through their own AI-assisted workflow.

The buyer reviews the incoming information, compares proposals, and decides what to accept. Each participant retains control of their own information and decisions.

```text
Buyer + ChatGPT
    |
    v
Purchase Card
    |
    v
Publish Selected Requirements
    |
    +---- Seller + Claude ---- Offer
    |
    +---- Inspector ---------- Report
    |
    +---- Family Member ------ Advice
    |
    v
Transaction Office / Inbox
    |
    v
Buyer + AI Review
    |
    v
Human Decision
    |
    v
Supported Proposal / Apply
    |
    v
Updated Current
```

Offers, reports, and advice remain external submissions for review. Updating Current requires a supported Proposal and explicit Human authorization to Apply; incoming information is not automatically converted into Card facts, and a purchase is not automatically completed.

This scenario combines existing Waquela Beta capabilities with an illustrative multi-party workflow. Individual interaction paths have been implemented and tested, while the complete used-car transaction scenario has not yet undergone end-to-end acceptance.

The implemented and tested foundation includes Cards, Publication, Public Discovery, Transaction Offices, Submissions, Inbox, Proposal / Apply, and two-person, multi-AI transaction interactions. Continuous collaboration among three or more people and the complete used-car workflow have not yet undergone end-to-end acceptance. This example makes no claim of automated matching, verified vehicle inspections, identity verification, payments, escrow, or guarantees.

Buying a Used Car is also the planned narrative for the future product walkthrough video. No video has been produced for this showcase update.

## Cards, Proposals, and Current

A **Card** organizes a matter using Markdown-backed sections and structured information. You can discover your Cards and read their **Current** view: a presentation of the information already accepted in that Card.

A **Proposal** records a suggested change for review. You decide whether to authorize a supported change. Saved suggestions can be useful even when they are not executable. A Proposal does not update Current simply because it exists.

Supported Apply operations use revision checks. They currently cover Card titles, Node facts, and Markdown section bodies, rather than arbitrary state changes.

## Share Selected Information

Private Cards require appropriate permission. Owners can publish selected snapshots for public viewing and withdraw their availability through Waquela.

Available publications can be browsed without signing in. Withdrawal does not remove historical records or copies someone has already obtained.

## Receive Information Through an Office

A personal Transaction Office gives external visitors a place to submit information to its owner. Submissions appear in the owner's private Inbox for Human review.

Visitor identity and reply methods are self-declared and unverified. Submissions do not automatically modify Cards, establish trusted identities, or become accepted changes.

## Work with a Supported AI Connection

An AI assistant can help read, organize, and propose changes through supported CKD Beta MCP capabilities. You direct the workflow and authorize supported changes. Capabilities vary by client and setup.

ChatGPT has been Human-tested for representative workflows. Claude is supported with incomplete workflow acceptance; Grok and Codex remain limited / experimental. Some workflows remain under validation; see the [feature boundaries](features.md) and [Beta notes](beta.md).

## Who This Showcase Is For

This introduction is for AI users, developers, product researchers, and potential Beta testers. It explains the product and its current boundaries; the CKD implementation source is not included.

[Visit the Waquela website](https://digist-sg-beta.web.app). Access and features may be limited during the experimental Beta period; broad public recruitment is on hold.

[Read the Beta notes](beta.md) · [See current features](features.md) · [Return to README](../README.md)
