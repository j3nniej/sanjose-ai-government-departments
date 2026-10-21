# Who Handles This?: AI for finding the right public agency

**Client:** City of San José — multilingual public-service navigation  
**Team:** [Add team member names], Aug–Oct 2026  
**My part:** I built a multilingual service-routing prototype and prepared a City pitch documenting its capabilities, a tested failure and mitigation, and deployment requirements.

## The problem

Residents may not know whether the City, County, or State handles a notice or everyday problem. Public directories can expect residents to know the department name before they know where to turn.

## What we built

- Residents describe a notice or problem in their own words. AI extracts the issue, requested action, supporting quote, and uncertainty; curated rules check the recommendation against supported public services.
- Residents see a recommended agency, supporting evidence, official sources, and a next step. They can return to saved reports.
- Residents decide whether to contact an agency. Ambiguous reports may need clarification or simulated staff review; the prototype does not file an official City case.

## What we found

The first synthetic language-parity check met developer expectations for **5 of 7 language variants**. One failure involved the German input “Mein Führerschein ist abgelaufen.” The first run incorrectly asked, “Möchten Sie Ihren Führerschein erneuern oder ersetzen?” even though the report says the driver’s license has expired.

The team tightened multilingual service-and-action guidance and supporting-quote checks. In a later run, all **7 of 7** language variants met developer-authored expectations, including the DMV renewal example. These runs use a development corpus; they do not establish independent accuracy, resident outcomes, or language equity.

## What I would do next

No resident or City-staff usability sessions are documented. I would run consented, multilingual sessions to learn whether residents can understand and use the recommended next step before considering a live pilot.

## Limitations

Who Handles This? is a prototype, not an official City of San José service. Its recommendations are not official decisions, and it does not submit cases to government agencies. Before any live resident pilot, City privacy and security owners would need to approve how real resident text is collected, processed, accessed, retained, and deleted, along with incident-response procedures.
