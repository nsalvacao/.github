# risk / NIST RMF source manifest

## Scope

- Domain: risk registers, control exceptions, risk treatment, and governance records that explicitly use NIST risk-management framing
- Source family: NIST Risk Management Framework guidance, centered on NIST SP 800-37 Rev. 2
- Public role: provenance anchor for risk-governance artifacts that rely on NIST RMF terminology and risk-based control treatment

## Official source basis

- NIST SP 800-37 Rev. 2 Risk Management Framework landing page: https://csrc.nist.gov/pubs/sp/800/37/r2/final
- NIST SP 800-37 Rev. 2 PDF: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r2.pdf

## Canonical document classes anchored here

- risk register artifacts with NIST RMF framing
- exception and deviation records that use NIST-style control tailoring and risk acceptance semantics
- risk and control-governance support records where NIST RMF is a named primary source family

## Validation Contract

- Supported source basis tokens: `NIST risk management`, `NIST RMF`, `SP 800-37`, `control exception handling`, `control tailoring`
- Allowed dimensions: `09_Project_Portfolio_Service_Governance`, `10_Risk_Exceptions_Traceability`
- Authority level: `aligned-semantics`

## Notes

- This manifest covers NIST RMF and risk-based control governance semantics, not incident-response handling.
- Use it instead of the incident-response manifest whenever the downstream artifact is about risk registers, exceptions, or control-treatment governance.

## Source Attribution

- Source manifests: self
- Primary source basis: NIST SP 800-37 Rev. 2 Risk Management Framework guidance
- Alignment mode: `guided-synthesis`
- Reviewed on: 2026-03-30
