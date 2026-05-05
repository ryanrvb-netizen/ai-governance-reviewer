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

The goal was not to build a full compliance engine. The goal was to create a practical review tool that helps surface risk,
