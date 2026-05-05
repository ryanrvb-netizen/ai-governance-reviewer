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

## How to use

1. Open the live demo  
2. Enter basic information about an AI model used in underwriting  
3. Toggle governance controls (human review, explainability, audit trail, etc.)  
4. Click “Assess Model Risk”  
5. Review the risk rating, identified gaps, and recommended actions  

This simulates a lightweight governance review workflow before a model is approved for use.

## Why I built this

Insurance companies are increasingly using AI and predictive models in underwriting workflows, but these systems need to be explainable, reviewable, and auditable.

I built this project to show how underwriting domain knowledge can be translated into a usable governance workflow for non-technical stakeholders.

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

*No login required. Runs fully in the browser.*

## Built with

- HTML  
- CSS  
- JavaScript  

## Status

MVP complete. Future improvements could include exporting the governance artifact, adding model card fields, and expanding the assessment logic for additional insurance use cases.

## Limitations

This tool is a simplified, rule-based simulation of an AI governance review process.

It does not replace formal compliance review, legal analysis, or model validation processes. In practice, governance assessments would include deeper documentation, model testing, and regulatory review workflows.

The goal of this project is to demonstrate how governance frameworks (NIST AI RMF, NAIC guidance) can be translated into a usable workflow for early-stage review.
