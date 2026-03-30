# platform / AWS Well-Architected source manifest

## Scope

- Domain: architecture trade-offs, operational readiness, reliability review, and cloud-operating patterns
- Source family: official AWS Well-Architected documentation
- Public role: provenance anchor for architecture reasoning, readiness, continuity, and some platform-governance assets

## Official source basis

- AWS Well-Architected Framework: https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html
- AWS Well-Architected Tool and guidance: https://aws.amazon.com/architecture/well-architected/

## Canonical document classes anchored here

- architecture trade-off and decision artifacts
- operational readiness and production-readiness support artifacts
- continuity and platform baseline support material

## Validation Contract

- Supported source basis tokens: `AWS Well-Architected`, `AWS operational readiness`, `AWS operational runbooks`, `AWS design principles`, `AWS readiness`
- Allowed dimensions: `01_Governance_Method`, `03_Architecture_Security_Decision`, `04_Quality_Review_Control`, `05_Delivery_Change_Readiness`, `06_Platform_Delivery_Automation_AI_Operations`, `07_Operations_Incidents_Continuity`, `08_Knowledge_Documentation_Continuous_Improvement`
- Authority level: `implementation-guidance`

## Notes

- AWS is used here as an architecture and operational-practice source family, not as a claim of AWS-only applicability.
- When paired with Microsoft Learn or Google SRE, this manifest contributes specific readiness and trade-off guidance.
- Use this manifest as supporting guidance for continuity only when the downstream artifact already has a primary continuity source family such as NIST continuity or ISO 22301.

## Source Attribution

- Source manifests: self
- Primary source basis: AWS Well-Architected documentation
- Alignment mode: `guided-synthesis`
- Reviewed on: 2026-03-30
