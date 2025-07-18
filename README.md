# Placements Data Standard

Status: Initial Draft
Effective Date: 2025-07-18

## Purpose  

This Placement Standard will standardise some of the data collected about children in care at the point they are referred for placement and the point where a placement is agreed. The goal of this standard is to support better analysis of placement sufficiency at the local and regional level, tackle high costs in the care market and improve outcomes for children in care.    

<a href="https://github.com/SocialCareData/placements-standard/issues/new?template=content_issue.yml&title=Issue+regarding+Placements+Spec+Purpose" class="web-button" target="_blank">Raise an issue about Purpose</a>

## Scope  

**The standard would help LAs:**  

* Better understand placement sufficiency: what provision is needed where, and at what notice    
* Speak the same data ‘language’ as neighbours to form regional view of sufficiency gaps    
* Distinguish between different drivers of placement costs (e.g. escalating need, displacement from foster to residential, increased referrals etc)    
* Make like-for-like comparisons of placement cost    
* Forecast future demand for different placement types  

**It will be designed to:**  

* Create the smallest possible burden on frontline staff   
* Minimise the amount of change required by LAs for adoption   
* Make use of existing data being gathered  

**The standard will *not*:**  

* Preclude LAs from gathering additional data fields to suit local needs   
* Impose a process for how the data is gathered in each LA (i.e. some LAs may embed these fields in a CMS referral form, others may gather this in excel etc)    
* Be designed to support home search    
* Establish a national contract for placements   
* Establish a standard referral form    
* Mandate architecture or functionality changes for CMS suppliers  

<a href="https://github.com/SocialCareData/placements-standard/issues/new?template=content_issue.yml&title=Issue+regarding+Placements+Spec+Scope" class="web-button" target="_blank">Raise an issue about Scope</a>

## Key assumptions  

There are a number of assumptions we have made in the design of the proposed data standard. We assume:  

* Placement teams rather than social workers or finance teams will either directly enter or ‘own’ the data suggested. Where they are not directly entering the data (e.g. because they are taking it from a referral form), they will ensure it’s fidelity to the standard    
* While total cost agreed at IPA is often an inaccurate representation of true cost, it is ‘accurate enough’ to enable useful life-for-like cost comparisons and regional cost analysis.  

The additional work for a placement worker of entering this data is approximately 90 seconds (based on initial pilots of this data model) 

<a href="https://github.com/SocialCareData/placements-standard/issues/new?template=content_issue.yml&title=Issue+regarding+Placements+Spec+Key+Assumptions" class="web-button" target="_blank">Raise an issue about Key Assumptions</a>

## Development principles  

* **Privacy By Design:** The data specifications must be developed to allow controlled access to data preserving privacy by default.   
* **Security By Design:** The specifications must ensure information flow between parties adheres to security and confidentiality best practices.   
* **Unambiguous Personal Data Representation:** The data specifications must enable the unambiguous identification of individuals and ensure that data about a person is always accurately linked to the person.   
* **Enabling Quality Data:** The data specifications must define clear expectations for data types, formats, and permissible values, enabling systems to generate, exchange, and consume high-quality, reliable information that is fit for its intended purpose.   
* **Collaborative Data Exchange:** The data specifications must promote seamless interoperability and collaborative data sharing among stakeholders.   
* **Simplicity**: The data specifications must prioritise ease of understanding and implementation. Complexity should only be introduced when to address specific professional or regulatory requirements.   
* **Reuse Existing Standards**: Where possible, specifications should align with UK implementations of HL7 FHIR, an established international standard widely used in health systems and increasingly in social care. 

<a href="https://github.com/SocialCareData/placements-standard/issues/new?template=content_issue.yml&title=Issue+regarding+Placements+Spec+Development" class="web-button" target="_blank">Raise an issue about Development</a>
