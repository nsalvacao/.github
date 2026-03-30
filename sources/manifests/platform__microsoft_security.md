# platform / Microsoft security source manifest

## Scope

- Domain: threat modeling, security review, and security architecture guidance
- Source family: Microsoft security guidance, including STRIDE-oriented threat-modeling material
- Public role: provenance anchor for security architecture artifacts where Microsoft security guidance materially applies

## Official source basis

- Microsoft SDL threat modeling guidance: https://learn.microsoft.com/security/engineering/threat-modeling-tool
- Azure security best practices and patterns: https://learn.microsoft.com/azure/security/fundamentals/best-practices-and-patterns
- Azure Well-Architected Framework security pillar: https://learn.microsoft.com/azure/well-architected/security/

## Canonical document classes anchored here

- threat models that explicitly use STRIDE semantics
- security architecture review and supporting security-control artifacts

## Validation Contract

- Supported source basis tokens: `Microsoft STRIDE`, `STRIDE`, `Microsoft security`, `Azure security`, `Microsoft threat modeling`
- Allowed dimensions: `03_Architecture_Security_Decision`, `06_Platform_Delivery_Automation_AI_Operations`, `10_Risk_Exceptions_Traceability`
- Authority level: `implementation-guidance`

## Notes

- This manifest supports Microsoft security semantics and STRIDE-style threat modeling. It does not replace OWASP source families where an artifact explicitly claims OWASP ASVS or OWASP threat-modeling structure.

## Source Attribution

- Source manifests: self
- Primary source basis: Microsoft security and threat-modeling guidance
- Alignment mode: `guided-synthesis`
- Reviewed on: 2026-03-30
