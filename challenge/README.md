# ORDS Metadata Compliance Challenge
## Overview
The Open Regulation Document Standard (ORDS) is a UK governmnent standard for regulatory metadata. It aims to make regulatory documents easier to access, reuse, and index by providing a consistent set of mandatory and optional fields.  

ORDS metadata feeds into our Find Business Regulations (FBR) service, enabling businesses to locate and filter relevant guidance from across government.

This challenge invites developers to test ORDS compatibility for existing guidance on GOV.UK and regulator sites. We invite participants to build tools that:
* Extract metadata from HTML and PDF regulatory documents.
* Validate compliance with ORDS.
* Embed metadata using RDFa or JSON-LD.
* Transform metadata into machine-readable formats.
* Enable multi-language support across English and Welsh.
* Provide feedback on usability and implementation.

## Objectives
* Validate ORDS metadata requirements.
* Explore embedding strategies for HTML and PDF.
* Assess paracticality for regulators and developers.
* Gather feedback to improve ORDS.

## Tasks
1. **Extract**  

Select a subset of regulatory documents from GOV.UK or a regulator site and extract mandatory and/or optional ORDS fields (see <Link> for the ontology).

2. **Validate**  

Implement a validator that checks for the presence of mandatory fields, correct formats, and logical relationships. Evaluate the classification metrics using different approaches.

3. **Embed**  

Embed ORDS metadata in HTML using RDFa or JSON-LD. Provide companion metadata files for PDFs.

4. **Transform**  

Output metadata in JSON-LD for APIs or Turtle (RDF) for linked data.

Bonus: Create a searchable index of documents using extracted metadata.

5. **Feedback**  

Submit a short report of issues encountered and suggestions for improving ORDS scheme or guidance.  

## Example Dataset
**HTML Pages:** GOV.UK-style regulatory guidance pages.  
**PDFs:** Sample regulatory documents with embedded headings.  
  
Provided in /data folder:
* sample-html/ (3 GOV.UK-style pages)
* sample-pdf/ (3 PDFs)
* ords-schema.ttl (ORDS ontology in Turtle format)

## Submission
Fork this repo.  

Complete tasks in /challenge folder.  

Add your feedback report in /feedback.  

Submit a pull request.

Refer to [contribute.md](../contribute.md) for further details on how to contribute
