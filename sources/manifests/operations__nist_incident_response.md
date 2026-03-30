# operations / NIST incident response source manifest

## Scope

- Domain: incident declaration, triage, escalation, analysis, coordination, containment, recovery, and post-incident handling
- Source family: NIST incident response guidance, centered on NIST SP 800-61 Rev. 3
- Public role: provenance anchor for incident response policies, plans, reports, playbooks, and learning artifacts where federal incident-response semantics materially apply

## Official source basis

- NIST SP 800-61 Rev. 3 Computer Security Incident Handling Guide landing page: https://csrc.nist.gov/pubs/sp/800/61/r3/final
- NIST SP 800-61 Rev. 3 PDF: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r3.pdf

## Canonical document classes anchored here

- incident management policies and response plans
- incident reports, timelines, and coordination playbooks
- escalation, recovery, and root-cause analysis artifacts that explicitly reuse NIST incident-response phases

## Validation Contract

- Supported source basis tokens: `NIST SP 800-61`, `NIST SP 800-61r3`, `NIST SP 800-61 Rev. 3`, `NIST incident response`, `incident response guidance`
- Allowed dimensions: `01_Governance_Method`, `05_Delivery_Change_Readiness`, `07_Operations_Incidents_Continuity`, `08_Knowledge_Documentation_Continuous_Improvement`, `09_Project_Portfolio_Service_Governance`, `10_Risk_Exceptions_Traceability`
- Authority level: `normative`

## Notes

- This manifest is intentionally bounded to incident-response semantics. It must not be used as a catch-all proxy for continuity, generic risk governance, or unrelated security design guidance.

## Source Attribution

- Source manifests: self
- Primary source basis: NIST SP 800-61 Rev. 3 Computer Security Incident Handling Guide
- Alignment mode: `direct-adaptation`
- Reviewed on: 2026-03-30
