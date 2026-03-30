# platform / SLSA source manifest

## Scope

- Domain: build provenance, software supply-chain integrity, and trusted build pipelines
- Source family: official SLSA framework guidance
- Public role: provenance anchor for build-provenance and supply-chain traceability artifacts that explicitly use SLSA concepts

## Official source basis

- SLSA overview: https://slsa.dev/
- SLSA specification: https://slsa.dev/spec/v1.0/
- SLSA provenance model: https://slsa.dev/spec/v1.0/provenance

## Canonical document classes anchored here

- artifact and build provenance records
- supply-chain traceability records for build pipelines

## Validation Contract

- Supported source basis tokens: `SLSA`, `Supply-chain Levels for Software Artifacts`, `build provenance`, `software supply-chain`
- Allowed dimensions: `06_Platform_Delivery_Automation_AI_Operations`
- Authority level: `normative`

## Notes

- This manifest is intentionally bounded to provenance and software supply-chain integrity semantics.
- It should not be used as a generic proxy for CI/CD, deployment automation, or architecture governance.

## Source Attribution

- Source manifests: self
- Primary source basis: official SLSA framework guidance
- Alignment mode: `direct-adaptation`
- Reviewed on: 2026-03-30
