# governance / NIST auditability source manifest

## Scope

- Domain: audit trails, traceability, log management, and tamper-evident governance records
- Source family: NIST logging and auditability guidance, centered on NIST SP 800-92
- Public role: provenance anchor for audit-trail and traceability artifacts that explicitly use NIST log-management semantics

## Official source basis

- NIST SP 800-92 Guide to Computer Security Log Management PDF: https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-92.pdf
- NIST SP 800-53 Rev. 5 security and privacy controls catalog landing page: https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final

## Canonical document classes anchored here

- audit-trail and traceability policies
- governance records that explicitly require log-management and non-repudiation controls

## Validation Contract

- Supported source basis tokens: `NIST auditability`, `NIST traceability`, `SP 800-92`, `audit trail`, `log management`
- Allowed dimensions: `01_Governance_Method`, `10_Risk_Exceptions_Traceability`
- Authority level: `aligned-semantics`

## Notes

- This manifest is bounded to logging, auditability, and traceability semantics.
- It should not be used as a proxy for incident handling, generic risk management, or service continuity.

## Source Attribution

- Source manifests: self
- Primary source basis: NIST SP 800-92 and related NIST auditability guidance
- Alignment mode: `guided-synthesis`
- Reviewed on: 2026-03-30
