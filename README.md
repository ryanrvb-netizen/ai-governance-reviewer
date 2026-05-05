# AI Model Governance Reviewer

A browser-based tool for reviewing governance risk in AI models used in insurance underwriting.

## What it does

The AI Model Governance Reviewer helps a non-technical compliance or governance user assess whether an AI model has basic controls in place before it is used to support underwriting decisions.

The user enters information about:

- Model purpose
- Data used
- Human review
- Explainability
- Audit trail
- Adverse action documentation
- Bias testing
- Model ownership

The tool then produces:

- Risk rating (Low / Moderate / High)
- Key governance gaps
- Plain-English governance summary
- Recommended actions
- NIST AI RMF framework mapping

## Why I built this

Insurance companies are increasingly using AI and predictive models in underwriting workflows, but these systems need to be explainable, reviewable, and auditable.

I built this project to show how underwriting domain knowledge can be translated into a simple governance workflow for non-technical users.

The goal was not to build a full compliance engine. The goal was to create a practical review tool that helps surface risk, missing controls, and documentation gaps before a model is relied on in a regulated decision process.

## Frameworks referenced

- NIST AI Risk Management Framework
- NAIC Model Bulletin on AI Systems
- Colorado SB 21-169

## Key features

- Rule-based risk assessment
- Plain-English governance summary
- Gap identification
- Recommended remediation steps
- NIST AI RMF mapping across GOVERN, MAP, MEASURE, and MANAGE
- Runs fully in the browser
- No login or backend required

## Live demo

https://ai-governance-reviewer.vercel.app

## Built with

- HTML
- CSS
- JavaScript

## Status

MVP complete. Future improvements could include exporting the governance artifact, adding model card fields, and expanding the assessment logic for additional insurance use cases.
